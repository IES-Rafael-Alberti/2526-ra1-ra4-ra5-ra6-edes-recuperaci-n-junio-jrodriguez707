[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/VU3nxsxY)
# 2526 - Recuperación de entornos de desarrollo - DAW

> AVISO!!! Únicamente puedes usar un editor (No IDE) y la documentación de plantUML para generar los diagramas UML. El uso de cualquier recurso que no sean estos, supondrá la no superación de la prueba.

> Evaluación de RA1, RA4, RA5 y RA6.
 
---
**Nombre:** [Nombre del alumno]
**RA de los que te examinas:** [RA de los que te examinas. Ojo, no confundas RAs con Unidad]
---


Edita este archivo y responde a las siguientes preguntas, justo debajo de *"Respuesta a la pregunta X"*. Luego, sube los cambios


## RA1 (10 Puntos) - Unidad 1

### 1. (4 puntos - 5 min) ¿Cómo interactúan los distintos **elementos de un ordenador** durante la ejecución de un programa software? Nombra los elementos y describe el proceso desde que se da la orden de ejecutar un programa hasta que pasa a ejecutarse y termina.

*Respuesta a la pregunta 1. (mínimo 300 palabras)*


---

### 2. (6 puntos - 15 min) Características de los siguientes Lenguajes de Programación: Python, Java, C, JavaScript. Habla sobre aspectos relacionados con (Nivel de abstracción, Modo de ejecución, Paradigmas, Características)
Un ejemplo: Kotlin
#### Kotlin — Ficha de características
Kotlin es un lenguaje de **alto nivel**, normalmente **compilado a bytecode** para ejecutarse sobre la **JVM**. Permite trabajar con **clases, objetos y funciones**, y se utiliza mucho en el desarrollo de aplicaciones Android. Su ventaja principal es que permite escribir código claro, moderno y con menos errores habituales, como los relacionados con valores nulos.

| Aspecto                         | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------- |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nivel de abstracción**        | Kotlin es un lenguaje de **alto nivel**. Esto significa que escribimos instrucciones que son fáciles de entender para una persona, sin tener que trabajar directamente con unos y ceros, memoria o instrucciones del procesador. Por ejemplo, podemos crear variables, funciones y clases de una forma bastante clara.                                                                                                                                                                                                                                                                                                                                         |
| **Modo de ejecución**           | Normalmente, Kotlin se usa sobre la **JVM**, la misma máquina virtual que utiliza Java. El proceso sería: escribimos **código fuente** en Kotlin, el compilador lo transforma en un código intermedio llamado **bytecode**, y después la JVM lo ejecuta. Por eso, un programa Kotlin puede funcionar en distintos sistemas siempre que tengan instalada la máquina virtual adecuada.                                                                                                                                                                                                                                                                           |
| **Paradigmas soportados**       | Kotlin permite programar de varias formas. Principalmente se usa como lenguaje **orientado a objetos**, porque permite crear clases y objetos. También permite usar funciones de forma cómoda, por lo que tiene características de programación **funcional**. Para este nivel, lo importante es entender que Kotlin nos permite organizar el programa en clases, funciones y datos.                                                                                                                                                                                                                                                                           |
| **Características principales** | Kotlin es un lenguaje moderno, claro y bastante seguro. Una de sus características más importantes es que ayuda a evitar errores con valores `null`. También permite escribir menos código que Java para hacer algunas tareas. Además, se puede usar junto con Java, por lo que muchas librerías de Java pueden utilizarse también en Kotlin. Kotlin se utiliza mucho en el desarrollo de aplicaciones Android, aunque también puede utilizarse para programas de escritorio, aplicaciones de servidor y otros tipos de proyectos. En clase lo hemos usado para aprender programación estructurada, funciones, clases, objetos y buenas prácticas. `fun main() { println("Hola mundo") } ` Este programa muestra por pantalla el texto `Hola mundo`.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |


*Respuesta a la pregunta 2. (mínimo 500 palabras)*


---

---


## RA4 (15 Puntos) - Unidad 6

### 8. (5 puntos - 10 min) ¿Qué áreas principales utiliza git para gestionar los cambios en un proyecto y para qué sirven cada uno?

*Respuesta a la pregunta 8. (mínimo 200 palabras)*


---


### 9. (10 puntos - 30 min) Estás en un repositorio local, y usas git para realizar el control de versiones de tu código. ¿Qué comando ejecutarías para estas situaciones?

Ejemplo de respuesta:
0. Inicializa un proyecto.
    + comando: `git init`

*Responde a las siguientes situaciones:*

1. Ver el historial de commits en una sola línea.
    + comando: 
   
2. Deshacer el último commit y deshacer cambios. Eliminar los cambios.
    + comando:

3. Crear la rama `featureA` y cambiar a ella.
    + comando:

4. Ver el estado del repositorio.
    + comando:

5. Clonar el repositorio `https://github.com/revilofe/HundirFlota.git`.
    + comando:

6. Descargar al repositorio local los cambios del remote `origin` rama `main`.
    + comando:

7. Subir los cambios del repositorio local al remote `origin` rama `main`.
    + comando:

8. Combinar la rama `featureA` con la rama principal.
    + comando:

9. Aplicar rebase a la rama `featureA` con la rama principal.
    + comando:

10. Continuar el rebase de la rama `featureA` con la rama principal, una vez resueltos los conflictos.
    + comando: 

---

---

## RA5 (15 Puntos) - Unidad 3

### 11. (15 puntos - 30 min) En este ejercicio, deberás modelar la relación que puede haber en una empresa: los **departamentos** están compuestos por diferentes tipos de **empleados**, entre los cuales se distingue entre **jefes** y **subordinados**. Cada departamento puede contener múltiples empleados, y cada jefe supervisa a uno o varios subordinados. Esto tendrás que realizarlo utilizando un **diagrama de clases UML**


**Requisitos del Ejercicio**

1. **Clases Principales**
2. **Relaciones entre Clases**
3. **Propiedades y Métodos**


**Entrega:** 
1. (5 puntos) Código origen e imagen del diagrama, generada por la herramienta UML con el diagrama de clases. https://www.plantuml.com/   

    *Respuesta a la pregunta 11.1*


2. (5 puntos) Código fuente, por ejemplo en kotlin, del diagrama de clases.

    *Respuesta a la pregunta 11.2*



3. (5 puntos) Explicación de las clases, relaciones entre clases y propiedades y métodos.

    *Respuesta a la pregunta 11.3*


---

---

## RA6 (15 Puntos) - Unidad 4

### 12. (15 puntos - 30 min) En este ejercicio, deberás modelar el ciclo de vida de un usuario dentro de un sistema utilizando un **diagrama de estados UML**.

El sistema gestiona a los usuarios en tres estados fundamentales:

* **Activo**: El usuario tiene acceso completo al sistema.
* **Bloqueado**: El usuario ha sido restringido debido a intentos fallidos de inicio de sesión o actividad sospechosa.
* **Desactivado**: El usuario ha decidido desactivar su cuenta o esta ha sido desactivada automáticamente por inactividad prolongada. No tiene por qué estar activo en el sistema para pasar a Desactivado.

**Requisitos del Ejercicio**

1. **Identificar los estados** en los que puede encontrarse un usuario dentro del sistema.
2. **Definir las transiciones** entre los estados, considerando las condiciones (**guardas**) y las **acciones** que se deben realizar en cada caso.
3. **Incluir las acciones de entrada y actividades internas** en los estados cuando sea necesario.

**Reglas del Negocio**

* Un usuario inicia en el estado **Activo** tras completar su registro.
* El usuario pasa a estado **Bloqueado** si supera **3 intentos fallidos** de inicio de sesión o si se detecta actividad sospechosa.
* El usuario pasa a estado **Desactivado** si solicita desactivar su cuenta o si permanece inactivo por más de **6 meses**.
* Un usuario en estado **Bloqueado** puede ser desbloqueado manualmente por un administrador o automáticamente por el sistema.
* Un usuario en estado **Desactivado** puede solicitar la reactivación de su cuenta.


**Entrega:**
1. (5 puntos) Imagen generada por la herramienta UML con el diagrama de estados. https://www.plantuml.com/
   
   *Respuesta a la pregunta 12.1*



2. (5 puntos) Código fuente del diagrama de estados.
   
   *Respuesta a la pregunta 12.2*



3. (5 puntos) Explicación de estados y sus acciones/actividades, transiciones y sus guardas.
   
   *Respuesta a la pregunta 12.3*


---

---

> Recuerda que debes subir los cambios al repositorio remoto.

[Acceso a la descripción y soluciones](https://docs.google.com/document/d/1vnTLuDog6NbLF6gQCbvKI3RiIr9Yd8GTjR7aYQ8xwzY/edit?usp=sharing)
