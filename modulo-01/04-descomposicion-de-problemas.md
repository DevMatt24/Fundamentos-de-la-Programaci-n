#Descomposición de problemas: dividir para resolver

En el tema anterior aprendimos a utilizar el pensamiento lógico para analizar situaciones, identificar información, reconocer patrones y encontrar soluciones razonables.

Ahora vamos a profundizar en una habilidad que nos ayudará a resolver problemas cada vez más complejos: la **descomposición de problemas**.

Cuando nos encontramos frente a un problema grande, es común no saber por dónde comenzar. Podemos intentar resolverlo todo al mismo tiempo, pero eso suele generar confusión.

Una estrategia mucho más efectiva consiste en dividir el problema en partes más pequeñas, comprender qué debemos hacer en cada una y después relacionarlas para construir una solución completa.

A esta técnica la llamamos **descomposición**.

## ¿Qué es la descomposición de problemas?

La descomposición de problemas consiste en dividir un problema complejo en otros más pequeños y manejables, de manera que podamos comprenderlos y resolverlos por separado.

Dicho de una forma sencilla: en lugar de intentar resolver todo de una vez, identificamos las partes que componen el problema y trabajamos sobre ellas.

### Una analogía: armar un rompecabezas

Imagina que tienes delante un rompecabezas de 1.000 piezas.

Si intentaras colocar todas las piezas al azar, probablemente tardarías mucho y te resultaría difícil encontrar dónde corresponde cada una.

¿Qué podrías hacer?

1. Separar las piezas de los bordes.
2. Agrupar las piezas según sus colores.
3. Identificar las partes que parecen pertenecer a una misma zona.
4. Armar cada sector por separado.
5. Unir los sectores hasta completar la imagen.

Observa que el rompecabezas sigue siendo el mismo. No eliminaste ninguna pieza ni cambiaste el objetivo.

Simplemente organizaste el trabajo para que fuera más fácil resolverlo.

En programación hacemos algo parecido: dividimos un problema grande en tareas pequeñas que podemos analizar y resolver con mayor claridad.

**Idea clave:** dividir un problema no significa cambiarlo ni simplificarlo artificialmente. Significa organizarlo para comprender mejor cómo resolverlo.

---

## 1. ¿Por qué necesitamos dividir los problemas?

Imagina que queremos desarrollar un videojuego.

El objetivo general es crear un juego en el que un personaje pueda moverse, saltar, recoger objetos, evitar enemigos y completar niveles.

¿Podríamos intentar resolver todas esas funcionalidades al mismo tiempo?

Podríamos intentarlo, pero sería difícil controlar todos los detalles y detectar dónde aparecen los errores.

En cambio, podemos dividir el proyecto en diferentes partes:

- Movimiento del personaje.
- Sistema de saltos.
- Detección de colisiones.
- Recolección de objetos.
- Comportamiento de los enemigos.
- Sistema de puntuación.
- Administración de niveles.

Ahora tenemos diferentes problemas más pequeños.

Podemos trabajar primero en el movimiento, comprobar que funciona y después continuar con las demás funcionalidades.

### ¿Qué ventajas obtenemos?

**1. Mayor comprensión**

Es más fácil entender una tarea pequeña que intentar comprender un sistema completo de una sola vez.

**2. Mejor organización**

Podemos identificar qué debemos resolver primero y qué tareas dependen de otras.

**3. Detección de errores**

Si una parte no funciona, podemos investigar esa sección sin tener que revisar absolutamente todo el sistema.

**4. Reutilización**

Algunas soluciones pueden utilizarse en diferentes partes de un mismo proyecto.

**5. Facilidad para realizar cambios**

Si necesitamos modificar una funcionalidad, podemos trabajar sobre la parte correspondiente sin alterar innecesariamente las demás.

---

## 2. Aprender a identificar las partes de un problema

La descomposición comienza cuando dejamos de observar un problema como una única tarea y empezamos a preguntarnos qué actividades necesitamos realizar para resolverlo.

Vamos a trabajar con una situación cotidiana.

### Ejemplo: organizar una compra en el supermercado

Imagina que tu objetivo es realizar una compra para toda la semana.

A simple vista, parece una sola actividad: ir al supermercado y comprar lo necesario.

Pero si analizamos mejor la situación, descubrimos que existen diferentes tareas:

1. Determinar qué alimentos necesitamos.
2. Revisar qué productos tenemos en casa.
3. Preparar una lista de compras.
4. Establecer cuánto dinero podemos gastar.
5. Buscar los productos.
6. Calcular el importe total.
7. Pagar la compra.
8. Comprobar que llevamos todos los productos.

Ahora podemos observar que cada tarea tiene un propósito diferente.

Por ejemplo, no tendría mucho sentido preparar una lista de compras sin saber qué productos necesitamos.

Tampoco tendría sentido intentar calcular el importe final antes de conocer los precios y las cantidades.

Esto nos permite descubrir algo importante:

**Las partes de un problema no solamente están relacionadas: muchas veces necesitan resolverse siguiendo un orden.**

### Practiquemos el razonamiento

Supongamos que tenemos un presupuesto de 50.000 pesos.

Durante la compra encontramos:

- Arroz: 3.000 pesos.
- Leche: 2.000 pesos.
- Carne: 15.000 pesos.
- Verduras: 8.000 pesos.

Para saber cuánto gastamos, primero necesitamos reunir los precios y después sumarlos.

3.000 + 2.000 + 15.000 + 8.000 = 28.000 pesos.

Ahora podemos comparar el resultado con nuestro presupuesto:

50.000 - 28.000 = 22.000 pesos disponibles.

Observa cómo una actividad aparentemente sencilla contiene diferentes operaciones que podemos separar y analizar.

---

## 3. De un problema grande a pequeñas tareas

Vamos a utilizar un ejemplo más relacionado con la programación.

**Problema:** queremos desarrollar un sistema que permita registrar las ventas de una tienda, calcular el total vendido y mostrar cuánto dinero ingresó durante el día.

Si intentáramos resolver todo de una vez, tendríamos que pensar en demasiadas cosas.

Por eso, vamos a descomponer el problema.

### Paso 1. Comprender el objetivo general

Necesitamos registrar las ventas y conocer el dinero total obtenido.

### Paso 2. Identificar las tareas principales

Podemos separar el sistema en estas actividades:

1. Registrar una venta.
2. Obtener el precio de los productos.
3. Calcular el importe de cada venta.
4. Acumular los importes.
5. Mostrar el total recaudado.

### Paso 3. Analizar cada tarea

Ahora podemos observar qué necesitamos para resolver cada una.

**Tarea 1: registrar una venta**

Necesitamos conocer qué producto se vendió y cuántas unidades se compraron.

**Tarea 2: obtener los precios**

Necesitamos conocer el precio correspondiente a cada producto.

**Tarea 3: calcular el importe**

Multiplicamos el precio por la cantidad comprada.

**Tarea 4: acumular los importes**

Sumamos el importe de cada venta al dinero acumulado anteriormente.

**Tarea 5: mostrar el resultado**

Presentamos cuánto dinero ingresó durante el día.

### Paso 4. Relacionar las tareas

Observa que no podemos calcular el importe de una venta sin conocer primero su precio y cantidad.

Tampoco podemos calcular el total recaudado sin haber registrado y calculado las ventas.

Podemos representar la relación de esta manera:

```text
REGISTRAR VENTAS
       |
       v
OBTENER PRECIOS Y CANTIDADES
       |
       v
CALCULAR CADA VENTA
       |
       v
ACUMULAR LOS IMPORTES
       |
       v
MOSTRAR TOTAL RECAUDADO
```

Esta representación nos permite comprender cómo se conectan las diferentes partes del problema.

**Lo importante no es solamente dividir: también debemos comprender cómo se relacionan las partes para alcanzar el objetivo general.**

---

## 4. Las partes de un problema pueden dividirse nuevamente

Una característica interesante de la descomposición es que una tarea pequeña también puede contener otras tareas.

Volvamos al sistema de ventas.

Habíamos identificado una actividad llamada «registrar una venta».

Pero ¿qué necesitamos hacer exactamente para registrar una venta?

Podemos dividirla nuevamente:

1. Identificar el producto.
2. Obtener su precio.
3. Solicitar la cantidad.
4. Comprobar que la cantidad sea válida.
5. Calcular el importe.

Ahora tenemos un nivel más detallado.

Podemos continuar dividiendo una tarea mientras sea necesario para comprender cómo resolverla.

Sin embargo, tampoco debemos dividir absolutamente todo.

Si una tarea ya es sencilla, clara y fácil de realizar, no necesitamos separarla en pasos innecesarios.

### Una analogía: preparar una comida

Imagina que una de tus tareas es preparar una ensalada.

Podrías dividirla en:

- Lavar los ingredientes.
- Cortar los vegetales.
- Colocarlos en un recipiente.
- Condimentar.

Pero también podrías dividir «lavar los ingredientes» en otras tareas:

- Abrir el grifo.
- Colocar los vegetales bajo el agua.
- Retirar la suciedad.
- Cerrar el grifo.

¿Es necesario llegar siempre a ese nivel de detalle?

No necesariamente.

Depende de qué tan compleja sea la tarea y de cuánto detalle necesitemos para comprenderla.

En programación sucede lo mismo: buscamos un nivel de división que facilite el trabajo sin generar complejidad innecesaria.

---

## 5. Relacionar la descomposición con los algoritmos

Recordemos que en el tema 1.2 aprendimos que un algoritmo es una secuencia de pasos ordenados para resolver un problema.

Ahora podemos relacionar ambos conceptos.

La descomposición nos ayuda a dividir un problema en tareas más pequeñas.

Los algoritmos nos permiten organizar los pasos necesarios para resolver esas tareas.

Veamos un ejemplo.

**Problema general:** calcular el precio final de una compra aplicando un descuento cuando corresponda.

Primero lo descomponemos:

- Obtener los productos y sus precios.
- Calcular el importe total.
- Comprobar si corresponde aplicar un descuento.
- Calcular el importe final.
- Mostrar el resultado.

Después diseñamos un algoritmo que organice esas tareas.

```text
INICIO

    Obtener el importe de la compra

    SI el importe es igual o mayor a 50000
        Calcular un descuento del 10%
        Restar el descuento al importe
    SI NO
        Mantener el importe original
    FIN SI

    Mostrar el importe final

FIN
```

Ahora tenemos una solución organizada.

Pero observa algo importante: primero identificamos las partes del problema y después organizamos las instrucciones.

No comenzamos escribiendo código al azar.

### ¿Qué diferencia existe entre descomponer y crear un algoritmo?

| Descomposición | Algoritmo |
|---|---|
| Divide el problema en partes. | Organiza los pasos para resolverlo. |
| Ayuda a identificar las tareas. | Explica cómo ejecutar las tareas. |
| Facilita la comprensión. | Permite representar la solución. |

Ambos conceptos se complementan.

---

## 6. Introducción a la programación modular

Cuando dividimos un problema en partes, podemos organizar la solución de manera que cada parte tenga una responsabilidad específica.

Esta idea está relacionada con la **programación modular**.

Un módulo es una parte de un programa que se encarga de realizar una tarea determinada.

Por ejemplo, en un sistema de ventas podríamos tener:

- Un módulo para registrar productos.
- Un módulo para calcular importes.
- Un módulo para aplicar descuentos.
- Un módulo para generar comprobantes.

Cada módulo tiene una responsabilidad.

Esto permite organizar sistemas grandes en componentes más pequeños y facilita su comprensión, mantenimiento y reutilización.

### Una analogía: el trabajo en una empresa

Imagina una empresa que necesita atender pedidos.

En lugar de que una sola persona realice absolutamente todas las actividades, podemos distribuir las responsabilidades:

- Una persona recibe los pedidos.
- Otra prepara los productos.
- Otra verifica que estén correctos.
- Otra organiza la entrega.

Cada persona cumple una función dentro de un objetivo general.

En programación modular buscamos algo parecido: separar responsabilidades para que cada parte del sistema se concentre en una tarea.

**Importante:** no debemos confundir descomposición con programación modular.

La descomposición es una estrategia para analizar y dividir problemas. La programación modular es una forma de organizar un programa utilizando módulos.

Primero podemos descomponer un problema en nuestra mente y después utilizar esa organización para diseñar los módulos del programa.

---

## 7. ¿Cómo saber si dividimos correctamente un problema?

No alcanza con separar una tarea en varias partes. También necesitamos comprobar que nuestra división tenga sentido.

Podemos hacernos estas preguntas:

**1. ¿Cada parte tiene un objetivo claro?**

Si no podemos explicar para qué sirve una tarea, quizás no la definimos correctamente.

**2. ¿Las tareas son comprensibles?**

Cada parte debería ser lo suficientemente sencilla como para analizarla sin confusión.

**3. ¿Las partes se relacionan con el problema original?**

No debemos agregar actividades que no sean necesarias para alcanzar el objetivo.

**4. ¿Respetamos el orden de las dependencias?**

Algunas tareas necesitan que otras se completen antes.

**5. ¿Podemos comprobar cada parte?**

Si podemos probar las tareas por separado, será más fácil encontrar errores.

### Ejemplo de una mala descomposición

Imagina que queremos calcular el total de una compra y dividimos el trabajo así:

1. Mostrar el resultado.
2. Obtener los precios.
3. Calcular el total.

El problema es que intentamos mostrar un resultado antes de haberlo calculado.

Las tareas existen, pero están organizadas de manera incorrecta.

Una mejor organización sería:

1. Obtener los precios.
2. Calcular el total.
3. Mostrar el resultado.

La diferencia parece sencilla, pero demuestra por qué debemos analizar las relaciones y dependencias entre las tareas.

---

## Ejercicios para desarrollar el razonamiento

En los siguientes ejercicios no buscamos que escribas código. Queremos que aprendas a observar un problema, identificar sus partes y explicar cómo las organizarías.

### Ejercicio 1. Dividir una tarea cotidiana

Imagina que tienes que organizar una habitación que está completamente desordenada.

1. ¿Cuál es el objetivo general?
2. ¿Qué tareas principales realizarías?
3. ¿En qué orden las organizarías?
4. ¿Existe alguna tarea que podrías dividir nuevamente?
5. ¿Cómo comprobarías que terminaste?

### Ejercicio 2. Analizar una compra

Una persona quiere comprar tres productos y conocer cuánto dinero necesita.

Los productos tienen estos precios:

- Producto A: 5.000 pesos.
- Producto B: 3.500 pesos.
- Producto C: 7.000 pesos.

Responde:

1. ¿Cuál es el problema?
2. ¿Qué tareas necesitas realizar?
3. ¿Qué datos necesitas?
4. ¿Qué operación permite obtener el total?
5. ¿Cómo comprobarías el resultado?

### Ejercicio 3. Descomponer un problema informático

Queremos crear un sistema que permita registrar los resultados de varios jugadores y mostrar quién obtuvo la mayor puntuación.

Identifica las tareas necesarias para resolverlo.

Pistas:

- Necesitamos registrar información.
- Debemos comparar resultados.
- Tenemos que identificar el valor más alto.
- Finalmente, debemos mostrar quién obtuvo ese resultado.

Explica por qué organizarías las tareas de esa manera.

### Ejercicio 4. Encontrar una mala organización

Una persona quiere preparar una comida y organiza estas tareas:

1. Servir la comida.
2. Comprar los ingredientes.
3. Preparar los alimentos.
4. Comprobar qué ingredientes necesita.

Responde:

1. ¿Qué problema tiene el orden elegido?
2. ¿Qué tarea debería realizar primero?
3. ¿Cómo reorganizarías las actividades?
4. ¿Por qué el orden es importante?

### Ejercicio 5. Descomposición aplicada a videojuegos

Queremos diseñar un sistema de vidas para un videojuego.

El personaje comienza con tres vidas. Cuando recibe daño, pierde una vida. Cuando llega a cero, termina la partida.

Divide este problema en tareas más pequeñas.

Después responde:

1. ¿Qué información necesitamos controlar?
2. ¿Qué acciones deben realizarse cuando el personaje recibe daño?
3. ¿Qué condición determina si la partida termina?
4. ¿Qué sucede si el personaje recibe dos daños?
5. ¿Qué sucede si recibe tres?
6. ¿Cómo comprobarías que el sistema funciona?

### Ejercicio 6. Reto de razonamiento

Una tienda necesita un sistema que permita registrar las compras de sus clientes, aplicar descuentos, calcular el importe final y generar un comprobante.

Tu tarea es descomponer el problema.

Identifica:

1. El objetivo general.
2. Las tareas principales.
3. Las tareas que podrían dividirse nuevamente.
4. El orden en que deberían realizarse.
5. Qué información necesita cada tarea.
6. Cómo comprobarías que cada parte funciona correctamente.

Finalmente, explica cómo relacionarías todas las partes para alcanzar el objetivo general.

---

## Resumen

- La **descomposición de problemas** consiste en dividir un problema complejo en tareas más pequeñas y manejables.
- Permite comprender mejor los problemas y organizar el trabajo.
- Cada tarea debe tener un objetivo claro y contribuir a la solución general.
- Las partes de un problema pueden dividirse nuevamente cuando necesitan mayor detalle.
- Es importante identificar las relaciones y dependencias entre las tareas.
- La descomposición se complementa con los algoritmos, porque permite identificar las partes y después organizar los pasos para resolverlas.
- La programación modular utiliza esta idea para organizar programas en componentes con responsabilidades específicas.

### Idea clave

**Cuando un problema parece demasiado grande para resolverlo, no necesariamente necesitamos una solución más complicada. Muchas veces necesitamos aprender a dividirlo correctamente.**

Un buen razonamiento comienza cuando dejamos de mirar el problema como una única dificultad y empezamos a comprender las partes que lo componen.

➡️ **Siguiente tema:** [1.5 - Reconocimiento de patrones y abstracción](./05-patrones-y-abstraccion.md)
