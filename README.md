# **Lógica de la programación Primer Cuatrimestre**

## *Guía de temas y ejercicios*

**Profesor**: Romero Guillermo Felix

**Año:** 2025

1. [Estructura de un codigo c#](\docs\codestructure.md)  
2. [Consola](\docs\console.md)  
3. [Variables](\docs\variables\variables.md)
    1. [int](\docs\variables\int.md)
    2. [float](\docs\variables\float.md)
    3. [bool](\docs\variables\bool.md)
    4. [char](\docs\variables\char.md)
    5. [string](\docs\variables\string.md)
    6. [object](\docs\variables\object.md)
4. [Condicional IF-ELSE](\docs\if.md)  
5. [Switch](\docs\switch.md)  
6. [While](\docs\while.md)  
7. [For](\docs\for.md)  
8. [Métodos](\docs\methods.md)  
9. [Colleciones Arrays](\docs\array.md)  
10. [Colleciones Listas](\docs\list.md)  
11. [Colleciones Matrices](\docs\exercises.md)  
> [Ejercicios](\docs\exercises.md)


# **Concatenar mensajes**

Tanto el Print como el Debug.Log reciben un “texto” entre comillas (“ ”), estos pueden ser varios en un solo lugar y Unirse, sumarse o mejor dicho CONCATENARSE.

Para lograr unir estos mensajes simplemente tenemos que.

![][image4]


## Ejercicio n°005

Crear una variable de valor numérico entero e imprimir el resultado.

## Ejercicio n°006

busquemos nuestro **ejercicio n°003** y volvamos a hacerlo, pero esta vez reemplazando nuestro nombre(string) y nuestra edad(int) con variables

# **Operaciones**

# **suma**

![][image11]

# **resta**

![][image12]

# **multiplicación**  

![][image13]

# **división**

![][image14]

# **módulo**

el módulo es en realidad el resto de una división, si el resto es 0, quiere decir 2 cosas… que el **primer** número es múltiplo del **segundo**.

* que ese **primero** número es **par**.

![][image15]

# **potencia**

![][image16]

![][image17]

# **raíz**

![][image18]

# **If (condicional)**

Algunas veces vamos a tener la necesidad de dividir el algoritmo dependiendo una o varias condiciones, para ello vamos a hacer uso de la estructura selectiva **if.**

*Esta estructura se puede analizar en tres partes. **sentencia, condición** y **cuerpo***

# **sentencia if, else, else if**

**If (SI):** 

Es la primera condición, el primer camino a tomar, se puede decir que es la cabeza de la estructura. 

Una vez sentenciado se le puede continuar con un **\[ else if \]** o un **\[ else \]**

*“si esto se cumple, tomo este camino”*

**else (SINÓ):** 

es la condición contraria y por descarte del **\[ if \]** o **\[ else if \]** de arriba, o el segundo camino a tomar. 

Siempre va a ir después de un **\[ if \]** o un **\[ else if \].** 

Una vez sentenciado no se le puede continuar con ninguna otra sentencia, esta es la última y la que cierra la estructura.

*“si el otro no se cumple, tomo este otro camino”*

**else if (SINÓ SI):** 

es la condición contraria al  **\[ if \]** o a otro **\[ else if \].** Se puede decir que es una condición condicionada por otra. Es como decir “en caso contrario y además si se cumple esta condición tomo ese camino”

Se puede usar como filtro, o para tomar rangos de valores específicos, También se usan como opciones intermedias entre el  **\[ if \]** y el  **\[ else \]**

*“si el otro no se cumple y ademas esto tambien se cumple, tomo este otro camino””*

# **Condición**

Una condición en resumen es un booleano, por lo tanto va a tener un valor verdadero o falso. 

Dentro de la estructura **if** la condición se pone dentro de los paréntesis **( )**

Esto va indicar si la sentencia se cumple, el flujo del código va a entrar al cuerpo.

![][image19]

# **Cuerpo** 

el cuerpo de un if else o else if, o sea, su camino resultante se escribe entre llaves **{ }** por ejemplo.

# 

# 

# **Switch**

![][image20]

# **While**

Un While va a repetir lo que tiene en su cuerpo mientras lo que está entre paréntesis se cumpla.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               

![][image21]

# 

# 

# **Extras**

# **Porcentaje**

* para calcular el **porcentaje** de un número conociendo el valor actual…

*Por ejemplo: sabiendo que 1000 es mi máximo, ¿cuanto porcentaje es 200?*

![][image22]

* para calcular el **porcentaje inverso** conociendo el mismo porcentaje.

*Por ejemplo: sabiendo que 1000 es mi maximo, ¿cuanto es mi 20%?*

![][image23]

# **Random**

Para calcular un numero aleatorio necesitamos usar la clase Random y su función Range. El mismo Random devuelve un valor numérico  se puede almacenar en una variable

**para enteros:**

* primer parametro: incluyente  
* segundo parametro: excluyente (no entra)

![][image24]

**para flotantes:**

* primer parametro: incluyente  
* segundo parametro: incluyente

![][image25]

# **Probabilidad**

Conceptualmente hablando de probabilidad vamos a necesitar tener un rango de valores para saber si mi probabilidad está por debajo o por encima.

Normalmente acá trabajamos mucho con probabilidades de **n / 100** por lo que el algoritmo básico seria algo asi como…

![][image26]

conceptualmente solo estamos agarrando 2/10, entonces da igual si lo hacemos así..

![][image27]

# **Obtener un mayor ![][image28]**

# 

# **Modelo de parcial**

## 

## Ejercicio n°020 (Carta especial)

En un videojuego de cartas podemos encontrar una carta conjuro que tiene la

siguiente descripción:

**“En el próximo ataque, tendrá una 50% de acertar. Si este acierta se sumará al daño base un 20% de la cantidad de cartas en el cementerio”**

Sabiendo que el daño base es 10 y la reducción por la defensa del enemigo es del 30%,

calcule y muestre el daño final. 

La cantidad de cartas en el cementerio puede ser random o pública para la modificación

## 

## Ejercicio n°021 (Torretas: radio de ataque)

Una torreta compuesta por dos cañones que tienen ángulos de visión diferentes.

**Nuestra torreta (radio de detección)**

Cuenta con **50 metros para unidades terrestres** y **250 metros para unidades aéreas**.

**En el área de juego**

* Generar entre 7 y 10 unidades terrestres con distancias entre 20 y 70 metros de distancia.  
* Generar entre 10 y 25 unidades aéreas con distancias entre 100 y 300 metros de distancia.

Sabiendo que ambos pelotones se encuentran a diferentes distancias. Indique cuantos aéreos y cuantos terrestres entran en el rango de la torreta.

Aclaración: el cañón aéreo no detecta terrestres y viceversa.

## 

## 

## Ejercicio n°022 (Hack de contraseñas)

Queremos generar un algoritmo para un componente dentro de un juego de espionaje online, estamos programando un aparato que hackea contraseñas de cofres de otros jugadores.

Sabiendo que las contraseñas son numéricas de **3 dígitos (000 a 999\)**, programar el algoritmo de hackeo de búsqueda de contraseña.

## 

## 

## Ejercicio n°023 (Combo maná)

En un juego de rol, un personaje realiza ataques hasta que se le consuma el maná.

Cada ataque cuesta 10 de maná y el daño varía entre 100 y 200\. Los ataques tienen

una chance de crítico del 50% que duplica el daño.

1. Indicar el daño total.  
2. Indicar la cantidad de ataques realizados sabiendo que el valor inicial de mana varía entre 100 y 150\.  
3. Indicar en cada ataque el daño realizado y en caso de que sea crítico también indicarlo.

## Ejercicio n°024 (Inteligencia Artificial muy simple)

Programe la IA de un personaje que cuenta con los siguientes estados:

El personaje tiene 4 estados posibles:

**Inactivo**

* Si la distancia del enemigo es menor a 5 metros y la vida del personaje es menor a 20, cambiar el estado del personaje a Huir.  
* Si la distancia del enemigo es menor a 5 metros, indicar que no hay ningún riesgo.

**Alerta**

* Si la distancia del enemigo es menor a 2 metros, cambiar al estado Atacar  
* Si la vida del personaje disminuye de 20, cambiar al estado Huir.  
* Si la distancia del enemigo es mayor a 5 metros, cambiar al estado Inactivo.

**Atacar**

* Golpear al enemigo con un daño aleatorio entre 100 y 200 hasta que muera. Indicar cuantos golpes fueron necesarios y pasar al estado Inactivo

**Huir**

* Informar si el personaje pudo huir o no, sabiendo que hay un 50% de chances de lograrlo.

Sabemos que el estado actual del enemigo es que esta a una distancia aleatoria entre 1 y 30 metros y tiene entre 2000 y 3500 de vida.

## 

## Ejercicio n°025 (Combo melee \+ críticos \+ el mejor de todos)

Realice un programa que golpee a un enemigo **10 veces**.

Sabemos que el daño base varía entre 100 y 200, que la chance de critico es del 30% y que si pega critico es 230 de daño.

1. *Indicar cual de los golpes no críticos fue el más fuerte.*  
2. *Indicar cuantos golpes críticos dio.*  
3. *Indicar el promedio de daño.*  
4. *Indicar el daño final.*  
5. *Cada vez que se da un golpe imprimir el daño realizado.*  
   

## Ejercicio n°026 (Niveles de Brillo)

En un juego de pelea medieval, el brillo que tienen las armaduras varía de color e intensidad según el nivel que tenga el objeto.

Sabemos que..

*  Si el ítem tiene un nivel menor a 4 el brillo será de color blanco y la intensidad será tenue.  
* si el nivel es 4, 5, 6 o 7 será de color amarillo y la intensidad moderada.   
* Al llegar al nivel 8 el brillo será verde y la intensidad brillante,  
* en el nivel 9 será azul e intenso  
* nivel 10 (el máximo) será Dorada y encandilante.  
1. Mostrar por consola las características del objeto según su nivel.  
2. Además, debe considerar que no se puedan tomar valores incorrectos del nivel.

# 

# 

# 

# **FOR**

Al igual que el While, este se va a repetir siempre y cuando la condición se cumpla.

En este ejemplo va a entrar 10 veces printeando el índice actual![][image29]

## Ejercicio n°027 (REPETIR)

	repetir el ejercicio 21, 22 y 25 pero usando **for**

## Ejercicio n°028 (Spawner)

Un spawn de enemigos elementales genera entre **40 y 70 enemigos**. Este tiene la probabilidad de spawnear **enemigo de fuego (50%)** y **enemigo de hielo (50%)** en la misma medida.

1. Mostrar cuántos de fuego y de hielo se generaron.  
2. Ahora agregar que dentro de la probabilidad de **enemigo de fuego (50%)** haya una probabilidad del **20% de generar enemigo tóxico** o sea…

    ( **30%** \+ **20%** ) \+ ( **50%** )

   

# 

# **Métodos**

# **Introducción**

Los métodos (o funciones) son como cajas cerradas en las que se puede encapsular y ejecutar código. A la hora de ejecutarse tienen que ser muy descriptivos, por ejemplo.

![][image30]

No sabemos que es lo que hay dentro de estos métodos, pero por sus nombres podemos intuir que es lo que hacen.

# **Ejecutar metodo**

![][image31]

Como ven, es tan simple como crear un método con un nombre, meterle algo adentro y ejecutarlo

# **Ejecutar metodo \+ Parámetro**

![][image32]

Entre **paréntesis ( )** tengo que configurar un tipo de dato para luego poder recibirlo dentro de la Función

# **Ejecutar metodo \+ Retorno**

![][image33]

Como se puede ver ahora la función también sirve para devolver cosas.

Para eso hay que acordarse de dos cosas importantes.

Configurar la salida 

![][image34]

usar el retorno

![][image35]

# **Ejecutar metodo \+ Parámetro \+ Retorno**

Ahora vamos a combinar todo

![][image36]

# **Extras**

**Parámetros Opcionales**

![][image37]

Como se puede ver, se está usando Sumar de 4 formas distintas sin dejar de ser la misma función. Vamos a Analizarlo…

![][image38]

Para que un parámetro sea **opcional**, hay que darle un valor en la misma inicialización.

Podemos poner parámetros **opcionales** después de **obligatorios**, pero no podemos poner **opcionales** y luego **obligatorios.**

# 
