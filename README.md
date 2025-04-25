# Ejercicios-python
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


Número entero = 98 - Int
Número Flotante = 8.22 -Float
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
print(resultado)

4. *Operadores relacionales*

4.1 Pide dos números e indica cuál es mayor o si son iguales.
