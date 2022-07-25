# readme
Angel-core-code-from-scratch-readme

## SEMANAS
SEMANA 1 [SEMANA1](blob/main/SEMANA%201)



##MARTES

LENGUAJES DE PROGRAMACION

existen varios lenguajes e interpretes en la programacion para que las maquinas puedan entender y leer la informacion. estan los compiladores y los interpretes
los compiladores son Los lenguajes se convierten directamente en código máquina que el procesador puede ejecutar. y los interpretres ejecutan un programa línea por línea y ejecutan cada comando


Pseudocode currency converter.
Descripcion: es una forma de describir una serie de pasos (un algoritmo) que se seguirán para resolver un problema, sin necesidad de desarrollarlo utilizando un tipo de lenguaje de programación

Ejemplo: 
1. start
2. num1<---GET (obtener) 
3. num2<---GET (obtener)
4. result<---num1+num2
5. print result
6. end


##MIERCOLES 
AÑO DE NACIMIENTO A BINARIO 


| POSICION | BINARIO |
|---|---|
|0|2^0=1|
|1|2^1=2|
|2|2^2=4|
|3|2^3=8|
|4|2^4=16|
|5|2^5=32|
|6|2^6=64|
|7|2^7=128|
|8|2^8=256|
|9|2^9=512|
|10|2^10=1024|


AÑO DE NACIMIENTO 1994 = BINARIO X

1111001010=1994

assembly 
para el color en git


EJERCICIO 2 MISP 

1 Crear un programa que agregue dos números dados proporcionados por el usuario

  .data
	      Bienvenido:.asciiz "\nBienvenido\n"
	      numero1: .asciiz "\nIngrese el primer numero: "
	      numero2: .asciiz "\nIngrese el segundo numero: "

  .text
	      main:
	      #welcome message
	      li $v0, 4
	      la $a0, Bienvenido
	      
	      #Ingrese el primer Numero
              li $v0, 4
              la $a0, numero1
              syscall

              li $v0, 5
              syscall
	      
	      #Guardando captura en la maquina
              move $t0, $v0

		#Ingrese Segundo Numero
              li $v0, 4
              la $a0, numero2
              syscall

              li $v0, 5
              syscall

	     #Guardand Captura del segundo Numero
              move $t1, $v0

              li $v0, 1
              move $a0, $t0
              syscall
              



Crear un programa que muestre su nombre:


 .data
	      Mi_Nombre: .asciiz "\nAngel Chacach\n"
  .text
	      main:
              li $v0, 4
              la $a0, Mi_Nombre
              syscall
              













