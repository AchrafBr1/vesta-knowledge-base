# VESTA 357

**Telecamera con sensore di movimento PIR da esterno cablata (VST-892EX-BUS)**

VST-892EX-BUS è una telecamera con sensore di movimento a infrarossi passivi (PIR) cablata per esterni. È in grado di inviare segnali filari e immagini catturate (qualità dell'immagine fino a 640 x 480 pixel) su BUS alla Centrale al rilevamento del movimento.

Dotato di funzionalità di illuminazione notturna, con alloggiamento resistente ai raggi UV e impermeabile secondo lo standard IPX6, VST-892EX-BUS è ideale per cortili, prati, cancelli, corridoi esterni e corridoi.

La telecamera PIR per esterni è progettata con un raggio di rilevamento tipico di 10 metri se montata ad un'altezza di 2,3 metri dal suolo. Fornisce immunità agli animali domestici fino a 60 chili con tre livelli di sensibilità selezionabili per adattarsi a diversi ambienti.

Inoltre, VST-892EX-BUS è progettato con il rilevatore di prossimità digitale. La funzione antimascheramento consente di rilevare eventuali tentativi di accecamento del rilevatore posizionando oggetti nel suo campo visivo.

La configurazione remota è supportata per la telecamera con sensore di movimento PIR. Oltre a regolare l'interruttore DIP, gli utenti possono anche abilitare/disabilitare la funzione doppio battito e l'immunità agli animali domestici, nonché regolare la sensibilità della telecamera PIR dalla pagina Web del pannello di controllo o dal server del portale domestico.

![](<.gitbook/assets/0 (2).png>)

-   _**Identificazione delle parti**_

![](<.gitbook/assets/1 (1) (1).jpeg>)

1.  **Rilevatore di prossimità digitale**

Il rilevatore di prossimità digitale viene utilizzato per rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.

1.  **Indicatore LED (rosso)**

L'indicatore LED viene utilizzato per indicare lo stato del sistema.

1.  **LED lampeggiante**

Il LED Flash fornisce luce sufficiente per l'acquisizione di immagini in condizioni di scarsa illuminazione.

1.  **Sensore IR**

Il sensore è destinato a rilevare oggetti in movimento.

-   1.  **Obiettivo della fotocamera PIR**

1.  **Tamper interno**
2.  **Pulsante Prova e impara**

\-Premere il pulsante una volta per accedere alla modalità test per 10 minuti.

1.  **Blocco interruttore DIP**

Sono presenti 8 DIP Switch per impostare la funzione e i livelli di sensibilità di rilevamento.

1.  **Interruttore a ponticello della resistenza terminale**

Quando la telecamera con sensore di movimento PIR è collegata come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale della telecamera con sensore di movimento PIR e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione . La capacità di comunicazione della linea BUS connessa verrà migliorata.

![](<.gitbook/assets/2 (1) (1).jpeg>)![](<.gitbook/assets/3 (3).png>)

**Ponticello acceso**

![](<.gitbook/assets/4 (1).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.
    -   Se il ponticello è su ON, la capacità di comunicazione verrà migliorata.

1.  **Capolinea autobus**

1

1.  **Foro per cablaggio BUS**
2.  **Staffa di fissaggio**
3.  **Ganci**
4.  **Fori di montaggio**

![](<.gitbook/assets/5 (3).png>)

-   _**Indicatore LED**_

Quando abilitato, l'indicatore LED si accenderà nelle seguenti condizioni:

-   Quando la telecamera PIR è in condizioni di guasto (tamper aperto o condizioni di mascheramento continuo), ogni volta che trasmette un movimento rilevato, il LED lampeggerà una volta.
-   Dopo aver premuto una volta il pulsante di test per accedere alla modalità test, il LED lampeggerà per 60 secondi per indicare che la fotocamera del sensore di movimento PIR si sta riscaldando.
-   In modalità Test, il LED lampeggerà una volta ogni volta che viene rilevato un movimento.

Il LED non lampeggerà se la telecamera PIR è normale e non è in modalità test.

![](<.gitbook/assets/6 (1) (1).png>)

_\\<NOTE>_

-   -   L'indicatore LED può essere abilitato impostando il DIP Switch 2 in posizione ON. Per favore riferisci a**Tabella delle posizioni dei DIP switch**di seguito per i dettagli.
-   _**Acquisizione di immagini**_

![](<.gitbook/assets/7 (2).png>)

Quando il sistema di allarme è armato, la telecamera PIR catturerà 1, 3 o 6 immagini di allarme con risoluzione di 640 x 480 o 320 x 240 (programmabili dal pannello di controllo) al rilevamento del movimento. Puoi anche richiedere manualmente alla telecamera PIR di scattare una foto tramite il pannello di controllo. Le immagini catturate verranno trasferite al Pannello di Controllo per la verifica visiva dell'allarme.

![](<.gitbook/assets/8 (3).png>)

_\\<NOTE>_

-   -   Se la tua telecamera PIR è installata in un luogo in cui il campo visivo della telecamera è un ambiente complesso con luce intensa o molti colori, le immagini catturate avranno dimensioni di file elevate, il che potrebbe comportare un troncamento quando le immagini vengono trasmesse al pannello di controllo .
-   _**Periodo di riscaldamento**_

![](<.gitbook/assets/9 (3).png>)

La telecamera PIR si riscalderà per 60 secondi quando viene accesa dal pannello di controllo quando si entra in modalità armata.

![](<.gitbook/assets/10 (3).png>)

-   _**Modalità di prova**_
    -   La telecamera PIR può essere messa in modalità test per 10 minuti premendo una volta il pulsante test.
    -   In modalità test, le funzioni di acquisizione delle immagini sono disabilitate. L'indicatore LED lampeggerà una volta ogni volta che viene rilevato un movimento.
    -   La telecamera PIR uscirà automaticamente dalla modalità test dopo 10 minuti e tornerà alla modalità normale.
    -   In modalità test, l'indicatore LED deve essere abilitato impostando il DIP Switch 2 in posizione ON e la funzione Double Knock deve essere disabilitata impostando il DIP Switch 7 in posizione OFF, affinché gli utenti possano testare il campo di rilevamento.
-   _**Funzione doppio colpo**_
    -   La telecamera PIR ha una funzione di doppia detonazione. Se è abilitata la funzione doppio battito, la telecamera PIR segnalerà un allarme alla centrale solo se vengono rilevati due movimenti entro 10 secondi. Se la funzione del doppio colpo è disabilitata, la telecamera PIR segnalerà un allarme al pannello di controllo quando viene rilevato un movimento.
-   _**Tabella delle posizioni dei DIP switch**_

![](<.gitbook/assets/11 (2).png>)![](<.gitbook/assets/12 (3).png>)

La funzione di ciascun DIP Switch è elencata nella tabella seguente. L'interruttore DIP è ON o OFF. La posizione superiore indica ON e la posizione inferiore indica OFF.

![](<.gitbook/assets/13 (3).png>)

Posizione DIP

Accendere

1 SPEGNIMENTO

Accendere

2 FUORI

Funzione

Modalità di prova

Modalità normale (predefinita)

Indicatore LED abilitato (predefinito)

Indicatore LED disabilitato

| IMMERSIONE | Livello di sensibilità |                                                 |        |   |
| ---------- | ---------------------- | ----------------------------------------------- | ------ | - |
| Cambia 5   | Interruttore 6         |                                                 |        |   |
| SU         | SU                     | Basso; Animale domestico da 60 kg               | SU     |   |
| SU         | SPENTO                 | Medio; Animale domestico da 35 kg (predefinito) |        |   |
| SPENTO     | SU                     | Alto; Animale domestico da 20 kg                | SPENTO |   |
|            |                        |                                                 |        |   |

![](<.gitbook/assets/14 (2).png>)

Interruttore

3

SU

SPENTO

SU

Telecamera PIR rivolta verso un muro entro 10 m

Telecamera PIR rivolta verso uno spazio aperto (nessun muro entro 10 m) (impostazione predefinita)

Telecamera PIR rivolta verso un prato

| SPENTO         | SPENTO        | Riservato                                 |   |
| -------------- | ------------- | ----------------------------------------- | - |
| IMMERSIONE     | Posizione     | Funzione                                  |   |
|                | SU            | Rilevamento doppio colpo                  |   |
| Cambia 7       | (predefinito) |                                           |   |
|                |               |                                           |   |
|                | SPENTO        | Rilevamento normale                       |   |
| Interruttore 8 | SU            | Immunità agli animali domestici abilitata |   |
|                |               |                                           |   |

Interruttore

4 FUORI

(predefinito)

Telecamera PIR rivolta verso a

terreno in cemento/pietra

OFF Immunità agli animali domestici disabilitata (impostazione predefinita)

_\\<NOTE>_

-   Dopo aver modificato le impostazioni del Dip Switch, riaccendere la telecamera PIR per applicare le nuove impostazioni del Dip Switch.

![](.gitbook/assets/15.jpeg)

2

-   ![](<.gitbook/assets/16 (3).png>)_**Impostazione remota**_
    -   La telecamera con sensore di movimento PIR supporta l'impostazione remota della funzione doppio battito, sensibilità e immunità agli animali domestici.
    -   Quando la telecamera PIR è accesa, la sua funzione di doppia detonazione è determinata dall'impostazione DIP SW7, la sensibilità è determinata da DIP SW5 e SW6 e l'immunità agli animali domestici è determinata da DIP SW8. Gli utenti possono regolare le impostazioni dell'interruttore DIP o modificare in remoto le impostazioni della funzione doppio battito, della sensibilità e dell'immunità agli animali domestici nella pagina Web del pannello di controllo o nel server Home Portal. L'impostazione remota sovrascriverà le impostazioni del DIP Switch.

**Pagina Web del Pannello di controllo**:

-   -   1.  Nella pagina web locale del pannello, andare alla pagina Modifica dispositivo e inserire la configurazione della telecamera PIR nella sezione Impostazione sensore. Fare clic su OK per confermare.

Fare riferimento alla tabella seguente per i dettagli di configurazione. Ad esempio, se si desidera disattivare la funzione di doppia percussione e impostare il livello di sensibilità su Basso, è possibile inserire 00.

| **Configurazione IR** | **Doppio colpo** | **Sensibilità**                              | **Immunità agli animali domestici** |
| --------------------- | ---------------- | -------------------------------------------- | ----------------------------------- |
| 00                    | NO               | Basso                                        | SÌ                                  |
| 20                    | NO               | medio                                        | SÌ                                  |
| 40                    | NO               | Alto                                         | SÌ                                  |
| 60                    | NO               | Immunità agli animali domestici disabilitata | NO                                  |
| 80                    | SÌ               | Basso                                        | SÌ                                  |
| A0                    | SÌ               | medio                                        | SÌ                                  |
| C0                    | SÌ               | Alto                                         | SÌ                                  |
| E0                    | SÌ               | Immunità agli animali domestici disabilitata | NO                                  |

**Server del portale domestico**:

-   -   -   1.  Su Home Portal Server, vai alla pagina Impostazioni dispositivo, fai clic sulla riga del dispositivo VST-892EX e seleziona "Configurazione IR".
            2.  Selezionare la funzione Doppio colpo (Abilita/Disabilita), Sensibilità (Alta/Media/Bassa) e Immunità agli animali domestici (Abilita/Disabilita) dal menu a discesa, quindi fare clic su "Invia" per confermare l'impostazione.
-   _**Segnale di supervisione**_
    -   -   Dopo l'installazione, la telecamera PIR trasmetterà automaticamente periodicamente i segnali di supervisione al pannello di controllo a intervalli casuali di 20-30 secondi.
-   _**Protezione antisabotaggio**_
    -   -   La telecamera PIR è protetta da un interruttore antimanomissione interno che viene compresso quando la telecamera PIR viene agganciata alla staffa di montaggio. Quando la telecamera PIR viene rimossa dalla staffa di montaggio, l'interruttore antimanomissione verrà attivato e la telecamera PIR invierà un segnale di apertura antimanomissione alla centrale di controllo per ricordare all'utente questa condizione.
-   _**Antimascheramento**_
    -   -   La telecamera PIR è dotata di un rilevatore di prossimità digitale in grado di rilevare eventuali tentativi di mascheramento (blocco) da parte di un intruso.
        -   Quando viene rilevato un evento di mascheramento e la condizione di mascheramento dura 3 minuti, VST-892EX-BUS invierà un segnale di allarme di mascheramento al pannello di controllo per notificare all'utente la condizione di mascheramento.
        -   Dopo che il mascheramento/blocco è stato rimosso per 3 minuti, VST-892EX-BUS invierà un segnale di ripristino al Pannello di Controllo.
-   _**Alimentazione elettrica**_
    -   -   Quando il VST-892EX-BUS è cablato a un pannello ibrido, l'alimentazione da 13,5 V può essere fornita dal pannello ibrido.
-   _**Attenzione**_![](.gitbook/assets/17.jpeg)
    -   Il cablaggio della telecamera PIR deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate sulle apparecchiature elettriche.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   _**Cablaggio telecamera PIR esterna**_
    -   -   Prima di collegare la telecamera PIR al bus di sistema, spegnere l'alimentazione.
        -   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/18 (3).png>)![](<.gitbook/assets/19 (3).png>)![](<.gitbook/assets/20 (2).png>)

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale dei dispositivi della linea BUS collegati, assicurarsi che gli interruttori a ponticello della resistenza terminale del primo (normalmente il pannello ibrido) e dei dispositivi BUS più lontani su una linea BUS siano impostati su ON per fungere da resistenze di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

_\\<NOTE>_

-   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.

3

-   -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.
-   _**Per iniziare: apprendere la telecamera PIR nel pannello di controllo**_

Seguire i passaggi seguenti per apprendere il dispositivo al pannello ibrido.

Passaggio 1. Collegare il dispositivo al pannello. Quindi, accendere il pannello.

Passaggio 2. Nella pagina Web del Pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3. Fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

Passaggio 4. Fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

Passaggio 5. Se il dispositivo viene acquisito con successo nel Pannello, verrà visualizzato nella sezione "Dispositivo acquisito".

-   _**Identificazione**_

IL "**Identificare**La funzione ” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per localizzare la Telecamera PIR nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo della telecamera IR.

**Passo 2.**Se la telecamera PIR riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED della telecamera PIR lampeggerà 10 volte per indicare all'utente dove si trova.

_\\<NOTE>_

-   -   -   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che la telecamera PIR non ha ricevuto il segnale dal pannello.

Verificare se la telecamera PIR è collegata correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Prova della camminata**_
    -   Per assicurarsi che la telecamera PIR sia in grado di comunicare con il pannello dopo l'apprendimento, posizionare il pannello di controllo in modalità Walk Test e premere il pulsante test sul VST-892EX-BUS per trasmettere un segnale di test al pannello.
    -   Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà di conseguenza le informazioni della telecamera PIR in cima all'elenco dei dispositivi.

_\\<NOTE>_

-   -   -   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se la telecamera PIR è collegata correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Metodo di montaggio e installazione**_
    -   **Montaggio con la staffa di montaggio:**
        -   -   La telecamera PIR può essere montata su una superficie piana con le viti di fissaggio, i tasselli e la staffa di montaggio in dotazione.
            -   La staffa di montaggio fornita è dotata di fori, dove la plastica è più sottile e può essere rotta per il montaggio

4

scopo.

-   Per montare VST-892EX-BUS con la staffa di montaggio:
    1.  Utilizzare la staffa di montaggio come sagoma e praticare 2 fori sulla parete per i tasselli.
    2.  Inserire i tasselli e fissare la staffa di montaggio alla parete con le viti.
    3.  Agganciare il VST-892EX-BUS sulla staffa di montaggio e poi**spingere verso il basso finché non si sente un clic**.

_\\<NOTE>_

-   Assicurarsi che la telecamera PIR sia agganciata correttamente alla staffa di montaggio, in modo che l'interruttore antimanomissione interno sia completamente premuto.
-   **Montaggio con staffa di montaggio e supporto rotante:**

Un supporto rotante è fornito come opzione di montaggio facile da usare**(articolo opzionale, venduto separatamente)**. È composto da una base da fissare a una superficie e da una sfera girevole per fissare la staffa di montaggio al supporto rotante.

Con il supporto rotante, la telecamera PIR può essere ruotata orizzontalmente per fornire una copertura ottimale.

Per fissare il supporto rotante alla parete viene fornito uno speciale cacciavite con punta bilaterale reversibile e viti con esagono incassato a tre stelle. Utilizzare il cacciavite in dotazione per serrare/allentare le viti con presa a stella.

5

-   -   Per montare VST-892EX-BUS con la staffa di montaggio e il supporto rotante:

1.  Fissare il supporto rotante alla parete con le viti fornite.
2.  Fissare la staffa di montaggio sulla sfera girevole con la vite di fissaggio fissata attraverso il foro dal design infallibile.
3.  Agganciare il VST-892EX-BUS alla staffa di montaggio e poi spingere verso il basso finché non si sente un clic.
4.  Ruotare la sfera girevole orizzontalmente per regolare l'angolo di rilevamento del VST-892EX-BUS. (Quando la vite di regolazione dell'angolo è allentata a metà, la sfera girevole può ancora essere ruotata.)
5.  Quando il VST-892EX-BUS viene ruotato in una posizione con la copertura di rilevamento desiderata, è possibile bloccare la posizione stringendo saldamente la vite di regolazione dell'angolo.

-   _**Raccomandazioni per l'installazione**_

**Si consiglia di installare la telecamera PIR nelle seguenti posizioni:**

-   Ad un'altezza di 2,3 metri (misurata dalla parte inferiore della fotocamera) sopra il livello del suolo per ottenere le migliori prestazioni
-   In un angolo per la visuale più ampia
-   In un luogo in cui un intruso normalmente si sposterebbe attraverso il campo visivo della telecamera PIR
-   Su una superficie o in un angolo dove gli animali sono inaccessibili
-   La telecamera PIR ha un raggio di rilevamento di 10 metri se montata a un'altezza di 2,3 metri dal suolo.

**Campo di rilevamento 892EX-BUS**

6

**Limitazioni:**

-   -   Non esporre completamente la telecamera PIR alla luce solare diretta.
    -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
    -   Non affrontare fonti di calore come fuochi e caldaie, né direttamente né installare sopra radiatori.
    -   Non tentare mai di smontare o modificare il dispositivo.
-   Installare la telecamera PIR verso l'alto. Non inclinarlo.
-   Non installare la telecamera con sensore di movimento dove gli oggetti vengono spostati dal vento, come alberi e biancheria, che potrebbero bloccare il campo visivo della telecamera con sensore di movimento.

7

_\\<IMPORTANT NOTE>_

-   Regolare i Dip Switch in base alla posizione di installazione della telecamera PIR per ottenere prestazioni ideali. Se le impostazioni del Dip Switch non corrispondono all'ambiente di installazione, le prestazioni della telecamera PIR saranno ostacolate e potrebbero causare falsi allarmi o l'impossibilità di rilevare il movimento.
-   La telecamera PIR rileva le differenze tra l'oggetto in movimento e lo sfondo. Se l'oggetto è inattivo (cioè non in movimento), la telecamera PIR non è in grado di rilevarlo.
-   La telecamera PIR ha una caratteristica direzionale ed è più efficace nel rilevare gli intrusi che si muovono nel suo campo di rilevamento. È meno sensibile nel rilevare i movimenti direttamente davanti alla telecamera PIR.
-   Per prestazioni ottimali, ricordarsi di regolare l'altezza di montaggio della telecamera con sensore di movimento rispetto all'altezza dell'animale domestico più alto della casa. I cani più alti richiedono che la telecamera con sensore di movimento sia montata più in alto per garantire la compatibilità con gli animali domestici.
-   La telecamera PIR ha un punto cieco di circa 1 metro sotto la telecamera se montata ad un'altezza di 2,3 metri. L'area dell'angolo cieco aumenterà se la telecamera PIR è montata a un'altezza superiore a 2,3 metri e si ridurrà se montata a un'altezza inferiore a tale altezza.
-   Se non richiesto, si consiglia di mantenere la posizione di montaggio della telecamera PIR a un'altezza di 2,3 metri per ottenere prestazioni ottimali. Se si modifica l'altezza di montaggio, eseguire un test di rilevamento per assicurarsi che la telecamera PIR possa normalmente rilevare gli intrusi all'altezza scelta.

8
