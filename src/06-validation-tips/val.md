# Embeber vs Referenciar

1. Embeber: Usar sub-documentos para realizar las relaciones, que esta un documento dentro de otro.

- Mejora rendimiento en busqueda de muchos datos relacionados
- Limitado a 1-1 y 1-N en una direccion
- Cambios contenidos

2. Referenciar: Los documentos estan separados y se hacen referencia entre ellos con identificadores. En UML, se expresan con cajitas separadas y una cardinalidad.

- Reduce el tamaño de la base de datos
- No repetir datos
- Actualizacion de datos unica para muchos
- Permite 1-1, 1-N, N-1 y N-N
- Preguntas para decidir cual
- ¿Que tan frecuente es consultada esa información?
- ¿Que tan frecuente se actualiza esa información?
- ¿La información se consulta en conjunto o por partes?