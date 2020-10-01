# Practica Pseudocodigo y complejidad
### Pseudocódigo
Una forma de representar algoritmos de forma independiente al lenguaje de programación es a través de pseudocódigo. Este consiste en la escritura de los pasos o instrucciones del algoritmo en palabras y símbolos más cercanos al lenguaje natural que al lenguaje máquina. Como tal no existen reglas ni espeicificaciones para escribir pseudocódigo, pero sí existen buenas prácticas y recomendaciones. Algunas de las principales es el uso de instrucciones de control como comandos `if`, `else`, ciclos como `for` y `while` y operadores lógicos como `and` u `or`. De esta forma se busca describir el comportamiento y funcionamiento de un algoritmo con lenguaje cercano al empleado comúnmente por las personas.
Por ejemplo, un posible pseudocódigo para un algoritmo que regrese la suma de dos números si el primero `x` es mayor al segundo `y` y en caso contrario regrese la resta; podría lucir como lo siguiente:

```
Entradas:
x
y
------
resultado <- 0
if x > y:
  resultado <- x + y
else:
  resultado <- x - y
return resultado
```

Donde `<-` hace referencia a una asignación, `<` es el operador de comparación *menor que* y por último la sentencia `return` indica el valor que va a regresar el algoritmo.


## Descripción

En este proyecto tendrás que describir, para cada algoritmo, la complejidad computacional de cada uno de ellos, y tendrás que anotar el resultado del algoritmo para un conjunto de valores de entrada determinado.

### Algoritmo 1
```
Entradas:
x
y
------
resultado <- 1
for i form 1 to y:
  resultado <- resultado * x
return resultado
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|x|y|resultado|
|-|-|-|
|2|5|**16**|
|3|3|**9**|
|10|8|**10000000**|


##### Complejidad
Escribe en esta sección la complejidad computacional que coresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).


**Dado el tiempo de ejecución n, despreciando las constantes, ya que el ciclo se ejecuta completo: Complejidad= O(n) el peor escenario**

### Algoritmo 2
```
Entradas:
x
valores
------
for each val in valores:
  if val > x:
    return false
  else if val == x:
    return true
return false
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|x|valores|resultado|
|-|-|-|
|4|[1, 2, 4, 7, 9]|**True**|
|9|[1, 3, 5, 6, 7]|**False**|
|3|[5, 6, 7, 8, 9, 10]|**True**|


##### Complejidad
Escribe en esta sección la complejidad computacional que corresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).

**El tiempo de ejecución es de n, por ello, sería O(n), o sea, que es el peor escenario posible, debido a que ejecuta el ciclo completo**

### Algoritmo 3
```
Entradas:
valores_x
valores_y
------
for each valx in valores_x:
  y_contiene_x <- false
  for each valy in valores_y:
    if valx == valy:
      y_contiene_x <- true
  if y_contiene_x == false:
    return false
  return true
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|valores_x|valores_y|resultado|
|-|-|-|
|[1, 2, 3]|[1, 2, 3, 4, 5]|**Tu respuesta aquí**|
|[2, 4]|[7, 5, 2, 8, 3]|**Tu respuesta aquí**|
|[3, 5, 2]|[6, 5, 3, 7, 1, 2]|**Tu respuesta aquí**|


##### Complejidad
Escribe en esta sección la complejidad computacional que coresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).

**Tu respuesta aquí**
