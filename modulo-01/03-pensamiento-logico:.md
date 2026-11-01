# 1.3 - Pensamiento lógico: aprender a razonar paso a paso

En los temas anteriores aprendimos qué significa programar y qué es un algoritmo.

Ahora vamos a desarrollar una habilidad fundamental para cualquier persona que quiera aprender programación: el **pensamiento lógico**.

No necesitas conocer ningún lenguaje de programación ni tener conocimientos avanzados de matemáticas. Vamos a partir de situaciones cotidianas para comprender cómo analizar problemas, relacionar información y llegar a conclusiones razonables.

El objetivo de este tema no es que memorices respuestas, sino que aprendas a explicar **por qué una solución tiene sentido y cómo puedes comprobar que es correcta**.

## ¿Qué es el pensamiento lógico?

El **pensamiento lógico** es la capacidad de analizar información, establecer relaciones entre ideas y utilizar esas relaciones para llegar a conclusiones.

Dicho de una forma más sencilla, consiste en pensar con orden y utilizar razones para determinar qué puede ocurrir, qué está ocurriendo o qué solución tiene sentido.

Imagina que llegas a tu casa y descubres que el suelo de la cocina está mojado.

Podrías pensar inmediatamente que alguien derramó agua, pero existen otras posibilidades:

- Se derramó un vaso.
- Se limpió el suelo recientemente.
- Hay una pérdida de agua.
- Entró agua desde el exterior.

En lugar de elegir una explicación al azar, puedes observar el entorno y buscar información que te ayude a descubrir qué sucedió.

Por ejemplo, si encuentras un vaso volcado junto al charco, tienes una pista que respalda una posible explicación.

Eso es razonar: utilizar la información disponible para evaluar las posibilidades.

### ¿Qué relación tiene con la programación?

Una computadora puede ejecutar instrucciones, comparar valores y seguir reglas. Sin embargo, nosotros necesitamos diseñar esas instrucciones de manera que resuelvan correctamente el problema.

Para hacerlo, debemos aprender a:

- Identificar qué información es importante.
- Separar los hechos de las suposiciones.
- Reconocer relaciones entre diferentes datos.
- Analizar qué sucede si cambia una condición.
- Anticipar los posibles resultados.
- Detectar contradicciones y errores.
- Comprobar si una conclusión está justificada.

Estas habilidades nos ayudan a diseñar algoritmos correctos antes de escribir código.

**Idea clave:** programar no consiste únicamente en decirle a una computadora qué hacer. También consiste en descubrir qué debería hacer y por qué.

---

## 1. Pensar con orden

Una de las primeras habilidades que necesitamos desarrollar es organizar nuestras ideas.

Imagina que tienes que salir de casa para ir a estudiar. Necesitas vestirte, preparar la mochila, comprobar que llevas tus materiales y salir.

Si sales antes de preparar la mochila, probablemente tengas que regresar.

El problema no es que las acciones sean incorrectas, sino que no las organizaste adecuadamente.

En programación sucede lo mismo: una solución puede contener todas las acciones necesarias y, aun así, fallar porque se ejecutan en un orden incorrecto.

### Ejemplo práctico

Quieres preparar una taza de té.

¿Cuál de estas secuencias tiene más sentido?

**Secuencia A**

1. Colocar la bolsita de té en la taza.
2. Calentar el agua.
3. Verter el agua caliente.
4. Esperar unos minutos.

**Secuencia B**

1. Verter agua fría en la taza.
2. Esperar unos minutos.
3. Calentar el agua.
4. Colocar la bolsita de té en una taza vacía.

La primera secuencia es más coherente con el objetivo. La segunda no sigue un orden adecuado para preparar el té como se espera.

En la práctica, también podrías calentar el agua antes de colocar la bolsita en la taza; no existe una única secuencia válida para todos los detalles. Lo importante es que los pasos permitan alcanzar el resultado.

### ¿Qué debemos aprender de este ejemplo?

Antes de resolver un problema, pregúntate:

1. ¿Qué quiero conseguir?
2. ¿Qué acciones necesito realizar?
3. ¿Qué debe ocurrir antes de cada acción?
4. ¿Qué pasos dependen de otros?
5. ¿Cómo sabré que terminé?

Estas preguntas te ayudarán a organizar soluciones más claras.

---

## 2. Diferenciar hechos, suposiciones y conclusiones

Pensar lógicamente no significa creer que nuestra primera idea siempre es correcta. Significa analizar la información antes de aceptar una conclusión.

Vamos a ver la diferencia entre tres conceptos.

- **Hecho:** información que podemos comprobar dentro de una situación.
- **Suposición:** una idea que consideramos posible, pero que todavía no hemos confirmado.
- **Conclusión:** una afirmación a la que llegamos después de analizar la información disponible.

### Ejemplo cotidiano

Imagina que un teléfono no enciende.

Sabemos que:

- Presionamos el botón de encendido.
- La pantalla permanece apagada.

Esos son los hechos observados.

Podríamos suponer que la batería está descargada, pero también podría existir un problema con el cargador, la pantalla u otro componente.

Por lo tanto, todavía no tenemos suficiente información para asegurar cuál es la causa.

Una forma razonable de continuar sería conectar el teléfono a un cargador que sabemos que funciona y observar qué sucede.

Este nuevo intento nos proporciona información adicional.

### ¿Por qué importa en programación?

Imagina que un programa muestra un resultado incorrecto.

En lugar de cambiar instrucciones al azar, conviene investigar:

- ¿Qué datos recibió?
- ¿Qué operaciones realizó?
- ¿Qué resultado esperábamos?
- ¿En qué momento apareció la diferencia?
- ¿Qué evidencia tenemos de que una instrucción está fallando?

De esta manera, buscamos la causa del problema en lugar de limitarnos a adivinar.

**Un buen programador no necesita acertar siempre a la primera. Necesita saber cómo investigar cuando algo no funciona.**

---

## 3. Reconocer relaciones entre información

Muchas situaciones pueden resolverse identificando cómo se relacionan distintos datos.

Por ejemplo, imagina que estás organizando una salida y tienes estas reglas:

- Necesitas una entrada para ingresar al evento.
- Tienes una entrada.
- El evento exige presentar la entrada en el acceso.

A partir de esa información, puedes concluir que tienes el documento requerido para cumplir esa condición de ingreso.

En programación hacemos algo parecido cuando comparamos valores o comprobamos si se cumplen determinadas reglas.

### Ejemplo: calcular el precio de una compra

Imagina que compras dos productos:

- Un cuaderno cuesta 3.000 pesos.
- Un lápiz cuesta 1.000 pesos.

Si el precio total se obtiene sumando ambos precios, podemos calcularlo así:

3.000 + 1.000 = 4.000 pesos.

Ahora supongamos que tienes 5.000 pesos.

Puedes relacionar ambos datos:

- Total de la compra: 4.000 pesos.
- Dinero disponible: 5.000 pesos.

Como 5.000 es mayor que 4.000, tienes suficiente dinero para pagar la compra y te quedan 1.000 pesos.

No necesitamos ningún lenguaje de programación para llegar a esta conclusión.

Sin embargo, este razonamiento puede convertirse después en un algoritmo que calcule el total, compare los valores y determine si el dinero alcanza.

### Una advertencia importante

Una conclusión solamente es válida si los datos y las reglas utilizadas son correctos.

Si olvidamos incluir un producto, el total será incorrecto. Si el precio cambia, debemos realizar nuevamente el cálculo.

Por eso, razonar también implica revisar la información que utilizamos.

---

## 4. Pensar en condiciones: ¿qué sucede si...?

En la vida cotidiana tomamos decisiones constantemente.

Si llueve, buscamos un paraguas. Si tenemos hambre, buscamos comida. Si el autobús llega, subimos; si no llega, esperamos o buscamos otra alternativa.

Estas situaciones nos enseñan a analizar una condición y determinar qué hacer según su resultado.

En programación, una **condición** es una expresión que permite comprobar si algo se cumple o no.

Para comenzar, podemos pensar en ella como una pregunta que admite una respuesta de verdadero o falso.

### Ejemplo: comprobar si tienes suficiente dinero

Imagina que quieres comprar un producto que cuesta 8.000 pesos y tienes 10.000 pesos.

La pregunta es:

¿Tengo dinero suficiente para comprarlo?

Comparamos los valores:

10.000 es mayor o igual que 8.000.

La condición se cumple, por lo que puedes pagar el producto.

Ahora cambiemos el dinero disponible:

- Si tienes 10.000 pesos, alcanza.
- Si tienes 8.000 pesos, alcanza exactamente.
- Si tienes 6.000 pesos, no alcanza.

Observa que no basta con probar un único caso. Debemos analizar qué sucede cuando los valores cambian.

### Un ejemplo con una edad

Supongamos que una actividad está permitida para personas de 18 años o más.

La regla es:

- Si la edad es mayor o igual que 18, cumple el requisito de edad.
- Si la edad es menor que 18, no cumple ese requisito.

Podemos analizar diferentes valores:

| Edad | ¿Tiene 18 años o más? |
| ---: | --- |
| 15 | No |
| 17 | No |
| 18 | Sí |
| 19 | Sí |
| 25 | Sí |

¿Por qué es importante comprobar el valor 18?

Porque es el límite de la condición. Si interpretáramos la regla incorrectamente como «mayor que 18», una persona de exactamente 18 años quedaría excluida.

Este tipo de error es muy común al diseñar algoritmos.

**Aprendizaje:** cuando exista una condición con un límite, prueba siempre el valor exacto del límite, además de valores inferiores y superiores.

---

## 5. Analizar diferentes posibilidades

Un problema puede tener más de un resultado posible. Para resolverlo correctamente, necesitamos considerar las situaciones que podrían presentarse.

Imagina que quieres salir de casa y decides qué ropa llevar según el clima.

Podrías establecer estas reglas:

- Si hace frío, llevar una chaqueta.
- Si llueve, llevar un paraguas.
- Si hace frío y llueve, llevar ambas cosas.
- Si no hace frío ni llueve, salir sin esos elementos adicionales.

Observa que pueden existir varias condiciones al mismo tiempo.

No tenemos que pensar solamente en una pregunta aislada, sino también en cómo se combinan distintas circunstancias.

### Ejemplo con una máquina expendedora

Una máquina debe comprobar si el dinero ingresado alcanza para pagar un producto.

Podemos distinguir tres situaciones:

1. El dinero es menor que el precio.
2. El dinero es igual al precio.
3. El dinero es mayor que el precio.

Si el producto cuesta 2.000 pesos, podemos analizar:

| Dinero ingresado | Situación |
| ---: | --- |
| 1.500 | Falta dinero. |
| 2.000 | El pago es exacto. |
| 2.500 | Sobra dinero. |

Ahora debemos decidir qué debería hacer la máquina en cada caso.

- Si falta dinero, informar cuánto falta.
- Si el pago es exacto, entregar el producto.
- Si sobra dinero, entregar el producto y devolver el cambio, si la máquina dispone de esa función.

Este último detalle es importante: el razonamiento no termina al identificar las situaciones. También debemos definir la respuesta adecuada para cada una.

En programación, esta forma de pensar permite construir soluciones que contemplan diferentes escenarios en lugar de funcionar únicamente en el caso más sencillo.

---

## 6. Descomponer un problema grande en problemas pequeños

A veces, un problema parece complicado porque intentamos resolverlo todo al mismo tiempo.

Una estrategia útil consiste en dividirlo en partes más pequeñas.

Esta técnica se conoce como **descomposición de problemas** y es una de las habilidades fundamentales del pensamiento computacional.

### Analogía: organizar un viaje

Imagina que quieres organizar un viaje.

La tarea completa puede parecer enorme, pero puedes dividirla en actividades más manejables:

1. Elegir el destino.
2. Definir el presupuesto.
3. Buscar transporte.
4. Reservar alojamiento.
5. Preparar el equipaje.
6. Comprobar los horarios.

Cada tarea puede analizarse por separado.

Por ejemplo, para definir el presupuesto, necesitas estimar el coste del transporte, el alojamiento, la comida y otras actividades.

De esta manera, un problema grande se convierte en un conjunto de problemas más pequeños que podemos resolver progresivamente.

### Ejemplo aplicado a la programación

Supongamos que queremos crear un sistema que calcule el total de una compra, aplique un descuento cuando corresponda y muestre el importe final.

Podemos dividir el problema así:

1. Obtener los precios de los productos.
2. Calcular el subtotal.
3. Comprobar si corresponde aplicar un descuento.
4. Calcular el descuento, si corresponde.
5. Restar el descuento al subtotal.
6. Mostrar el importe final.

Cada paso tiene un objetivo concreto.

Si el resultado final es incorrecto, podemos revisar cada parte para encontrar dónde se produce el error.

Esta estrategia facilita tanto el diseño de algoritmos como la posterior comprobación de sus resultados.

---

## 7. Reconocer patrones

Un patrón es una característica, estructura o comportamiento que se repite de una manera que podemos identificar.

Reconocer patrones nos ayuda a comprender situaciones y anticipar qué podría suceder después.

### Ejemplo cotidiano

Observa esta secuencia:

2, 4, 6, 8, 10...

¿Qué número debería continuar?

La respuesta más sencilla es 12, porque cada número aumenta en 2.

Hemos identificado una regla que se repite: sumar 2 al valor anterior.

Ahora observa otra secuencia:

5, 10, 20, 40...

En este caso, cada número es el doble del anterior. El siguiente sería 80.

### ¿Qué tiene que ver esto con programar?

Los programas suelen realizar tareas repetitivas.

Por ejemplo, si necesitamos calcular el precio final de 100 productos, no queremos diseñar 100 soluciones diferentes. Podemos reconocer que todos requieren el mismo procedimiento y buscar una forma de repetirlo.

Del mismo modo, si una serie de pasos se repite con distintos datos, podemos diseñar una solución general que funcione para todos ellos.

Reconocer patrones nos ayuda a evitar trabajo innecesario y a encontrar soluciones que puedan reutilizarse.

### Cuidado con las conclusiones apresuradas

Una secuencia corta no siempre determina una única regla posible.

Por ejemplo, 2, 4, 6 podría continuar con 8 si sumamos 2, pero también podríamos inventar otras reglas que produzcan esos mismos tres valores y después cambien.

En un ejercicio de patrones, debemos buscar la regla más coherente con la información disponible y explicar por qué la elegimos.

En situaciones reales, cuando los datos no son suficientes, puede ser necesario obtener más información.

---

## 8. Comprobar nuestras ideas mediante pruebas

Una solución puede parecer correcta y, aun así, contener errores.

Por eso necesitamos comprobar nuestras ideas con ejemplos concretos.

Este hábito es la base de las pruebas de escritorio que estudiaremos más adelante.

### Ejemplo: una regla para calcular el total

Imagina que diseñamos este procedimiento:

1. Obtener el precio de un producto.
2. Obtener la cantidad comprada.
3. Multiplicar el precio por la cantidad.
4. Mostrar el total.

Supongamos que el precio es de 2.000 pesos y compramos 3 unidades.

El resultado esperado es:

2.000 × 3 = 6.000 pesos.

Ahora probemos con una sola unidad:

2.000 × 1 = 2.000 pesos.

Y con ninguna unidad:

2.000 × 0 = 0 pesos.

Los tres resultados tienen sentido si estamos calculando el importe de una cantidad de unidades sin incluir otros cargos.

Pero todavía debemos pensar en otras situaciones:

- ¿Qué sucede si la cantidad es negativa?
- ¿Qué sucede si el precio no es válido?
- ¿Qué sucede si el usuario escribe un texto en lugar de un número?

Estas preguntas nos ayudan a descubrir situaciones que no habíamos considerado.

No siempre necesitamos resolver todos esos casos de inmediato, pero sí debemos reconocer que existen y decidir qué comportamiento esperamos del sistema.

### La diferencia entre creer y comprobar

Decir «creo que funciona» no es lo mismo que probar una solución.

Cuando realizamos una prueba, establecemos unos datos de entrada, calculamos o ejecutamos los pasos y comparamos el resultado obtenido con el esperado.

Si ambos coinciden, tenemos evidencia de que la solución funciona para ese caso particular.

Para ganar confianza en un algoritmo, necesitamos probar varios casos relevantes, incluidos los límites y las situaciones especiales.

---

## 9. Un método para resolver problemas con lógica

Hasta ahora vimos diferentes habilidades. Vamos a reunirlas en un método que podrás utilizar durante todo el curso.

Cuando te encuentres frente a un problema, sigue estos pasos:

### Paso 1. Comprender el objetivo

Pregúntate qué necesitas conseguir.

No comiences buscando una solución antes de entender el problema.

### Paso 2. Identificar la información

Determina qué datos tienes y cuáles necesitas obtener.

Distingue la información confirmada de las suposiciones.

### Paso 3. Dividir el problema

Si el problema es grande, sepáralo en tareas más pequeñas.

Esto te permitirá concentrarte en una parte a la vez.

### Paso 4. Definir las reglas

Identifica qué operaciones, condiciones o relaciones necesitas utilizar.

Pregúntate qué sucede cuando los datos cambian.

### Paso 5. Diseñar la solución

Organiza los pasos necesarios para alcanzar el objetivo.

Puedes comenzar escribiendo instrucciones con palabras comunes.

### Paso 6. Comprobar la solución

Prueba diferentes situaciones y analiza si los resultados tienen sentido.

Si encuentras un error, revisa el razonamiento y modifica los pasos necesarios.

### Paso 7. Explicar por qué funciona

Intenta justificar por qué tu solución resuelve el problema.

Si no puedes explicar cómo llegaste al resultado, probablemente necesites revisar alguna parte del razonamiento.

Este método no es una regla rígida que debas seguir siempre de manera idéntica. Es una guía para aprender a resolver problemas con mayor claridad y orden.

---

## Ejercicios para desarrollar el pensamiento lógico

Ahora te toca practicar. Intenta resolver cada ejercicio antes de consultar una respuesta o pedir ayuda.

No te limites a dar un resultado: explica cómo llegaste a él.

### Ejercicio 1. Ordenar instrucciones

Quieres preparar tu mochila para ir a estudiar.

Estas son algunas de las acciones que necesitas realizar:

- Comprobar el horario de clases.
- Guardar los materiales necesarios.
- Cerrar la mochila.
- Identificar qué materias tienes ese día.

Ordénalas de una manera lógica y explica por qué elegiste ese orden.

### Ejercicio 2. Encontrar el patrón

Observa la siguiente secuencia:

3, 6, 12, 24, 48, ...

Responde:

1. ¿Qué regla observas?
2. ¿Qué número debería continuar?
3. ¿Cómo comprobarías que tu respuesta sigue la regla?

### Ejercicio 3. Analizar una condición

Una persona puede participar en una actividad si tiene al menos 16 años.

Analiza estos casos:

| Edad | ¿Cumple el requisito? |
| ---: | --- |
| 14 | ¿? |
| 15 | ¿? |
| 16 | ¿? |
| 17 | ¿? |

Explica por qué cambia o se mantiene la respuesta.

### Ejercicio 4. Detectar información faltante

Un estudiante afirma:

«Mi computadora no funciona porque tiene un virus».

¿Qué información tenemos realmente?

1. ¿Qué hecho conocemos?
2. ¿Qué parte de su afirmación es una suposición?
3. ¿Qué pruebas podríamos realizar para investigar el problema?
4. ¿Podría existir otra explicación?

### Ejercicio 5. Dividir un problema

Quieres calcular cuánto gastaste en una tienda después de comprar cinco productos.

Escribe los pasos que seguirías para resolverlo.

Después, responde:

- ¿Qué información necesitas?
- ¿Qué operación debes realizar?
- ¿Cómo comprobarías el resultado?

### Ejercicio 6. Analizar diferentes posibilidades

Un producto cuesta 4.500 pesos. Tienes 4.000 pesos.

1. ¿Cuánto dinero te falta?
2. ¿Qué ocurriría si tuvieras exactamente 4.500 pesos?
3. ¿Qué ocurriría si tuvieras 5.000 pesos?
4. ¿Qué regla general podrías utilizar para determinar si tienes suficiente dinero?

### Ejercicio 7. Encontrar un error de razonamiento

Una persona dice:

«Cada vez que llevo paraguas, llueve. Por lo tanto, si mañana llevo paraguas, seguramente lloverá».

¿La conclusión está justificada por la información proporcionada?

Explica por qué llevar un paraguas no demuestra que vaya a llover.

### Ejercicio 8. Reto de razonamiento

Queremos diseñar un sistema que determine si una persona puede entrar a un evento.

Las reglas son:

- Debe tener una entrada válida.
- Debe tener al menos 18 años.

Responde:

1. ¿Qué datos necesita el sistema?
2. ¿Qué condiciones debe comprobar?
3. ¿Qué debería ocurrir si tiene una entrada válida y 20 años?
4. ¿Qué debería ocurrir si tiene una entrada válida y 17 años?
5. ¿Qué debería ocurrir si tiene 20 años, pero no tiene una entrada válida?
6. ¿Qué debería ocurrir si tiene exactamente 18 años y una entrada válida?

Finalmente, explica cómo organizarías los pasos para resolver el problema.

---

## Resumen

- El **pensamiento lógico** permite analizar información, establecer relaciones y llegar a conclusiones justificadas.
- Organizar los pasos en un orden coherente ayuda a construir soluciones correctas.
- Distinguir hechos de suposiciones evita aceptar explicaciones sin suficiente evidencia.
- Analizar condiciones permite determinar qué hacer cuando cambian las circunstancias.
- La descomposición transforma problemas complejos en tareas más manejables.
- Reconocer patrones permite identificar comportamientos repetitivos y diseñar soluciones reutilizables.
- Las pruebas ayudan a comprobar si una solución funciona en diferentes situaciones.
- Explicar por qué una solución funciona es tan importante como obtener el resultado correcto.

### Idea clave

**Aprender a programar comienza mucho antes de escribir código: comienza cuando aprendemos a analizar un problema, organizar nuestras ideas, comprobar nuestras conclusiones y explicar por qué una solución tiene sentido.**

No necesitas encontrar siempre la respuesta correcta al primer intento. Necesitas desarrollar un método para investigar, razonar, probar y mejorar tus soluciones.

➡️ **Siguiente tema:** [1.4 - Descomposición de problemas: dividir para resolver](./04-descomposicion.md)
