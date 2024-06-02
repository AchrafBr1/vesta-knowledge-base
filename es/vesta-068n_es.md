---
description: Manual para centrales tipo BOGP de VESTA (VESTA-068N y VESTA-067
---

# VESTA-068N: Manual instalador \[BOGP]

## Introducción: Manual para Centrales Tipo BOGP Autónomas

<figure><img src=".gitbook/assets/image.png" alt="" width="325"><figcaption><p>VESTA-068N/VESTA-067</p></figcaption></figure>

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

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption><p>Insertar la SIM y Batería externa</p></figcaption></figure>

### 1.2 Configuración del APN

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption><p>Configuración del APN paso a paso</p></figcaption></figure>

{% hint style="warning" %}
Advertencia! Para paneles que NO disponen de batería externa, solo pilas internas, habilitar el cloud usando el teclado y pantalla LCD del propio panel de la siguiente forma antes de proceder:
{% endhint %}

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Habilitar el cloud, cuando se usa el panel únicamente por pilas</p></figcaption></figure>





## 2. Registro del panel como instalador y usuario

### 2.1 Registro como instalador

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Paso 1:</strong> Entrar como instalador en la APP SmartHomeSec</td><td><img src=".gitbook/assets/image (9).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Paso 2:</strong> Seleccionar el botón + </p><p>(Añadir panel) </p></td><td><img src=".gitbook/assets/image (10).png" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Paso 3:</strong> Introducir la dirección MAC del panel que viene una etiqueta</td><td><img src=".gitbook/assets/image (11).png" alt="" data-size="original"></td><td></td></tr></tbody></table>

Una vez registrado el panel como instalador, está listo [✨](https://emojipedia.org/es/chispas) para su configuración.

{% hint style="danger" %}
El panel deberá estar encendido y con conexión a internet. Dispondremos de 15 minutos tras la alimentación para registrar el panel.
{% endhint %}

{% hint style="success" %}
La MAC del panel siempre está en un lateral del mismo físicamente. En el campo **NOMBRE**, debemos colocar el abonado o cualquier identificativo del panel.
{% endhint %}

### 2.2 Registro de la cuenta de usuario

La cuenta de usuario es la que se emplea para controlar el sistema y está destinada al usuario final. Desde la APP SmartHomeSec, esta cuenta permite armar, desarmar y realizar cualquier operativa. Existen dos tipos de cuentas de usuario: Master y Esclava.

La primera cuenta que registramos es la Master. La diferencia principal entre la cuenta Master y la Esclava es que la Master permite crear nuevos usuarios, mientras que la Esclava no puede crear nuevas cuentas.





