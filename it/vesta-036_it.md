# VESTA036

**Sensore di movimento PIR immune agli animali domestici da esterno (EIR-32)**

L'EIR-32, un rilevatore PIR da esterno alimentato a batteria, consente un'installazione esterna economica e semplice fornendo allo stesso tempo eccezionali capacità di rilevamento.

Il sensore integrato con sensibilità di rilevamento elimina la possibilità di falsi allarmi causati da piccoli animali o altri disturbi esterni.

La funzione antimascheramento consente di rilevare eventuali tentativi di accecamento del rilevatore posizionando oggetti nel suo campo visivo.

Inoltre, il campo di rilevamento regolabile offre la soluzione efficace per ogni ambiente di installazione, offrendo uno stile di vita tranquillo e proteggendo allo stesso tempo i tuoi locali e le persone a te care tutto l'anno.

-   _**Identificazione delle parti**_

**Vista frontale****Vista interna****Vista posteriore**

![](<.gitbook/assets/0 (32).png>)

1.  **Rilevatore di prossimità digitale**

Il rilevatore viene utilizzato per rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.

1.  **Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato del sistema.

1.  **Sensore IR**

Il sensore è destinato a rilevare oggetti in movimento.

1.  **Pulsante di prova**

Il pulsante Test viene utilizzato per testare le prestazioni della radio e per scopi di apprendimento.

1.  **Blocco interruttore DIP**

Sono presenti 8 DIP Switch per impostare la funzione e i livelli di sensibilità di rilevamento.

1.  **Interruttore antimanomissione**

EIR-32 è protetto dall'interruttore antimanomissione contro qualsiasi rimozione non autorizzata dalla piastra di montaggio o dalla posizione di montaggio.

1.  **Compartimento della batteria**
2.  **Piastra di montaggio**
3.  **Zona separatista**

L'area Breakaway ha 6 fori (2 per il montaggio su superficie e 4 per il montaggio ad angolo) dove la plastica è più sottile per il montaggio con viti. Quando il rilevatore viene rimosso con la forza dalla posizione di montaggio, l'area Break Away si staccherà e consentirà l'attivazione dell'interruttore antimanomissione.

**10. Scudo protettivo**

Lo schermo protettivo protegge il rilevatore digitale di prossimità dalla pioggia.

-   _**Indicatore LED**_

Nella modalità di funzionamento normale, l'indicatore LED rimane spento tranne:

-   Quando il sensore di movimento è in condizioni di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED lampeggerà

1

6 volte.

-   -   Quando l'interruttore antimanomissione viene attivato, il LED lampeggerà per 6 volte per indicare che sta trasmettendo "**Manomettere**" segnale.
    -   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED lampeggerà per 6 volte.
    -   In modalità Test, il LED lampeggerà per 6 volte ogni volta che viene rilevato un movimento.
-   _**Modalità di prova**_

Il sensore di movimento può essere messo in modalità Test per 10 minuti premendo una volta il pulsante Test. In modalità Test, il timer di spegnimento è disabilitato e l'indicatore LED è abilitato ad accendersi per due secondi ogni volta che viene rilevato un movimento. Il sensore di movimento uscirà automaticamente dalla modalità test dopo 10 minuti e tornerà alla modalità normale.

Per mettere il sensore di movimento in modalità test costante, regolare il DIP switch 1 (fare riferimento a_Tabella delle posizioni dei DIP switch_).

-   _**Batteria**_
    -   Il sensore di movimento utilizza due batterie al litio AAL91 come fonte di alimentazione.
    -   Il sensore di movimento è dotato di rilevamento della tensione della batteria bassa. Quando viene rilevata una batteria scarica, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo possa visualizzare lo stato di conseguenza.
    -   **Per cambiare la batteria:**

**Passo 1:**Navigare nel Pannello di Controllo in modalità Programmazione.

**Passo 2:**Rimuovere il sensore di movimento dalla posizione di montaggio e svitarlo per aprire il coperchio superiore.

**Passaggio 3:**Rimuovere le vecchie batterie e premere il pulsante antimanomissione per alcuni secondi per scaricarle completamente.

**Passaggio 4:**Inserire due nuove batterie al litio AAL91.

**Passaggio 5:**Riavvitare il coperchio superiore.

**Passaggio 6:**Rimontare il sensore di movimento nella posizione di montaggio.

**Passaggio 7:**Navigare nel Pannello di controllo per uscire dalla modalità di programmazione e tornare alla modalità operativa. La procedura è completa.

-   _**Segnale di vigilanza**_
    -   Dopo l'installazione, il sensore di movimento trasmetterà automaticamente periodicamente i segnali di supervisione al pannello di controllo a intervalli casuali da 30 a 50 minuti.
    -   Se il pannello di controllo non ha ricevuto il segnale dal sensore di movimento per il periodo di tempo preimpostato, il pannello di controllo indicherà sul display che il particolare sensore di movimento sta riscontrando un problema di segnale assente.
-   _**Sveglia**_

Il sensore di movimento dispone di un "tempo di sospensione" automatico di circa un minuto per il risparmio energetico. Dopo aver trasmesso un movimento rilevato, il sensore di movimento non lo ritrasmetterà per un minuto. Qualsiasi ulteriore movimento rilevato entro questo periodo di sonno di un minuto prolungherà la durata del sonno di un altro minuto. In questo modo, il movimento continuo davanti al sensore di movimento non scaricherà eccessivamente la batteria.

-   _**Funzione doppio colpo**_

Il sensore di movimento ha una funzione di doppio battito. Se è abilitata la funzione doppio battito, il Sensore di Movimento segnalerà un allarme alla centrale solo se vengono rilevati due movimenti entro 10 secondi. Se la funzione del doppio colpo è disabilitata, il sensore di movimento segnalerà un allarme alla centrale quando viene rilevato un movimento.

-   _**Rilevamento di prossimità**_
    -   Il sensore di movimento è dotato di un rilevatore di prossimità digitale in grado di rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.
    -   Quando viene rilevato un evento di mascheramento e la condizione di mascheramento dura 2 minuti, EIR-32 invierà un segnale di apertura antimanomissione alla centrale di controllo per notificare all'utente la condizione.
    -   Dopo che il mascheramento/blocco è stato rimosso per 2 minuti, EIR-32 invierà un segnale di ripristino della manomissione alla centrale di controllo.

_\\<NOTE>_

-   -   Qualsiasi movimento del trigger IR annullerà l'evento/condizione di mascheramento attualmente rilevato. Un evento di mascheramento deve essere rilevato e durare 2 minuti affinché venga trasmesso il report di apertura manomissione.
-   _**Tabella delle posizioni dei DIP switch**_

La funzione di ciascun DIP Switch è elencata nella tabella seguente. L'interruttore DIP è ON o OFF. La posizione superiore indica ON e la posizione inferiore indica OFF.

|   | IMMERSIONE    |   |        | Posizione |                                               |                                      | Funzione |   |   |
| - | ------------- | - | ------ | --------- | --------------------------------------------- | ------------------------------------ | -------- | - | - |
|   |               |   |        |           |                                               |                                      |          |   |   |
|   | Interruttore1 |   |        | SU        |                                               | Modalità di prova                    |          |   |   |
|   |               |   | SPENTO |           | Modalità normale (predefinita)                |                                      |          |   |   |
|   |               |   |        |           |                                               |                                      |          |   |   |
|   | Interruttore2 |   |        | SU        |                                               | Riservato                            |          |   |   |
|   |               |   | SPENTO |           |                                               |                                      |          |   |   |
|   |               |   |        |           |                                               |                                      |          |   |   |
|   |               |   |        | SU        |                                               | PIR rivolto verso un muro entro 10 m |          |   |   |
|   | Interruttore3 |   |        | SPENTO    |                                               | PIR affacciato su uno spazio aperto  |          |   |   |
|   |               |   |        |           | (nessun muro nel raggio di 10 m)(predefinito) |                                      |          |   |   |
|   |               |   |        |           |                                               |                                      |          |   |   |
|   |               |   |        | SU        |                                               | PIR fronte prato (default)           |          |   |   |
|   | Interruttore4 |   |        | SPENTO    |                                               | PIR rivolto verso un cemento/pietra  |          |   |   |
|   |               |   |        | terra     |                                               |                                      |          |   |   |
|   |               |   |        |           |                                               |                                      |          |   |   |
|   |               |   |        |           |                                               |                                      |          |   |   |

![](<.gitbook/assets/1 (36).png>)

|   |               | IMMERSIONE |        |               | Livello di sensibilità                     |                                                       |          |   |   |
| - | ------------- | ---------- | ------ | ------------- | ------------------------------------------ | ----------------------------------------------------- | -------- | - | - |
|   |               |            |        |               |                                            |                                                       |          |   |   |
|   | Interruttore5 |            |        | Interruttore6 |                                            |                                                       |          |   |   |
|   | SU            |            |        | SU            |                                            | Basso; Animale domestico da 60 kg (predefinito)       |          |   |   |
|   | SU            |            |        | SPENTO        |                                            | Medio; Animale domestico di 35 kg                     |          |   |   |
|   | SPENTO        |            |        | SU            |                                            | Alto; Animale domestico da 20 kg                      |          |   |   |
|   | SPENTO        |            |        | SPENTO        |                                            | Riservato                                             |          |   |   |
|   |               |            |        |               |                                            |                                                       |          |   |   |
|   | IMMERSIONE    |            |        | Posizione     |                                            |                                                       | Funzione |   |   |
|   | Interruttore7 |            |        | SU            |                                            | Abilitazione doppio tocco (impostazione predefinita)  |          |   |   |
|   |               |            | SPENTO |               | Disabilita doppio colpo                    |                                                       |          |   |   |
|   |               |            |        |               |                                            |                                                       |          |   |   |
|   | Interruttore8 |            |        | SU            |                                            | Abilita immunità agli animali domestici (predefinita) |          |   |   |
|   |               |            | SPENTO |               | Disabilita immunità agli animali domestici |                                                       |          |   |   |
|   |               |            |        |               |                                            |                                                       |          |   |   |

![](<.gitbook/assets/2 (42).png>)

SU

![](<.gitbook/assets/3 (40).png>)

SPENTO

_**\\<NOTE>**_

-   Dopo aver modificato le impostazioni del Dip Switch, riaccendere l'EIR-32 affinché funzioni con le nuove impostazioni del Dip Switch.

2

-   _**Protezione antisabotaggio**_
    -   EIR-32 è protetto da un interruttore antimanomissione che viene compresso quando viene agganciato alla staffa di montaggio.
    -   Ogni volta che il sensore di movimento viene rimosso dalla piastra di montaggio, l'interruttore antimanomissione verrà attivato.
    -   Quando il sensore di movimento viene rimosso con la forza dalla posizione di montaggio, l'area Break Away sulla piastra di montaggio si stacca, consentendo anche l'attivazione dell'interruttore antimanomissione.
    -   Il sensore di movimento invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione ogni volta che l'interruttore antimanomissione viene attivato.
-   _**Per iniziare: apprendere il sensore di movimento nel pannello di controllo**_
    -   Allentare le viti di fissaggio e rimuovere il gruppo coperchio.
    -   In base alle tue esigenze, imposta l'interruttore di sensibilità come mostrato in_Tabella delle posizioni dei DIP switch_.
    -   Inserire due batterie al litio AAL91 nel portabatterie facendo attenzione a collegare correttamente la polarità.
    -   L'indicatore LED lampeggerà per 60 secondi. Il sensore di movimento si sta riscaldando. Durante il periodo di riscaldamento, il sensore di movimento non è attivato. Si consiglia di rimanere lontani dall'area di rilevamento durante questo periodo. Al termine del periodo di riscaldamento, il LED si attenua e il sensore di movimento è pronto per funzionare.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Premere una volta il pulsante Prova. L'indicatore LED lampeggerà per tre volte.
    -   Se il pannello di controllo riceve il segnale, visualizzerà le informazioni di conseguenza. Fare riferimento al manuale del Pannello di controllo per completare il processo di apprendimento. (Per alcuni modelli di centrale, il sensore di movimento può essere appreso come un normale PIR con attributi programmabili e quindi la centrale segnalerà quando viene attivato un allarme).
    -   Dopo aver appreso il sensore di movimento, mettere il pannello di controllo in modalità Walk Test. Tenere il sensore di movimento nella posizione desiderata e premere il pulsante Test per verificare che questa posizione rientri nel raggio del segnale del pannello di controllo.
    -   Quando sei soddisfatto che il sensore di movimento funzioni nella posizione scelta, puoi procedere all'installazione.

_\\<NOTE>_

-   -   -   **Prova della camminata**essere condotto per confermare il corretto funzionamento e la copertura del sensore di movimento.
        -   Durante l'apprendimento del sensore di movimento o l'esecuzione del test di camminata, evitare di ostruire il rilevatore antimascheramento con le mani, altrimenti il ​​segnale di apertura antimanomissione verrà trasmesso al pannello di controllo se la condizione di mascheramento dura per 2 minuti.
-   _**Metodo di montaggio e installazione**_
    -   **Montaggio con piastra di montaggio:**
        -   -   Il sensore di movimento è progettato per essere montato su una superficie piana o in una situazione d'angolo con viti di fissaggio e tasselli forniti.
            -   La piastra di montaggio fornita è dotata di fori in cui la plastica è più sottile e può essere rotta per il montaggio. Due fori a sfondamento sono per il fissaggio in superficie e quattro fori a sfondamento sono per il fissaggio ad angolo, come mostrato in figura.
            -   Per montare l'EIR-32 con la staffa di montaggio:
                1.  Utilizzare la piastra di montaggio come sagoma per praticare i fori sulla parete per i tasselli.
                2.  Inserire i tasselli e fissare la piastra di montaggio alla parete con le viti.
                3.  Montare l'EIR-32 con i ganci della piastra di montaggio fissati sul coperchio posteriore dell'EIR-32, quindi spingere verso il basso finché non si sente un clic per bloccare il gancio.
                4.  Inserire lo schermo protettivo (è necessario prima rimuovere la pellicola protettiva da entrambi i lati).

![](<.gitbook/assets/4 (26).jpeg>)![](<.gitbook/assets/5 (34).png>)

3

-   **Montaggio con piastra di montaggio e supporto rotante (opzionale):**
    -   Un supporto rotante è fornito come opzione di montaggio facile da usare**(articolo opzionale, venduto separatamente)**. È composto da una base da fissare alla superficie e da una sfera girevole da fissare alla piastra di montaggio e all'EIR-32.

![](<.gitbook/assets/6 (23).jpeg>)

-   Grazie al supporto rotante, l'EIR-32 può essere ruotato orizzontalmente per fornire una copertura ottimale.

Per fissare il supporto rotante alla parete vengono forniti uno speciale cacciavite con punta bilaterale reversibile e viti con esagono incassato a tre stelle.

![](<.gitbook/assets/7 (18).png>)

Utilizzare il cacciavite in dotazione per serrare/allentare le viti con presa a stella.

![](<.gitbook/assets/8 (21).png>)

-   Per montare EIR-32 con piastra di montaggio e supporto rotante:
    1.  Fissare il supporto rotante alla parete con le viti fornite.
    2.  Fissare la piastra di montaggio sulla sfera girevole con la vite di fissaggio fissata attraverso il foro dal design infallibile.
    3.  Montare l'EIR-32 con i ganci della piastra di montaggio fissati sul coperchio posteriore dell'EIR-32, quindi spingere verso il basso finché non si sente un clic per bloccare il gancio.
    4.  Inserire lo schermo protettivo (è necessario prima rimuovere la pellicola protettiva da entrambi i lati).

![](<.gitbook/assets/9 (20).png>)

4

1.  Ruotare la sfera girevole orizzontalmente per regolare l'angolo di rilevamento dell'EIR-32. (Quando la vite di regolazione dell'angolo è allentata a metà, la sfera girevole può ancora essere ruotata.)
2.  Quando l'EIR-32 viene ruotato in una posizione con la copertura di rilevamento desiderata, è possibile bloccare la posizione stringendo saldamente la vite di regolazione dell'angolo.

![](<.gitbook/assets/10 (10).jpeg>)

_\\<NOTE>_

-   -   Dopo aver montato EIR-32, se la centrale di controllo visualizza lo stato di guasto manomissione per il dispositivo, assicurarsi che il rilevatore antimascheramento non sia ostruito da alcun oggetto e attendere due minuti per vedere se lo stato manomissione aperta viene cancellato. Se lo stato Tamper aperto persiste dopo due minuti, rimuovere EIR-32 dalla posizione di montaggio e verificare se l'interruttore antimanomissione è adeguatamente compresso contro la piastra di montaggio.
-   _**Raccomandazioni per l'installazione**_

**Si consiglia di installare il sensore di movimento nelle seguenti posizioni:**

![](<.gitbook/assets/11 (14).png>)

-   Ad un'altezza di 2 metri (misurata dalla parte inferiore del sensore di movimento) dal suolo per ottenere le migliori prestazioni.
-   In un angolo per la visuale più ampia.
-   Il punto in cui un intruso normalmente si sposterebbe attraverso il campo visivo del sensore di movimento.
-   Su una superficie o in un angolo dove gli animali sono inaccessibili.
-   Il sensore di movimento ha un raggio di rilevamento di 10 M se montato a un'altezza di 2 metri dal suolo.

**Limitazioni:**

-   Non esporre completamente il sensore di movimento alla luce solare diretta.
-   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
-   Non affrontare fonti di calore come fuochi e caldaie, né installare sopra termosifoni.
-   Non tentare mai di smontare o modificare l'unità.
-   Installare il sensore di movimento verso l'alto. Non inclinarlo.

![](<.gitbook/assets/12 (11).jpeg>)

-   Non installare il sensore di movimento in prossimità di oggetti mossi dal vento, come alberi e biancheria, che potrebbero bloccare il campo visivo del sensore di movimento.

![](<.gitbook/assets/13 (11).jpeg>)

5

-   Eliminare tutte le superfici riflettenti la luce dall'area di rilevamento, nonché le pozzanghere d'acqua.

![](<.gitbook/assets/14 (12).jpeg>)

-   Evitare di mirare al percorso del flusso d'aria di aspirazione o di scarico dell'unità esterna.

![](<.gitbook/assets/15 (9).jpeg>)

_\\<IMPORTANT NOTE>_

-   Regolare i Dip Switch in base alla posizione di installazione del sensore di movimento per ottenere prestazioni ideali. Se le impostazioni del Dip Switch non corrispondono all'ambiente di installazione, le prestazioni del sensore di movimento saranno ostacolate e potrebbero causare falsi allarmi o l'impossibilità di rilevare il movimento.
-   Il sensore di movimento rileva le differenze tra l'oggetto in movimento e lo sfondo. Se l'oggetto è fermo (cioè non in movimento), il sensore di movimento non è in grado di rilevarlo.
-   Il sensore di movimento ha una caratteristica direzionale ed è più efficace nel rilevare intrusi che si muovono attraverso il campo di rilevamento. È meno sensibile nel rilevare il movimento direttamente verso il sensore di movimento.
-   Per prestazioni ottimali, ricordarsi di regolare l'altezza di montaggio del sensore di movimento rispetto all'altezza dell'animale domestico più alto della casa. I cani più alti richiedono che il sensore di movimento sia montato più in alto per una maggiore compatibilità con gli animali domestici.
-   Il sensore di movimento ha un punto cieco di circa 1 metro sotto di esso se montato ad un'altezza di 2 metri. L'area del punto cieco aumenterà se si monta il sensore di movimento a un'altezza superiore a 2 M e si ridurrà se inferiore a 2 M.
-   Se non richiesto, suggeriamo di mantenere la posizione di montaggio del sensore di movimento a 2M per prestazioni ottimali. Se si modifica l'altezza di montaggio, eseguire un test di rilevamento per assicurarsi che il sensore di movimento possa rilevare normalmente l'intruso all'altezza desiderata.

6
