# Music Manager

Music Manager es un proyecto backend para gestionar una lista de música. Permite organizar, crear, borrar y realizar operaciones CRUD en archivos de música. Utiliza Node.js, Express y MongoDB para proporcionar una API robusta y funcional.

## Características

- Listar archivos MP3 desde un directorio dado.
- Proveer una API para acceder a la lista de archivos.
- Permitir la búsqueda y filtrado de archivos.
- Guardar metadatos en una base de datos.

## Requisitos

- Node.js
- MongoDB

## Instalación

### 1. Configuración del Entorno

1. Instalar Node.js: Si no tienes Node.js instalado, descárgalo e instálalo desde [nodejs.org](https://nodejs.org/).
2. Clona el repositorio y navega a la carpeta del proyecto:

    ```bash
    git clone https://github.com/coderunner86/proyecto_4.git
    cd proyecto_4
    ```

3. Configura el proyecto:

    ```bash
    npm init -y
    npm install express mongoose multer fs-extra
    npm install node_modules
    ```

### 2. Creación del archivo de environment
    
    ```bash
    PORT=5000
    MONGODB_URI=mongodb://localhost:27017/music-manager
    ```

### 3. Ejecutar el proyecto:

    ```
    node server.js
    ```
