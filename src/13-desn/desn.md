# Desnormalizacion

Es el proceso de optimizar el funcionamiento de una BD agregando datos redundantes.

- Esto es hacer duplicidad de datos y agregar direcciones no essenciales para acelerar las consultas o reducir la cantidad.

- Esta mal visto la duplicidad de datos en una base de datos relacional, pero en una base de datos documental puede ser un aliado. Porque nos ahorramos consultas o aceleramos esas mismas consultas por tener indexacion.

- Tambien permite mantener datos historicos, datos que no queremos que cambien en una instancia, aunque tengan cambios sus origines.

- Reduce los Join y simplifica las consultas.

Ejemplo

Tenemos una coleccion ‘order’ que esta desnormalizada, donde se hace embeding a los productos como items. Estos tendran la referencia sus productos correspondientes (product_id), datos extra como la cantidad (qty) y datos que pueden o no ser actualizados por ser una instancia de la orden (title, price) y que se quieran acceder rapidamente.