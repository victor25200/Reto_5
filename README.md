# Reto_5
# Punto 1:
Dado un número entero, determine si ese número corresponde al código ASCII de una minúscula vocal.
## Código
```python
a : int
a = int(input("Ingrese un entero: ")) 
if a == 141 :
  print("El numero " + str(a)+ " corresponde a una vocal en minuscula del codigo ASCII")
elif a == 145 :
  print("El numero " + str(a)+ " corresponde a una vocal en minuscula del codigo ASCII")
elif a == 151 :
  print("El numero " + str(a)+ " corresponde a una vocal en minuscula del codigo ASCII")
elif a == 157 :
  print("El numero " + str(a)+ " corresponde a una vocal en minuscula del codigo ASCII")
elif a == 165 : 
  print("El numero " + str(a)+ " corresponde a una vocal en minuscula del codigo ASCII")   
else:
  print("El numero " + str(a)+ " no corresponde a una vocal en minuscula del codigo ASCII")

```
## Programa funcionando

[![image.png](https://i.postimg.cc/0jQtHb5w/image.png)](https://postimg.cc/47DbY49f)
[![image.png](https://i.postimg.cc/sD0FyCtz/image.png)](https://postimg.cc/3dpfCV8f)
# Punto 2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
## Código
```python
x = (input("Ingrese una longitud: "))
a = ord(x)
if a % 2 == 0: 
    print("El código ASCII de "+ str(x) +" es par")
else:
    print("El código ASCII de "+ str(x) +" no es par")
```
## Programa funcionando

[![image.png](https://i.postimg.cc/FHHSgGBQ/image.png)](https://postimg.cc/6yFTBVKH)
[![image.png](https://i.postimg.cc/SR42XGM3/image.png)](https://postimg.cc/0Mt2FDZ0)
#  punto 3:
Dado un carácter, construye un programa en Python para determinar si el carácter es un dígito o no.
## Código
```python
char1 = "a"
a = (input("Ingrese un numero entero: "))
print(a)
a = ord(a)
if a >= 48 and a <= 57:
   print("el caracter selecionado es un es un digito  ")
else:
    print("el caracter selecionado no es un digito  ")
```
## Programa funcionando
[![image.png](https://i.postimg.cc/Bv0drc7D/image.png)](https://postimg.cc/G4X7YYCh)
[![image.png](https://i.postimg.cc/GhTV9SZG/image.png)](https://postimg.cc/dLv4xnQV)
# Punto 4:
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El numero x es negativo"
Cero (0): "El numero x es el neutro para la suma"
## Código
```python
x : float
x = float(input("Ingrese un numero entero: "))
if x > 0:
   print("El número " + str(x)+ " es positivo")
elif x < 0:
  print("El numero " + str(x)+ " es negativo")
else:
    print( "El numero " + str(x)+ " es el neutro para la suma")
```
Programa funcionando
[![image.png](https://i.postimg.cc/fTQL1C4N/image.png)](https://postimg.cc/z3p8gnXt)
[![image.png](https://i.postimg.cc/mr1WLxM6/image.png)](https://postimg.cc/NytzDzd1)
[![image.png](https://i.postimg.cc/YSYDDtQk/image.png)](https://postimg.cc/f3WvJnHg)
# Punto 5:
Dado el centro y la radio de un círculo, determine si un punto de R2 pertenece o no al interior del círculo.
## Código
```python
h : float
k : float
r : float
x : float
y : float
h = float(input("Ingrese la cordenada en x para el centro del circulo"))
k = float(input("Ingrese la cordenada en y pare el centro del circulo"))
r = float(input("Ingrese el radio del circulo"))
x = float(input("Ingrese la cordenada en x del punto"))
y = float(input("Ingrese la cordenada en y del punto"))
print("El centro esta en (" + str(h) + ","+ str(k)+ ")"  )
print("El radio es (" + str(k)+ ")"  )
if (x-h + y-k)**2 >= r**2:
   print("El punto  (" + str(x) + ","+ str(y)+  ") no esta en el circulo")

else:
     print("El punto  (" + str(x) + ","+ str(y)+  ") esta en el circulo")
```
## Programa funcionando
[![image.png](https://i.postimg.cc/fLDrpk7Z/image.png)](https://postimg.cc/t1vkVqmm)
[![image.png](https://i.postimg.cc/j5BJCn8Y/image.png)](https://postimg.cc/XGcvzqSs)
# Punto 6:
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
## Código
```python
a : float
b : float
c : float
a = float(input("Ingrese la primera longitud: ")) 
b = float(input("Ingrese la segunda longitud: ")) 
c = float(input("Ingrese la tercera longitud: ")) 
print("Las longitudos son a =" + str(a) + " b="+str(b)+" c="+str(c))
if a+b<c :
   print("Con estas longitude se puede construir un triangulo ")
elif a+c < b:
     print("Con estas longitude se puede construir un triangulo ")
elif b+c < a:
     print("Con estas longitude se puede construir un triangulo ")
else :
      print("Con estas longitude no se puede construir un triangulo ")
```
## Programa funcionando
[![image.png](https://i.postimg.cc/LstHjY6M/image.png)](https://postimg.cc/HJLDgLyS)
[![image.png](https://i.postimg.cc/d0YFQsRN/image.png)](https://postimg.cc/NKpSpwzR)
