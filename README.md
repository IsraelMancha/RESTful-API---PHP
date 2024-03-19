# API RESTful en PHP

Esta es una API RESTful simple escrita en PHP que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos de posts.

## Funcionalidades

- Listar todos los posts.
- Obtener los detalles de un post específico.
- Crear un nuevo post.
- Actualizar un post existente.
- Eliminar un post.

## Requisitos

- PHP >= 7.0
- Servidor web (por ejemplo, Apache o Nginx)
- Base de datos MySQL (u otro sistema compatible con PDO)

## Instalación

1. Clona o descarga este repositorio en tu máquina local.
2. Configura tu servidor web para que apunte al directorio raíz del proyecto.
3. Importa la base de datos `blog.sql` proporcionada en tu sistema de gestión de base de datos.

## Uso

- Accede a la API a través de las siguientes rutas:
  - `GET /posts`: Lista todos los posts.
  - `GET /posts/{id}`: Obtiene los detalles de un post específico.
  - `POST /posts`: Crea un nuevo post.
  - `PUT /posts/{id}`: Actualiza un post existente.
  - `DELETE /posts/{id}`: Elimina un post.

## Configuración

- Puedes configurar los detalles de la base de datos en el archivo `config.php`.
- Asegúrate de tener los permisos adecuados para que PHP pueda escribir en la base de datos si es necesario.

## Contribución

¡Las contribuciones son bienvenidas! Si encuentras un error o deseas agregar nuevas características, no dudes en abrir un problema o enviar una solicitud de extracción.
