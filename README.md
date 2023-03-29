Algoritmo replit
	Definir apolipoproteína, apolipoproteína_AI, apolipoproteínaB Como Real
	Escribir "Ingrese su nivel de  apolipoproteína-AI y apolipoproteína B (mg/dL)"
	Leer apolipoproteína_AI,apolipoproteínaB
	Si apolipoproteína_AI>=130 Entonces
		Escribir "Su nivel de apolipoproteína-AI esta en optimas condiciones (es beneficioso)"
	SiNo
		SI apolipoproteína_AI<130 Entonces
			Escribir "Su nivel de apolipoproteína-AI no esta en optimas condiciones (no es beneficioso)"
		FinSi
	Fin Si
	Si apolipoproteínaB<90 Entonces
		Escribir "Su nivel de apolipoproteína B esta en un nivel optimo por lo que no deberia de preocuparse"
	SiNo
		Si apolipoproteínaB >=90 y apolipoproteínaB <115  Entonces
			Escribir "Su nivel de apolipoproteína B esta sobre el limite de lo optimo,entonces tenga cuidado"
		SiNo
			Si apolipoproteínaB>=115 y apolipoproteínaB<=140 Entonces
				Escribir "Su nivel de apolipoproteína B esta muy alto, corre riesgo"
			SiNo
				Si apolipoproteínaB>140 Entonces
					Escribir "Su nivel de apolipoproteína B esta muy alto, debe de cuidarse mejor"
				Fin Si
			Fin Si
		Fin Si
	FinSi
FinAlgoritmo
