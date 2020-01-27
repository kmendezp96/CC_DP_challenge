# Best Practices and Design Patterns Workshop
## Descripción:
se maneja el sistema de una tienda con una serie de tipos de productos en catálogo. Cada producto tiene sus respectivos datos (nombre, precio, cantidad y una lista de cada item como tal, es decir, el tamaño de la lista y la cantidad es el mismo). toda tienda por obligación deben vender galletas y leche, más las galletas pueden ser galletas de chocolate y vainilla aunque puede agregar las que usted crea necesarias para el negocio. Igualmente la leche puede ser de vainilla o de chocolate, nuevamente puede agregar nuevos tipos.
El cliente sólo puede comprar un producto a la vez y tiene acceso al historial de todas las compras que ha hecho en la tienda
Actualmente el cliente en su factura solo puede ver el id del item que compro, mas no puede ver ni el nombre ni el precio del producto, la solución planteada debe permitir que el cliente de algún modo almacene esa información.

## Requerimientos:
- Usar al menos dos patrones distintos.
- En la clase Main no debería haber métodos adicionales a main.
- En el método main no debería haber llamados a constructores de productos directamente, ni tampoco debería pedir atributos de los productos a excepción de posiblemente la cantidad.
- 5 empleados.
- 10 clientes que pediran distintos productos en distinta cantidad.
- Vender debe ser una acción de un empleado y no de la tienda.
- Añadir al menos otro tipo de leche y/o galleta.
- Añadir otro tipo nuevo de producto (al mismo nivel de milk o cookie).
- Deben haber al menos 30 transacciones.
- Al final el programa para cada cliente debe imprimir su historial de compras con el id de item que compró, el nombre y el precio del producto.
- Commits progresivos, no todo puede ir en un mismo commit.

## Opcionales:
- Añadir la posibilidad de que un cliente compre múltiples productos en una sola transacción, en este caso el programa no imprimirá al final el historial de compras sino solo el último recibo (con id del item, nombre, precio).
- Usar un patrón diferente a los incluidos en la presentación.
- Añadir javadocs.
