# ACME

_Aplicaci贸n realizada con fines de prueba de conocimientos tecnicos para el cargo de desarrollador PHP en Grupo OET._

## Comenzando 馃殌

_Estas instrucciones le permitir谩n obtener una copia del proyecto en funcionamiento en su m谩quina local para prop贸sitos de pruebas._

### Instalaci贸n 馃敡
_Es necesario que ponga en marcha la aplicaci贸nn sobre una m谩quina con acceso a internet, debido a que contiene librerias importadas v铆a CDN, esto con el fin de un 贸ptimo funcionamiento._

_Verificar el archivo ubicado en la ruta: **app/database/acme_database_generator.sql** que es el archivo de backup para la generacion de la base de datos utilizada para esta aplicaci贸n y ejecutar el contenido como un query._

_Una vez ejecutado el script de generaci贸n de la base de datos, por favor verificar el archivo ubicado en la ruta: **app/config/config.ini** y parametrizar los datos respectivos para la conexion con el servidor MySQL en su maquina, los cuales son:_

```
1. host: Host del servidor MySQL (default localhost/127.0.0.1).
```
```
2. user: Usuario de conexion al servidor MySQL (default root).
```
```
3. password: Contrasena del usuario de conexion al servidor MySQL.
```
```
4. database: Nombre de la base de datos a utilizar (default acme).
```
```
4. port: Puerto de acceso al servidor de MySQL (default 3306).
```

_Una vez verificada la informaci贸nn de configuraci贸n, se podr谩 utilizar la aplicaci贸n de forma correcta._

## Construido con 馃洜锔?

* [PHP v7.4](https://www.php.net/manual/es/intro-whatis.php) - Lenguaje backend de la aplicaci贸n.
* [jQuery](https://api.jquery.com/) - Utilizado para interactuar con los elementos del DOM.
* [Ajax](https://api.jquery.com/jquery.ajax/) - Utilizado para el manejo de las peticiones POST/GET de los datos.
* [Bootstrap v5](https://getbootstrap.com/) - Utilizado para el dise帽o de las interfaces.
* [Bootstrap Icons](https://developers.google.com/fonts/docs/material_icons) - Utilizado para estilizar los botones.
* [SweetAlert2](https://sweetalert2.github.io/) - Utilizado para la generaci贸n de alertas din谩micas.
* [DataTables](https://datatables.net/) - Plug-in de jQuery utilizado para el control de las tablas HTML.

## Autor 鉁掞笍

* **Johann Esneider** - *Desarrollador de la aplicaci贸n* - [LinkedIn](https://www.linkedin.com/in/johannesneiderdev/)
