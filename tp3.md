# trabajo práctico 3

  Se deberá resolver los siguientes ejercicios y obtener por consola los resultados esperados para practicar funciones.

## ejercicio 1:

completar el siguiente código para que el resultado sea:  
la suma de 2 y 5 es 7.

código:
```
function sumar(numero1, numero2) {
    // completar.
}

suma(2, 5);
```
fin del código.

## ejercicio 2:

completar el siguiente código para que el resultado sea:  
la resta    de 12 y 10 es 2

código:
```
function resta(numero1, numero2) {
    // completar.
}

var resultado = resta(12, 10);
console.log(resultado);
```
fin del código.


## ejercicio 3:

completar el siguiente código para que el resultado sea:  
la multiplicación   de 5  y 10 es 50

código:  
```
function mutiplica(numero1, numero2) {
    // completar.
}

console.log(multiplica(5, 10));
```
fin del código.

## ejercicio 4:

completar el siguiente código para que al ejecutar este comando por consola:  
node ejercicio-4.js pepe  
la respuesta  sea:  
  
hola pepe, sabias que tu nombre tiene 4 letras.  
  
  probar con otros nombres.

código:  
```
var nombre = process.argv[2];

function saludar(nombre) {
    // completar.
}

saludar(nombre);
```
fin del código.

## ejercicio 5:

Queremos parametrizar el script que nos dice el mes. Se pide completar el siguiente código para que al ejecutar este comando por consola:  
node ejercicio-5.js 8
la respuesta  sea:  
  agosto
  
  probar con otros números.  
  nota: se toma como ejemplo el codigo del ejercicio 5 de la práctica 2.

código:  
```
var mes  = parseInt(process.argv[2]);

function nombreDeMes(numero) {
    // completar.
}

console.log("el mes es: "+nombreDeMes(mes));
```
fin del código.

## ejercicio 6:

completar el siguiente código para que el resultado sea:  
la suma de 2 y 5 es 7

código:
```
function sumar(numero1, numero2) {
    // completar.
}

console.log("la suma de 2 y 5 es "+suma(2,5));
```
fin del código.

## ejercicio 7:

  Se deberá completar las funciones para que retorne los resultados.
  
  código:
  var n1 = 10;
  var n2 = 3;
```
function sumar(numero1, numero2) {
    // completar.
}

function restar(numero1, numero2) {
    // completar.
}

function multiplica(numero1, numero2) {
    // completar.
}

console.log("la suma es "+suma(n1, n2));
console.log("la resta  es "+resta(n1, n2));
console.log("la multiplicacion es "+multiplica(n1, n2));
```
fin del código. 