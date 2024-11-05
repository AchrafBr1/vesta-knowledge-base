---
description: Manual para centrales tipo BOGP de VESTA (VESTA-068N y VESTA-067)
---

# VESTA-068N: Manual instalador \[BOGP]

## Introducción: Manual para Centrales Tipo BOGP Autónomas

<figure><img src=".gitbook/assets/image (19).png" alt="" width="325"><figcaption><p>VESTA-068N/VESTA-067</p></figcaption></figure>

Este manual está diseñado para guiarte en la puesta en marcha y configuración de centrales tipo BOGP autónomas, operadas a pilas o con batería externa. El contenido del manual está organizado de la siguiente manera:

1. Conexión de batería externa y SIM
2. Alta del panel en instalador y Master
3. Añadir y configurar dispositivos
4. Completar configuraciones del sistema y reporte a CRA

## 1. Conexión de batería externa + SIM y configuración de APN

{% hint style="info" %}
Es crucial configurar el APN para que el panel pueda comunicarse con el cloud de SmartHomeSec. Asimismo, la conexión de la batería externa es fundamental para que el panel mantenga una comunicación constante y efectiva con el cloud. Si el panel solo cuenta con pilas internas, no se conectará al cloud a menos que se habilite el XMPP en los ajustes del panel.
{% endhint %}

### 1.1 Conexión de SIM y batería externa

<figure><img src=".gitbook/assets/image (4) (1).png" alt=""><figcaption><p>Insertar la SIM y Batería externa</p></figcaption></figure>

#### Baterías externas recomendadas:

{% hint style="success" %}
El panel con batería externa está **conectado al cloud al 100%. Usará las pilas de BACKUP en caso de agotar la batería externa**

**Muy importante** estas baterías requieren de ventilación por lo tanto evitar cualquier sitio confinado sin ventilación
{% endhint %}

{% tabs %}
{% tab title="8 meses de duración" %}
[DEM-7M-BACKUP](https://bydemes.com/es/productos/intrusion/alarma-vesta/baterias/DEM-7M-BACKUP/especificaciones)

<figure><img src=".gitbook/assets/image (17).png" alt="" width="225"><figcaption><p>Batería externa 7,5V /400Ah/3000W</p></figcaption></figure>
{% endtab %}

{% tab title="14 meses de duración" %}
[DEM-16M-BACKUP](https://bydemes.com/es/productos/intrusion/alarma-vesta/baterias/DEM-16M-BACKUP/especificaciones)

<figure><img src=".gitbook/assets/image (18).png" alt="" width="225"><figcaption><p>Batería externa 12V/500Ah, 6000W</p></figcaption></figure>
{% endtab %}
{% endtabs %}

### 1.2 Configuración del APN

<figure><img src=".gitbook/assets/Multimedia1.gif" alt=""><figcaption><p>Configuración del APN en la central</p></figcaption></figure>



{% hint style="success" %}
Para **entrar en configuración del panel BOGP** usando el teclado y pantalla LCD, hay que pulsar **\* durante 4 segundos.**
{% endhint %}

{% hint style="info" %}
Nota: También podemos configurar el APN con un comando SMS, que debemos enviar al número de teléfono de la SIM conectada en el panel:

**PROG 7982 GAPN:**<mark style="color:orange;">**internet**</mark>**,**<mark style="color:purple;">**user**</mark>**,**<mark style="color:blue;">**password**</mark>

_<mark style="color:orange;">Parameter 1</mark>: GPRS APN_

_<mark style="color:purple;">Parameter 2</mark>: GPRS user name_

_<mark style="color:blue;">Parameter 3</mark>: GPRS password_
{% endhint %}

{% hint style="warning" %}
Advertencia! Para paneles que NO disponen de batería externa, solo pilas internas, habilitar el cloud usando el teclado y pantalla LCD del propio panel de la siguiente forma antes de proceder:
{% endhint %}

<figure><img src=".gitbook/assets/image (2) (1).png" alt=""><figcaption><p>Habilitar el cloud, cuando se usa el panel únicamente por pilas</p></figcaption></figure>

## 2. Registro del panel como instalador y usuario

### 2.1 Registro como instalador

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Paso 1:</strong> Entrar como instalador en la APP <a href="guia-de-usuario-smarthomesec.md">SmartHomeSec</a></td><td><img src=".gitbook/assets/image (9) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Paso 2:</strong> Seleccionar el botón +</p><p>(Añadir panel)</p></td><td><img src=".gitbook/assets/image (10) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Paso 3:</strong> Introducir la dirección MAC del panel que viene una etiqueta</td><td><img src=".gitbook/assets/image (11) (1).png" alt="" data-size="original"></td><td></td></tr></tbody></table>

Una vez registrado el panel como instalador, está listo ✨ para su configuración.

{% hint style="danger" %}
El panel deberá estar encendido y con conexión a internet. Dispondremos de 15 minutos tras la alimentación para registrar el panel.
{% endhint %}

{% hint style="success" %}
La MAC del panel siempre está en un lateral del mismo físicamente. En el campo **NOMBRE**, debemos colocar el abonado o cualquier identificativo del panel.
{% endhint %}

### 2.2 Registro de la cuenta de usuario

La cuenta de usuario es la que se emplea para controlar el sistema y está destinada al usuario final. Desde la APP [SmartHomeSec](guia-de-usuario-smarthomesec.md), esta cuenta permite armar, desarmar y realizar cualquier operativa. Existen dos tipos de cuentas de usuario: Master y Esclava.

La primera cuenta que registramos es la Master. La diferencia principal entre la cuenta Master y la Esclava es que la Master permite crear nuevos usuarios, mientras que la Esclava no puede crear nuevas cuentas.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Paso 1:</strong> Acceder al panel como instaladores el código por defecto es [7982]</td><td><img src=".gitbook/assets/Imagen de WhatsApp 2024-06-02 a las 15.19.19_5e1f9a7f.jpg" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Paso 2:</strong> Seleccionar el apartado Menú principal del sistema<img src=".gitbook/assets/image (14) (1).png" alt=""></td><td></td><td></td></tr><tr><td><strong>Paso 3:</strong> Seleccionar lista de cuentas</td><td></td><td><img src=".gitbook/assets/image (15) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Paso 4:</strong> Seleccionar añadir</td><td></td><td><img src=".gitbook/assets/image (17) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Paso 5:</strong> Si es un usuario nuevo: Seleccionamos crear una cuenta</td><td><img src=".gitbook/assets/image (18) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Paso 6:</strong> Rellenamos los datos de nuestro usuario para el acceso a la APP</p><p><img src=".gitbook/assets/image (19) (1).png" alt="" data-size="original"></p></td><td></td><td></td></tr></tbody></table>

{% hint style="success" %}
Registro de usuario completado completado! para información como operar con la APP de usuario seguír la guía de usuario de [SmartHomeSec](guia-de-usuario-smarthomesec.md)
{% endhint %}

## 3. Añadir y configurar dispositivos

Para añadir y configurar dispositivos RF de VESTA, siga los siguientes pasos:

### 3.1 Añadir dispositivos

**Paso 1:** Acceda a la configuración del panel desde la APP instalador:

<figure><img src=".gitbook/assets/image (20).png" alt="" width="192"><figcaption><p>Instalador -> Ajustes</p></figcaption></figure>

**Paso 2:** Seleccione "Dispositivos" en el menú.

<figure><img src=".gitbook/assets/image (21).png" alt="" width="190"><figcaption><p>Instalador -> Ajustes -> Dispositivos</p></figcaption></figure>

**Paso 3:** En el **menú** haga clic en "**Añadir dispositivo**".

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (23).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (24).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (25).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

{% hint style="info" %}
El panel se pondrá en modo escucha, es el momento de pulsar nuestros botones "**learn**" de los dispostivos VESTA (Normalmente botón frontal, consultar manual del dispositivos en caso de duda)

<img src=".gitbook/assets/image (26).png" alt="" data-size="original">
{% endhint %}

**Paso 5:** El panel en modo escucha pulsar el botón learn, aquí una guía de la ubicación de botónes de los dispositivos más usados:

<figure><img src=".gitbook/assets/image (27).png" alt=""><figcaption><p>Botón learn de los dispositivos VESTA</p></figcaption></figure>

{% hint style="danger" %}
Importante! En caso de los PIRCAMS y teclados: La pulsación debe ser de 3 o 4 segundos. Mientras que el resto de dispositivos con una pulsación corta es suficiente para añadirlos.
{% endhint %}

Una vez añadidos, los dispositivos RF estarán listos para su uso y podrán ser gestionados desde el mismo apartado, aquí un ejemplo de configuración del atributo del sensor:

### 3.2 Configuración de la zona

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (28).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (30).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (31).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

{% hint style="info" %}
Para configurar las zonas correctamente, es importante familiarizarse con los atributos disponibles y su impacto en el comportamiento del sistema de alarma.

Por ejemplo: Interior es una zona instantánea y Entrada es una zona retardada; Podemos asignar estos atributos en el apartado Respuesta en armado que significa "Cuando el sistema está armado"
{% endhint %}

## 4. Configuración del panel y reporte a CRA (Central Receptor de Alarmas)

### 4.1 Configuración de seguridad

En esta sección, se detalla cómo ajustar la **duración de la sirena** durante una alarma y establecer los **retardos de entrada y salida**. Para facilitar la identificación y el ajuste, las opciones críticas se resaltan en \*\*color \*\*<mark style="color:red;">**rojo**</mark>.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (3).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Seguridad</td><td></td></tr><tr><td><img src=".gitbook/assets/image (4).png" alt="" data-size="original"></td><td><ol><li>La <strong>duración de sirena</strong> en caso de alarma</li><li>Al habilitar esta opción se retarda el reporte de las alarmas 30 segundos (<strong>Recomendable dejar DESACTIVADA</strong>)</li><li>Ajustar los <strong>retardos de entrada y salida</strong></li></ol></td><td></td></tr></tbody></table>

### 4.2 Configuración de panel

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (10).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (7).png" alt="" data-size="original"></td><td>NOTAS ANEXO 1</td><td></td></tr></tbody></table>

_ANEXO 1_

{% hint style="info" %}
1. El **Polling con Central Receptora de Alarma** (Muy importante configurar acorde al tiempo facilitado por la CRA)
2. Conectar Alarma: Cuando el panel se encuentra únicamente por pilas (<mark style="color:red;">**SIN BATERÍA EXTERNA**</mark>) esta opción nos permite acceder al panel por **CLOUD durante la ALARMA**
3.  **Modo ahorro Activado:**

    1. **El panel cuando solo opera por PILAS, estará OFFLINE, solo se conecta en caso de alarma**\
       **a. MODO AHORRO **<mark style="color:red;">**DESACTIVADO**</mark>**: El panel se quedará en CLOUD 100% con las pilas \[Advertencia! Las pilas durarán 14 días]**

    b. **MODO AHORRO **<mark style="color:green;">**ACTIVADO**</mark>**: El panel se quedará en OFFLINE reportará todos los eventos tanto a la APP como CRA \[Las pilas durarán 7 meses aprox.]**
{% endhint %}

### 4.3 Configurar códigos de usuario

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (20).png" alt="Instalador -> Ajustes" data-size="original"></td><td>Instalador -> Ajustes</td><td></td></tr><tr><td><img src=".gitbook/assets/image (8).png" alt="" data-size="original"></td><td>Ajustes -> PIN de usuario</td><td></td></tr><tr><td><img src=".gitbook/assets/image (9).png" alt="" data-size="original"></td><td>Añadir el Nombre y código para cada usuario, este código permitirá al usuario cambiar de modo desde la APP o teclados consultar <a href="guia-de-usuario-smarthomesec.md">Manual de usuario</a> para más información</td><td></td></tr></tbody></table>

### 4.4 Actualización del panel

Es crucial mantener el panel de control actualizado para asegurar un rendimiento óptimo y la seguridad del sistema. Las actualizaciones pueden contener mejoras esenciales, correcciones de errores y parches de seguridad que protegen contra vulnerabilidades conocidas.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (11).png" alt="" data-size="original"></td><td>Panel -> Actualización de FW</td><td></td></tr><tr><td><img src=".gitbook/assets/image (12).png" alt="" data-size="original"></td><td>Seleccionar del listado el firmware con versión más alta (Número más alto y letra más alta)</td><td></td></tr></tbody></table>

{% hint style="info" %}
NOTA: El panel por 2G o poca cobertura puede tardar 8 minutos en actualizar.

Si el panel comunica por 4G/LTE con buena cobertura la actualización puede tardar entre 3-5 minutos
{% endhint %}

{% hint style="danger" %}
Una vez el panel en modo actualización <mark style="color:red;">**NO apagar**</mark> ni desconectar bajo ningún concepto. El panel se reiniciará automáticamente.

APAGAR EL PANEL DURANTE UNA ACTUALIZACIÓN PUEDE DEJARLO TOTALMENTE INOPERATIVO
{% endhint %}

### 4.5 Configuración de reporte a CRA (Central Receptora de Alarmas)

_**Reporte Eventos**_

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13).png" alt="" data-size="original"></td><td>Ajustes -> Reporte</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14).png" alt="" data-size="original"></td><td>En el apartado reporte disponemos de configuración de reporte para eventos y archivos capturados para fotos de PIRCAMS</td><td></td></tr><tr><td><img src=".gitbook/assets/image (15).png" alt="" data-size="original"></td><td>En este apartado configuramos la URL de repote de nuestra CRA, y muy importante el <strong>GRUPO 2</strong> o superior ya que el gruopo 1 está empleado para la APP. ANEXO 2 para ejemplos</td><td></td></tr></tbody></table>

_ANEXO 2_

{% hint style="success" %}
Ejemplos de reporte de **EVENTOS** en diferentes protocolos:

:fire: **MANITOU (más usado en España): ip://**<mark style="color:blue;">**ABONADO**</mark>**@**<mark style="color:orange;">**IP\_DE\_CRA**</mark>**:**<mark style="color:purple;">**PUERTO**</mark>**/MAN**

:flag\_fr: SIA: **ip://**<mark style="color:blue;">**ABONADO**</mark>**@**<mark style="color:orange;">**IP\_DE\_CRA**</mark>**:**<mark style="color:purple;">**PUERTO**</mark>**/SIA2**

:map: CID: **ip://**<mark style="color:blue;">**ABONADO**</mark>**@**<mark style="color:orange;">**IP\_DE\_CRA**</mark>**:**<mark style="color:purple;">**PUERTO**</mark>**/CID**
{% endhint %}

_**Reporte fotos**_

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13).png" alt="" data-size="original"></td><td>Ajustes -> Reporte</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14).png" alt="" data-size="original"></td><td>En el apartado reporte disponemos de configuración de reporte para eventos y archivos capturados para fotos de PIRCAMS</td><td></td></tr><tr><td><img src=".gitbook/assets/image (16).png" alt="" data-size="original"></td><td>En este apartado configuramos la URL de repote de nuestra CRA para el envío de fotos. ANEXO 3 para ejmplos</td><td></td></tr></tbody></table>

{% hint style="success" %}
Ejemplos de reporte de **FOTOS** en diferentes protocolos:

:fire: **MANITOU**: <mark style="color:blue;">**ABONADO**</mark>**@**<mark style="color:orange;">**IP\_DE\_CRA**</mark>**:**<mark style="color:purple;">**PUERTO**</mark>
{% endhint %}
