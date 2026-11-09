# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts.

Herramienta de IA usada: (escribe aqui cual usaste)

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens | 
|-------|------------|--------| 
| Los estudiantes programan en Java. |34 |7 | 
| The students program in Java. |28 | 5| 
| desafortunadamente |19 | 5| 

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100.0% | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5 | 65.3% | BiblioTec, PrestaLibro, BiblioTec, BiblioTec, BiblioTec |
| 1 | 44.5% | BiblioTec, LectoGo, PrestaLibro, BiblioTec, LibroYa |
| 1.8 | 32.2% | LibroYa, LibroYa, BiblioTec, LibroYa, PaginaLibre |

## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |SI |SI |
| Menciona a los usuarios principales |NO |SI |
| Tiene exactamente 3 funcionalidades |NO |SI |
| Esta en 3 parrafos |NO |SI |
| Lo usaria en un informe real |NO |SI |
## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. |
| Instruccion | Crea un programa en Java usando una clase Producto con los atributos codigo, nombre, precio y stock. |
| Contexto | para gestionar los productos de una tienda |
| Ejemplo | Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato | Explica primero la estructura de la clase y luego presenta el codigo Java. |