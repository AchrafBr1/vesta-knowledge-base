# 🛡️ ALARMSPACE

**MANUAL DE USUARIO V.3.0.1.4-003**

**ALARMSPACE** (PASARELA CENTRAL RECEPTORA DE ALARMAS)

**Software de CRA para control de dispositivos de seguridad e incendio**

![](<../.gitbook/assets/0 (10).png>)

![](<../.gitbook/assets/1 (35).png>)

\
**ÍNDICE**

ÍNDICE 2

1\. Introducción 5

1.1. Funciones 5

1.2. Novedades 5

2\. Módulo Servidor 5

2.1. Login 5

2.2. Usuarios 6

2.2.1. Gestión de Usuarios 6

2.2.2. Grupos de Usuario 6

2.2.3. Logout P2P Hyundai/Hikvision 7

2.3. DVR 8

2.3.1. Lista 8

2.3.1.1. Datos Generales 8

2.3.1.1.1. DVR MASTER\_BYDEMES 10

2.3.1.1.2. Importaciones 11

2.3.1.2. Opciones 11

2.3.1.3. Leyenda 12

2.3.1.4. Alarmas 12

2.3.1.4.1. Gestionar Alarmas por canal 14

2.3.1.4.2. Gestionar estados 16

2.3.1.4.3. Calendario Alarmas 17

2.3.1.5. _Certificados_ 18

2.3.2. DVR por Usuario 19

2.3.3. DVR por Grupo 19

2.3.4. Listado de DVRs 20

2.3.5. Grupos 20

2.3.6. Abonados INTRUSIÓN 21

2.3.7. Usuarios paneles 22

2.3.8. Zonas Central 23

2.3.9. Datos Abonados 25

2.3.10. Parámetros IA 25

2.3.11. Nuevos Códigos VESTA 28

Ge2.4. Alarmas 29

2.4.1. Acciones 29

2.4.2. Pasarela 30

2.4.3. Listado 30

2.4.4. Eventos DVRs 31

2.4.5. Programación Listados 32

2.4.6. Códigos Intrusión 33

2.5. Configuración 34

2.5.1. Parámetros Receptora 34

2.5.1.1. Parámetros generales 35

2.5.1.2. Comunicaciones con CRA 35

2.5.1.3. Otros parámetros 36

2.5.2. Incorporar Licencias 37

2.5.3. Renovar Tablas Master 37

2.5.4. Configuración Avanzada 37

2.5.5. Panel de Control 40

2.5.6. Visor de Logs 41

2.5.7. Certificados Automáticos 42

2.5.8. Instancias P2P Dahua 42

2.6. Copias de Seguridad 43

2.6.1. Importar/Exportar 43

2.6.2. Configurar 43

2.6.3. Limpieza 44

2.7. Idiomas 45

2.8. Ayuda 45

3\. Módulo Operador 45

3.1. Login 45

3.2. Tiempo Real 48

3.2.1. Incendio 56

3.2.2. Video-porteros 58

3.2.3. Incendio Analógico 59

3.3. Vídeo 61

3.4. Alarmas 63

3.4.1. Alarmas Intrusión 64

4\. Módulo ActiveX 68

4.1. Comandos Pasarela 68

4.2. Nuevos Comandos 71

5\. Configuración pasarela VESTA 73

5.1. Introducción 73

5.1.1. Bienvenidos 73

5.2. Programación Central VESTA 73

5.3. Configuraciones AlarmSpace 76

5.3.1. Configuraciones generales - VESTALog 76

5.3.1.1. Tiempo real 77

5.3.1.2. Histórico 77

5.3.1.3. Log 78

5.3.1.4. Configuración VESTA 78

5.3.1.5. Códigos Eventos 82

5.3.1.6. Destinos eventos 84

5.3.1.7. Reasignar Eventos 85

5.3.1.8. Configurar Balanceador 85

5.3.1.9. _Parámetros LORA_ 85

_5.3.1.10. Parámetros API_ 86

_5.3.1.11. API Múltiple_ 86

5.3.1.12. Configuración general de AlarmSpace 87

5.3.2. Control de abonados 88

5.4. Configuraciones Software de Recepción de Alarmas de CRA 90

5.4.1. Manitou 90

5.4.2. SBN 92

5.4.3. Softguard 92

5.5. Módulo Visor – Acceso Bidireccional para centrales VESTA 92

5.5.3. Comando llamada al Visor Vesta 92

6\. Configuración central AXHUH 94

6.1. Hikvision AXHUB and AlarmSpace 94

6.1.2. Introducción 94

6.1.3. Requisitos mínimos 94

6.1.4. Configuraciones iniciales en AlarmSpace 94

6.1.5. Configuraciones especiales de la AXHUB 95

6.1.5.1. Centro de Recepción de Alarmas 95

6.1.5.2. Registro EHome 96

6.1.5.3. Ajustes adicionales 97

6.1.6. Funcionamiento en AlarmSpace 98

6.1.6.1. Parámetros Generales 98

6.1.6.2. Configuración Alarmas Vídeo 99

6.1.6.3. Control desconexiones 100

7\. Módulo Visor Cámaras 102

### &#x20;1. Introducción <a href="#toc84228587" id="toc84228587"></a>

AlarmSpace es una plataforma de software para el control, monitorización y visualización de videograbadores y cámaras.

### &#x20;1.1. Funciones <a href="#toc84228588" id="toc84228588"></a>

· Visualización de cámaras en tiempo real​

· Reproducción de vídeo grabado​

· Gestión de entradas de alarmas y de alarmas técnicas de los videograbadores​

· Integración con los principales software de CRA.&#x20;

### &#x20;1.2. Novedades <a href="#toc84228589" id="toc84228589"></a>

AlarmSpace integra también otros dispositivos como Videoporteros y Centrales de Incendio Convencionales de Honeywell. Además, funciona como una pasarela para la recepción, gestión y retransmisión de eventos de la Central Vesta.

### &#x20;2. Módulo Servidor <a href="#toc84228590" id="toc84228590"></a>

El módulo servidor de Alarmspace es solo accesible por usuarios de tipo administrador. Sus funciones principales son las altas y modificaciones de usuarios, de equipos, asignaciones de cámaras a usuarios, configuraciones de acciones de alarmas, de códigos de pasarela, de parámetros de receptora y realización y configuración de copias de seguridad de los datos sensibles del programa.

### &#x20;2.1. Login <a href="#toc84228591" id="toc84228591"></a>

El módulo Servidor de AlarmSpace requiere un acceso a través de un usuario de nivel _Administrador._ El usuario por defecto es:

Usuario: admin

Contraseña: 12345

Después se puede cambiar la contraseña del administrador y crear más usuarios administradores en el menú Usuarios.

![](<../.gitbook/assets/2 (31).png>)

La pantalla de acceso al servidor nos informa de la versión actual de AlarmSpace, nos pide Usuario y contraseña y podemos _Aceptar_ para entrar en el Servidor o _Salir_ para abortar la operación. El último usuario utilizado queda registrado y aparecerá por defecto la próxima vez que se ejecute el Servidor.

### &#x20;2.2. Usuarios <a href="#toc84228592" id="toc84228592"></a>

Altas y modificaciones de usuarios.

#### &#x20;2.2.1. Gestión de Usuarios <a href="#toc84228593" id="toc84228593"></a>

![](<../.gitbook/assets/3 (27).png>)

En esta tabla vemos todos los usuarios del sistema. Al hacer doble click sobre el usuario lo cargamos en la parte inferior para editarlo:

![](<../.gitbook/assets/4 (16).png>)

Podemos cambiar la descripción del usuario, el nombre, la contraseña y el nivel (administrador u operador). Sólo los administradores pueden acceder al módulo servidor.

También se pueden crear nuevos usuarios con el botón nuevo. Se rellenan todos los campos y se pulsa el botón _Guardar_.

También se pueden eliminar usuarios cargando el Usuario con doble-click y pulsando el botón _Borrar._

Para descartar los cambios que se están realizando podemos pulsar el botón _Cancelar._

#### &#x20;2.2.2. Grupos de Usuario <a href="#toc84228594" id="toc84228594"></a>

A los usuarios que hemos definido en el punto anterior podemos asignarles uno o más grupos. Como los usuarios pueden usarse para controlar remotamente paneles de intrusión desde AlarmSpace (Ver Módulo Visor – Acceso Bidireccional para centrales VESTA), estos grupos nos sirven para asignarle al usuario un conjunto de paneles que el usuario tiene permisos para controlar. La operativa es asignar el grupo al panel (en Control de abonados) y al asignar el grupo al usuario, el panel le será asignado automáticamente.

Para asignar un grupo a un usuario primero seleccionamos el usuario en el desplegable:

![](<../.gitbook/assets/5 (14).png>)

Una vez seleccionado en la parte inferior asignamos el grupo/grupos que le queramos asignar (o seleccionamos “Todos los Grupos”) y pulsamos en “Añadir Grupo”:

![](<../.gitbook/assets/6 (12).png>)

El Grupo quedará asignado al Usuario:

![](<../.gitbook/assets/7 (12).png>)

Si deseamos quitar un grupo a un usuario, seleccionamos el usuario en el desplegable, doble-click sobre el grupo a quitar, se carga en la sección inferior y le damos a “Quitar Grupo”:

![](<../.gitbook/assets/8 (12).png>)

#### &#x20;2.2.3. Logout P2P Hyundai/Hikvision <a href="#toc84228595" id="toc84228595"></a>

Si se utiliza el P2P de Hyundai y/o Hikvision podemos desconectar el usuario de P2P mediante este menú. La reconexión de nuevo con el mismo u otro usuario de P2P se lanzará automáticamente al arrancar el módulo servidor.

### &#x20;2.3. DVR <a href="#toc84228596" id="toc84228596"></a>

Gestión de videograbadores, cámaras y dispositivos soportados.

#### &#x20;2.3.1. Lista <a href="#toc84228597" id="toc84228597"></a>

Altas y modificaciones de los equipos.

\
**2.3.1.1. Datos Generales**

Gestión de altas y modificaciones de los equipos. Se presentan en una tabla:

![](<../.gitbook/assets/9 (13).png>)

En cada fila vemos la información del equipo. Si tiene problemas de conexión la fila aparece en rojo.

Podemos buscar equipos por descripción, abonado o número de serie.

Permite sincronizar todos los equipos.

Se pueden mostrar los equipos filtrados por criterios: desconectados, por tipo/marca de equipo, por descripción, por tipo de conexión, por grupo...

Los equipos que se están visualizando según el filtro se pueden exportar a CSV-Excel y a PDF.

Para gestionar cambios doble-click sobre la fila del equipo:

![](<../.gitbook/assets/10 (52).png>)

Si queremos añadir un nuevo equipo pulsamos en el botón Nuevo.

Añadimos o modificamos la descripción del equipo. Elegimos el tipo de conexión predeterminado, directo o P2P. Si tiene datos para conectar por los dos medios intentará primero por el predeterminado y si falla por el otro.

En conexión directa tenemos que poner en Dirección la IP o el DDNS y el Puerto.

Tipos dispositivos:

· Coloso Evolution: Marca Dahua con firmware ByDemes

· Coloso AS: Marca Dahua con firmware ByDemes-AirSpace

· HyundaiNextGen: Marca Hyundai modelos NextGen

· Hikvision: Marca Hikvision

· Dahua General: Marca Dahua con firmware original

· Videoportero Dahua: Videoporteros marca Dahua (SDK Dahua)

· Honeywell incendio: Marca Honeywell modelos convencionales

· Honeywell analógico: Marca Honeywell, modelos analógicos

· AX HUB: Marca Hikvision, central de intrusión con captura de vídeo en AlarmSpace

Grupo: se puede asignar un grupo al dispositivo para filtrar en Servidor/Operador y para envío de emails de grupo.

Abonado: el número de abonado que se mandará al software de CRA en los eventos.

Código Verificación: código necesario para visualizar determinadas cámaras de equipos Hikvision.

Número Serie para consultar el P2P: número de serie del equipo necesario para acceder vía P2P al equipo. El P2P tiene que estar activado en el grabador.

Puerto P2P: el puerto TCP programado en el equipo, aunque no hace falta abrirlo en la red de la instalación del cliente, es necesario informarlo.

Usuario: un usuario válido del equipo

Contraseña: la contraseña del usuario anterior.

Al pulsar _Cargar configuración_ el software intentará conectar con el equipo por las vías disponibles e informará de la correcta o incorrecta conexión por cada una de ellas.

![](<../.gitbook/assets/11 (27).png>)

Además, carga el número de serie leído en _Número de Serie,_ los canales totales del equipo en _Canales,_ los canales de salida y la Fecha del equipo.

Si pulsamos en _Guardar_ se guardarán los cambios y se añadirá la fila si era un equipo nuevo. Si pulsamos en _Cancelar_ se descartarán los cambios.

El botón _Datos_ permite asignar datos adicionales al equipo:

![](<../.gitbook/assets/12 (20).png>)

Se han añadido nuevos filtros para poder utilizar estos cambios:

![](<../.gitbook/assets/13 (16).png>)

Permite filtrar por población, provincia, teléfono y email.

\
**2.3.1.1.1. DVR MASTER\_BYDEMES**

Al instalar o actualizar AlarmSpace aparece en la lista de DVR un grabador máster llamado MASTER\_BYDEMES. Se utiliza para enviar eventos genéricos del sistema al software de CRA. Se puede editar como cualquier otro DVR aunque no podemos conectar con él porque no existe físicamente. Podemos modificar el número de abonado que se mandará (por defecto 0000) y podemos elegir los eventos de alarma que queramos enviar:

![](<../.gitbook/assets/14 (13).png>)

Los tipos de alarmas a gestionar son:

_Test periódico_ envía una señal de test periódicamente con el mismo período que definimos para el hearbeat en Configuración -> _Parámetros Receptora_

_Disco Duro Lleno_ detecta cuando al disco del servidor de AlarmSpace le queda menos de un 10% de capacidad libre y envía el aviso.

_Error serv. P2POri_ avisa si falla el chequeo del servicio de P2P contra la nube de Dahua Original

_Rest. serv, P2POri_ avisa cuando se restaura el servicio P2P contra Dahua Original

_Error serv. P2P_ avisa si falla el chequeo del servicio de P2P contra la nube de ByDemes

_Rest. serv, P2P_ avisa cuando se restaura el servicio P2P contra ByDemes

\
**2.3.1.1.2. Importaciones**

AlarmSpace es capaz de importar datos del programa SmartPSS de Dahua. La importación se hace a través del fichero devices.xml resultado de la exportación de SmartPSS. Importamos los datos sobre la plantilla de un DVR ya existente, para completar los datos que no contenga el fichero devices con los del modelo:

![](<../.gitbook/assets/15 (11).png>)

En este caso si pulsamos sobre _Importar DVR XML copiando el resto de datos,_ daríamos de alta los nuevos grabadores en AlarmSpace con los datos de devices.xml y el resto de datos del DVR _ColEvoP2PPrb._

También podemos crear nuevos equipos copiando los datos de otro. Si pulsamos en _Nuevo DVR copiando datos_ creamos un nuevo equipo exactamente con los mismos datos que _ColEvoP2PPrb._ Entonces solo tenemos que cambiar los datos propios del DVR (datos de conexión, abonado, ...) pero el resto de datos (opciones, alarmas...) ya los tendremos dados de alta.

\
**2.3.1.2. Opciones**

Programamos distintas opciones generales del equipo:

![](<../.gitbook/assets/16 (11).png>)

_Segundos grabación pre vídeo alarma:_ en caso de tener las entradas de vídeo cableadas, por detección de movimiento o eventos IVS, cuando llega una alarma de grabador AlarmSpace descarga un vídeo de unos segundos antes de la cámara asociada con la duración asignada en esta casilla. En el ejemplo 30 segundos de vídeo.

_Segundos grabación vídeo en alarma:_ en la misma situación anterior, los segundos que descargaremos después del salto de la alarma (10 en este caso).

_Priorizar canal:_ el canal en el que se realizará la descarga si está disponible: principal o substream.

_Activar chequeo del sistema:_ hace falta activar esta casilla para recibir los eventos de los equipos.

_Enviar email cuando se detecta una desconexión:_ enviará un recordatorio a las 12 horas de tener un equipo desconectado.

_Enviar alarmas por pasarela:_ los eventos que se reciban de los equipos se enviarán al software de CRA mediante el protocolo elegido en _Parámetros Receptora_

_Operador Automático:_ los eventos enviados al Software de CRA no esperarán respuesta de este, se cerrarán automáticamente después del envío.

_Enviar alarmas a verificación de vídeo:_ Los eventos no se mandarán al Software de CRA sino que aparecerán en la pestaña _alarmas_ del Módulo Operador

_Email cliente:_ email o emails separados por punto y coma (;) a los que se pueden enviar los eventos de este equipo en concreto. Hace falta configurar el servidor SMTP en _Parámetros Receptora_

_Reiniciar:_ permite reiniciar remotamente el equipo.

_Sincronizar hora:_ actualiza la hora del equipo remoto con la hora del servidor de AlarmSpace

_Cerrar Alarmas Pendientes:_ si existen alarmas no respondidas por el software de CRA o no atendidas en las _alarmas_ del Operador, mediante este botón las podemos finalizar todas.

_Guardar configuración del DVR a disco:_ permite guardar la configuración que estamos realizando a un fichero en el sistema de ficheros del servidor de AlarmSpace.

_Cargar configuración del disco a DVR:_ recarga los datos de configuración desde un fichero elegido.

\
**2.3.1.3. Leyenda**

Sin uso en la actualidad

\
**2.3.1.4. Alarmas**

Configurar las Alarmas que deseamos recibir y reenviar:

![](<../.gitbook/assets/17 (7).png>)

En esta pantalla inicial de alarmas marcamos los eventos generales del equipo que queremos monitorizar. Pulsamos el check al lado del evento y elegimos un tipo de evento a mandar en el desplegable. Los tipos de eventos se corresponden a los códigos (ContactID,SIA) que enviaremos al software de CRA. Son configurables a través de la sección _Pasarela_ del menú _Alarmas._ También elegimos la zona que mandaremos con el evento. En la sección enviar email podemos elegir no enviarlo, enviarlo al mail administrador (AS), configurado en _Configuración -> Parámetros Receptora,_ enviarlos al email de _Grupo_ o al email de cliente configurado en _Opciones_.

Los eventos a monitorizar son Fallo, Falta o Disco Duro Lleno, Conflicto de IP. Estos eventos tienen que estar configurados en el grabador y con la opción _Subir Alarma,_ si no, no los recibiremos. Los eventos _Desconexión/Reconexión_ no dependen de ninguna configuración del grabador. El tiempo de desconexión para darla por válida es configurable en el menú _Configuración -> Configuración avanzada,_ mediante el parámetro: TIEMPO\_DESCONEXIÓN\_DVR (en segundos).

El botón _Gestionar Alarmas por canal_ se utiliza para configurar alarmas de cada uno de los canales del grabador.

El botón _Gestiona estados_ permite programar alarmas que retardadas de los eventos y enviar recordatorios si persiste el estado de alarma.

El botón _Calendario Alarmas_ establece un calendario en el que se reciben o no los eventos. Especialmente pensado para recibir o no los eventos de llamada de los VTO de los kits de los vídeo-porteros.

En el caso de vídeo-porteros tenemos otro tipo de alarma para monitorizar:

![](<../.gitbook/assets/18 (8).png>)

Es la _Llamada VTO._ Si está marcada se mandará el evento asociado a ALARMA MEDICA (Ver _Alarmas -> Pasarela_) cuando un usuario pulse el botón de llamada del VTO. Esto permitirá gestionar la llamada desde el Módulo ActiveX de AlarmSpace y hacer gestiones con los bObject de los softwares de CRA.

_Alarmas de incendio_

En el caso de centrales de incendio convencionales de Honywell, nos aparece un botón para poder seleccionar más eventos para enviar a CRA:

![](<../.gitbook/assets/19 (8).png>)

Pulsando el botón _Más Eventos_ accedemos al siguiente formulario:

![](<../.gitbook/assets/20 (9).png>)

En el formulario aparecen todos los eventos genéricos de la central que no tenemos en la pestaña Alarmas anterior. Podemos marcar qué eventos queremos enviar a CRA marcando el check al lado del evento. El código que se enviará lo elegimos con el desplegable (con los códigos disponibles definidos en Alarmas - Pasarela). También podemos asignar un número de zona a asignar al evento tecleándolo en las casillas de _Zona._ Cuando hemos terminado los cambios debemos pulsar en el botón _Guardar_ para conservarlos.

**2.3.1.4.1. Gestionar Alarmas por canal**

Programación de los eventos de cada canal:

En la tabla superior se muestran todos los canales detectados en el grabador. Doble-click sobre una fila para cargar los parámetros programados para cada canal.

En _Canal_ vemos el número de cámara/canal,

En _Nombre_ modificamos la descripción de la cámara.

En _Zona en Pasarela_ ponemos la zona que se va a enviar al software de CRA. Si se deja en blanco enviará el número de canal en 3 dígitos (ex: 001,016...)

El Check _Activo_ permite seleccionar si un canal tiene una cámara activa o no. Así por ejemplo, si el canal no está activo, no se mostrará como opción a la hora de generar un Certificado de la instalación.

Marcamos los eventos que queremos enviar como en los eventos generales y escogemos en el desplegable el tipo de evento que se asocia al código (SIA/ContactID) que se mandará al software de CRA. Este código se asocia en la sección _Pasarela_ del menú _Alarmas._

Igualmente podemos mandar email al correo del administrador de AlarmSpace (_Configuración -> Parámetros Receptora),_ al de grupo (DVR -> _Grupos_), y/o al del propio cliente (configurado en _Opciones_).

También se pueden mandar eventos inteligentes IVS. Recordemos que todos estos eventos (excepto _Fallo Grabación_ y _Cámara en Negro_), hay que programarlos en el grabador y marcar la opción _Subir Evento_ o parecida (dependiendo de la marca y el modelo del grabador).

Los botones _Enviar todo_ y _No enviar nada,_ marcan y desmarcan respectivamente todos los envíos.

Podemos copiar los datos de un canal en los otros canales pulsando con el botón derecho sobre la fila. Nos aparece el menú _Copiar datos en los otros canales._ Pulsando sobre el menú podemos elegir a qué canales queremos replicar los datos:

Al pulsar Ok se copian y guardan los datos en los canales seleccionados.

\
&#xNAN;_&#x41;larmas de incendio_

Los eventos de incendio son totalmente distintos de los de los grabadores. También podemos gestionarlos al cargar el botón _Gestionar Alarmas por canal_ si estamos gestionando una central de incendio:

Cargamos los datos de cada zona y podemos elegir que eventos queremos enviar al software de gestión con el check _Gestionar._ Asociamos el código que enviaremos con el evento seleccionado en _Codigo_ (Ver _Alarmas -> Pasarela_).

\
**2.3.1.4.2. Gestionar estados**

Gestión de los estados de los equipos. Permite mandar señales al cabo de unos minutos de producirse una desconexión de un grabador o de una cámara, recordar si continua la desconexión periódicamente y avisar de la restauración del evento al cabo de unos minutos:

En este caso enviaría la desconexión de la cámara uno con el código asociado al evento ALARMA MEDICA (Ver _Alarmas -> Pasarela_) a los 10 minutos de producirse el evento. Cada 24 horas (1440 minutos) mandaría un recordatorio de la desconexión (en caso de estar todavía desconectada) y la reconexión de la cámara se mandaría inmediatamente.

\
**2.3.1.4.3. Calendario Alarmas**

AlarmSpace dispone de un calendario en el que le podemos indicar los horarios en los que deseamos registrar y enviar las alarmas y en cuáles no. Está especialmente pensado para la gestión de llamadas de vídeo-portero, para permitir que en determinados horarios las llamadas se gestionen localmente en la instalación mediante la pantalla VTH o cuando debe saltar la alarma en AlarmSpace para ser gestionada remotamente desde el centro de control.

En el ejemplo vemos los horarios del lunes. Los eventos saltarían de 12 de la noche hasta las 8 de la mañana. Se atenderían en local hasta las dos del mediodía. Remotamente hasta las 4, en local de 4 a 8 de la tarde y en remoto hasta finalizar.

Podemos copiar estos horarios al resto de días de la semana con el botón _Copiar a todos los días,_ sólo de lunes a viernes o elegir los días a copiar con _Copiar a otros días:_

**2.3.1.5.&#x20;**_**Certificados**_

Programamos la generación automatizada de certificados de las instalaciones. Si activamos esta opción en un DVR se generará un certificado de la instalación en el directorio _AutoCerts,_ dentro de la carpeta de trabajo de AlarmSpace:

_Activo:_ marcando este check se activa la generación de certificados automáticos en el grabador.

_Fecha Inicio_: fecha a partir de la cual empezarán a generar certificados.

_Fecha Fin_: fecha a partir de la cual dejarán de generarse los certificados.

_Período_: frecuencia con la que se generarán los certificados. Depende de la escala de tiempo que elijamos en el desplegable (meses, horas o minutos). En el cas del ejemplo se generará un certificado cada 3 meses.

_Tipo_: puede ser básico (capturas de las cámaras y pequeño histórico de eventos recientes) o Completo (se añaden las grabaciones existentes de cada uno de los canales activos)

_Enviar por Email_: enviamos el certificado generado al email que consta en _Email._

_Fecha Próximo:_ es la fecha en la que se generará y enviará si así lo hemos seleccionado el próximo certificado. No es editable.

_Hora envío_: podemos forzar una hora de generación y envío del certificado. El sistema esperará hasta la hora señalada del día que toque el envío para generar y enviar el certificado.

_Minutos Grabaciones:_ en caso de elegir el tipo de certificado completo, indicamos aquí los minutos anteriores a la generación del certificado que queremos buscar grabaciones existentes. Si se ponen muchos minutos (por ejemplo un mes) el certificado puede tener un número de hojas importante.

#### &#x20;2.3.2. DVR por Usuario <a href="#toc84228607" id="toc84228607"></a>

Podemos asignar cámaras individualmente a usuarios, para que estos las puedan visualizar o no el Módulo Operador:

Marcamos las cámaras que queremos asignar al usuario.

Con el botón _Asignar todas las cámaras al usuario seleccionado_ asignamos todas las cámaras de todos los grabadores al usuario.

Con el botón _Quitar todas las cámaras al usuario seleccionado_ le quitamos la asignación de todas las cámaras al usuario.

Podemos seleccionar un usuario modelo y asignarle las mismas cámaras al usuario seleccionado mediante el botón _Asignar DVR del modelo al usuario seleccionado._

Con el botón _Guardar_ dejamos los cambios registrados.

#### &#x20;2.3.3. DVR por Grupo <a href="#toc84228608" id="toc84228608"></a>

Funcionalidad no implementada.

#### &#x20;2.3.4. Listado de DVRs <a href="#toc84228609" id="toc84228609"></a>

Con esta funcionalidad generamos un fichero csv con todos los equipos en la ruta especificada:

Ejemplo de listado csv:

#### &#x20;2.3.5. Grupos <a href="#toc84228610" id="toc84228610"></a>

Definimos grupos para poder asociar los equipos a un determinado conjunto o grupo en este caso. Al asociar un equipo a un grupo podremos filtrar los equipos por este grupo (tanto en la lista del Servidor como en los equipos que se muestre en el Operador) como enviar las alarmas que marquemos a un email de ese grupo.

Para añadir o modificar grupos:

Botón _Nuevo_ para empezar a añadir uno nuevo o doble click en la tabla para editar un grupo existente.

Debemos poner una descripción del grupo y un email. Con el botón _Guardar_ para almacenarlo y _Borrar_ para eliminarlo.

_Cancelar_ para descartar los cambios.

#### &#x20;2.3.6. Abonados INTRUSIÓN <a href="#toc84228611" id="toc84228611"></a>

Visualizamos los abonados de la aplicación, si están activos o no, el tiempo de polling, si están en fallo polling , si hay que enviar los eventos de fallo de polling, la fecha del último polling y si hay que enviar la señal a algún destino particular de cada abonado, el tipo de central, la Mac del equipo, el grupo al que están asignadas, el número de fallos de polling para generar evento de fallo, la fecha de registro, el estándard utilizado para los códigos de intrusión (CID, SIA), si se envían los eventos de Fallo polling, la Tolerancia del Test periódico, el estado de la vía de Ethernet(Ip) del panel, el estado y nivel de cobertura de GPRS del panel, el estado de la batería (si es batería externa si está presento o no) y si tiene programado un rearmado automático:&#x20;

Si le damos doble click sobre un abonado podemos cambiar algunos parámetros del abonado:&#x20;

Concretamente podemos cambiar el Período de polling (para ajustarlo al que esté programado en la central VESTA en cuestión), en minutos, elegir si enviar o no los eventos de polling, y activar/desactivar el abonado. Si un abonado está inactivo las señales que puedan llegar quedan registradas, pero no pasan al software de gestión de CRA. También permite programar un test periódicamente (es un polling que sí que llegará al software de CRA). En el ejemplo se envía cada 24 horas. Para evitar un retraso de este test se le asignar una tolerancia (en segundos).

En _Destino Señales_ podemos elegir un distinto para las señales de este abonado. Si se deja en blanco se enviarán a la Ip:Puerto que se defina en la configuración de AlarmSpace -> _Parámetros Receptora_ o en la _configuración particular de Vesta_. En el desplegable aparecen los destinos particulares que hemos dado de alta en VESTALog en el apartado _Destino Eventos,_ que serán otras Ip:Puerto para enviar. También está la opción _Todos los destinos,_ con la que se enviarán las señales a todas las Ip:Puerto que tengamos definidas en _VESTALog -> Destino Eventos._

Alarmspace registra la Mac de los equipos para evitar duplicidades o usos maliciosos de la pasarela. Si un equipo con el mismo número de abonado transmite con una Mac distinta la CRA recibirá un error de Mac. Si sabemos que es un simple cambio de equipo, para solucionar este problema podemos pulsar el botón “Resetear Mac”, que borra la Mac del equipo y cogerá la de la próxima transmisión. Para saber la Mac de la otra central que está transmitiendo con el mismo número de abonado, esta quedará reflejada en la casilla MAC Error (se reseteará junto con la MAC Equipo con el botón Resetear MAC)

Podemos elegir un Grupo para cada equipo, este permite filtrar la visualización de los equipos en el Módulo Visor por usuario y facilita el envío de códigos de usuario por grupos. Estos grupos se definen en DVR -> Grupos.

Se pueden modificar el Número de Fallos Polling para Mandar Fallo. Esto es, el número de veces que tiene que fallar el polling de una central para generar el evento de fallo de polling.

También podemos visualizar el estándar de códigos que usa el abonado (SIA o CID).

Si marcamos el check _Rearmado automático_ el panel se armará automáticamente al cabo de 2 horas de la apertura. Este tiempo es configurable individualmente para cada abonado en la utilidad a la que se accede con el botón Datos Abonado.

Con el desplegable API podemos asignar unos parámetros API distintos de los genéricos al abonado para usar en el VisorHTML (solo para combinar equipos asignados a distintos backends de Climax en un mismo AlarmSpace).

Entre las acciones que podemos realizar, aparte de Guardar los cambios, Cancelar los cambios o Borrar el equipo (eliminarlo definitivamente de los equipos registrados, podemos acceder al Módulo Visor desde el botón “Estado Central”.

Con el botón Última Localización vemos la última localización enviada desde una App de usuario con el botón de pánico.

Con el botón “Usuarios Central” accedemos al mantenimiento de Usuarios Paneles de la central, para poder cambiar remotamente códigos de usuario de los paneles.

Con el botón “Zonas Central” accedemos al mantenimiento Zonas Central, donde visualizamos las zonas y dispositivos que tenemos agregados al panel. Podemos asignar una cámara de un grabador dado de alta en DVR → Lista, que enviará una grabación del canal cuando salte esa zona.

Con el botón “Parámetros IA” procedemos a ajustar los parámetros del análisis inteligente de imágenes capturadas por pircam y cámaras integradas.

#### 2.3.7. Usuarios paneles <a href="#id-2.3.7._usuarios_paneles" id="id-2.3.7._usuarios_paneles"></a>

Módulo de control de usuarios de los paneles:

En “Directo/Programación” elegimos si programamos los usuarios individuales o de todo un grupo o la lectura y envío de datos directamente a un panel. Si elegimos Programación(Nombres) significa que podemos cambiar códigos de los usuarios, añadir o eliminar usuarios de todo un grupo por el Nombre del usuario. Así, elegimos el Grupo a controlar en el desplegable “Grupos”. Para elegir un usuario, hacemos doble click sobre un usuario. Para crear uno nuevo, le damos al botón Nuevo (nos pregunta a que partición pertenecerá el usuario).

Una vez seleccionado o creado podemos poner el Código y si envía Reporte (envía sus armados/desarmados). Si marcamos Borrar, en cuanto enviemos se borrará el usuario de los paneles. Si marcamos la casilla “Código Temporal”, el usuario solo estará activo en la franja horaria limitada por las fechas “Activo Desde” y “Activo Hasta”.

Una vez guardados los cambios, pulsando el botón “Enviar a Todo el Grupo”, los usuarios marcados como “Activos”, se enviarán (o borrarán si así se ha seleccionado) a los distintos paneles del grupo. El modo de proceder es buscar en los paneles el usuario con el nombre que se les ha asignado, si los encuentra, cambia el código que tienen en el panel/área por el que le hemos asignado. Si no lo encuentra, añade el nuevo usuario con el nuevo código. Si lo que hacemos es borrarlo, si encuentra el usuario, lo elimina del panel.

**Nota importante: El nombre de usuario tiene que ser exactamente como se encuentra en el panel, cualquier variación como un espacio de más o una letra equivocada, hará que se trate como un usuario completamente nuevo.**

También desde aquí (Programación), podemos planificar códigos temporales para un solo panel. Elegimos “Abonado individual”, ponemos el número de abonado y le damos a “Buscar abonado”. Si tiene algún código temporal asignado aparecerá en la tabla. Se pueden añadir nuevos códigos temporales, eliminarlos o cambiar los datos y funcionará exactamente igual que con los códigos temporales de los grupos pero solo con el panel seleccionado.

Si en el desplegable “Directo/Programación” elegimos “Directo”, nos aparece una casilla para buscar el abonado (el panel con ese número de abonado):

Ponemos el número de abonado y pulsando en “Buscar Abonado”, si encuentra el abonado en los Abonados INTRUSIÓN, nos refleja todos los usuarios del panel. Desde aquí, haciendo doble click sobre un usuario podemos asignarle un nuevo código (no podemos leer el código anterior por protección de datos). También podemos añadir un nuevo usuario o borrar uno existente (excepto los usuarios master e installer).

#### 2.3.8. Zonas Central <a href="#refheading___toc4816_1729251194" id="refheading___toc4816_1729251194"></a>

Visualizamos las zonas y dispositivos del panel. Para asegurarnos de que no ha habido cambios en la configuración de zonas podemos hacer click en el botón _Refrescar Zonas (se leen las zonas del panel)._ Cuando seleccionamos con doble-click una zona podemos asignarle una cámara de un grabador:

En este caso, cuando se dispare la zona 3 del panel, se descargará un vídeo de la cámara 2 del vídeo-grabador con número de abonado 9986. Se pueden asignar varias cámaras a una misma zona (y se descargará un vídeo de cada una de ellas cuando se dispare la zona) y asignar una misma cámara a varios canales (si ya se está descargando vídeo cuando salte la otra zona a la que está asignado el canal, no se descargará de nuevo el vídeo). Cuando pulsamos en _Seleccionar Cámara,_ se abre el programa Operador, vamos al Grabador que queremos, visualizamos la cámara en concreto y con el botón derecho damos click al menú _Seleccionar cámara_ que aparece:

#### 2.3.9. **Datos Abonados** <a href="#refheading___toc4854_1729251194" id="refheading___toc4854_1729251194"></a>

Gestión de los datos de los abonados de intrusión.

Asignamos un nombre, dirección, población, provincia, teléfono y email. Estos datos podrán ser consultados en el Tratamiento de Alarmas del programa Operador, para facilitar la gestión de los eventos.

También se añaden contactos con su nombre, teléfono, email y orden de llamada, y aparecen diferentes estados internos de los abonados de intrusión.

#### **2.3.10. Parámetros IA** <a href="#refheading___toc5239_4106682935" id="refheading___toc5239_4106682935"></a>

Ajustamos los umbrales de detección de humano, umbral de confirmación de intrusión, el modelo de predicción utilizado y el tiempo que espera el sistema al análisis (si no se mostrará la imagen sin analítica):

Vemos en la imagen que podemos configurar el “Nivel de Detección”, un parámetro entre 0-1 que determinará el umbral a partir del cual se considera un humano correctamente identificado. Cuanto más se acerca a 1 mayor es la exigencia de la detección. El valor recomendado por defecto es 0.4 pero puede ser necesario aplicar otros valores en determinados escenarios e imágenes.

Igualmente se configura el “Nivel de Confirmación”, también entre 0-1, que es el nivel que considera el sistema para dar una imagen cono Intrusión confirmada. Cuanto más se acerque a 1 mayor exigencia en la confirmación de una detección como positiva.

En “Modelo de Predicción” asignamos el modelo que utilizará la IA para analizar las imágenes. Se irán añadiendo modelos para adaptarlos a distintos escenarios (interior, montaña, playa, etcétera).

El “Timeout Proceso” es el tiempo límite que espera el sistema a obtener la imagen ya analizada. Si pasado este tiempo no se obtiene respuesta, se continuará con la imagen original sin analizar.

Podemos ver el funcionamiento de estos parámetros cargando una imagen de prueba con el botón “Carga Imagen de Pruebas”. Una vez cargada le damos a “Analizar” y veremos los distintos niveles de detección de humanos y vehículos:

Como vemos en este caso la alarma estaría confirmada porque el nivel de confirmación está configurado a 0.57 y la persona se detecta con una precisión del 0.61. Si cambiamos este nivel a 0.65 para probar:

Ya vemos que evidentemente el análisis es el mismo pero ahora no se da la alarma como confirmada porque 0.61 es menor del valor de confirmación configurado, 0.65.

Igualmente si subimos el nivel de detección a 0.63 ni tan solo nos pintará el recuadro en la persona porque considera que no tiene el nivel suficiente para indicar que es una persona:

A parte de esta imagen genérica de pruebas, podemos pedir una imagen de la propia instalación con el botón “Pedir Imagen Instalación”. Veremos que no aparece el VisorHTML desde donde podemos hacer una petición de imagen por ejemplo de un pircam. Con la particularidad que se almacenará una imagen analizada (puesto que tenemos la anlítica en marcha) pero también una imagen virgen sin analizar, que podemos usar para configurar con más precisión los parámetros con la imagen de la propia instalación. Después de hacer la petición pulsamos en “Cargar Imagen Instalación” y elegimos la última imagen guardada en el directorio de abonado y cuyo nombre finaliza por NonIA (la imagen tendrá un nombre del estilo 2023.09.13.08.27.44.435.P1.Z3\_NonIA.JPG).

#### **2.3.11. Nuevos Códigos VESTA** <a href="#toc1088" id="toc1088"></a>

Cuando el sistema detecta que los panales de la familia Vesta están utilizando nuevos códigos, se activa el botón !!NUEVOS CÖDIGOS VESTA!!:

Pulsamos sobre el botón para ver los nuevos códigos y sus definiciones:

Podemos Copiar Códigos, para pagarlos en un documento para darlos de alta en nuestro sistema, Cancelar, con lo cual seguirá activo el botón de nuevos eventos y los avisos, o “No volver a mostrar hasta que aparezcan nuevos”, nos damos por enterados de los nuevos códigos y desaparece el aviso.

### &#x20;Ge2.4. Alarmas <a href="#toc84228613" id="toc84228613"></a>

Gestión de los parámetros referentes a Eventos y Alarmas de los equipos.

#### &#x20;2.4.1. Acciones <a href="#toc84228614" id="toc84228614"></a>

Listado de acciones que se pueden asignar a una alarma que haya saltado en el programa Operador, si los eventos son enviados a esta aplicación. Para agilizar el tratamiento de la alarma se asignan acciones predeterminadas (disposiciones) que se definen en este apartado:

Con el botón de _Nuevo_ preparamos la edición. Introducimos la acción deseada y pulsamos en _Guardar._ Si hacemos doble-click en la tabla superior podemos modificar o _Borrar_ acciones ya existentes.

#### &#x20;2.4.2. Pasarela <a href="#toc84228615" id="toc84228615"></a>

Los eventos de los equipos pueden ser enviados al software de control de la CRA mediante unos protocolos propios de cada programa. Pero los eventos se codifican mediante unos códigos estandarizados. Los más conocidos son ContactctID y SIA. En esta tabla podemos personalizar estos códigos para adaptarlos al estándar o para sincronizarlos con los códigos que entienda correctamente el software de gestión de CRA. Posteriormente, cada uno de estos códigos puede ser asignado a los eventos que deseemos mandar al software de CRA, por ejemplo, en Alarmas (para eventos genéricos del equipo) o en Alarmas por Canal, para gestionar eventos de cada cámara o canal.

En esta tabla aparecen todos los códigos con su descripción. Haciendo doble-click sobre uno de ellos podemos editarlo:

Cambiar, el código que se envía en _Código Manitou,_ cambiar la _Descripción de Alarma,_ que será el texto que nos aparecerá para elegir en la definición de eventos.

Podemos borrar el código con el botón _Borrar._

Podemos añadir un código con su descripción con el botón _Nuevo._

#### &#x20;2.4.3. Listado <a href="#toc84228616" id="toc84228616"></a>

Los eventos de los equipos se pueden enviar al software de CRA o al programa operador, pero también quedan registrados en el sistema AlarmSpace. En este listado se pueden consultar estos eventos por días:

#### &#x20;2.4.4. Eventos DVRs <a href="#toc84228617" id="toc84228617"></a>

Los eventos de los equipos se pueden enviar al software de CRA o al programa operador, pero también quedan registrados en el sistema AlarmSpace. En este listado se pueden consultar, ordenar, filtrar y exportar estos eventos:

Filtro por fecha en los desplegables _Entre, y._

Aplicar filtro por Número de abonado, Número de serie o Descripción del equipo en el desplegable _Quitar filtro._

Filtrar por tipos de eventos en _Tipo evento._

Con el botón _Refrescar_ refrescamos los datos para los filtros aplicados.

Los botones de la derecha exportan los datos que están en ese momento filtrados a CSV/Excel y a PDF.

Este listado también puede visualizarse desde la aplicación _Operador_ en la pestaña _Alarmas_ desde el botón _Listado Eventos DVR_.

Este listado contiene campos adicionales en caso de contener dispositivos de incendio analógico. Se muestran el tipo de dispositivo, el Lazo, Dirección, Celda, Referencia, SubDirección, Descripción del Dispositivo, Descripción de la Zona y el Valor Analógico:

Igualmente, este listado ampliado se exporta completamente a Excel y Pdf.

#### 2.4.5. Programación Listados <a href="#refheading___toc8412_3540658743" id="refheading___toc8412_3540658743"></a>

Los listados se pueden mandar periódicamente por email. Mediante esa sección podemos programar distintos listados, a distintas horas y para distintos destinatarios:

En la tabla, aparecen los listados programados. Doble click sobre uno de ellos para modificarlo. Botón Nuevo para crear una nueva programación:

Configuramos un nombre para el listado, el Período (cada cuándo se enviará) en horas, la hora del envío, el email (emails separados por “;”) a los que se enviará. Visualizamos la hora del último listado enviado y la del próximo envío y podemos seleccionar los eventos que deseemos incluir en el listado:

Finalmente, podemos activar o desactivar el envío con el Check de “Activo”.

#### 2.4.6. **Códigos Intrusión** <a href="#refheading___toc4801_499769440" id="refheading___toc4801_499769440"></a>

Cuando se trabaja con el Operador de AlarmSpace para tratar Alarmas de Intrusión, el significado de los códigos recibidos de los paneles se define en las tablas que se presentan en este punto.

P

Podemos cambiar la descripción del evento, marcar si es un evento que requiere usuario en vez de zona (aperturas, cierres…), el color con el que aparecerá el evento (RGB pasado a decimal), en _display seleccionamos_ si el evento pasará por pantalla de control o si pasará directo al histórico, en _priority_

### &#x20;2.5. Configuración <a href="#toc84228619" id="toc84228619"></a>

Configuraciones generales del sistema completo de AlarmSpace.

#### &#x20;2.5.1. Parámetros Receptora <a href="#toc84228620" id="toc84228620"></a>

Parámetros de las comunicaciones con el software de recepción de eventos de la central de alarmas. Otros parámetros usados genéricamente por toda la aplicación:

\
**2.5.1.1. Parámetros generales**

Si se desea enviar correos electrónicos en algún evento, debemos tener configurado un servidor SMTP para posibilitar el envío (consultar con vuestro proveedor de correo electrónico). Los parámetros necesarios son:

SMTP USERNAME: nombre de usuario de la cuenta de correo

SMTP SERVER: servidor de SMTP

SMTP PASSWORD: contraseña de SMTP

SMTP FROM: dirección que constará como remitente en los correos enviados

ADMIN MAIL: dirección genérica a la que se enviarán los correos de administrador

Las imágenes y vídeos descargados por la aplicación se guardan localmente en la máquina de AlarmSpace. En este apartado definimos las rutas donde quedan almacenados:

RUTA CAPTURAS CLIENTE: almacén de las capturas realizadas manualmente cuando se visualiza una cámara en tiempo real o una grabación el en programa Operador

RUTA VÍDEOS CLIENTE: almacén de los vídeos descargador manualmente cuando se visualiza una cámara en tiempo real o una grabación el en programa Operador

RUTA VÍDEOS SERVIDOR: almacén de los vídeos descargados automáticamente por AlarmSpace cuando salta una alama de un canal.

\
**2.5.1.2. Comunicaciones con CRA**

Las comunicaciones con el software de CRA se configuran desde este apartado.

TIPO RECEPTORA: modelo de software utilizado en CRA para la recepción de alarmas. Valores posibles: Manitou, SBN, Softguard o compatibles.

MANITOU ACTIVE: si la comunicación está activa. Si no se marca, no se enviarán los eventos.

MANITOU PLANTILLA: informamos de la plantilla de códigos que utilizaremos para codificar los eventos: SIA O CID (ContactID)

MANITOU PORT: puerto TCP de escucha del software de CRA

MANTOU SERVER: ip de escucha del software de CRA

MANITOU LINE: línea identificadora de AlarmSpace como receptora. Algunos softwares de CRA son capaces de duplicar abonados que provienen de receptoras distintas

HEARTBEAT: periodo (en segundos) en el que se envía señal de latido o "estoy vivo" que manda AlarmSpace al software de CRA en el formato adecuado para informar de comunicación correcta.

CONVERT 2 AVI: con esta opción activada AlarmSpace intentará convertir todos los vídeos que se manden al formato estandarizado AVI

SEÑALES DESCONEXIÓN: número de veces que se manda al software de CRA la desconexión de un equipo (con o sin recepción de ACK/Confirmación)

SEND RETRIES: número de veces que se intentará volver a mandar cada señal si no se reciben ACK/Confirmaciones del software de CRA

AX HUB PASSWORD: clave para la sincronización de las centrales AX HUB de HIKVISION para la recepción de los vídeos de la central. Debe coincidir con la programada en la propia central (ver _Configuración central AXHUB -> Configuraciones especiales de la AXHUB -> Registro EHome_) Se puede personalizar luego en el apartado Contraseña de cada central que se ha dado de alta.

PUBLIC IP: para recibir los vídeos de la central AXHUB AlarmSpace funciona como receptora/pasarela, por ello debemos informar de la IP pública sobre la que hay que abrir los puertos 7660 y 8089. (ver _Configuración central AXHUB -> Configuraciones iniciales en AlarmSpace)_

\
**2.5.1.3. Otros parámetros**

INTERVALO SECUENCIA: intervalo de visualización de nuevo bloque de cámaras. Actualmente sin uso.

SERVICE CHECKDVR TIEMOUT: intervalo en segundos en que se realizará la comprobación de conexión de los equipos.

TIMEOUT ALARM STATUS: tiempo en minutos que no volvemos a considerar una alarma válida si es del mismo equipo y canal

INTERVALO SINCR. HORA: periodo de tiempo en segundos en el que se realiza una sincronización de la hora de los equipos que lo permiten

SONIDO ALARMA: sonido que emite el servidor de Alarmspace cada vez que envía una alarma.

RECEPTORA ACTIVA: sin este parámetro activo no se envían los eventos al software de CRA

SERVICE CHECK DISK SPACE: cantidad de espacio libre en el disco duro del servidor de AlarmSpace antes de avisar de poco espacio en disco.

REINICIAR SERVICIO SI OOM: reiniciar el servicio de chequeo de equipos de AlarmSpace si se produce un error de desbordamiento de memoria.

#### &#x20;2.5.2. Incorporar Licencias <a href="#toc84228624" id="toc84228624"></a>

Funcionalidad que permite incorporar nuevas licencias de centrales AXHUB para permitir la recepción de los vídeos que generen. Si una central no está en esta lista no será capaz de enrolarse en AlarmSpace. Para nuevas licencias contacte con el servicio técnico de ByDemes. **No usar sin indicación expresa de personal calificado de ByDemes.**

#### &#x20;2.5.3. Renovar Tablas Master <a href="#toc84228625" id="toc84228625"></a>

Funcionalidad que permite renovar las tablas de datos usados para distintas funciones por AlarmSpace. Básicamente se trata de añadir parámetros que no están en las tablas mediante ficheros subministrados por personal de ByDemes. **No usar sin indicación expresa de personal calificado de ByDemes.**

#### &#x20;2.5.4. Configuración Avanzada <a href="#toc84228626" id="toc84228626"></a>

Lista todos los parámetros de configuración de AlarmSpace. Permite la visualización de parámetros añadidos en futuras versiones. También permite la actualización de los parámetros mediante la edición en la propia tabla y el botón _Guardar._

Cada parámetro contiene su propia descripción. **No usar sin indicación expresa de personal calificado de ByDemes.**

| Nombre                                    | Valor                                                      | Descripción                                                                                                                                                  |
| ----------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ADMIN\_MAIL                               | alarmspace@bydemes.com                                     | Email Administración. Es el que recibe errores y alertas.                                                                                                    |
| ALLOW\_DELETE\_VESTA\_IN\_BACKEND         | false                                                      | Si es verdadero elimina el panel del backend de Vesta cuando se borra el panel en AlarmSpace                                                                 |
| ALLOW\_SERVICE\_RESTART\_ON\_OOM          | 0                                                          | Permitimos reiniciar el servicio en errores de falta de memoria                                                                                              |
| APEXIS\_SECONDS\_BETWEEN\_ALARMS          | 60                                                         | Segundos que pasan entre que se detecta una alarma y se vuelve a detectar de nuevo                                                                           |
| APEXIS\_STATUS\_RETRIEVAL\_INTERVAL       | 2                                                          | Valor en segundos del intervalo de peticiones de estado.                                                                                                     |
| AVISOS\_PASARELA\_DESCONEXION\_DVR        | 1                                                          | Numero de señales que se envían a la pasarela cuando detectamos desconexión de un DVR                                                                        |
| CHECK\_USE\_CPU                           | 1                                                          | Si es 1 reinicia servicio si uso de CPU supera LIMIT\_CPU\_USAGE                                                                                             |
| COMPANY\_EMAIL                            | alarmspace@bydemes.com                                     | Email de la empresa                                                                                                                                          |
| COMPANY\_NAME                             | ByDemes                                                    | Nombre de la empresa                                                                                                                                         |
| CONVERT\_2\_AVI                           | 1                                                          | Convertir los ficheros de alarma vía pasarela a formato avi antes de enviar                                                                                  |
| DAYS\_PRESERVE\_CERTIFICATES              | 30                                                         | Tiempo que se guardan los certificados automaticos en dias                                                                                                   |
| DAYS\_PRESERVE\_VIDEOS                    | 30                                                         | Los ficheros multimedia se borrarán pasados estos días de su creación.                                                                                       |
| DISABLE\_CERTS\_AUT\_SERVICE              | false                                                      | Deshabilita el servicio de generacion y envio de certificados automaticos                                                                                    |
| DISABLE\_FIRE\_SERVICE                    | false                                                      | No ejecuta el proceso de control de equipos de incendio                                                                                                      |
| DISABLE\_VTO\_SERVICE                     | false                                                      | No ejecuta el proceso de control de videoporteros                                                                                                            |
| EHOME\_KEY                                | 12345678                                                   | Password genérico para conexión centrales AXHUB                                                                                                              |
| FFMPEG\_PROGRAM\_FILE                     | C:\Program Files (x86)\ByDemes\AlarmSpace\utils\ffmpeg.exe | Convertir los ficheros de alarma vía pasarela a formato avi antes de enviar                                                                                  |
| FORCE\_MAINSTREAM\_FIRST                  | false                                                      | Mostrar Stream Principal por defecto en Operador                                                                                                             |
| FUEGO\_ANALOG\_LINEA                      | 17                                                         | Linea de Receptora para envío a Manitou de eventos de incendio analógico                                                                                     |
| FUEGO\_ANALOG\_PLANTILLA                  | HONA                                                       | Plantilla que se utizara en el EventType de Manitou para eventos de incendio analogico                                                                       |
| INTERVALO\_SECUENCIA                      | 30                                                         | Tiempo que transcurre entre cada bloque de secuencias de cámaras en el visor                                                                                 |
| IP\_SEARCH\_EVENT\_AS\_CAM\_DISCONNECTION | true                                                       | Autorizar evento DH\_IPSEARCH\_EVENT\_EX como desconexion de cámara                                                                                          |
| LIMIT\_CPU\_USAGE                         | 80                                                         | Porcentaje de uso de CPU a partir del cual se reinicia el servicio de grabadores                                                                             |
| LIMIT\_FREE\_MEMORY                       | 20                                                         | Porcentaje memoria libre a partir del cual se reinicia el servicio de grabadores                                                                             |
| LOGS\_DVRSERVICE\_PRESERVE                | 180                                                        | Días maximos que se guardan los logs del servicio de control de equipos                                                                                      |
| MANITOU\_ACTIVE                           | 1                                                          | Si VALOR = 1 el sistema se convertirá en un proxy para Manitou                                                                                               |
| MANITOU\_LINE                             | 1                                                          | Campo extra para enviar en la trama de pasarela. Aplicable a Manitou.                                                                                        |
| MANITOU\_PLANTILLA                        | SIA                                                        | Plantilla que se utilizará en el EventType de Manitou                                                                                                        |
| MANITOU\_PORT                             | 23505                                                      | Puerto del Host Manitou                                                                                                                                      |
| MANITOU\_RETRIES                          | 3                                                          | Número reintentos envío Software de CRA                                                                                                                      |
| MANITOU\_SERVER                           | 192.168.0.2                                                | Dirección del Host Manitou                                                                                                                                   |
| MAX\_AB\_FILES\_SIZE                      | 200                                                        | Maximo tamaño permitido por abonado                                                                                                                          |
| MAX\_FILES\_SIZE                          | 1000                                                       | Maximo tamaño de ficheros almacenados                                                                                                                        |
| OPTIMIZE\_FOR\_VESTA                      | false                                                      | Optimiza para VESTA. Atencion los servicios de otros dispositivos no funcionarán.                                                                            |
| P2P\_PROXY\_LISTEN\_PORT                  | 7000                                                       | Puerto socket en el que el servicio P2P está escuchando                                                                                                      |
| PERIODICAL\_DVRSERVICE\_RESTART           | 0                                                          | Reseteo Periodico Servicio DVR                                                                                                                               |
| PERIOD\_NOTIFICATIONS                     | 10                                                         | Tiempo de repetición de los mensajes de Telegram                                                                                                             |
| PUBLIC\_IP                                |                                                            | IP Publica para la recepción de eventos de la central AXHUB                                                                                                  |
| RECEPTORA\_ACTIVA                         | 1                                                          | Permite recibir alarmas desde el programa de recepción de video                                                                                              |
| RECEPTORA\_HEARTBEAT                      | 60                                                         | Número de segundos                                                                                                                                           |
| RECEPTORA\_HEARTBEAT\_LAST\_KO\_TIME      |                                                            | Ultima vez que detectamos la receptora en ko                                                                                                                 |
| RECEPTORA\_HEARTBEAT\_LAST\_OK\_TIME      | 2017-01-14 18:01:26                                        | Ultima vez que detectamos la receptora en ok                                                                                                                 |
| RECEPTORA\_HEARTBEAT\_STATUS              | OK                                                         | Valores OK-KO                                                                                                                                                |
| RUTA\_CAPTURAS\_CLIENTE                   | C:\AlarmSpace2Shared\Fotos                                 | Ruta padre en la que se guardan las capturas de los videos captados por el programa cliente                                                                  |
| RUTA\_VIDEOS\_CLIENTE                     | C:\AlarmSpace2Shared\Videos                                | Ruta padre en la que se guardan los videos captados por el programa cliente                                                                                  |
| RUTA\_VIDEOS\_SERVIDOR                    | C:\AlarmSpace2Shared\Servidor                              | Ruta padre en la que se guardan los videos de los DVRs                                                                                                       |
| SDK\_VENUS                                | 1                                                          |                                                                                                                                                              |
| SERVER\_ADDRESS                           | 192.168.1.21:8003                                          | Dirección del webService                                                                                                                                     |
| SERVICE\_CHECKDVR\_TIMEOUT                | 30                                                         | Segundos que el Servicio deja pasar para revisar la lista de DVRs                                                                                            |
| SERVICE\_CHECK\_DISK\_SPACE               | 10                                                         | Valor en porcentaje de espacio que ha de quedar libre antes de mostrar una advertencia                                                                       |
| SERVICE\_SYNCRDVR\_TIMEOUT                | 3600                                                       | Tiempo para sincronizar horas                                                                                                                                |
| SERVICIO\_GC\_TIMER                       | 10                                                         | Segundos entre recolección de memoria por el GarbageCollector                                                                                                |
| SHOW\_PROTOCOL\_CODIFICATION              | false                                                      | Muestra el estandar utilizado para los codigos de eventos de intrusion                                                                                       |
| SHOW\_PSW\_DVR\_LIST                      | false                                                      |                                                                                                                                                              |
| SMTP\_FROM                                | alarmspace@bydemes.com                                     | Muestra la columna password decodificada en el control de DVR                                                                                                |
| SMTP\_PASSWORD                            | xxxxxxxxxxx                                                |                                                                                                                                                              |
| SMTP\_SERVER                              | smtp.office365.com                                         |                                                                                                                                                              |
| SMTP\_USERNAME                            | alarmspace@bydemes.com                                     |                                                                                                                                                              |
| SMTP\_USE\_SSL                            | true                                                       | Usar encriptacion SSL en el envio de correos por SMTP                                                                                                        |
| SONIDO\_ALARMA                            | alarm\_2.wav                                               | Fichero de audio que sonara al recibir una alarma el cliente. Ha de estar dentro de AppPath+CarpetaWav                                                       |
| TELEGRAM\_TOKEN                           |                                                            | Telegram Bot Token used for Telegram Notifications                                                                                                           |
| TIEMPO\_DESCONEXION\_CAMARA               | 30                                                         | Tiempo que espera el sistema para confirmar la desconexión de una cámara                                                                                     |
| TIEMPO\_DESCONEXION\_DVR                  | 135                                                        | Tiempo que espera el sistema para confirmar la desconexión de una DVR                                                                                        |
| TIME\_FIND\_RECORDINGS                    | 120                                                        | Minutos en los que buscaremos grabaciones para el certificado automatico completo                                                                            |
| TIMEOUT\_ALARM\_STATUS                    | 1                                                          | Tiempo en minutos que permitimos al servicio ignorar una alarma en un canal si no ha variado de estado activo desde la primera vez que se procesó la alarma. |
| TIME\_ALARMS\_CLOSING                     | 0                                                          | Minutos en los que se cerrará automáticamente una alarma (0 para no cerrar)                                                                                  |
| TIPO\_RECEPTORA                           | 0                                                          | 0 = Manitou, 1 = SBN                                                                                                                                         |
| UPLOAD\_ALARM\_COLOSO\_EVOLUTION\_PORT    | 55550                                                      |                                                                                                                                                              |
| USE\_MANITOU                              | 0                                                          | Si VALOR = 1 el sistema se convertirá en un proxy para Manitou                                                                                               |

#### 2.5.5. Panel de Control <a href="#refheading___toc8430_3540658743" id="refheading___toc8430_3540658743"></a>

El Panel de Control muestra el estado de los servicios de AlarmSpace y permite reiniciarlos, pararlos, deshabilitarlos y volver a habilitarlos:

Si se deshabilita un servicio, este dejará de funcionar y no se reiniciará en ningún momento (ni tan solo con el reinicio del servidor). La única forma de volver a ponerlo en marcha en volver a Habilitar el servicio.

**NOTA IMPORTANTE: use este módulo con cuidado y solo si está seguro de sus consecuencias. Un mal uso de este módulo puede suponer un mal funcionamiento global del software AlarmSpace.**

#### 2.5.6. Visor de Logs <a href="#refheading___toc8432_3540658743" id="refheading___toc8432_3540658743"></a>

Los distintos servicios de AlarmSpace generan distintos logs. Esta herramienta permite visualizar todos estos logs en tiempo real. Solo hay que seleccionar en el desplegable el servicio que se desea monitorizar y se irá refrescando el log correspondiente:

#### 2.5.7. **Certificados** A**utomáticos** <a href="#refheading___toc5067_3394744638" id="refheading___toc5067_3394744638"></a>

Parámetros generales de configuración de certificados automáticos:

| Nombre                       | Valor | Descripción                                                                       |
| ---------------------------- | ----- | --------------------------------------------------------------------------------- |
| DAYS\_PRESERVE\_CERTIFICATES | 30    | Tiempo que se guardan los certificados automaticos en dias                        |
| DISABLE\_CERTS\_AUT\_SERVICE | false | Deshabilita el servicio de generacion y envio de certificados automaticos         |
| TIME\_FIND\_RECORDINGS       | 120   | Minutos en los que buscaremos grabaciones para el certificado automatico completo |

#### 2.5.8. **Instancias P2P Dahua** <a href="#refheading___toc5122_2053723952" id="refheading___toc5122_2053723952"></a>

Permite definir distintas instancias de los servicios P2P Dahua de AlarmSpace para paralelizar el procesado. Las instancias se pueden ejecutar en la misma máquina del servidor o en cualquier máquina de la red LAN.

Para iniciar una nueva instancia utilizamos el botón “Nuevo”. Llenamos los paámetros de Ip (la ip privada de la máquina en la que se va a ejecutar el servicio), port (el puerto que va a utilizar el servicio), si está activo o no, y el tipo de P2P (“bydemes” para equipos Dahua con firmware ByDemes y “dahua” para los que tienen firmware original de Dahua). Después guardamos y el sistema se encargará de iniciar el nuevo servicio y de balancear equitativamente los equipos a través de los distintos servicios paralelizados. Hay que tener en cuenta que si el servicio se quiere ejecutar en una instancia distinta del Servidor de AlarmSpace, hay que instalar el software “AlarmSpace2 P2P Services Installer” manualmente.

### 2.6. Copias de Seguridad <a href="#refheading___toc8434_3540658743" id="refheading___toc8434_3540658743"></a>

Gestión de importaciones y exportaciones de datos de la base de datos.

#### 2.6.1. Importar/Exportar <a href="#refheading___toc8436_3540658743" id="refheading___toc8436_3540658743"></a>

Exporta a un fichero el contenido de la base de datos. El fichero permite la recuperación total de los datos de la base de datos en un sistema nuevo. Seleccionamos la carpeta de destino con el botón con tres puntos y le damos a procesar:

Se nos genera el fichero de backup en el directorio seleccionado.

Si elegimos la pestaña Importar, recuperamos los datos del fichero que seleccionamos y los incorporamos a la actual instalación de AlarmSpace.

**NOTA IMPORTANTE: La importación de los datos de un fichero de backup elimina los datos que contenga la base de datos y los sustituye por los datos del backup. Use esta funcionalidad solo en caso de pérdida importante de datos y teniendo en cuenta que los datos añadidos posteriormente se perderán.**

#### 2.6.2. Configurar <a href="#refheading___toc8438_3540658743" id="refheading___toc8438_3540658743"></a>

Las copias de seguridad de la base de datos pueden ser realizadas periódicamente mediante este módulo:

En este módulo elegimos donde guardar las copias, tenemos que “Activar Programación Periódica”, elegimos cada cuanto tiempo la realizamos y seleccionamos en qué fecha empezamos las copias. También podemos eliminar copias anteriores a los días seleccionados, para no tener problemas de ocupación de discos.

Podemos seleccionar las tablas para la copia. En este sentido es importante conocer que AlarmSpace crea tablas por fechas para que las tablas de la base de datos no crezcan indiscriminadamente. Cuando una tabla llega a un límite, se crea una tabla nueva y la antigua se renombra. Podemos seleccionar no copiar estas tablas antiguas, la copia será más liviana y tendremos igualmente todos los datos guardados. Para no copiar las tablas antiguas debemos quitar el Check de los puntos “all” y “old\_tables”:

#### 2.6.3. **Limpieza** <a href="#refheading___toc8440_3540658743" id="refheading___toc8440_3540658743"></a>

Para disminuir el volumen de la base de datos podemos limpiarla con esta nueva funcionalidad. Consiste en eliminar tablas antiguas de las que ya no necesitamos los datos (y que podemos tener en backups antiguos). Distinguiremos las tablas antiguas porque se les añade un numeración. Así pues, por ejemplo la tabla alarms va generando tablas antiguas de la forma alarms\_0000000001, alarms\_0000000002, … Estas tablas que tienen la numeración se pueden ir eliminando y no van a afectar en el correcto funcionamiento del programa.

### 2.7. Idiomas <a href="#refheading___toc8442_3540658743" id="refheading___toc8442_3540658743"></a>

Permite el cambio de idioma de la plataforma AlarmSpace. Hasta el momento están disponibles los idiomas siguientes:

Al realizar un cambio de idioma se nos pide reiniciar el Servidor para refrescar los cambios.

### 2.8. Ayuda <a href="#refheading___toc8444_3540658743" id="refheading___toc8444_3540658743"></a>

En el apartado ayuda encontramos información sobre la versión y licencias de AlarmSpace y distintos documentos de ayuda disponibles para la plataforma. También podemos buscar si hay disponibles actualizaciones de la versión de la plataforma AlarmSpace:

### 3. Módulo Operador <a href="#topic_modulooperador" id="topic_modulooperador"></a>

Módulo de visualización de cámaras en tiempo real, visualización y descarga de grabaciones y tratamiento de alarmas. Este módulo actúa como cliente del módulo Servidor, de manera que se puede instalar en varias máquinas que atacarán a la máquina servidora. Es de utilización simultánea por varios operadores.

### &#x20;3.1. Login <a href="#toc84228635" id="toc84228635"></a>

Para entrar en el módulo Operador debemos subministrar un usuario de AlarmSpace válido, de cualquier nivel.

El usuario operador por defecto tiene contraseña 12345. Se puede cambiar y crear más usuarios operadores desde el Servidor de AlarmSpace en el menú Usuarios

Podemos usar el _Auto Login_ que, en la próxima carga del programa Operador en esta máquina nos rellenará los campos _Usuario_ y _Contraseña_ con los últimos valores utilizados, de manera que no hará falta rellenar los datos de usuario y contraseña para entrar rápidamente en la aplicación. Para revertir el AutoLogin hay que arrancar el Operador con el parámetro STOPAUTO.

También se puede acceder al Operador facilitando el usuario y la contraseña y un abonado en concreto por línea de comandos:

"C:\Program Files\ByDemes\AlarmSpace2 Client Module\AppOperador.exe" -user operador -pwd 12345 -ab 1234

Esta sentencia inicia el módulo Operador con el usuario “operador”, con password “12345” y solo con las cámaras del abonado “1234”. Podemos usar solo alguno de los parámetros, por ejemplo si no ponemos el parámetro -ab, se abrirá con todos los equipos asignados al usuario.

Utilizando el parámetro de línea de comandos -cert el Operador no se abrirá, solo generará al vuelo un certificado de cámaras de un abonado. Para que esta opción funcione, debemos añadir también los parámetros ya mencionados -user y -pwd para validar el usuario de acceso. Si usamos el parámetro -ab nos generará el certificado de ese abonado, si no, nos pedirá que introduzcamos el número de abonado:

Podemos usar el parámetro -cert sin argumentos o indicarle a continuación la ruta donde se guardará el certificado. Si no se pone la ruta se guardará en la carpeta asignada al grupo al que pertenece el equipo o si no tiene grupo asignado en la ruta por defecto (p.e. "C:\Program Files\ByDemes\AlarmSpace2 Client Module\AutoCerts”). En el certificado también se pueden listar las grabaciones de cada uno de los canales, eso se consigue añadiendo el parámetro -minFindRecord XXX, que indica los minutos de grabaciones que queremos buscar. Un ejemplo simple de línea de comandos para generar un certificado al vuelo:

"C:\Program Files\ByDemes\AlarmSpace2 Client Module\AppOperador.exe" -cert -user operador -pwd 12345 -ab 1234

Y un ejemplo fijando la ruta del certificado en C:\CertificadosDVR\DVR1234 y buscando 120 minutos de grabaciones:

"C:\Program Files\ByDemes\AlarmSpace2 Client Module\AppOperador.exe" -cert C:\CertificadosDVR\DVR1234 -user operador -pwd 12345 -ab 1234 -minFindRecord 120

El módulo Operador nos muestra en la ventana de acceso la versión de Operador que estamos ejecutando. Es recomendable que esta versión corresponda con la versión que se esté ejecutando en el servidor de AlarmSpace, si no algunas funcionalidades podrían no realizarse correctamente.

La primera vez que iniciamos un Operador hay que configurar la dirección del servidor (para informar al Operador de dónde debe conectarse). Esto se hace mediante el botón _Configuración:_

Aquí debemos introducir la Ip del Servidor de AlarmSpace, seguida de dos puntos (:) y el puerto 8003 (por defecto, se puede cambiar en la configuración del servidor). Si la comunicación es correcta después de _Aceptar_ nos aparece la confirmación:

Si falla, también se nos indica y como consecuencia no podremos trabajar correctamente con el Operador hasta que solucionemos el problema:

Hay que poner correctamente la Ip del servidor y el puerto indicado. Si aun así el problema persiste, hay que contactar con el personal técnico de ByDemes.

### &#x20;3.2. Tiempo Real <a href="#toc84228636" id="toc84228636"></a>

Mediante la pestaña _Tiempo Real_ visualizamos cámaras en tiempo real. Se pueden activar varias cámaras a la vez de un mismo grabador o de varios.

En el panel de la izquierda aparece un panel con distintas pestañas.

En la pestaña DVR aparece la lista de todos los equipos con la posibilidad de expandir las cámaras de cada equipo, solo los equipos/cámaras que estén asignadas al usuario en el _Módulo Servidor -> DVR -> DVR por Usuario_

La lista se hace por descripción del equipo. Con el botón _Listar DVR's por Abonado_ vemos la lista por número de abonado. Volviendo a pulsarlo volvemos a ver los equipos por su descripción.

Con doble-click sobre una cámara la visualizamos en tiempo real. Con doble-click sobre un grabador se visualizan todas las cámaras del equipo.

Si seleccionamos una de las visualizaciones nos aparecen opciones disponibles sobre lo que estamos visualizando:

En  descargamos el vídeo que estamos visualizando.

En hacemos una captura de la imagen en ese momento.

En escuchamos el sonido del equipo si tiene esa opción.

En activamos el micro para hablar con el equipo.

En encontramos la función “Instant Replay”, reproduce la grabación de la cámara 5 minutos antes

En  hacemos un zoom de cualquier parte de la visualización de la cámara, seleccionado con el ratón.

En limpiamos la pantalla y dejamos de visualizar la cámara.

En la parte inferior tenemos la opción de limpiar todas las cámaras que estamos viendo y de recargar los equipos del usuario:

Con el botón derecho sobre un grabador nos aparece un menú contextual con distintas opciones:

_Activar Stream Principal_ pasa la visualización de las cámaras al modo con más resolución llamado Stream Principal

_Activar Substream_ pasa la visualización al modo de resolución reducida Substream, permite no sobrecargar el canal de comunicación del cliente y de AlarmSpace

_Gestionar Relés_ nos abre las salidas de relé disponibles en el equipo y nos permite activarlos y desactivarlos:

Marcamos el estado de los relés que deseamos y pulsamos en el botón _Modificar Estado Relés._

_Certificado Cámaras_ nos realiza una captura del estado de todas las cámaras del equipo que puede funcionar como certificado de instalación o revisión. Nos pregunta en que carpeta guardar el certificado y las cámaras que queremos capturar (por si algunos canales no se utilizan, por defecto todos los canales del DVR). Además, podemos añadir un comentario manualmente en el certificado:

Si el certificado se ha generado correctamente veremos la confirmación:

Y obtendremos el certificado en la ruta indicada:

El logotipo es sustituible por un _.bmp_ de resolución parecida al que tenemos en _C:\Program Files\ByDemes\AlarmSpace2\LogoCert\LogoClient.bmp._ Para cambiarlo substituimos el fichero LogoClient.bmp por el nuevo .bmp con ese mismo nombre.

El certificado también muestra los eventos que ha tenido el equipo las últimas 24 horas, para ver por ejemplo las pruebas que se han realizado en la instalación o mantenimiento:

_“Certificado Completo de Cámaras”_ genera un certificado exactamente igual que el anterior, pero incluye un listado completo de las distintas grabaciones de todas las cámaras activas del último mes:

“_Visor Cámaras”_ abre la aplicación Visor Camaras, que muestra la cámara seleccionada y una grabación de 30 segundos antes.

La pestaña _PTZ_ permite distintas opciones sobre la cámara si es que esta es ajustable y motorizada:

_Step/Speed_ ajusta el paso de los cambios, cuanto más alta más rápido se realizarán.

Con las flechas movemos la cámara hacia las distintas direcciones.

Con _Zoom_ ampliamos o reducimos la imagen.

Con _Focus_ acercamos o alejamos el punto de enfoque de la cámara.

Con _IRIS_ abrimos o cerramos el iris de la cámara para ajustar la cantidad de luz que percibirá.

La pestaña _Preset_ permite ejecutar las distintas acciones que el equipo tenga definido en sus pre-sets:

Elegir el número de _Preset_ y pulsar _Ejecutar._

La pestaña _Filter_ aplica filtros a los equipos que se visualizan en la pestaña DVR. Podemos filtrar aplicando un _Filtro General_ con lo que filtramos por _Tipo DVR_ (ColosoEvo, Dahua, Hivision, HyundaiNextGen...), por _Tipo conexión,_ tipo de conexión preferida: directa o P2P y por _Grupo:_ mostrará solo los equipos que tengan asignado ese grupo en el _Módulo Servidor -> DVR -> Lista -> Datos Generales_.

En este caso solo se mostrarían los equipos del GRUPO 1. Observar que cuando un filtro está aplicado aparece una (F) al lado del título _Filter,_ para tener claro que no se muestran todos los equipos asignados al usuario sino solo los que permite el filtro seleccionado.

#### 3.2.1. Incendio <a href="#topic_incendio" id="topic_incendio"></a>

Cuando el equipo es del tipo Central de Incendio convencional al hacer doble click nos aparece esta ventana:

Vemos todas las zonas de la central, con las alarmas y averías activas en cada una. Si pasamos por encima de una zona nos da la alarma actual, la temperatura de la central, la tensión de entrada de red y de salida auxiliar, la tensión de la batería y la tensión de la propia zona. También un histórico de los últimos eventos de la zona.

Distingue entre alama de detector y de pulsador y avería de cortocircuito y de circuito abierto.

Vemos el estado del zumbador interno, de las averías del sistema y de las sirenas, con sus historiales. Además, vemos un historial general con todos los eventos sucedidos recientemente y podemos silenciar remotamente el zumbador interno de la central.

Con el botón derecho sobre el equipo nos sale la opción de _Generar Certificado,_ que nos crea un certificado con los estados y tensiones de toda la central asimismo como unos gráficos con la evolución temporal de los estados en los que ha estado la central en el período seleccionado.

#### &#x20;3.2.2. Video-porteros <a href="#toc84228638" id="toc84228638"></a>

Cuando se produce una llamada de un video-portero correctamente configurado en el módulo servidor para enviar la llamada al Operador, nos aparece una pantalla emergente como esta mientras suena un timbre de aviso:

En ella vemos la cámara del VTO. A continuación, iniciamos conversación con el botón _Iniciar Conversación,_ podemos _Abrir Puerta, Abrir Segunda Puerta, Parar Timbre._

La _opción Liberar Llamada_ se utiliza por si este Operador no puede atender la llamada en este momento, aunque la haya cogido, la puede liberar y aparecerá en todos los operadores abiertos de nuevo, pudiéndola coger otro Operador. Finalmente, para terminar la llamada podemos usar _Terminar Conversación_ (no cierra la ventana) o _Cerrar Ventana,_ que termina y cierra la ventana simultáneamente.

Si hay más de una llamada al mismo tiempo, aparecerá primero una y cuando se cierre aparecerá la siguiente. En caso de tener más de un operador activo, aparecerá la primera llamada en todos los operadores y cuando uno inicie conversación aparecerá la siguiente en los otros operadores, de manera que con vario operadores se pueden tratar varias llamadas a la vez.

#### 3.2.3. Incendio Analógico <a href="#refheading___toc8456_3540658743" id="refheading___toc8456_3540658743"></a>

Cuando el tipo de equipo es “Honeywell Analógico”, nos aparece la siguiente pantalla:

Tenemos una visión general de la central. Si pasamos por encima de los iconos nos sale el historial de cada dispositivo. En _Historial General_ un histórico general. En la parte izquierda, podemos realizar consultas de los dispositivos. Si no completamos ningún dato y pulsamos el botón consultar  nos devolverá toda la configuración de la central. Si en el desplegable del lado de configuración elegimos por ejemplo los dispositivos _En Test_ nos devuelve solo los dispositivos que estén en test. Si elegimos un _Lazo,_ un _Tipo_ y ponemos una dirección, nos devuelve una información más precisa del dispositivo en concreto. Si ponemos una zona (y borramos la dirección, que tiene preferencia) nos devuelve información del dispositivo que tenemos en esa zona. Con el botón derecho sobre el botón consultar nos aparece (previa contraseña de administrador) un menú con opciones bidireccionales:

Podemos anular zonas, ponerlas en test y volverlas al estado normal. También con el botón derecho sobre el icono de _Avería Sistema_ podemos rearmar la central:

Si hacemos click con el botón derecho sobre el dispositivo nos aparece un menú en el que podemos generar un pdf con toda la configuración de la central:

### &#x20;3.3. Vídeo <a href="#toc84228640" id="toc84228640"></a>

Mediante la pestaña vídeo buscamos grabaciones del canal seleccionado filtrando por distintos criterios:

Filtramos por las fechas deseadas y por el tipo de evento que ha provocado la grabación del archivo de vídeo: todos, por alarmas externas, por detección de movimiento, por cualquier alarma o por distintas con consultas.

Con el botón _Consultar_ nos aparecen en la derecha todas las grabaciones disponibles según los filtros seleccionados:

Doble-click sobre una de las grabaciones que aparecen y nos reproduce el vídeo asociado:

Durante la reproducción tenemos distintas opciones:

&#x20;pausa y reanudar la reproducción.

detener totalmente la reproducción, la pantalla se queda en negro.

&#x20;avance/retroceso rápido/lento y por fotogramas.

&#x20;descargar un vídeo de lo que se está visualizando.

&#x20;capturar la pantalla en una imagen de lo que se está visualizando en ese momento.

&#x20;barra de selección de tiempo, nos lleva justo al segundo deseado del vídeo. Podemos descargar a partir de ese segundo.

En la pestaña _Capturas_ podemos visualizar las capturas de imágenes que tengamos almacenadas localmente en el equipo, en la ruta que tengamos programada en _Módulo Servidor -> Configuración -> Parámetros Receptora -> Parámetros generales_ (en RUTA CAPTURAS CLIENTE):

### &#x20;3.4. Alarmas <a href="#toc84228641" id="toc84228641"></a>

La pestaña Alarmas se utiliza para gestionar alarmas recibidas de los equipos. Los eventos de los equipos se pueden mandar al software de CRA si están programados como _Enviar Alarmas por pasarela_ o bien enviarse al Operador si está marcada la opción _Enviar Alarmas a verificación de vídeo._

En este último caso las alarmas aparecen en el módulo de alarmas de todos los operadores cuyos usuarios tengan el equipo asignado:

Seleccionamos la alarma de _Alarmas Activas._ Si tiene vídeos asociados podemos reproducirlos: si tiene vídeo pre-alarma y/o vídeo post-alarma los visualizamos seleccionando el check correspondiente. Podemos pausar la reproducción, reanudarla, pararla totalmente, avanzar más rápido, retroceder y tomar una captura de pantalla de cualquier momento. También nos muestra una captura del momento de la alarma en _Captura de la alarma._

Una vez seleccionada le damos al botón _Procesar Alarma,_ veremos que nos lleva a la pestaña de _Tiempo Real_ para visualizar la cámara en directo. Volvemos a la pestaña _Alarmas_ y seleccionamos una acción asociada al tratamiento de la alarma que saldrá en el combo desplegable _Acción._ Las acciones de este desplegable se crean en el _Servidor de AlarmSpace -> Alarmas -> Acciones._ Para asociar la acción a la alarma pulsamos el botón _Guardar Acción._ Ponemos un comentario en el espacio reservado para ello (debajo de _Procesar Alarma_). Finalmente procesamos el evento con el botón _Procesar Alarma._

En el botón _Listado Eventos DVR,_ nos aparece el listado de eventos de los equipos de AlarmSpace, con posibilidad de filtrar por diversos criterios y exportar a excel/CSV y PDF. Para más detalles ver _Módulo Servidor -> Alarmas -> Eventos DVRs._

#### 3.4.1. Alarmas Intrusión <a href="#toc84228642" id="toc84228642"></a>

El módulo de Alarmas del Operador ahora es capaz también de recibir alarmas de intrusión de las centrales Vesta. Para que se reciban en el Operador hay que poner en la Configuración pasarela VESTA, en el apartado de ComputerProtocol (Protocolo de salida) el tipo OPERADOR:

Una vez esté configurado, vemos que los eventos de los paneles de intrusión nos aparecen en el Operador:

Los tratamos igual que en el caso anterior, añadiendo una acción y guardándola y poniendo un comentario. A la hora de guardar podemos guardar solo el evento que estamos procesando o _Cerrar Todas Abonado_ para guardar todos los eventos del abonado. En el Operador también podemos ver el _Listado Eventos DVR_

Eventos DVRs, que también incluye los eventos de intrusión y entrar en el mantenimiento de _Abonados INTRUSIÓN_.

Los eventos se pueden configurar con distintos colores, según el grado de importancia que queramos darles, y se pueden ordenar por prioridades. También se pueden elegir los eventos que pasan por pantalla o van directos al histórico.

En la parte derecha superior vemos los datos asignados al abonad (nombre, dirección, población, provincia, teléfono y email).

Pulsando en el botón _Contactos_ vemos los contactos asignados al abonado (nombre, teléfono,email), ordenados por el _Orden_ que hayamos establecido en Datos Abonados:

En _Estados_ vemos los estados disponibles del Abonado:

Y en _Zonas,_ las zonas detectadas en el panel:

Si hay un evento de imagen nos muestra la primera imagen capturada:

y con el botón reproducir  podemos visualizar todo el vídeo y realizar acciones bidireccionales:

### &#x20;4. Módulo ActiveX <a href="#toc84228643" id="toc84228643"></a>

El módulo ActiveX es una aplicación que permite visualizar cámaras en tiempo real y grabaciones a través de Internet Explorer o navegadores compatibles integrados en bObject de softwares de CRA como Manitou, SBN y Softguard.

### &#x20;4.1. Comandos Pasarela <a href="#toc84228644" id="toc84228644"></a>

La actual “PASARELA ACTIVEX GENERICO” de Alarmspace V2, incluye un servidor web que permanece a la “escucha” en el puerto 8003 (hacia adelante).&#x20;

Busca (al instalarse) el primer puerto libre sobre el 8003.&#x20;

Este puerto se puede modificar en un fichero de texto configuracion.dat dentro de la carpeta de instalación y reiniciando el servicio.&#x20;

(Debe estar abierto entre las máquinas de los operadores y la máquina en que corre AlarmspaceV2). También es importante que la Ip que aparece en este fichero (en las 4 primeras líneas) corresponda con la Ip del Servidor de AlarmSpace (en el ejemplo 192.168.X.XXX):

server=192.168.X.XXX;database=bydemesvideo;User Id=bydemesvideo; password=06851f3848543ea; port=3350; Persist Security Info=True

192.168.X.XXX:8003

192.168.X.XXX:9000

192.168.X.XXX:10003

Tras todo ello, ya se puede utilizar la llamada al sitio web y los comandos mostrados a continuación con el siguiente sistema:&#x20;

http://\[IP\_maquina\_alarmspace]:8003/bydemes.html?address=\[IP\_maquina\_alarmspace]\&port=8003\&subscriber=9 999\&channel=4\&channel\_source=main&#x20;

Siendo **subscriber** el número de abonado configurado en Alarmspace V2, en este ejemplo solo conectaría al DVR del abonado 9999 y mostraría el canal 4 en stream principal en vivo&#x20;

Parametrizable según la siguiente tabla de comandos:&#x20;

**channel=** número de canal para la visualización en directo, comienza por 1.&#x20;

**Opción**, si el equipo tiene CANAL “0”&#x20;

Si en número de canal se escribe 0 el sistema interpretará que se quiere utilizar el "Canal 0" va acompañado de los parámetros (“multiplay\_type” y “multiplay\_channel”)&#x20;

**multiplay\_type=\<n>** donde \<n> es 4, 8, 9, 16. Es decir el número de canales.&#x20;

**multiplay\_channel=\<n>** donde \<n> es el primer canal que se mostrará en la “parrilla”.&#x20;

_(Esta opción depende del grabador, algunos solo admiten CH0 y no entienden el resto de órdenes)_&#x20;

**channel\_source=main** | **sub**. Para seleccionar el stream de la conexión mainstream o substream. Por defecto es "sub".&#x20;

**channel\_save\_video=** Si está a 1 al iniciar la conexión empezará a guardar el video. El botón de guardar video quedará en rojo para que el operador pueda detenerlo.&#x20;

**channel\_save\_image=** Si está a 1 hace una captura de pantalla al iniciar la sesión.&#x20;

**prealarm\_channel=** número de canal para seleccionar en las grabaciones.&#x20;

**prealarm\_save\_video**=-segundos/-segundos. Rango de segundos a contar desde el momento “ahora”. Es decir, si pones -20/-5 y ahora son las 10:32:40, el video guardado irá desde las 10:32:20 a las 10:32:35.&#x20;

**prealarm\_view\_video**=-segundos/-segundos.&#x20;

Rango de segundos a contar desde el momento “ahora”. Es decir, si se escribe -20/-5 y ahora son las 10:32:40, el video irá desde 10:32:20 a 10:32:35.&#x20;

Utilice esta opción para mostrar el preview de la prealarma en la ventana de la derecha en vez de descargarlo. Es compatible con el anterior prealarm\_save\_video. Si se utilizan los dos, se visualizará y se descargará.&#x20;

_Es muy importante que el DVR esté grabando y “en hora” con el Alarmspace, de lo contrario puede no encontrar los videos grabados solicitados como prealarma, se recomienda la opción NTP para sincronizar la hora y pedir al grabador, por ejemplo -60/5 (un minuto antes de la alarma)_&#x20;

**Se pueden poner todas las opciones al mismo tiempo:**

ejemplo: port=3500\&subscriber=9999\&channel=4\&channel\_source=main\&channel\_save\_image=1\&channel\_save\_video=1\&p realarm\_channel=8\&prealarm\_save\_video=-20/0

Con esto el sistema se conectará al canal 4, del DVR del abonado 9999, en mainstream, hará una captura de pantalla y al tiempo empieza a guardar video en real, seguidamente pedirá la grabación de canal 8 desde 20 segundos antes de ahora mismo y la guardará

Se pueden agregar más comandos mediante & y no debe haber espacios en blanco

**Además, en el ActiveX de los operadores encontrarán:**

Un botón para activar las salidas de relé del dvr. Un botón para activar el audio del dvr.

Un botón para activar el sistema de habla-escucha bidireccional.

Un botón para hacer Replay en caso de haber solicitado una prealarma. Solo aparece si se ha solicitado una prealarma con los parámetros.

Va reproduciendo el momento de la alarma mientras no se solicita otra prealarma y mientras la grabación esté en el disco del DVR.

El operador puede con los botones de búsqueda visualizar grabaciones de otras cámaras y si pulsa Replay vuelve a visualizar la prealarma

Unos botones para seleccionar grabaciones de audio almacenadas en el PC y que se pueden enviar al DVR para que sean oídas mediante los altavoces amplificados que se hayan conectado al DVR en la instalación

Estos ficheros de audio deben ser wavs de 16bits 8Khz y Mono, se adjuntan unos pocos de ejemplo

No recomendamos sean excesivamente grandes pues durante la reproducción se bloquea el navegador

Además de los botones de grabar video y tomar fotos tanto en la parte de visión en vivo como en visión de grabaciones

En tiempo real podemos seleccionar cámara y tipo de stream, así como controlar domos seleccionando incluso la velocidad de control

En reproducción podemos seleccionar el canal, la fecha y la hora y pulsar GO para pasar a reproducir el momento

Y los controles sobre la grabación

### &#x20;4.2. Nuevos Comandos <a href="#toc84228645" id="toc84228645"></a>

**NUEVOS COMANDOS**&#x20;

**dvr\_name=nombre.** Se puede identificar un equipo por el nombre asignado. Permite distinguir entre dos grabadores con el mismo número de abonado.&#x20;

**sincPlaybackChannel=1 | 0.** Permite cambiar la vista de vídeo grabada al canal que cambiamos en la vista en directo, el tiempo de visualización será el escogido en prealarm\_view\_video.&#x20;

&#x20;  **fire\_subscriber=** Número de abonado asignado a una central de incendio. Aparecerá la visualización del estado de la      central y podremos interactuar con ella. Combinado con los comandos de DVR, permite visualizar las cámaras                    simultáneamente.&#x20;

&#x20;  **vto\_subscriber=** Número de abonado asignado a un videoportero (VTO). Aparece la pantalla de control del VTO, visualizamos la cámara, podemos conversar y abrir puertas. Combinado con comandos de DVR, permite visualizar cámaras adicionales.&#x20;

El nuevo botón ‘?’ muestra una tabla con las cámaras ordenadas por la última detección de movimiento. Así podemos tener una orientación del recorrido detectado:&#x20;

### 5. Configuración pasarela VESTA <a href="#id-5._configuracion_pasarela" id="id-5._configuracion_pasarela"></a>

### &#x20;5.1. Introducción <a href="#toc84228647" id="toc84228647"></a>

#### &#x20;5.1.1. Bienvenidos <a href="#toc84228648" id="toc84228648"></a>

La central de intrusión de Climax VESTA puede enviar los eventos generados en distintos formatos. AlarmSpace ha ampliado sus capacidades para recibir estos eventos, procesarlos y generar nuevas señales de salida adaptadas a los protocolos de los principales softwares de recepción actualmente en nuestro país (Manitou, SBN, Softguard y compatibles). &#x20;

Además, el propio AlarmSpace realiza un control del polling programable y nos ofrece la opción de desactivar abonados (no se mandan al software de CRA) y de cambiar los tiempos de polling. Adicionalmente podemos monitorizar los eventos recibidos en tiempo real. &#x20;

El sistema de recepción ofrece una configuración de alta disponibilidad mediante un cluster de dos máquinas (principal y backup) que disminuyen a niveles muy bajos la posibilidad de perder eventos o de sufrir retrasos importantes.&#x20;

### &#x20;5.2. Programación Central VESTA <a href="#toc84228649" id="toc84228649"></a>



### Configuración Rápida de CRA (Central receptora de alarmas en un panel VESTA)

{% hint style="info" %}
Paso 1:  Entra en la APP o WEB **SmartHomeSec** como instalador

Paso 2: Accede a la sección **AJUSTES -> REPORTE**

Paso 3: Añade una URL nueva y asigna el **GRUPO 2**

Paso 4: Añade en la URL: **ip://ABONADO@IP:PUERTO/MAN**&#x20;

```markup
ABONADO = Abonado facilitado por CRA 
IP = IP pública de CRA
PUERTO = PUERTO de CRA 
```
{% endhint %}





El esquema de programación aconsejado para la correcta recepción de eventos de la Central VESTA es el siguiente:&#x20;

En esta figura CRA representa el software de recepción de CRA, VESTA una central instalada y AlamSpace MAIN y BACKUP son dos instancias de AlarmSpace en dos máquinas distintas. Pueden ser virtualizadas, pero aconsejamos que estén sobre máquinas físicas distintas. Si falla la conexión con AlarmSpace MAIN la central lo intentará a través de AlarmSpace BACKUP. Siempre volverá a intentar por la conexión MAIN para ver si se recupera.&#x20;

Para programar los parámetros de comunicaciones en la central VESTA debemos dirigirnos al Cloud de ByDemes: [https://smarthomesec.bydemes.com/ByDemes/](https://smarthomesec.bydemes.com/ByDemes/) y acceder con nuestro usuario y contraseña. Una vez dentro seleccionamos el panel deseado y vamos a la sección de _Ajuste/Reporte_ &#x20;

En las distintas URL configuramos los parámetros de comunicación. La URL1 está reservada para uso interno. En la URL 2 introducimos los datos de nuestro AlarmSpace receptor principal de la manera siguiente:&#x20;

```
ip://1234@123.123.123.123:23506/MAN 
```

Donde 1234 es el número de abonado, 123.123.123.123 es la Ip pública de AlarmSpace y 23506 el puerto abierto contra la máquina de AlarmSpace para recibir eventos.&#x20;

_**NOTA IMPORTANTE**_

_**La Ip debe escribirse sin ceros a la izquierda, NO hay que completar con 0 hasta los 3 dígitos. De hacerlo así no funcionará la conexión.**_

En el grupo le asignamos el _Grupo 2_, esto nos asegura que se mandarán todos los eventos.&#x20;

Para asegurar la máxima disponibilidad recomendamos asignar una nueva URL (la URL 3). Esta tiene que ir dirigida a la máquina de AlarmSpace de Backup (con la Ip pública de la máquina de backup y el puerto abierto sobre esa máquina). Elegiremos también el _Grupo 2_ para enviar solamente los eventos que fallen por la vía principal (distinto grupo se envían todos, mismo grupo envía solo los que fallan en el anterior).&#x20;

En la _Secuencia de Informes(Reporting Sequence)_ elegimos _Esencial_ y en los re-intentos recomendamos solo un re-intento para agilizar el paso a la vía secundaria si falla el envío (si no se usa la vía secundaria podemos aumentar hasta 3 re-intentos).&#x20;

Faltarán los datos de subida de imágenes:&#x20;

También con el protocolo “Manitou” y la cadena [1234@123.123.123.123:23506](mailto:1234@123.1123.123.123:23506) con el mismo número de abonado, ip y puerto que de la vía principal.&#x20;

Le damos a “Enviar” y ya tendremos las comunicaciones asignadas.&#x20;

_**NOTA IMPORTANTE**_&#x20;

_**Recomendamos que la comunicación con AlarmSpace BACKUP se realice sobre otra vía de comunicación (otra fibra/ADSL distinta de la principal) y a poder ser de Operadores distintos (con infraestructura física distinta), para asegurar la recepción de eventos si cae una de las línea de comunicación.**_&#x20;

### &#x20;5.3. Configuraciones AlarmSpace <a href="#toc84228650" id="toc84228650"></a>

#### 5.3.1. Configuraciones generales - VESTALog <a href="#topic_configuracionesgenerales_vestalo" id="topic_configuracionesgenerales_vestalo"></a>

La aplicación VESTALog tiene distintas funcionalidades. Visualizar los eventos recibidos y reenviados al software de recepción de CRA en tiempo real, ver un histórico de las tramas tratadas, un log de texto con los detalles de funcionamiento de la receptora, una configuración de parámetros de la receptora, elegir distintos destinos para los eventos, reasignar o desechar eventos y configurar la función balanceador.&#x20;

\
**5.3.1.1. Tiempo real**

Visualizamos los eventos recibidos de las centrales VESTA, las respuestas y los eventos enviados al software de CRA y sus respuestas.&#x20;

\
**5.3.1.2. Histórico**

Se muestran las tramas recibidas de las centrales VESTA. Podemos filtrarlas por fechas y por número de abonado.&#x20;

\
**5.3.1.3. Log**

Registro de acciones realizadas por la aplicación. Útil para testeo y debug.

\
**5.3.1.4. Configuración VESTA**

Parámetros de la receptora:&#x20;

* ServidorMy: Ip del servidor de mysql local (la propia Ip de la máquina)
* ServidorMyBackup: Ip del servidor de mysql de backup (dejar 0 si es en AlarmSpace Backup o no se implementa la máquina de Backup)
* rutaVideos: ruta donde se guardarán imágenes y videos recibidos.
* domainForUNC: si se desea guardar los vídeos por red puede ser necesaria la autentificación de usuario por UNC. Introduzca aquí el dominio.
* userForUNC: usuario para guardar vídeos e imágenes en red.
* passwordForUNC: contraseña para guardar vídeos e imágenes en red
* checkForUser: pedirá usuario y contraseña al iniciar el visor bidireccional. Si no tiene permisos sobre el panel no permitirá el acceso.
* secondsBefore: solo se muestran en el visor bidireccional imágenes y vídeos de estos últimos segundos, para no visualizar vídeos antiguos que puedan confundir al operador.
* sendVisorEvents: si se activa esta opción, todas las acciones de un usuario en el visor bidireccional mandarán un evento al software de CRA.
* useLoadBalancer: permite repartir las conexiones entrantes de paneles entre dos o más máquinas de manera que incrementa el número de eventos simultáneos que se pueden tratar.
* Ip: ip local (privada) de la máquina sobre la que abriremos el puerto de escucha.
* Puerto: el puerto de escucha. Hay que abrirlo en TCP en el router para recibir eventos contra esta máquina.
* PuertoEncriptacion: el puerto de escucha de tramas encriptadas (distinto del que se reciben las tramas sin encriptar). Si se desea más seguridad se puede programar las centrales para enviar con encriptación de la siguiente manera:

ip://1234@3.123.23.123:23508/MAN\_TLS para los eventos

Elegir Manitou (TLS) para las imágenes.

* Linea: linea de receptora, usada por algunos softwares de CRA para distinguir y asociar abonados a una determinada receptora.
* PuertoMedical: puerto de escucha de tramas de equipos de la gama médica. También utilizado para recibir el protocolo SIA DC09 (SIA IP) cuando el software de CRA no soporta otros protocolos.
* Title: Nombre de la Receptora.
* IniCar: carácter de inicio de las tramas recibidas de los paneles. **No modificar sin supervisión de byDemes.**
* EndCar: carácter de fin de las tramas recibidas de los paneles. **No modificar sin supervisión de byDemes.**
* manitouServer: ip del servidor del software de CRA utilizado.
* manitouPort: puerto de escucha del software de CRA utilizado.
* vestaAutoactivateAb: si está a 1 los nuevos abonados que reciba la aplicación se activan automáticamente. Si es cero se registra el abonado, pero hay que activarlo manualmente.
* vestaPollingTime: tiempo entre señales de pollings por defecto. Se asignará automáticamente a todos los nuevos abonados. Se puede cambiar individualmente.

_Si hacemos click en esta fila con el botón derecho del ratón podemos asignar este valor a todos los abonados de intrusión que tenemos actualmente:_

* vestaDaysPreserveFrames: días que se conservarán las tramas del histórico.
* vestaDaysPreserveImages: días que se conservarán las imágenes en el disco duro de AlarmSpace
* VestaNumAb: número de abonado de la aplicación para enviar eventos internos.
* VestaInternalTestPeriod: frecuencia con la que se mandará el test interno de la aplicación en segundos. Si es 0 no se manda el test.
* VestaAccountDefaultTestPeriod: frecuencia con la que se mandará al Software de CRA un test de la Central VESTA si está realizando correctamente el polling.

_Si hacemos click en esta fila con el botón derecho del ratón podemos asignar este valor a todos los abonados de intrusión que tenemos actualmente._

* AllowMultipleDestines: Permitir múltiples destinos de señales a CRA
* ComputerProtocol: Protocolo de salida, debe coincidir con el programado en la central (XML, SIA…)
* ASReceiverType: Software de CRA
* skipDateFromFrame: NO enviar fecha del evento, aunque venga en la trama
* automaticResponse: No enviar evento al software de CRA y confirmar automáticamente
* privateProtocol: podemos cambiar el tipo de modelo utilizado (CID) por uno personalizado en la trama enviada al software de CRA.
* refuseUserCaptures: si ponemos este campo a verdadero, las peticiones de imágenes de los pircam realizadas por los usuarios (web o App) no llegarán a CRA preservando así la privacidad.
* continuosuCRAConnection: la conexión con el software de CRA se realiza al iniciar el servicio y no se interrumpe, se mantiene constantemente.
* sendCallerIdToCRA: la identificación de la central se envía en la trama lanzada hacia CRA.
* externally Monitoring: el test interno de la central (lanzado periódicamente según VestaInternalTestPeriod), puede comprobar también la conectividad externa mandándolo a través de la Ip pública.
* publicIp: ip pública utilizada por el servidor de Vesta, utilizada para mandar externamente el test interno. También se usa para comprobar que los paneles que queremos visualizar con el VisorHTML transmiten a esta CRA.
* numPollingFailure: número consecutivo de fallos de la señal de polling para enviar error.
* Heartbeat: trama del latido interno para enviar al software de CRA para certificar que el proceso está vivo.
* HeartbeatPeriod: tiempo de repetición en segundos del anterior latido.
* AESKey: clave de encriptación de la clave AES a utilizar si se utiliza la transmisión SIA-DC09 cifrada.
* sendEventoOnWrongMac: permite seleccionar si se manda al software de CRA un evento de un panel con la Mac errónea (no coincidente con la que tenemos registrada). Si se manda el evento se acompaña de otro evento que indica el error (CodigoEventoMacError). Si se marca no mandar no se manda nada, como si el abonado estuviera inactivo.
* DefaultBypassTolerance: si dejamos pasar uno de los test pollings cada cierto tiempo, podemos introducir una tolerancia para que el envío no se retrase. Aquí introducimos esta tolerancia en segundos.
* AllEventAsPolling: cualquier evento recibido del panel (no solo la señal de polling propiamente) refresca el tiempo de polling (y restaura el estado de fallo polling en caso de estar activo). Si se pone a falso, solo la señal de polling refresca el tiempo de polling.
* SynchASPolling: sincroniza automáticamente el tiempo de polling programado en AlarmSpace con el tiempo de polling que tienen programados los paneles. Tenemos tres opciones:

Si elegimos todos los paneles, se sincronizarán todos los abonados de AlarmSpace con sus correspondientes paneles (necesitamos tener actualizada la MAC de los paneles)

Si elegimos _Solo en el tiempo indicado,_ se sincronizarán solo los abonados cuyos paneles tengan configurado el tiempo que ponemos en el campo siguiente (_TimeSynchASPolling)_

Si elegimos _No sincronizar,_ no se sincroniza ningún abonado.

* TimeSynchASPolling: solo se sincronizan los abonados cuyos paneles tienen este tiempo programado (tiempo en segundos). Por ejemplo si le ponemos 21600 segundos, se actualizarán los abonados que tengan paneles programados con 6 horas de polling (típicamente equipos que funcionan solo con baterías).
* AddURLGpsLink: añada una URL con la geolocalización de un evento geolocalizado para ser ejecutad directamente con un solo click.
* Logffmpeg: Activa el log para visualizar la respuesta del programa ffmpeg al construir un vídeo a través de las imágenes recibidas.
* SendEventNewVESTACodes: cuando el sistema detecta que se han liberado nuevos códigos ContactID en el sistema Climax-VESTA se envía un eventos con este código acompañando el evento de test interno de la pasarela. Este código se puede configurar en Códigos Eventos y dejará de enviarse cuando se acepten los nuevos códigos en el Servidor de AlarmSpace, DVR→Abonados INTRUSION ¡¡NUEVOS CÖDIGOS VESTA!!

**5.3.1.5. Códigos Eventos**

Códigos de eventos programables de la pasarela:

* CodigoEventoPolling: el código ContactID que la aplicación entenderá como señal de polling, para el control de desconexiones. No se enviará al software de recepción.
* CodigoEventoFalloPolling: código ContactID enviado al tercer fallo de la señal de polling.
* CodigoEventoFalloPolling2Vias: código ContactID enviado al tercer fallo de la señal de polling en equipos que tienen por lo menos 2 vías de comunicación (detectado automáticamente por el sistema).
* CodigoEventoRestPolling: código ContactID enviado al recibir una señal de polling estando en fallo polling.
* CodigoEventoRestPolling2Vias: código ContactID enviado al recibir una señal de polling estando en fallo polling en equipos que tienen por lo menos 2 vías de comunicación (detectado automáticamente por el sistema).
* CodigoEventoMacError: un evento generado por la pasarela con este código se generará cuando se detecte que la identificación (MAC) de la central que manda con un número de abonado, no corresponde con la identificación que se recibió al registrar el abonado por primera vez.
* VestaInternalTestCode: código ContactID enviado como test interno (heartbeat) de la propia aplicación.
* CodigoEventoPollingSIA: En caso de usar el protocolo SIAIP (SIA-DC09) fijamos el código el evento de polling.
* CodigoEventoFalloPollingSIA: código SIA enviado al tercer fallo de la señal de polling.
* CodigoEventoFalloPollingSIA2Vias: código SIA enviado al tercer fallo de la señal de polling en equipos con 2 vías de comunicación como mínimo.
* CodigoEventoRestPollingSIA: código SIA enviado al recibir una señal de polling estando en fallo polling.
* CodigoEventoRestPollingSIA2Vias: código SIA enviado al recibir una señal de polling estando en fallo polling en equipos con 2 vías de comunicación como mínimo.
* CodigoEventoMacErrorSIA: código SIA enviado una MAC errónea però en formato SIA.
* videoEvCodeSIA: código SIA enviado al cuando se adjunta un evento de vídeo
* userCaptureCode: código del evento que envían los paneles en caso de una captura de imagen de un usuario
* visorArmCode: código ContactID que se envía al armar una partición desde el visor bidireccional en caso de estar activado
* visorDisarmCode:. código ContactID que se envía al desarmar una partición desde el visor bidireccional en caso de estar activado
* visorPartialArmCode:. código ContactID que se envía al hacer un armado en casa de una partición desde el visor bidireccional en caso de estar activado
* visorBypassCode: código ContactID que se envía al anular una zona desde el visor bidireccional en caso de estar activado
* visorRestoreBypassCode: código ContactID que se envía al habilitar una zona desde el visor bidireccional en caso de estar activado
* visorSceneApplyCode: código ContactID que se envía al aplicar una escena desde el visor bidireccional en caso de estar activado
* visorTakeSnapshotCode: código ContactID que se envía al hacer una petición de imagen desde el visor bidireccional en caso de estar activado
* registerAccountEvCode: código ContactID que se envía al registrar por primera vez un abonado. Si se deja en blanco no se envía este evento.
* EraseAccountEvCode: código ContactID que se envía al borrar un abonado desde Abonados INTRUSIÓN. Si se deja en blanco no se envía el evento.
* visorArmCodeSIA: código SIA que se envía al armar una partición desde el visor bidireccional en caso de estar activado
* visorDisarmCodeSIA:. código SIA que se envía al desarmar una partición desde el visor bidireccional en caso de estar activado
* visorPartialArmCodeSIA:. código SIA que se envía al hacer un armado en casa de una partición desde el visor bidireccional en caso de estar activado
* visorBypassCodeSIA: código SIA que se envía al anular una zona desde el visor bidireccional en caso de estar activado
* visorRestoreBypassCodeSIA: código SIA que se envía al habilitar una zona desde el visor bidireccional en caso de estar activado
* visorSceneApplyCodeSIA: código SIA que se envía al aplicar una escena desde el visor bidireccional en caso de estar activado
* visorTakeSnapshotCodeSIA: código SIA que se envía al hacer una petición de imagen desde el visor bidireccional en caso de estar activado
* registerAccountEvCodeSIA: código SIA que se envía al registrar por primera vez un abonado. Si se deja en blanco no se envía este evento.
* EraseAccountEvCode: código SIA que se envía al borrar un abonado desde Abonados INTRUSIÓN. Si se deja en blanco no se envía el evento.

\
**5.3.1.6. Destinos eventos**

Definimos destinos particulares a los que se pueden enviar las señales recibidas de la VESTA. Serán seleccionables por cada abonado:

Tenemos que definir la Ip, puerto y una línea (si la usa el software de CRA que tenga que recibir el evento). Le ponemos un nombre para referenciarlo en los abonados particulares, en el Servidor de AlarmSpace -> DVR -> Abonados VESTA

**5.3.1.7. Reasignar Eventos**

Funcionalidad que permite reescribir el código de evento de una trama, para que el software de CRA reciba el evento deseado:

Cambio del código de alarma (evento Contact ID o SIA) por el código deseado. Tenemos distintas opciones:

* En las 4 primeras líneas se cambia el evento original (E130) por el nuevo (E131) si coincide la Zona (la 1 o la 2) si en el tiempo retardo (10 segundos) llega el EventoDesactiva (E401 o E402). Si no llega el EventoDesactiva a los 10 segundos llegará el evento E130.
* En la 5ª línea, el evento E780 se desechará y no se enviará al software de CRA puesto que el evento nuevo está en blanco.
* En la 6ª línea se cambia el evento original (E132) por el nuevo (E133), para cualquier zona, puesto que la zona está en blanco, si en tiempo retardo (10 segundos) llega el EventoDesactiva (E401). Si no llega el EventoDesactiva a los 10 segundos llegará el evento E132.

**5.3.1.8. Configurar Balanceador**

Funcionalidad en desarrollo.

**5.3.1.9.&#x20;**_**Parámetros LORA**_

En este apartado aparecen los parámetros configurados automáticamente para el correcto funcionamiento de la recepción de eventos mediante las redes Lorawan. Un indice propio de cada CRA, el nombre de la CRA (se puede modificar, es meramente informativo), la Ip asignada por la red privada virtual y el puerto utilizado por la red para recibir eventos. No hace falta abrir ese puerto porque estamos sobre una VPN.

_**5.3.1.10. Parámetros API**_

Para el correcto funcionamiento del VisorHTML y otros procesos internos de AlarmSpace, debemos configurar correctamente los parámetros de la API, dependiendo de distintos sub-distribuidores. En general, podemos dejar los parámetros que vienen por defecto, que son los que vemos en pantalla y que funcionarán correctamente.

**Atención: No modificar estos parámetros sin consultar al personal especializado de ByDemes.**

_**5.3.1.11. API Múltiple**_

Esta funcionalidad permite definir más de una API para uso con el VisorHTML. Los distintos parámetros de cada API se pueden asignar individualmente a un abonado en concreto, de manera que tendrán preferencia estos parámetros en frente de los parámetros generales definidos en Parámetros API.

**5.3.1.12.&#x20;**_**Parámetros Nuva**_

Desde este apartado podemos habilitar las comunicaciones con la nube de Nuvathings, para recibir eventos de sus dispositivos.

Para habilitar las comunicaciones ponemos el EnableNuvaCS a verdadero. Eh el HostNuva respetamos el valor por defecto cloud.nuvasafe.com y en el PuertoNuva también: 11112. En el CsIdNuva tenemos que poner el identificador que se nos ha asignado desde Nuvathings para ser reconocidos en su nube. El polling de los dispositivos Nuva los controla la propia nube con lo que el Código de Eventos Polling no se utiliza en este caso. Sí que podemos personalizar la LineaNuva (Línea de Receptora, prefijo de Línea) para distinguirlo de los eventos que provengan de otros equipos como VESTA.

_**5.3.1.13. Nuva Múltiple**_

AlarmSpace permite conectarse simultáneamente a la nube de Nuvathings con diversos identificadores, para facilitar el uso a plataformas que sirvan servicios a distintas CRA distintamente o para cualquier tipo de tipología multi-CRA. En este apartado configuraremos los distintos CsId

\
**5.3.1.12. Configuración general de AlarmSpace**

Los parámetros de comunicación con el Software de CRA se configuran en el Servidor de AlarmSpace, en el apartado de Configuración/Parámetros de Receptora:&#x20;

Tenemos que seleccionar el tipo de programa, marcar como activo, el puerto y la ip del servidor. En esta versión la central VESTA solamente transmite en formato ContactID (indiferentemente de la plantilla seleccionada que si que aplica a los eventos de los grabadores).&#x20;

#### &#x20;5.3.2. Control de abonados <a href="#toc84228660" id="toc84228660"></a>

Visualizamos los abonados de la aplicación, si están activos o no, el tiempo de polling, si están en fallo polling y la fecha del último polling:&#x20;

Si le damos doble click sobre un abonado podemos cambiar algunos parámetros del abonado:&#x20;

Concretamente podemos cambiar el Período de polling (para ajustarlo al que esté programado en la central VESTA en cuestión), en minutos, y activar/desactivar el abonado. Si un abonado está inactivo las señales que puedan llegar quedan registradas, pero no pasan al software de gestión de CRA. También permite programar un test periódicamente (es un polling que sí que llegará al software de CRA). En el ejemplo se envía cada 24 horas. Con la MAC del equipo comprobamos si el número de abonado que recibimos corresponde con la MAC que tenemos registrada. Si no es así enviamos un evento de error (por defecto el código E304, ver configuración VESTA). Existe la posibilidad de asignar un grupo a cada abonado. Luego se pueden asignar grupos a usuarios, de manera que cada usuario tendría acceso bidireccional solamente a su grupo de abonados. La columna Num. Fallos Polling es el número de fallos consecutivos que tiene que haber para que se mande el evento de fallo de polling. Si no se define, por defecto es 3. También podemos ver la fecha en la que se registró cada abonado, el set de códigos utilizado por el abonado (CID o SIA), la Tolerancia Test, que son los segundos de margen (anteriores o posteriores) que tomará el sistema para considerar una señal de polling como test y el check Enviar Eventos Polling que permite desactivar el envío de eventos polling (se sigue controlando los fallos de polling pero no se mandan los eventos a CRA). Las nuevas columnas más gráficas muestran el estado de conexión de Ethernet (negro: no hay ethernet en la instalación, rojo: falla ethernet, verde: ethernet ok), el nivel de cobertura GSM, y el nivel de batería. Rearmado Automático se refiere a la capacidad del sistema para reamar remotamente y automáticamente un panel después de un tiempo definido a partir del desarmado. La columna Parámetros API indica si el abonado tiene que usar parámetros API (para el VisorHTML) distintos de los parámetros por defecto. Estos parámetros se elegirán en el progrma VESTA Lo → API Múltiple.

### &#x20;5.4. Configuraciones Software de Recepción de Alarmas de CRA <a href="#toc84228661" id="toc84228661"></a>

#### &#x20;5.4.1. Manitou <a href="#toc84228662" id="toc84228662"></a>

Este es un ejemplo donde se configuran las receptoras en Manitou y un ejemplo de cómo debería quedar:&#x20;

Se puede utilizar un puerto/driver dedicado o uno compartido (más de una receptora).&#x20;

Debemos elegir la línea que coincida con la que hemos programado en la pasarela de la central VESTA:&#x20;

Y el tipo de transmisor Manitou con “Capacidad de Vídeo”:&#x20;

#### &#x20;5.4.2. SBN <a href="#toc84228663" id="toc84228663"></a>

Póngase en contacto con su técnico habitual de IBS para habilitar la comunicación con la pasarela.

#### &#x20;5.4.3. Softguard <a href="#toc84228664" id="toc84228664"></a>

Póngase en contacto con su técnico habitual de Softguard para habilitar la comunicación con la pasarela.&#x20;

### 5.5. Módulo Visor – Acceso Bidireccional para centrales VESTA <a href="#toc2401" id="toc2401"></a>

El módulo Visor es una aplicación que permite visualizar los videos recibidos en alarma y las fotografías capturadas manualmente a través de cualquier navegador web compatible HTML5 y que permite ser “llamado” desde cualquier software de CRA que permita asignar una URL a un evento de alarma. Contiene funcionalidades de bidireccionalidad con las centrales que permiten armar/desarmar la central, anular/habilitar zonas, capturar una imagen del pircam y aplicar escenas definidas en la central

#### 5.5.3. Comando llamada al Visor Vesta <a href="#toc73094191" id="toc73094191"></a>

La actual versión de AlarmSpace V2, incluye un servidor web adicional para las centrales VESTA que permanece a la “escucha” en el puerto 8003.

Busca (al instalarse) el primer puerto libre sobre el 8003.

_Este puerto se puede modificar en un fichero de texto “configuracion.dat” dentro de la carpeta de instalación y reiniciando el servicio._

_(Debe estar abierto entre las máquinas de los operadores y la máquina en que corre AlarmspaceV2). También es importante que la Ip que aparece en este fichero (en las 4 primeras líneas) corresponda con la Ip del Servidor de AlarmSpace (en el ejemplo 192.168.X.XXX):_

_server=192.168.X.XXX;database=bydemesvideo;User Id=bydemesvideo; password=06851f3848543ea; port=3350; Persist Security Info=True_

_192.168.X.XXX:8003_

_192.168.X.XXX:9000_

_192.168.X.XXX:10003_

Tras todo ello, ya se puede utilizar la llamada al sitio web con el siguiente formato:

http://111.111.111.111:8003/bydemesVisor.html?subscriber=XXXX

Siendo 111.111.111.111 la IP de la máquina en que corre AlarmSpace y XXXX el número de abonado de la central VESTA.

Opcionalmente se puede añadir el parámetro secondsBefore: http://111.111.111.111:8003/bydemesVisor.html?subscriber=XXXX\&secondsBefore=YYY

Si ponemos secondsBefore solo listará los vídeos e imágenes de los últimos YYY segundos. Si no hay ninguno va refrescando hasta que se recibe alguno.

Esta llamada nos abrirá el navegador web con la siguiente ventana:

En la parte izquierda tenemos el video más reciente recibido en alarma y también los 10 últimos videos recibidos, accesibles desde un desplegable.

En la parte central tenemos las 10 últimas fotografías tomadas manualmente desde la aplicación VESTA, también accesibles desde un desplegable.

Debajo de los vídeos se nos muestra la localización de un pánico enviado por un usuario si se ha producido en los últimos 10 minutos.

En la parte derecha tenemos el estado de las particiones y zonas de la central, y las funciones bidireccionales. Vemos si la central está online y por qué vía ha sido la última transmisión (Ethernet en este caso), también nos informa de las vías disponibles. Nos indicara Ethernet, GPRS con el nivel de señal y operador y el estado de la batería:

Podemos realizar un armado parcial, un armado total o un desarmado de cada una de las particiones. Aplicar o quitar un bypass (anular) a una zona y capturar una imagen de un pircam (si tenemos permisos). Finalmente podemos aplicar escenas que hemos definido en la central, que permiten por ejemplo apagar las luces y conectar la alarma al salir de casa o el proceso contrario al entrar. Se ha añadido la funcionalidad de _Consultar comunicaciones,_ al pulsar el botón nos aparecen las URL de reporte que tiene configurado el panel, con lo que podemos comprobar que sean correctas y el tiempo de polling programado, para verificar con el que tengamos programado en AlarmSpace.

Si tenemos activada la opción sendVisorEvents, todas las acciones realizadas en el Visor mandarán un evento (con Código configurable) al software de CRA.

### &#x20;6. Configuración central AXHUH <a href="#toc84228667" id="toc84228667"></a>

### &#x20;6.1. Hikvision AXHUB and AlarmSpace <a href="#toc84228668" id="toc84228668"></a>

#### &#x20;6.1.2. Introducción <a href="#toc84228669" id="toc84228669"></a>

AXHUB es una central de intrusión de Hikvision capaz de conectarse con cámaras Ip y de almacenar vídeos de los saltos de alarmas. Con AlarmSpace podemos descargar al momento estos vídeos y retransmitirlos al software de recepción de la CRA. Con esto se consigue aumentar la capacidad de la central puesto que los sucesivos vídeos no se pierden si no que se van descargando.

#### &#x20;6.1.3. Requisitos mínimos <a href="#toc84228670" id="toc84228670"></a>

Las versiones mínimas para el funcionamiento de la descarga de vídeo son:

Central AXHUB modelo DS-PWA32-HG Versión de Firmware: V1.0.4 build 190629

AlarmSpace2 Versión 3.0.0.3

#### &#x20;6.1.4. Configuraciones iniciales en AlarmSpace <a href="#toc84228671" id="toc84228671"></a>

Para la correcta comunicación con la Central AXHUB debemos programar unos parámetros generales en AlarmSpace:

A parte de los parámetros propios de la comunicación con un software de CRA (tipo software, plantilla, puerto, Ip...) los nuevos parámetros a programar son:

AX HUB PASWORD: número que se deberá programar luego en cada central AXHUB para permitir la comunicación con AlarmSpace. Por defecto: 12345678

PUBLIC IP: Una IP pública de la CRA en la que podamos dirigir los puertos 7660 i 8089 a la máquina de AlarmSpace. La comunicación es sobre TCP.

Con estos parámetros el alta de cada central en AlarmSpace se hará automáticamente sin intervención de ningún usuario. Más adelante veremos otros parámetros que se pueden costumizar.

#### &#x20;6.1.5. Configuraciones especiales de la AXHUB <a href="#toc84228672" id="toc84228672"></a>

Los parámetros necesarios para conectar y recibir alarmas y vídeos de la AXHUB en el software de recepción de alarmas son el "Centro de Recepción de Alarmas" (Alarm Receiving Center) y "Registro EHome" (Ehome Registration)

\
**6.1.5.1. Centro de Recepción de Alarmas**

En el web server de la central vamos a los "Parámetros de Comunicación" y en concreto al "Centro de Recepción de Alarmas":

Esta vía de comunicación será la que enviará directamente las alarmas y eventos (no vídeos) al software de recepción mediante el protocolo SIA IP. Debemos elegir el tipo de protocolo (SIA o ContactiID), la IP/Dominio de la máquina donde esté el software de CRA con su correspondiente puerto abierto y un número de abonado. Los otros parámetros se pueden dejar por defecto excepto el Heartbeat interval. Podemos optar por deshabilitarlo o por poner un test cada 24 horas, el control de polling ya lo realiza AlarmSpace.

\
**6.1.5.2. Registro EHome**

El protocolo EHome/Isup es el que utiliza AlarmSpace para descargar vídeos:

En "Server Address" debemos poner la IP Pública que tenga el puerto 7660 abierto en TCP sobre la máquina de AlarmSpace.

En "Device ID" debemos poner el mismo número de abonado que en el protocolo de recepción de alarmas para que los vídeos recibidos se asocien al mismo abonado.

El "Modo de Comunicación" (Communication Mode) debemos elegir el que mejores prestaciones nos dé, priorizando siempre conexión de red cableada o wifi. Pero la transmisión de vídeos también es posible si solo tenemos comunicaciones móviles. Es importante destacar que según la disponibilidad de tipos de redes móviles la transmisión de los vídeos puede ser más larga. Mostraremos ajustes para disminuir el tamaño (peso) de los vídeos que hace razonable la utilización de cualquier método de comunicación.

Finalmente, en "EHome Login Password" tenemos que introducir la palabra que hayamos programado en el AXHUB Password de AlarmSpace para permitir la comunicación.

\
**6.1.5.3. Ajustes adicionales**

ara ajustar el tamaño (peso) de los vídeos al canal de comunicación que utilicemos tenemos que ir al menú de "Video & Audio":

Aquí podemos elegir por cada canal parámetros que influirán de manera decisiva en los vídeos generados. Si usamos comunicaciones móviles, sobre todo si no llegan a 4G seguiremos los siguientes pasos:

\- Intentamos transmitir siempre el Sub-stream.

\- La resolución intentamos elegir la más baja que nos permita la cámara.

\- La Video Bitrate es la característica que nos permite bajar de manera importante el tamaño. Si vemos que la transmisión es demasiado larga disminuimos este parámetro. El único límite es que el vídeo resultante sea suficientemente inteligible por el usuario final.

\- Podemos elegir entre 5 segundos de pre-vídeo y 2 de post-alarma o inversamente 2 de pre-vídeo y 5 de post-alarma, según las necesidades de la instalación o de la zona concreta. Esto no influirá en el tamaño de los vídeos generados.

Todos estos parámetros (sobre todo el Video Bitrate) deben ser ajustados en la instalación real, haciendo pruebas de transmisión de vídeos hasta lograr un equilibrio entre el tiempo que tardamos en transmitir el vídeo y el resultado final del vídeo transmitido. Dependiendo de las cámaras, ópticas y resoluciones un Bitrate más bajo puede dar un buen resultado, mientras que con otras no. Con un nivel de cobertura adecuado se pueden conseguir tiempos de entre 20-25 segundos en la transmisión de vídeos completos de menos de 100 KBytes.

#### &#x20;6.1.6. Funcionamiento en AlarmSpace <a href="#toc84228676" id="toc84228676"></a>

Una vez activemos el protocolo EHome en la central, esta se nos dará de alta en el software de AlarmSpace al que esté apuntando la IP/Puerto siempre y cuando el password de AXHUB coincida. Los parámetros mínimos de funcionamiento se incorporan a la programación de AlarmSpace de manera que podemos empezar a funcionar sin ni siquiera abrir el Servidor de AlarmSpace.

Sin embargo, hay parámetros configurables que pueden ser convenientes a nivel general por la CRA o a nivel particular de cada equipo (especialmente si se utilizan comunicaciones móviles).

\
**6.1.6.1. Parámetros Generales**

Cuando aparece la nueva central en el servidor de AlarmSpace tiene los siguientes parámetros asignados:

Como nombre por defecto AXHUB seguido del número de abonado que le hayamos asignado (el nombre se puede cambiar sin problemas)

El tipo de conexión no se utiliza, y en la Dirección IP aparece la propia de la máquina. El puerto utilizado es informativo. El tipo de dispositivo no hay que tocarlo, es el adecuado.

En el abonado nos aparece el número de abonado programado en la central, no hay que modificarlo a no ser que se modifique también en la central.

El número de serie es informativo y el Usuario no se utiliza.

En la contraseña aparecerá siempre la contraseña general de AXHUB. Se puede personalizar por cada equipo, pero primero hay que programar en la central el password por defecto de la CRA y una vez dado de alta el equipo en AlarmSpace cambiar la Contraseña en ambos lados (en AlarmSpace y en el protocolo EHome de la central)

Los canales son el número de cámaras totales (conectadas o no) que tiene la central.

Es importante destacar que desde el servidor de AlarmSpace no se puede comprobar la comunicación ni recargar los datos de la central. La comunicación no se puede iniciar bidireccionalmente.

\
**6.1.6.2. Configuración Alarmas Vídeo**

Por defecto las alarmas de vídeo quedan configuradas en cada canal de la AXHUB:

Si no existe en la configuración de Códigos de la pasarela el eventos "ALARMA VIDEO" se añade automáticamente. Si la plantilla utilizada es SIA se añade con el código "VA" si es ContactID con el código "E995":

Si se cambia el código "VA"/"E995" por cualquier otro código que desee utilizar el usuario, ese será el código que se enviará al software de CRA en el evento de Alarma de Vídeo, en esta central y en todas las que se den de alta en el futuro. Es importante no cambiar la descripción de la alarma "ALARMA VIDEO" porque si no en las próximas altas automáticas volverá a crearse un código de pasarela "ALARMA VIDEO" con valor "VA"/"E995" que será el que se asignará a las alarmas de vídeo.

\
**6.1.6.3. Control desconexiones**

AlarmSpace crea un control de desconexión/reconexión de los equipos automáticamente con el nombre de código de pasarela "FALLO POLLING"/"REST. FALLO POLLING" y con la zona "000":

Los códigos de pasarela asignados por defecto a los eventos "FALLO POLLING" y "REST. FALLO POLLING" son "NT"/"NR" para protocolo SIA y "E356"/"R356". Estos códigos se pueden cambiar en el menú "Alarmas/Pasarela" por los códigos que se desee que envíe AlarmSpace con los eventos de desconexión y reconexión:

El control de desconexiones de las centrales AXHUB es totalmente transparente para el software de CRA (solo recibe el fallo y la restauración si se producen). Sin embargo, para controlarlo, internamente AlarmSpace recibe y controla test periódicos de la central. Si usamos comunicaciones móviles con una SIM con consumo de datos limitado puede que deseemos cambiar la frecuencia con la que la AXHUB envía esos test (para reducir el consumo de datos). Para indicar esto a la central tenemos que programar el parámetro "Segundos polling" en las Opciones de la central seleccionada:

Vemos que en este caso están programados a 15 segundos, podemos cambiarlos a los segundos deseados. Por ejemplo, si ponemos 900 segundos tendremos que la central envía un test cada 15 minutos. También podemos cambiar el parámetro "Nº fallos polling para mandar desconexión", que significa el número de veces que esperamos un test y no lo recibimos antes de mandar el evento desconexión. En este caso está en 3 intentos, lo que quiere decir que si los segundos polling son 15 nos mandará la desconexión a los 45 (15\*3) segundos, pero que si son 15 minutos nos mandará la desconexión a los 45 minutos. Por eso es conveniente (si la comunicación utilizada lo permite) poner una frecuencia de polling elevada (Segundos polling pequeño) para tener un mayor control del estado de conexión del equipo.

### 7. Módulo **Visor Cámaras** <a href="#refheading___toc4818_1729251194" id="refheading___toc4818_1729251194"></a>

El módulo Visor Cámaras es el equivalente al Módulo ActiveX pero en aplicación de escritorio. Visualizamos una cámara en directo y la grabación de los segundos antes. Los parámetros que se utilizan son exactamente los mismos, menos la información de “address” y “port”. Si no se pasan parámetros el programa nos pide número de abonado y cámara a visualizar (funcionalidad básica). Los parámetros se pasarían de la siguiente manera:

"C:\Program Files\ByDemes\AlarmSpace2\VisorCamaras.exe" "subscriber=9986\&channel=2"

Se pueden utilizar todos los tags definidos en el Módulo ActiveX, agregando siempre con el separador &.
