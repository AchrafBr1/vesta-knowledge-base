# VESTA259

**Misuratore di interruttori di alimentazione su guida DIN (serie PSM-DIN2-ZW)**

![](<.gitbook/assets/0 (97).jpeg>)

L'interruttore di alimentazione è in grado di ricevere segnali wireless dal coordinatore nella rete Z-Wave per attivare/disattivare gli apparecchi ad esso collegati. Il Power Switch consente inoltre di tenere traccia del consumo energetico con un misuratore di potenza integrato e di trasmettere regolarmente i dati alla rete Z-Wave.

L'interruttore di alimentazione è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermediari "in ascolto".

![](<.gitbook/assets/1 (81).jpeg>)

La serie PSM-DIN2-ZW comprende i seguenti modelli:

PSM-DIN2-ZW

PSM-DIN2-ZW-OTA

![](<.gitbook/assets/2 (75).png>)![](<.gitbook/assets/3 (68).jpeg>)

-   _**Identificazione delle parti**_
    1.  **Connettore di ingresso**
    2.  **Connettore di uscita**
    3.  **Porta per antenna esterna**
    4.  **Indicatore LED**
    5.  **Pulsante funzione**

\-Premere il pulsante funzione 3 volte entro 1,5 secondi per inviare un codice di apprendimento.

\-Tenere premuto per 10 secondi per ripristinare le impostazioni di fabbrica.

![](<.gitbook/assets/4 (78).png>)

-   _**Indicatore LED**_
    -   Acceso: accensione
    -   Spento: spegnimento
    -   La luce rossa lampeggia due volte: 1. L'interruttore di alimentazione è appena stato acceso,_O_
        1.  L'interruttore di accensione è stato appena ripristinato alle impostazioni di fabbrica.
-   _**Attenzione**_
    -   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
    -   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
-   _**Cablaggio e installazione**_

![](<.gitbook/assets/5 (78).png>)![](<.gitbook/assets/6 (58).png>)

**Prima dell'installazione, assicurarsi che l'alimentazione sia stata scollegata.**

![](<.gitbook/assets/7 (46).jpeg>)

-   -   Collegare il terminale L del connettore di ingresso al terminale L dell'alimentatore, utilizzare il fusibile per il cavo. Collegare il terminale N del connettore di ingresso al terminale N dell'alimentatore.
    -   Collegare il terminale N del connettore di uscita al terminale N del dispositivo esterno e collegare il terminale L del connettore di uscita al terminale L del dispositivo esterno.
    -   Collegare l'antenna esterna alla porta dell'antenna esterna.
    -   Montare il dispositivo all'interno del quadro elettrico utilizzando una guida DIN.
-   _**Inclusione (aggiunta o dispositivo di apprendimento)**_

![](<.gitbook/assets/8 (53).png>)

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Accendere il dispositivo attivando l'alimentatore esterno.
-   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione**O**Apprendimento**modalità (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
-   Fare riferimento al manuale operativo del Z-Wave Gateway o del pannello di controllo per completare il processo di aggiunta.

1

-   -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Esclusione**_) prima di tentare di includerlo nell'attuale gateway/pannello di controllo Z-Wave.
-   _**Esclusione (Rimozione Dispositivo)**_

![](<.gitbook/assets/9 (49).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.

_\\<NOTE>_

-   -   -   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway Z-Wave o il pannello di controllo manterranno comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave del dispositivo.
        -   Il ripristino delle impostazioni di fabbrica del dispositivo cancellerà anche tutti i dati di alimentazione accumulati.
-   _**Prova di portata**_

![](<.gitbook/assets/10 (51).png>)![](<.gitbook/assets/11 (41).png>)

Per verificare se il dispositivo è in grado di comunicare con Z-Wave Gateway o pannello di controllo:

-   -   -   Mettere il Gateway/Pannello in modalità test di portata (Walk Test).
        -   Premere il pulsante funzione sul dispositivo.
        -   Il Gateway/Pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio operativo (fare riferimento al manuale operativo del Gateway/Pannello).
-   _**Operazione**_
    -   Dopo essere stato incluso in un gateway o pannello di controllo Z-Wave, collegare un elettrodomestico all'interruttore di alimentazione. I dati relativi alla potenza e al consumo energetico di questo elettrodomestico verranno trasferiti al Pannello di controllo.
    -   Premendo il pulsante sull'interruttore di accensione è inoltre possibile attivare/disattivare l'interruttore di accensione.
    -   Accendere/spegnere a distanza l'apparecchio elettrico tramite il Pannello di Controllo (fare riferimento al manuale del Pannello di Controllo).
    -   Se la potenza in uscita è inferiore a 1 kW, PSM-DIN2 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 2 W per aggiornare le informazioni sull'alimentazione del PSM-DIN2.

Se la potenza in uscita è superiore a 1 kW, PSM-DIN2 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 5 W per aggiornare le informazioni sull'alimentazione di PSM-DIN2.

-   -   PSM-DIN2 trasmette un segnale con i dati di alimentazione al gateway/pannello di controllo Z-Wave ogni 10 minuti a partire dall'ultima volta che viene trasmesso un segnale.
    -   L'interruttore di alimentazione trasmette un segnale con i dati di alimentazione al gateway/pannello di controllo Z-Wave ogni volta che il consumo energetico aumenta di 0,1 kW/ora.
    -   Se l'alimentazione dell'interruttore di alimentazione viene ricollegata dopo una precedente disconnessione, il precedente stato di accensione/spegnimento dell'interruttore di alimentazione verrà ripristinato immediatamente.
    -   Quando la potenza è inferiore a 20 W, è più probabile che si verifichino errori di misurazione.
-   _**Specifiche di potenza**_
    -   Per**110 V:**il carico operativo massimo è 1760 W e 16 A. Attenzione: non superare il carico massimo.
    -   Per**230 V:**il carico operativo massimo è 3680 W e 16 A. Attenzione: non superare il carico massimo.
-   _**Informazioni sull'onda Z**_

![](<.gitbook/assets/12 (43).png>)![](<.gitbook/assets/13 (32).png>)![](<.gitbook/assets/14 (31).png>)

**Tipo di dispositivo:**Tipo generico Switch binario

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Tipologia di prodotto:**0x0004

**Codice prodotto:**0x0003

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Z-Wave Plus Informazioni CC

Associazione CC,(S2)

Associazione multicanale CC, (S2)

Informazioni sul gruppo di associazione CC, (S2)

Servizio Trasporti CC

Versione CC,(S2)

CC specifico del produttore, (S2)

Dispositivo ripristinato localmente CC, (S2)

Livello di potenza CC, (S2)

2

Misuratore CC, v2

Cambia CC binario

Supervisione CC,(S2)

Aggiornamento firmware Md CC, (S2)

![](<.gitbook/assets/15 (31).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo Switch può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta un gruppo di associazione con supporto di cinque nodi per il Raggruppamento 1. Per il Raggruppamento 1, lo Switch segnalerà il suo stato più recente al Gateway/Pannello Z-Wave. Gruppo 1 per “LifeLine”: (nodi max: 5)

Cambia CC binario (COMMAND_CLASSE_INTERRUTTORE_BINARIO)

Misuratore CC (COMANDO_CLASSE_METRO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Segnalazione automatica al Raggruppamento 1 (nodo massimo 5)
-   Rapporto eventi on/off

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

-   Ripristino delle impostazioni di fabbrica

Quando l'interruttore di alimentazione viene ripristinato alle impostazioni di fabbrica, invierà il ripristino del dispositivo localmente a tutti i nodi del Gruppo 1.

-   Rapporto del contatore:
    -   Se la potenza in uscita è inferiore a 1 kW, PSM-DIN2 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 2 W per aggiornare le informazioni sull'alimentazione del PSM-DIN2.
    -   Se la potenza in uscita è superiore a 1 kW, PSM-DIN2 trasmetterà un segnale al gateway/pannello Z-Wave quando la potenza devia di +/- 5 W per aggiornare le informazioni sull'alimentazione di PSM-DIN2.
    -   PSM-DIN2 trasmette un segnale con i dati di alimentazione al gateway/pannello di controllo Z-Wave ogni 10 minuti a partire dall'ultima volta che viene trasmesso un segnale.
    -   L'interruttore di alimentazione trasmette un segnale con i dati di alimentazione al gateway/pannello di controllo Z-Wave ogni volta che il consumo energetico aumenta di 0,1 kW/ora.
    -   Formato dei dati:

Esempio 1:**41 64 00 00 50 14**FF FF**00 00 00 00**kWh (00005014 = 20500 = 20,5)

-   -   -   Valore attuale:**41 64 00 00 50 14**
        -   Valore precedente:**00 00 00 00**

Esempio 2:**41 74 00 00 27 10**FF FF**00 00 00 00**W (00002710 = 10000 = 10 W)

-   Valore attuale:**41 74 00 00 27 10**
-   Valore precedente:**00 00 00 00**

3
