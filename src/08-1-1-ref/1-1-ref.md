# Relaciones 1 a 1 referenciadas

Este se usa cuando se superan las restricciones, como pueden ser:

- Peso maximo de 16MB: Esto podria pasar si se llena con muchas propiedades y/o muy pesadas, como pueden ser binarios, imagenes, videos, etc.
- Consultas lentas: Al realizar una peticion, puede que se procese informacion innecesaria (Se puede superar con restringir las propiedades que se entregaran) o muy pesada.
- Se requieran acelerar ciertas consultas: Puede que se requieran hacer consultas que requieran mucha velocidad para grandes cantidad de documentos y dejemos apartado los detalles que no se requiren para esas consultas. Como puede ser en productos y el detalle de esos productos.

