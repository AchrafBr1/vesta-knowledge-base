# Configuración de Vaelsys con paneles VESTA

## **Índice de Contenidos**

&#x20;1.- Resumen de la integración

2.- Configuración previa

3.- Alta de dispositivos Vesta

4.- Sincronización de estados de armado de áreas

5.- Activación de escenas



***



En el siguiente documento se explican los pasos a seguir para configurar dispositivos de Vesta en el sistema Vaelsys V4.

## &#x20;1.- Resumen de la integración

&#x20;El sistema Vaelsys V4 se puede integrar con cualquier panel Vesta. A través de la comunicación con el panel, se establecen dos líneas de comunicación:

&#x20;●       Sincronización de los estados de armado de las áreas de Vesta: El sistema VaelsysV4 mantiene una sincronización continua del estado de armado de las diferentes zonas del panel Vesta. De esta forma, se pueden tomar acciones cuando una zona del panel se arma o desarma, lo que permite, por ejemplo, armar el sistema de videoanálisis de forma sincronizada a través del panel.

&#x20;●       Activación de escenas a partir de eventos de videoanálisis: A través del sistema de avisos de VaelsysV4 es posible notificar al panel para la activación de una escena de forma sincronizada con un evento de videoanálisis. También se ha añadido en este aspecto una acción especial “VAELSYS” para las escenas así como **50 zonas reservadas (700-749)** con el fin de que puedan notificarse eventos de videoanálisis a través del panel Vesta.

## 2.- Configuración previa <a href="#qq1nvl3yy120" id="qq1nvl3yy120"></a>

La comunicación con el panel Vesta se realiza a través de conexión directa TCP/IP, por lo es necesario que antes de dar de alta un dispositivo Vesta en un videoanálisis VaelsysV4 el panel esté operativo y disponible a través de red local para que el sistema de videoanálisis pueda comunicarse correctamente con él.

&#x20;Para el proceso de alta deberán conocerse también los siguientes datos sobre el panel:

&#x20;●       Host y puerto donde está disponible el panel. Es el mismo host y puerto donde está disponible la interfaz web de configuración del panel.

&#x20;●       Usuario y contraseña de acceso al panel. Son las mismas credenciales utilizadas para acceder a la interfaz web de configuración del panel.

●       Dirección MAC del dispositivo.

&#x20;

{% hint style="info" %}
Es necesario haber accedido a la web del dispositivo Vesta al menos una vez y haber cambiado la contraseña que viene por defecto. **Si no se hace, el** **dispositivo Vesta cortará las conexiones después de aproximadamente una hora de haberse encendido.**
{% endhint %}

&#x20;

{% hint style="info" %}
La conexión directa con dispositivos Vesta depende de su versión de firmware. **No actualice el firmware de su dispositivo Vesta sin consultar previamente** la compatibilidad con equipos Vaelsys.
{% endhint %}

## &#x20;3.- Alta de dispositivos Vesta

En el apartado de configuración del equipo de videoanálisis podrá encontrar un apartado “Vesta” que contiene todas las herramientas necesarias para añadir, borrar y gestionar paneles Vesta.

Para añadir un nuevo panel, diríjase a la pestaña de “Dispositivos” y haga clic en el botón “Añadir”:

<figure><img src=".gitbook/assets/image (32).png" alt=""><figcaption><p>Conexión on el panel VESTA</p></figcaption></figure>

{% hint style="info" %}
En el campo **host** es posible especificar la dirección del panel con un hostname. Tenga en cuenta la configuración del DNS del dispositivo para su uso.
{% endhint %}

&#x20;

> En el caso de necesitar personalizar el puerto de conexión, puede especificarse en el campo host a continuación del host del dispositivo haciendo uso del carácter “:”.
>
> <img src=".gitbook/assets/image (33).png" alt="" data-size="original">

Si la conexión ha sido satisfactoria, el dispositivo aparecerá en la tabla de dispositivos como disponible, indicando el firmware detectado del panel:

<figure><img src=".gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

En el caso de haber habido algún error de configuración, el dispositivo se añadirá a la lista y aparecerá como erróneo. Al hacer clic en “Detalles” se puede obtener más información acerca de la causa del fallo:

<figure><img src=".gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

&#x20;En cualquier caso,, el dispositivo puede editarse haciendo clic en el botón de editar:

<figure><img src=".gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

O borrase haciendo clic en el botón de borrar:

<figure><img src=".gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

## 4.- Sincronización de estados de armado de áreas <a href="#jgxogytag93r" id="jgxogytag93r"></a>

Una vez dado de alta un dispositivo, en la pestaña de “Áreas” puede verse el estado de armado de cada área del panel:

<figure><img src=".gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

Cuando un área del panel está armada el icono indicativo estará verde, en caso contrario, el icono permanecerá azul:

<figure><img src=".gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Seleccionando los diferentes paneles en la lista superior, se filtran las áreas en la lista inferior.
{% endhint %}

{% hint style="info" %}
Es posible que los cambios de armado de un panel no se reflejen inmediatamente en el sistema de videoanálisis. El retraso de actualización podría encontrarse entre 1 y 10 segundos.
{% endhint %}

Como puede observarse, cada área del panel está representada en la tabla de áreas por dos filas, una representa su “Armado total” y la otra su “Armado en casa”. Dependiendo del estado de cada uno, los iconos aparecerán iluminados o no:

<figure><img src=".gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Algunos paneles Vesta disponen de más estados de armado a parte de “Armado total” y “Armado en casa”. Estos estados son ignorados por el sistema de videonálisis, sólo los estados mencionados producirán un evento utilizable en el sistema de videoanálisis.
{% endhint %}

Con el fin de realizar alguna acción cuando un área del panel se arme, pulsando en el botón editar, puede cambiarse el aviso asociado a este evento:

<figure><img src=".gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

Para crear un aviso que se pueda asociar a la entrada de armado se irá a (1)”Configuración” - (2)“Avisos del sistema” y aquí (3)añadir un aviso y (4)agregar las acciones que sean necesarias. Por ejemplo “Armar partición por tiempo de activación” y si se quiere crear alguna alarma con retardo “Borrar alarmas pendientes al final del evento”.

<figure><img src=".gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Para más información sobre la configuración de avisos del sistema consulte la guía rápida de configuración de avisos de Vaelsys V4.
{% endhint %}

&#x20;De la misma manera, puede también asociarse un aviso a la pérdida o recuperación de señal con el panel Vesta:

<figure><img src=".gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

## 5.- Activación de escenas <a href="#ycacmmbfrnrj" id="ycacmmbfrnrj"></a>

Es posible activar una escena de un panel Vesta a partir de una acción en el interior de un aviso. Para hacerlo, diríjase al apartado de Avisos del sistema, cree o edite un aviso y añada la acción.

En el formulario puede seleccionar sobre qué panel Vesta dado de alta actuar y el número de escena a activar:

<figure><img src=".gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

Este aviso se configurará en la regla del análisis que se quiera configurar para notificar a Vesta

<figure><img src=".gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

Para notificar una alarma sólo si no se desactiva el panel Vesta en X segundos habrá que generar un segundo aviso, con la acción de “Notificación programada después de X segundos” que llame al aviso con la acción “Notificar a panel Vesta”.



v1.0
