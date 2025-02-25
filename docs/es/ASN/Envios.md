# Envíos 

**Descripción general**

El apartado Envíos está diseñado para gestionar y monitorear los envíos dentro del sistema. Incluye dos vistas principales: Pendientes y Enviados, permitiendo un control claro y estructurado del estado de cada envío.

**Funcionalidades principales**

## Vistas Disponibles

- Pendientes: Muestra un listado de envíos que aún no han sido procesados ​​o enviados.

- Enviados: Presenta un listado con los envíos que ya han sido gestionados y marcados como enviados.

## Navegación entre vistas

Los usuarios pueden cambiar entre las pestañas Pendientes y Enviados para visualizar los elementos correspondientes a cada estado.

## Pendiente

Listado de Envíos Pendientes:

- Se presenta un listado de los envíos aún no procesados.

Cada fila incluye la siguiente información:

   - ID: Identificador único del envío.
   - Número de Envío: Código o número de referencia del envío.
   - Botones de acción:

        - Información: Proporciona detalles adicionales sobre el envío. Al pulsar, se abre un cuadro emergente o modal con información relevante.
        - Etiquetas: Genera y permite descargar etiquetas para el envío correspondiente.
        - Enviar: Cambia el estado del envío a "Enviado" y lo mueve automáticamente a la pestaña Enviados.
        - Borrar: Permite eliminar este envío. Se notificará a TKE de que el ASN debe ser borrado. Todos los paquetes incluidos en este envío volverán a aparecer en “Pendiente de Envío”. 

![image](images/imagendeWord.png)

## Enviados

Listado de Envíos Enviados:

Similar al listado de la pestaña Pendiente, pero muestra únicamente los envíos que ya han sido procesados ​​y enviados.

Cada fila incluye:

   - ID: Identificador ASN.
   - Número de Envío: Código o número de referencia del envío.
   - Fecha de envío.
   - Botones de acción:
        - Información: Proporciona detalles adicionales sobre el envío. Al pulsar, se abre un cuadro emergente o modal con información relevante.
        - Etiquetas: Genera y permite descargar etiquetas (de artículos, cajas, pallets y albarán) para el envío correspondiente.
        - Enviado: información del estado del envío.

Esta vista actúa como un registro de envíos completados, permitiéndole su consulta en cualquier momento.

![image](images/listEnvyEnvy.png)

## Preguntas frecuentes

<b>¿Qué información se muestra en el apartado de Envíos?</b>

El apartado de Envíos tiene dos pestañas principales:

Pendiente: Muestra los envíos que aún no han sido procesados, con la siguiente información:
Identificación del envío.
Número de Envío.
Botones de acción: Información, Etiquetas y Enviar .
Enviados: Muestra los envíos que ya han sido gestionados, con los mismos campos de información.

<b>¿Qué acciones puedo realizar desde la pestaña "Pendiente"?</b>

Desde la pestaña Pendiente, puedes:

Consultar información detallada del envío seleccionando el botón Información.
Generar etiquetas para los artículos y las cajas utilizando el botón Etiquetas.
Marcar un envío como completado y moverlo a la pestaña Enviados utilizando el botón Enviar.

<b>¿Cómo puedo ver un envío que ya ha sido procesado?</b>

Para consultar los envíos ya procesados:

Ve a la pestaña Enviados.
Busca el envío que necesitas.
Selecciona el envío para ver su información o generar etiquetas nuevamente.

<b>¿Qué hace el botón "Información"?</b>

El botón Información muestra detalles del ASN del envío seleccionado.

<b>¿Qué sucede al presionar el botón "Enviar" en la pestaña Pendiente?</b>

Al presionar el botón Enviar:

El estado del envío cambia de "Pendiente" a "Enviado".
El envío se mueve automáticamente de la pestaña Pendiente a la pestaña Enviados.
Este cambio asegura un registro claro de los envíos completados.

<b>¿Puedo generar etiquetas para envíos ya completados?</b>

Sí, desde la pestaña Enviados, puedes generar etiquetas nuevamente utilizando el botón Etiquetas asociadas a cada envío.

<b>¿Qué diferencia hay entre las pestañas "Pendiente" y "Enviados"?</b>

Pendiente: Contiene envíos que aún no han sido procesados ​​o completados. Estos pueden ser gestionados con acciones como enviar y generar etiquetas.

Enviados: Contiene los envíos que ya han sido procesados ​​y marcados como completados. Aquí solo se pueden consultar los detalles o generar etiquetas nuevamente.