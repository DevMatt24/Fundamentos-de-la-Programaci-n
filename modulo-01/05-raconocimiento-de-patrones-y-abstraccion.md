# 1.5 - Reconocimiento de patrones y abstracción: aprender a encontrar lo importante

En los temas anteriores aprendimos a analizar situaciones, reconocer relaciones entre datos y dividir problemas complejos en partes más pequeñas.

Ahora vamos a desarrollar dos habilidades que nos permitirán comprender mejor los problemas y encontrar soluciones:

- Reconocer patrones.
- Abstraer información.

Aunque parecen conceptos diferentes, ambos nos ayudan a pensar de manera más organizada.

El reconocimiento de patrones nos permite identificar elementos, comportamientos o situaciones que se repiten.

La abstracción nos permite concentrarnos en la información importante y dejar de lado los detalles que no necesitamos para resolver un problema.

Vamos a estudiarlos desde situaciones cotidianas.

---

## 1. Reconocimiento de patrones: descubrir lo que se repite

¿Qué tienen en común estas situaciones?

- El sol sale cada mañana.
- Un semáforo cambia de rojo a verde y luego a amarillo.
- Una semana tiene siete días.
- Un jugador pierde una vida cada vez que recibe daño.
- Una persona recibe su sueldo todos los meses.

Todas presentan algo en común: existe un comportamiento, una característica o una secuencia que se repite.

A eso podemos llamarlo **patrón**.

Un patrón es una regularidad que podemos identificar en un conjunto de elementos o situaciones.

Reconocer patrones significa observar, comparar y descubrir qué característica se mantiene o qué regla se repite.

### Ejemplo 1: descubrir una secuencia numérica

Observa los siguientes números:

2 - 4 - 6 - 8 - 10

¿Puedes descubrir qué está sucediendo?

Vamos a analizarlos:

- De 2 a 4 aumentamos 2.
- De 4 a 6 aumentamos 2.
- De 6 a 8 aumentamos 2.
- De 8 a 10 aumentamos 2.

Encontramos una regularidad: cada número aumenta dos unidades respecto al anterior.

Por lo tanto, si continuamos siguiendo esa regla, el siguiente número sería 12.

No adivinamos el resultado. Observamos los datos, comparamos sus diferencias y descubrimos una regla.

### Ejemplo 2: reconocer un patrón en la vida cotidiana

Imagina que todas las mañanas realizas estas actividades:

1. Despertarte.
2. Lavarte los dientes.
3. Desayunar.
4. Prepararte para salir.

Después de varios días observas que repites prácticamente la misma secuencia.

Has reconocido un patrón de comportamiento.

¿Por qué es útil identificarlo?

Porque cuando conocemos una secuencia habitual podemos anticipar qué actividad viene después y organizar mejor nuestras acciones.

En programación ocurre algo parecido: identificar acciones que se repiten nos permite reconocer cuándo una tarea podría resolverse mediante una estructura repetitiva.

### Ejemplo 3: patrones en videojuegos

Imagina que estás jugando un videojuego y un enemigo se comporta de esta manera:

1. Camina hacia la derecha.
2. Llega hasta una pared.
3. Cambia de dirección.
4. Camina hacia la izquierda.
5. Llega hasta la otra pared.
6. Cambia nuevamente de dirección.

Después de observarlo durante un tiempo, descubres que repite ese comportamiento.

¿Qué acabas de reconocer?

Un patrón de movimiento.

No necesitas analizar cada movimiento como si fuera algo completamente nuevo. Descubriste una regla que explica su comportamiento.

Esto es muy importante en programación: muchas veces podemos comprender un sistema observando qué acciones se repiten y bajo qué condiciones.

---

## 2. No todos los patrones son numéricos

Es un error pensar que reconocer patrones consiste solamente en encontrar secuencias de números.

Los patrones pueden aparecer de diferentes maneras.

**Patrones numéricos:** una secuencia de números que sigue una regla.

Ejemplo:

3 - 6 - 9 - 12 - 15.

La regla es sumar 3.

**Patrones visuales:** figuras que se repiten o siguen una transformación.

Ejemplo:

Círculo - cuadrado - círculo - cuadrado - círculo.

La regla consiste en alternar dos figuras.

**Patrones de comportamiento:** acciones que se repiten bajo determinadas circunstancias.

Ejemplo:

Cada vez que un personaje recibe daño, pierde una vida.

**Patrones de organización:** elementos que mantienen una estructura semejante.

Ejemplo:

Cada producto de una tienda tiene un nombre, un precio y una cantidad disponible.

Reconocer estas regularidades nos permite comprender mejor cómo están organizadas las cosas.

---

## 3. ¿Cómo podemos reconocer un patrón?

No necesitamos adivinar. Podemos utilizar un pequeño procedimiento de razonamiento.

1. Observar los elementos.
2. Comparar sus características.
3. Identificar qué cambia y qué permanece igual.
4. Formular una posible regla.
5. Comprobar si esa regla explica los ejemplos.
6. Utilizarla para anticipar qué podría suceder después.

### Ejemplo resuelto

Observa esta secuencia:

5 - 10 - 20 - 40 - 80

**Paso 1. Observar**

Tenemos cinco números ordenados.

**Paso 2. Comparar**

- 5 × 2 = 10.
- 10 × 2 = 20.
- 20 × 2 = 40.
- 40 × 2 = 80.

**Paso 3. Identificar la regularidad**

Cada número es el doble del anterior.

**Paso 4. Formular la regla**

Multiplicar por 2.

**Paso 5. Comprobar**

80 × 2 = 160.

Por lo tanto, siguiendo esa regla, el siguiente número sería 160.

### Una observación importante

No debemos confundir una posible regla con una verdad absoluta.

Por ejemplo:

2 - 4 - 6

Podemos pensar que la regla es sumar 2 y que el siguiente número será 8.

Sin embargo, con solamente tres números podrían existir otras reglas que también expliquen esa secuencia.

Por eso, cuando analizamos patrones, debemos comprobar que la regla sea coherente con la información disponible.

---

## 4. Abstracción: aprender a distinguir lo importante

Ahora vamos a estudiar el segundo concepto.

Imagina que necesitas comprar una computadora.

Cuando analizas las opciones, encuentras información como:

- Precio.
- Memoria RAM.
- Procesador.
- Capacidad de almacenamiento.
- Color.
- Tamaño de la caja.
- Diseño del teclado.
- Peso.

¿Necesitas prestar atención a absolutamente todos esos detalles para decidir cuál computadora te conviene?

No necesariamente.

Si tu objetivo es elegir una computadora para programar, probablemente te interesen especialmente el procesador, la memoria RAM, el almacenamiento y el precio.

El color o el diseño pueden ser secundarios para esa decisión.

Esto nos permite comprender qué es la **abstracción**.

La abstracción consiste en concentrarnos en las características importantes de una situación o problema, dejando de lado los detalles que no son necesarios para el objetivo que queremos alcanzar.

No significa ignorar información sin motivo. Significa seleccionar la información según lo que necesitamos resolver.

### Una analogía: un mapa

Imagina que utilizas un mapa para llegar a una dirección.

El mapa muestra:

- Calles.
- Avenidas.
- Cruces.
- Nombres de lugares.
- Direcciones.

Pero no muestra absolutamente todo lo que existe en la ciudad.

No necesitas ver los muebles de cada casa, las personas que caminan por las veredas o los objetos que hay dentro de los negocios.

¿Por qué?

Porque el objetivo del mapa es ayudarte a orientarte y encontrar un camino.

El mapa representa una parte de la realidad, seleccionando la información que resulta útil para esa tarea.

Eso es una forma de abstracción.

---

## 5. Aplicar la abstracción a un problema

Vamos a trabajar con una situación concreta.

**Problema:** queremos crear un sistema que determine si un estudiante aprobó o desaprobó.

Imagina que tenemos esta información:

- Nombre: Martín.
- Edad: 19 años.
- Curso: Programación.
- Nota del primer examen: 7.
- Nota del segundo examen: 8.
- Color favorito: azul.
- Ciudad: Salta.
- Nota mínima para aprobar: 6.

¿Necesitamos todos esos datos para determinar si aprobó?

No.

Vamos a razonar:

- El nombre puede servir para identificar al estudiante.
- Las notas son necesarias para realizar el cálculo.
- La nota mínima establece la condición de aprobación.
- La edad no interviene en este cálculo.
- El color favorito no tiene relación con el resultado.
- La ciudad tampoco es necesaria para determinar el promedio.

Por lo tanto, para resolver este problema podemos concentrarnos en las notas y en el criterio de aprobación.

Si calculamos el promedio:

(7 + 8) / 2 = 7,5.

Como 7,5 es mayor o igual a 6, el estudiante aprobó.

Observa lo que hicimos: teníamos mucha información, pero seleccionamos solamente la que necesitábamos para resolver el problema.

Eso es abstraer.

### ¿Qué pasaría si cambiara el objetivo?

Supongamos que ahora queremos crear un sistema para registrar estudiantes y organizar sus datos personales.

En ese caso, la edad, el nombre y la ciudad podrían ser importantes.

La información que antes considerábamos innecesaria ahora puede resultar útil.

**Conclusión:** un dato no es importante o irrelevante por sí mismo. Su importancia depende del problema que queremos resolver.

---

## 6. Diferenciar abstracción y descomposición

Es importante no confundir estos dos conceptos porque cumplen funciones diferentes.

Recordemos lo que aprendimos en el tema anterior.

**Descomposición:** consiste en dividir un problema grande en partes más pequeñas.

**Abstracción:** consiste en seleccionar la información importante y dejar de lado los detalles que no necesitamos.

Veamos un ejemplo.

Queremos desarrollar un sistema para administrar un videojuego.

Podemos utilizar la descomposición para separar el sistema en:

- Movimiento del personaje.
- Sistema de vidas.
- Sistema de puntuación.
- Enemigos.
- Inventario.

Ahora concentrémonos en el sistema de vidas.

Para resolverlo podemos utilizar la abstracción.

Nos interesa conocer:

- Cuántas vidas tiene el personaje.
- Cuándo pierde una vida.
- Qué sucede cuando llega a cero.

En cambio, no necesitamos conocer el color de su ropa ni el diseño del escenario para determinar si perdió todas sus vidas.

Podemos resumirlo así:

| Concepto | ¿Qué hacemos? |
|---|---|
| Descomposición | Dividimos el sistema en partes. |
| Abstracción | Seleccionamos la información relevante. |
| Reconocimiento de patrones | Identificamos comportamientos o reglas que se repiten. |

Las tres habilidades se complementan y nos ayudan a razonar mejor.

---

## 7. Reconocer patrones y abstracción en conjunto

Ahora vamos a combinar los dos conceptos.

Imagina un videojuego donde existen diferentes enemigos.

Cada enemigo tiene:

- Nombre.
- Color.
- Tamaño.
- Velocidad.
- Cantidad de vidas.
- Comportamiento.

Después de observarlos, descubrimos que todos tienen algo en común: cuando reciben un ataque, pierden una cantidad de vida.

**Primero: reconocimiento de patrones.**

Identificamos que existe un comportamiento que se repite entre los enemigos.

**Segundo: abstracción.**

Para analizar ese comportamiento, no necesitamos prestar atención a sus colores, nombres o tamaños.

Nos concentramos en los elementos importantes:

- Vidas actuales.
- Daño recibido.
- Vidas restantes.

**Tercero: razonamiento.**

Podemos establecer una regla:

Vidas restantes = vidas actuales - daño recibido.

Por ejemplo:

Un enemigo tiene 10 puntos de vida y recibe 3 puntos de daño.

10 - 3 = 7.

Le quedan 7 puntos de vida.

Ahora podemos aplicar la misma lógica a otros enemigos, independientemente de su apariencia.

Este ejemplo demuestra cómo las habilidades que estamos aprendiendo pueden combinarse para comprender y resolver problemas.

---

## 8. ¿Por qué son importantes estas habilidades en programación?

Cuando desarrollamos un programa, normalmente trabajamos con situaciones que pueden contener mucha información y diferentes comportamientos.

El reconocimiento de patrones nos permite:

- Detectar acciones que se repiten.
- Identificar regularidades.
- Anticipar comportamientos.
- Reconocer reglas comunes entre diferentes situaciones.

La abstracción nos permite:

- Concentrarnos en los datos necesarios.
- Evitar distraernos con información irrelevante.
- Representar situaciones complejas de manera más sencilla.
- Diseñar soluciones enfocadas en el objetivo.

Ambas habilidades ayudan a evitar que intentemos resolver todo al mismo tiempo o que nos perdamos entre detalles innecesarios.

Recordemos que la computadora ejecuta instrucciones, pero somos nosotros quienes debemos comprender qué información utilizar y qué reglas establecer.

---

## Ejercicios para desarrollar el razonamiento

Ahora vamos a practicar. En estos ejercicios no alcanza con responder rápidamente: necesitamos explicar cómo llegamos a nuestras conclusiones.

### Ejercicio 1. Encontrar patrones numéricos

Observa las siguientes secuencias:

A) 2 - 4 - 6 - 8 - ___

B) 5 - 10 - 20 - 40 - ___

C) 1 - 4 - 9 - 16 - ___

Para cada una:

1. Identifica qué regla observas.
2. Explica cómo llegaste a esa conclusión.
3. Indica cuál sería el siguiente número.
4. Comprueba si tu regla funciona con todos los elementos.

### Ejercicio 2. Reconocer un patrón de comportamiento

Un personaje de videojuego realiza estas acciones:

- Camina hacia adelante.
- Llega a un obstáculo.
- Cambia de dirección.
- Camina nuevamente.
- Llega a otro obstáculo.
- Cambia de dirección.

Responde:

1. ¿Qué comportamiento se repite?
2. ¿Qué regla podrías establecer?
3. ¿Qué sucedería si no existieran obstáculos?
4. ¿Qué información necesitarías para representar este comportamiento?

### Ejercicio 3. Distinguir información importante

Queremos desarrollar un sistema que calcule el importe de una compra.

Tenemos estos datos:

- Nombre del cliente.
- Color favorito.
- Precio del producto.
- Cantidad comprada.
- Ciudad de residencia.
- Marca del producto.
- Dirección de entrega.

Responde:

1. ¿Qué información necesitas para calcular el importe?
2. ¿Qué datos no intervienen directamente en ese cálculo?
3. ¿Por qué los consideraste innecesarios?
4. ¿Cambiaría tu respuesta si el objetivo fuera organizar la entrega del producto?

### Ejercicio 4. Aplicar abstracción a un videojuego

Queremos determinar si un personaje perdió todas sus vidas.

Disponemos de esta información:

- Nombre del personaje.
- Color de su vestimenta.
- Cantidad de vidas.
- Nivel actual.
- Puntuación.
- Estado de sus vidas.

Responde:

1. ¿Qué información es necesaria para resolver el problema?
2. ¿Qué información podemos dejar de lado?
3. ¿Qué condición debería cumplirse para indicar que el personaje perdió?
4. Explica por qué seleccionaste esos datos.

### Ejercicio 5. Diferenciar los conceptos

Explica con tus palabras la diferencia entre:

- Reconocimiento de patrones.
- Abstracción.
- Descomposición.

Después inventa una situación cotidiana donde puedas aplicar los tres conceptos.

### Ejercicio 6. Reto de razonamiento

Una tienda vende diferentes productos. Cada producto tiene un nombre, un precio, una categoría, un color y una cantidad disponible.

Queremos desarrollar un sistema que permita conocer cuándo un producto se está quedando sin existencias.

Responde:

1. ¿Qué problema queremos resolver?
2. ¿Qué información necesitamos?
3. ¿Qué información no es necesaria para este objetivo?
4. ¿Qué patrón podríamos reconocer si observamos las ventas durante varios días?
5. ¿Cómo dividirías el problema en tareas más pequeñas?
6. ¿Qué regla utilizarías para determinar cuándo quedan pocas unidades?

Justifica cada decisión.

---

## Resumen

- Un patrón es una regularidad que podemos identificar en diferentes elementos o situaciones.
- Reconocer patrones significa observar, comparar y encontrar reglas que se repiten.
- Los patrones pueden ser numéricos, visuales, de comportamiento o de organización.
- La abstracción consiste en concentrarnos en la información importante para resolver un problema.
- Un dato puede ser relevante para un problema e irrelevante para otro.
- La descomposición divide un problema en partes, mientras que la abstracción selecciona la información necesaria.
- Estas habilidades se complementan para facilitar el análisis y la resolución de problemas.

### Idea clave

**Pensar lógicamente no consiste en observar absolutamente todo, sino en aprender a reconocer qué se repite, qué información importa y cómo utilizarla para llegar a una solución.**

Cuanto mejor podamos identificar patrones y abstraer información, más preparados estaremos para comprender problemas complejos y diseñar soluciones.

➡️ **Siguiente tema:** [1.6 - Secuencias e instrucciones: aprender a ordenar acciones](./06-secuencias-e-instrucciones.md)
