# POC API en Swoole y Lumen

_Docker-Compose para el api principal y el api de tipo de cambio_


### Instalación 🔧

```

git clone https://github.com/dantelibralato/api-poc-exec.git api-poc-exec;
cd api-poc-exec;
git clone https://github.com/dantelibralato/api-poc.git api-poc;
git clone https://github.com/dantelibralato/api-poc-tipo-cambio.git api-poc-tipo-cambio;

#Este proceso puede tardar por lo menos 10 minutos.
docker-compose up -d --build;

docker-compose logs;
docker-compose ps;

```


## Ejecutando las pruebas ⚙️


```

#API Tipo-Cambio
curl http://0.0.0.0:1215/api/v1/tipocambio/20100411


#API Principal
curl http://0.0.0.0:1214/api/v1/productos/1/2019/4/USD/pruebas


```


## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles



---
⌨️ con ❤️ por [dantelibralato](https://github.com/dantelibralato) 😊
