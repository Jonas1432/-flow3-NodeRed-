# -flow3-NodeRed-

Este repositorio es para el Tercer ejercicio de NodeRed para el curso Internet de las Cosas Código IOT del grupo 11.

## Introducción 

Este ejercicio consiste únicamente en conectar un nodo Inject con un nodo Debug y automatizarlo para que genere un TimeStamp cada 1 segundo, mostrando la fecha actual, esta funcion se realiza mediante la pestaña Debug.

# Referencias 

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com 

## ||Instrucciones de preparación del entorno||
Para ejecutar este flow, es necesario lo siguiente

1. Arrancar NodeRed con el comando node-red 
2. despues ejecutas localhost:1880
3. Importar el flow
4. Hacer clic en el boton Deploy
5. Instrucciones de operación
6. Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug.

## Tercer Flow-3

- Usamos la funcion se utiliza la misma que la anterior ejercicio.

* Agregamos un boton de funcion
* Lo configuramos para que cada que repita nos de la fecha con 
* var date = new
* Date/(msg.payload);
* msg.payload=date.toString();

## Resultado

Como se muestra en la imagen agregada.
 
![](https://github.com/Jonas1432/-flow3-NodeRed-/blob/main/flow-3.png)

# [Resultado-Final]

![](https://github.com/Jonas1432/-flow3-NodeRed-/blob/main/Resultado-Flow3.png)

# Créditos

* Desarrollado por Jonathan Araujo
* https://github.com/Jonas1432