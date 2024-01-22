# VESTA009

-   Sensore di movimento PIR Serie IR(P)-29

Il PIR rileva la firma a infrarossi per rilevare i movimenti all'interno di un'area assegnata e segnala al pannello di controllo di attivare l'allarme se un intruso attraversa il suo percorso di rilevamento.

Il PIR è costituito da un design in due parti composto da una copertura e una base. Il coperchio contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio. La base è dotata di fori per consentire il montaggio su una superficie piana o in una situazione d'angolo

Il PIR è dotato di un interruttore antimanomissione che verrà attivato quando il coperchio viene aperto. Può anche avvisarti per segnalare problemi di comunicazione e situazioni di batteria scarica.

Il PIR è progettato per fornire un raggio di rilevamento tipico di 12 metri se montato a 2 metri dal suolo.

I modelli Pet-Immune del sensore PIR serie IR-29 supportano ulteriormente la funzione di immunità agli animali domestici e non rilevano animali domestici fino a 27 kg entro un raggio di 7 metri per ridurre al minimo la situazione di falsi allarmi.

**Il sensore PIR serie IR-29 include i seguenti modelli**:

IR-29 / IR-29 F1 – Sensore PIR con batterie alcaline

IRP-29 / IRP-29 F1 – Sensore PIR Pet Immune con batterie alcaline

IR-29SL / IR-29SL-F1 – Sensore PIR con batteria al litio.

![](<.gitbook/assets/0 (3) (1).png>)IRP-29SL / IRP-29SL-F1 – Sensore PIR Pet Immune con batteria al litio

-   _**Identificazione delle parti**_

**1. Pulsante di prova/indicatore LED**

Il pulsante di test viene utilizzato per testare le prestazioni della radio e per scopi di apprendimento.

L'indicatore LED viene utilizzato per indicare lo stato del sistema.

**2. Isolante della batteria**

**3. Interruttore ponticello di abilitazione/disabilitazione supervisione (JP2)**

![jumper open](<.gitbook/assets/1 (5) (1).png>)![jumper close](<.gitbook/assets/2 (5) (1).png>)

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

**Ponticello acceso**

Il collegamento del ponticello viene inserito collegando i due pin

-   Quando impostato su ON, la supervisione è disabilitata.**(Impostazione di fabbrica per i modelli con frequenza 433AM)**
-   Quando impostato su OFF, la supervisione è abilitata.**(Impostazione di fabbrica per i modelli di frequenza 868WF)**

**433FM**E**Modelli di frequenza 868FM**non supporta l'interruttore jumper JP2, la supervisione è abilitata e non può essere disabilitata.

**4. Interruttore a ponticello per l'aumento della sensibilità (JP3)**

-   Quando impostato su OFF, la sensibilità di rilevamento del PIR è a livello normale.**(impostazione di fabbrica per i modelli non immuni agli animali domestici)**
-   Quando impostato su ON, la sensibilità di rilevamento PIR è alta. (Impostazione di fabbrica per i modelli Pet-Immune)

**5. Interruttore antimanomissione**

L'interruttore antimanomissione protegge il PIR dall'apertura non autorizzata del coperchio.

-   _**Sveglia**_

Il PIR ha un “**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, il PIR non ritrasmetterà per 1 minuto; qualsiasi ulteriore movimento rilevato durante questo periodo di sonno prolungherà la durata del sonno di un altro minuto. In questo modo il movimento continuo davanti a un PIR non scaricherà eccessivamente la batteria.

-   _**Funzione di supervisione**_

Se abilitato (vedere la tabella sopra), quando il PIR è in modalità di funzionamento normale effettuerà periodicamente un autotest trasmettendo un segnale di supervisione una volta ogni 30-50 minuti

Se la Centrale non riesce a ricevere i segnali di Supervisione trasmessi da un certo PIR per un tempo prestabilito, appare un “**Fuori servizio**r” verrà generato il messaggio di errore.

-   _**Funzione di aumento della sensibilità**_

È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento del PIR. Per aumentare la sensibilità di rilevamento, collegare l'interruttore jumper (JP3) o il**SU**posizione (impostazione predefinita per i modelli Pet-Immune). Per mantenere la normale sensibilità di rilevamento, scollegare l'interruttore jumper (JP3) o il**SPENTO**posizione (impostazione predefinita per i modelli non immuni agli animali domestici).

-   _**Modalità di prova**_

Il PIR può essere messo in modalità Test premendo il pulsante Test sul coperchio anteriore. In modalità Test, disabiliterà il timer di spegnimento e consentirà all'indicatore LED di lampeggiare ogni volta che viene rilevato un movimento. Ogni volta che si preme il pulsante Test, il PIR trasmetterà un segnale di test al pannello di controllo per il test della portata radio ed entrerà in modalità test per 3 minuti. La modalità test scade dopo 3 minuti.

-   _Indicatore LED_

Nella modalità di funzionamento normale, l'indicatore LED si accende nelle seguenti situazioni (per i modelli F1, invece, il LED lampeggia):

-   Quando viene rilevato un movimento in condizioni di batteria scarica
-   Quando il coperchio viene aperto e l'interruttore antimanomissione viene attivato.
-   Quando viene rilevato un movimento se la condizione di Tamper persiste.
-   Quando viene rilevato un movimento in modalità Test
-   Quando il pulsante Test viene premuto in condizione di manomissione o se il PIR ha la batteria scarica.
-   _Batteria_

Il sensore di movimento PIR serie IR-29 utilizza batterie alcaline o al litio come fonte di alimentazione:

-   I modelli ad alimentazione alcalina utilizzano due batterie alcaline AA da 1,5 V come fonte di alimentazione.
-   I modelli alimentati al litio utilizzano una batteria al litio da 3 V 2/3 A (EL123AP) come fonte di alimentazione.

Il PIR è dotato di funzione di rilevamento della batteria scarica. Se viene rilevata una tensione della batteria bassa, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.

Per ogni installazione, la batteria viene installata in fabbrica prima della spedizione con un isolante inserito.

\\<NOTE>

-   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _Iniziare_
-   Estrarre l'isolante della batteria per attivare la batteria.
-   L'indicatore LED lampeggerà per 30 secondi. (Il PIR si sta riscaldando). Durante il periodo di riscaldamento, il PIR non verrà attivato. Al termine del periodo di riscaldamento, il LED si spegnerà e il PIR sarà pronto per il funzionamento.
-   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
-   Premere il pulsante di prova sul coperchio anteriore.
-   Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.
-   Dopo aver appreso il PIR, inserire il Pannello di Controllo in “**Prova della camminata**", tenere il PIR nella posizione desiderata e premere il pulsante Test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
-   Quando sei soddisfatto che il PIR funzioni nella posizione scelta, puoi procedere al montaggio.
-   _Metodo di montaggio_
-   Il PIR è progettato per essere montato su una superficie piana o in una situazione d'angolo con viti di fissaggio e tasselli forniti.
-   ![](<.gitbook/assets/3 (5) (1).png>)La base è dotata di fori, dove la plastica è più sottile e può essere rotta per il montaggio. Due fori a sfondamento sono per il fissaggio in superficie e quattro fori a sfondamento sono per il fissaggio ad angolo, come mostrato in figura.
-   Per il montaggio ad angolo, viene fornita una staffa triangolare per aggiungere la protezione antimanomissione posteriore. La staffa include anche due fori per il montaggio a parete.
-   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Grazie alla staffa rotante, l'IR-29 può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
-   **Montaggio ad angolo:**

1.  Sfondare i quattro knockout d'angolo.
2.  Utilizzando i quattro fori come modello, praticare dei fori sulla superficie dell'angolo
3.  Inserire i tasselli
4.  Avvitare la base nel tassello a muro.
5.  ![](<.gitbook/assets/4 (5) (1).png>)Avvitare il coperchio sulla base.

-   **Montaggio ad angolo con staffa triangolare:**

La staffa triangolare può essere montata a parete tramite viti o cuscinetti biadesivi.

Montaggio a vite

1.  Sfondare i due fori sulla staffa triangolare.
2.  Utilizzando i due fori come modello, praticare dei fori sulla superficie dell'angolo. Inserire i tasselli.
3.  Avvita la staffa triangolare nei tasselli con i due bastoncini di puntamento in alto rivolti verso di te.
4.  Montare il PIR sui ganci della staffa triangolare.

Montaggio autoadesivo

1.  L'angolo di montaggio deve essere pulito, asciutto e liscio. Se necessario, pulire l'angolo di montaggio con uno sgrassatore adatto.
2.  Due cuscinetti biadesivi sono fissati sulla staffa triangolare prima della spedizione.
3.  Rimuovere la copertura protettiva dai cuscinetti biadesivi.
4.  Attacca la staffa triangolare all'angolo desiderato con i due bastoncini di puntamento in alto rivolti verso di te.
5.  Montare il PIR sui ganci della staffa triangolare.

-   **Montaggio su superficie:**

1.  Rimuovere la vite di fissaggio e il gruppo coperchio.
2.  ![](<.gitbook/assets/5 (4) (1).png>)Sfonda i fori all'interno della base
3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.
4.  Inserire i tasselli se si fissa su intonaco o mattoni.
5.  Avvitare la base nei tasselli.
6.  Avvitare il coperchio sulla base.

-   **Montaggio su superficie con staffa rotante (articolo opzionale, venduto separatamente):**

La staffa rotante può essere montata a parete tramite viti in dotazione.

1.  Avvitare la staffa rotante al muro.
2.  Montare opportunamente i 3 ganci della staffa rotante nei 3 fori della base.
3.  Ruotare la staffa per il campo di rilevamento corretto e serrare la vite di fissaggio.

-   _Installazione_
-   Decidi la posizione del PIR e se deve essere montato ad angolo o su superficie.
-   Dopo aver selezionato il sito di installazione, seguire i passaggi sopra descritti per montare il PIR.
-   Premere il pulsante Test per accedere alla modalità Test. Camminare attorno all'area protetta osservando quando il LED si accende e verificare che la copertura di rilevazione sia adeguata.
-   Quando la copertura di rilevamento risulta soddisfacente, l'installazione è completata.
-   _Raccomandazioni per l'installazione_

Il PIR è progettato per fornire un raggio di rilevamento tipico di 12 metri se montato a 2 metri dal suolo.

Per la serie Pet-Immune PIR, fornisce una portata tipica di PET IMMUNE di 7 metri se montato a 1,9-2,0 metri dal suolo. Se montato più in alto rispetto al suolo, offre una gamma PET IMMUNE più ampia.

Per sfruttare appieno il PIR, è necessario considerare le seguenti linee guida:

-   **Si consiglia di installare il PIR nelle seguenti posizioni**
-   Montare il rilevatore ad un'altezza di 1,9 M-2,0 M per ottenere le migliori prestazioni:

![](<.gitbook/assets/6 (7).png>)

\\<Important NOTE>

-   Per ottenere le prestazioni ottimali della serie Pet-Immune PIR, ricordarsi di regolare l'altezza del sito di montaggio PIR rispetto all'altezza dell'animale più alto della casa. Gli animali domestici più alti della media potrebbero richiedere che il PIR sia montato più in alto ai fini dell'immunità agli animali domestici.
-   Quando si decide l'altezza del luogo di montaggio del PIR, ricordarsi di prendere in considerazione il possibile punto cieco. L'angolo cieco sotto il PIR si allarga proporzionalmente all'altezza del sito di montaggio del PIR.
-   Tieni presente che le prestazioni sono influenzate da fattori esterni, come l'altezza dell'oggetto rilevato, il raggio di rilevamento desiderato, l'area di installazione, ecc. L'altezza di montaggio suggerita può essere regolata in base ai fattori reali dell'ambiente di installazione.
-   Quando l'IR-29 è montato con una staffa rotante, non avrà l'area di rilevamento normale (come nel diagramma sopra) o il tipico raggio d'azione immune agli animali domestici.
-   Montare in un punto in cui gli animali non possano raggiungere l'area di rilevamento arrampicandosi su mobili o altri oggetti.
-   Non puntare il rilevatore verso le scale su cui gli animali possono salire.
-   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR da un lato all'altro.
-   In un angolo per avere la visuale più ampia.
-   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
-   Non posizionare un PIR per guardare direttamente una porta protetta da un Contatto Porta, questo potrebbe causare la trasmissione dei segnali radio Contatto Porta e PIR nello stesso istante in cui si entra, annullandosi a vicenda.
-   Non installare il PIR completamente esposto alla luce solare diretta.
-   Evitare di installare il PIR in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
-   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
-   Not pointing directly at sources of heat e.g. fires or boilers, and not above radiators.
-   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.
