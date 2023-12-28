# VESTA040

Sensore di urti, vibrazioni e rottura vetri SVGS-5

SVGS-5 è un sensore di urti, vibrazioni/rottura vetro. È in grado di inviare segnali wireless al pannello di controllo al rilevamento della rottura del vetro della finestra o di urti/vibrazioni.

![](<.gitbook/assets/0 (9).jpeg>)Identificazione delle parti

1.  **Pulsante Apprendi/Test**

(Premere il pulsante con uno strumento appuntito come una graffetta.)

-   Premere una volta il pulsante per trasmettere un codice di apprendimento/test.
-   Premere il pulsante una volta per accedere alla modalità test per 3 minuti.
-   Premere il pulsante per 5 secondi per regolare le impostazioni di sensibilità dal pannello di controllo.

1.  **Indicatore LED**

-   **Si accende per 1 secondo:**Quando il sensore è acceso.
-   **Lampeggia una volta:**Segnale di trasmissione.
-   **Lampeggia tre volte lentamente:**Rilevata batteria scarica all'accensione.

**Caratteristiche**

-   _Rilevamento batteria e batteria scarica_
-   Il sensore ne usa uno**P2477ZV**Batteria al litio come fonte di alimentazione.
-   Il sensore è in grado di rilevare una bassa tensione della batteria. Quando la batteria è scarica, un segnale di batteria scarica verrà inviato al pannello di controllo insieme alla trasmissione regolare.
-   Quando si cambia la batteria, utilizzare uno strumento affilato per aprire lo slot della batteria per rimuovere e inserire la batteria.
-   Quando si inserisce la batteria, il**positivo(+)**il lato della batteria deve essere rivolto verso l'alto.**MAI**inserire la batteria con il lato negativo (-) rivolto verso l'alto.

![](<.gitbook/assets/1 (6).jpeg>)

-   _**Supervisione**_

Il sensore trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione in base alle impostazioni dell'utente. L'intervallo predefinito di fabbrica è 30-50 minuti.

-   _**Regolazione della sensibilità**_

Il sensore può inviare segnali di allarme alla centrale in base ai diversi livelli di sensibilità impostati nella centrale. I livelli di sensibilità includono alto, medio e basso (l'impostazione predefinita è media se nel Pannello di controllo non è impostato alcun livello di sensibilità). Maggiore è la sensibilità, più facile sarà l'attivazione del sensore quando viene rilevata la rottura di una finestra/vetro o una vibrazione d'urto.

Dopo aver aggiunto il sensore al Pannello di controllo, è possibile impostarne ulteriormente il livello di sensibilità dal Pannello di controllo o dalla Home

Pagina Web del server del portale.

1.  Utilizzare uno strumento affilato come una graffetta per premere il pulsante Test sul sensore per 5 secondi. Il LED del sensore sarà acceso fisso.
2.  Fare riferimento al manuale operativo del pannello di controllo per modificare il dispositivo. Gli utenti saranno in grado di regolare le impostazioni di sensibilità entro 10 secondi.
3.  Vai a**Tipo e sensibilità**e seleziona l'impostazione desiderata dal menu a discesa.
4.  Clic**OK**per confermare. Il LED del sensore si affievolirà per indicare l'operazione riuscita.

-   Per i dettagli sulla gamma della modalità di rilevamento di urti/vibrazioni, vedere la sezione Installazione nella sezione successiva.
-   _**Modalità di rilevamento**_
-   La funzione di rilevamento di urti/vibrazioni del dispositivo può essere attivata in base alla diversa modalità selezionata nel Pannello di controllo.
-   **Modalità di shock a impulso singolo**_**(modalità predefinita per SVGS-5 se non è impostata alcuna modalità di rilevamento nel Pannello di controllo)**_

Il dispositivo viene attivato da un singolo rilevamento di shock che supera la soglia di rilevamento.

-   **Modalità Multi Impulso/Vibrazione Accumulata**

Il dispositivo viene attivato da una delle seguenti condizioni:

1.  Quando**3**i conteggi degli impulsi vengono rilevati all'interno**20****secondi**.
2.  Quando si accumulano vibrazioni minori rilevate con**2 minuti**supera la soglia di rilevamento.

-   Per i dettagli sulla gamma della modalità di rilevamento di urti/vibrazioni, vedere la sezione**Installazione**nella sezione successiva.
-   _**Modalità di prova**_

Il sensore può essere messo in modalità test per 3 minuti premendo il pulsante test:

-   Premere una volta il pulsante Impara/Test, il LED lampeggerà per indicare che il sensore è stato messo in modalità test.
-   In modalità test, ogni volta che il sensore viene attivato, il LED lampeggia.
-   Il sensore uscirà dalla modalità test dopo 3 minuti.
-   _**Sveglia**_

Il sensore entrerà in un periodo di sospensione di 2 minuti dopo ogni attivazione. Il sensore non ritrasmetterà il segnale di rilevamento durante questo periodo di 2 minuti. Ogni attivazione del rilevamento di shock durante questo periodo riporterà il timer di spegnimento a 2 minuti. Il tempo di sospensione scade solo se non viene rilevato alcuno shock per 2 minuti, quindi il sensore tornerà al funzionamento normale e trasmetterà il successivo segnale di rilevamento dello shock.

Learning and Installation

-   _**Apprendimento**_

1.  Estrarre l'isolatore della batteria dal sensore.
2.  Fare riferimento al manuale del pannello di controllo per mettere il pannello in modalità di apprendimento.
3.  Premere una volta il pulsante Apprendimento/Test per trasmettere un codice di apprendimento.
4.  Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.

-   _**Superficie e materiale di montaggio**_

Il sensore deve essere montato direttamente su una superficie di vetro o compensato.

-   Spessore del vetro: Vetro placcato, temperato e laminato: minimo 5 mm.
-   Spessore del compensato: massimo 9 mm.
-   Spessore della cassetta di sicurezza: minimo 3 mm
-   _**Sensibilità e campo di rilevamento**_

La sensibilità del sensore viene regolata tramite il pannello di controllo. Il campo di rilevamento della diversa sensibilità varia a seconda dei materiali della superficie di montaggio.

|                                         | Bicchiere                                 | Compensato                                   | Scatola di sicurezza        |   |
| --------------------------------------- | ----------------------------------------- | -------------------------------------------- | --------------------------- | - |
| Materiale                               | Vetro placcato/temperato/laminato/cablato | Compensato                                   | Acciaio/Biossido di silicio |   |
| Spessore                                | Minimo 5 mm                               | Massimo 9 mm                                 | minimo                      |   |
| Modalità di rilevamento urti/vibrazioni | Modalità a impulso singolo                | Modalità multi impulso/vibrazione accumulata |                             |   |
| Sensibilità                             | Basso                                     | 8000mm                                       | 2000 mm                     | - |
| medio                                   | 10000 mm                                  | 2500 mm                                      | -                           |   |
| Alto                                    | 12000 mm                                  | 3000 mm                                      | 1400 mm                     |   |

-   _**Passaggi e linee guida per l'installazione**_

1.  Regolare la sensibilità del sensore come desiderato in base al materiale della superficie di montaggio utilizzando la tabella fornita in precedenza

sezione.

**Installazione su finestra/parete:**

Determinare la posizione di montaggio su finestra o parete. Il sensore può essere montato al centro o all'angolo. Se un sensore non è in grado di coprire l'intera superficie, utilizzare più sensori.

\\<NOTE>

-   Durante il montaggio ad angolo, assicurarsi di mantenere una distanza di almeno 10 mm tra il sensore e il bordo della finestra o del muro. Regolare la direzione dello slot della batteria (**Non affrontare l'angolo**) per evitare difficoltà durante la rimozione dello slot della batteria.

**Installazione della cassetta di sicurezza:**

Quando si monta su Safety Box, montare il sensore a non più di 2 cm di distanza dal perno della porta.

1.  ![](<.gitbook/assets/5 (12).png>)Pulire e asciugare la posizione di montaggio. Non installare su superfici sporche o web.
2.  Utilizzare il nastro biadesivo fornito (Ø35 mm x 8 mm) da applicare al coperchio posteriore di SVGS e attaccare il sensore nella posizione di montaggio.

\\<NOTE>

-   Non applicare il nastro biadesivo sul coperchio anteriore dove si trovano il pulsante Test e l'indicatore LED e non applicare il nastro due volte.

![](<.gitbook/assets/6 (7).png>)

-   _**Installation Guideline**_
-   Assicurarsi sempre di testare il raggio di rilevamento dopo l'installazione per confermare il raggio di rilevamento effettivo.
-   Il nastro adesivo potrebbe perdere la sua appiccicosità nel tempo. Assicurati di controllare il sensore almeno una volta ogni 6 mesi.
-   Evitare il montaggio in luoghi soggetti a forte vento che potrebbe spostare il sensore.
-   Evitare il montaggio in luoghi soggetti a scosse o vibrazioni, che potrebbero causare falsi allarmi.
-   Impostare il sensore su una sensibilità bassa durante l'installazione su finestre mobili per evitare falsi allarmi.
-   Evitare il montaggio in una posizione in cui il sensore potrebbe facilmente entrare in collisione con un oggetto.
-   Durante il montaggio su compensato:

1.  Utilizzare solo l'impostazione di sensibilità elevata.
2.  Il montaggio a parete accanto a mobili di grandi dimensioni può influenzare la portata di rilevamento del sensore e la portata di trasmissione del segnale. Assicurarsi di testare il sensore se si sceglie di montarlo in tale posizione.

-   Il campo di rilevamento del sensore dipende dalle dimensioni e dal materiale del nastro adesivo. La tabella dei range di sensibilità fornita in questo documento è testata con il nastro adesivo fornito dalla fabbrica. Se si utilizza un nastro adesivo diverso, assicurarsi di testare nuovamente il campo di rilevamento.
