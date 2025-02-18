# FastAPI Docker App

Este proyecto es una API simple creada con FastAPI y desplegada en un contenedor Docker utilizando Uvicorn como servidor ASGI.

## Requisitos Previos
Antes de ejecutar la aplicación, asegúrate de tener instalados los siguientes programas:


- [Docker](https://www.docker.com/get-started)

## Instalación y Uso

 1. Descargar la imagen

 ```sh
  docker pull alexanderjrs/fastapi:latest 

 
 2. Ejecutar el contenedor 
  docker run -d --name fastapi -p 8000:8000 alexanderjrs/fastapi:latest 

 3. Abrir el navegador 
        
        http://localhost:8000/ 