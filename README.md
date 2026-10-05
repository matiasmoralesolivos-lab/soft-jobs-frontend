# Soft Jobs — Frontend

Aplicación frontend de Soft Jobs desarrollada con React y Vite.

[Ver aplicación online](https://soft-jobs-frontend-j0im.onrender.com)

## Tecnologías

* React
* Vite
* React Router
* Axios
* Bootstrap

## Funcionalidades

* Registro de usuarios.
* Inicio y cierre de sesión.
* Autenticación mediante JWT.
* Visualización del perfil del usuario autenticado.
* Navegación entre las distintas vistas de la aplicación.

## Instalación

Clonar el repositorio e instalar las dependencias:

```bash
npm install
```

## Ejecución

Iniciar el servidor de desarrollo:

```bash
npm run dev
```

La aplicación se ejecutará en la dirección indicada por Vite en la terminal.

## Conexión con el Backend

La URL de la API se encuentra configurada en:

```text
src/config/constans.js
```

El frontend utiliza los siguientes endpoints:

```text
POST /usuarios
POST /login
GET  /usuarios
```

## Estructura principal

```text
src/
├── components/
├── config/
├── contexts/
├── views/
└── App.jsx
```

La aplicación se conecta al backend mediante Axios y utiliza `sessionStorage` para almacenar el token de autenticación durante la sesión.
