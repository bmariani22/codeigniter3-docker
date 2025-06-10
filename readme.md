# Codeigniter + Docker
Este proyecto provee un contenedor base para el desarrollo de una aplicación PHP utilizando [Codeigniter 3](https://codeigniter.com/userguide3/general/welcome.html) como framework principal.

# Uso
## Clonar repositorio
Clonar este repositorio utilizando:
```bash
git clone https://github.com/bmariani22/codeigniter3-docker.git /path/to/folder/
```

## Build
Para buildear la imagen utilizar:
```bash
docker build -t codeigniter3-docker .
```

Esto crea una imagen en el propio directorio de la aplicación

## Deploy
Para correr la imagen:
```bash
docker run -d -p 8080:80 codeigniter3-docker
```

Esto crea un contenedor en segundo plano que puede ser accedido en http://8080:80