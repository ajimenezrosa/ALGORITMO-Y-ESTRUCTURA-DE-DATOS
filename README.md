# Manual de Algoritmos y Estructuras de Datos

## Índice

1. [Introducción](#introducción)
    - [¿Qué son los algoritmos y las estructuras de datos?](#qué-son-los-algoritmos-y-las-estructuras-de-datos)
    - [Aplicaciones prácticas](#aplicaciones-prácticas)
2. [Análisis de Algoritmos](#análisis-de-algoritmos)
    - [Notación Big O](#notación-big-o)
    - [Complejidad temporal y espacial](#complejidad-temporal-y-espacial)
    - [Análisis de casos](#análisis-de-casos)


3.  [Estructura de datos primitivas](#primitivas)
4. [Decisiones e Iteraciones](#iteracinoes)

## Introducción

### ¿Qué son los algoritmos y las estructuras de datos?

**Definición de algoritmos:**
Los algoritmos son conjuntos de instrucciones lógicas y bien definidas diseñadas para resolver un problema o realizar una tarea específica. Estas instrucciones pueden ser expresadas en forma de pseudocódigo, diagramas de flujo o en algún lenguaje de programación. Los algoritmos son la esencia del pensamiento computacional y son utilizados en todas las áreas de la informática.

**Definición de estructuras de datos:**
Las estructuras de datos se refieren a la forma en que se organizan y se almacenan los datos en la memoria de una computadora. Estas estructuras son fundamentales para la eficiencia y la optimización de los algoritmos, ya que determinan cómo se accede y se manipula la información. Ejemplos comunes de estructuras de datos incluyen listas, pilas, colas, árboles, grafos, entre otros.

**Importancia en informática:**
Tanto los algoritmos como las estructuras de datos son fundamentales en informática. Los algoritmos proporcionan un enfoque sistemático para resolver problemas, mientras que las estructuras de datos permiten organizar y manipular eficientemente grandes cantidades de datos. Estas herramientas son utilizadas en una amplia variedad de aplicaciones, desde el desarrollo de software hasta la optimización de procesos en empresas.

### Aplicaciones prácticas

**Ejemplos de uso en la vida real:**
- Los algoritmos de búsqueda se utilizan en motores de búsqueda en internet para encontrar resultados relevantes.
- Las estructuras de datos como los árboles se utilizan en bases de datos para organizar y recuperar información de manera eficiente.
- Los algoritmos de enrutamiento se utilizan en sistemas de navegación para encontrar la ruta más corta entre dos ubicaciones.

**Importancia en el desarrollo de software:**
- Los programadores utilizan algoritmos y estructuras de datos para diseñar y optimizar algoritmos.
- Comprender los principios de los algoritmos y las estructuras de datos es fundamental para escribir código eficiente y escalable.
- Las entrevistas de trabajo en informática a menudo incluyen preguntas sobre algoritmos y estructuras de datos para evaluar las habilidades de resolución de problemas de los candidatos.

# 
# Estructura de datos primitivas<a name="primitivas"></a>

Claro, aquí tienes una explicación sobre estructuras de datos y datos primitivos, diseñada para ser clara y adecuada para una clase de estructura de datos.

---

### **Introducción a Estructuras de Datos**

Una **estructura de datos** es una forma particular de organizar y almacenar datos en una computadora de tal manera que podamos acceder y modificar esos datos de manera eficiente. Las estructuras de datos son fundamentales en la programación y la informática porque nos permiten manejar grandes cantidades de datos de manera efectiva.

Las estructuras de datos se dividen en dos categorías principales:
1. **Estructuras de datos primitivos** (o tipos de datos primitivos)
2. **Estructuras de datos no primitivas**

### **Datos Primitivos**

Los **datos primitivos** son los tipos de datos más básicos y fundamentales que proporciona un lenguaje de programación. Son los bloques de construcción básicos con los que se pueden crear estructuras de datos más complejas. Algunos ejemplos comunes de datos primitivos incluyen:

1. **Enteros (int)**
   - Representan números enteros.
   - Ejemplo: `10`, `-5`, `42`
   - En Python: `x = 10`

2. **Punto Flotante (float)**
   - Representan números con decimales.
   - Ejemplo: `3.14`, `-0.001`, `2.718`
   - En Python: `pi = 3.14`

3. **Caracteres (char)**
   - Representan un solo carácter.
   - Ejemplo: `'a'`, `'Z'`, `'$'`
   - En Python, los caracteres se tratan como cadenas de longitud uno: `letra = 'a'`

4. **Booleanos (bool)**
   - Representan valores de verdad.
   - Ejemplo: `True`, `False`
   - En Python: `es_verdad = True`

5. **Cadena de caracteres (string)**
   - Representan una secuencia de caracteres.
   - Ejemplo: `"Hola"`, `"Estructuras de Datos"`, `"12345"`
   - En Python: `mensaje = "Hola Mundo"`

### **Estructuras de Datos No Primitivas**

Las **estructuras de datos no primitivas** se construyen a partir de los datos primitivos y nos permiten organizar grandes cantidades de datos de manera eficiente. Algunos ejemplos comunes incluyen:

1. **Arreglos (Arrays)**
   - Colecciones de elementos del mismo tipo, almacenados en ubicaciones contiguas de memoria.
   - Ejemplo en Python: `numeros = [1, 2, 3, 4, 5]`

2. **Listas**
   - Similar a los arreglos, pero pueden contener elementos de diferentes tipos y su tamaño es dinámico.
   - Ejemplo en Python: `mi_lista = [1, "dos", 3.0, True]`

3. **Pilas (Stacks)**
   - Colecciones de elementos con acceso restringido, donde solo se puede agregar o quitar elementos desde el tope (LIFO: Last In, First Out).
   - Ejemplo: Manejo de historial en un navegador web.

4. **Colas (Queues)**
   - Colecciones de elementos donde se añaden elementos al final y se eliminan del frente (FIFO: First In, First Out).
   - Ejemplo: Sistema de impresión de documentos en una impresora.

5. **Listas Enlazadas (Linked Lists)**
   - Colección de elementos llamados nodos, donde cada nodo contiene un valor y una referencia al siguiente nodo en la secuencia.
   - Ejemplo: Implementación de una lista de tareas.

6. **Árboles (Trees)**
   - Estructuras jerárquicas donde cada nodo tiene un valor y referencias a nodos hijos.
   - Ejemplo: Representación de una organización jerárquica.

7. **Grafos (Graphs)**
   - Conjunto de nodos (o vértices) conectados por aristas (o arcos).
   - Ejemplo: Redes sociales, donde cada nodo representa una persona y cada arista una amistad.

### **Ejemplos en Código**

#### Enteros y Operaciones Básicas
```python
a = 10
b = 5
suma = a + b        # 15
resta = a - b       # 5
producto = a * b    # 50
division = a / b    # 2.0
```

#### Cadenas y Operaciones Básicas
```python
saludo = "Hola"
nombre = "Mundo"
mensaje = saludo + " " + nombre  # "Hola Mundo"
longitud = len(mensaje)          # 10
```

#### Uso de Listas
```python
mi_lista = [1, 2, 3, 4, 5]
mi_lista.append(6)              # [1, 2, 3, 4, 5, 6]
primer_elemento = mi_lista[0]   # 1
```

### **Conclusión**

Entender los datos primitivos y cómo se pueden usar para construir estructuras de datos más complejas es esencial para cualquier programador. Estas estructuras permiten organizar, gestionar y manipular datos de manera eficiente, lo cual es fundamental para resolver problemas en el mundo real.

---

Claro, a continuación, añadiré una explicación sobre decisiones e iteraciones, incluyendo ejemplos en pseudocódigo y en lenguajes de programación como Python.

---

## **Decisiones e Iteraciones**<a name="iteracinoes"></a>

En la programación, es común tomar decisiones y repetir bloques de código. Para esto, utilizamos estructuras de control como las decisiones (if, switch) y las iteraciones (while, for). Estas estructuras nos permiten controlar el flujo de un programa.

### **Decisiones**

#### **Condicionales (if-else)**

La estructura condicional `if-else` permite ejecutar un bloque de código si se cumple una condición y otro bloque si no se cumple.

**Pseudocódigo:**
```
si (condición) entonces
    // Código a ejecutar si la condición es verdadera
sino
    // Código a ejecutar si la condición es falsa
fin si
```

**Ejemplo en Python:**
```python
edad = 18
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

#### **Condicional múltiple (switch-case)**

La estructura `switch-case` permite seleccionar entre varias alternativas posibles basadas en el valor de una variable.

**Pseudocódigo:**
```
según (variable) hacer
    caso valor1:
        // Código a ejecutar si variable == valor1
    caso valor2:
        // Código a ejecutar si variable == valor2
    defecto:
        // Código a ejecutar si ninguna de las condiciones anteriores se cumple
fin según
```

**Ejemplo en Python (usando un diccionario para simular switch-case):**
```python
def switch_case(dia):
    dias = {
        "Lunes": "Inicio de semana",
        "Martes": "Segundo día de la semana",
        "Miércoles": "Mitad de semana",
        "Jueves": "Casi fin de semana",
        "Viernes": "Último día laboral",
        "Sábado": "Día de descanso",
        "Domingo": "Día de descanso"
    }
    return dias.get(dia, "Día no válido")

print(switch_case("Lunes"))
```

### **Iteraciones**

#### **Bucle `while`**

El bucle `while` repite un bloque de código mientras se cumpla una condición.

**Pseudocódigo:**
```
mientras (condición) hacer
    // Código a ejecutar mientras la condición sea verdadera
fin mientras
```

**Ejemplo en Python:**
```python
contador = 0
while contador < 5:
    print("Contador:", contador)
    contador += 1
```

#### **Bucle `for`**

El bucle `for` se usa para iterar sobre una secuencia (como una lista, una tupla, un diccionario, un conjunto o una cadena).

**Pseudocódigo:**
```
para (inicialización; condición; actualización) hacer
    // Código a ejecutar en cada iteración
fin para
```

**Ejemplo en Python (iterando sobre una lista):**
```python
numeros = [1, 2, 3, 4, 5]
for numero in numeros:
    print("Número:", numero)
```

**Ejemplo en Python (usando range para una secuencia de números):**
```python
for i in range(5):
    print("Iteración:", i)
```

### **Conclusión**

Las estructuras de control como las decisiones e iteraciones son esenciales en la programación para manejar el flujo del programa y repetir acciones de manera eficiente. Las decisiones `if-else` y `switch-case` permiten tomar caminos diferentes basados en condiciones, mientras que los bucles `while` y `for` nos permiten repetir acciones hasta que se cumpla una condición o a lo largo de una secuencia.

---

Espero que esta explicación adicional sobre decisiones e iteraciones sea útil para tu clase de estructuras de datos. ¡Buena suerte!