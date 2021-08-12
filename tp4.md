# trabajo práctico 4

  Se deberá resolver los siguientes ejercicios y obtener por consola los resultados esperados para practicar condicionales y funciones.

## ejercicio 1:

completar el siguiente código para que si le pasamos a la función "meGusta" un 7 muestre:  
¡me encanta el 7!  
pero si le pasamos otro número diga:  
el numero x no me gusta.  
donde x debe mostrar el número que le pasamos a la función.


código:
```
var num = 7;

function meGusta(numero) {
    // completar.
}

meGusta(num);
```
fin del código.

## ejercicio 2:

completar el siguiente código para que la función si recibe una palabra con menos de 5  letras como: "sol", "luna", "agua" muestre:  
es una palabra corta.  
pero si le pasamos una palabra mas larga como: "cielo", "javascript". muestre:  
es una palabra larga.

código:
```
var texto = "agua";

function esPalabraCorta(palabra) {
    // completar.
}

esPalabraCorta(texto);
```
fin del código.


## ejercicio 3:

Hacer la función divide. Recordemos que no se puede dividir por 0, por lo tanto si el segundo número es un 0 debe mostrar un error con el siguiente mensaje:  
no se puede dividir por 0  
si no mostrar el resultado.  

código:  
```
var num1 = 10;
var num2 = 2;

function divide(n1, n2)  {
    // completar.
}

divide(num1, num2);
```
fin del código.

## ejercicio 4:

Nos piden hacer una función que complete una palabra. En pantalla solo debe mostrar una cadena de 7 caracteres. si la palabra tiene 4 letras debe rellenar el resto con puntos.  
ejemplo:  
si la palabra es agua, debe mostrar:  
agua...  
si la palabra es sol, debe mostrar:  
sol....  
si la palabra es jueves muestra:  
jueves.  
siempre el resultado tiene que ser de 7 caracteres. revisar que en el primer caso se le agrega 3 puntos, en el segundo 4 puntos y en el segundo caso como tiene 6 letras se le agrega un punto.  
si la palabra es de más de 7 letras, mostrará error con el  siguiente mensaje:  
error: la palabra es muy larga.

código:  
```
var texto  = "agua";

function completar(palabra) {
    // completar.
}

completar(texto);
```
fin del código.
