# Heroes Backend 🦸‍♂️🦸‍♀️

Backend falso basado en `json-server`, ideal para prácticas con **Angular**, **React**, **Vue** o cualquier frontend que necesite una API REST rápida y sencilla.

Este repositorio utiliza **my-json-server**, por lo que no necesitas instalar nada para probarlo en remoto.


## 🌐 API remota disponible

Base URL:

```url
https://my-json-server.typicode.com/borilio/heroes-backend
```

## 📦 Recursos disponibles

Este backend contiene dos colecciones principales:

* `heroes`
* `users`

## 🚀 Endpoints disponibles

### 🦸 Heroes

Obtener todos los héroes:

```http
GET /heroes
```

Ejemplo real:

```url
https://my-json-server.typicode.com/borilio/heroes-backend/heroes
```

Obtener héroe por ID:

```http
GET /heroes/1
```

Filtrar por universo:

```http
GET /heroes?universe=Marvel
GET /heroes?universe=DC
```

Filtrar por activos:

```http
GET /heroes?active=true
```

Buscar por nombre:

```http
GET /heroes?name=Batman
```

Ordenar por poder:

```http
GET /heroes?_sort=power&_order=desc
```

Limitar resultados:

```http
GET /heroes?_limit=5
```

### 👤 Users

Obtener todos los usuarios:

```http
GET /users
```

Ejemplo real:

```
https://my-json-server.typicode.com/borilio/heroes-backend/users
```

Obtener usuario por ID:

```http
GET /users/1
```

Usuarios activos:

```http
GET /users?active=true
```

Buscar por email:

```http
GET /users?email=nick.fury@shield.gov
```

## ⚠️ Importante sobre my-json-server

Este servicio está pensado para pruebas rápidas, por lo que:

✅ Permite peticiones `GET` sin problema
⚠️ `POST`, `PUT`, `PATCH` y `DELETE` son aceptados pero no guardarán cambios permanentes.

Si necesitas persistencia real, usa `json-server` en local.


## 🧪 Ideal para practicar

Este backend es perfecto para trabajar:

* HttpClient en Angular
* CRUD básico
* Observables
* Filtros y búsquedas
* Tablas dinámicas
* Formularios conectados a API

## 👨‍💻 Autor

Repositorio creado para prácticas y aprendizaje.

[https://github.com/borilio/heroes-backend](https://github.com/borilio/heroes-backend)
