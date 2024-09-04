# Frecuencias de aparición

## Descripción

Este programa permite al usuario introducir una cadena de caracteres y luego analiza cuántas veces aparece cada uno de los caracteres dentro de la cadena. Al final, imprime un diccionario en el que las claves son los caracteres de la cadena y los valores corresponden a la cantidad de veces que cada carácter aparece. **Este tipo de procesamiento básico de datos puede ser muy útil en tareas de *data engineering*, donde se requiere analizar, limpiar y transformar datos textuales para su uso en sistemas más complejos, como bases de datos o análisis de grandes volúmenes de información.**

## Funcionamiento

1. **Entrada de la cadena**: El programa solicita al usuario que introduzca una cadena de texto.
   
2. **Conversión a minúsculas**: La cadena introducida se convierte completamente en minúsculas para que el conteo no distinga entre mayúsculas y minúsculas. Esto asegura que "A" y "a" se consideren el mismo carácter.

3. **Conteo de caracteres**: El programa recorre cada carácter de la cadena y los almacena en un diccionario. Si el carácter ya existe en el diccionario, incrementa su valor en 1. Si es la primera vez que aparece, lo añade al diccionario con un valor de 1.

4. **Salida**: Al final, el programa muestra el diccionario que contiene cada carácter encontrado en la cadena y la cantidad de veces que se repite.

## Ejemplo de uso

Si el usuario introduce la cadena: `Hola Mundo`, el programa devolverá algo como:

```
{'h': 1, 'o': 2, 'l': 1, 'a': 1, ' ': 1, 'm': 1, 'u': 1, 'n': 1, 'd': 1}
```

## Consideraciones

- El programa no distingue entre caracteres alfabéticos, espacios o signos de puntuación, es decir, cuenta todos los caracteres de la cadena.
- Los espacios también se cuentan como un carácter.
  
**En el ámbito de la ingeniería de datos, procesos como este son fundamentales para estructurar y preparar datos de entrada para análisis posteriores, optimizando su almacenamiento y facilitando la toma de decisiones a partir de los datos procesados.**
