### Sistema de Gestión de Usuarios

#### Descripción

Has sido contratado por una empresa para desarrollar un sistema de gestión de usuarios que permita realizar las siguientes operaciones:

- [x] Crear usuario: Debe permitir agregar un nuevo usuario con la siguiente información:
      a. Nombre completo
      b. Correo electrónico
      c. Rol (puede ser "administrador", "usuario estándar" o "invitado")

- [x] Listar usuarios: Debe mostrar una lista de todos los usuarios registrados en el sistema.

- [x] Actualizar usuario: Debe permitir actualizar la información de un usuario existente,incluyendo su nombre, correo electrónico y rol.

- [x] Eliminar usuario: Debe permitir eliminar un usuario existente del sistema.

- Buscar usuario por correo electrónico: Debe permitir buscar un usuario por su correo electrónico y mostrar su información completa.

- [x] Autenticación y Autorización: Implementar un sistema de autenticación y autorización utilizando tokens JWT (JSON Web Tokens) para proteger las rutas de la API y restringir el acceso a ciertas operaciones según el rol del usuario.

### Instalación con docker-compose (recomendado)

```sh
docker-compose up -d
npm run dev
```

### Instalación manual

```sh
git clone
cd mern-tasks-auth
npm i
npm run build
npm start
```

> Se necesita tener mongoDB instalado y corriendo.

Asi mismo me gustaria mensionar que ciertos aspectos de la aplicacion no estan completos, como por ejemplo la actualizacion de usuarios y la busqueda de usuarios por correo electronico por falta de tiempo, pero la aplicacion cumple con los requerimientos minimos solicitados.

### Tecnologias utilizadas

- Node.js
- Express
- MongoDB
- JWT
- React
- Redux
- Materialize CSS
- Docker
- Docker-compose

Muchas gracias por la oportunidad de participar en este proceso de selección, quedo atento a cualquier comentario o sugerencia.
