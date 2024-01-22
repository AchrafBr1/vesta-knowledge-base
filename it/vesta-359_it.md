# VESTA 359

**Manuale dell'utente del contatto porta cablato (DC-23-BUS).**

DC-23-BUS è un contatto porta cablato che monitora l'apertura/chiusura di dispositivi specifici (ad esempio, porta o finestra). Il contatto porta cablato è fissato al telaio del dispositivo monitorato con un magnete di azionamento fissato al dispositivo. Quando la porta o la finestra si apre, il magnete si allontana dal contatto porta cablato, attivando un interruttore magnetico interno che fa sì che il contatto porta cablato trasmetta segnali di allarme tramite BUS alla centrale.

Con un terminale di estensione integrato, DC-23-BUS può anche essere collegato a un dispositivo cablato per fungere anche da trasmettitore universale.

Il design del contatto porta cablato è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

**Identificazione delle parti**

![](<.gitbook/assets/0 (2).jpeg>)

1.  **Indicatore LED/pulsante Test**

Premere il pulsante Test per accedere alla modalità test per 3 minuti.

1.  **Vite di fissaggio del coperchio**
2.  **Interruttore ponticello di ingresso (JP2)**

![](<.gitbook/assets/1 (3).png>)

**Ponticello acceso****Ponticello spento**

![](<.gitbook/assets/2 (3).jpeg>)![](<.gitbook/assets/3 (1) (1).jpeg>)

Il collegamento del ponticello viene inserito, collegando i due Il collegamento del ponticello viene rimosso o “**parcheggiato**" nessuno

perni. spillo.

-   -   Jumper ON: è impostato Normalmente Chiuso (N.C.).
    -   Jumper OFF: è impostato Normalmente Aperto (N.O.).**(Impostazione di fabbrica)**.

1.  **Interruttore a ponticello della resistenza terminale**

Quando il contatto della porta è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del contatto della porta e l'interruttore del ponticello del primo dispositivo BUS (solitamente del pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/4 (2).png>)

**Ponticello acceso**

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su ON, la capacità di comunicazione verrà migliorata.
    -   Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.

1.  **Capolinea autobus**
2.  **Terminale di estensione**

Oltre all'interruttore magnetico integrato, viene fornito un terminale di contatto pulito aggiuntivo a 2 pin per un interruttore magnetico di estensione o qualsiasi dispositivo con contatto N.C. (normalmente chiuso) o N.A. (Normalmente aperto).

1.  **Interruttore antimanomissione**

Quando il contatto porta cablato è montato, l'interruttore antimanomissione verrà attivato quando il coperchio viene aperto o quando il contatto porta cablato viene rimosso dalla superficie di montaggio.

1.  **Fori di montaggio**

Utilizzato per fissare e avvitare il contatto porta direttamente sul telaio della porta o sul muro.

1

1.  **Area di separazione per fori di cablaggio (per terminal autobus)**
2.  **Magnete**
3.  **Foro per vite magnetica**
4.  **Distanziatore magnetico**

**Caratteristiche**

![](<.gitbook/assets/5 (4).png>)

-   _**Indicatore LED**_
    -   Nella modalità di funzionamento normale, il LED non si accende quando viene attivato il contatto porta cablato.
    -   Quando il coperchio del contatto porta cablato viene aperto o viene attivato l'interruttore antimanomissione, il LED lampeggerà 3 volte. Quando la condizione di manomissione continua, il LED lampeggerà 3 volte ogni volta che viene attivato il contatto porta cablato.
    -   Quando il contatto porta cablato è in modalità test, il LED lampeggerà 3 volte ogni volta che viene attivato.
-   _**Terminale di estensione**_

![](<.gitbook/assets/6 (2).png>)

DC-23-BUS è dotato di un terminale di estensione per fornire una maggiore flessibilità. A seconda dell'impostazione di JP2, il terminale dell'interno forma un circuito chiuso (normalmente chiuso (N.C.)) o aperto (normalmente aperto (N.A.)) con il dispositivo ad esso collegato. Quando il dispositivo collegato al terminale di estensione viene attivato, verrà attivato il contatto porta cablato.

| Per connettere il dispositivo al terminale dell'interno: | _**Vista dall'alto del DC-23-BUS**_ |   |
| -------------------------------------------------------- | ----------------------------------- | - |
|                                                          |                                     |   |

![](<.gitbook/assets/7 (1).jpeg>)

1.  Aprire il coperchio del contatto porta cablato con un cacciavite allentando la vite di fissaggio del coperchio nella parte inferiore del dispositivo.
2.  L'estremità superiore del case anteriore ha un foro in plastica più sottile. Attraversare il foro per creare un foro per il collegamento del cablaggio al terminale di estensione.
3.  Collegare il dispositivo al terminale dell'estensione.

![](<.gitbook/assets/8 (1).jpeg>)

Il terminale di estensione può essere utile per le seguenti situazioni:

-   Se il contatto porta cablato non può essere montato sul telaio della porta, è possibile collegare un interruttore magnetico di estensione aggiuntivo al terminale di estensione per montare il contatto porta in remoto.
-   Qualsiasi dispositivo a contatto pulito con un contatto N.C. (normalmente chiuso) o N.A. Il circuito (normalmente aperto) può essere collegato al terminale di estensione affinché il contatto porta cablato funga da trasmettitore universale.
-   È possibile collegare più dispositivi a contatto pulito insieme al contatto porta cablato, come mostrato nell'immagine seguente.

![](<.gitbook/assets/9 (5).png>)

-   _**Alimentazione elettrica**_
    -   Quando il DC-23-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.
-   _**Protezione antisabotaggio**_
    -   Il contatto porta cablato è protetto da un interruttore antimanomissione che viene compresso contro la superficie di montaggio quando il contatto porta cablato è montato in posizione. Ogni volta che il coperchio del contatto porta cablato viene aperto o rimosso dalla superficie di montaggio, l'interruttore antimanomissione verrà attivato e il contatto porta cablato invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione.
-   _**Segnale di vigilanza**_
    -   Il contatto porta cablato trasmetterà automaticamente periodicamente i segnali di supervisione alla centrale di controllo a intervalli casuali di 20-30 secondi.
    -   Se il pannello di controllo non ha ricevuto il segnale dal contatto porta cablato per un periodo di tempo prestabilito, il pannello di controllo indicherà che quel particolare contatto porta sta riscontrando un problema di segnale assente.
-   _**Modalità di prova**_
    -   In modalità normale, premere il pulsante Test per trasmettere un segnale di test al pannello di controllo. Il contatto porta cablato entrerà in modalità test per 3 minuti.
    -   In modalità test, il LED lampeggerà 3 volte ogni volta che viene attivato il contatto porta cablato.
    -   Ogni ulteriore pressione del pulsante Test ripristinerà il periodo della modalità test a 3 minuti.

![](<.gitbook/assets/10 (5).png>)![](<.gitbook/assets/11 (3).png>)![](<.gitbook/assets/12 (4).png>)

2

-   ![](<.gitbook/assets/13 (5).png>)_**Attenzione**_
    -   Il cablaggio del contatto porta deve essere eseguito solo da tecnici certificati con adeguata conoscenza e formazione in apparecchiature elettriche.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   _**Cablaggio del contatto della porta**_
    -   -   Prima di collegare il contatto porta cablato al BUS del sistema, spegnere l'alimentazione.
        -   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/14 (4).png>)![](<.gitbook/assets/15 (2).jpeg>)

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale tra i dispositivi della linea BUS collegati, assicurarsi che i ponticelli della resistenza terminale del primo (normalmente la centrale ibrida) e dei dispositivi BUS più lontani su una linea BUS siano impostati. su ON per fungere da resistori di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

_\\<NOTE>_

-   -   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
    -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o malfunzionamenti. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/16 (5).png>)

-   _**Apprendimento**_

Seguire i passaggi seguenti per apprendere il dispositivo al pannello ibrido.

Passaggio 1: collegare il dispositivo al pannello. Quindi, accendere il pannello.

Passaggio 2: nella pagina Web del pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3: fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

Passaggio 4: fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

Passaggio 5: Se il dispositivo viene acquisito con successo nel Pannello, verrà visualizzato nella sezione "Dispositivo acquisito".

-   Una volta acquisito nella centrale, il DC-23-BUS verrà riconosciuto come 2 dispositivi separati e occuperà 2 zone nella centrale.

![](<.gitbook/assets/17 (3).png>)

3

![](<.gitbook/assets/18 (5).png>)

-   Per differenziare i 2 dispositivi separati, si consiglia di rinominare il nome del dispositivo con

facendo clic su "Modifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo.

Come mostrato nella pagina Modifica dispositivo, l'ID con le ultime due cifre di "**00**" rappresenta l'interruttore magnetico interno.

![](<.gitbook/assets/19 (4).png>)

L'ID con le ultime due cifre di "**02**" rappresenta il terminale di estensione.

![](<.gitbook/assets/20 (4).png>)

-   _**Identificazione**_

La funzione “Identifica” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il Contatto Porta Cablato nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo del DC-23-BUS.

**Passo 2.**Se il contatto porta cablato riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED del contatto porta cablato lampeggerà 10 volte per indicare all'utente dove si trova.

_\\<NOTE>_

-   -   -   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il contatto porta cablato non ha ricevuto il segnale dal pannello.

Verificare se il DC-23-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Prova della camminata**_
    -   Per assicurarsi che il contatto porta cablato sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale di controllo in modalità Walk Test e premere il pulsante Test sul DC-23-BUS per trasmettere un segnale di test alla centrale.
    -   Quando la centrale riceve il segnale di test, emetterà un segnale acustico e visualizzerà di conseguenza le informazioni del contatto porta cablato in cima all'elenco dei dispositivi.

_\\<NOTE>_

-   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se il DC-23-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Installazione**

-   _**Linee guida per l'installazione**_
    -   Il contatto porta cablato deve essere installato sul telaio della porta/finestra e il magnete sulla porta/finestra
    -   La distanza tra il contatto porta cablato e il magnete non deve essere superiore a 15 mm quando la porta è chiusa.
    -   Evitare di montare il contatto porta cablato su superfici metalliche. Se montato su superfici metalliche, assicurarsi di verificare se il contatto porta cablato può essere attivato quando la porta viene aperta.
    -   Montare il contatto porta cablato il più in alto possibile.
-   _**Montaggio del contatto porta cablato**_

1.  Trova una posizione adatta vicino alla porta/finestra per installare il contatto porta cablato.
2.  Il contatto porta cablato presenta 2 contrassegni su un lato (fare riferimento alla figura), che indicano la posizione dell'interruttore magnetico interno. Il contatto porta cablato deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.
3.  Per montare il contatto porta cablato:
    -   1.  Utilizzare i 2 fori di montaggio come modello e praticare i fori nel telaio da montare.
        2.  Utilizzare i tasselli forniti per l'installazione su intonaco/mattone.
        3.  Avvitare il contatto della porta nei tasselli forniti.
4.  Per montare il magnete:
    1.  Utilizzare i 2 fori per le viti magnetiche come modello e praticare i fori nella porta/finestra da montare.

-   _NOTA >_
    -   Il magnete non deve trovarsi a più di 15 mm dal contatto porta cablato quando la porta è chiusa.
    -   Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta cablato. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.
    -   Avvitare il magnete sulla porta/finestra.
    -   Inserire i due cappucci bianchi nei fori delle viti del magnete per garantire l'integrità estetica.

1.  L'installazione è ora completa.

4
