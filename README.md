# Ejercicio 8

## 1.- Realizar la multiplicación de todos los elementos de un arreglo de entrada con n elementos.
```
Entradas:
x (con n elementos) 
------
producto = 1
for x[i] in range i=(0,n)
    producto = producto*x[i]
Return producto
```

## 2.- Calcular el promedio de un arreglo con n números enteros de entrada.
```
Entradas:
x (con n elementos)
------
suma = 0
for x[i] in range i=(0,n)
    suma = suma + x[i]
promedio  = suma/n
Return promedio
```

## 3.- Obtener el elemento más pequeño.
Supuse que era para un arreglo de n elementos.
```
Entradas:
x (con n elementos)
------
pequeño = 0
for x[i] in range i=(0,n)
    if x[i]>pequeño
        pequeño = x[i]
Return pequeño 
```

## 4.- Obtener el elemento más grande.
```
Entradas:
x (con n elementos)
------
grande = 0
for x[i] in range i=(0,n)
    if x[i]>grande
        grande = x[i]
Return grande 
```

## 5.- Determinar si un número es primo o no lo es.
```
Entradas:
x
------
if x%2 == 0
    Return "Es primo"
else
    Return "No es primo"
```

## ¿Cuál es la complejidad de los problemas?
1.- O(n) 
2.- O(n)
3.- O(n)
4.- O(n) 
5.- O(1)