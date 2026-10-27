# 1.2 - Algoritmos: el corazón de la programación

En el tema anterior aprendimos que programar consiste en resolver problemas mediante instrucciones que una computadora puede ejecutar.

Pero antes de escribir código, necesitamos responder una pregunta fundamental:

**¿Cómo sabemos qué instrucciones debemos escribir y en qué orden?**

La respuesta está en los algoritmos.

Los algoritmos son una de las bases de la programación. Nos permiten organizar nuestras ideas, pensar en una solución y definir los pasos necesarios antes de comenzar a escribir código.

No necesitas saber programar para entenderlos. De hecho, ya utilizas algoritmos en tu vida cotidiana sin darte cuenta.

## ¿Qué es un algoritmo?

Un **algoritmo** es una secuencia finita de pasos claros y ordenados que permite resolver un problema o realizar una tarea.

Vamos a dividir esta definición en partes para entenderla mejor.

- **Secuencia de pasos:** una serie de instrucciones que debemos seguir.
- **Finita:** la secuencia debe terminar después de una cantidad limitada de pasos.
- **Claros:** cada instrucción debe indicar qué hay que hacer sin dejar dudas importantes.
- **Ordenados:** los pasos deben seguir una secuencia lógica para alcanzar el resultado esperado.

Aunque la definición parece técnica, los algoritmos están presentes en muchas actividades que realizamos todos los días.

### Una analogía: seguir una receta de cocina

Imagina que quieres preparar un sándwich.

Podrías seguir estos pasos:

1. Buscar dos rebanadas de pan.
2. Colocar una rebanada sobre un plato.
3. Agregar el queso.
4. Agregar el jamón.
5. Colocar la otra rebanada de pan encima.
6. Servir el sándwich.

Esta lista representa un algoritmo porque establece los pasos necesarios para completar una tarea.

Ahora imagina que intentas seguir la receta colocando primero el sándwich en el plato y buscando el pan al final. El orden no tendría mucho sentido.

En programación sucede algo parecido: **no basta con saber qué acciones necesitamos realizar; también debemos determinar en qué orden ejecutarlas.**

### ¿Todos los algoritmos necesitan una computadora?

No.

Un algoritmo puede existir sin estar escrito en un lenguaje de programación.

Por ejemplo, las instrucciones para preparar una comida, organizar una mochila o calcular cuánto dinero necesitas para una compra pueden describirse como algoritmos.

Lo importante no es utilizar una computadora, sino definir una serie de pasos que permita alcanzar un resultado.

Cuando queremos resolver un problema mediante un programa, diseñamos un algoritmo y después lo expresamos en un lenguaje de programación.

---

## Las características de un buen algoritmo

Para que un algoritmo sea útil, debe cumplir ciertas características.

Veamos las principales mediante ejemplos sencillos.

### 1. Debe ser finito

Un algoritmo debe terminar en algún momento.

Imagina que creas una lista de instrucciones para contar desde el 1 hasta el 10.

1. Comenzar en el número 1.
2. Mostrar el número actual.
3. Sumar 1 al número.
4. Si el número es menor o igual que 10, repetir el proceso.
5. Terminar.

El algoritmo tiene una condición que permite saber cuándo detenerse.

Si diseñáramos un proceso que repite los mismos pasos indefinidamente sin una razón prevista para detenerse, no cumpliría la característica de ser finito.

En programación existen las repeticiones infinitas, pero debemos comprender cómo controlarlas para evitar que un programa quede ejecutándose sin terminar cuando no es lo esperado.

### 2. Debe ser preciso

Cada instrucción debe ser suficientemente clara para que pueda ejecutarse correctamente.

Por ejemplo, imagina que le dices a alguien:

> Agrega un poco de azúcar.

Una persona puede interpretar qué significa «un poco» según sus preferencias.

Pero si necesitamos una instrucción exacta, sería mejor decir:

> Agrega una cucharadita de azúcar.

En programación, las instrucciones ambiguas pueden provocar resultados incorrectos o impedir que una tarea se complete.

Por eso, debemos expresar los pasos de forma clara y específica.

### 3. Debe estar ordenado

Los pasos deben ejecutarse en una secuencia lógica.

Imagina que quieres calcular el total de una compra:

1. Obtener el precio de cada producto.
2. Sumar los precios.
3. Mostrar el total.

Si intentas mostrar el resultado antes de realizar la suma, todavía no tendrás el valor que necesitas.

El orden importa porque algunos pasos dependen de los resultados de los anteriores.

### 4. Puede recibir entradas y producir salidas

Muchos algoritmos reciben información, realizan operaciones y generan un resultado.

A estos elementos los llamamos **entrada**, **proceso** y **salida**.

Veamos un ejemplo: calcular el precio total de dos productos.

- **Entrada:** el precio del primer producto y el precio del segundo.
- **Proceso:** sumar ambos precios.
- **Salida:** mostrar el total de la compra.

Podemos representarlo así:

```text
ENTRADA
Precio del producto 1
Precio del producto 2

PROCESO
Total = Precio 1 + Precio 2

SALIDA
Mostrar el total
```

Esta estructura es muy importante porque nos ayuda a identificar qué información necesita un algoritmo, qué debe hacer con ella y qué resultado debe entregar.

No todos los algoritmos necesitan recibir datos externos; algunos trabajan con valores previamente definidos o realizan tareas que no producen una salida visible. Sin embargo, entrada, proceso y salida constituyen un modelo muy útil para comenzar.

---

## Diseñemos nuestro primer algoritmo

Ahora vamos a resolver un problema sencillo.

**Problema:** queremos calcular la suma de dos números.

Antes de escribir código, debemos pensar cómo resolverlo.

### Paso 1. Comprender el problema

Necesitamos obtener dos números y calcular cuánto suman.

Por ejemplo:

- Primer número: 5.
- Segundo número: 3.
- Resultado esperado: 8.

### Paso 2. Identificar la entrada, el proceso y la salida

| Elemento | ¿Qué necesitamos? |
| --- | --- |
| Entrada | Dos números. |
| Proceso | Sumar los dos números. |
| Salida | Mostrar el resultado. |

### Paso 3. Escribir los pasos

Podemos describir el algoritmo con palabras sencillas:

1. Pedir el primer número.
2. Pedir el segundo número.
3. Sumar ambos números.
4. Mostrar el resultado.
5. Terminar.

¡Ya tenemos un algoritmo!

Todavía no hemos escrito código, pero sabemos exactamente qué debe hacer nuestra futura aplicación.

### Paso 4. Comprobar el resultado

Probemos con diferentes valores:

| Primer número | Segundo número | Resultado esperado |
| ---: | ---: | ---: |
| 5 | 3 | 8 |
| 10 | 7 | 17 |
| 4 | 0 | 4 |
| -2 | 6 | 4 |

Esta comprobación nos permite verificar si la solución funciona con diferentes entradas.

**Idea importante:** un algoritmo no se considera bien diseñado simplemente porque funciona con un ejemplo. Conviene probar diferentes casos para descubrir posibles errores.

---

## ¿Qué es el pseudocódigo?

Hasta ahora hemos descrito nuestros algoritmos utilizando palabras comunes.

Pero, a medida que los problemas se vuelven más complejos, necesitamos una forma más organizada de representar las instrucciones.

Aquí aparece el **pseudocódigo**.

El pseudocódigo es una forma de describir un algoritmo mediante instrucciones estructuradas que se parecen al código de programación, pero sin tener que respetar todas las reglas de un lenguaje específico.

Su objetivo es ayudarnos a pensar en la solución antes de implementarla.

### Una analogía: el plano de una casa

Imagina que quieres construir una casa.

Antes de comenzar la construcción, puedes preparar un plano que indique dónde estarán las habitaciones, las puertas y las ventanas.

El plano no es la casa terminada, pero permite organizar el trabajo y detectar problemas antes de construir.

El pseudocódigo cumple una función parecida: es un borrador organizado de la solución que queremos implementar.

### Ejemplo: sumar dos números con pseudocódigo

```text
INICIO
    LEER numero1
    LEER numero2

    suma <- numero1 + numero2

    MOSTRAR suma
FIN
```

Veamos qué significa cada instrucción:

- `INICIO`: indica dónde comienza el algoritmo.
- `LEER numero1`: obtiene el primer número.
- `LEER numero2`: obtiene el segundo número.
- `suma <- numero1 + numero2`: calcula la suma y guarda el resultado.
- `MOSTRAR suma`: presenta el resultado.
- `FIN`: indica que el algoritmo terminó.

El símbolo `<-` representa una asignación: estamos guardando un valor en un lugar identificado por un nombre.

Por ejemplo, si `numero1` vale 5 y `numero2` vale 3, la instrucción de asignación guarda el valor 8 en `suma`.

No existe una única sintaxis universal para escribir pseudocódigo. Lo importante es mantener una estructura clara y utilizar las mismas convenciones a lo largo del material.

### ¿Por qué utilizar pseudocódigo?

Porque permite concentrarnos en la lógica sin preocuparnos todavía por la sintaxis de un lenguaje.

Por ejemplo, en Python escribiríamos las instrucciones de una manera específica. En JavaScript, C# o Java podríamos expresarlas de otra forma.

Sin embargo, la idea de obtener dos números, sumarlos y mostrar el resultado seguiría siendo la misma.

**Primero diseñamos la solución; después aprendemos a expresarla en el lenguaje elegido.**

---

## ¿Qué son los diagramas de flujo?

Otra forma de representar un algoritmo es mediante un **diagrama de flujo**.

Un diagrama de flujo utiliza símbolos gráficos y flechas para mostrar los pasos de un proceso y la relación entre ellos.

En lugar de leer únicamente una lista de instrucciones, podemos observar visualmente cómo avanza el algoritmo desde el inicio hasta el final.

### Los símbolos más comunes

Estos son algunos de los símbolos que encontrarás al estudiar diagramas de flujo:

| Símbolo | Nombre | ¿Para qué sirve? |
| --- | --- | --- |
| Óvalo | Inicio o fin | Indica dónde comienza o termina el proceso. |
| Rectángulo | Proceso | Representa una operación o una acción. |
| Paralelogramo | Entrada o salida | Representa la lectura o presentación de datos. |
| Rombo | Decisión | Permite evaluar una condición y elegir un camino. |
| Flecha | Línea de flujo | Indica la dirección que sigue el algoritmo. |

Estos símbolos facilitan la lectura de un algoritmo, especialmente cuando incluye decisiones o repeticiones.

### Ejemplo: determinar si un número es positivo, negativo o cero

Supongamos que queremos crear un algoritmo que reciba un número y nos diga si es positivo, negativo o igual a cero.

Primero, pensemos en las reglas:

- Si el número es mayor que cero, es positivo.
- Si el número es menor que cero, es negativo.
- Si no es mayor ni menor que cero, es igual a cero.

Podemos representar la solución con este diagrama simplificado:

```text
          ( INICIO )
               |
               v
       / Leer número /
               |
               v
       < ¿número > 0? >
          /         \
        Sí           No
        |             |
        v             v
 [Mostrar           < ¿número < 0? >
  "Positivo"]         /         \
                    Sí           No
                    |             |
                    v             v
               [Mostrar       [Mostrar
               "Negativo"]    "Es cero"]
                    |             |
                    +------v------+
                           |
                           v
                         ( FIN )
```

Este dibujo utiliza texto para que podamos visualizar el recorrido, aunque no reproduce exactamente las formas geométricas de un diagrama formal.

Observa que el algoritmo necesita dos decisiones:

1. Primero comprueba si el número es mayor que cero.
2. Si no lo es, comprueba si es menor que cero.
3. Si ninguna de las dos condiciones se cumple, el número necesariamente es cero.

Por ejemplo:

- Entrada: `8`. Salida: `Positivo`.
- Entrada: `-4`. Salida: `Negativo`.
- Entrada: `0`. Salida: `Es cero`.

**Lo importante:** el diagrama permite visualizar cómo cambia el recorrido del algoritmo según los datos que recibe.

---

## Del problema al programa

Ahora que conocemos los algoritmos, podemos comprender mejor cómo se relacionan con la programación.

Imagina que quieres crear una aplicación que calcule el total de una compra.

El proceso podría ser el siguiente:

```text
PROBLEMA
Calcular el total de una compra
        |
        v
ALGORITMO
Obtener los precios y sumarlos
        |
        v
PSEUDOCÓDIGO
Describir los pasos de la solución
        |
        v
CÓDIGO
Escribir la solución en Python,
JavaScript u otro lenguaje
        |
        v
PROGRAMA
Ejecutar la solución para obtener
el total de la compra
```

Cada etapa cumple una función diferente:

- **Problema:** identifica qué necesitamos resolver.
- **Algoritmo:** define los pasos necesarios para resolverlo.
- **Pseudocódigo o diagrama de flujo:** permite representar y organizar la solución.
- **Código:** expresa el algoritmo utilizando un lenguaje de programación.
- **Programa en ejecución:** realiza las operaciones y produce los resultados esperados.

Un detalle importante: el pseudocódigo y los diagramas de flujo son herramientas opcionales de diseño. Podemos pasar de un algoritmo a código sin utilizarlos, pero resultan especialmente útiles cuando estamos aprendiendo o trabajamos con problemas complejos.

---

## Errores comunes al diseñar algoritmos

Cuando empezamos a aprender, hay algunos errores que conviene evitar.

### 1. Comenzar a escribir código sin entender el problema

Si no sabemos qué queremos resolver, es fácil terminar escribiendo instrucciones que no conducen al resultado esperado.

**Cómo evitarlo:** explica el problema con tus propias palabras e identifica qué resultado necesitas obtener.

### 2. Olvidar algún paso

Imagina que calculas el total de una compra, pero olvidas incluir uno de los productos.

El algoritmo podría ejecutarse sin errores y, aun así, entregar un resultado incorrecto.

**Cómo evitarlo:** revisa qué datos necesitas y comprueba que todas las operaciones necesarias estén incluidas.

### 3. Escribir instrucciones ambiguas

Una instrucción como «calcular el resultado» no es suficiente si todavía no sabemos qué operación debemos realizar.

**Cómo evitarlo:** define claramente qué información utilizarás y qué operación debes aplicar.

### 4. No contemplar todos los casos

En el ejemplo anterior, comprobar solamente si un número es positivo no nos permite distinguir entre un número negativo y el cero.

**Cómo evitarlo:** piensa en diferentes entradas posibles y determina qué debería ocurrir en cada situación.

### 5. No probar el algoritmo

Una solución puede parecer correcta al leerla, pero contener errores que aparecen al utilizar otros valores.

**Cómo evitarlo:** realiza pruebas manuales con diferentes datos antes de implementar el programa.

Recuerda que un algoritmo bien organizado facilita la programación, pero también debemos comprobar que realmente resuelva el problema.

---

## Ejercicios para practicar

Antes de continuar, intenta diseñar tus propios algoritmos. No necesitas escribir código: puedes utilizar palabras comunes o pseudocódigo.

### Ejercicio 1. Preparar una mochila

Imagina que necesitas preparar tu mochila antes de ir a estudiar.

Escribe entre cinco y ocho pasos que te permitan completar la tarea.

Piensa en estas preguntas:

- ¿Qué debes comprobar antes de comenzar?
- ¿En qué orden debes guardar las cosas?
- ¿Cómo puedes asegurarte de que no olvidaste nada?

### Ejercicio 2. Calcular el promedio

Quieres calcular el promedio de tres notas.

Identifica:

1. ¿Cuáles son las entradas?
2. ¿Qué operación debes realizar?
3. ¿Cuál es la salida?
4. ¿Qué pasos debería seguir el algoritmo?

Pista: suma las tres notas y divide el resultado entre tres.

### Ejercicio 3. Analizar una decisión

Diseña un algoritmo que reciba la edad de una persona y determine si tiene 18 años o más.

Piensa qué condición necesitas comprobar y qué mensaje debes mostrar en cada caso.

### Ejercicio 4. Detectar errores

Observa este algoritmo:

```text
INICIO
    LEER numero1
    MOSTRAR suma
    LEER numero2
    suma <- numero1 + numero2
FIN
```

¿Encuentras algún problema?

Pista: piensa en qué momento se calcula la suma y cuándo se intenta mostrar.

Intenta corregir el orden de las instrucciones.

---

## Resumen

- Un **algoritmo** es una secuencia finita de pasos claros y ordenados que permite resolver un problema o realizar una tarea.
- Un buen algoritmo debe ser preciso, seguir un orden lógico y terminar cuando corresponda.
- La **entrada** es la información que recibe el algoritmo; el **proceso** es lo que hace con ella; la **salida** es el resultado que produce.
- El **pseudocódigo** permite describir una solución de forma estructurada sin depender de un lenguaje de programación específico.
- Los **diagramas de flujo** representan visualmente los pasos, las decisiones y los recorridos de un algoritmo.
- Diseñar y probar una solución antes de escribir código ayuda a detectar errores y facilita el desarrollo.

### Idea clave

**Un algoritmo es el plan que define cómo resolver un problema. El código es la forma de expresar ese plan para que una computadora pueda ejecutarlo.**

No necesitas comenzar escribiendo código complicado. Aprende a identificar problemas, dividirlos en pasos y comprobar tus soluciones. Esa habilidad será útil independientemente del lenguaje de programación que elijas.

➡️ **Siguiente tema:** [03 - Lenguajes de programación](./03-lenguajes.md)
