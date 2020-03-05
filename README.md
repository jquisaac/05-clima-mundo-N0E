## Aplicacion del Clima - Curso Node

Recuerden ejecutar ```npm installa``` para las liberias

### npm's instalados

```
npm i --save yargs
npm i axios
```

### Servicios utilizados

Se requiere registro en este sitio web:

https://rapidapi.com/dev132/api/city-geo-location-lookup

Se puede iniciar secion con git.

Servicios:

Obtener coordenada:
Get: https://devru-latitude-longitude-find-v1.p.rapidapi.com/latlon.php?location=New+York

Obteber clima:
Get: api.openweathermap.org/data/2.5/weather?lat=35&lon=139&appid=045314753c16625be483966eb4ced4d5

### Ejemplo:

```
node app -d <<direccion>>
node app -d "New York"
```



