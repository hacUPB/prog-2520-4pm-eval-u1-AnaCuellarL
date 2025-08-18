# Taller Unidad 2

## Ejercicio condicionales:

1. **Verificación de peso de despegue:** En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

**Solución**

**Analisis**
 |Variables de entrada| Descripción|
 |--------------------|------------|
 |peso_maximo|Peso máximo de despegue de la aeronave a analizar|
 |peso_combustible| Peso del combustible estimado|
 |peso_carga| Peso de la carga estimada(pasajerosy equipaje)|
 |peso_vacio| Peso de la aeronave en vacio|

|Variable intermedia| Descripción|
|-------------------|------------|
|peso_estimado| La suma de los pesos del combustible, carga y vacio|

 |Variables de salida| Descripción|
 |-------------------|------------|
 |lim_max| indica si se sobrepasa el peso maximo de despegue o no|

**Diagrama de Flujo:**

¡[imagen](Diagrama_condicionales.png)

2. **Control de temperatura del motor:** Durante una inspección de rutina, se mide la temperatura de un motor de turbina. Si la temperatura es mayor a un valor crítico, se debe indicar "Peligro: sobrecalentamiento". Si está dentro del rango seguro, indicar "Operación normal". Si es demasiado baja, indicar "Motor frío – Calentar antes de operar".

**Solución**

**Analisis**
|Variables de entrada| Descripción|
|--------------------|------------|
|temperatura_turbina| La temperatura de la turbina|
|val_critico| Valor critico de la temperatura de la turbina|
|val_bajo| Valor muy bajo de temperatura de la turbina|

|Valores de salida| Descripción|
|-----------------|------------|
|ind_temperatura| La indicación de la temperatura de la turbina|

**Diagrama de flujo**

## Ejercicio Bucles:

2. **Registro de altitudes de vuelo:** Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

**Solución:**

**Analisis**

|Variable de entrada| Descripción|
|-------------------|------------|
|altitud| La altitud registrada|

|Variable de control| 
|-------------------|
|i|

|Variable de salida| Descripción|
|altitud_tiempo| Altitudes en el tiempo|

**Diagrama de flujo**

i=i+10


## Ejercicio de Bucles y condicionales:

3. **Simulación de conteo de pasajeros:** Durante el abordaje, un sistema cuenta a los pasajeros que ingresan. Si el número total supera la capacidad máxima, el sistema debe detener el conteo y mostrar un mensaje de alerta.