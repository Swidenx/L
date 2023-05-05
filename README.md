import os
import tkinter as tk
import re
def S():
if os.path.isfile("archivos.txt"):
    archivoTexto=open("archivos.txt", "r+"):
    print("Digito nombre del beneficiario, identificacion y numero de telefono")
    nombre=input()
    identificacion=input()
    numero=input()
    lineasTexto=archivoTexto.readlines()
    for elementos in lineasTexto:
        # Busqueda por elemento completo
        while re.search(identificacion, elemntos):
            print("La identificacion ya existe,intente de nuevo")
            nombre=input()
            identificacion=input()
            numero=input()
        archivoTexto.write(nombre + " ")
        archivoTexto.write(identificacion + " ")
        archivoTexto.write(numero + "\n")
        achivoTexto.close()
else:
    archivoTexto=open("archivos.txt","w")
    print("Digito nombre del beneficiario, identificacion y numero de telefono")
    nombre=input()
    identificacion=input()
    numero=input()
    archivoTexto.write(nombre + " ")
    archivoTexto.write(identificacion + " ")
    archivoTexto.write(numero + "\n")
    achivoTexto.close()
print("Ingrese el nombre del beneficiario para buscarlo") 
letra=input()
# Busqueda por letra
for elementos in lineasTexto:
    if re.findall(letra, elemento):
        print(elemento)

ventana = tk.Tk()
#entrada1 = tk.Entry(ventana)
#entrada2 = tk.Entry(ventana)
#entrada3 = tk.Entry(ventana)
resultado = tk.Label(ventana, text="a")
#entrada1.grid(row=2, column=0)
#entrada2.grid(row=2, column=1)
#entrada3.grid(row=2, column=2)
botonOp1.grid(row= , column= )
botonOp2.grid(row= ,column= )
botonOp3.grid(row= ,column= )#Consult
resultBotonOp1= tk.Button(ventana, text=" ")
resultBotonOp2= tk.Button(ventana, text=" ")
resultBotonOp3=tk.Button(ventana, text=" " )#Consult
ventana2 = tk.Tk()
botonOp11.grid(row= , column= )
botonOp12.grid(row= , column= )
botonOp13.grid(row= , column= )
resultBotonOp11= tk.Button(ventana2, text=" ")
resultBotonOp12= tk.Button(ventana2, text=" ")
resultBotonOp13= tk.Button(ventana2, text=" ")
ventana3 = tk.Tk()
botonQuest.grid(row= , column= )
botonConsult.grid(row= , column= )
resultBotonQuest= tk.Button(ventana3, text=" ")
resultadoBotonConsult= tk.Button(ventana3, text=" ")
ventana4 = tk.Tk()
#1-(5 Stars)
resultBotonCalificationOfStars= tk.Button(ventana4, text="Stars")
                                                                               
