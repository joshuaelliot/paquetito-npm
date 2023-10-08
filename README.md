# paquetito-npm

Este paquete de npm te permite mostrar mensajes de registro divertidos en la consola.

## Instalación

Para utilizar este paquete en tu proyecto, puedes instalarlo con npm o yarn:

```bash
npm install paquetito-npm
# o
yarn add paquetito-npm
```
Uso
Importar el paquete
Puedes importar la clase `ConsoleLogsito` en tu código de la siguiente manera:

ES6 Modules
```javascript
import ConsoleLogsito from "paquetito-npm";

const paquetitoNpm = new ConsoleLogsito();
```
CommonJS
```javascript
const ConsoleLogsito = require("paquetito-npm");

const paquetitoNpm = new ConsoleLogsito();
```
Utilizar la clase
Una vez que hayas importado la clase, puedes utilizarla para mostrar mensajes divertidos en la consola:
```javascript
paquetitoNpm.consoleSad();

```

Métodos Disponibles:
```javascript
consoleSad()
```
Este método muestra en la terminal el siguiente mensaje:
```javascript
"Este es un console.log después de tumbar el servidor que tenía la planilla de la empresa."
```
```javascript
consoleHappy()
```
Este método muestra en tu terminal el siguiente mensaje:
```javascript
`Este es un console.log después de que me depositaron el sueldo de todos por error! 
PSDT: ¡Ya me fui del país! XD.`
```
Contribución
Si deseas contribuir a este proyecto, siéntete libre de abrir problemas (issues) o enviar solicitudes de extracción (pull requests) en GitHub.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.


Asegúrate de reemplazar `"tu-usuario/tu-repo"` con la URL de tu repositorio de GitHub si deseas incluir un enlace a tu repositorio para contribuciones. También, asegúrate de incluir la licencia correcta en el archivo LICENSE si no lo has hecho aún. Esta documentación proporciona una estructura más organizada y descriptiva para que los usuarios comprendan y utilicen tu paquete de manera efectiva.
