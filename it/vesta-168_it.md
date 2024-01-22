# VESTA168

**Interruttore di controllo dell'otturatore SCS-1-ZW**

**introduzione**

SCS-1-ZW è un interruttore di controllo per tapparelle a tre pulsanti Z-Wave progettato per controllare un gruppo di dispositivi domotici preprogrammati semplicemente premendo i pulsanti dello scenario nella stessa rete Z-Wave.

L'interruttore di controllo dell'otturatore è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

![](<.gitbook/assets/0 (61).jpeg>)

**Introduzione al dispositivo**

**1. LED scenario**

Quando viene premuto uno qualsiasi dei 3 pulsanti dello scenario, il LED si accenderà brevemente

**2. Pulsanti degli scenari**

L'interruttore di controllo dell'otturatore ha 3 pulsanti di scenario

1.  **Compartimento della batteria**
2.  **Pulsante funzione**
    -   Premere il pulsante 3 volte entro 1,5 secondi per trasmettere un codice di apprendimento.
    -   Tenere premuto per 10 secondi per ripristinare.
3.  **LED (rosso)**

Il LED rosso si accende nelle seguenti situazioni:

-   -   Lampeggia una volta:

Quando l'interruttore di controllo Sutter trasmette un segnale.

-   -   Lampeggia due volte:

The Shutter Control Switch has successfully added into a Z-Wave network.

1.  **Foro per pulsante funzione**

**Caratteristiche**

![](<.gitbook/assets/1 (54).jpeg>)

-   _**Rilevamento batteria e batteria scarica**_

L'interruttore di controllo dell'otturatore utilizza due batterie alcaline AA da 1,5 V come fonte di alimentazione.

Lo Switch riporterà la percentuale della batteria al Pannello di controllo rispettivamente al 100%, 75%, 50%, 25%. Se la tensione della batteria è bassa (25%), un segnale di batteria scarica verrà inviato alla centrale per avvisare l'utente. L'interruttore di controllo dell'otturatore è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, l'interruttore di scenario trasmetterà il segnale di batteria scarica al coordinatore Z-Wave.

![](<.gitbook/assets/2 (58).png>)

-   _**Supervisione**_

Questa funzione utilizza la classe di comando Wake Up Z-Wave. La classe di comando di riattivazione consente allo Switch alimentato a batteria di notificare al pannello di controllo/gateway che è attivo e pronto a ricevere eventuali comandi in coda. Il periodo di tempo dell'intervallo di riattivazione viene programmato automaticamente in base alle impostazioni del pannello di controllo quando è incluso lo switch. L'impostazione consigliata dell'intervallo di tempo è compresa tra 30 e 60 minuti.

![](<.gitbook/assets/3 (58).png>)

-   _**Controllo scenari e tapparelle**_

Quando viene premuto un pulsante di scenario, l'interruttore di controllo della tapparella invierà un segnale al pannello di controllo per attivare lo scenario corrispondente (vedere Pannello di controllo per i dettagli). Impostare lo scenario nel Pannello di Controllo su

1

controllare la funzione di apertura/chiusura/arresto dell'otturatore per azionare l'otturatore tramite l'interruttore di controllo scenario.

L'interruttore emetterà un segnale acustico come indicazione quando il pulsante viene premuto.

![](<.gitbook/assets/4 (57).png>)

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Rimuovere il coperchio utilizzando un cacciavite.
    -   Inserire la batteria quindi riposizionare il coperchio.
    -   Inserisci il pannello di controllo Z-Wave**Modalità di inclusione**(fare riferimento al manuale del pannello di controllo Z-Wave).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/5 (56).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale Z-Wave o al pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.

-   -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

![](<.gitbook/assets/6 (38).png>)

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul dispositivo.
    -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   L'interruttore di controllo dell'otturatore entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi attivato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi all'interruttore di controllo dell'otturatore.
    -   Per programmare l'interruttore di controllo dell'otturatore utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi all'interruttore di controllo dell'otturatore entro il periodo di riattivazione.

![](<.gitbook/assets/7 (32).png>)![](<.gitbook/assets/8 (29).jpeg>)

**Installazione**

-   L'interruttore di controllo dell'otturatore è progettato per essere montato su una superficie piana con viti di fissaggio.
-   La base ha 3 fori, dove la plastica è più sottile, per il montaggio.
    1.  Rimuovere il coperchio utilizzando un cacciavite.
    2.  Sfonda gli appositi fori sulla base.
    3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.
    4.  Avvitare la base sulla superficie.
    5.  Riposizionare il coperchio sulla base e fissarlo serrando la vite di fissaggio.

![](<.gitbook/assets/9 (19).jpeg>)

2

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Sensore - Notifica

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2

Associazione Gruppo Informazioni CC

Batteria CC

Dispositivo reimpostato localmente CC

CC specifico del produttore, v2

Attivazione scena CC

Versione CC, v2

Svegliati CC, v2

Z-Wave Plus Informazioni CC, v2

Livello di potenza CC

Notifica CC, v4

Aggiornamento firmware CC, v2

![](<.gitbook/assets/10 (34).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Attivazione scena CC

(COMANDO_CLASSE_SCENA_ATTIVAZIONE)

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC

3
