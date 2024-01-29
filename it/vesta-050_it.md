# VESTA050

**Allarme di riconoscimento vocale (VRA)**

L'allarme di riconoscimento vocale (VRA) riconosce i comandi vocali o le parole chiave preimpostate e attiva un allarme di aiuto. Oltre all'attivazione vocale, il VRA dispone anche di un grande pulsante che consente agli utenti di chiedere aiuto durante un'emergenza.

* **Identificazione delle parti**

**Vista frontaleVista posterioreVista laterale**

![](<.gitbook/assets/0 (39).jpeg>)

1. **Pulsante Guida (con retroilluminazione blu)**
   1. Premere una volta per inviare un codice di apprendimento o attivare un allarme antipanico
   2. Tenere premuto il pulsante per 8 secondi per inviare un codice di annullamento al pannello di controllo.
   3. La retroilluminazione blu lampeggerà quando il segnale viene trasmesso al pannello di controllo.
2. **Indicatore LED (verde/ambra)**

* LED verde acceso: quando è collegata l'alimentazione esterna.
* LED verde SPENTO: quando l'alimentazione esterna viene rimossa.
* Il LED ambra lampeggia per tre volte: stato di batteria scarica rilevato all'accensione.
* Il LED ambra lampeggia una volta ogni 5 secondi: stato di batteria scarica rilevato durante il funzionamento.
  1. **Microfono per VR (riconoscimento vocale)**
  2. **Compartimento della batteria**
  3. **Interruttori DIP**
  4. **Buco della serratura**
  5. **Jack DC (con funzione di blocco)**

Collegare un adattatore di alimentazione CC 5 V e ruotarlo di 90 gradi in senso orario fino alla posizione di blocco. Per rimuovere l'adattatore, ruotarlo di 90 gradi in senso antiorario nella posizione aperta originale e rimuoverlo.

* **Alimentazione elettrica**
  *
    * VRA può essere alimentato collegandosi a un alimentatore da 5 V CC o a due batterie di tipo C.
    * Quando VRA è collegato all'alimentazione da 5 V CC, il LED verde si accende. Quando l'alimentazione CC viene rimossa, VRA passerà all'utilizzo delle batterie (se le batterie sono già installate e non esaurite) e continuerà a funzionare; il LED verde si spegnerà.
    * Quando alimentato da batterie di tipo C, VRA trasmetterà insieme a qualsiasi stato rilevato di batteria scarica

1

trasmissioni regolari del segnale di stato al pannello di controllo per la visualizzazione di conseguenza.

*
  * Quando si sostituiscono le batterie, rimuovere il coperchio posteriore svitando la vite di fissaggio inferiore e quindi inserendo un cacciavite a testa piatta per sollevare il coperchio posteriore. Rimuovere le vecchie batterie, quindi premere due volte il pulsante Guida per scaricarle completamente prima di inserire nuove batterie.
* **Segnale di supervisione**
  * Dopo l'apprendimento nel pannello di controllo, VRA trasmetterà automaticamente i segnali di supervisione ogni 30-50 minuti.
  * Se la centrale di controllo non ha ricevuto il segnale di supervisione da VRA per un periodo di tempo preimpostato, indicherà che l'allarme di riconoscimento vocale è fuori portata del segnale o è fuori servizio.
* **Sensibilità**
  * La funzione di riconoscimento vocale ha tre livelli di sensibilità: alto, medio, basso. Quando il livello di sensibilità è impostato su alto, VRA rileverà più facilmente la parola chiave/comando e attiverà l'allarme.
  * Utilizzare uno strumento affilato per regolare le posizioni degli interruttori DIP per impostare il livello di sensibilità.

|   |                   |                   |                |                                      |              |   |
| - | ----------------- | ----------------- | -------------- | ------------------------------------ | ------------ | - |
|   |                   |                   |                |                                      |              |   |
|   |                   | **IMMERSIONE**    |                | **Ricerca (livello di sensibilità)** |              |   |
|   |                   |                   |                |                                      |              |   |
|   | **Interruttore1** |                   |                |                                      |              |   |
|   |                   | **Interruttore2** |                |                                      |              |   |
|   |                   |                   |                |                                      |              |   |
|   | SPENTO            |                   | SPENTO         |                                      | Basso        |   |
|   |                   |                   |                |                                      |              |   |
|   | SU                |                   | SPENTO         |                                      | medio        |   |
|   |                   |                   |                |                                      |              |   |
|   | SPENTO            |                   | SU             |                                      | Alto         |   |
|   |                   |                   |                |                                      |              |   |
|   |                   |                   |                |                                      |              |   |
|   |                   |                   | **IMMERSIONE** |                                      | **Funzione** |   |
|   |                   |                   |                |                                      |              |   |
|   | **Interruttore3** |                   |                |                                      | Riservato    |   |
|   |                   | **Interruttore4** |                |                                      |              |   |
|   |                   |                   |                |                                      |              |   |

![](<.gitbook/assets/1 (33).jpeg>) ![](<.gitbook/assets/2 (45).png>)

_\\_

*
  * Dopo aver modificato le impostazioni del Dip Switch, scollegare l'alimentazione (sia l'alimentatore esterno che le batterie devono essere rimosse) e quindi ricollegare l'alimentazione al VRA. VRA lo farà

funziona con il livello di sensibilità appena impostato dopo la riaccensione.

* **Iniziare**
  * Rimuovere il coperchio posteriore svitando la vite di fissaggio inferiore, quindi inserendo un cacciavite a testa piatta per sollevare il coperchio posteriore.
  * In base alle proprie esigenze, impostare l'interruttore di sensibilità come mostrato nella tabella di posizione dei Dip Switch.
    * Accendere l'allarme con riconoscimento vocale collegandolo a un alimentatore da 5 V CC o a due batterie di tipo C.
    * Mettere il Pannello di Controllo in modalità apprendimento
    * Premere il pulsante sull'allarme di riconoscimento vocale per trasmettere un codice di apprendimento.
    * Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
    * Riposizionare la cover posteriore.
* **Prova della camminata**
  *
    * Dopo aver appreso con successo il VRA, posizionare il pannello di controllo in modalità test di copertura, quindi premere il pulsante sul VRA per confermare che questa posizione si trova all'interno del raggio del segnale del pannello di controllo. Fare riferimento al manuale del pannello di controllo per completare il test di copertura.
* **Operazione**
  *
    * Dopo aver appreso con successo il VRA, premendo una volta il pulsante si attiverà un allarme di aiuto. Quando si preme il pulsante, VRA emetterà un segnale acustico.
    * L'Utente può anche pronunciare lo specifico comando vocale per attivare un Allarme di Aiuto. Quando le parole trigger vengono riconosciute, VRA emetterà un lungo segnale acustico.
    * Le parole di attivazione potrebbero essere "SARA Alarm (tedesco)" o "Aiuto (inglese)", a seconda della versione del firmware. "SARA Alarm (tedesco)" deve essere pronunciato due volte entro 5 secondi per attivare l'allarme, mentre

2

È necessario pronunciare "Aiutami (inglese)" solo una volta per attivare l'allarme.

* Premendo e tenendo premuto il pulsante per 8 secondi o più si invierà un codice di annullamento al pannello di controllo per interrompere l'allarme.

**Modi per cercare aiuto**

![](<.gitbook/assets/3 (45).png>)

O

\*\*Pronuncia la parola chiave trigger.\*\***Premi il pulsante Aiuto.**

![](<.gitbook/assets/4 (29).jpeg>)

_\\_

*
  * Per garantire la precisione del riconoscimento vocale, evitare di installare VRA in una stanza grande o rumorosa.
  * L'ambiente ideale per il riconoscimento vocale è il silenzio o il silenzio parziale. Se si pronuncia il comando vocale con voce normale, parlare entro 2 metri dal VRA per garantire l'attivazione dell'allarme.
  * La funzione di riconoscimento vocale ha tre livelli di sensibilità. Puoi provare con loro e selezionare il livello che meglio si adatta alla tua posizione di montaggio.
* **Installazione**

Dopo aver eseguito il Walk Test per confermare che il VRA si trova nel raggio del segnale del pannello di controllo e sei sicuro che il livello di sensibilità selezionato funzioni nella posizione scelta, puoi procedere con l'installazione. Esistono due modi per installare VRA: montaggio a parete e distribuzione su superficie.

* **Montaggio a parete**

Assicurarsi che il VRA sia montato approssimativamente all'altezza del torace (circa 130 cm-150 cm dal suolo), dove il pulsante sia facilmente accessibile e azionabile.

*
  1. Identificare la serratura sul retro di VRA, praticare un foro sulla parete e inserire il tassello fornito (Figura 1). Montare la vite di fissaggio e lasciare la parte non filettata per appendere il VRA, come mostrato in Figura 2.

Figura 1 Figura 2

![](<.gitbook/assets/5 (19).jpeg>) ![](<.gitbook/assets/6 (26).jpeg>)

3

1. Montare la fessura del buco della serratura del VRA sulla testa della vite. Spingere delicatamente e con decisione il VRA verso il basso, come mostrato di seguito. (Figura 5,6)

Figura 5 Figura 6

![](<.gitbook/assets/7 (23).jpeg>) ![](<.gitbook/assets/8 (16).jpeg>)

* **Posizionamento in superficie**

VRA è dotato di un cuscinetto antiscivolo sul retro. Il dispositivo può anche essere utilizzato su una superficie piana senza essere installato in una posizione fissa.

![](<.gitbook/assets/9 (23).png>)

4
