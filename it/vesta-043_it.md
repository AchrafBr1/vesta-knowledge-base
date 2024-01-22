# VESTA043

-   Interruttore di scenario intelligente WSS-4E-ZW
-   introduzione

WSS-4E-ZW è un interruttore di scenario a quattro pulsanti Z-Wave progettato per controllare un gruppo di dispositivi di automazione domestica preprogrammati semplicemente premendo i pulsanti di scenario nella stessa rete Z-Wave.

Lo Scenario Switch è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

![](<.gitbook/assets/0 (13).png>)

-   Introduzione al dispositivo

**1. LED scenario**

Sono presenti quattro LED di scenario, il LED si accenderà in base al pulsante di scenario corrispondente premuto.

**2. Pulsante Scenario**

Lo Scenario Switch dispone di 4 pulsanti scenario:

![未命名-1](<.gitbook/assets/1 (7) (1).jpeg>)Pulsante 1

Pulsante 2

Pulsante 3

Pulsante 4

**3. Vano batteria**

**4. Pulsante funzione**

-   Premere il pulsante 3 volte entro 1,5 secondi per trasmettere un codice di apprendimento.
-   Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

**5. LED (rosso)**

Il LED rosso si accende nelle seguenti situazioni:

-   Lampeggia una volta:

Quando l'interruttore di scenario sta trasmettendo un segnale.

-   Lampeggia due volte:

Lo Scenario Switch è stato aggiunto con successo a una rete Z-Wave.

**6. Foro per pulsante funzione**

-   Caratteristiche
-   _Rilevamento batteria e batteria scarica_

L'interruttore di scenario utilizza due batterie alcaline AA da 1,5 V come fonte di alimentazione.

Lo Switch riporterà la percentuale della batteria al Pannello di controllo rispettivamente al 100%, 75%, 50%, 25%. Se la tensione della batteria è bassa (25%), un segnale di batteria scarica verrà inviato alla centrale per avvisare l'utente.

L'interruttore di scenario è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, l'interruttore di scenario trasmetterà il segnale di batteria scarica al coordinatore Z-Wave.

-   _**Supervisione**_

Questa funzione utilizza la classe di comando Wake Up Z-Wave. La classe di comando di riattivazione consente all'interruttore della luce alimentato a batteria di notificare al pannello di controllo/gateway che è attivo e pronto a ricevere eventuali comandi in coda. Il periodo di tempo dell'intervallo di riattivazione viene programmato automaticamente in base alle impostazioni del pannello di controllo quando è incluso l'interruttore della luce. L'impostazione consigliata dell'intervallo di tempo è compresa tra 30 e 60 minuti.

-   _**Scenario**_

Quando viene premuto un pulsante scenario, l'interruttore scenario invierà un segnale al pannello di controllo per attivare lo scenario corrispondente (vedere Pannello di controllo per i dettagli). L'interruttore emetterà anche un segnale acustico come indicazione.

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Rimuovere il coperchio utilizzando un cacciavite.
-   Inserire la batteria quindi riposizionare il coperchio.
-   Inserisci il pannello di controllo Z-Wave**Modalità di inclusione**(fare riferimento al manuale del pannello di controllo Z-Wave).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
-   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale Z-Wave o al pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.

-   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
-   Lo Scenario Switch entrerà in modalità Sleep Z-Wave (per risparmiare energia) dopo essersi attivato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi allo switch di scenario.
-   Per programmare l'interruttore di scenario utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi all'interruttore di scenario entro il periodo di riattivazione.
-   Installazione
-   Lo Scenario Switch è progettato per essere montato su una superficie piana con viti di fissaggio.
-   La base ha 3 fori, dove la plastica è più sottile, per il montaggio.

1.  Rimuovere il coperchio utilizzando un cacciavite.
2.  Sfonda gli appositi fori sulla base.
3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.
4.  Avvitare la base sulla superficie.
5.  Riposizionare il coperchio sulla base e fissarlo serrando la vite di fissaggio.

![未命名-2](<.gitbook/assets/2 (2) (1).jpeg>)

-   Informazioni sull'onda Z

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

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Attivazione scena CC

(COMANDO_CLASSE_SCENA_ATTIVAZIONE)

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC
