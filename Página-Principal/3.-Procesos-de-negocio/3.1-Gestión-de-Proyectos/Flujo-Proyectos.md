[[_TOC_]]

Para la gestión de los proyectos, se utilizará el flujo estándar de oportunidad que ofrece Dynamics 365, con las personalizaciones necesarias para adaptarlo al proceso actual de Inserta.

Este flujo puede iniciarse al dar de alta un nuevo cliente potencial, o bien crear una nueva oportunidad con una cuenta existente en el sistema.

## **Desde cliente potencial**

Para empezar el flujo desde el cliente potencial, primero se tendrá que contar con el cliente potencial al que queremos generar una oportunidad, o bien dar uno nuevo de alta.

Para generar un nuevo cliente potencial, desde la vista principal de clientes potenciales, utilizaremos el botón “Nuevo”, esto nos abrirá un formulario de cliente potencial donde debemos informar los datos antes de continuar.

![1.png](/.attachments/1-a0535456-cbe1-45ec-a309-6bf8d8445600.png)

Una vez verificados todos los datos, haremos clic en "Calificar" para generar la oportunidad. Es fundamental asegurarse de que el lead no provenga de un cliente o financiador existente. Si este es el caso, antes de calificar el lead, debemos indicar a qué cliente está relacionado en el formulario correspondiente.

![image.png](/.attachments/image-1f24e968-6c6e-4249-a07d-bccd730bfab2.png)

![2.png](/.attachments/2-ad7ee483-f5a5-4b38-ba85-e30d74608b29.png)

Al calificar el cliente potencial, se abrirá una nueva oportunidad vinculada a una nueva cuenta, a menos que se haya especificado un cliente existente en el formulario del lead. En ese momento, será necesario indicar el tipo de oportunidad, que en este caso será "Proyecto", y también el "Asunto" y "Plazo presentación" correspondiente.

![image.png](/.attachments/image-f32390bc-96b0-4866-bee6-378d1cd341be.png)

Una vez que guardemos la información, al tratarse de una oportunidad de tipo "Proyecto", se habilitará y mostrará un proceso de negocio personalizado para Inserta, con las respectivas etapas definidas. Cabe destacar que este proceso de negocio solo se muestra para oportunidades de este tipo.

![image.png](/.attachments/image-585db29f-66e1-483c-93ef-c667ac1e475b.png)

En este punto, se puede subir la documentación necesaria en la pestaña "Documentos" de la oportunidad, la cual está vinculada a un repositorio de SharePoint para la gestión documental. Una vez se hayan subido todos los documentos e informado todos los campos requeridos en la etapa de Inicio, incluido el campo "Evaluar idoneidad" marcado como "Sí", pasaremos a la siguiente etapa: Decisión.

De este modo, por un lado, actualizamos la fase de la oportunidad a "Decisión", etapa en la que Francisco revisará la oportunidad y por otro lado, al marcar "Sí" en el campo "Evaluar idoneidad", se enviará un correo electrónico a Francisco con el enlace a la oportunidad para su revisión.

![image.png](/.attachments/image-a7872d0d-2897-4fed-aa25-cd13415d6342.png)

Una vez que Francisco haya revisado la oportunidad, deberá completar los campos "Situación actual", "Necesidad del cliente", "Solución propuesta" y "Decidir si proceder o no proceder". En caso de ser favorable a la creación del presupuesto, el campo "Decidir si proceder o no proceder" deberá marcarse como "Sí". Como en la fase de Inicio, Francisco deberá llenar estos campos y avanzar el proceso a la fase de Gestión.

De este modo, se actualizará la fase de la oportunidad a "Gestión", etapa en la que el equipo técnico creará el presupuesto. Además, al marcar "Sí" en el campo "Decidir si proceder o no proceder", se enviará un correo electrónico al equipo técnico designado, informándoles que pueden comenzar a generar el presupuesto y subir la documentación necesaria.

![image.png](/.attachments/image-d29c79ea-b232-4995-af64-492a41310732.png)

NOTA: Los campos también se encuentran en el formulario

Para elaborar la propuesta, el equipo técnico tendrá que generar una oferta, desde la pestaña “Ofertas” en el formulario de la oportunidad, se verá una vista con las ofertas generadas. Para generar la primera oferta, haremos clic en “Crear Oferta”.

![5.png](/.attachments/5-b6c71ba4-3274-48d1-9b1a-38c84738809d.png)

Esto nos llevará a un nuevo formulario de oferta. Dado que se trata de una oferta derivada de una oportunidad de tipo "Proyecto", los campos "Fecha de ejecución", "Fecha de inicio del proyecto", "Fecha de fin del proyecto" y "Condiciones de pago" serán obligatorios.

![6.png](/.attachments/6-0825bbb4-b1cd-4989-928d-6d84ddb4ad86.png)

Desde este formulario, en la vista de Productos de la oferta, podremos añadir los diferentes cargos para generar el presupuesto deseado. Para ello, hacemos clic en "Agregar producto".

![7.png](/.attachments/7-e590430e-5a8b-4721-b873-e6b02ed5e6bc.png)

Esto abrirá un formulario para agregar los productos, en este caso de tipo "cargo", a la oferta. En este formulario, deberemos seleccionar el cargo que se desea añadir y configurar tanto el precio unitario como la cantidad a incorporar, ya que, dependiendo del proyecto, los cargos pueden tener importes variables.

NOTA: Para crear nuevos cargos ir a [3.6 Gestión de productos](/Página-Principal/3.-Procesos-de-negocio/3.6-Gestión-de-productos)

![8.png](/.attachments/8-052eeaab-f769-43ee-be61-dd4e0c273da8.png)

Una vez que esté correctamente configurado, hacemos clic en "Guardar" para añadir el nuevo cargo a la oferta. Repetiremos este proceso hasta que hayamos agregado todos los cargos deseados a la oferta. Luego, procedemos a activar la oferta haciendo clic en "Activar". Esta acción bloqueará la oferta para que no se pueda modificar, asegurando así la coherencia de los datos que se presentarán al cliente.

![9.png](/.attachments/9-eb86182d-0b7d-458c-b90b-c2b736166d44.png)

Si es necesario generar nuevas versiones de la oferta, no se creará una nueva oferta desde cero como en el primer caso. En su lugar, dentro de la última oferta editada, hacemos clic en el botón "Revisar". Esto generará una nueva oferta con los datos de la anterior, sobre la cual realizaremos las modificaciones necesarias. La oferta que hemos descartado se inactivará automáticamente. De esta manera, mantenemos un seguimiento claro de los entregables y cambios realizados en los presupuestos para una misma oportunidad.

![10.png](/.attachments/10-a2e07c05-335c-4408-b6df-5e30d032e534.png)

**Cuando se establece el % de subvención aceptada, se deberá adaptar el presupuesto, que se realizará también mediante el botón “Revisar” de la oferta.**

Por último, se han implementado dos proceso automatizado de notificación por correo electrónico, cuyo periodo de aviso está parametrizado para que pueda ajustarse en el futuro si es necesario, actualmente establecido en 2 meses y 1 mes respectivamente. El primer proceso informará al equipo de proyectos y administración sobre la fecha de finalización de la ejecución y el nombre del proyecto, lo que les brindará tiempo suficiente para revisar los objetivos a cumplir, el presupuesto y otros aspectos relevantes. Este enfoque está especialmente dirigido a la fase de revisión final del proyecto. 
NOTA: El campo parametrizado se encuentra en la entidad "Parámetros de Aplicación"

![1.png](/.attachments/1-94e3e383-a538-4adc-88a5-9d06f2ac8fc5.png)

El segundo proceso enviará una notificación cuando quede 1 mes para cumplir la fecha de justificación del proyecto.

NOTA: El campo parametrizado se encuentra en la entidad "Parámetros de Aplicación"

![2.png](/.attachments/2-4876fcdf-6333-4c88-8c60-2781dfa579c3.png)

## **Desde cuenta**
Para dar de alta una nueva oportunidad asociada a una cuenta que ya tenemos dada de alta, podremos hacerlo desde la propia cuenta a la que queremos generar la oportunidad, o desde el panel de oportunidades.

Desde el formulario de la cuenta, vamos a la pestaña “Oportunidades”, esto nos mostrará una vista con las oportunidades relacionadas a la cuenta. 

Para crear una nueva oportunidad, hacemos clic en “Crear Oportunidad”, de esta manera generaremos una nueva oportunidad relacionada a la cuenta.

![8.png](/.attachments/8-500abaeb-73a4-401e-989b-46ac201be984.png)

![image.png](/.attachments/image-43864111-68ac-49af-9571-0a69592bad7b.png)

Para hacerlo desde el panel general de oportunidades, hacemos clic en "Nuevo". Esto abrirá un formulario de oportunidad en el que tendremos que completar la información requerida, como la cuenta a la que queremos relacionar la nueva oportunidad, junto con los campos "Tipo de oportunidad", "Asunto" y "Plazo presentación".

![9.png](/.attachments/9-0210d476-e09c-42b1-bac2-3f60b95c464c.png)

Una vez hemos generado la oportunidad, continuaremos con el proceso de la misma manera que al calificar el cliente potencial

## Trazabilidad estado de las fases del proyecto

Desde Inserta, surgió la necesidad de visualizar los tiempos en los que se encuentra cada una de las fases del proyecto. Para abordar esto, se ha implementado una tabla en el formulario de oportunidad que automáticamente registra el inicio y fin de cada etapa. Esto permite analizar posteriormente, o incluso durante el proceso, los tiempos dedicados a cada fase del proyecto.

![image.png](/.attachments/image-489dd334-e885-49b1-970f-c68b74cf1e71.png)

