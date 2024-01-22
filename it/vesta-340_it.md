# VESTA 340

**Modulo di espansione uscite programmabili serie WEPC-1**

**introduzione**

Il modulo di espansione di uscite programmabili serie WEPC-1 è progettato per fornire uscite programmabili per la centrale ibrida. Collegato alla Centrale Ibrida tramite connessione BUS, dispone di 4 uscite relè programmabili, utilizzabili in abbinamento alle centrali compatibili. La serie WEPC-1 è dotata di una propria custodia, dotata di protezione antimanomissione e indicatori di stato LED.

**Il modulo di espansione di uscite programmabili serie WEPC-1 include i seguenti modelli:**

**WEPC-1**– Modulo di espansione uscite programmabili

**WEPC-1B**– Modulo di espansione uscite programmabili con pacco batterie ricaricabili

**Identificazione delle parti**

**Vista frontale****Vista posteriore**

![](<.gitbook/assets/0 (18).jpeg>)

**Vista interna**

![](<.gitbook/assets/1 (12).jpeg>)

1

1.  **LED di alimentazione (rosso)**

Acceso: alimentato da un adattatore di alimentazione da 12 V o da un pannello ibrido.

Spento – Quando l'alimentazione è spenta o quando è alimentata da una batteria ricaricabile.

1.  **Zona 1~4 LED (rosso)**

Il LED della zona corrispondente si accenderà quando l'interruttore di uscita relè a contatto pulito è acceso e la luce LED si spegnerà quando l'interruttore viene spento.

1.  **LED di trasmissione (rosso)**

Si accende quando la connessione tra il modulo di espansione e il pannello di controllo è normale.

1.  **Zona separatista**

Quando il modulo di espansione viene rimosso con la forza dalla posizione di montaggio, l'area si stacca e consente l'attivazione dell'interruttore antimanomissione.

1.  **Interruttore antimanomissione (per montaggio a parete)**

Il modulo di espansione è protetto dall'interruttore antimanomissione contro qualsiasi rimozione non autorizzata dalla posizione di montaggio.

1.  **Fori di montaggio**
2.  **Foro di cablaggio**
3.  **Terminale di collegamento della batteria (solo per WEPC-1B)**

Per collegare la batteria ricaricabile al PCB.

1.  **Interruttore ponticello resistenza terminale (J3)**

Quando il modulo di espansione è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del modulo di espansione e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

-   Portare il ponticello su OFF rimuovendo il collegamento del ponticello o “parcheggiando” il collegamento del ponticello su un pin.

![](<.gitbook/assets/2 (34).png>)

\-Ruotare il ponticello su ON appoggiando il collegamento del ponticello su entrambi i pin.

1.  **Batteria ricaricabile (solo per WEPC-1B)**
2.  **DC Jack**

Per il collegamento dell'alimentazione switching CC 12V.

Per fornire un'alimentazione stabile e sufficiente per caricare le batterie ricaricabili per WEPC-1B, si consiglia vivamente di utilizzare un adattatore di alimentazione switching da 12 V/1 A.

1.  **Terminale BUS collegabile**
2.  **Terminale di uscita PGM del relè a contatto pulito**
3.  **Interruttore antimanomissione (per la copertura della custodia)**

Il modulo di espansione è protetto dall'interruttore antimanomissione contro qualsiasi apertura non autorizzata del case. Ogni volta che il coperchio della custodia viene aperto, l'interruttore antimanomissione verrà attivato.

1.  **Pulsante di ripristino (riservato per uso interno)**
2.  **Pulsante di prova**

Premere il pulsante test per inviare un segnale di test al pannello di controllo.

**Alimentazione elettrica**

-   Il modulo di espansione è alimentato dal pannello ibrido, che può fornire una fonte di alimentazione da 13,5 V al modulo di espansione. Inoltre, si consiglia di utilizzare l'adattatore di alimentazione esterno (12 V) quando è collegato a carichi che richiedono un assorbimento di energia maggiore.
-   Quando l'alimentazione dall'adattatore viene interrotta e ripristinata, il modulo di espansione trasmetterà rispettivamente un segnale di mancanza AC e un segnale di ripristino alla Centrale.

2

**Pacco batteria ricaricabile (solo per WEPC-1B)**

-   Per WEPC-1B, nel modulo di espansione è preinstallata una batteria ricaricabile Ni-MH che funge da backup in caso di interruzione di corrente.
-   Collegare manualmente il pacco batteria al PCB per utilizzarlo come fonte di alimentazione di riserva e/o per caricarlo automaticamente quando l'alimentazione viene collegata dall'adattatore o dal pannello ibrido. \\<Note>Prima di collegare il pacco batteria, assicurarsi che l'alimentazione del jack DC e/o del terminale BUS sia/siano spenti.

Si consiglia vivamente di utilizzare un adattatore di alimentazione switching da 12 V/1 A per fornire energia stabile e sufficiente per caricare le batterie.

-   Quando la batteria ricaricabile è scarica, il modulo di espansione trasmetterà un segnale di batteria scarica alla Centrale. Una volta caricate le batterie, trasmetterà anche un segnale di ripristino batterie alla Centrale.

**Protezione antisabotaggio**

La serie WEPC-1 dispone di due interruttori antimanomissione; ognuno ha una funzione diversa.

-   L'interruttore antimanomissione per il coperchio della custodia si trova nella parte anteriore della scheda. È in posizione normale quando la custodia è chiusa. La violazione della manomissione avviene quando viene aperta la custodia in cui viene rilasciato l'interruttore antimanomissione (Tamper Open).
-   L'interruttore antimanomissione per il montaggio a parete è situato sul retro della scheda. È in posizione normale quando il modulo è ben montato a parete. La violazione della manomissione avviene quando il modulo viene rimosso con la forza dalla posizione di montaggio, l'area si stacca e consente l'attivazione dell'interruttore antimanomissione.
-   Il tamper viene considerato attivato se uno qualsiasi dei tamper viene aperto. Il tamper è considerato ripristinato solo quando entrambi i tamper sono nello stato chiuso.

**Segnale di vigilanza**

-   Dopo essere stato appreso dal Pannello di Controllo, il Modulo di Espansione trasmetterà automaticamente i Segnali di Supervisione ogni 20-30 secondi.

**Collegamento al Pannello Ibrido**

-   Prima del collegamento, assicurarsi che l'alimentazione sia stata scollegata e che l'interruttore della batteria del pannello sia stato spostato in posizione OFF.
-   Per agevolare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema sono codificate a colori.

| **Rosso**  | VDD   |
| ---------- | ----- |
| **Nero**   | TERRA |
| **Giallo** | 485A  |
| **Verde**  | 485B  |

-   Per una comunicazione ottimale della connessione cablata tra la centrale e i dispositivi BUS collegati, assicurarsi che il ponticello di comunicazione del dispositivo BUS più lontano e il ponticello J53 della centrale di controllo siano impostati su ON per fungere da resistenza di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.
-   La serie WEPC-1 può essere collegata e alimentata dalla centrale tramite il terminale BUS o dall'alimentazione esterna tramite l'adattatore da 12 V. Se il modulo di espansione utilizza l'alimentazione esterna, assicurarsi di bypassare il terminale VDD rosso sul pannello di controllo utilizzando il connettore di giunzione Wago 221.
-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

3

-   Il diagramma seguente mostra come WEPC-1 è collegato e alimentato dal pannello ibrido.

![](<.gitbook/assets/3 (11).jpeg>)

-   Quello che segue è il collegamento di WEPC-1B al pannello ibrido, con WEPC-1B alimentato dalla fonte di alimentazione esterna.

![](<.gitbook/assets/4 (11).jpeg>)

4

_\\<NOTE>_

-   _Assicurarsi di bypassare il terminale VDD rosso sul pannello di controllo utilizzando il connettore di giunzione Wago 221 fornito. Collegare il terminale VDD al dispositivo BUS successivo (VST-892-BUS come esempio) alimentato dal pannello ibrido._
-   _Il design collegabile del terminale BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dal dispositivo per facilità d'uso e ricollegarle dopo il cablaggio. Quando si reinstallano le morsettiere sulla scheda, assicurarsi di installarle nella stessa direzione per evitare potenziali pericoli._

**Iniziare**

Dopo aver collegato la scheda di espansione al pannello ibrido e completato il cablaggio del dispositivo, procedere all'apprendimento e alla programmazione del sensore dell'interruttore di alimentazione.

-   _**Apprendimento**_

**Passo 1.**Collegare il modulo di espansione al pannello di controllo. Quindi, accendere il pannello di controllo**.**

**Passo 2.**Clicca su "**Apprendimento**" per accedere alla pagina di apprendimento.

**Passaggio 3.**Clicca su "**Inizio**" per accedere alla modalità di apprendimento.

**Passaggio 4.**Clic**"Aggiungere"**per includere il modulo di espansione nel pannello.

**Passaggio 5.**Se il modulo di espansione viene appreso con successo nel sistema, il dispositivo aggiunto verrà visualizzato nella sezione "Dispositivo acquisito". Il tipo di dispositivo verrà visualizzato come "Expander".

-   _**Programmazione del sensore dell'interruttore di alimentazione**_

Dopo aver aggiunto il modulo di espansione delle uscite programmabili, procedere alla programmazione del sensore dell'interruttore di alimentazione.

**Passo 1.**Fare clic su Sensore cablato per accedere a questa pagina Web. Vedrai gli espansori nella parte inferiore della pagina.

**Passo 2.**Fai clic su "Modifica" alla fine della voce dell'espansore.

**Passaggio 3.**Selezionare e assegnare l'interruttore di uscita per ciascuna zona.

-   **Tipo**: selezionare per attivare l'interruttore di alimentazione per ciascuna zona dal menu a discesa Tipo. L'impostazione predefinita è "Disabilitato" ed è possibile scegliere di assegnare l'interruttore di alimentazione dell'uscita relè con contatto pulito a una zona selezionando "Interruttore di alimentazione".

**Passaggio 4.**Fare clic su "**OK**" per salvare le modifiche al termine. In alternativa, fare clic su "**Rese**t” per reinserire tutte le informazioni.

**Passaggio 5.**Se il processo ha esito positivo, sullo schermo verrà visualizzato "**Aggiornato con successo.**” L'interruttore di alimentazione verrà assegnato ad un'area e una zona specifica.

**Passaggio 6.**Fai clic su "Controllo PSS" in Gestione dispositivo e entrerai**Sensore dell'interruttore di alimentazione**pagina web.

**Passaggio 7.**In questa pagina è possibile accendere o spegnere l'interruttore di alimentazione di ciascuna zona.

**Passaggio 8.**Puoi anche modificare le impostazioni e le informazioni del tuo dispositivo. Fare clic su "**Modificare**" alla fine dell'immissione del dispositivo e fare clic su "OK" per salvare le modifiche al termine.

-   _**Identificazione**_

La funzione “Identifica” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il Modulo di Espansione Uscite Programmabili nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo dell'espansore.

![](<.gitbook/assets/5 (21).png>)

5

**Passo 2.**Se il modulo di espansione di uscita programmabile riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED di alimentazione del WEPC-1(B) lampeggerà per 10 volte per indicare all'utente dove si trova.

_\\<NOTE>_

-   -   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il modulo di espansione uscite programmabili non ha ricevuto il segnale dalla centrale.

Verificare se WEPC-1(B) è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Prova della camminata**_
-   Per assicurarsi che il modulo di espansione delle uscite programmabili sia in grado di comunicare con

Centrale dopo l'apprendimento, posizionare la Centrale in modalità Walk Test e premere il pulsante Test su WEPC-1(B) per trasmettere un segnale di test alla Centrale.

-   Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà di conseguenza le informazioni di WEPC-1(B) in cima all'elenco dei dispositivi.

_\\<NOTE>_

-   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se WEPC-1(B) è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Cablaggio PGM**

-   La porta PGM può fungere da uscita relè a contatto pulito.
-   Per impostazione predefinita, N.C e COM sono impostati come cortocircuitati.
-   È possibile impostare il N.O. e COM come cortocircuito accendendo l'interruttore di alimentazione tramite la pagina web di programmazione.

**Impostazione predefinita****Impostazione tramite pagina di programmazione**

![](<.gitbook/assets/6 (11).jpeg>)![](<.gitbook/assets/7 (10).jpeg>)

**Come montare il modulo di espansione delle uscite programmabili**

![](<.gitbook/assets/8 (8).jpeg>)

Il modulo di espansione delle uscite programmabili può essere montato a parete procedendo come segue:

-   Allentare la vite di fissaggio inferiore e rimuovere il coperchio anteriore,
-   Utilizzando i fori della scheda di espansione uscite programmabili come dima, segnare i fori da praticare sulla parete.
-   Praticare dei fori nella posizione contrassegnata sul muro. Se necessario, inserire i tasselli.
-   Avvitare la base sulla posizione di montaggio.
-   Riposizionare il coperchio anteriore e serrare le viti di fissaggio inferiori.

6
