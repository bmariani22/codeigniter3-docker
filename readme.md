# Codeigniter + Docker
Este proyecto provee un contenedor base para el desarrollo de una aplicación PHP utilizando [Codeigniter 3](https://codeigniter.com/userguide3/general/welcome.html) como framework principal.

# Build
Para buildear la imagen utilizar:
```
docker build -t codeigniter3-docker .
```

# Deploy
Para correr el contenedor:
```
docker run -d -p 8080:80 codeigniter3-docker
```

Esto inicia la aplicación en segundo plano y puede ser accedida en http://8080:80