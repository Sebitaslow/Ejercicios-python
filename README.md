# Ejercicios-python

1.*Ejercicios Prácticos de Python*

1.1 Solicita el nombre y edad del usuario, luego imprime un saludo personalizado que incluya ambos datos.

print ("Pon tu nombre: ")
nombre = input()
print("Pon tu apellido: ")
apellido = input()
print ("Pon tu edad: ")
edad = input()
print ("Bienvenido " + nombre + " " + apellido + " Tu edad es: " + edad + " años.", "Te desamos suerte en tu nuevo proyecto")

1.2 Pide al usuario que ingrese su comida favorita y su color favorito, luego imprime una frase con ambos.

print("¿Cual es tu comida favorita?:      ")
comida = input()
print("")
print ("¿Que color es tu favorito?:   ")
Colors = input()
print("")
print(f"Que delicioso es comer {comida} y este el {Colors} es expectacular")

1.3 Solicita un número y muestra su doble y su triple.

numer = float(input("Escribe un número:  "))

doble = numer * 2
triple = numer * 3

print(f"El doble de {numer} es {doble}")
print(f"El doble de {numer} es {triple}")

2.*Tipos de datos en Python*

2.1 Declara una variable de cada tipo básico: entero, flotante, cadena y booleano.


Número_entero = 98 - Int
Número_Flotante = 8.22 -Float
Texto = "La vida es una yuca" -str
Verdadero = True - Bool

2.2 Convierte una cadena con valor numérico a entero y realiza una suma con otro número.

cadena = "902"
Numer = int(cadena)
print(Numer + 92)

2.3 Convierte una entrada de texto a número flotante, multiplícala por 2 y muestra el resultado.

Texto = "313.12"
Numer = float(Texto)
print(Numer * 2)

2.4 Escribe una función que reciba un string y devuelva True si puede convertirse a número y False si no.

print ("Esribe un caracter:  ")
caracter = input ()
def numero (caracter): ## creamos la funcion para que caracter sea numero
    try: ## se pone try por si el usuario pone otra cosa que no sea numero el resultado sea falso
        float(caracter) ## Se hace que el caracter osea el numero que ingrese sea real osea cualquier número
        return True
    except ValueError:
        return False
    
resultado = numero(caracter)
print(resultado)"

3. *Operadores en Python*

3.1 Calcula el área de un rectángulo a partir de base y altura ingresadas por el usuario.

B = float(input("Escribe la base del cuadrado: "))
A = float (input("Escribe la altura del cuadrado: "))
print(A * B)

3.2 Dado un precio y un porcentaje de descuento, muestra el valor final a pagar.

Precio = float(input("Escribe el precio: "))
porcentaje = float(input("Escribe el porcentaje: "))
resultado = (Precio * porcentaje)/ 100
print (f"El valor a pagar: ${resultado}")

3.3 Calcula el residuo de dividir dos números dados por el usuario.

A = float(input ("Escribe el numero que deseas dividir: "))
B = float ( input ("Escribe cuantas veces deseas dividir: "))

resultado = A % B

print(int(resultado))

3.4 Escribe una fórmula que use al menos tres operadores diferentes y muestre el resultado.

A = float (input("Numero a restar, sumar y dividir entre 4, 5, 6: "))
resultado1 = A + 4
resultado2 = resultado1 * 5
resultado3 = resultado2 / 6
print (resultado3)

4. *Operadores relacionales*

4.1 Pide dos números e indica cuál es mayor o si son iguales.

R = float (input("Escribe un número: "))
X = float (input("Escribe un número: "))
if R > X:
    print (f"{R} Es mayor")
else:
    if X > R:
        print (f"{X} Es mayor")
    else:
        if X == R:
            print (f"{X} y {R} Son iguales")

4.2 Solicita una edad y determina si la persona es menor de edad (menor a 18).

edad = int (input("Escribe tu edad: "))
if edad < 18 :
    print ("Eres Menor de edad")
else:
    print ("No eres menor de edad")

4.3 Escribe un programa que compare dos cadenas de texto e indique si son iguales o distintas.

M = str (input("Escribe Una palabra: "))
F = str (input("Escribe una Palabra: "))
if M == F:
    print ("Estas dos palabras son iguales")
else:
        print ("Estas dos palabras no son iguales")

5. *Operadores lógicos*

5.1 Pide al usuario su edad y si tiene licencia de conducción. Solo si ambas condiciones se cumplen, imprime que puede conducir.

Edad = int (input("¿Cuál es tu edad?: "))
conduccion = input("¿Tiernes Licencia para conducir? (sí/no): ")
if conduccion  in ["sí", "si"] and Edad >= 18:
    print ("Puede conducir")
else:
    print ("No puede conducir")

5.2 Solicita si una persona tiene experiencia laboral y título universitario. Usa operadores lógicos para decidir si puede aplicar a una oferta de trabajo.

laboral =  (input("¿Tienes experiencia laboral? (sí/no): "))
conduccion = input("¿Tiernes título universitario? (sí/no): ")
if laboral  in ["sí", "si"] and conduccion in ["sí", "si"]:
    print ("Puede aplicar a oferta de trabajo")
else:
    print ("No Puede aplicar a oferta de trabajo")

5.3 Dado un número, determina si está en el rango de 10 a 50 (inclusive).

numero = float (input("Escribe un numero: "))
if numero >= 10 and numero <= 50:
    print ("El numero esta en el rango de 10 a 50")
else:
    print("El numero no esta en el rango de 10 a 50")
