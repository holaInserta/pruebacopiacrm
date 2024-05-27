[[_TOC_]]


Para la gestión de las formaciones, se utilizará el flujo estándar de oportunidad que ofrece Dynamics 365, con las personalizaciones necesarias para adaptarlo al proceso actual de Inserta.

Este flujo puede iniciarse al dar de alta un nuevo cliente potencial, o bien crear una nueva oportunidad con una cuenta existente en el sistema.

## **Desde cliente potencial**
Para empezar el flujo desde el cliente potencial, primero se tendrá que contar con el cliente potencial al que queremos generar una oportunidad, o bien dar uno nuevo de alta.

Para generar un nuevo cliente potencial, desde la vista principal de clientes potenciales, utilizaremos el botón “Nuevo”, esto nos abrirá un formulario de cliente potencial donde debemos informar los datos antes de continuar.

![1.png](/.attachments/1-091268bb-6890-4c9b-8a08-7492f31d477f.png)

Una vez verificados todos los datos, haremos clic en "Calificar" para generar la oportunidad. Es fundamental asegurarse de que el lead no provenga de un cliente o financiador existente. Si este es el caso, antes de calificar el lead, debemos indicar a qué cliente está relacionado en el formulario correspondiente.

![2.png](/.attachments/2-d0a47773-5a02-4ee4-a700-e8b52ea4698f.png)

Al calificar el cliente potencial, se abrirá una nueva oportunidad vinculada a una nueva cuenta, a menos que se haya especificado un cliente existente en el formulario del lead. En ese momento, será necesario indicar el tipo de oportunidad, que en este caso será "Formación", y también el "tema" correspondiente.

![3.png](/.attachments/3-65872613-fa7c-4fb9-890b-6ee39204903e.png)

Una vez completada la información general de la oportunidad, podemos elaborar la propuesta. Para ello, tendremos que generar una oferta, desde la pestaña “Ofertas” en el formulario de la oportunidad, se verá una vista con las ofertas generadas. Para generar la primera oferta, haremos clic en “Crear Oferta”.

![4.png](/.attachments/4-8950ee2e-f82f-4442-978e-8da2646adf4b.png)

Esto nos dirigirá a un nuevo formulario de oferta en el podremos añadir las diferentes formaciones con las que generar la propuesta.

Desde este formulario, en la vista de Productos de la oferta, podremos añadir las diferentes formaciones para generar el presupuesto deseado. Para ello, hacemos clic en "Agregar producto".

![5.png](/.attachments/5-344d228f-4a54-4fec-a7a7-37295fc316f7.png)

Esto abrirá un formulario para agregar los productos, en este caso de tipo "formación", a la oferta. En este formulario, deberemos seleccionar la formación que se desea añadir y configurar tanto el precio unitario como la cantidad a incorporar, ya que, dependiendo de la oportunidad en la que nos encontremos, la formación o formaciones pueden tener importes variables.

NOTA: Para crear nuevas formaciones ir a [3.6 Gestión de cargos](/Página-Principal/3.-Procesos-de-negocio/3.6-Gestión-de-cargos)

![6.png](/.attachments/6-54c3847d-8440-422f-bfa2-433b71d3dd94.png)

Para poder buscar más fácilmente productos que sean únicamente formaciones, en el campo de "Producto existente", hacemos clic en "Búsqueda" (Icono de la lupa) y luego en "Búsqueda avanzada"

![7.png](/.attachments/7-a679b604-1cb8-4c3d-a542-1dc0da544b52.png)

Esto nos abrirá una ventana en la que podremos elegir entre distintas vistas sobre las que queremos buscar al formación. Una vez elegida la deseada, hacemos clic en listo y se agregará al formulario.

![8.png](/.attachments/8-79f97f91-e6ec-4be3-999b-b6c45cd57f71.png)

Una vez que esté correctamente configurado, hacemos clic en "Guardar" para añadir la nueva formación a la oferta. Repetiremos este proceso hasta que hayamos agregado todas las formaciones deseadas a la oferta. Luego, procedemos a activar la oferta haciendo clic en "Activar". Esta acción bloqueará la oferta para que no se pueda modificar, asegurando así la coherencia de los datos que se presentarán al cliente.

![9.png](/.attachments/9-68727fc0-1e66-4d2e-a6d2-372fdb0c8279.png)

Si es necesario generar nuevas versiones de la oferta, no se creará una nueva oferta desde cero como en el primer caso. En su lugar, dentro de la última oferta editada, hacemos clic en el botón "Revisar". Esto generará una nueva oferta con los datos de la anterior, sobre la cual realizaremos las modificaciones necesarias. La oferta que hemos descartado se inactivará automáticamente. De esta manera, mantenemos un seguimiento claro de los entregables y cambios realizados en los presupuestos para una misma oportunidad.

![10.png](/.attachments/10-b4256f6d-ad26-4463-ba1a-a4504761c167.png)

## **Desde cuenta**

Para dar de alta una nueva oportunidad asociada a una cuenta existente, podemos hacerlo desde la propia cuenta o desde el panel de oportunidades.

Desde el formulario de la cuenta, accedemos a la pestaña “Oportunidades”, donde veremos una lista de las oportunidades relacionadas con esa cuenta.

Para crear una nueva oportunidad, simplemente hacemos clic en “Crear Oportunidad”, lo que generará una nueva oportunidad asociada a la cuenta seleccionada.

![8.png](/.attachments/8-500abaeb-73a4-401e-989b-46ac201be984.png)

Para hacerlo desde el panel general de oportunidades, hacemos clic en "Nuevo". Esto abrirá un formulario de oportunidad en el que tendremos que completar la información requerida, como la cuenta a la que queremos relacionar la nueva oportunidad, junto con los campos "Tipo de oportunidad" y "Tema".

![9.png](/.attachments/9-0210d476-e09c-42b1-bac2-3f60b95c464c.png)

Una vez hemos generado la oportunidad, continuaremos con el proceso de la misma manera que al calificar el cliente potencial.
Al ganar la oportunidad de tipo "Formación", se generará automáticamente un evento en el sistema para su gestión y configuración posterior.
NOTA: Revisar el apartado [3.5 Gestión de eventos](/Página-Principal/3.-Procesos-de-negocio/3.5-Gestión-de-eventos)



