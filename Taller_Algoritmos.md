# Taller Algoritmos

1. **Verificación de peso de despegue**
    
    En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

  ![Diagrama_peso_de_despegue](./imagenes/peso%20aeronave.drawio.png)


4. **Control de combustible en pruebas**
    
    Durante un ensayo en banco de un motor a reacción, se mide el nivel de combustible cada minuto y se detiene el registro cuando el combustible baja del 10%. Mostrar el tiempo total de operación antes de llegar a ese punto.


    

    #### **Datos de entrada**

|nombre    |Descripcion        |
|----------|-------------------|
|combustible  |cantidad de combustible que se lee cada minuto|
||

#### **Datos de salida**

|nombre    |Descripcion        |
|----------|-------------------|
|tiempo   |tiempo transcurrido de la operación en minutos|
||

#### **Datos intermedios**

|nombre    |Descripcion        |
|----------|-------------------|
|capacidad| capacidad minima del tanque para la prueba (10%) |
||



**Pseudocodigo**

```
inicio

leer combustible

mientras  combustible >= capacidad*0.1

     tiempo = tiempo + 1

     leer combustible

mostrar "tiempo total de prueba:" tiempo

fin
 ```

3. **Control de temperatura en cabina**
    
    Un sistema mide cada 5 minutos la temperatura en cabina durante una hora. Si en algún momento se detecta una temperatura mayor a 27°C o menor a 18°C, debe indicar que se active el sistema de climatización.

**pseudocodigo**

