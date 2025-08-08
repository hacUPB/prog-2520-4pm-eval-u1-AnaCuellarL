# Sistema Binario

## Valores booleanos

- La logica Booleana es un campo escencial de la teoría de la computación y se fundamenta en el sistema algebraico que permite representar y manipular proposiciones mediante aplicación de operadores lógicos desarrollado por George Boole. Este sistema establece la base de la representación y procesamiento de información binaria en la computación moderna.

 Esta lógica trabaja con valores binarios, donde cada variable puede tener solo dos estados posibles:

   - Verdadero (1)
   
   - Falso (0)

Esto es escencial en la toma de desiciones y el diseño de circuitos lógicos en electronica y en el control de flujos de ejecución mediante condicionales y bucles en programación.

![alt text](image.png)

## Bits y Bytes

- Los bits y los bytes son escenciales para entender el procesamiento y representación de la información.

  - Un bit es la unidad más basica de información binaria y puede adoptar uno de dos estados **1** ó **0**.

  - Un byte consta de ocho bits, lo cual amplia significativamente las posibilidades de representación de informació. Con un byte se pueden formar 256 combinaciones únicas de estado binario ($2^8$).

**Ejercicio 1:**

En la siguiente figura se muestran diferentes estados que se pueden representar usando una palabra binaria de 3 bits. Responde la pregunta de la imagen:

![alt text](image-1.png)

  **Respuesta:**

  Si tiene *n* cantidad de variables entondes puede haber $2^n$ siendo n la cantidad de estados, y 2 los digitos binarios posibles.

## Sistema decimal a binario

Hay dos formas de convertir un numero decimal (en base 10) a un número binario (en base 2):

1. dividir el decimal por 2 hasta que el residuo de 0:

  **Ejemplo:**

  Número 28 a binario:
    
    28 | 2  Residuo: 0
    14 | 2  Residuo: 0
    7  | 2  Residuo: 1
    3  | 2  Residuo: 1
    1  | 2  Residuo: 1
    0  | 

Número: 11100

y el número de los residuos se lee de abajo hacia arriba.

2. Una  caja de conversión:


|256|128|64|32|16| 8| 4| 2| 1|
|---|---|--|--|--|--|--|--|--|
|   |   |  |  |  |  |  |  |  |


**Ejemplo:**

Número 28

|256|128|64|32|16| 8| 4| 2| 1|
|---|---|--|--|--|--|--|--|--|
| 0 | 0 |0 |0 |1 |1 |1 |0 |0 |


## De binario a decimal

- Para convertir un número binario a decimal simplemente al ser un sistema posicional la conversión se da con la sumatoria de los números por la base del sistema a la posición del número.

  **Ejemplo:**

  Numero 1101 a Decimal

 

  Entonces:

  1 * $2^4$ + 1 * $2^3$ + 0 * $2^2$ + 1 * $2^1$ 

  Entonces:

  1 * 16 + 1 * 6 + 0 * 4 + 1 * 2 

  Entonces: 

  16 + 6 + 0 + 2 = 24

**Ejercicio 2:**

1. Convierte el número decimal 22 a binario:

  **Respuesta:**


|256|128|64|32|16| 8| 4| 2| 1|
|---|---|--|--|--|--|--|--|--|
| 0 | 0 |0 |0 |1 |0 |1 |1 | 0|

2. ¿Cuál es el resultado decimal del número binario 10110?

  **Respuesta:**

 | 5 | 4 | 3 | 2 | 1 |
 |---|---|---|---|---|
 | 1 | 0 | 1 | 1 | 0 |

 Entonces:

 1 * $2^5$ + 0 * $2^4$ + 1 * $2^3$ + 1 * $2^2$ + 0 * $2^1$

 = 1 * 32 + 0 * 16 + 1 * 6 + 1 * 4 + 0 * 2

 = 32 + 0 + 6 + 4 + 0

 = 42

## Otros datos en binario

