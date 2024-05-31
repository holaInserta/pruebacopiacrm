En Dynamics 365 Sales, hemos desarrollado cuatro comunicaciones automatizadas vía email para optimizar el flujo de proyectos. Estos procesos utilizan plantillas de correo electrónico preconfiguradas, lo que permite realizar cambios futuros en la comunicación simplemente modificando el contenido de las plantillas, sin necesidad de alterar el proceso en sí. Esto proporciona un flujo escalable y autónomo para Inserta.

Para acceder a las plantillas, dirígete a la pestaña "Configuración personal" ubicada en la parte inferior del menú lateral izquierdo y selecciona "Plantillas de correo electrónico". Utiliza la vista "All Language Email Templates" para gestionar las plantillas.

![image.png](/.attachments/image-36f8b071-460b-4565-83f7-df6956f24d3e.png)

Las plantillas configuradas son las siguientes:

# Para la entidad Oportunidad:

**Inserta - Fase 2**
- Descripción: Se envía un correo a Francisco para la revisión de la oportunidad.

![image.png](/.attachments/image-25fb1114-b4b2-425e-aff0-6f1ca2914926.png)

Es importante conservar la configuración del vinculo del registro, para esto la configuración del protocolo será **Otro** y el valor de url será **[[urlRecord]]** como se observa en la imagen.
![image.png](/.attachments/image-0e3c39a4-135c-42d3-8832-9246a7b0db96.png)


**Inserta - Fase 3**

- Descripción: Se envía un correo al equipo técnico para que generen el presupuesto.

![image.png](/.attachments/image-3b022392-db64-4eb3-bd96-0f0a5632477b.png)

Es importante conservar la configuración del vinculo del registro, para esto la configuración del protocolo será **Otro** y el valor de url será **[[urlRecord]]** como se observa en la imagen.
![image.png](/.attachments/image-0e3c39a4-135c-42d3-8832-9246a7b0db96.png)

# Para la entidad Oferta:

**Inserta - Fecha fin del proyecto**

- Descripción: Se envía un correo informativo sobre la fecha fin del proyecto, basado en los días configurados en la entidad "Parámetros de Aplicación".

![image.png](/.attachments/image-3e991188-744c-4017-86cd-81a58fc570d5.png)

Adicional al tema del vinculo, es importante mantener las variables @diasFin para el asunto y cuerpo de la plantilla, este valor se busca por los procesos automáticos de generación de correo electrónico para reemplazar el valor por el cálculado.

**Inserta - Fecha de justificación**

- Descripción: Se envía un correo informativo sobre la fecha de justificación, basado en los días configurados en la entidad "Parámetros de Aplicación".

![image.png](/.attachments/image-7547f513-b3fe-4b2c-83fc-56b50c487971.png)

Adicional al tema del vinculo, es importante mantener las variables @diasJustificacion para el asunto y cuerpo de la plantilla, este valor se busca por los procesos automáticos de generación de correo electrónico para reemplazar el valor por el cálculado.

Estas configuraciones aseguran que el flujo de trabajo se mantenga eficiente y actualizado con facilidad, mejorando así la comunicación y gestión de proyectos en Inserta.