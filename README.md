# BuggBlock
![image](https://github.com/JDAA4/BuggBlock/assets/116245157/65daf13c-2535-4d8d-affb-3b8539ea917c)

## Descripción

BuggBlock es una plataforma tipo blog personal donde los usuarios pueden compartir sus opiniones sobre diversas tecnologías. Los administradores pueden gestionar publicaciones y usuarios.

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/JDAA4/BuggBlock.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd BuggBlock
    ```
3. Configura tu entorno de desarrollo (asegúrate de tener PHP y un servidor web configurado).

## Uso

1. Inicia el servidor web y asegúrate de que el proyecto esté accesible.
2. Accede a la página principal del proyecto en tu navegador:
    ```
    http://localhost/BuggBlock/views/index.php
    ```

## Funcionalidades

### Usuarios

- **Inicio de sesión**: Los usuarios pueden iniciar sesión en la plataforma.
- **Gestión de usuarios**: Los administradores pueden crear, editar y eliminar usuarios.

### Publicaciones

- **Crear Publicaciones**: Los usuarios pueden crear nuevas publicaciones.
- **Editar Publicaciones**: Los usuarios pueden editar sus publicaciones existentes.
- **Eliminar Publicaciones**: Los usuarios pueden eliminar sus publicaciones.

## Archivos Relevantes

- [index.php](views/index.php): Página principal del proyecto.
- [login.php](views/login.php): Página de inicio de sesión.
- [administrador.php](views/administrador.php): Panel de administración.
- [cerrarSesion.php](controlls/cerrarSesion.php): Controlador para cerrar sesión.
- [publicaciones.php](models/publicaciones.php): Modelo para gestionar publicaciones.




