# Tarea: Mi prompt profesional

## Funcionalidad elegida

Un programa en Java que pide las notas de un estudiante, calcula su promedio e indica si aprobo o desaprobo.
## Version 1: prompt basico
```text
Haz un programa que calcule notas.
```

**Resultado:** la IA hizo el programa en Python, uso una escala de 0 a 10 con aprobado desde 5 y escribio "Suspenso".

**Que falto:** no dije el lenguaje, la escala de notas ni la nota minima para aprobar, asi que la IA tuvo que adivinar.

## Version 2

```text
Actua como desarrollador Java. Crea un programa en Java que pida 3 notas de un estudiante en escala de 0 a 20, calcule el promedio e indique "Aprobado" si el promedio es 11 o mas, o "Desaprobado" si es menor.
```

**Que cambie:** agregue el rol (desarrollador Java), el lenguaje, la cantidad de notas, la escala de 0 a 20 y la nota minima para aprobar.

**Por que:** en la version 1 la IA adivino todo eso y lo hizo en Python con escala de 0 a 10.

**Que mejoro:** ahora el programa esta en Java, usa la escala de 0 a 20 y muestra "Aprobado" o "Desaprobado". Pero no explica el codigo y todo esta dentro del main.
## Version 3: prompt final

```text
Actua como desarrollador Java. Soy estudiante de programacion orientada a objetos y necesito un programa de consola para calcular las notas de un curso. Crea un programa en Java que pida el nombre del estudiante y 3 notas en escala de 0 a 20, valide que cada nota este en ese rango, calcule el promedio con un metodo calcularPromedio() e indique "Aprobado" si el promedio es 11 o mas, o "Desaprobado" si es menor. No uses librerias externas, solo Scanner. La salida debe verse asi: Estudiante: Ana | Promedio: 14.33 | Aprobado. Explica primero en 3 lineas como funciona el programa y luego presenta el codigo Java completo.
```

**Que cambie:** agregue el contexto (soy estudiante de POO), el nombre del estudiante, la validacion de notas, el metodo calcularPromedio(), una restriccion (solo Scanner), un ejemplo de la salida y el formato de la respuesta.

**Por que:** en la version 2 la IA no explicaba el codigo y ponia todo dentro del main.

**Que mejoro:** la IA explico primero en 3 lineas, creo una clase Estudiante con el metodo calcularPromedio(), valido las notas y mostro la salida igual al ejemplo.
## Componentes del prompt final

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. |
| Contexto | Soy estudiante de programacion orientada a objetos y necesito un programa de consola para calcular las notas de un curso. |
| Instruccion | Crea un programa en Java que pida el nombre del estudiante y 3 notas en escala de 0 a 20, valide que cada nota este en ese rango, calcule el promedio con un metodo calcularPromedio() e indique "Aprobado" si el promedio es 11 o mas, o "Desaprobado" si es menor. |
| Restriccion | No uses librerias externas, solo Scanner. |
| Ejemplo | La salida debe verse asi: Estudiante: Ana \| Promedio: 14.33 \| Aprobado. |
| Formato | Explica primero en 3 lineas como funciona el programa y luego presenta el codigo Java completo. |
## Evaluacion del resultado

| Criterio | Cumple |
|----------|--------|
| El programa esta en Java | Si |
| Pide el nombre y 3 notas de 0 a 20 | Si |
| Valida que las notas esten entre 0 y 20 | Si |
| Usa un metodo calcularPromedio() | Si |
| Muestra Aprobado o Desaprobado con nota minima 11 | Si |
| Solo usa Scanner, sin librerias externas | Si |
| Explica primero y luego presenta el codigo | Si |
| La salida tiene el formato del ejemplo | Si |
## Errores que evite
1. **Ser demasiado general:** en la version 1 solo pedi "un programa que calcule notas" y la IA lo hizo en Python con una escala de 0 a 10. Lo evite diciendo el lenguaje, la cantidad de notas, la escala de 0 a 20 y la nota minima para aprobar.

2. **No indicar el formato:** en la version 2 la IA entrego solo el codigo, sin explicarlo. Lo evite pidiendo que explique primero en 3 lineas y luego presente el codigo, y dando un ejemplo de como debe verse la salida.