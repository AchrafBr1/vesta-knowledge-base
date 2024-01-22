# VESTA224

**Modulo di espansione serie WEZC-8**

**introduzione**

Questa guida all'installazione deve essere utilizzata insieme al manuale utente del pannello ibrido a cui è collegato il modello della serie WEZC-8.

Il modulo di espansione della serie WEZC-8 è progettato per supportare l'espansione della centrale ibrida. Collegato alla Centrale Ibrida tramite connessione BUS, può consentire l'espansione fino a 8 zone sulle centrali compatibili. La serie WEZC-8 è dotata di una propria custodia, dotata di protezione antimanomissione e indicatori di stato LED.

**Il modulo di espansione serie WEZC-8 include i seguenti modelli:**

**WEZC-8**– Modulo di espansione con 8 zone cablate

**WEZC-8B**– Modulo di espansione con 8 zone cablate e pacco batterie ricaricabili

**Identificazione delle parti**

**Vista frontale****Vista posteriore**

![](<.gitbook/assets/0 (6).jpeg>)

**Vista interna**

![](<.gitbook/assets/1 (8).jpeg>)

1

1.  **LED di alimentazione (rosso)**

Acceso: alimentato da un adattatore di alimentazione da 12 V o da un pannello ibrido.

Spento – Quando l'alimentazione è spenta o quando è alimentata da una batteria ricaricabile.

1.  **Zona 1~8 LED (rosso)**

Il LED della zona corrispondente si accenderà quando determinate zone vengono attivate o presentano condizioni di manomissione o mascheramento.

1.  **LED di trasmissione (rosso)**

Si accende quando la connessione o la trasmissione del segnale tra il modulo di espansione e il pannello di controllo è normale.

1.  **Zona separatista**

Quando il modulo di espansione viene rimosso con la forza dalla posizione di montaggio, l'area verrà staccata, provocando l'attivazione dell'interruttore antimanomissione.

1.  **Interruttore antimanomissione (per montaggio a parete)**

Il modulo di espansione è protetto dall'interruttore antimanomissione contro qualsiasi rimozione non autorizzata dalla posizione di montaggio.

1.  **Fori di montaggio**
2.  **Foro di cablaggio**
3.  **Terminale di collegamento della batteria (solo per WEZC-8B)**

Per collegare la batteria ricaricabile al PCB.

1.  **Pacco batteria ricaricabile (solo per WEZC-8B)**
2.  **Interruttore ponticello resistenza terminale (J3)**

Quando il modulo di espansione è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del modulo di espansione e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/2 (9).jpeg>)

Portare il ponticello su OFF rimuovendo il collegamento del ponticello o “parcheggiando” il collegamento del ponticello su un pin.

![](<.gitbook/assets/3 (8).jpeg>)

Ruotare il ponticello su ON appoggiando il collegamento del ponticello su entrambi i pin.

**11. Presa CC**

Per il collegamento dell'alimentazione switching CC 12V.

Per fornire un'energia stabile e sufficiente per caricare le batterie ricaricabili per WEZC-8B, si consiglia vivamente di utilizzare un alimentatore switching da 12 V/1 A.

1.  **Terminale BUS collegabile**
2.  **Terminale di zona e terminale di uscita tensione ausiliaria da 13,5 V e terminale GND**

La tensione tipica è 13,5 V e potrebbe variare a seconda della tensione di uscita del terminale.

**14. Pulsante di prova**

Premere il pulsante test per inviare un segnale di test al pannello di controllo.

1.  **Pulsante di ripristino (riservato per uso interno)**
2.  **Interruttore antimanomissione (per la copertura della custodia)**

Il modulo di espansione è protetto dall'interruttore antimanomissione contro qualsiasi apertura non autorizzata del case. Ogni volta che il coperchio della custodia viene aperto, l'interruttore antimanomissione verrà attivato.

**Alimentazione elettrica**

-   Il modulo di espansione è alimentato dal pannello ibrido, che può fornire una fonte di alimentazione da 13,5 V al modulo di espansione. Inoltre, si consiglia di utilizzare l'adattatore di alimentazione esterno (12 V) quando è collegato a carichi che richiedono un assorbimento di energia maggiore.
-   Quando l'alimentazione dall'adattatore viene interrotta e ripristinata, il modulo di espansione trasmetterà rispettivamente un segnale di mancanza AC e un segnale di ripristino alla Centrale.

2

**Pacco batteria ricaricabile (solo per WEZC-8B)**

-   Per WEZC-8B, una batteria ricaricabile Ni-MH è preinstallata nel modulo di espansione per fungere da backup in caso di interruzione di corrente.
-   Collegare manualmente il pacco batteria al PCB per utilizzarlo come fonte di alimentazione di riserva e/o per caricarlo automaticamente quando l'alimentazione viene collegata dall'adattatore o dal pannello ibrido. \\<Note>Prima di collegare il pacco batteria, assicurarsi che l'alimentazione del jack DC e/o del terminale BUS sia/siano spenti.

Si consiglia vivamente di utilizzare un adattatore di alimentazione switching da 12 V/1 A per fornire energia stabile e sufficiente per caricare le batterie.

-   Quando la batteria ricaricabile è scarica, il modulo di espansione trasmetterà un segnale di batteria scarica alla Centrale. Una volta caricate le batterie, trasmetterà anche un segnale di ripristino batterie alla Centrale.

**Protezione antisabotaggio**

La serie WEZC-8 ha due interruttori antimanomissione; ognuno ha una funzione diversa.

-   L'interruttore antimanomissione per il coperchio della custodia si trova nella parte anteriore della scheda. È in posizione normale quando la custodia è chiusa. La violazione della manomissione avviene quando viene aperta la custodia in cui viene rilasciato l'interruttore antimanomissione (Tamper Open).
-   L'interruttore antimanomissione per il montaggio a parete è situato sul retro della scheda. È in posizione normale quando il modulo è ben montato a parete. La violazione della manomissione avviene quando il modulo viene rimosso con la forza dalla posizione di montaggio; l'area di fuga verrà staccata, provocando l'attivazione dell'interruttore antimanomissione.
-   Il tamper viene considerato attivato se uno qualsiasi dei tamper viene aperto. Il Tamper è considerato ripristinato solo quando entrambi i tamper sono nello stato chiuso.

**Segnale di vigilanza**

-   Dopo essere stato appreso dal Pannello di Controllo, il Modulo di Espansione trasmetterà automaticamente i Segnali di Supervisione ogni 20-30 secondi.

**Collegamento al Pannello Ibrido**

-   Prima del collegamento, assicurarsi che l'alimentazione sia stata scollegata e che l'interruttore della batteria del pannello sia stato spostato in posizione OFF.
-   Per agevolare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema sono codificate a colori.

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   Per una comunicazione ottimale dei dispositivi BUS collegati, assicurarsi del dispositivo BUS più lontano

L'interruttore a ponticello della resistenza terminale e l'interruttore a ponticello J53 del pannello di controllo sono impostati su ON per fungere da resistori di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

-   La serie WEZC-8 può essere collegata e alimentata dal pannello di controllo tramite il terminale BUS o dall'alimentazione esterna tramite l'adattatore da 12 V. Se il modulo di espansione utilizza l'alimentazione esterna, assicurarsi di bypassare il terminale VDD rosso sul pannello di controllo utilizzando il connettore di giunzione Wago 221.

3

-   Quello che segue è WEZC-8 collegato e alimentato dal pannello ibrido:

![](<.gitbook/assets/4 (8).jpeg>)

-   Quello che segue è il collegamento di WEZC-8B al pannello ibrido, con WEZC-8B alimentato da una fonte di alimentazione esterna.

![](<.gitbook/assets/5 (6).jpeg>)

4

_Nota:_

-   _Assicurarsi di bypassare il terminale VDD rosso sul pannello di controllo utilizzando il connettore di giunzione Wago 221 fornito. Collegare il terminale VDD al dispositivo BUS successivo (VST-892-BUS come esempio) alimentato dal pannello ibrido._
-   _Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dal dispositivo per facilità d'uso e ricollegarle dopo il cablaggio. Quando si reinstallano le morsettiere sulla scheda, assicurarsi di installarle nella stessa direzione per evitare potenziali pericoli._
-   _Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione._

**Cablaggio di zona**

-   Le 8 zone possono essere cablate per supervisionare dispositivi NC (normalmente chiusi) o NA (normalmente aperti), ad esempio sensori PIR, contatti porta, rilevatori di fumo, sensori di acqua, sensori di incendio, sensori di CO, rilevatori di gas, rilevatori di calore e rottura vetri rilevatori, ecc.
-   Collega i dispositivi cablati a qualsiasi terminale di zona.
-   Calibro del filo: minimo 22 AWG, massimo 19 AWG. Non utilizzare cavi schermati.
-   Le zone cablate supportano la configurazione del loop Single-End-of-Line (SEOL), Double-End-of-Line (DEOL), con valori di resistenza selezionabili di 1 KΩ, 2,2 KΩ, 3,74 KΩ, 4,7 KΩ, 5,6 KΩ, 6,8 K Ω , 8,2 KΩ, 10 KΩ ohm.
-   Il triplo loop di fine linea (TEOL) può essere configurato in diverse combinazioni: 4,7 KΩ, 6,8 KΩ,

12KΩ (selezione valore resistore: 6,8K), 4,7KΩ/5,6KΩ, 4,7KΩ, 2,2KΩ/3KΩ (valore resistore

selezione: 4,7 K) o 4,7 KΩ/5,6 KΩ, 5,6 KΩ, 2,2 KΩ/3 KΩ (selezione valore resistenza: 5,6 K).

-   Installare i resistori all'estremità di ciascun circuito di zona lontano dalla centrale. Il pannello rileverà se il circuito è sicuro, aperto o in corto.
-   Per un circuito NC, disporre di un resistore EOL in serie con il circuito.
-   For an NO loop, please have an EOL resister in parallel (across) the loop. Please refer to the following diagrams for wiring examples.
-   Se viene modificato il metodo di cablaggio di una zona, assicurarsi di spegnere e riaccendere il sistema per evitare di attivare l'allarme.

Fare riferimento ai seguenti schemi dei loop da 1 a 10 per esempi di cablaggio.

**Cablaggio NA/NC**

La centrale è in grado di rilevare l'allarme per i corrispondenti dispositivi NA o NC tramite circuiti aperti, sicuri o in corto.

_\\<NOTE>_

 Non è presente alcuna resistenza EOL nel loop 1 e nel loop 2

**Cablaggio NA/NC**

1.2.

![](<.gitbook/assets/6 (6).jpeg>)![](<.gitbook/assets/7 (6).jpeg>)

5

**Cablaggio del resistore di fine linea singolo**

3.4.

![](<.gitbook/assets/8 (7).png>)

5.6.

![](<.gitbook/assets/9 (10).png>)

**Cablaggio del resistore di fine linea doppio**

7.8.

![](<.gitbook/assets/10 (11).png>)

**Cablaggio triplo EOL**

9.10.

![](<.gitbook/assets/11 (6).png>)

6

**Iniziare**

Dopo aver collegato la scheda di espansione alla centrale ibrida e completato il cablaggio del dispositivo, procedere all'apprendimento e alla programmazione delle zone.

-   _**Apprendimento**_

**Passo 1.**Collegare il modulo di espansione al pannello di controllo. Quindi, accendere il pannello di controllo**.**

**Passo 2.**Clicca su -**Apprendimento**‖ per accedere alla pagina di apprendimento.

**Passaggio 3.**Clicca su -**Inizio**‖ per accedere alla modalità di apprendimento.

**Passaggio 4.**Clic**"Aggiungere"**per includere il modulo di espansione nel pannello.

**Passaggio 5.**Se il modulo di espansione viene acquisito con successo nel sistema, il dispositivo aggiunto verrà visualizzato nella sezione "Dispositivo acquisito". Il tipo di dispositivo verrà visualizzato come "Espansore".

-   _**Programmazione zone cablate**_

Dopo aver aggiunto il modulo di espansione, procedere alla programmazione delle zone cablate.

**Passo 1.**Fare clic su Sensore cablato per accedere a questa pagina Web. Vedrai gli espansori in fondo alla pagina.

**Passo 2.**Fare clic su "Modifica" alla fine della voce dell'espansore.

**Passaggio 3.**Modificare il tipo di sensore cablato, cablaggio di zona e resistenza EOL per ciascuna zona.

-   **Tipo**: selezionare dal menu a tendina la tipologia del sensore filare per ciascuna zona.
-   **Ciclo continuo**: selezionare il numero corrispondente al cablaggio di zona per ciascuna zona dal menu a discesa. In questa pagina Web sono riportati gli schemi elettrici di seguito come riferimento.
-   **Resistore**: Selezionare la resistenza per il cablaggio della zona.
-   **Stato**: Lo stato di ciascuna zona (Ripristino, Manomissione o Attivazione) verrà visualizzato qui.

**Passaggio 4.**Fare clic su ―**OK**‖ per salvare le modifiche al termine. In alternativa, fare clic su ―**Rese**t‖ per reinserire tutte le informazioni.

**Passaggio 5.**Se il processo ha esito positivo, sullo schermo verrà visualizzato ―**Aggiornato con successo.**‖ Il sensore verrà assegnato ad un'area e una zona specifica. Per modificare le impostazioni o le informazioni del dispositivo, fare clic su ―**Modificare**‖ alla fine dell'immissione del dispositivo.

**Passaggio 6.**Entrerai**Modifica dispositivo**pagina web.

**Passaggio 7.**Modifica le impostazioni e le informazioni del tuo dispositivo. Fare clic su "OK" per salvare le modifiche al termine.

-   _**Identificazione**_

La funzione ―Identifica‖ permette di localizzare uno specifico dispositivo BUS nel sistema BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il Modulo di Espansione nel sistema BUS:

**Passo 1.**Nella pagina web della centrale ibrida, fare clic su "Identifica" sotto l'elenco dei dispositivi dopo la voce della colonna del dispositivo dell'espansore.

![](<.gitbook/assets/12 (9).png>)

**Passo 2.**Se il modulo di espansione riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED di alimentazione del modulo di espansione lampeggerà per 10 volte per indicare all'utente dove si trova.

_\\<NOTE>_

-   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il modulo di espansione non ha ricevuto il segnale dal pannello.

Verificare se il modulo di espansione è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

7

-   _**Prova della camminata**_
-   Per assicurarsi che il modulo di espansione sia in grado di comunicare con la centrale successivamente

appreso, posizionare il pannello di controllo in modalità Walk Test e premere il pulsante Test su WEZC-8 per trasmettere un segnale di test al pannello di controllo.

-   Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà le informazioni del modulo di espansione in cima all'elenco dei dispositivi.

_\\<NOTE>_

-   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se il modulo di espansione è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Come montare il modulo di espansione**

Il modulo di espansione può essere montato a parete. Seguire i passaggi seguenti per montarlo:

-   Allentare la vite di fissaggio inferiore e rimuovere il coperchio anteriore.
-   Utilizzando i fori del Modulo di Espansione come dima, segnare i fori da praticare sul muro.
-   Praticare dei fori nella posizione contrassegnata sul muro. Se necessario, inserire i tasselli.
-   Avvitare la base sulla posizione di montaggio.
-   Riposizionare il coperchio anteriore e serrare le viti di fissaggio inferiori.

![](<.gitbook/assets/13 (3).jpeg>)

8
