# Imagem para testes com Cypress

Para generar una nueva imagen, basta correr el siguiente comando en la raiz del proyecto:

```bash
docker build -t micro-biblioteca -f cypress/Dockerfile .
```

Para ejecutar la aplicación completa via Docker
```bash
docker run -ti -p 3000:3000 -p 5000:5000 micro-biblioteca
```
