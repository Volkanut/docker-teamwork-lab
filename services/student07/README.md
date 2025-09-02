Miguel Angel Muñoz Piñeros - 2274590

# Go simple service

Un servicio básico en Go utilizando el framework [Gin](https://github.com/gin-gonic/gin).  
La instancia expone un mensaje y un endpoint de healthcheck.

Para ejecutarlo con docker directamente:

```bash
docker build -t go-simple-service .

docker run --rm -p 8080:8080 go-simple-service

curl http://localhost:8080/ # O usar simplemente el navegador
# Respuesta: "Miguel sends greetings from Go!"

curl http://localhost:8080/health
# Respuesta: "ok"
```