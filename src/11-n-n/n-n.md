# Relaciones muchos a muchos

La relacion muchos a muchos (N-N) es cuando un documento de una coleccion A puede estar relacionado con varios documentos de una coleccion B y viceversa.
Esta relacion es siempre Referencial.

Se pueden realizar de 2 formas:

- Con una coleccion intermediaria, que hace de puente entre 1 o más colecciones.
- Embeber dentro de cada documento un arreglo con los identificadores de sus relaciones.

Casos de uso
Usar referencia cuando la relacion es N-N

Ejemplo:
Primera parte.

Un producto puede pertenecer a varias tiendas y una tienda puede tener varios productos. Lo realizaremos mediante un arreglo para referenciar.

Se utiliza una nomenclatura como cualquier otra propiedad pero con un doble corchete y de tipo ObjectId: products_ids[]:<ObjectId>.