## Relación entre `Proveedor` e `Insumo` (N:M)
 
 Para representar la relación muchos a muchos entre los proveedores y los insumos, se implementa una tabla intermedia:
 
 ### Tabla intermedia: `ProveedorxInsumo`
 
 | Atributo              | Descripción                                                                                    |
 |-----------------------|------------------------------------------------------------------------------------------------|
 | ID\_PROVEEDOR         | Clave foránea que referencia a `Proveedor`                                                     |
 | ID\_INSUMO            | Clave foránea que referencia a `Insumo`                                                        |
 | PRECIO_REFERENCIAL    | Base de comparación de precios para decisiones de compra y negociación con los proveedores.    |
 
 ### ¿Por qué?
 
 - Para un mismo proveedor, este puede ofrecer mas de un insumo del mismo tipo a la empresa para abastecer su almacén.
 - Un mismo insumo puede provenir de diferentes proveedores cuando s.
 - La tabla intermedia permite asociar el precio de un insumo con su proveedor, lo cual es esencial para la selección de los proveedores al momento de realizar la planificación de una compra.
