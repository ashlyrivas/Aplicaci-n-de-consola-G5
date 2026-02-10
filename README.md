# Aplicaci-n-de-consola-G5
Este repositorio es para subimos el desarrollo
Explicación Técnica del Programa

BREVE EXPLICACION DE LO QUE SE UTILIZO EN LA APLICACIÓN
Por qué se usó: Para almacenar las 3 notas de cada uno de los 5 estudiantes en una estructura matricial. Permite acceso directo con notas[estudiante, nota].

Arreglo Unidimensional double[] promedios
Por qué se usó: Para almacenar los cálculos individuales. Separa el almacenamiento de datos brutos (notas) de los procesados (promedios).

Ciclos for Anidados
Por qué se usaron: Para recorrer sistemáticamente estudiantes (5 iteraciones) y sus notas (3 iteraciones). Control preciso del flujo sin condicionales complejos.

Validación double.TryParse()
Por qué se usó: Para asegurar que solo se acepten números válidos entre 0-20. Previene errores por entrada incorrecta del usuario.

Variables Temporales suma
Por qué se usó: Para acumular las 3 notas antes del cálculo del promedio, manteniendo operaciones simples y legibles.

Formato :F2 en Strings
Por qué se usó: Para mostrar promedios con 2 decimales, dando precisión profesional sin complicar el cálculo interno.
