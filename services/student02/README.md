# 🐳 Servicio Student02

Este servicio corresponde al estudiante **Student02** dentro del laboratorio *Docker Lab: Build Your Own Service*.  

---

## 🔧 Cambios realizados
- Se creó la carpeta `services/student02/`.  
- Se agregó un `Dockerfile` y la aplicación dentro de `app/`.  
- Se configuró el servicio para escuchar en el puerto interno **8080** y exponerse en el host en el puerto **8102**.  
- Se implementaron dos endpoints:  
  - `/` → devuelve el nombre del estudiante **Student02**.  
  - `/health` → devuelve el texto `ok`.  

---

## 🚀 Cómo ejecutar el servicio

1. Desde la raíz del proyecto, construye y levanta los contenedores:  
   ```bash
   docker compose up --build -d
