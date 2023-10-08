# paquetito-npm
Este es un package npm que te ayuda a mostrar console.log divertidos
## ConsoleLogsito

Puedes usar import ConsoleLogsito from "paquetito-npm"

o tambien puedes usar  const paquetitoNpm = require("paquetito-npm")

## Usando la clase con ES6:
Recuerda que antes de ejecutar tu codigo con esta sintaxis 
debes asegurarte que tu archivo deba tener la extension 
correcta : Archivo.mjs  .
si usas import la sintaxis es  asi :

const paquetitoNpm = new ConsoleLogsito;

y seguido de ello usas el metodo consoleSad()  :

paquetitoNpm.consoleSad();

## Usando la clase con CommonJS :

usando require es asi :

const paquetitoNpm = require("paquetito-npm");

const usoPaquetitoNpm = new paquetitoNpm();

usoPaquetitoNpm.consoleSad();

## Metodos que tiene la clase ConsoleLogsito :

## metodo consoleSad 
 muestra en la terminal este mensaje:

este es un console.log despues de tumbar el servidor que tenia la planilla de la empresa .

## metodo consoleHappy

muestra en tu terminal un mensaje :

este es un console.log despues de que me depositaran el sueldo de todos por error ! psdt : ya me fui del pais XD.