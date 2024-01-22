# VESTA053

**League of Legends-1ZW****Sensore di luce ambientale, umidità e temperatura**

**introduzione**

LMHT-1ZW è un sensore di luce ambientale, umidità e temperatura Z-Wave. Monitora l'ambiente domestico e trasmette l'illuminamento (lux), l'umidità e la temperatura misurati al coordinatore nella rete Z-Wave.

Il sensore è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

La serie LMHT-1ZW comprende i seguenti modelli.

League of Legends-1ZW

League of Legends-1ZW-OTA

**Identificazione delle parti**

1.  **Sensore di luce/indicatore LED**
    -   **Lampeggia una volta:**Trasmissione del codice di apprendimento/Ripristino delle impostazioni di fabbrica
    -   **Lampeggia due volte:**Dopo che il sensore è stato aggiunto con successo al gateway/pannello di controllo Z-Wave.
2.  **Termometro**
3.  **Compartimento della batteria**
4.  **Pulsante funzione**
    -   Premi una volta per inviare un segnale al coordinatore.
    -   Tenere premuto per 10 secondi per ripristinare le impostazioni di fabbrica.
    -   Premere per 3 volte entro 1,5 secondi per trasmettere il codice di apprendimento.

![](<.gitbook/assets/0 (41).jpeg>)

**Caratteristiche**

-   _**Monitoraggio dell'illuminazione, dell'umidità e della temperatura**_
    -   Il sensore misura l'illuminamento, l'umidità e la temperatura per trasmettere regolarmente i dati misurati al pannello di controllo/gateway Z-Wave.

Il segnale di lettura dell'illuminamento/umidità e della temperatura viene trasmesso ogni 1 minuto. Il sensore trasmetterà automaticamente il segnale anche quando:

-   -   -   La temperatura varia di +/- 2°C
        -   L'umidità cambia del +/- 10%
        -   L'illuminamento varia di 1500 lux rispetto all'illuminamento precedente
        -   L'illuminamento attuale è maggiore o uguale a 300 lux e cambia del 45% rispetto all'illuminamento precedente
        -   L'illuminamento attuale è inferiore a 300 lux e varia di oltre 60 lux rispetto all'illuminamento precedente
        -   Accendere il sensore inserendo la batteria.
    -   È inoltre possibile premere una volta il pulsante funzione per trasmettere manualmente il segnale di lettura corrente.
-   _**Rilevamento batteria e batteria scarica**_
    -   Il sensore utilizza una batteria al litio CR123A da 3 V come fonte di alimentazione.
    -   Il sensore è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il sensore trasmetterà un segnale di batteria scarica al gateway/pannello di controllo.

1

-   -   Il sensore riporterà la percentuale della batteria al gateway/pannello di controllo rispettivamente al 100%, 75%, 50% e 25%. Se la tensione della batteria è bassa (25%), il segnale di batteria scarica verrà inviato alla Centrale per avvisare l'utente.
    -   Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte il pulsante funzione per scaricarla completamente prima di inserire una nuova batteria.
-   _**Supervisione**_

Questa funzione utilizza la classe di comando Wake Up Z-Wave. La classe di comando di riattivazione consente al sensore alimentato a batteria di notificare al pannello di controllo/gateway che è attivo e pronto a ricevere eventuali comandi in coda. Il periodo di tempo di riattivazione viene programmato automaticamente in base alle impostazioni del pannello di controllo quando The Sensor è incluso. L'impostazione consigliata dell'orario di sveglia è superiore a 60 minuti.

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il sensore è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

Il sensore deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il sensore verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Rimuovere prima la batteria del sensore.
-   Tieni premuto il pulsante funzione. Tenendo premuto il pulsante funzione, accendere il sensore reinserindo la batteria e attendere 10 secondi per ripristinare le impostazioni di fabbrica.

_\\<NOTE>_

-   -   Il ripristino delle impostazioni di fabbrica del sensore lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway o il pannello di controllo Z-Wave manterrà comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni del sensore Z-Wave.
-   _**Prova di portata**_

Per verificare se il sensore è in grado di comunicare con il gateway Z-Wave o il pannello di controllo:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul sensore.
    -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   Il sensore entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi risvegliato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi al sensore.
    -   Per programmare il sensore utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi al sensore entro il periodo di riattivazione.

2

**Installazione**

-   _**Montaggio del sensore**_

Il sensore può essere montato utilizzando due metodi: montaggio autoadesivo o con viti.

**Montaggio autoadesivo**

1.  Pulire la superficie con uno sgrassatore idoneo.
2.  Rimuovere il rivestimento da un lato del cuscinetto adesivo biadesivo e applicare saldamente il cuscinetto adesivo sul retro del dispositivo.
3.  Rimuovere l'altro rivestimento e posizionare/premere saldamente il dispositivo nella posizione desiderata.

![](<.gitbook/assets/1 (35).jpeg>)

Non utilizzare il metodo di montaggio autoadesivo su superfici scarsamente verniciate e/o ruvide.

**Montaggio a vite**

La base del sensore ha due fori per viti, dove la plastica è più sottile per il montaggio. Per montare il sensore:

-   1.  Staccare il gruppo coperchio superiore e base allentando la vite di fissaggio del coperchio utilizzando un cacciavite Phillips.
    2.  Sfonda i fori sulla base.
    3.  Utilizzare i fori come dima e praticare due fori e inserire i tasselli.
    4.  Avvitare la base sui tasselli.
    5.  Riposizionare il coperchio superiore sulla base agganciando la base al gancio di fissaggio e spingendo il coperchio verso la base.
    6.  Fissare e riavvitare il coperchio superiore alla base utilizzando un cacciavite Phillips.
-   _**Informazioni sull'onda Z**_

**Tipo di dispositivo:**Sensore - Notifica

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**

Associazione CC, v2

Associazione Gruppo Informazioni CC

Batteria CC

Dispositivo reimpostato localmente CC

CC specifico del produttore, v2

Sensore multilivello CC, V5

Versione CC, v2

Svegliati CC, v2

Z-Wave Plus Informazioni CC, v2

Livello di potenza CC

Notifica CC, v4

Aggiornamento firmware CC,v2

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Sensore multilivello CC,V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC

Gruppo 2 per “Rapporto temperatura”:

Sensore multilivello CC,V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Gruppo 3 per “Rapporto umidità”:

Sensore multilivello CC, V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Gruppo 4 per “Rapporto Luminanza”:

Sensore multilivello CC, V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

3
