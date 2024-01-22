# VESTA222

**PSS-29-F1/PSM-29-F1**

![](<.gitbook/assets/0 (92).jpeg>)

**Serie di interruttori di alimentazione**

**introduzione**

La serie Power Switch è progettata per consentire all'utente di accendere/spegnere da remoto un apparecchio ad esso collegato.

La serie Power Switch comprende i seguenti modelli:

**PSS-29-F1:**Interruttore di alimentazione

**PSM-29-F1:**Interruttore di alimentazione con misuratore

Il modello PSM-29-F1 è dotato di un misuratore di potenza integrato per misurare il consumo di elettricità. I dati energetici raccolti verranno riportati alla centrale.

L'integrazione del Power Switch nel tuo sistema domotico ti consentirà di controllare comodamente gli elettrodomestici per scopi di comfort o risparmio energetico.

**Identificazione delle parti**

![](<.gitbook/assets/1 (78).jpeg>)

**1. Pulsante Test, ovvero indicatore LED**

Il pulsante Test funge anche da indicatore LED. Il pulsante di prova viene utilizzato per controllare l'interruttore di alimentazione. L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore di alimentazione.

**Indicazione LED:**

L'indicatore LED si accende nelle seguenti condizioni:

-   Acceso: l'interruttore di alimentazione è acceso.
-   Spento: l'interruttore di alimentazione è spento.
-   Lampeggia due volte: quando è acceso.
-   Lampeggia lentamente: in modalità di apprendimento.
-   Lampeggia tre volte: quando l'apprendimento ha avuto successo.
-   Lampeggia brevemente: trasmissione del segnale RF

**Prova utilizzo pulsante:**

-   Premere il pulsante per attivare/disattivare l'interruttore di accensione
-   Tenere premuto il pulsante per 3 secondi per inviare un codice di apprendimento.
-   Tieni premuto il pulsante mentre accendi l'interruttore di accensione, quindi rilascia il pulsante quando il LED si accende per ripristinare le impostazioni di fabbrica

**Iniziare**

Passaggio 1: collegare l'interruttore di alimentazione alla presa di corrente.

Passaggio 2: mettere il pannello di controllo in modalità apprendimento.

Passaggio 3: tenere premuto il pulsante Test sull'interruttore di accensione per 3 secondi per inviare un codice di apprendimento.

Passo 4: Il LED inizierà a lampeggiare lentamente, indicando che l'interruttore di accensione è in modalità di apprendimento.

Passaggio 5: se il pannello di controllo riceve il segnale dall'alimentazione

interruttore, visualizzerà le informazioni di conseguenza. Fare riferimento al manuale del Pannello di controllo per completare il processo di apprendimento.

Passo 6: Quando l'interruttore di accensione riceve il codice di apprendimento dal pannello di controllo, il LED dell'interruttore di accensione lampeggerà 3 volte e poi si spegnerà per indicare che il processo di apprendimento è completo.

![](<.gitbook/assets/2 (72).png>)

_\\<NOTE>_

-   Dopo essere entrato nella modalità di apprendimento, l'interruttore di accensione non lascerà automaticamente la modalità di apprendimento a meno che non riceva conferma dal pannello di controllo o a meno che non venga premuto il pulsante Test.
-   Se l'interruttore di alimentazione esiste già in un sistema con pannello di controllo, sarà necessario rimuoverlo dal pannello di controllo prima di poterlo inserire in un pannello di controllo diverso.

1

**Prova della camminata**

Per verificare se l'interruttore di alimentazione è in grado di comunicare con il pannello di controllo:

-   Mettere il Pannello di Controllo in modalità Walk Test.
-   Premere il pulsante Test sull'interruttore di alimentazione.
-   Il pannello di controllo dovrebbe visualizzare se l'interruttore di alimentazione rientra nel raggio operativo (fare riferimento al manuale operativo del pannello di controllo).

**Supervisione**

-   Dopo che l'interruttore di accensione è stato acquisito con successo nel pannello di controllo, il dispositivo trasmetterà automaticamente il segnale di supervisione insieme allo stato ON/OFF al pannello di controllo a intervalli casuali da 30 a 50 minuti.
-   Se il pannello di controllo non ha ricevuto il segnale dall'interruttore di alimentazione per il periodo di tempo preimpostato, il pannello di controllo indicherà sul display che quel particolare interruttore di alimentazione sta riscontrando un problema di mancanza di segnale.

**Operazione**

![](<.gitbook/assets/3 (67).jpeg>)

-   _**Installazione**_
    -   Collegare l'interruttore di alimentazione a una presa di corrente, quindi collegare l'apparecchio alla presa dell'interruttore di alimentazione. L'apparecchio deve essere nello stato ON.
-   _**Controllo degli elettrodomestici**_
    -   Dopo che l'interruttore di alimentazione è stato acquisito con successo nel pannello di controllo, il pannello di controllo può accendere/spegnere in remoto l'interruttore di alimentazione per controllare l'apparecchio. Per i dettagli fare riferimento al manuale del pannello di controllo.
    -   È inoltre possibile premere il pulsante sull'interruttore di accensione per alternarne lo stato di accensione/spegnimento
    -   Se l'interruttore di alimentazione viene rimosso dalla presa di corrente, dopo averlo ricollegato, il suo precedente stato di accensione/spegnimento e i dati attuali sull'energia erogata (solo PSM-29-F1) verranno trasmessi al pannello di controllo.
-   _**Monitoraggio del consumo energetico (solo per PSM-29-F1)**_

![](<.gitbook/assets/4 (58).jpeg>)![](<.gitbook/assets/5 (39).jpeg>)

Con un misuratore di potenza integrato per misurare il consumo di elettricità, l'interruttore del misuratore di potenza PSM-29-F1 trasmetterà i dati sul consumo energetico al pannello di controllo quando:

-   -   Quando l'interruttore del misuratore di potenza è acceso/spento.
    -   Ogni volta che l'energia erogata dall'interruttore di accensione cambia di +/- 2 W.
    -   Ogni volta che il consumo energetico accumulato aumenta di 0,2 kW/ora.
-   _**Carico operativo massimo**_
    -   Per 110 V: il carico massimo di funzionamento è 1760 W e 16 A.
    -   Per 230 V: il carico massimo di funzionamento è 3680 W e 16 A.
    -   Se l'interruttore di alimentazione si surriscalda, interromperà automaticamente l'alimentazione come misura di sicurezza. L'indicatore LED lampeggerà rapidamente. Dopo lo spegnimento, l'interruttore di alimentazione riprenderà il normale funzionamento se la temperatura scende al di sotto del punto di soglia.

![](<.gitbook/assets/6 (49).jpeg>)![](<.gitbook/assets/7 (52).png>)

_\\<NOTE>_

-   Il carico operativo massimo di_**Tipo B**_è 110 V, 1650 W e 15 A, che è diverso dal carico operativo massimo per 110 V e 230 V indicato sopra.

**Ripristino delle impostazioni di fabbrica**

-   Il ripristino delle impostazioni di fabbrica dell'interruttore di accensione cancellerà la sua memoria e lo ripristinerà alle impostazioni predefinite di fabbrica.
-   Tieni premuto il pulsante di prova mentre accendi l'interruttore di alimentazione, quindi rilascia il pulsante quando il LED si accende per ripristinare le impostazioni di fabbrica.

2
