Algoritmo identificador
	Definir codigo,cifra 	Como Entero
	Escribir "Ingrese una cifra que contenga 3 digitos"
	Leer cifra
	codigo=cifra
	Si cifra<100 Entonces
		Escribir "La cifra no tiene 3 digitos"
	SiNo
		Escribir "La cifra es correcta"
	FinSi
	Si codigo mod 2=0 y codigo mod 3=0 y codigo mod 5 =0
		Escribir "Director general"
		
	FinSi
FinAlgoritmo
