# VESTA 200

**Manuale dell'utente del contatto porta (DC-15SL-2W-F1).**

Il contatto porta monitora l'apertura/chiusura di dispositivi specifici (ad esempio porta o finestra). Il contatto porta è fissato al telaio del dispositivo monitorato con un magnete di azionamento fissato al dispositivo. Quando la porta o la finestra si apre, il magnete si allontana dal contatto porta, attivando un interruttore magnetico interno che fa sì che il contatto porta trasmetta il segnale di allarme al pannello centrale. Il dispositivo ha anche la capacità di comunicare problemi di segnale insieme a situazioni di batteria scarica.

Il design del contatto porta è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

Il Contatto Porta è un dispositivo di trasmissione del segnale radio bidirezionale. Quando il contatto della porta viene attivato ma non ha ricevuto il riconoscimento dal pannello di controllo, il contatto della porta invierà nuovamente il segnale per garantire che il pannello riceva correttamente la notifica.

![](<.gitbook/assets/0 (81).jpeg>)

_**Identificazione delle parti**_

1.  **Indicatore LED/pulsante Test**

Premere il pulsante Test per trasmettere il codice di apprendimento o accedere alla modalità test per 3 minuti.

1.  **Fori di montaggio**

Utilizzato per fissare e avvitare il contatto della porta direttamente sul telaio della porta o sul muro.

1.  **Isolante della batteria**
2.  **Interruttore antimanomissione**

Fornisce protezione antimanomissione contro l'apertura e/o la rimozione non autorizzata del dispositivo dalla superficie di montaggio.

_**Interruttore e terminale interni**_

Allentare la vite di fissaggio inferiore e rimuovere il coperchio per rivelare il terminale come mostrato.

1.  **Terminale di estensione**

Oltre all'interruttore magnetico integrato, viene fornito un terminale di contatto pulito aggiuntivo a 2 pin per un interruttore magnetico di estensione o qualsiasi dispositivo con funzionalità N.C. (normalmente chiuso).

![](<.gitbook/assets/1 (71).jpeg>)![](<.gitbook/assets/2 (66).jpeg>)

**Ponticello acceso****Ponticello spento**

Il collegamento del ponticello viene inserito se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   1.  **Interruttore a ponticello con interruttore magnetico interno (JP3)**
        -   Quando il ponticello è impostato su ON, l'interruttore magnetico interno è disabilitato. Solo il dispositivo collegato al terminale di estensione attiverà il contatto della porta
        -   Quando il ponticello è impostato su OFF, l'interruttore magnetico interno è abilitato.

**(Impostazione di fabbrica per tutti i modelli)**

-   1.  **Magnete**
        -   Montare il magnete sul lato del contatto porta dove sono presenti 2 segni di nervatura per indicare la posizione dell'interruttore magnetico interno. Il contatto porta deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.
    2.  **Foro per vite magnetica**
    3.  **Distanziatore magnetico**
-   _**Accessori inclusi**_

![](<.gitbook/assets/3 (60).jpeg>)

-   -   1.  1 magnete e distanziatore magnetico
        2.  Berretti bianchi
        3.  Viti
        4.  2 tasselli
-   _**Indicatore LED**_
    -   Nella modalità di funzionamento normale, il LED non si accende quando viene attivato il contatto della porta.
    -   Quando la tensione della batteria del Contatto Porta è bassa, ogni volta che il Contatto Porta viene attivato (dispositivo aperto/chiuso), il LED si accenderà per 2 secondi.

1

-   -   Quando il coperchio viene aperto o viene attivato l'interruttore antimanomissione, il LED si accenderà per 2 secondi. Quando la condizione di manomissione persiste, il LED si accenderà per 2 secondi ogni volta che viene attivato il contatto della porta.
    -   Quando il contatto porta è in modalità test, il LED si accenderà ogni volta che viene attivato.
    -   Quando la batteria è scarica, il contatto della porta interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
-   _**Batteria**_
    -   Il contatto della porta ne utilizza uno**Batteria al litio CR2, 3 V**come fonte di energia. Notare che:**SEMPRE**sostituire la batteria con la dimensione e il voltaggio corretti.
    -   Il contatto della porta è in grado di rilevare la condizione di batteria scarica. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per notificare la condizione. Il LED si accenderà quando il contatto della porta viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il contatto della porta interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
    -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _**Segnale di vigilanza**_
    -   Il Contatto della Porta trasmetterà automaticamente periodicamente i Segnali di Supervisione alla Centrale di Controllo ad intervalli casuali di 90-110 minuti.
    -   Se il pannello di controllo non ha ricevuto il segnale dal contatto della porta per un periodo di tempo preimpostato, il pannello di controllo indicherà che il particolare contatto della porta sta riscontrando un problema di segnale assente.
-   _**Modalità di prova**_
    -   In modalità normale, premere il pulsante Test per trasmettere un segnale di test e un codice di apprendimento al pannello di controllo. Anche il contatto della porta entrerà in modalità test per 3 minuti.
    -   In modalità test, il LED si accende ogni volta che viene attivato il contatto della porta.
    -   Ogni ulteriore pressione del pulsante Test ripristinerà il tempo della modalità test a 3 minuti.
-   _**Iniziare**_
    -   Estrarre l'isolante della batteria per attivare la batteria.
    -   Mettere il pannello di controllo in modalità apprendimento (fare riferimento al manuale operativo del pannello).
    -   Premere il pulsante di test del contatto porta.
    -   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
    -   Dopo aver appreso il contatto della porta, posizionare il pannello di controllo in (**Prova di camminata)**modalità, tenere il contatto della porta nella posizione desiderata e premere il pulsante Test per trasmettere il segnale di test al pannello di controllo. Se il pannello di controllo si trova nel raggio del segnale del contatto della porta, il pannello visualizzerà di conseguenza le informazioni sul contatto della porta.
    -   Procedere con il montaggio e l'installazione una volta accertato che la posizione del contatto della porta funzioni correttamente.
-   _**Metodi di montaggio e installazione**_

Si consiglia di posizionare il contatto porta sul telaio della porta/finestra e il magnete sulla porta/finestra.

Passaggio 1: trovare una posizione adatta vicino alla porta/finestra per installare il contatto porta. Effettuare un test di copertura per verificare se la posizione rientra nel raggio del segnale del pannello di controllo.

Passo 2: Il contatto della porta presenta 2 contrassegni su un lato (fare riferimento alla figura), che indicano la posizione dell'interruttore magnetico interno. Il contatto della porta deve essere installato in posizione verticale o invertita, per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.

Passaggio 3: per montare il contatto porta:

1.  Remove the white caps covering the two mounting holes.
2.  Utilizzare i 2 fori di montaggio come modello per il posizionamento appropriato dei fori.
3.  Utilizzare i tasselli forniti per l'installazione su intonaco/mattone.
4.  Avvitare il contatto porta nei tasselli forniti utilizzando un cacciavite Philips.
5.  Riposizionare i cappucci bianchi per coprire i due fori di montaggio.
    -   _NOTA >_
        -   Assicurarsi che la molla dell'interruttore antimanomissione sia posizionata in modo che entri in contatto con la superficie di montaggio attraverso l'apertura dell'interruttore antimanomissione.

![](<.gitbook/assets/4 (56).jpeg>)

Passaggio 4: per montare il magnete:

(i) Utilizzare i 2 fori per le viti magnetiche come modello per il posizionamento appropriato dei fori.

2

-   _NOTA >_
    -   Il magnete non deve trovarsi a più di 15 mm dal contatto della porta quando la porta è chiusa.
    -   Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.

![](<.gitbook/assets/5 (37).jpeg>)

1.  Avvitare il magnete sulla porta.
2.  Inserire i due cappucci bianchi nei fori delle viti del magnete per garantire l'integrità estetica. Passaggio 5: l'installazione è ora completa.

-   _**Utilizzando il terminale di estensione**_

Il contatto porta è dotato di un terminale di estensione per fornire una maggiore flessibilità. Il terminale dell'estensione forma un circuito chiuso con il dispositivo ad esso collegato. Quando il dispositivo viene attivato, il loop verrà aperto; verrà attivato anche il Contatto Porta.

![](<.gitbook/assets/6 (46).jpeg>)

Il terminale di estensione e l'interruttore magnetico interno possono funzionare insieme per attivare il contatto della porta quando uno di essi è attivato, è anche possibile scegliere di disabilitare l'interruttore magnetico interno tramite l'impostazione del ponticello JP3.

Per connettere il dispositivo al terminale dell'interno:

1.  Aprire il contatto porta allentando la vite di fissaggio utilizzando un cacciavite Philips.
2.  L'estremità superiore del case anteriore ha un foro in plastica più sottile. Attraversare il foro per creare un foro per il collegamento del cablaggio al terminale di estensione.
3.  Collegare il dispositivo al terminale dell'estensione

Il terminale Interno può essere utile per la seguente situazione.

-   Se il contatto della porta non può essere montato sul telaio della porta, è possibile collegare un interruttore di estensione aggiuntivo al terminale di estensione per montare il contatto della porta in remoto.
-   Qualsiasi dispositivo a contatto pulito con circuito N.C. (normalmente chiuso) può essere collegato al terminale di estensione facendo in modo che il contatto della porta funga da trasmettitore universale.
-   È possibile cablare più dispositivi a contatto pulito insieme al contatto porta, come mostrato nello schema seguente.

![](<.gitbook/assets/7 (43).jpeg>)![](<.gitbook/assets/8 (39).jpeg>)

_\\<NOTE>_

-   **Se sia l'interruttore magnetico interno che il terminale di estensione funzionano insieme, allora:**

Quando la porta protetta viene aperta/chiusa**O**il dispositivo esterno viene attivato, il Contatto Porta si attiva e trasmette immediatamente un segnale.

Tuttavia, il Contatto porta trasmetterà solo a**Porta chiusa**O**Restaurato**segnale dopo entrambe le porte**E**il dispositivo esterno viene ripristinato per 3 sec.

3
