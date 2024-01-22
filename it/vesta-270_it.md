# VESTA 270

-   Telecamera con sensore di movimento PIR
-   VST-892
-   introduzione

VST-892 è una telecamera con sensore di movimento a infrarossi passivi (PIR). È in grado di inviare segnali wireless e immagini catturate (qualità dell'immagine fino a 640 x 480 pixel) al pannello di controllo al rilevamento del movimento.

La telecamera PIR è progettata per fornire un raggio di rilevamento tipico di 10 metri se montata a 2,3-2,5 metri dal suolo. I modelli immuni agli animali domestici non rilevano gli animali domestici fino a 50 cm/20 kg se montati a 2,3-2,5 metri dal suolo. Per i modelli compatibili con ripetitori/router**(Solo modelli P5)**, il raggio di comunicazione RF può essere ulteriormente esteso in aree difficili da raggiungere.

VST-892 è progettato con il rilevatore di prossimità digitale. La funzione antimascheramento consente di rilevare eventuali tentativi di accecamento del rilevatore posizionando oggetti nel suo campo visivo.

La telecamera PIR è costituita da un design in due parti composto da una copertura e una base. Il coperchio contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio. La base è dotata di fori per consentire il montaggio su una superficie piana o in una situazione d'angolo con una staffa triangolare per il montaggio ad angolo.

-   ![](<.gitbook/assets/0 (2) (1).png>)
-   Identificazione delle parti

1.  **LED lampeggiante**

Il LED Flash fornisce luce sufficiente per l'acquisizione di immagini in condizioni di scarsa illuminazione.

1.  **LED blu/pulsante funzione**

**LED blu:**

(Per favore riferisci a_**Indicatore LED**_descrizione qui sotto per i dettagli)

**Utilizzo dei pulsanti funzione:**

-   Tieni premuto il pulsante per 3 secondi per inviare un codice di apprendimento, rilascialo quando il LED blu si accende.
-   Premere il pulsante una volta per accedere alla modalità test per 3 minuti.
-   Premere una volta il pulsante per inviare un codice di apprendimento al ripetitore/router. (Solo modelli P5)

1.  **Rilevatore di prossimità digitale**

Il rilevatore di prossimità digitale viene utilizzato per rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.

1.  **Sensore IR**
2.  **Obiettivo della fotocamera PIR**
3.  **Compartimento della batteria**
4.  ![](<.gitbook/assets/1 (2) (1).png>)**Interruttore antimanomissione**
5.  **Interruttore ponticello di attivazione/disattivazione dell'immunità agli animali domestici (JP3)**

![jumper open](<.gitbook/assets/2 (2) (1).png>)![jumper close](<.gitbook/assets/3 (2) (1).png>)

**Ponticello spento**

Se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

**Ponticello acceso**

Il collegamento del ponticello viene inserito collegando i due pin

Se impostato su ON, l'immunità agli animali domestici è disabilitata.

Se impostato su OFF, l'immunità agli animali domestici è abilitata. (Impostazione di fabbrica)

1.  **Interruttore ponticello per aumento sensibilità (JP4)**

Quando impostato su ON, la sensibilità di rilevamento del PIR è alta.

Quando impostato su OFF, la sensibilità di rilevamento del PIR è a livello normale. (Impostazione di fabbrica)

-   Caratteristiche
-   _**Indicatore LED**_

Nella modalità di funzionamento normale, il LED blu non si accende tranne che nelle seguenti situazioni:

-   Quando la telecamera PIR è in condizioni di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED blu lampeggia per 2 secondi.
-   Quando il coperchio viene aperto e l'interruttore antimanomissione viene violato, il LED blu lampeggia per 2 secondi, per indicare che sta trasmettendo il segnale "Tamper".
-   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED Blu lampeggerà per 2 secondi.
-   Quando la telecamera PIR entra in modalità test, il LED blu lampeggia per 1 secondo. Durante la modalità Test, anche il LED Blu lampeggerà per 2 secondi ogni volta che viene rilevato un movimento.
-   Quando la telecamera PIR è in fase di riscaldamento di 30 secondi, il LED blu lampeggia lentamente.
-   Quando la telecamera PIR trasmette immagini catturate in condizioni di guasto (batteria scarica, interruttore antimanomissione attivato), il LED blu lampeggia continuamente.

Il LED non lampeggerà se la manomissione della telecamera PIR e la batteria sono normali e non sono in modalità test,

Se il LED lampeggia per indicare la trasmissione del segnale, lampeggerà due volte rapidamente dopo aver ricevuto la conferma dalla centrale.

-   _**Acquisizione di immagini**_

Quando il sistema di allarme è armato, la telecamera PIR catturerà 1, 3 o 6 immagini di allarme con risoluzioni 640 x 480 o 320 x 240 (programmabili dal pannello di controllo) al rilevamento del movimento. Puoi anche richiedere manualmente alla telecamera PIR di scattare una foto tramite il pannello di controllo. Le immagini catturate verranno trasferite al Pannello di controllo per essere visualizzate dagli utenti.

-   _**Periodo di riscaldamento**_

Quando il sistema del pannello di controllo entra in modalità attivazione o quando la telecamera PIR viene messa in modalità test, la telecamera PIR si riscalda per 30 secondi. Durante il periodo di riscaldamento di 30 secondi, la telecamera PIR non verrà attivata. Il LED blu lampeggerà lentamente durante il periodo di riscaldamento solo quando il PIR entra in modalità test.

-   _**Sveglia**_

La telecamera PIR ha un "**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, la telecamera PIR non ritrasmetterà per 1 minuto. Qualsiasi movimento rilevato durante questo periodo ripristinerà il tempo di sonno a 1 minuto. Il movimento continuo davanti alla telecamera PIR non scaricherà quindi la batteria.

-   _Rilevamento batteria e batteria scarica_

La telecamera PIR utilizza tre batterie al litio CR123A da 3 V collegate in serie come fonte di alimentazione. Rimuovere il coperchio del vano batterie e inserire le batterie per attivare la telecamera PIR.

La telecamera PIR è dotata della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, la telecamera PIR trasmetterà il segnale di batteria scarica al pannello di controllo. Se viene rilevato un movimento in condizioni di batteria scarica, il LED blu lampeggerà per 2 secondi.

Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte l'interruttore antimanomissione o il pulsante funzione per scaricarla completamente prima di inserire nuove batterie

-   _**Protezione antisabotaggio**_

La telecamera PIR è protetta da un interruttore antimanomissione che viene compresso quando la telecamera PIR è installata correttamente. Quando la telecamera PIR viene rimossa dalla superficie montata o il suo coperchio viene aperto, l'interruttore antimanomissione verrà attivato e la telecamera PIR invierà un segnale di apertura antimanomissione al pannello di controllo del sistema per ricordare all'utente la condizione. Se viene rilevato un movimento quando l'interruttore antimanomissione è aperto, il LED blu lampeggerà per 2 secondi.

-   _**Supervisione**_

La telecamera PIR effettuerà periodicamente un autotest trasmettendo un segnale di supervisione una volta ogni 30-50 minuti.

-   _**Modalità di prova**_
-   La modalità test serve per verificare il raggio di rilevamento della telecamera PIR (non la copertura della ripresa).
-   Premere una volta il pulsante Funzione per accedere alla modalità Test per 3 minuti, il LED blu lampeggerà per 1 secondo.
-   La telecamera PIR si riscalderà per 30 secondi. Si prega di non attivare la fotocamera durante questo periodo di riscaldamento.
-   Dopo il periodo di riscaldamento, è possibile attivare la telecamera PIR per verificare il raggio di rilevamento IR. Se la telecamera PIR viene attivata, il LED blu lampeggerà per 2 secondi.

\\<Note>

-   Affinché la modalità test funzioni senza intoppi, si consiglia di disattivare il timer di spegnimento.
-   _Apprendimento_
-   Rimuovere il coperchio del vano batteria allentando la vite del vano batteria.
-   Inserire le batterie. Orientare la batteria secondo l'indicazione della polarità.
-   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
-   Premere e tenere premuto il pulsante funzione per 3 secondi, rilasciare il pulsante quando il LED blu si accende, il LED blu si accenderà per 25 secondi in modalità apprendimento, aggiungere la telecamera PIR al pannello di controllo durante questo periodo (fare riferimento al pannello di controllo per terminare l'apprendimento in corso). Se il PIR viene aggiunto con successo al pannello di controllo, il LED blu lampeggerà 6 volte per indicarlo. Se il PIR non viene aggiunto entro 25 secondi, ripetere il processo di apprendimento.

\\<Note>

-   Se la telecamera PIR esiste già in un sistema di pannello di controllo, sarà necessario rimuovere la telecamera PIR dal pannello di controllo prima di poterla acquisire in un pannello di controllo diverso.
-   Quando si apprende la telecamera PIR in un ripetitore/router, premere una volta il pulsante funzione (invece di tenerlo premuto per 3 secondi) per inviare un codice di apprendimento. (Solo modelli P5)
-   _Prova della camminata_
-   Dopo aver appreso la telecamera PIR, inserire il pannello di controllo in "**Prova della camminata**", tenere la telecamera PIR nella posizione desiderata e premere il pulsante funzione per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
-   Quando sei soddisfatto che la telecamera PIR funzioni nella posizione scelta, puoi procedere al montaggio.
-   _**Modifica l'area operativa della telecamera PIR**_
-   Seguire le istruzioni di seguito per modificare l'area della telecamera PIR nel pannello di controllo

1.  Utilizzare la funzione Modifica dispositivo del pannello per modificare l'impostazione dell'area della telecamera PIR.
2.  Tenere premuto il pulsante Test per 3 secondi sulla telecamera PIR per inviare un segnale alla centrale, quindi rilasciare il pulsante quando il LED si accende.

-   _**Rilevamento di prossimità**_
-   VST-892 è dotato di un rilevatore di prossimità digitale in grado di rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.
-   Quando viene rilevato un evento di mascheramento e la condizione di mascheramento dura 2 minuti, VST-892 invierà un segnale di apertura antimanomissione al pannello di controllo per notificare all'utente la condizione.
-   Dopo che il mascheramento/blocco è stato rimosso per 2 minuti, VST-892 invierà un segnale di ripristino della manomissione al pannello di controllo.
-   _**Funzione di immunità agli animali domestici**_

Il sensore PIR supporta la funzione di immunità agli animali domestici e non rileva animali domestici fino a 50 cm/20 kg per ridurre al minimo la situazione di falsi allarmi.

La funzione Pet Immunity può essere abilitata/disabilitata impostando la posizione dell'interruttore Jumper (JP3). Quando l'interruttore jumper (JP3) è impostato su ON, l'immunità agli animali domestici è disabilitata. Quando l'interruttore jumper (JP3) è impostato su OFF, l'immunità agli animali domestici è abilitata. (Impostazione di fabbrica).

-   _**Funzione di aumento della sensibilità**_

È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento del PIR. Per aumentare la sensibilità di rilevamento, impostare l'interruttore jumper (JP4) su ON. Per mantenere la normale sensibilità di rilevamento, impostare l'interruttore jumper (JP4) su OFF (impostazione di fabbrica).

-   Installazione
-   _Linee guida per l'installazione_
-   La telecamera PIR è progettata per essere montata su una superficie piana o in una situazione d'angolo con viti e tasselli di fissaggio forniti.
-   La base è dotata di fori, dove la plastica è più sottile, per il montaggio. Due fori pretranciati servono per il fissaggio su superficie e una staffa di montaggio triangolare viene utilizzata per il fissaggio ad angolo.
-   Il raggio di rilevamento arriva fino a 10 metri se la telecamera PIR è montata a 2,3-2,5 metri dal suolo.
-   Quando la funzione Pet-Immunity è abilitata, non rileverà animali domestici fino a 50 cm/20 kg se montato a 2,3-2,5 metri dal suolo. Se necessario, puoi regolare l'altezza della telecamera PIR in base alle dimensioni del tuo animale domestico per prestazioni immunitarie ottimali. Una posizione di installazione più alta fornirà uno spazio più ampio immune agli animali domestici, ma aumenterà anche l'angolo cieco sotto la telecamera PIR.
-   Quando il VST-892 è montato con una staffa rotante, non avrà la normale area di rilevamento (come nel diagramma) o il tipico raggio d'azione per l'immunità agli animali domestici.

VST-892**Intervallo di rilevamento**

![](<.gitbook/assets/4 (2) (1).png>)

**Si consiglia di installare la telecamera PIR nelle seguenti posizioni**

-   Montare in un punto in cui gli animali non possano raggiungere l'area di rilevamento arrampicandosi su mobili o altri oggetti.
-   Non puntare il rilevatore verso le scale su cui gli animali possono salire.
-   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR.
-   Tra 2,3 e 2,5 m dal suolo per le migliori prestazioni.
-   In un angolo per avere la visuale più ampia.
-   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
-   Non installare la telecamera PIR completamente esposta alla luce solare diretta.
-   Evitare di installare la telecamera PIR in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
-   ![](<.gitbook/assets/5 (1) (1) (1).png>)Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
-   Non puntare direttamente verso fonti di calore, ad es. Fuochi o caldaie e non sopra i termosifoni.
-   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.
-   **Assicurati di mantenere sempre la potenza del segnale RSSI fissa su "4".**
-   _Montaggio della telecamera PIR_
-   Il PIR è progettato per essere montato su una superficie piana o in una situazione d'angolo con viti di fissaggio e tasselli forniti.
-   Per il montaggio ad angolo, viene fornita una staffa triangolare per aggiungere la protezione antimanomissione posteriore. La staffa include anche due fori per il montaggio a parete.
-   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Grazie alla staffa rotante, il VST-892 può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
-   **Montaggio ad angolo:**

1.  Aprire il coperchio allentando la vite del coperchio utilizzando un cacciavite Philips.
2.  Supera i 4 fori d'angolo al centro della base.
3.  Utilizzare i fori come modello per praticare i fori sulla superficie.
4.  Inserire i tasselli se si fissa su intonaco o mattoni.
5.  Avvitare la base nei tasselli.
6.  Montare il coperchio sulla base e serrare.

-   **Montaggio ad angolo con la staffa triangolare:**

1.  Sulla staffa triangolare sono realizzati 4 fori. Per fissare la staffa sul_Muro A_, svolta_Eliminazione A e B_. Per fissare la staffa_Muro B_, svolta_KO C&D_. Per fissare la staffa su entrambi_Wall A & B_, svolta_KO A&D o B&C_.
2.  Utilizzare i due fori come sagoma per praticare i fori sulla superficie dell'angolo.
3.  Inserire i tasselli.
4.  Avvitare la staffa triangolare nei tasselli con_i due bastoncini di puntamento (E)_in alto, di fronte a te.
5.  ![triangular bracket](<.gitbook/assets/6 (1) (1) (1).jpeg>)![](<.gitbook/assets/7 (1) (1) (1) (1).png>)Montare la telecamera PIR sui ganci della staffa triangolare.

-   **Montaggio su superficie:**

1.  Aprire il coperchio allentando la vite del coperchio utilizzando un cacciavite Philips.
2.  Attraversa i 2 fori della superficie al centro della base.
3.  Utilizzare i fori come modello per praticare i fori sulla superficie.
4.  ![](<.gitbook/assets/8 (1) (1) (1).png>)Inserire i tasselli se si fissa su intonaco o mattoni.
5.  Avvitare la base nei tasselli.
6.  Montare il coperchio sulla base e serrare.

-   **Montaggio su superficie con staffa rotante (articolo opzionale, venduto separatamente):**

La staffa rotante può essere montata a parete tramite viti in dotazione.

1.  Avvitare la staffa rotante al muro.
2.  Montare opportunamente i 3 ganci della staffa rotante nei 3 fori della base.
3.  Ruotare la staffa per il campo di rilevamento corretto e serrare la vite di fissaggio.
