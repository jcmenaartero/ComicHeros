# Proyecto Final
Trabajo final de LMSGI, 1º ASIR

## Instalación y ejecución de la aplicación

Pasos a realizar para iniciar la aplicación

### Backend

En esta aplicación se utiliza una API simulada, que devuelve datos en formato JSON.
Para ello instalamos [JSON-Server](https://www.npmjs.com/package/json-server) de manera global:

```
npm install -g json-server
```

Luego en la carpeta que contiene el db.json, que seria nuestro Backend simulado,
iniciamos el servicio, con el sigiente comando:

```
json-server --watch db.json
```

### Frontend

En la carpeta del frontend ejecutar el comando:

```
npm install
```
Instala todas las librerias y dependencias de la aplicación.

Una vez tengamos instalado todo lo anterior y tengamos iniciado nuestro json-server,
ejecutamos en nuestro Frontend el siguiente comando:

```
ng serve -o
```

## Recursos utilizados

- Se han implementado componentes de [Angular Material](https://material.angular.io/).

- Mayoritariamente el responsive y la estructura de la aplicación esta hecha con [@angular/flex-layout](https://www.npmjs.com/package/@angular/flex-layout) de una forma básica.

- [Quicktype](https://app.quicktype.io/) es una aplicación web muy util para tipar archivos JSON en distintos lenguajes de programación. 



