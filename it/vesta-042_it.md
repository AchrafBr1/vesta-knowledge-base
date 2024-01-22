# VESTA042

PSM-29ZW / PSS-29ZW

Serie di interruttori di alimentazione

introduzione

La serie Power Switch comprende i seguenti modelli:

**PSS-29ZW:**Interruttore di alimentazione Z-Wave con funzione Router

**PSM-29ZW:**Interruttore di alimentazione Z-Wave con funzione misuratore e funzione router

Gli interruttori di alimentazione abilitati Z-Wave sono in grado di ricevere segnali wireless dal coordinatore nella rete Z-Wave per attivare/disattivare gli apparecchi ad esso collegati. L'interruttore di alimentazione funge anche da router nella rete Z-Wave. Dopo essere stato incluso nella rete Z-Wave, consente ad altri dispositivi Z-Wave di unirsi alla rete tramite l'interruttore di accensione.

L'interruttore di alimentazione con funzione contatore (PSM-29ZW) ha la caratteristica extra di tenere traccia del consumo energetico con il misuratore di potenza integrato e di trasmettere regolarmente i dati al coordinatore.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermediari "in ascolto".

Gli interruttori di alimentazione Z-Wave consentono l'accesso alla classe "S2 Unauthenticated" e supportano l'inclusione Z-Wave SmartStart così come l'inclusione classica.

Identificazione delle parti

1.Pulsante funzione ovvero indicatore LED

Il pulsante funzione funge anche da indicatore LED. Il pulsante funzione viene utilizzato per controllare l'interruttore di accensione. L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore di alimentazione.

**Indicazione LED:**

L'indicatore LED si accende nelle seguenti condizioni:

-   Acceso: accensione
-   Spento: spegnimento
-   La luce rossa lampeggia due volte:

1.L'interruttore di alimentazione è appena stato acceso.

2.L'interruttore di accensione è stato appena ripristinato alle impostazioni di fabbrica.

**Utilizzo dei pulsanti funzione:**

-   Premere il pulsante funzione per accendere/spegnere l'interruttore di accensione.
-   Premere il pulsante funzione 3 volte entro 1,5 secondi per trasmettere un codice di apprendimento.
-   Tieni premuto il pulsante funzione per 10 secondi per ripristinare le impostazioni di fabbrica.

| _Tipo F_                                                           | _Tipo J_                                                                                                                                                                                               | _Tipo B_ | _Tipo E_ | _Tipo G_ |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | -------- | -------- |
| <img src=".gitbook/assets/0 (12).png" alt="" data-size="original"> | <img src=".gitbook/assets/1 (16).png" alt="" data-size="original"><img src=".gitbook/assets/2 (19).png" alt="" data-size="original"><img src=".gitbook/assets/3 (18).png" alt="" data-size="original"> |          |          |          |

**Caratteristiche**

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

Il dispositivo supporta sia il processo di inclusione classico che il processo di inclusione SmartStart.

**Inclusione classica**

-   Collegare l'interruttore di alimentazione a una presa di corrente.
-   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione****modalità**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
-   Fare riferimento al manuale operativo del Z-Wave Gateway o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Rimozione del dispositivo**_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave.

**Inclusione SmartStart**

![](<.gitbook/assets/4 (17).png>)Z-Wave SmartStart utilizza il DSK del dispositivo per migliorare e semplificare il processo di inclusione. DSK è la chiave specifica del dispositivo utilizzata per l'autenticazione. Le informazioni DSK vengono memorizzate nel formato del codice QR stampato su un adesivo e attaccato al dispositivo.

-   Scansiona l'adesivo del codice QR sull'interruttore di accensione per ottenere DSK e trasferirlo al gateway Z-Wave.
-   Collega l'interruttore di alimentazione a una presa di corrente, una richiesta di inclusione di SmartStart verrà inviata automaticamente al gateway.
-   Il gateway includerà automaticamente il dispositivo al momento del riconoscimento del dispositivo abbinando la richiesta di inclusione al DSK ottenuto

&lt;NOTA>

-   Il DSK del dispositivo viene utilizzato solo durante l'inclusione.
-   Il DSK può essere letto senza che l'interruttore di alimentazione sia acceso, quindi è possibile preparare il gateway per includere il dispositivo prima di accendere l'interruttore di alimentazione.
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.

\\<NOTE>

-   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway Z-Wave o il pannello di controllo manterranno comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave del dispositivo.
-   Il ripristino delle impostazioni di fabbrica del dispositivo cancellerà anche tutti i dati di alimentazione accumulati.
-   Prima di rimuovere o ripristinare le impostazioni di fabbrica dell'interruttore di alimentazione, assicurarsi che le informazioni DSK del dispositivo siano state rimosse o non esistano nel gateway. Se rimuovi o ripristini le impostazioni di fabbrica del dispositivo, ma il relativo DSK esiste ancora nel gateway, il gateway includerà nuovamente automaticamente il dispositivo.
-   _Prova di portata_

Per verificare se il dispositivo è in grado di comunicare con Z-Wave Gateway o pannello di controllo:

-   Mettere il Gateway/Pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il Gateway/Pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio operativo (fare riferimento al manuale operativo del Gateway/Pannello).
-   _Capacità del dispositivo router Z-Wave_

L'interruttore di alimentazione consente ad altri dispositivi Z-Wave di unirsi alla rete Z-Wave tramite il router. La capacità massima dei dispositivi che possono connettersi alla rete Z-Wave tramite l'interruttore di alimentazione è 255.

Operazione

-   _**Controllo degli elettrodomestici**_
-   Dopo essere stato incluso in un gateway o pannello di controllo Z-Wave, collegare un elettrodomestico all'interruttore di alimentazione. I dati relativi alla potenza e al consumo energetico di questo elettrodomestico verranno trasferiti al Pannello di controllo.
-   Gli utenti possono accendere/spegnere da remoto l'apparecchio elettrico tramite il pannello di controllo (fare riferimento al manuale del pannello di controllo).
-   Premendo il pulsante funzione sull'interruttore di accensione è inoltre possibile attivare/disattivare l'interruttore di accensione.
-   L'interruttore di alimentazione trasmette un segnale con i dati di alimentazione al gateway/pannello Z-Wave ogni 10 minuti a partire dall'ultima volta che viene trasmesso un segnale.
-   Quando l'interruttore di alimentazione viene ricollegato dopo essere stato rimosso dalla presa di corrente, il precedente stato di accensione/spegnimento dell'interruttore di alimentazione verrà ripristinato immediatamente.
-   _**Monitoraggio del consumo energetico (solo PSM-29ZW)**_
-   Se la potenza in uscita è inferiore a 1 kW, PSM-29 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 2 W per aggiornare le informazioni sull'alimentazione del PSM-29.
-   Se la potenza in uscita è superiore a 1 kW, PSM-29 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 5 W per aggiornare le informazioni sull'alimentazione del PSM-29.
-   L'interruttore di alimentazione trasmette un segnale con i dati di alimentazione al gateway/pannello Z-Wave ogni volta che il consumo energetico aumenta di 0,1 kW/ora.
-   Quando la potenza è inferiore a 20 W, è più probabile che si verifichino errori di misurazione.
-   _**Specifiche di potenza**_
-   Per**110 V:**il carico operativo massimo è 1760 W e 16 A. Attenzione: non superare il carico massimo.
-   Per**230 V:**il carico operativo massimo è 3680 W e 16 A. Attenzione: non superare il carico massimo.
-   Se l'interruttore di alimentazione si surriscalda, interromperà automaticamente l'alimentazione come misura di sicurezza. L'interruttore di alimentazione deve essere scollegato e ricollegato dopo l'interruzione per riprendere il normale funzionamento.
-   _**Informazioni sull'onda Z**_

**Tipo di dispositivo:**Interruttore di accensione/spegnimento

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

Misuratore CC, v2

CC di base

Interruttore binario CC

Dispositivo reimpostato localmente CC

CC specifico del produttore

Livello di potenza CC

Versione CC, v2 o successiva

Z-Wave Plus Informazioni CC

**Supporto CC consigliato:**Metadati aggiornamento firmware CC

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo Switch può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta un gruppo di associazione con supporto di cinque nodi per il Raggruppamento 1. Per il Raggruppamento 1, lo Switch segnalerà il suo stato più recente al Gateway/Pannello Z-Wave.

Il raggruppamento 1 include:

Commutatore binario CC (SWITCH_BINARIO_RAPPORTO)

Misuratore CC, v2 (METRO_RAPPORTO_COMANDO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Segnalazione automatica al Raggruppamento 1 (nodo massimo 5)
-   Rapporto eventi on/off

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

-   Ripristino delle impostazioni di fabbrica

Quando l'interruttore di alimentazione viene ripristinato alle impostazioni di fabbrica, invierà il ripristino del dispositivo localmente a tutti i nodi del Gruppo 1.
