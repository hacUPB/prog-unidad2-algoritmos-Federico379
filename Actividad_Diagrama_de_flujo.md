# **Ejercicio solucion de problema con algoritmo**





- Una empresa necesita calcular el ingreso total y el promedio mensual del sueldo de un empleado durante 6 meses. Diseña un algoritmo para solucionar el problema.


Datos de entrada
|nombre    |Descripcion        |
|----------|-------------------|
|ID   |identificador de empleados|
s1,s2,s3,s4,s5,s6|sueldos de los 6 meses|
||

Datos de salida
|nombre    |Descripcion          |
|----------|---------------------|
|prom   |promedio mensual|
|total| ingreso total|
|id|
||
 

 

Datos intermedios 

|nombre |descripcion |


 

 

 

 

 

 

 

Procedimientos 

Total = S1 + S2 + S3 + S4+ S5 + S6 

Prom = Total / 6 

 

Pseudocódigo 

 
```
Inicio 

Leer ID, S1, S2, S3, S4, S5, S6 

Total = S1 + S2 + S3 + S4+ S5 + S6 

Prom = Total / 6 

Mostrar  ID, Total, Prom 

Fin 
 ```

 

 

A = 15 

B = 2 

 

A > B à Verdadero 

A = B à Falso 

 

A >= 0 à Verdadero 


**Ejercicio 1**

Un acuario necesita determinar cuántos litros o galones de agua caben en un acuario, pero solo dispone de una cinta métrica. Diseña un algoritmo para solucionar el problema. 

 


Datos de entrada
|nombre    |Descripcion        |
|----------|-------------------|
|largo  |largo del tanque en cm|
|ancho|ancho del tanque en cm|
|alto|alto del tanque en cm|
|unidad|unidad de medida (litro o galon) del volumen total|
||

Datos de salida
|nombre    |Descripcion          |
|----------|---------------------|
|volumen_lt    |volumen total en litros|
|volumen_gal|volumen total en galones|
||

 

 

 

Pseudocódigo 

 
```
Inicio 

Mostrar “Por favor ingrese las medidas del tanque” 

Leer Largo, Ancho, Alto 

Mostrar “Ingres L para litros y G para galones” 

Leer Unidad 

 

Volumen = Largo * Ancho * Alto   //volumen en cm3 equivalente a mL 

Volumen_lt = Volumen/1000       //en Litros 

 

Si Unidad = “G” 

Volumen_gl = Volumen_lt * 0.26 

Mostrar Volumen_gl 

Si no 

Mostrar Volumen_lt 

Fin Si 

Fin 
```

**Ejercicio 2**

Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo

Datos de entrada
|nombre    |Descripcion        |
|----------|-------------------|
|lapices   |cantidad de lapices|
||

Datos de salida
|nombre    |Descripcion          |
|----------|---------------------|
|valor     |precio de los lapices|
||

```
inicio

leer lapices

si lapices < 1000

       valor=lapices*90

si no

       valor=lapices*85

fin si

mostrar valor

fin
```
 
**Ejercicio 3**

Un almacen de ropa tiene una promoción, por compras superiores a $250.ooo se les aplicara un descuento de 15%, de caso contrario solo se aplicara un 8% de descuento. Realiceun algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacen y de cuanto es el descuento que obtendrá.

Datos de entrada
|nombre  |descripción         |
|-----------|--------------------|
|valor        |valor de la compra|
||

Datos de salida
|nombre  |descripción   |
|-----------|-----------------|
|total |valor con descuento aplicado|
||
|descuento| descuento aplicado|
||

```
Inicio

Leer valor

Si valor>250.000

            Total=Valor*0.15

Si no

            Total=valor*0.08

Fin si

Mostrar total

Fin
```

**Ejercicio 4**

El director de una escuela esta organiando un viaje de estudios, y requiere determinar cuanto debe cobrar a cada alumno y cuanto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o mas, el costo por cada alumno es de 65.00; de 50 a 99 alumnos, el costo es de 70.00; de 30 a 49, de 95.00; y si son menos de 30, el costo de la renta del autobús es de 4000.00, sin importar el numero de alumnos.

Datos de entrada
|nombre  |descripción         |
|-----------|--------------------|
|estudiantes |numero de estudiantes que van|
||

Datos de salida
|nombre  |descripción   |
|-----------|-----------------|
|costo |valor que debe pagar cada estudiante|
||
|autobus| valor total del autobus|
||

```
Inicio

Leer estudiantes

Si estudiantes>100

                 Costo=65.00

                 Autobús=estudiantes*65.00

Si estudiantes (50,99)

              Costo=70.00

               Autobús= estudiantes*70.00

Si estudiantes (30,49)

       Costo=95.00

       Autobús= estudiantes*95.00

Si estudiantes<30

        Costo=4000/estudiantes

        Autobús=4000.00

Fin si

Fin
```




 

 