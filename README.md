# PARCIAL1CORTE
# PARTE II
## PUNTO 3
Para el cálculo del valor de un libro, se tienen los siguientes parámetros: <br>
	* Categoría del descuento: El porcentaje de descuento que recibe un cliente dependiendo su relación con la Escuela es el siguiente:<br>
		* *Empleado*: Este grupo incluye profesores y todos los miembros de la comunidad que trabaja en la Escuela, tienen un descuento del 10%. <br>
		* *Estudiante*: Este grupo incluye a estudiantes actuales o egresados de la Escuela, tienen un 20% de descuento.<br>
		* *Otros*: Este grupo incluye cualquier cliente que no pertenezca a la Escuela, para este grupo no existe ningún descuento.<br>
	* Calificación del libro: Los libros dentro de ECIBooks están categorizados con un valor numérico de 1 a 30, con base en esta categoría es calculado el precio del libro.<br>
		* *De 1 a 10*: Rango menor, el valor de los libros de esta categoría es de 25.000 pesos.
		* *De 11 a 20*: Rango intermedio, el valor de los libros de esta categoría es de 50.000 pesos.
		* *De 11 a 30*: Rango mas alto, el valor de los libros de esta categoría es de 100.000 pesos. 

## PUNTO 4
Defina las clases de equivalencia necesarias para realizar las pruebas y asegurar la calidad del programa. Estas pueden ser realizadas en cualquier archivo que sea claramente visible. <br>

1. Categoría del descuento:<br>
	*correctos* <br>
	
	a. Empleado=true 
	b. Estudiante=true 
	c. Otros= true <br>
	*Incorrectos* 
	
	d. Empleado=false
	e. Estudiante=false
	f. Otros= false
2. Calificación del libro: 
	*correctos* <br>
	
	a. bookCategory>0 y bookCategoria<11
	b. bookCategory>10 y bookCategory<21
	c. bookCategory>20 y bookCategory<31 
	
	*Inconrrectos* <br>
	d. bookCategoria<1  
	e. bookCategoria>30
