# Bucles o ciclos

## While

- Es cuando la condición se indica antes de iniciar el bucle.

## For 

- Es cuando se tiene una conticion inicial y una variable de control en el mismo bucle.


## Ejercicio:

1. Un profesor tiene un salario inicial de $1500, y recibe un incremento de 10% anual durante 6 años ¿Cuál es su salario al cabo de 6 años? ¿Qué salario ha recibido en cada uno de los 6 años? realice el algorítmo y represente la solución mediante el diagrama de flujo, el pseudocodigo y el diagrama N/S utilizando el ciclo apropiado.

 **Res/**

   **Analisis**

  | Input|
  |------|
  | -----|

  |Output|
  |------|
  | anual, total|

  | Control|
  |--------|
  | año|

  **Diagrama de flujo**

  ¡[text](Diagrama_ejercicio_1.png)


  **Pseudocódigo**

  ```
  Inicio
  año=1
  sal=1500
  total=0
  Mientras año <= 6:
      anual= sal * 1,1
      total= total + anual
      sal=anual
      año= año + 1
      Mostrar anual
  Fin mientras
  Mostrar total
  Fin
 ```

2. Se requiere un algoritmo para determinar, de N cantidades, cuantas son cero, cuantas son menores que cero y cuántas son mayores a cero. Realice el diagrama de flujo y pseudocódigo.


 **Res/**

  **Analisis**

   | Input|
  |------|
  | N|

  |Output|
  |------|
  | cero, mayor, menor|

  | Control|
  |--------|
  | i|

  **Diagrama de flujo**

  
¡[texto](Diagrama_ejercicio_2.png)

**Pseudocódigo:**
```
Inicio
Leer N
i=0
cero=0
mayor=0
menor=0
Mientras i<N;
  leer cant
  Si cant>0
  mayor=mayor+1
  Si no
  Si cant=0
  cero=cero+1
  Si no
  menor=menor+1
  Fin si
i=i+1
Fin mientras
Mostrar cero, mayor, menor

Fin

```


## Tarea

- Tienen una tarjeta de $10'000.000. Calcular el valor de todas las cuotas sabiendo:

1. Valor de la compra.
2. Tasa de interes 2%.
3. Número de cuotas, maximo 36.

**Solución**


  **Analisis**

  |Variables de entrada|
  |--------------------|
  | valor_compra|
  | numero_cuotas|

  |Variables de control|
  |--------------------|
  |numero_cuotas|

|Variables de salida|
|-------------------|
|Valor_cuota|

**Diagrama de flujo**

¡[texto](Tarea_bucles.png)

