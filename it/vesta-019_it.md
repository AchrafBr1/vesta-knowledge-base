# VESTA019

Manuale utente Contatto porta (DC-23 / DC-23-R3).

Il contatto porta monitora l'apertura/chiusura di dispositivi specifici (ad esempio porta o finestra). Il contatto porta è fissato al telaio del dispositivo monitorato con un magnete di azionamento fissato al dispositivo. Quando la porta o la finestra si apre, il magnete si allontana dal contatto porta, attivando un interruttore magnetico interno che fa sì che il contatto porta trasmetta il segnale di allarme al pannello centrale. Il dispositivo ha anche la capacità di comunicare problemi di segnale insieme a situazioni di batteria scarica.

Il design del contatto porta è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

Il contatto per porta serie DC-23 comprende i seguenti modelli:

DC-23: Il coperchio del contatto della porta è fissato da una vite di fissaggio inferiore.

DC-23-R3: il coperchio del contatto della porta è fissato da due fermi nella parte superiore e inferiore

![](<.gitbook/assets/0 (3) (1).jpeg>)

Identificazione delle parti

1.  **Indicatore LED/pulsante Test**

Premere il pulsante Test per trasmettere il codice di apprendimento o accedere alla modalità test per 3 minuti.

1.  **Fori di montaggio**

Utilizzato per fissare e avvitare il contatto della porta direttamente sul telaio della porta o sul muro.

1.  **Interruttore antimanomissione**

Quando il contatto della porta è montato, l'interruttore antimanomissione verrà attivato quando il coperchio viene aperto o quando il contatto della porta viene rimosso dalla superficie montata.

1.  **Isolante della batteria**
2.  **Interruttore Jumper di supervisione (JP2)**

**(**_**Solo modello 868WF**_**)**

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**” on one pin.

**Ponticello acceso**

Viene inserito il ponticello che collega i due pin

![jumper close](<.gitbook/assets/1 (10).png>)![jumper open](<.gitbook/assets/2 (11).png>)

-   Jumper ON: Supervisione disabilitata
-   Jumper OFF: Supervisione abilitata.**(Impostazione di fabbrica)**

1.  **Interruttore a ponticello con interruttore reed (JP3)**

![jumper close](<.gitbook/assets/3 (10).png>)![jumper open](<.gitbook/assets/4 (10).png>)

**Ponticello acceso**

Viene inserito il ponticello che collega i due pin

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   Jumper ON: Interruttore Reed disabilitato. Solo il dispositivo collegato al terminale di estensione attiverà il contatto della porta
-   Jumper OFF: Interruttore Reed abilitato.**(Impostazione di fabbrica per tutti i modelli)**

1.  **Terminale di estensione**

Oltre all'interruttore magnetico integrato, viene fornito un terminale di contatto pulito aggiuntivo a 2 pin per un interruttore magnetico di estensione o qualsiasi dispositivo con funzionalità N.C. (normalmente chiuso).

1.  ![](<.gitbook/assets/5 (7) (1).png>)**Compartimento della batteria**
2.  **Magnete**
3.  **Foro per vite magnetica**
4.  **Distanziatore magnetico**

Caratteristiche

-   _**Indicatore LED**_
-   Nella modalità di funzionamento normale, il LED non si accende quando viene attivato il contatto della porta.
-   Quando la tensione della batteria del Contatto Porta è bassa, ogni volta che il Contatto Porta viene attivato (dispositivo aperto/chiuso), il LED si accenderà per 2 secondi.
-   Quando il coperchio viene aperto o viene attivato l'interruttore antimanomissione, il LED si accenderà per 2 secondi. Quando la condizione di manomissione persiste, il LED si accenderà per 2 secondi ogni volta che viene attivato il contatto della porta.
-   Quando il Contatto Porta è in modalità Test, il LED si accenderà ogni volta che viene attivato.
-   Quando la batteria è scarica, il contatto della porta interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
-   _**Terminale di estensione**_

Il contatto porta è dotato di un terminale di estensione per fornire una maggiore flessibilità. Il terminale dell'estensione forma un circuito chiuso con il dispositivo ad esso collegato. Quando il dispositivo viene attivato, il circuito viene aperto, verrà attivato anche il contatto della porta.

Il terminale di estensione e l'interruttore magnetico interno possono funzionare insieme per attivare il contatto della porta quando uno di essi è attivato, è anche possibile scegliere di disabilitare l'interruttore magnetico interno tramite l'impostazione del ponticello JP3.

Per connettere il dispositivo al terminale dell'interno:

![](<.gitbook/assets/6 (4) (1).jpeg>)**Per il modello DC-23:**

1.  Aprire il coperchio del contatto porta utilizzando un cacciavite per allentare la vite di fissaggio del coperchio nella parte inferiore del coperchio del contatto porta. (Vedi l'immagine sotto dall'angolo di visione superiore).
2.  L'estremità superiore del case anteriore ha un foro in plastica più sottile. Attraversare il foro per creare un foro per il collegamento del cablaggio al terminale di estensione.
3.  Collegare il dispositivo al terminale dell'estensione

**Per il modello DC-23-R3:**

1.  ![](<.gitbook/assets/7 (3) (1).jpeg>)Usa il pollice per premere sulla chiusura, mentre la premi, estrai il coperchio dalla base del contatto porta (vedi immagine sotto dall'angolo di vista superiore).
2.  L'estremità superiore del case anteriore ha un foro in plastica più sottile. Attraversare il foro per creare un foro per il collegamento del cablaggio al terminale di estensione.
3.  Collegare il dispositivo al terminale dell'estensione

Il terminale Interno può essere utile per la seguente situazione.

-   Se il contatto porta non può essere montato sul telaio della porta, è possibile collegare un ulteriore interruttore magnetico di estensione al terminale di estensione per montare il contatto porta in remoto.
-   Qualsiasi dispositivo a contatto pulito con circuito N.C. (normalmente chiuso) può essere collegato al terminale di estensione facendo in modo che il contatto della porta funga da trasmettitore universale.
-   È possibile cablare più dispositivi a contatto pulito insieme al contatto porta, come mostrato nello schema seguente.

![](<.gitbook/assets/8 (2) (1).png>)

-   Il terminale di estensione e l'interruttore magnetico interno possono funzionare insieme per attivare il contatto della porta quando uno di essi è attivato, è anche possibile scegliere di disabilitare l'interruttore magnetico interno tramite l'impostazione del ponticello JP3. Se sono in uso sia il terminale di estensione che l'interruttore magnetico interno e uno di essi viene attivato (aperto). Il contatto porta invierà il segnale di chiusura (ripristino) del contatto porta solo quando entrambi sono chiusi.
-   _**Batteria**_
-   Il contatto porta è alimentato da una batteria al litio CR123 da 3 V. Notare che:**SEMPRE**sostituire la batteria con la dimensione e il voltaggio corretti.
-   Il contatto della porta è in grado di rilevare la condizione di batteria scarica. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per notificare la condizione. Il LED si accenderà quando il contatto della porta viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il contatto della porta interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
-   Quando si cambia la batteria, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarla completamente prima di inserire la nuova batteria.
-   _**Protezione antisabotaggio**_
-   Il contatto porta è protetto da un interruttore antimanomissione che viene compresso contro la superficie di montaggio quando il contatto porta è montato. Ogni volta che il coperchio del contatto della porta viene aperto o rimosso dalla superficie montata, l'interruttore antimanomissione verrà attivato e il contatto della porta invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione.
-   _**Segnale di vigilanza**_
-   La funzione di supervisione per il modello 868WF è controllata dall'impostazione del ponticello JP2. Per il modello diverso da 868WF, la funzione di supervisione è sempre abilitata.
-   Quando abilitato, il Contatto Porta trasmetterà automaticamente periodicamente i Segnali di Supervisione alla Centrale di Controllo ad intervalli casuali di 30-50 minuti.
-   Se il pannello di controllo non ha ricevuto il segnale dal contatto della porta per un periodo di tempo preimpostato, il pannello di controllo indicherà che il particolare contatto della porta sta riscontrando un problema di segnale assente.
-   _**Modalità di prova**_
-   In modalità normale, premere il pulsante Test per trasmettere un segnale di test e un codice di apprendimento al pannello di controllo. Anche il contatto della porta entrerà in modalità test per 3 minuti.
-   In modalità test, il LED si accende ogni volta che viene attivato il contatto della porta.
-   Ogni ulteriore pressione del pulsante Test ripristinerà il tempo della modalità test a 3 minuti.
-   _**Iniziare**_
-   Aprire il coperchio del contatto porta e inserire la batteria.
-   Mettere il pannello di controllo in modalità apprendimento (fare riferimento al manuale operativo del pannello).
-   Premere il pulsante di test del contatto porta.
-   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
-   Dopo aver appreso il contatto della porta, posizionare il pannello di controllo in (**Prova di camminata)**modalità, tenere il contatto della porta nella posizione desiderata e premere il pulsante Test per trasmettere il segnale di test al pannello di controllo. Se il pannello di controllo si trova nel raggio d'azione del segnale del contatto della porta, il pannello visualizzerà di conseguenza le informazioni sul contatto della porta.
-   Procedere con il montaggio e l'installazione una volta accertato che la posizione del contatto della porta funzioni correttamente.

Installazione

-   _Linee guida per l'installazione_
-   Il contatto porta deve essere installato sul telaio della porta/finestra e il magnete sulla porta/finestra
-   La distanza tra il contatto della porta e il magnete non deve essere superiore a 15 mm quando la porta è chiusa.
-   Evitare di montare il contatto porta su una superficie metallica. In caso di montaggio su una superficie metallica, verificare se il contatto della porta può essere attivato quando la porta viene aperta.
-   Montare il contatto porta il più in alto possibile.
-   _**Montaggio del contatto porta**_

1.  Trovare una posizione adatta vicino alla porta/finestra per installare il contatto porta.
2.  Il contatto della porta presenta 2 contrassegni su un lato (fare riferimento alla figura), che indicano la posizione dell'interruttore magnetico interno. Il contatto della porta deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.
3.  Per montare il contatto porta:
4.  Utilizzare i 2 fori di montaggio del contatto porta come modello per il posizionamento appropriato dei fori.
5.  Utilizzare i tasselli forniti per l'installazione su intonaco/mattone.
6.  Avvitare il contatto della porta nei tasselli forniti.
7.  Per montare il magnete:
8.  Utilizzare i 2 fori per le viti magnetiche come modello per il posizionamento appropriato dei fori.

&lt;Nota>

-   Il magnete non deve trovarsi a più di 15 mm dal contatto della porta quando la porta è chiusa.
-   Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.

1.  Avvitare il magnete sulla porta.
2.  Inserire i due cappucci bianchi nei fori delle viti del magnete per garantire l'integrità estetica.
3.  L'installazione è ora completa.

![](<.gitbook/assets/9 (4) (1).png>)

Dichiarazione FCC

Questo dispositivo è conforme alla Parte 15 delle norme FCC. Il funzionamento è soggetto alle seguenti due condizioni:

(1) Questo dispositivo non può causare interferenze dannose e

(2) Questo dispositivo deve accettare qualsiasi interferenza ricevuta, comprese le interferenze che potrebbero causare un funzionamento indesiderato.

Attenzione FCC:

Per garantire la conformità continua, eventuali cambiamenti o modifiche non espressamente approvati dalla parte responsabile della conformità potrebbero invalidare il diritto dell'utente a utilizzare questa apparecchiatura. (Esempio: utilizzare solo cavi di interfaccia schermati per il collegamento al computer o ai dispositivi periferici).
