# VESTA 358

**Sensore di movimento PIR cablato (IR-35-BUS)**

**introduzione**

Il PIR rileva la firma a infrarossi per rilevare i movimenti all'interno di un'area assegnata e segnala alla centrale di controllo tramite BUS di attivare l'allarme se un intruso attraversa il suo percorso di rilevamento.

Il PIR è progettato per fornire un raggio di rilevamento tipico di 12 metri se montato a 2,5 metri dal suolo. Il sensore PIR supporta anche la funzione di immunità agli animali domestici e non rileva animali domestici fino a 25 kg per ridurre al minimo la situazione di falsi allarmi.

Il PIR è costituito da un design in due parti composto da una copertura e una base. Il coperchio contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio.

**Identificazione delle parti**

![](<.gitbook/assets/0 (1) (1).jpeg>)

1.  **Test Button / LED Indicator**
    -   Premere una volta il pulsante test per accedere alla modalità test per 3 minuti.
    -   L'indicatore LED viene utilizzato per indicare lo stato del sistema.
2.  **Sensore IR**
3.  **Interruttore a ponticello della resistenza terminale**

Quando il sensore di movimento PIR è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del sensore di movimento PIR e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

-   -   -   Se il ponticello è disattivato (il collegamento del ponticello è rimosso o “parcheggiato” su un pin), la capacità di comunicazione è a livello normale.
            -   Se il ponticello è su ON, la capacità di comunicazione verrà migliorata.

1.  **Capolinea autobus**
2.  **Interruttore ponticello di attivazione/disattivazione dell'immunità agli animali domestici (JP3)**
    -   Se impostato su ON, l'immunità agli animali domestici è disabilitata (impostazione di fabbrica).
    -   Se impostato su OFF, l'immunità agli animali domestici è abilitata.

![](<.gitbook/assets/1 (2).png>)

**Ponticello acceso**

![](<.gitbook/assets/2 (2).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

![](<.gitbook/assets/3 (1).jpeg>)

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

**6. Interruttore a ponticello per l'aumento della sensibilità (JP4)**

-   -   Quando impostato su ON, la sensibilità di rilevamento del PIR è alta.
    -   Quando impostato su OFF, la sensibilità di rilevamento del PIR è a livello normale. (Impostazione di fabbrica)

1.  **Interruttore antimanomissione**
2.  **Vite di fissaggio inferiore**

1

**Caratteristiche**

![](<.gitbook/assets/4 (2).jpeg>)

-   _**Indicatore LED**_

Nella modalità di funzionamento normale, l'indicatore LED lampeggerà 3 volte nelle seguenti situazioni:

-   Quando il coperchio viene aperto e l'interruttore antimanomissione viene attivato.
-   Quando viene rilevato un movimento se la condizione di Tamper persiste.
-   Quando viene rilevato un movimento in modalità Test
-   Quando il pulsante Test viene premuto in condizione di manomissione

Il LED non lampeggerà se la manomissione PIR è normale e il PIR non è in modalità test.

![](<.gitbook/assets/5 (1).jpeg>)

-   _**Protezione antisabotaggio**_

Il PIR è protetto da un interruttore antimanomissione che viene compresso quando il PIR è installato correttamente. Quando il PIR viene rimosso dalla superficie montata o dalla staffa di montaggio, o il suo coperchio viene aperto, l'interruttore antimanomissione verrà attivato e il PIR invierà un segnale di apertura antimanomissione al pannello di controllo del sistema per ricordare all'utente la condizione. Se viene rilevato un movimento quando l'interruttore antimanomissione è aperto, il LED lampeggerà 3 volte.

![](<.gitbook/assets/6 (2).jpeg>)

-   _**Funzione di supervisione**_

Dopo l'installazione, il PIR trasmetterà automaticamente periodicamente i segnali di supervisione alla centrale ad intervalli casuali di 20-30 secondi.

![](<.gitbook/assets/7 (3).png>)

-   _**Modalità di prova**_

Il PIR può essere messo in modalità Test premendo il pulsante Test. Ogni volta che si preme il pulsante Test, il PIR trasmetterà un segnale di test al pannello di controllo per il test della portata radio ed entrerà in modalità test per 3 minuti. La modalità test scade dopo 3 minuti.

![](<.gitbook/assets/8 (4).png>)

-   _**Funzione di immunità agli animali domestici**_
    -   Il sensore PIR supporta la funzione di immunità agli animali domestici e non rileva animali domestici fino a 25 kg per ridurre al minimo la situazione di falsi allarmi.
    -   La funzione Pet Immunity può essere abilitata/disabilitata impostando la posizione dell'interruttore Jumper (JP3). Quando l'interruttore jumper (JP3) è impostato su ON, l'immunità agli animali domestici è disabilitata (impostazione di fabbrica). Quando l'interruttore jumper (JP3) è impostato su OFF, l'immunità agli animali domestici è abilitata.
    -   La funzione Pet Immunity può essere regolata anche tramite impostazione remota, fare riferimento al_**Impostazione remota**_ section below.
-   _**Funzione di aumento della sensibilità**_
    -   È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento del PIR.
    -   Per aumentare la sensibilità di rilevamento, impostare l'interruttore jumper (JP4) su ON. Per mantenere la sensibilità di rilevamento normale, impostare l'interruttore jumper (JP4) su OFF (impostazione di fabbrica).
    -   La funzione Sensibilità può essere regolata anche tramite impostazione remota, fare riferimento a_**Impostazione remota**_sezione seguente.
-   _**Impostazione remota**_
    -   Il sensore di movimento PIR supporta l'impostazione remota dell'immunità e della sensibilità degli animali domestici.
    -   Quando il PIR è acceso, la sua funzione di immunità agli animali domestici e la sensibilità sono determinate dalle impostazioni JP3 e JP4. Gli utenti possono regolare le impostazioni dei ponticelli o modificare in remoto le impostazioni di immunità e sensibilità degli animali domestici dal pannello di controllo. L'impostazione remota sovrascriverà le impostazioni del ponticello.

**Pagina Web del Pannello di controllo**:

-   -   1.  Nella pagina web locale del Pannello, vai alla pagina Modifica dispositivo.
        2.  Immettere la configurazione del sensore di movimento PIR nella sezione Impostazione sensore. Fare clic su OK per confermare.
        3.  Fare riferimento alla tabella seguente per i dettagli di configurazione. Ad esempio, se desideri abilitare l'immunità agli animali domestici e impostare il livello di sensibilità su alto, puoi inserire 03.

![](<.gitbook/assets/9 (4).png>)![](<.gitbook/assets/10 (4).png>)

| **Configurazione IR** | **Immunità agli animali domestici** | **Sensibilità** |
| --------------------- | ----------------------------------- | --------------- |
| 00                    | Disable                             | Normale         |
| 01                    | disattivare                         | Alto            |
| 02                    | Abilitare                           | Normale         |
| 03                    | Abilitare                           | Alto            |

**Server del portale domestico**:

-   -   -   1.  Su Home Portal Server, vai alla pagina Impostazioni dispositivo, fai clic sulla riga del dispositivo IR-35 e seleziona "Configurazione IR".
            2.  Selezionare la funzione Pet Immunity (Abilita/Disabilita) e Sensibilità (Alta/Normale) dagli elenchi a discesa, fare clic su "Invia" per confermare l'impostazione.
-   _**Alimentazione elettrica**_
    -   -   Quando l'IR-35-BUS è cablato a una centrale ibrida, la centrale ibrida può fornire un'alimentazione da 13,5 V.
-   _**Attenzione**_
    -   Il cablaggio del sensore di movimento PIR deve essere eseguito solo da un tecnico certificato con adeguata conoscenza e formazione in apparecchiature elettriche.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.

![](<.gitbook/assets/11 (1).jpeg>)![](.gitbook/assets/12.jpeg)![](<.gitbook/assets/13 (4).png>)

2

-   ![](<.gitbook/assets/14 (3).png>)_**Cablaggio del sensore di movimento PIR**_
    -   Prima di collegare il sensore di movimento PIR al bus di sistema, spegnere l'alimentazione.
    -   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/15 (1).jpeg>)

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale tra i dispositivi della linea BUS collegati, assicurarsi che gli interruttori a ponticello della resistenza terminale del primo (normalmente il pannello ibrido) e dei dispositivi BUS più lontani su una linea BUS siano impostati su ON per fungere da resistenze di terminazione. Assicurati di abilitare solo i 2 jumper sopra menzionati e

non impostare i ponticelli su ON per nessun altro dispositivo BUS intermedio.

_\\<NOTE>_

-   -   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
    -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/16 (4).png>)

-   _**Per iniziare: apprendere il sensore di movimento PIR nel pannello di controllo**_

Seguire i passaggi seguenti per apprendere il dispositivo al pannello ibrido.

Passaggio 1. Collegare il dispositivo al pannello. Quindi, accendere il pannello.

Passaggio 2. Nella pagina Web del Pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3. Fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

Passaggio 4. Fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

Passaggio 5. Se il dispositivo viene acquisito con successo nel Pannello, verrà visualizzato nella sezione "Dispositivo acquisito".

![](<.gitbook/assets/17 (1).jpeg>)

-   _**Identificazione**_

IL "**Identificare**La funzione ” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il sensore di movimento PIR nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo della telecamera IR.

**Passo 2.**Se il sensore di movimento PIR riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED del sensore di movimento PIR lampeggerà 10 volte per indicare all'utente dove si trova.

![](<.gitbook/assets/18 (4).png>)

_\\<NOTE>_

-   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il sensore di movimento PIR non ha ricevuto il segnale dal pannello.

Verificare se la connessione cablata tra il pannello e il sensore di movimento PIR è collegata correttamente.

3

-   ![](.gitbook/assets/19.jpeg)_**Prova della camminata**_
    -   Per assicurarsi che il sensore di movimento PIR sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale in modalità Walk Test e premere il pulsante Test sull'IR-35-BUS per trasmettere un segnale di test alla centrale.
    -   Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà di conseguenza le informazioni del sensore di movimento PIR nella parte superiore dell'elenco dei dispositivi.

![](<.gitbook/assets/20 (3).png>)

_\\<NOTE>_

-   -   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se l'IR-35-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Ripristino delle impostazioni di fabbrica**_

Il sensore di movimento PIR può essere ripristinato in fabbrica sull'immunità agli animali domestici e sulla sensibilità predefinite in base alle impostazioni JP3 e JP4. Seguire i passaggi seguenti per procedere.

Passaggio 1. Scollegare l'alimentazione dal sensore di movimento PIR.

Passaggio 2. Premere e tenere premuto il pulsante Test del sensore di movimento PIR, quindi accendere il dispositivo. Continuare a tenere premuto il pulsante Test per 5 secondi. Rilasciare il pulsante Test dopo che il LED ha lampeggiato 5 volte. Il ripristino delle impostazioni di fabbrica è completo.

**Installazione**

-   _**Linee guida per l'installazione**_
    -   Il PIR è progettato per essere montato su una superficie piana o in un angolo.
    -   Il raggio di rilevamento arriva fino a 12 metri se il PIR è montato 2,3-2,5 metri sopra
    -   Quando la funzione Pet-Immunity è abilitata, il PIR non rileverà animali domestici fino a 25 kg se montato a 2,3-2,5 metri dal suolo. Se necessario, è possibile regolare l'altezza del PIR in base alla taglia del proprio animale domestico per prestazioni ottimali di immunità agli animali domestici. Una posizione di installazione più alta fornirà uno spazio più ampio immune agli animali domestici, ma aumenterà l'angolo cieco sotto il PIR.
    -   Quando il PIR è montato con la staffa rotante, non avrà la normale area di rilevamento (come nel diagramma seguente) o il tipico raggio di immunità agli animali domestici.
    -   Dopo aver selezionato il sito di installazione, premere il pulsante Test per accedere alla modalità Test. Camminare attorno all'area protetta osservando quando il LED si accende e verificare che la copertura di rilevazione sia adeguata.
    -   Quando la copertura del rilevamento risulta soddisfacente, seguire i passaggi descritti in_**Metodo di montaggio**_sezione seguente per montare il PIR.

**Campo di rilevamento IR-35-BUS**

4

-   _**Metodo di montaggio**_
    -   Il PIR è progettato per essere montato su una superficie piana o in un angolo.
    -   La base ha due fori, dove la plastica è più sottile e può essere rotta per il montaggio su superficie.
    -   Una staffa di montaggio include due fori per viti centrali per fissare il PIR su una superficie e quattro fori per viti laterali per fissare il PIR su un angolo.
    -   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Grazie alla staffa rotante, l'IR-35-BUS può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
-   **Montaggio su superficie senza staffa di montaggio:**
    1.  Rimuovere la vite di fissaggio inferiore e il gruppo del coperchio.
    2.  Attraversa i due fori dall'interno della base
    3.  Utilizzare i fori come modello e praticare i fori sulla superficie da montare.
    4.  Inserire i tasselli se il PIR deve essere fissato su intonaco o mattoni.
    5.  Screw the base onto the wall plugs.
    6.  Avvitare il coperchio sulla base.
-   **Montaggio su superficie con la staffa di montaggio:**
    1.  Utilizzare i due fori centrali per le viti sulla staffa come modello e praticare i fori nella superficie da montare.
    2.  Inserire i tasselli se il PIR deve essere fissato su intonaco o mattoni.
    3.  Avvita la staffa di montaggio sui tasselli con i due bastoncini di puntamento in alto e rivolti verso di te.
    4.  Montare il PIR sui ganci della staffa di montaggio.

5

-   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Grazie alla staffa rotante, l'IR-35-BUS può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
-   La staffa rotante può essere montata a parete con le viti fornite.
    1.  Avvitare la staffa rotante al muro.
    2.  Montare opportunamente i 3 ganci della staffa rotante nei 3 fori della base.
    3.  Ruotare la staffa per il campo di rilevamento corretto e serrare la vite di fissaggio.

**Raccomandazioni per l'installazione**

-   **Si consiglia di installare il PIR nelle seguenti posizioni:**
    -   Ad un'altezza di 2,3 M-2,5 M per le migliori prestazioni:
    -   Nei luoghi in cui gli animali non possono raggiungere l'area di rilevamento arrampicandosi su mobili o altri oggetti.
    -   Non puntare il sensore verso scale sulle quali gli animali potrebbero arrampicarsi.
    -   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR da un lato all'altro.
    -   In un angolo per avere la visuale più ampia.
    -   In una posizione in cui il campo visivo non sia ostruito, ad esempio, da tende, ornamenti, ecc.
-   **Limitazioni**

|  | Non installare all'aperto.                         |  | Evitare ostacoli di grandi dimensioni nell'area di rilevamento. |
| - | -------------------------------------------------- | - | --------------------------------------------------------------- |
|   |                                                    |   |                                                                 |
|  | Non esporre completamente il PIR alla luce diretta |  | Evitare vapori o umidità elevata che potrebbero causare         |
|   | luce del sole.                                     |   | condensazione.                                                  |
|   |                                                    |   |                                                                 |
|   |                                                    | 6 |                                                                 |

|  | Evitare oggetti in movimento, ad esempio tende, pareti  |  | Evitare la luce riflessa da superfici luminose, ad es.  |
| - | ------------------------------------------------------- | - | ------------------------------------------------------- |
|   | tendaggi, ecc. nell'area di rilevamento.                |   | specchi, finestre, ecc.                                 |
|   |                                                         |   |                                                         |
|  | Evitare di installare il PIR in aree in cui             |  | Evitare superfici riflettenti nell'area di rilevamento. |
|   | macchine come condizionatori o riscaldatori             |   | Le firme infrarosse riflesse possono portare a falsità  |
|   | può causare un rapido cambiamento della temperatura nel |   | allarme.                                                |
|   | zona di rilevamento.                                    |   |                                                         |
|   |                                                         |   |                                                         |

7
