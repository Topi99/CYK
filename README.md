# README

## Algoritmo CYK

Implementación en Python 3 del algoritmo CYK para verificar la aceptación de una cadena dependiendo de una Gramática Libre de Contexto (GLC).

## Ejecución

`$ python3 cyk.py < input.txt`

## Input

El programa recibe un archivo de entrada, con la GLC en el siguiente formato:
  ```
  S AB BC
  A BA a
  B CC b
  C AB a
  ```
Después de la GLC siguen las cadenas que se desean revisar.

## Output

El programa imprime una cadena de texto, si se acepta la cadena ingresada imprime "Accepted", de lo contrario escribe "Rejected".

### Elaborado por Topiltzin Hernández Mares para la materia de Matemáticas Computacionales.