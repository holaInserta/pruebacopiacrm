La entidad de Producto es la que se utilizará para definir todo tipo de cargos que se añadirán en los presupuestos.
Cada producto definirá un cargo específico. Para crear uno nuevo, tendremos que ir a productos y hacer clic en "Agregar producto", esto nos llevará a un formulario en el que tendremos que completar los siguientes datos:

- **Nombre:** Es el nombre que recibirá el cargo
- **Id. de producto:** Es el identificador único que recibe el cargo
- **Tipo de producto:** Indica el tipo de producto que se creará
- **Unidad de venta:** Indica la unidad de venta del producto. Por defecto, este campo se establecerá con el valor "Unidad predeterminada", pero puede cambiarse eligiendo cualquier otro de la lista de búsqueda
- **Unidad predeterminada:** Es la unidad predeterminada que se utilizará para este cargo. Por defecto, este campo se establecerá con el valor "Unidad principal". En el caso de haber elegido una unidad de venta diferente a la establecida por defecto, el valor de este campo se borrará y será necesario elegir otro
- **Decimales admitidos:** Indica el número de decimales que podrá tener el precio del cargo. Por defecto, se informa a "2" para permitir los decimales estandarizados, pero puede ser modificado por otro valor entero
- **Lista de precios predeterminada:** Indica la lista de precios utilizada para este cargo. Por defecto, se creará con el valor "PVP Inserta", pero puede cambiarse por otra lista de precios definida

Una vez informados estos campos, hacemos clic en Guardar y se creará el cargo. Para poder utilizar correctamente este cargo, será necesario definir el comportamiento de los precios.
Para ello, en el producto que hemos creado, vamos a la pestaña de "Detalles adicionales" y, en la vista de "Elementos de lista de precios", hacemos clic en "Crear elemento de lista de precios"

![5.png](/.attachments/5-354df901-1719-4f16-8c26-1d32c103bcab.png)

Se abrirá una ventana en la que se tiene que informar la lista de precios para la que se quiere configurar el nuevo elemento y, en la pestaña "Información de precios", se tendrá que indicar el precio predeterminado del cargo. El precio predeterminado puede ser 0, ya que una vez se añada el cargo en la oferta, se podrá modificar el importe para dicho cargo en el oferta que se vaya a utilizar.

![3.png](/.attachments/3-e2cf442c-4bff-44d2-8e2c-22dfd9cb58c5.png)

![4.png](/.attachments/4-46059ee6-e433-4bca-8e9b-25ed093f290a.png)

Una vez hecho esto, el producto ya podrá ser utilizado en la configuración de los presupuestos a través de las oportunidades.
