
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

       Algoritmo multiplicar_por_9_un_numero
  
	Escribir "ingresa un número"
  
	Leer num
  
	resultado<-num * 9
  
	Escribir "el resultado de ",num," * 9 es: ",resultado
  
  ![tabla del 9](https://user-images.githubusercontent.com/101203475/159968076-a6c24d73-cbfe-4143-ad77-15650ffe132d.png)

3. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”.


5. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo promedio_calificaciones

	Escribir "ingresa la calificación del primer periodo"
	Leer cal1
	
	Escribir "ingresa la calificación del segundo periodo"
	Leer cal2
	
	Escribir "ingresa la calificación del tercer periodo"
	Leer cal3
	
	Escribir "ingresa la calificación del cuarto periodo"
	Leer cal4
	
	promedio<-(cal1+cal2+cal3+cal4)/4
	
	Si promedio >= 6 Entonces
	
		Escribir "felicidades has aprobado, tu promedio es de ",promedio
	SiNo
		Escribir "Lo siento has reprobado, tu promedio es de ", promedio
	Fin Si
	
        FinAlgoritmo
	
![promedio](https://user-images.githubusercontent.com/101203475/159974255-8bab51f1-73d1-469f-9c07-1e13b6df491a.png)



7. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

        Algoritmo par_o_impar

	Escribir "ingresa un número"
	
	Leer num
	
	Si num  % 2 == 0 Entonces
	
		escribir "el número ",num," es par"
		
	SiNo
	
		escribir "el número ",num, " es impar"
		
	Fin Si
		
        FinAlgoritmo

![par o impar](https://user-images.githubusercontent.com/101203475/159971589-d17f627c-752b-44eb-a5da-b34172bf2418.png)


8. Un programa que pida una letra y detecte si es una vocal.

Algoritmo detecta_si_es_vocal

	Escribir "ingresa una letra"
	
	Leer vocal
	
	Segun vocal Hacer
	
		"a"|"A":
			Escribir "la letra ",vocal," es una vocal"
		"e"|"E":
			Escribir "la letra ",vocal," es una vocal"
		"i"||"i":
			Escribir "la letra ",vocal," es una vocal"
		"o"||"O":
			Escribir "la letra ",vocal," es una vocal"
		"u"||"U":
			Escribir "la letra ",vocal," es una vocal"			
		De Otro Modo:
			Escribir "la letra ",vocal," no es vocal"
	Fin Segun

      FinAlgoritmo
      
 ![vocales](https://user-images.githubusercontent.com/101203475/159973741-5d61f39e-c9db-47e7-8508-7e05742f5b55.png)


10. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
11. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.

        Algoritmo Nombre_Impreso

	Escribir "ingresa tu nombre"
	
	Leer nombre
	
	Escribir "ingresa el número de veces que deseas imprimir tu nombre"
	
	Leer num
	
	Para i<-1 Hasta num Con Paso 1 Hacer
	
	Escribir nombre
		
	Fin Para
	
	FinAlgoritmo
	
	
11. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
