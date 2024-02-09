Esta sección proporciona información sobre cómo Microsoft Dataverse, la plataforma de datos detrás de componentes de Acelerador Nonprofit, gestiona la seguridad, desde la autenticación del usuario hasta la autorización, que permite a los usuarios realizar acciones con datos y servicios. Conceptualmente, la seguridad en Dataverse sirve para garantizar que los usuarios pueden hacer el trabajo que deben con la cantidad mínima de fricción, al tiempo que se protegen los datos y servicios. La seguridad de Dataverse se puede implementar como modelo de seguridad sencilla con acceso amplio en todo momento a modelos de seguridad muy complejos en los que los usuarios tienen acceso específico a nivel de registro y campo.

A continuación, describiremos los elementos de seguridad que implementaremos.

# Unidades de negocio.
Las unidades de negocio brindan seguridad y estructura para agrupar usuarios y, a menudo, se utilizan para imitar la estructura departamental de una organización.

Todo usuario asignado a un entorno Dataverse pertenecerá a una unidad de negocio. La primera unidad de negocio creada para una organización se denomina unidad de negocio raíz.

Las unidades de negocio se pueden eliminar, pero no la unidad de negocio raíz. Se puede crear una jerarquía de unidades de negocio secundarias adicionales según sea necesario.

# Roles de seguridad.
Dataverse utiliza seguridad basada en roles para agrupar una colección de privilegios. Estos roles de seguridad se pueden asociar directamente a los usuarios o se pueden asociar con equipos y unidades de negocios de Dataverse. Luego, los usuarios pueden asociarse con el equipo y, por lo tanto, todos los usuarios asociados con el equipo se beneficiarán del rol.

Un concepto clave de seguridad de Dataverse que se debe comprender es que los privilegios se acumulan y los mayores privilegios de acceso se aplican a un usuario con múltiples roles de seguridad. Por ejemplo, si un usuario tiene dos roles de seguridad, uno con privilegios de eliminación pero sin privilegios de escritura y el otro con privilegios de escritura pero sin privilegios de eliminación, el usuario podrá leer y escribir en el entorno.

# Seguridad a nivel de columna para controlar el acceso.
Los permisos a nivel de columna se otorgan a nivel de tabla, pero es posible que tenga ciertas columnas asociadas con una tabla que contenga datos que sean más confidenciales que las otras columnas. Para estas situaciones, se utiliza la seguridad a nivel de columna para controlar el acceso a columnas específicas.

La seguridad a nivel de columna está disponible para las columnas predeterminadas en la mayoría de las tablas listas para usar, columnas personalizadas y columnas personalizadas en tablas personalizadas. La seguridad a nivel de columna la gestionan los perfiles de seguridad.