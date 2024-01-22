# VESTA041

**Sensore ambientale RS-23-ZW**V: R3

**introduzione**

RS-23-ZW è un sensore ambientale Z-Wave. È dotato di funzione di rilevamento della temperatura e dell'umidità per monitorare gli ambienti domestici. Le informazioni su temperatura e umidità verranno trasmesse alla rete Z-Wave e visualizzate sullo schermo LCD del sensore ambientale.

Il sensore ambientale è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

La serie Z-Wave Room Sensor comprende i seguenti modelli:

RS-23-ZW

![](<.gitbook/assets/0 (33).png>)

RS-23-ZW-OTA

**Identificazione delle parti**

**1. Display LCD**

Il display LCD visualizza le seguenti informazioni:

-   Temperatura nell'impostazione Fahrenheit / Celsius
-   Umidità UR%.
-   Connettività di rete Z-Wave (![](<.gitbook/assets/1 (30).jpeg>)icona).

![](<.gitbook/assets/2 (27).jpeg>)

\-Stato della batteria scarica (icona).

-   -   Retroilluminazione LCD accesa: quando viene premuto il pulsante funzione.

1.  **Pulsante funzione**
    -   Premere il pulsante una volta per:

Invia un segnale di supervisione con informazioni su temperatura/umidità Accendi la retroilluminazione LCD per 10 secondi.

-   -   Premere il pulsante 3 volte entro 1,5 secondi per trasmettere il codice di apprendimento.
    -   Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica. Fare riferimento a**Rimozione del dispositivo (esclusione)**per dettagli.

1.  **Vite della base (coperchio aperto/chiuso)**

Quando il coperchio anteriore è installato su quello posteriore, aprire il coperchio allentando la vite della base e chiuderlo allo stesso modo.

1.  **Ponticello di impostazione Fahrenheit/Celcius (JP1)**
    -   Se il collegamento del ponticello è inserito tra i 2 pin superiori, il display LCD visualizzerà la temperatura in gradi Celsius. (**Impostazione di fabbrica**)
    -   Se il collegamento del ponticello è inserito tra i 2 pin inferiori, il display LCD visualizzerà la temperatura in Fahrenheit.
2.  **Compartimento della batteria**

![](<.gitbook/assets/3 (25).jpeg>)![](<.gitbook/assets/4 (27).jpeg>)

Il sensore ambientale è alimentato da due batterie alcaline AA da 1,5 V

1.  **Copertina posteriore**
2.  **Fori per montaggio a parete**

**Caratteristiche**

-   _**Rilevamento della temperatura e dell'umidità**_
    -   Il sensore ambientale trasmetterà regolarmente i segnali di temperatura e umidità in base all'impostazione.

1

L'intervallo predefinito in fabbrica è 10 minuti.

-   -   Quando la temperatura cambia di +/- 2°C o l'umidità cambia di +/- 10%, anche il sensore ambiente trasmetterà un segnale.
    -   È inoltre possibile premere una volta il pulsante funzione per trasmettere manualmente un segnale di temperatura e umidità.
    -   L'intervallo di rilevamento della temperatura è di circa -10°C~50°C.( 14°F~122°F)
    -   L'intervallo di rilevamento dell'umidità è di circa il 10%~90% umidità relativa
-   _**Rilevamento batteria e batteria scarica**_
    -   Il sensore ambiente utilizza due batterie alcaline da 1,5 V come fonte di alimentazione. Le batterie sono incluse nella confezione.
    -   Il sensore ambientale riporterà la percentuale della batteria al pannello di controllo Z-Wave rispettivamente al 100%, 75%, 50%, 25%, 0%. Se la tensione della batteria è bassa (25%), un segnale di batteria scarica verrà inviato al pannello di controllo Z-Wave per avvisare l'utente.
    -   Il sensore ambientale è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il sensore ambientale trasmetterà il segnale di batteria scarica per avvisare l'utente e visualizzare l'icona di batteria scarica sul display LCD.
    -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte il pulsante funzione per scaricarle completamente prima di inserire nuove batterie.
-   _**Supervisione**_
    -   Questa funzione utilizza la classe di comando Wake Up Z-Wave. La classe di comando di riattivazione consente al sensore ambientale alimentato a batteria di notificare al pannello di controllo/gateway Z-Wave che è attivo e pronto a ricevere eventuali comandi in coda. L'orario di sveglia viene programmato automaticamente in base alle impostazioni del pannello di controllo Z-Wave quando è incluso il sensore ambientale. L'impostazione consigliata dell'orario di sveglia è superiore a 60 minuti.
-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Rimuovere il coperchio allentando la vite di fissaggio.
    -   Inserire le 2 batterie alcaline nel vano batterie collegando la polarità corretta come mostrato sul coperchio del vano batterie per accendere il sensore ambiente.
    -   Inserisci il gateway Z-Wave o il pannello di controllo Z-Wave in**Inclusione**O**Apprendimento**(fare riferimento al manuale del gateway Z-wave o del pannello di controllo Z-Wave).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo Z-Wave per completare il processo di apprendimento.
    -   Se il sensore è già stato**incluso**(appreso) in un altro Z-Wave Gateway/Pannello di controllo Z-Wave, o se non è possibile apprendere il sensore nell'attuale Z-Wave Gateway/Pannello di controllo Z-Wave, escluderlo prima (vedere_**Esclusione**_) prima di tentare di farlo**includere**nell'attuale Z-Wave Gateway/Z-Wave Control Panel.
-   _**Rimozione del dispositivo (esclusione)**_

Il sensore ambientale deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo Z-Wave in**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo Z-Wave).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il sensore ambientale verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway Z-Wave di rete è mancante o inutilizzabile)._

-   Rimuovere prima le batterie del sensore ambiente.
-   Tieni premuto il pulsante funzione. Tenendo premuto il pulsante funzione, accendere il sensore ambientale reinserindo le batterie e attendere 10 secondi per ripristinare le impostazioni di fabbrica.

_\\<NOTE>_

-   Il ripristino delle impostazioni di fabbrica del sensore ambientale lo ripristinerà alle impostazioni predefinite di fabbrica (escluse dalla rete Z-wave). Il gateway Z-Wave o il pannello di controllo Z-Wave manterranno comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo Z-Wave su come rimuovere le impostazioni Z-Wave del sensore ambiente.

2

-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o il pannello di controllo Z-Wave:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul dispositivo.
    -   Il pannello di controllo del gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del pannello di controllo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   Il sensore ambientale entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi attivato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo Z-Wave non sono in grado di inviare comandi al sensore ambientale.
    -   Per programmare il sensore ambiente, inviare i comandi al sensore ambiente entro il periodo di riattivazione.

**Installazione**

-   _**Montaggio del sensore ambiente**_

Per la migliore qualità del display LCD, il sensore ambientale deve essere montato in una posizione a circa 5∘ sopra l'altezza degli occhi.

-   Montaggio a vite.

Durante il montaggio con viti, assicurarsi di utilizzare solo le viti fornite nella confezione dal produttore originale, poiché viti inadeguate potrebbero danneggiare l'interno del dispositivo.

-   1.  Rimuovere il coperchio anteriore utilizzando un cacciavite.
    2.  Sfonda i fori sul retro della copertina.
    3.  Utilizzando i fori come modello, praticare dei fori sulla superficie
    4.  Inserire i tasselli in caso di fissaggio su intonaco o mattoni
    5.  Avvitare il coperchio posteriore nei tasselli
    6.  Riavvitare il coperchio anteriore sul coperchio posteriore
-   _**Informazioni sull'onda Z**_

**Tipo di dispositivo:**Sensore - Notifica

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

Batteria CC

Dispositivo reimpostato localmente CC

CC specifico del produttore

Sensore multilivello CC

Versione CC, v2 o successiva

Svegliati CC

Z-Wave Plus Informazioni CC

Aggiornamento firmware CC, v2 (solo versione OTA)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Il sensore ambientale può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta 3 gruppi di associazione.

Gruppo 1 per “LifeLine”:

Sensore multilivello CC,V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Batteria CC(COMANDO_CLASSE_UTENTE_DI BASE)

Dispositivo reimpostato localmente CC

_(Supporta 1 nodo)_

Gruppo 2 per “Rapporto temperatura”:

Sensore multilivello CC, v5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

_(supporta 5 nodi)_

3

Gruppo 3 per “Rapporto umidità”:

Sensore multilivello CC,V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

_(supporta 5 nodi)_

4
