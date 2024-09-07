# tcit-forum-frontend
Frontend para aplicación de foro con React y Redux - TCIT Challenge

# TCIT Challenge - Backend para Aplicación de Manejo de Posts

Aplicación para lectura, creación y eliminación de mensajes (posts). Backend (servidor) desarrollado con Ruby on Rails.
Desarrollado por [Mauricio Oyarzún](https://github.com/moyarzun).

## Requisitos

- Ruby (versión 2.7 o superior)
- Rails (versión 6.0 o superior)
- Node.js (versión 14 o superior)
- npm (versión 6 o superior)
- Base de datos (PostgreSQL recomendado)

## Instalación

1. Clonar el repositorio de GitHub:

    ```bash
    git clone https://github.com/tu-usuario/tcit-forum-backend.git
    cd tcit-forum-backend
    ```

2. Instalar las dependencias del proyecto:

    ```bash
    bundle install
    ```

3. Editar el archivo `config/database.yml` con los datos de conexión a la base de datos.

4. Asegurar que la base de datos esté en ejecución y accesible desde la ubicación del servidor.

5. Configurar la base de datos:

    ```bash
    rails db:create
    rails db:migrate
    ```

## Ejecución en Ambiente de Desarrollo

1. Iniciar la aplicación:

    ```bash
    rails s
    ```

2. Abrir navegador en [http://localhost:3001](http://localhost:3001)

## Ejecución en Ambiente de Producción

1. Configurar la base de datos para producción:

    ```bash
    RAILS_ENV=production rails db:create
    RAILS_ENV=production rails db:migrate
    ```

2. Iniciar el servidor en modo producción:

    ```bash
    RAILS_ENV=production rails s
    ```

3. Abrir navegador en [http://localhost:3001](http://localhost:3001)
