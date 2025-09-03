# Servicio Student03

Este servicio corresponde al estudiante **Student03** dentro del laboratorio *Docker Lab: Build Your Own Service*.
Elaborado por: Ricardo Erazo

---

## Cambios realizados
- Se creó la carpeta `services/student03/`.  
- Se agregó un `Dockerfile` y la aplicación dentro de `app/`.  
- Se configuró el servicio para escuchar en el puerto interno **8080** y exponerse en el host en el puerto **8103**.  
- Se implementaron dos endpoints:  
  - `/` → devuelve el nombre del estudiante **Student03**.  
  - `/health` → devuelve el texto `ok`.  

---

## Cómo ejecutar el servicio

1. Desde la raíz del proyecto, construye y levanta los contenedores:  
   ```bash
   docker compose up --build -d

2. Comprobarlo buscando en el navegador: localhost:8103 y luego localhost:8103/health
