# VESTA052

-   POVS-1-ZW
-   Sensore PIR di occupazione/vacanza
-   introduzione

POVS-1-ZW è un sensore di movimento a infrarossi passivi Z-Wave. È in grado di inviare segnali wireless al coordinatore nella rete Z-Wave al rilevamento del movimento. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. I sensori di movimento a infrarossi passivi Z-Wave consentono l'accesso alla classe "S2 Unauthenticated" e supportano l'inclusione Z-Wave SmartStart così come l'inclusione classica.

-   Identificazione delle parti
-   ![Mini-PIR B 2](<.gitbook/assets/0 (12).jpeg>)1. Obiettivo IR con indicatore LED

L'indicatore LED si trova al centro della lente IR.

L'indicatore LED si accende nelle seguenti condizioni:

-   Lampeggia una volta dopo aver premuto il pulsante funzione:

Il PIR entra in modalità Inclusione/Esclusione o rileva un movimento in modalità Test.

**2. Vano batteria**

Il PIR è alimentato da una batteria al litio CR123A 3V.

**3. Pulsante funzione**

-   Premere il pulsante una volta entro 30 secondi dall'inserimento della batteria per accedere a Inclusion o\\
    Modalità di esclusione.
-   Premere una volta il pulsante durante il normale funzionamento per inviare un comando di notifica di sveglia\\
    e accedere alla modalità test.
-   Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare le impostazioni di fabbrica del PIR.

**4. Base magnetica**

Il PIR viene distribuito sulla base magnetica durante l'installazione. Il magnete all'interno del PIR e della base garantirà che il PIR rimanga attaccato alla base indipendentemente dalla posizione e dall'angolo del PIR.

-   Caratteristiche
-   _**Rilevamento di occupazione/vacanze**_

Quando il PIR rileva un movimento, trasmetterà un segnale di attivazione. Il PIR inizia quindi il conto alla rovescia del timer di occupazione/vacanza. La durata del timer è regolabile da**30 secondi**A**60 minuti**e deve essere regolato dal coordinatore/pannello di controllo della rete Z-Wave.

Durante il timer, se il PIR rileva un movimento, il timer verrà ripristinato.

Quando il timer scade senza alcun rilevamento di movimento, il PIR trasmetterà un segnale di ripristino del rilevamento di movimento e tornerà al normale funzionamento.

Per favore riferisci a_**Configurazione della classe di comando**_per maggiori dettagli sulle impostazioni.

-   _**Regolazione della sensibilità**_

La sensibilità PIR può essere regolata per soddisfare diversi requisiti sia come sensore di sicurezza che di presenza/assenza. È possibile selezionare fino a 5 livelli di sensibilità tramite il coordinatore/pannello di controllo della rete Z-Wave. Seguire i passaggi seguenti per regolare la sensibilità:

1.  Premere una volta il pulsante funzione sul PIR, il PIR si attiverà.
2.  Entro 10 secondi, impostare la nuova sensibilità PIR dal Pannello di Controllo (fare riferimento al manuale del Pannello di Controllo per i dettagli). Il pannello invierà il segnale al PIR per completare l'impostazione.
3.  Se l'impostazione della sensibilità non viene completata entro questo intervallo, ricominciare dal passaggio 1.

Per favore riferisci a_**Configurazione della classe di comando**_per maggiori dettagli sulle impostazioni.

-   _Rilevamento batteria e batteria scarica_

Il PIR utilizza una batteria al litio CR123A da 3 V come fonte di alimentazione. Il corpo principale deve essere rimosso dalla base per accedere al vano batteria. Il vano batteria è dotato di una striscia che deve essere premuta sotto la batteria quando questa viene inserita. Quando rimuovi la pastella, solleva semplicemente la striscia.

Il PIR è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il PIR trasmetterà il segnale di batteria scarica al coordinatore nella rete Z-Wave.

Se la batteria non viene sostituita dopo che è scarica ed è scarica, il PIR interromperà tutte le operazioni.

Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte il pulsante funzione per scaricarla completamente prima di inserire la nuova batteria

-   _**Svegliati**_

Questa funzione utilizza la classe di comando Wake Up Z-Wave. La Classe Comando Risveglio consente al PIR alimentato a batteria di notificare alla Centrale/Gateway che è sveglio e pronto a ricevere eventuali comandi in coda. Il periodo di tempo dell'intervallo di riattivazione viene programmato automaticamente in base alle impostazioni del pannello di controllo quando è incluso il PIR. L'impostazione consigliata dell'intervallo di tempo è compresa tra 60 minuti.

-   _**Modalità di prova**_
-   La modalità test consente di verificare il raggio di rilevamento del PIR.
-   Per accedere alla modalità Test, premere una volta il pulsante Funzione per entrare nella modalità Test per 3 minuti.
-   Durante la modalità test, è possibile attivare il sensore PIR per verificarne la copertura di rilevamento. Se il PIR viene attivato, il LED lampeggerà una volta per indicare.
-   _**Aggiunta di dispositivi (inclusione)**_

Il dispositivo supporta sia il processo di inclusione classico che il processo di inclusione SmartStart. Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   **Inclusione classica**
-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Inserire la batteria e premere il pulsante una volta entro 30 secondi. Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).

**Inclusione SmartStart**

![](<.gitbook/assets/1 (19).png>)![](<.gitbook/assets/2 (22).png>)

I prodotti abilitati SmartStart possono essere aggiunti a una rete Z-Wave eseguendo la scansione del codice QR Z-Wave presentato sul prodotto con un controller che fornisce l'inclusione di SmartStart. Non sono necessarie ulteriori azioni e il prodotto SmartStart verrà aggiunto automaticamente entro 10 minuti dall'accensione nelle vicinanze della rete. Z-Wave SmartStart utilizza il DSK del dispositivo per migliorare e semplificare il processo di inclusione.**DSK**è la chiave specifica del dispositivo utilizzata per l'autenticazione. Le informazioni DSK vengono memorizzate nel formato del codice QR stampato su un'etichetta e incollata all'esterno del dispositivo, come mostrato nell'esempio sul lato destro.

-   Scansiona il codice QR sulla base di POVS-1-ZW per ottenerlo**DSK**e trasferirlo al gateway Z-Wave.

**Solo esempio**

-   Accendi POVS-1-ZW, una richiesta di inclusione SmartStart verrà inviata automaticamente al gateway.
-   Il gateway includerà automaticamente il dispositivo al momento del riconoscimento del dispositivo abbinando la richiesta di inclusione al DSK ottenuto

&lt;NOTA>

-   Il DSK del dispositivo viene utilizzato solo durante l'inclusione.
-   Il DSK può essere letto senza che il POVS si accenda, quindi è possibile preparare il gateway per includere il dispositivo prima di installare e accendere il POVS-1-ZW.
-   Se il POVS-1-ZW è già stato**incluso**(appreso) in un altro gateway/pannello di controllo Z-Wave, escluderlo prima (vedi_**Esclusione**_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave. Il POVS-1-ZW non invierà una richiesta di inclusione SmartStart se è già in un gateway/pannello di controllo Z-Wave.
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Inserire la batteria e premere il pulsante una volta entro 30 secondi. Il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.
-   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.

&lt;NOTA>

-   Prima di rimuovere o ripristinare le impostazioni di fabbrica del POVS-1-ZW, assicurarsi che le informazioni DSK del dispositivo siano state rimosse o non esistano nel gateway. Se rimuovi o ripristini le impostazioni di fabbrica del dispositivo, ma il relativo DSK esiste ancora nel gateway, il gateway includerà nuovamente automaticamente il dispositivo.
-   _**Prova di portata**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
-   Il PIR entrerà in modalità Z-Wave Sleep (per risparmiare energia) dopo essersi svegliato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi al PIR.
-   Per programmare il PIR utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi al PIR entro il periodo di riattivazione.
-   Installazione
-   _Altezza di montaggio e copertura del rilevamento PIR_
-   Il PIR ha una copertura di rilevamento di un cono di 120∘ nella parte anteriore. Se montato ad un'altezza compresa tra 1,2 e 2,1 m e rivolto in avanti, il PIR ha una portata massima di 10 metri.
-   La direzione del PIR può essere cambiata semplicemente ruotando il PIR sulla base. Dopo aver cambiato direzione, assicurarsi di testare la funzione di rilevamento per confermare la nuova copertura di rilevamento.
-   _Assemblea_
-   Il PIR è composto da una copertina anteriore e da una copertina posteriore. Il coperchio posteriore deve essere separato per l'installazione della batteria e la configurazione della rete Z-Wave.
-   Per separare la cover posteriore, tenere il PIR con entrambe le mani e girarlo come mostrato nell'immagine qui sotto per aprire il PIR.

![Mini-PIR B](<.gitbook/assets/3 (3) (1).jpeg>)

-   _Installazione_
-   Il corpo principale PIR ha un magnete interno nella parte inferiore e posteriore, che fissa il corpo principale alla base del magnete PIR quando posizionato sulla base. Le posizioni dei magneti sono identificate dal segno circolare sull'involucro.
-   La funzione di rilevamento del movimento del PIR è direzionale. È più sensibile al movimento laterale e meno sensibile al movimento verticale dall'alto verso il basso. Utilizzare la posizione del magnete inferiore come riferimento per determinare la direzione orizzontale e verticale del PIR.
-   La base PIR ha 2 fori di montaggio utilizzati per l'installazione su superficie con viti di fissaggio e tasselli forniti. La base ha anche un magnete all'interno. Un lato della base ha un'apertura per delimitare il lato anteriore della base. Il corpo principale deve essere posizionato sulla base con la lente rivolta verso l'apertura anteriore per garantire che la copertura di rilevamento del PIR non sia ostruita dalla base.

![](<.gitbook/assets/4 (1) (1).jpeg>)

1.  Utilizzare i 2 fori di montaggio sulla base PIR come modello e praticare dei fori sulla superficie.
2.  Inserire i tasselli se si fissa su intonaco o mattoni.
3.  Avvitare la base nei tasselli.
4.  Posiziona il PIR sulla base. Il magnete all'interno del PIR e della base garantirà che il PIR rimanga attaccato alla base.
5.  Ruotare il PIR per regolare la copertura di rilevamento in base al percorso di movimento previsto dell'intruso. Assicurarsi che l'intruso si sposti attraverso la copertura di rilevamento PIR da un lato all'altro.

-   _Linee guida per l'installazione_
-   **Si consiglia di installare il PIR nelle seguenti posizioni.**
-   In una posizione tale per cui un intruso si muoverebbe normalmente attraverso il campo visivo del PIR da un lato all'altro, evitare l'installazione nel punto in cui l'intruso si sposta attraverso la copertura di rilevamento dal PIR dall'alto verso il basso.
-   Tra 1,9 e 2 m dal suolo per le migliori prestazioni quando rivolto in avanti.
-   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
-   Non installare il PIR in un luogo esposto alla luce solare diretta o vicino ad apparecchi di riscaldamento/raffreddamento e a una presa d'aria
-   Non puntare il PIR verso fonti di calore come riscaldatori, radiatori e finestre.
-   Non puntare il PIR verso la finestra.
-   Evitare ostacoli di grandi dimensioni nell'area di rilevamento ed evitare oggetti in movimento come le tende.
-   Evitare luoghi in cui l'animale potrebbe arrampicarsi e compromettere l'immunità dell'animale, come le scale.
-   Informazioni sull'onda Z

**Tipo di dispositivo:**Notifica sensore di tipo generico

**Tipo di ruolo:**Segnalazione del sonno degli schiavi (RSS)

**Identificativo del produttore:**0x018E

**ID tipo prodotto:**0x0001

**Codice prodotto:**0x0104

**Classe di comando supportata:**

| **Classe di comando**                     | **Versione** | **Classe di sicurezza richiesta**      |
| ----------------------------------------- | ------------ | -------------------------------------- |
| Associazione                              | 2            | Classe di sicurezza più alta garantita |
| Informazioni sul gruppo dell'associazione | 3            | Classe di sicurezza più alta garantita |
| Reimpostazione del dispositivo localmente | 1            | Classe di sicurezza più alta garantita |
| Metadati di aggiornamento del firmware    | 5            | Classe di sicurezza più alta garantita |
| Specifico del produttore                  | 2            | Classe di sicurezza più alta garantita |
| Multicanale                               | 4            | Highest Granted Security Class         |
| Associazione multicanale                  | 3            | Classe di sicurezza più alta garantita |
| Livello di potenza                        | 1            | Classe di sicurezza più alta garantita |
| Notifica                                  | 8            | Classe di sicurezza più alta garantita |
| Batteria                                  | 1            | Classe di sicurezza più alta garantita |
| Svegliati                                 | 2            | Classe di sicurezza più alta garantita |
| Configurazione                            | 1            | Classe di sicurezza più alta garantita |
| Versione                                  | 3            | Classe di sicurezza più alta garantita |
| Servizio di trasporto                     | 2            | Nessuno                                |
| Informazioni su Z-Wave Plus               | 2            | Nessuno                                |
| Sicurezza 2                               | 1            | Nessuno                                |
| Supervisione                              | 1            | Nessuno                                |

**Gruppi associativi:**

| **ID** | **Nome**           | **Conteggio dei nodi** | **Descrizione**                                                                                                                                                                                                                               |
| ------ | ------------------ | ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | Ancora di salvezza | 5                      | <p>Supporta le seguenti classi di comandi:</p><ul><li>Ripristino del dispositivo localmente: attivato al ripristino</li><li>Rapporto di notifica: attivato dal PIR</li><li>Report batteria: quando il livello della batteria cambia</li></ul> |
| 2      | Insieme di base    | 5                      | <p>Quando il PIR si attiva, il gruppo 2 invia 0xFF.</p><p>Quando il PIR viene ripristinato, il gruppo 2 invia 0x00.</p>                                                                                                                       |

**Configurazione della classe di comando:**

| **Numero** | **Nome**               | **Misurare** | **Minimo** | **Massimo** | **Predefinito** | **Descrizione**                                                                                                                                                                                                                                            |
| ---------- | ---------------------- | ------------ | ---------- | ----------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1          | Sensibilità IR         | 1            | 1          | 5           | 4               | <p>Regolazione del livello di sensibilità:</p><ul><li>1: il più basso; 5: il più alto</li><li>Quando il massimo è maggiore di 5, 5 sarà il valore impostato; quando il minimo è inferiore a 1, 1 sarà il valore impostato.</li></ul>                       |
| 2          | Tempo di ripristino IR | 1            | 1          | 120         | 1               | <p>La durata del timer è regolabile da 30 secondi a 60 minuti:</p><ul><li>1: 30 secondi; 120: 60 minuti</li><li>Quando il massimo è maggiore di 120, 120 sarà il valore impostato; quando il minimo è inferiore a 1, 1 sarà il valore impostato.</li></ul> |
