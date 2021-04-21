# qgis-server-mapproxy #

The repository demonstrates how to generate
raster tiles, statically or dynamically, using 
[Docker](https://www.docker.com/) container orchestration with:

* [QGIS Server v3](https://docs.qgis.org/3.16/en/docs/server_manual)
* [MapProxy v1](https://mapproxy.org/)
* [NGINX proxy server v1](https://www.nginx.com/)

It includes a reference implementation using a vector layer:
[natural earth's](https://www.naturalearthdata.com/) `ne_10m_land`.

## Getting Started

```
rm -rf mapproxy/cache/* && docker compose up
# browse to http://localhost:8080/mapproxy/demo/
```

## Credits

GEM/openquake created the great docker containers for mapproxy and qgis-server:

https://github.com/gem/oq-qgis-server


