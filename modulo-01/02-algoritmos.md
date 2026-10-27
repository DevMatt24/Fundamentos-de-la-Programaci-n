# 1.2 - Algoritmos: el corazón de la programación

## ¿Qué es un algoritmo?

Un **algoritmo** es una secuencia de pasos **finitos**, **ordenados** y **sin ambigüedad** que resuelven un problema.

La palabra suena técnica, pero los usas todos los días:

**Ejemplo: algoritmo para hacer café**

```javascript
1. Hervir agua
2. Poner café en la taza
3. Verter el agua caliente
4. Revolver
5. (Opcional) Agregar azúcar
```

## Características de un buen algoritmo

| Característica | Significado |
| --- | --- |
| **Finito** | Debe terminar en algún momento |
| **Preciso** | Cada paso debe ser claro, sin ambigüedad |
| **Ordenado** | Los pasos se ejecutan en un orden lógico |
| **Entrada y salida** | Recibe datos (entrada) y produce un resultado (salida) |

## Pseudocódigo

El **pseudocódigo** es una forma de escribir algoritmos en lenguaje casi natural, sin las reglas estrictas de un lenguaje de programación. Sirve para diseñar la solución antes de programarla.

**Ejemplo: sumar dos números**

```javascript
INICIO
    Leer numero1
    Leer numero2
    suma <- numero1 + numero2
    Mostrar suma
FIN
```

## Diagramas de flujo

Otra forma de representar algoritmos es con **diagramas de flujo**, usando símbolos gráficos:

```javascript
  (Inicio)
     |
     v
 [Leer número]  <- Entrada
     |
     v
(¿Es mayor que 0?) <- Decisión
   |         |
  Sí         No
   |         |
   v         v
[Mostrar    [Mostrar
"Positivo"]  "Negativo"]
     |
     v
   (Fin)
```

## De la idea al programa

```javascript
Problema -> Algoritmo -> Código -> Programa
(idea)     (pseudocódigo) (Python, etc.) (ejecutable)
```

> 💡 **Consejo:** Antes de escribir código, escribe el algoritmo en papel o pseudocódigo. Ahorrarás mucho tiempo de corrección.

## 📌 Resumen

- Un algoritmo es un conjunto de pasos ordenados para resolver un problema.
- Existen herramientas para diseñar algoritmos: **pseudocódigo** y **diagramas de flujo**.
- Todo programa parte de un algoritmo: primero piensa la solución, luego escríbela en código.

➡️ Siguiente tema: [03 - Lenguajes de programación](./03-lenguajes.md)
