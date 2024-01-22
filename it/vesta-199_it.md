# VESTA199

**Manuale dell'utente del contatto porta (DC-16SL).**

Il contatto porta monitora l'apertura/chiusura di dispositivi specifici (ad esempio porta o finestra). Il contatto porta è fissato al telaio del dispositivo monitorato con un magnete di azionamento fissato al dispositivo. Quando la porta o la finestra si apre, il magnete si allontana dal contatto porta, attivando un interruttore magnetico interno che fa sì che il contatto porta trasmetta il segnale di allarme al pannello di controllo. Il dispositivo ha anche la capacità di comunicare problemi di segnale insieme a situazioni di batteria scarica.

Il design del contatto porta è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

**Il Contatto Porta comprende i seguenti modelli di frequenza:**

**433 m**

**433FM F1**

**868WF**

**868FM**

**868FMF1**

**869FM**

**869F1**

![](<.gitbook/assets/0 (80).jpeg>)

-   _**Identificazione delle parti**_

![](<.gitbook/assets/1 (60).png>)

1.  **Indicatore LED**
2.  **Pulsante Impara/Test**

\-Premere il pulsante Test per trasmettere un codice di apprendimento.

\-Premere una volta il pulsante Test per accedere alla modalità Test per 3 minuti.

1.  **Interruttore Jumper di supervisione (JP2)**

**Ponticello acceso**

![](<.gitbook/assets/2 (65).jpeg>)

**Ponticello spento**

![](<.gitbook/assets/3 (59).jpeg>)

Il collegamento del ponticello viene inserito se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

~~-~~Quando il ponticello è impostato su ON, la supervisione è disabilitata.**(Impostazione di fabbrica per 433AM)**

\-Quando il ponticello è impostato su OFF, la supervisione è abilitata.**(Impostazione di fabbrica per i modelli 868WF, 868FM, 869FM)**

_**I modelli 433FM-F1, 868FM-F1 e 869-F1 non hanno questo ponticello installato e la supervisione è sempre abilitata**_

1.  **Batteria**
2.  **Foro per vite di fissaggio del coperchio**
3.  **Eliminazioni**
4.  **Interruttore antimanomissione**
5.  **Foro isolante della batteria**
6.  **Segni di costole**
7.  **Magnete**

\-Montare il magnete sul lato del contatto porta dove sono presenti 2 segni di nervatura per indicare la posizione dell'interruttore magnetico interno. Il contatto porta deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.

1

-   1.  **Foro per vite magnetica**
    2.  **Distanziatore magnetico**
-   _**Accessori inclusi**_
    -   1.  1 magnete
        2.  2 viti
        3.  1 tampone biadesivo
        4.  2 tasselli
        5.  2 viti di montaggio del magnete
        6.  1 distanziatore magnetico
        7.  2 tappi bianchi
-   _**Indicatore LED**_

![](<.gitbook/assets/4 (55).jpeg>)![](<.gitbook/assets/5 (36).jpeg>)

Nella modalità di funzionamento normale, l'indicatore LED rimane spento tranne nelle seguenti situazioni:

-   -   Quando l'interruttore antimanomissione del contatto porta viene attivato.
    -   Ogni volta che il contatto della porta viene attivato in caso di manomissione o di batteria scarica.
    -   Ogni volta che il contatto della porta viene attivato e trasmette il segnale in modalità test.
-   _**Supervisione**_
    -   Se abilitato, il contatto porta trasmetterà automaticamente periodicamente i segnali di supervisione alla centrale di controllo a intervalli casuali da 30 a 50 minuti in modalità di funzionamento normale.
    -   Se il pannello di controllo non ha ricevuto il segnale dal contatto della porta per un periodo di tempo preimpostato, il pannello di controllo indicherà che quel particolare contatto della porta sta riscontrando un problema di segnale assente.
-   _**Interruttore antimanomissione**_
    -   È progettato per proteggere dalla rimozione non autorizzata dalla posizione di montaggio, dall'apertura del coperchio o da un'installazione instabile. Quando viene attivato il tamper, il contatto porta emetterà un segnale alla centrale di controllo per la segnalazione, inoltre il LED si accenderà.
-   _**Batteria**_

![](<.gitbook/assets/6 (45).jpeg>)![](<.gitbook/assets/7 (42).jpeg>)![](<.gitbook/assets/8 (38).jpeg>)

Il contatto della porta ne utilizza uno**Batteria al litio CR2 da 3 V**come fonte di alimentazione, è anche in grado di rilevare la batteria scarica. Quando la batteria è scarica, un segnale di batteria scarica verrà inviato alla centrale insieme alla trasmissione regolare. Il LED si accenderà quando il contatto della porta viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il contatto della porta interromperà tutte le funzioni e il LED lampeggerà ogni 4 secondi.

-   **Sostituzione della batteria:**

Dopo aver rimosso la batteria, premere il pulsante Impara/Test 5-6 volte per scaricarla completamente prima di inserire la nuova batteria.

![](<.gitbook/assets/9 (39).png>)

_\\<NOTE>_

-   -   A causa delle caratteristiche della batteria, dopo aver inserito una nuova batteria nel contatto porta, controllerà automaticamente se questa batteria funziona correttamente o meno entro 16 minuti dall'inserimento.
-   _**Modalità di prova**_

![](<.gitbook/assets/10 (22).jpeg>)

Il contatto della porta può essere messo in modalità test per 3 minuti premendo una volta il pulsante test sul coperchio anteriore. Durante la modalità Test, l'indicatore LED si accenderà al momento dell'attivazione. Ad ogni pressione del pulsante Test, il contatto della porta trasmetterà un segnale di test al pannello di controllo per il test della portata radio e ripristinerà la modalità test alla durata di 3 minuti. Uscirà automaticamente dalla modalità test dopo 3 minuti e ritornerà alla modalità di funzionamento normale.

![](<.gitbook/assets/11 (25).jpeg>)

-   _**Iniziare**_

Passaggio 1: estrarre costantemente l'isolante della batteria

Passo 2: Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.

Passaggio 3: premere il pulsante Test sul contatto della porta per inviare il segnale al pannello di controllo.

Passo 4: Se il Pannello di Controllo riceve correttamente il segnale, il Pannello di Controllo dovrebbe rispondere (ad esempio emettendo dei segnali acustici). Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.

Passaggio 5: dopo aver appreso il contatto della porta, inserire il pannello di controllo in "**Prova della camminata**”, tenere premuto il contatto della porta

nella posizione desiderata e premere il pulsante Test per confermare se questa posizione rientra nel raggio del segnale del pannello di controllo.

Passaggio 6: quando sei soddisfatto del contatto porta nella posizione scelta, procedi con l'installazione.

![](<.gitbook/assets/12 (21).jpeg>)

-   _**Installazione**_

Passaggio 1: montare il contatto della porta utilizzando uno dei metodi seguenti.

Passaggio 2: montare il magnete sull'oggetto più mobile (come una porta) utilizzando le viti fornite.

Allineare il magnete in base al segno della nervatura sul contatto porta.

Ove necessario, utilizzare il distanziatore magnetico per allineare meglio il magnete ai segni delle nervature.

![](<.gitbook/assets/13 (28).png>)

-   _NOTA >_
    -   Il magnete non dovrebbe essere più di**15 mm**dal rilevatore quando la porta è chiusa.
    -   I due cappucci bianchi forniti possono essere inseriti nei fori delle viti del magnete per integrità estetica.

2

-   ![](<.gitbook/assets/14 (21).jpeg>)_**Metodi di montaggio**_

Esistono due modi per montare il contatto porta: montaggio autoadesivo o montaggio con viti.

![](<.gitbook/assets/15 (19).jpeg>)

-   **Montaggio autoadesivo**

I.La superficie di montaggio deve essere pulita, asciutta e liscia. Pulisci il

superficie di montaggio con uno sgrassatore adatto, se necessario.

1.  Rimuovere la copertura protettiva da un lato del cuscinetto biadesivo. Applicare sul retro del dispositivo e premere con decisione

30 secondi per garantire un buon contatto.

1.  Rimuovere l'altro coperchio e premere con decisione il contatto della porta

la posizione desiderata per 30 secondi.

![](<.gitbook/assets/16 (27).png>)

_\\<NOTE>_

-   -   Non utilizzare il metodo di installazione del tampone adesivo su una superficie con vernice scrostata o screpolata o su una superficie ruvida.
    -   Si prega di non riapplicare il nastro adesivo 3M. Non può essere riutilizzato
    -   Installare il contatto della porta sull'oggetto più fisso (come il telaio della porta o della finestra) e montare il magnete sull'oggetto più mobile (come la porta o la finestra).
-   **Montaggio a vite**

La base ha due fori, dove la plastica è più sottile, per il montaggio. Per montare il contatto porta:

-   -   1.  Rimuovere il coperchio svitando la vite di fissaggio del coperchio utilizzando un cacciavite a croce.

![](<.gitbook/assets/17 (18).jpeg>)

1.  Sfonda il knockout sulla base.
2.  Utilizzando i fori come modello, praticare entrambi i fori.

IV. Inserire i tasselli se si fissa su intonaco o mattoni.

1.  Avvitare la base nella presa a muro utilizzando un cacciavite Philips.

VI. Attaccare il coperchio alla base e serrare la vite di fissaggio del coperchio.

3
