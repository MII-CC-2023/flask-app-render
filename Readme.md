# Flask APP 

Aplicación, hola mundo, en Flask, y su fichero Dockerfile para contenerizarla.

Para comprobar que es correcta podemos crear la imagen:

```
docker build -t flask-app .
```
y ejecutarla en un contenedor:

```
docker run -d --name app -p 8080:8080 flask-app
```