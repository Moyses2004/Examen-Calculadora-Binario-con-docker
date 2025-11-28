# Examen-Calculadora-Binario-con-docker
# Calculadora de Números Binarios con Python y Docker

Este proyecto es una aplicación web realizada con **Python (Flask)** y ejecutada dentro de un contenedor **Docker**.  
La aplicación permite ingresar dos números binarios y muestra como salida:

- Suma binaria  
- Multiplicación binaria  


##  Tecnologías utilizadas
- Python 3.12  
- Flask 3.0  
- Docker  
- HTML + CSS embebido  

---

##  Estructura del proyecto
 app.py
 Dockerfile
 requirements.txt
 README.md

 
---

##  Cómo ejecutar el proyecto con Docker

## 1. Construir la imagen
``bash
docker build -t binarios-app .

---
##  Ejecutar el contenedor

docker run -d -p 5000:5000 --name binarios-contenedor binarios-app

### Abrir la aplicación

http://localhost:5000

## bajar Docker

docker stop binarios-contenedor
docker rm binarios-contenedor


## universidad tecnologica de honduras
## Freddys Moyses Villanueva Cortes
## 202330010315
## Arquitectura de computadoras
