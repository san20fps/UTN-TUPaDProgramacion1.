#Subo Pratica unidad 1
1 print("Hola Mundo!")
2 nombre=input("Por favor, ingrese su nombre: ")
print(f"Hola {nombre}!")
3 nombre=input("Ingrese su nombre: ")
apellido=input("Ingrese su apellido: ")
edad=int(input("Ingrese su edad: "))
lugarDeResidencia=input("Ingrese su lugar de residencia: ")
print(f"Hola! Soy {nombre} {apellido}, tengo {edad} años y vivo en {lugarDeResidencia}")
4 radio=int(input("Ingrese el radio de un circulo: "))
area=3.14*radio**2
perimetro=2*3.14*radio
print(f"El area del circulo es {area}, y el perimetro es {perimetro}")
5 segundos=int(input("Ingrese la cantidad de segundos que desee: "))
horas=segundos/3600
print(f"{segundos} segundos equivalen a {horas} hora/s")
6 num=int(input("Ingrese un numero para mostrar su tabla de multiplicar: "))
print(f"Tabla de multiplicar de {num}")
print(f"{num}x1={num*1}")
print(f"{num}x2={num*2}")
print(f"{num}x3={num*3}")
print(f"{num}x4={num*4}")
print(f"{num}x5={num*5}")
print(f"{num}x6={num*6}")
print(f"{num}x7={num*7}")
print(f"{num}x8={num*8}")
print(f"{num}x9={num*9}")
print(f"{num}x10={num*10}")
7 num1=int(input("Ingrese un numero distinto de 0: "))
num2=int(input("Ingrese otro numero distinto de 0: "))
suma=num1+num2
resta=num1-num2
multiplicacion=num1*num2
division=num1/num2
print("Resultados")
print(f"La suma entre {num1} y {num2} es {suma}")
print(f"La resta entre {num1} y {num2} es {resta}")
print(f"La multiplicacion entre {num1} y {num2} es {multiplicacion}")
print(f"La division entre {num1} y {num2} es {division}")
8 altura=int(input("Ingrese su altura: "))
peso=float(input("Ingrese su peso: "))
alturaMetros=altura/100
imc=peso/(alturaMetros)**2
print(f"Su IMC es de {imc}")
9 celsius=int(input("Ingrese una temperatura en grados celsius: "))
fahrenheit=9/5*celsius+32
print(f"La equivalencia de los grados celsius a grados fahrenheit es {fahrenheit}")
10 nota1=int(input("Ingrese la primera nota: "))
nota2=int(input("Ingrese la segunda nota: "))
nota3=int(input("Ingrese la tercera nota: "))
promedioDeNotas=(nota1+nota2+nota3)/3
print(f"El promedio de las 3 notas ({nota1},{nota2},{nota3}) es de: {promedioDeNotas}")
