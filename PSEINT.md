# PSEINT

<p>
PSeInt (abreviatura de "Pseudo Intérprete") es un software libre y gratuito que se utiliza para aprender a programar. Es un entorno de desarrollo integrado (IDE) que permite a los usuarios escribir, ejecutar y depurar programas simples en pseudocódigo, un lenguaje de programación que no sigue la sintaxis de ningún lenguaje de programación real, pero que es útil para comprender los conceptos básicos de la programación.
</p>

<p>
PSeInt es muy popular en entornos educativos, ya que permite a los estudiantes practicar los conceptos básicos de la programación sin preocuparse por la sintaxis de un lenguaje de programación específico. Además, PSeInt proporciona una visualización detallada del proceso de ejecución de los programas, lo que ayuda a los estudiantes a entender cómo funcionan sus programas y cómo mejorarlos.
</p>

# EJEMPLOS DE VECTORES
- HACER UN PROGRAMA CON LAS OPERACIONES BASICAS CON VECTORES

<pre>
<code>
Algoritmo Vector1_sumar_elementos_vector
	//DEFINIR DATOS 
	Definir v, s, max, min Como Entero
	Dimension v[10]
	//LLENAR UN VECTOR
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		v[i] = Aleatorio(1,6)
	Fin Para
	
	//RECORRER EL VECTOR
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Escribir v[i] 
	Fin Para
	
	//SUMAR LOS ELEMENTOS DEL VECTOR
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		s = s + v[i] 
	Fin Para
	Escribir "Suma: ",s
	
	//CALCULAR EL MAYOR ELEMENTO DE UN VECTOR
	max = v[1]
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Si v[i] > max Entonces
			max = v[i]
		FinSi
	Fin Para
	
	//CALCULAR EL MENOR ELEMENTO DE UN VECTOR
	min = v[1]
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Si v[i] < min Entonces
			min = v[i]
		FinSi
	Fin Para
	
FinAlgoritmo
</code>
</pre>

# ANEXO 1: VIDEO YOUTUBE

<p align="center">
  <a href="https://www.youtube.com/watch?v=d_xDOLVZDcM">
     <img src="https://i.ytimg.com/vi/d_xDOLVZDcM/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCGVOy-C79y7-ZpAva2gm6XJY9Nmg" alt="Expresiones Regulares" width="400" height="300" border="10" /></a>
  <a href="https://www.youtube.com/watch?v=d_xDOLVZDcM"></a>
</p>