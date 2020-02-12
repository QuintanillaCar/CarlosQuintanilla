SubAlgoritmo resultado <- prom(num1,num2,num3)
	Definir  resultado Como Entero;
	resultado<-(num1+num2+num3)/3;
FinSubAlgoritmo

SubAlgoritmo funcion3 <-banos(nombre,genero)
	definir gen Como Caracter;
	Escribir "Ingrese nombre";
	leer nombre;
	Escribir "Ingrese genero F/M";
	leer genero;
	Si genero=M Entonces
		Escribir"Ingrese al baño de Hombres";
		si genero = F Entonces
			Escribir "Ingrese al baño de mujeres";
			
		FinSi
	SiNo
		Definir i Como Entero;
		definir ducha Como Caracter;
		Escribir"Vuelva a ingresar sus datos o Desea ducha";
		leer i;
	FinSi

	
FinSubAlgoritmo
SubAlgoritmo contar <- cuenta(num)
	Definir contar Como Entero;
	Definir contador como entero;
	contador<-0;
		
	Repetir
		num <- trunc (num/10);
		contador<- contador +1;
			
	Hasta Que num < 10
	contar<-contador+1;
FinSubalgoritmo

	

SubAlgoritmo funcion5
	
	
FinSubAlgoritmo
SubAlgoritmo participantes<- participa(nombre, apellido, fono, email )
	definir arr como entero;
	definir i Como Entero;
	Definir cantidad Como Entero;
	Escribir "Cuantos participantes son?";
	Leer cantidad;
	definir x Como Entero;
	Dimension arr[nombre,apellido,fono,email];
	para x<-0 Hasta (largo) Con Paso 1 Hacer
		Escribir "Ingresar datos de los participantes";
		
		 
	
	FinPara
	
	
FinSubAlgoritmo
Algoritmo Evaluacion

		
	Limpiar Pantalla;
	
	definir tabla  como entero;
	
	
	Repetir
		
		Escribir "BIENVENIDO A SU EVALUACION";
		Escribir "";
		Escribir "***********EVALUACION*******";
		Escribir "1- Secuencial ";
		Escribir "2- Condicional Si Entonces ";
		Escribir "3- Condicional Si entonces anidado ";
		Escribir "4- Condicional según ";
		Escribir "5- Repetitiva Mientas";
		Escribir "6- Repetitiva Repetir ";
		Escribir "7- Repetitiva para";
		Escribir "8- Arreglo Simple ";
		Escribir "9- Arreglo bidimensional ";
		Escribir "10-Salir ";
		Escribir "****************************";
		Escribir " ";
		Escribir "Ingrese una alternativa de 1 a 10";
	
		Leer tabla;
		
	Hasta Que tabla <-9
	
	Segun tabla Hacer
		
					1: Escribir "Secuencial";
						leer resultado;
					2: Escribir "Condicional Si Entonces";
						
					3: Escribir "Condicional Si entonces anidado";
						
					4: Escribir "Condicional según";
						
					5: Escribir "Repetitiva Mientas";
						
					6: Escribir "Repetitiva Repetir";
						
					7: Escribir " Repetitiva para";
						
					8: Escribir "Arreglo Simple";
						
					9: Escribir "Arreglo bidimensional";
						
					10:Escribir "Salir";
						
				
				FinSegun
						
				
				
			
		
		
    
	
FinAlgoritmo
