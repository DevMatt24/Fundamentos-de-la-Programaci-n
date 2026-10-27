# 1.1 - ¿Qué es programar?

Antes de escribir código, necesitamos entender qué significa programar, para qué sirve y cómo se relaciona con las cosas que usamos todos los días.

No necesitas tener conocimientos previos para entender este tema. Vamos a empezar desde lo más básico.

## ¿Qué es un programa?

Un **programa** es un conjunto de instrucciones que le indican a una computadora qué hacer y en qué orden hacerlo.

Para entenderlo mejor, imagina que quieres preparar un sándwich. Necesitas seguir una serie de pasos:

1. Buscar dos rebanadas de pan.
2. Colocar el queso sobre una de ellas.
3. Agregar el jamón.
4. Juntar ambas rebanadas.
5. Servir el sándwich.

Si sigues los pasos correctamente, obtienes el resultado esperado.

Un programa funciona de manera parecida: le damos instrucciones a la computadora para que realice una tarea.

La diferencia es que una computadora no interpreta nuestras instrucciones de la misma manera que una persona. Necesita que estén expresadas de una forma que pueda procesar.

Por eso existen los **lenguajes de programación**.

### ¿Qué es un lenguaje de programación?

Un lenguaje de programación es un lenguaje con reglas y palabras específicas que utilizamos para escribir instrucciones que una computadora pueda ejecutar mediante el software adecuado.

Existen muchos lenguajes de programación. Algunos ejemplos son:

- **Python:** conocido por tener una sintaxis relativamente sencilla para principiantes.
- **JavaScript:** muy utilizado para crear páginas web interactivas.
- **C#:** utilizado en aplicaciones, videojuegos y otros sistemas.
- **Java:** utilizado en aplicaciones empresariales, entre otros ámbitos.
- **C y C++:** utilizados, por ejemplo, en sistemas, aplicaciones de alto rendimiento y videojuegos.

Cada lenguaje tiene sus propias reglas, pero todos nos permiten expresar instrucciones para resolver problemas.

**Analogía:** si una receta es una forma de comunicarle a alguien cómo preparar una comida, un lenguaje de programación es una forma de comunicarle a la computadora cómo realizar una tarea.

---

## ¿Qué significa programar?

**Programar es diseñar, escribir, probar y mejorar instrucciones para que una computadora realice una tarea o resuelva un problema.**

Pero hay algo importante: programar no consiste únicamente en escribir código.

Antes de escribir una sola línea, necesitamos pensar qué queremos conseguir y cómo podemos conseguirlo.

Imagina que quieres construir una casa. No comenzarías colocando ladrillos al azar. Primero necesitarías saber qué casa quieres construir, preparar un plano y organizar el trabajo.

En programación sucede algo parecido.

Podemos dividir el proceso en cuatro pasos:

### 1. Entender el problema

Primero debemos identificar qué necesitamos resolver.

Por ejemplo:

*Quiero crear un programa que me diga si una persona es mayor de edad.*

Antes de programar, debemos entender qué información necesitamos y qué resultado queremos obtener.

### 2. Diseñar una solución

Ahora pensamos cómo resolver el problema paso a paso.

En nuestro ejemplo:

1. Obtener la edad de la persona.
2. Comprobar si tiene 18 años o más.
3. Si tiene 18 años o más, indicar que es mayor de edad.
4. Si tiene menos de 18 años, indicar que es menor de edad.

Todavía no escribimos código. Simplemente estamos organizando nuestras ideas.

### 3. Escribir el código

Una vez que sabemos qué hacer, expresamos esos pasos utilizando un lenguaje de programación.

Por ejemplo, en Python:

```python
edad = int(input("¿Cuántos años tienes? "))

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

No te preocupes si todavía no entiendes este código. Lo estudiaremos más adelante.

Por ahora, quédate con esta idea: **el código es la forma de expresar nuestras instrucciones utilizando un lenguaje de programación.**

### 4. Probar y corregir

Después de escribir el programa, debemos comprobar si funciona correctamente.

Por ejemplo:

- Si ingresamos `20`, debería mostrar que somos mayores de edad.
- Si ingresamos `15`, debería mostrar que somos menores de edad.
- Si aparece un error o el resultado no es el esperado, debemos investigar qué ocurrió y corregirlo.

A este proceso de encontrar y corregir errores se lo conoce como *depuración*.

Los errores son una parte normal de la programación. Incluso los programadores experimentados los cometen. Lo importante es aprender a identificarlos y solucionarlos.

---

## ¿Qué puede hacer un programa?

Los programas están presentes en muchísimas actividades cotidianas, aunque a veces no nos demos cuenta.

Veamos algunos ejemplos.

### Realizar cálculos

Una calculadora puede sumar, restar, multiplicar y dividir porque contiene instrucciones que realizan esas operaciones.

**Ejemplo:** ingresar dos números y obtener su suma.

### Tomar decisiones

Un programa puede comprobar si se cumple una condición y actuar de una manera u otra según el resultado.

**Ejemplo:** una aplicación bancaria puede comprobar si tienes saldo suficiente antes de realizar una operación.

### Repetir tareas

Un programa puede repetir una misma tarea muchas veces sin que tengamos que indicarle manualmente cada repetición.

**Ejemplo:** una aplicación puede recorrer una lista de 1.000 productos para encontrar aquellos que cuestan menos de un determinado precio.

### Guardar y recuperar información

Los programas pueden trabajar con información almacenada para utilizarla cuando sea necesario.

**Ejemplo:** una aplicación de notas guarda tus escritos para que puedas consultarlos más tarde.

### Comunicarse con las personas

Un programa puede mostrar mensajes, recibir información y responder a las acciones del usuario.

**Ejemplo:** una aplicación del clima recibe una consulta y muestra la temperatura de una ciudad.

Como puedes ver, programar no se limita a crear páginas web o videojuegos. También permite automatizar tareas, procesar información y resolver problemas de todo tipo.

---

## Nuestro primer ejemplo: ¿un número es par o impar?

Ahora vamos a utilizar una situación sencilla para entender cómo piensa un programa.

**El problema:** queremos crear un programa que nos diga si un número es par o impar.

Antes de escribir código, pensemos como programadores.

### Paso 1. Identificar la información

Necesitamos conocer un número que nos proporcione el usuario.

Por ejemplo: `8`.

### Paso 2. Pensar cómo resolverlo

Un número es par cuando puede dividirse entre 2 sin dejar resto.

Por ejemplo:

- 8 dividido entre 2 da 4, con resto 0.
- 7 dividido entre 2 da 3, con resto 1.

Por lo tanto, podemos utilizar el resto de una división para determinar si el número es par o impar.

### Paso 3. Organizar las instrucciones

Podemos escribir la solución con palabras sencillas, sin utilizar todavía un lenguaje de programación:

1. Pedir un número al usuario.
2. Calcular el resto de dividir ese número entre 2.
3. Si el resto es 0, indicar que el número es par.
4. En caso contrario, indicar que el número es impar.

Este conjunto ordenado de pasos representa una solución al problema.

### Paso 4. Convertir la solución en código

En Python, podríamos escribir:

```python
numero = int(input("Ingresa un número: "))

if numero % 2 == 0:
    print("El número es par.")
else:
    print("El número es impar.")
```

Por ahora, no hace falta memorizar la sintaxis. Lo importante es comprender la lógica:

- El programa recibe un número.
- Realiza una comprobación.
- Elige qué mensaje mostrar según el resultado.

Más adelante aprenderemos qué significa cada instrucción y cómo escribir nuestros propios programas.

---

## Una idea fundamental: la computadora no adivina

Imagina que le pides a alguien que prepare un café, pero solamente le dices: «Prepara un café».

Una persona probablemente entenderá lo que quieres decir y completará los detalles por su cuenta.

Una computadora, en cambio, necesita instrucciones concretas proporcionadas por el programa. No puede asumir automáticamente todos los detalles que no especificamos.

Por eso, al programar, debemos definir con claridad qué información necesitamos, qué operaciones debemos realizar y qué resultado esperamos obtener.

Esto no significa que las computadoras siempre hagan literalmente cualquier cosa que escribamos: los programas también pueden contener errores, y su ejecución depende del lenguaje, el entorno y las herramientas utilizadas.

La idea es que **la computadora ejecuta las instrucciones del programa según sus reglas; no puede corregir por sí sola una solución que no hemos diseñado correctamente.**

Aprender a programar implica desarrollar la capacidad de transformar una idea en instrucciones claras y ordenadas.

---

## Errores comunes al comenzar

Antes de terminar, conviene aclarar algunas ideas que suelen confundir a quienes están aprendiendo.

- **«Programar es memorizar código».** No. Memorizar algunas instrucciones puede ayudar, pero lo fundamental es comprender los problemas y cómo resolverlos.
- **«Tengo que saber matemáticas avanzadas».** No necesariamente. Para comenzar, alcanza con comprender operaciones básicas, condiciones y razonamiento lógico.
- **«Si me equivoco, significa que no sirvo para programar».** Para nada. Los errores forman parte del aprendizaje y nos ayudan a comprender cómo funcionan los programas.
- **«Tengo que aprender todos los lenguajes».** No. Puedes comenzar con uno, aprender los fundamentos y después aplicar esos conocimientos a otros lenguajes.

No necesitas saberlo todo desde el primer día. Necesitas avanzar paso a paso, practicar y aprender de cada error.

---

## Resumen

- Un **programa** es un conjunto de instrucciones que permite realizar una tarea.
- Un **lenguaje de programación** nos permite expresar esas instrucciones siguiendo reglas específicas.
- **Programar** consiste en diseñar, escribir, probar y mejorar soluciones a problemas.
- Un programa puede realizar cálculos, tomar decisiones, repetir tareas, almacenar información y comunicarse con el usuario.
- Antes de escribir código, debemos comprender el problema y organizar una solución.
- Los errores son normales y aprender a corregirlos forma parte de la programación.

### Para comprobar lo aprendido

Antes de continuar, intenta responder estas preguntas con tus propias palabras:

1. ¿Qué diferencia hay entre un programa y un lenguaje de programación?
2. ¿Por qué programar no consiste solamente en escribir código?
3. Si quisieras crear una aplicación que calcule el precio total de una compra, ¿qué información necesitarías y qué pasos seguirías?
4. ¿Por qué es importante probar un programa después de escribirlo?

No hace falta responder con palabras técnicas. Lo importante es que puedas explicar las ideas con claridad.

---

**Idea clave:** programar es aprender a resolver problemas paso a paso y expresar nuestras soluciones mediante instrucciones que una computadora pueda ejecutar.

➡️ **Siguiente tema:** [02 - Algoritmos](./02-algoritmos.md)
