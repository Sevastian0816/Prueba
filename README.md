# Prueba
Primera tarea de clase Sevastian Sanchez 

Taller de Python

Programación Básica – Primer Semestre

Objetivo General

Fortalecer el pensamiento lógico y el desarrollo de programas básicos en Python
mediante preguntas abiertas y ejercicios prácticos.

Parte 1

Conceptos Básicos

1. ¿Qué es Python y para qué se utiliza?
   -Python es un lenguaje de programación de alto nivel. Fue creado por Guido van russem y lanzado por primer vez en 1991. Si diseño permite escribir códigos más simples y claros en comparación con otros lenguajes, por lo que es muy utilizado tanto ppr principiantes como por programadores profesionales 

 Phyton se utiliza para desarrollar diferentes tipos de programas y aplicaciones como por ejemplo, sitios webs, aplicaciones moviles y de escritorio, programas de automatización y sistemas de inteligencia artificial. Python es un lenguaje de propósito general, lo que significa que se puede utilizar para crear una variedad de programas diferentes y no está especializado en ningún problema específico. Esta versatilidad, junto con su facilidad para los principiantes, lo ha convertido en uno de los lenguajes de programación más utilizados en la actualidad.

2. ¿Cuáles son las ventajas de programar en Python?
 Los desarrolladores pueden leer y comprender fácilmente los programas de Python debido a su sintaxis básica similar a la del inglés. 

•Python permite que los desarrolladores sean más productivos, ya que pueden escribir un programa de Python con menos líneas de código en comparación con muchos otros lenguajes.

•Python es muy versátil, ya que se puede utilizar para crear páginas web, aplicaciones, videojuegos, programas de automatización, inteligencia artificial y análisis de datos. También cuenta con una gran cantidad de librerías y herramientas que ayudan a desarrollar proyectos de manera más rápida y eficiente, de esta manera, los desarrolladores no tienen que escribir el código desde cero.

•Los desarrolladores pueden utilizar Python fácilmente con otros lenguajes de programación conocidos, como Java, C y C++.

3. ¿Qué diferencia existe entre una variable numérica y una variable tipo texto?
La diferencia entre una variable numérica y una variable tipo texto está en la información que almacenan y el tipo de operaciones que se pueden realizar con ellas 

La variable tipo numérica se utilizan para guardar números y realizar operaciones matemáticas como las suma, resta, multiplicacion, etc..
Mientras que la variable tipo texto se utiliza para guardar información escrita o caracteres

4. Explique con sus palabras qué es un algoritmo.
Se le denomina algoritmo a un conjunto de pasos que se siguen o realizan para resolver un problema o realizar una tarea.

5. ¿Por qué es importante la indentación en Python? 
Es importante porque define los bloques de código y afecta cómo se ejecuta el programa. Si está mal hecha, puede causar errores o cambiar el resultado. Además, mejora la lectura del código.

Parte 2 – Análisis de Código
Observe el siguiente programa:
nombre = input("Digite su nombre: ")
print("Bienvenido", nombre)
Responda:
1. ¿Qué función cumple input()?
. La función input() se utiliza para pedirle información a el usuario, en este caso el nombre
Cuando el programa llega a esa linea se detiene y espera que el usuario o persona escriba
2. ¿Qué función cumple print()?
3. Print() sirve para mostrarle al usuario información, en este caso muestra la palabra "Bienvenido"

Si colocaríamos 

print("Hola", nombre)

Al colocar el código nos aparecerá al final 

Hola y el nombre que escribiste
4. ¿Qué dato almacena la variable nombre? 
La variable "nombre"  almacena un dato de tipo cadena de texto (conocido como string). Se utiliza para guardar información como el nombre de una persona, un objeto o un identificador
Parte 3 – Variables y Operadores
Responda
1. ¿Qué es una variable en programación?
   Una variable es un espacio o referencia con nombre que permite
almacenar información. Su contenido puede cambiar durante la ejecución del programa
2. ¿Cuál es la diferencia entre:
 +
 -
 *
 / 
12 + 4   # 16
12 - 4   # 8
12 * 4   # 48
12 / 4   # 3.0

+ suma dos valores.

- resta el valor 

* multiplica.

/ divide y el resultado casi siempre es decimal.

3. ¿Qué sucede si se divide un número entre cero?
Dividir cualquier cantidad entre cero no arroja ningún valor. El cálculo no genera una cifra real, sino que se trata de una acción matemática indefinida.
Parte 4 – Condicionales
Analice el siguiente código:
edad = int(input("Digite su edad: "))
if edad >= 18:
 print("Es mayor de edad")
else:
 print("Es menor de edad")
Responda:
1. ¿Qué evalúa la condición?
Evalúa que el usuario cumpla con la mayoría de edad
2. ¿Qué ocurre si el usuario digita 20?
   Se muestra un mensaje con el texto "Eres mayor de edad"
3. ¿Qué ocurre si el usuario digita 15?
   Se muestra un mensaje con el texto "Eres menor de edad"

Parte 5 – Ciclos
Responda
1. ¿Para qué sirve un ciclo for?
. El ciclo for sirve y fue diseñado para iterar sobre estructuras coleccionables conocidas, como lo son:
Listas, arreglos, cadenas, rangos numéricos, resultados de consultas, etc...
2. ¿Para qué sirve un ciclo while?
   El ciclo while sirve para gestionar la repetición de procesos mediante la evaluación de un estado booleano.
Su función esencial es sostener la ejecución de un segmento de código en un bucle activo. interrumpiéndose únicamente
cuando la expresión lógica de control se vuelve falsa

3. ¿Qué diferencia existe entre for y while?
   El ciclo for y while son estructuras de control de flujo iterativas. Ambos automatizan la ejecución constante
de un fragmento de código, pero la diferencia no está solamente en la sintaxis, la verdadera diferencia está
en la intención semántica y en el modelo que representan.
For Se usa cuando el ciclo depende de una colección o secuencia iterable. Esto ocurre cuando se trabaja con elementos que ya existen y se pueden contar 
While Se usa cuando cuando el ciclo depende de una condición lógica. Se refiere cuando no tienes idea de cuántas repeticiones serán necesarias. el bucle
no depende de una lista si no de una condición
Parte 6 – Ejercicios Prácticos
Ejercicio 1
Realice un programa que solicite dos números y muestre:
 Suma
 Resta
 Multiplicación
 División

# Ejercicio 1
# Programa que solicita dos números y muestra operaciones básicas

num1 = float(input("Ingrese el primer número: "))
num2 = float(input("Ingrese el segundo número: "))

print("Suma:", num1 + num2)
print("Resta:", num1 - num2)
print("Multiplicación:", num1 * num2)

if num2 != 0:
    print("División:", num1 / num2)
else:
    print("No se puede dividir entre 0")

Ejercicio 2
Crear un programa que solicite el nombre y la edad de una persona y muestre si es:
 Niño
 Adolescente
 Adulto

# Ejercicio 2
# Programa que clasifica según la edad

nombre = input("Ingrese su nombre: ")
edad = int(input("Ingrese su edad: "))

if edad < 12:
    print(nombre, "es un Niño")
elif edad < 18:
    print(nombre, "es un Adolescente")
else:
    print(nombre, "es un Adulto")

Ejercicio 3
Realizar un programa que muestre los números del 1 al 20 usando for.
# Ejercicio 3
# Mostrar números del 1 al 20 usando for

for i in range(1, 22):
 print (i)   

Ejercicio 4
Crear un programa que muestre la tabla de multiplicar de un número ingresado por el
usuario.
# Ejercicio 4
# Tabla de multiplicar de un número

numero = int(input("Ingrese un número: "))

for i in range(1, 11):
    print(numero, "x", i, "=", numero * i)





Parte 7 – Preguntas de Reflexión
1. ¿Por qué es importante aprender programación?
      Porque te enseña a resolver paso a paso cualquier problema. Además, te permite automatizar tareas repetitivas y te abre muchas oportunidades de trabajo.
2. ¿En qué áreas se usa Python hoy?
      En casi todo: análisis de datos, páginas web, automatización de tareas, inteligencia artificial, ciberseguridad, ciencia, videojuegos y educación.
3. ¿Cómo ayuda la programación con problemas reales?
      Permite analizar grandes cantidades de información rápido, evitar errores manuales y hacer tareas automáticas (por ejemplo, detectar fraudes, organizar rutas de reparto o ayudar en diagnósticos médicos).

   Parte 8 – Ejercicio de Lógica (5%) ⭐
Problema
Un estudiante necesita calcular el promedio de 3 notas.
Condiciones:
 Si el promedio es mayor o igual a 3.0 → “Aprobó”.
 Si el promedio es menor a 3.0 → “Reprobó”.
Actividad:
Diseñe el algoritmo y luego el código en Python.

# Ejercicio 4
# Tabla de multiplicar de un número

nota1 = float(input("Digite nota 1: "))
nota2 = float(input("Digite nota 2: "))
nota3 = float(input("Digite nota 3: "))
promedio = (nota1 + nota2 + nota3) / 3
print (promedio)
if promedio >= 3.0:
 print("Aprobó")
else:
 print("Reprobó")
