[[_TOC_]]

Para la gestión de los proyectos, se utilizará el flujo estándar de oportunidad que ofrece Dynamics 365, con las personalizaciones necesarias para adaptarlo al proceso actual de Inserta.

Este flujo puede iniciarse al dar de alta un nuevo cliente potencial, o bien crear una nueva oportunidad con una cuenta existente en el sistema.

## **Desde cliente potencial**
Para empezar el flujo desde el cliente potencial, primero se tendrá que contar con el cliente potencial al que queremos generar una oportunidad, o bien dar uno nuevo de alta.

Para generar un nuevo cliente potencial, desde la vista principal de clientes potenciales, utilizaremos el botón “Nuevo”, esto nos abrirá un formulario de cliente potencial donde debemos informar los datos antes de continuar.

![1.png](/.attachments/1-a0535456-cbe1-45ec-a309-6bf8d8445600.png)

Una vez verificados todos los datos, haremos clic en "Calificar" para generar la oportunidad. Es fundamental asegurarse de que el lead no provenga de un cliente o financiador existente. Si este es el caso, antes de calificar el lead, debemos indicar a qué cliente está relacionado en el formulario correspondiente.

![2.png](/.attachments/2-ad7ee483-f5a5-4b38-ba85-e30d74608b29.png)


Al calificar el cliente potencial, se abrirá una nueva oportunidad vinculada a una nueva cuenta, a menos que se haya especificado un cliente existente en el formulario del lead. En ese momento, será necesario indicar el tipo de oportunidad, que en este caso será "Proyecto", y también el "tema" y "Plazo de presentación" correspondiente.

![3.png](/.attachments/3-101798c1-f403-4d6a-b58d-68882475e6dc.png)

Una vez que guardemos la información, al tratarse de una oportunidad de tipo "Proyecto", se habilitará y mostrará un proceso de negocio personalizado para Inserta, con las respectivas etapas definidas. Cabe destacar que este proceso de negocio solo se muestra para oportunidades de este tipo.

![image.png](/.attachments/image-585db29f-66e1-483c-93ef-c667ac1e475b.png)

En este punto, se puede subir la documentación necesaria en la pestaña "Documentos" de la oportunidad, la cual está vinculada a un repositorio de SharePoint para la gestión documental. Una vez se hayan subido todos los documentos e informado todos los campos requeridos en la etapa de Inicio, incluido el campo "Evaluar idoneidad" marcado como "Sí", pasaremos a la siguiente etapa: Decisión.

De este modo, por un lado, actualizamos la fase de la oportunidad a "Decisión", etapa en la que Francisco revisará la oportunidad y por otro lado, al marcar "Sí" en el campo "Evaluar idoneidad", se enviará un correo electrónico a Francisco con el enlace a la oportunidad para su revisión.

![image.png](/.attachments/image-9567df9c-8f5b-42ac-b6cd-6d2a1ac9c24d.png)

Una vez que Francisco haya revisado la oportunidad, deberá completar los campos "Situación actual", "Necesidad del cliente", "Solución propuesta" y "Decidir si proceder o no proceder". En caso de ser favorable a la creación del presupuesto, el campo "Decidir si proceder o no proceder" deberá marcarse como "Sí". Como en la fase de Inicio, Francisco deberá llenar estos campos y avanzar el proceso a la fase de Gestión.

De este modo, se actualizará la fase de la oportunidad a "Gestión", etapa en la que el equipo técnico creará el presupuesto. Además, al marcar "Sí" en el campo "Decidir si proceder o no proceder", se enviará un correo electrónico al equipo técnico designado, informándoles que pueden comenzar a generar el presupuesto y subir la documentación necesaria.

![image.png](/.attachments/image-d29c79ea-b232-4995-af64-492a41310732.png)

![4.png](/.attachments/4-1357d14f-181a-4c2c-86ab-fd4a800ff5ab.png)

Para elaborar la propuesta, el equipo técnico tendrá que generar una oferta, desde la pestaña “Ofertas” en el formulario de la oportunidad, se verá una vista con las ofertas generadas. Para generar la primera oferta, haremos clic en “Crear Oferta”.

![5.png](/.attachments/5-b6c71ba4-3274-48d1-9b1a-38c84738809d.png)

Esto nos dirigirá a un nuevo formulario de oferta. En primer lugar, al ser una oferta proveniente de una oportunidad de tipo proyecto, los campos de "Fecha de ejecución", "Fecha de inicio de proyecto" y "Fecha fin del proyecto", serán obligatorios.

![6.png](/.attachments/6-0825bbb4-b1cd-4989-928d-6d84ddb4ad86.png)

Desde este formulario, en la vista de Productos de la oferta, podremos añadir los diferentes cargos para generar el presupuesto deseado. Para ello, hacemos clic en "Agregar producto".

![7.png](/.attachments/7-e590430e-5a8b-4721-b873-e6b02ed5e6bc.png)

Esto abrirá un formulario para la creación del nuevo cargo de la oferta, en el que tendremos que elegir el cargo que se quiere añadir y configurar el precio unitario y cantidad a incorporar.

![8.png](/.attachments/8-052eeaab-f769-43ee-be61-dd4e0c273da8.png)

Una vez está correctamente configurado, hacemos clic en "Guardar" y se añadirá el nuevo cargo a la oferta. Repetiremos este proceso hasta que hayamos agregado todos los cargos que deseamos a la oferta, entonces pasamos a activar la oferta haciendo clic en “Activar”.

![9.png](/.attachments/9-eb86182d-0b7d-458c-b90b-c2b736166d44.png)

Si es necesario realizar nuevas versiones de la oferta, no se creará una nueva oferta tal y como se hace la primera. Para estos casos, dentro de la última oferta que hemos editado hacemos clic en el botón “Revisar”. Esto generará una nueva oferta con los datos de la anterior sobre la que haremos las modificaciones necesarias y, la oferta que hemos desechado se inactivará.

![10.png](/.attachments/10-a2e07c05-335c-4408-b6df-5e30d032e534.png)

Cuando se establece el % de subvención aceptada, se deberá adaptar el presupuesto, que se realizará también mediante el botón “Revisar” de la oferta.

## **Desde cuenta**
Para dar de alta una nueva oportunidad asociada a una cuenta que ya tenemos dada de alta, podremos hacerlo desde la propia cuenta a la que queremos generar la oportunidad, o desde el panel de oportunidades.

Desde el formulario de la cuenta, vamos a la pestaña “Oportunidades”, esto nos mostrará una vista con las oportunidades relacionadas a la cuenta. 

Para crear una nueva oportunidad, hacemos clic en “Crear Oportunidad”, de esta manera generaremos una nueva oportunidad relacionada a la cuenta.

![8.png](/.attachments/8-500abaeb-73a4-401e-989b-46ac201be984.png)

Para hacerlo desde el panel general de oportunidades, hacemos clic en “Nuevo”, esto abrirá un formulario de oportunidad, donde tendremos que informar la cuenta a la que queremos relacionar la nueva oportunidad.

![9.png](/.attachments/9-0210d476-e09c-42b1-bac2-3f60b95c464c.png)

Una vez hemos generado la oportunidad, continuaremos con el proceso de la misma manera que al calificar el cliente potencial

