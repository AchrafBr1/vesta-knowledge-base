# VESTA220

**Controllo porta garage Z-Wave (GDC-3)**

**introduzione**

GDC-3 è un controllo per porta del garage Z-Wave che si collega all'apriporta del garage. Dopo aver aderito a una rete Z-Wave, GDC-3 può ricevere comandi attraverso la rete Z-Wave per attivare l'apriporta del garage collegato, fornendo un comodo funzionamento per l'apertura o la chiusura a distanza della porta del garage.

GDC-3 include anche un sensore di inclinazione della porta del garage (Tilt-GDC3) che può essere installato su una porta del garage inclinata o un contatto della porta del garage (DC-16SL-GDC3 / DC-32-EX-GDC3) che può essere utilizzato su una porta del garage con apertura orizzontale per segnalare lo stato della porta del garage quando la porta del garage è "aperta" o "chiusa".

Prima che la porta del garage attivata inizi a muoversi, i LED di avviso sul GDC-3 lampeggeranno e la sirena incorporata emetterà segnali acustici di allarme.

Z-Wave è un protocollo di comunicazione wireless che utilizza radio RF a bassa potenza. Il controllo della porta del garage Z-Wave consente l'accesso alla classe "S2 Unauthenticated" e supporta l'inclusione Z-Wave SmartStart così come l'inclusione classica.

**Identificazione delle parti**

**GDC-3 (controllo porta del garage)**

![](<.gitbook/assets/0 (90).jpeg>)

1. **Indicatore LED verde**
   * **SU**: Collegato all'alimentazione.
   * \*\*Lampeggia con LED rosso per 5 secondi:\*\*Prima che la porta del garage si muova.
2. **Indicatore LED rosso**
   * \*\*Lampeggia una volta al secondo:\*\*In modalità apprendimento per Tilt-GDC3.
   * \*\*Lampeggia una volta ogni 5 secondi:\*\*Batteria Tilt-GDC3 scarica
   * \*\*Lampeggia con LED verde per 5 secondi:\*\*Prima che la porta del garage si muova.
3. **Pulsante funzione**
   * Premere il pulsante 3 volte entro 1 secondo per includere o escludere il dispositivo nella/dalla rete Z-Wave.
   * Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.
   * Premere una volta il pulsante per aprire/chiudere la porta del garage.
4. **Terminali di connessione**

Collegare ai terminali della console a parete con pulsante sull'apriporta del garage.

1. **Jack DC (con funzione di blocco)**

Collegare un adattatore di alimentazione DC 9V1A e ruotarlo di 90 gradi in senso orario fino alla posizione di blocco. Per rimuovere l'adattatore, ruotarlo di 90 gradi in senso antiorario nella posizione aperta originale e rimuoverlo.

1. **Pulsante Impara**

Utilizzare uno strumento appuntito per premere una volta il pulsante di apprendimento per accedere alla modalità di apprendimento per Tilt-GDC3.

1. **Fori di montaggio**
2. **Staffa di fissaggio**

1

**Tilt-GDC3 (sensore di inclinazione della porta del garage)**

![](<.gitbook/assets/1 (77).jpeg>)

**1. Pulsante test/indicatore LED**

**Pulsante di prova:**

* Premere il pulsante Test per trasmettere un codice di apprendimento al GDC-3.
* Premere il pulsante Test per segnalare la posizione della porta del garage ed entrare in modalità test per 3 minuti. In modalità test, il LED si accende ogni volta che viene attivato il sensore di inclinazione della porta del garage.

**Indicatore LED:**

*
  * Il LED lampeggerà per 3 volte durante la trasmissione di un codice di apprendimento.
  * Il LED si accenderà ogni volta che il dispositivo viene attivato in modalità test.
  * Il LED si accenderà ogni volta che viene attivato l'interruttore antimanomissione.
  * (Sportello aperto) In caso di guasto del dispositivo o in modalità test, il LED lampeggerà per 6 volte.
  * (Porta chiusa) In caso di guasto del dispositivo o in modalità test, il LED lampeggerà per 6 volte. Dopo 10 secondi, il LED lampeggerà per 3 volte.
  * Quando la batteria è scarica, il sensore di inclinazione della porta del garage interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.

1. **Fori di montaggio**

Utilizzato per fissare e avvitare il sensore di inclinazione della porta del garage direttamente sulla parte superiore della porta del garage.

**3. Interruttore antimanomissione**

Quando il sensore di inclinazione della porta del garage è montato, l'interruttore antimanomissione sarà completamente premuto contro la porta del garage.

Quando il coperchio del dispositivo viene aperto o quando viene rimosso dalla superficie di montaggio, l'interruttore antimanomissione verrà attivato.

Il LED lampeggerà per 6 volte e invierà un segnale di apertura antimanomissione per notificare agli utenti questa condizione.

1. **Isolante della batteria**
2. **Compartimento della batteria**

Il sensore di inclinazione della porta del garage è alimentato da una batteria al litio CR123 da 3 V. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per avvisare l'utente di questa condizione.

**DC-16SL-GDC3 (contatto porta del garage)**

![](<.gitbook/assets/2 (71).jpeg>)

**1. Indicatore LED**

Nella modalità di funzionamento normale, l'indicatore LED rimane spento tranne nelle seguenti situazioni:

\-Quando l'interruttore antimanomissione del contatto porta viene attivato.

2

*
  * Ogni volta che il contatto della porta viene attivato a causa dell'attivazione del tamper o di una condizione di batteria scarica.
  * Ogni volta che il contatto della porta viene attivato e trasmette il segnale in modalità test.

1. **Pulsante di prova**
   * Premere il pulsante Test per trasmettere un codice di apprendimento al GDC-3.
   * Premere il pulsante Test per segnalare la posizione della porta del garage ed entrare in modalità test per 3 minuti. In modalità test, il LED si accende ogni volta che viene attivato il contatto della porta.
2. **Compartimento della batteria**

Il contatto della porta è alimentato da uno**Batteria al litio CR2 da 3 V**. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per avvisare l'utente di questa condizione.

1. **Foro per vite di fissaggio del coperchio**
2. **Eliminazioni**
3. **Interruttore antimanomissione**

È progettato per proteggere contro la rimozione non autorizzata dalla posizione di montaggio, l'apertura del coperchio o un'installazione instabile. Quando viene attivata la manomissione, un segnale di manomissione verrà segnalato al pannello di controllo tramite GDC-3 e anche il LED si accenderà.

1. **Foro isolante della batteria**
2. **Segni di costole**
3. **Magnete**

Montare il magnete sul lato del contatto porta dove sono presenti 2 segni di nervatura per indicare la posizione dell'interruttore magnetico interno. Il contatto porta deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.

1. **Foro per vite magnetica**
2. **Distanziatore magnetico**

**DC-32-EX-GDC3 (contatto porta garage esterna)**

![](<.gitbook/assets/3 (66).jpeg>)

1. **Cover protettiva**
2. **Coperchio della batteria**

3

\*\*3.\*\***Interruttore antimanomissione anteriore**

Quando il coperchio della batteria viene rimosso, l'interruttore antimanomissione anteriore verrà attivato.

1. **Indicatore LED**
2. **Pulsante Impara/Test**

Utilizzare uno strumento appuntito per premere il pulsante per trasmettere il codice di apprendimento o accedere alla modalità test per 3 minuti.

Premere il pulsante Test per segnalare la posizione della porta del garage ed entrare in modalità test per 3 minuti. In modalità test, il LED si accende ogni volta che viene attivato il contatto della porta.

\*\*6.\*\***Compartimento della batteria**

Il contatto porta utilizza due batterie al litio AA L91 come fonte di alimentazione.

\*\*7.\*\***Interruttore antimanomissione posteriore**

Ogni volta che il contatto della porta viene rimosso dalla superficie di montaggio, verrà attivato l'interruttore antimanomissione posteriore.

1. **Ganci**
2. **Fori di chiusura**
3. **Eliminazioni**
4. **Zona separatista**

**Iniziare**

![](<.gitbook/assets/4 (75).png>)

* _**Impara Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 in GDC-3**_

Accendere tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 e collegare GDC-3 all'alimentazione.

* Utilizzare uno strumento appuntito per premere una volta il pulsante di apprendimento del GDC-3 per accedere alla modalità di apprendimento. GDC-3 emetterà un segnale acustico e il LED rosso inizierà a lampeggiare.
* Premere il pulsante Test di Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 per inviare un codice di apprendimento a GDC3, il LED lampeggerà per 3 volte.
* Se l'apprendimento ha esito positivo, GDC-3 emetterà 2 segnali acustici per indicarlo. Se Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 è già stato aggiunto a GDC-3, GDC-3 emetterà un suono Di-Do per avvisare l'utente.
* Utilizzare uno strumento appuntito per premere ancora una volta il pulsante di apprendimento del GDC-3 per tornare alla modalità normale, il LED rosso si spegnerà. In alternativa, GDC-3 uscirà automaticamente dalla modalità di apprendimento con 5 segnali acustici dopo 1 minuto di inattività.

![](<.gitbook/assets/5 (76).png>)

*
  * _NOTA >_
    * Il controllo della porta del garage supporta solo un sensore. Se un secondo sensore (sensore di inclinazione o contatto porta) viene acquisito nel GDC-3, il vecchio sensore verrà sostituito dal sensore appena appreso.
* _**Aggiunta di GDC-3 al sistema (inclusione)**_

![](<.gitbook/assets/6 (55).png>)

Il dispositivo supporta sia il processo di inclusione classico che il processo di inclusione SmartStart.

**Inclusione classica**

* Collegare GDC-3 all'alimentazione
* Inserisci il gateway Z-wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale utente del gateway Z-wave o del pannello di controllo).
* Entro 1 secondo, premere il pulsante funzione 3 volte.
* Fare riferimento al manuale utente del gateway Z-wave o del pannello di controllo per completare il processo di aggiunta.
* Se il controllo della porta del garage è già stato aggiunto/incluso in un altro gateway/pannello di controllo Z-wave, o se non è possibile aggiungerlo all'attuale gateway/pannello di controllo Z-wave, provare prima a rimuoverlo (vedere\_**Rimozione del dispositivo**\_).

**Inclusione SmartStart**

I prodotti abilitati SmartStart possono essere aggiunti a una rete Z-Wave eseguendo la scansione del codice QR Z-Wave presente sul prodotto con un controller che fornisce l'inclusione di SmartStart. Non sono necessarie ulteriori azioni e il prodotto SmartStart verrà aggiunto automaticamente entro 10 minuti dall'accensione nelle vicinanze della rete. Z-Wave SmartStart utilizza le informazioni DSK del dispositivo per migliorare e semplificare il processo di inclusione.**DSK**sta per Device Specific Key utilizzata per l'autenticazione e la comunicazione crittografata. Le informazioni DSK vengono memorizzate nel formato codice QR stampato su un'etichetta e incollata sulla parte anteriore del dispositivo, come nell'esempio mostrato a destra.

![](<.gitbook/assets/7 (45).jpeg>)

* Scansiona il codice QR sul retro di GDC-3 per ottenere il**DSK**informazioni e trasferirle al gateway Z-Wave.
* Collega GDC-3 all'alimentazione, una richiesta di inclusione SmartStart verrà inviata automaticamente al gateway.
* Il gateway includerà automaticamente il dispositivo al riconoscimento del file

4

dispositivo abbinando la richiesta di inclusione al DSK ottenuto.

![](<.gitbook/assets/8 (51).png>)

*
  * _NOTA>_
    * Il DSK del dispositivo viene utilizzato solo durante l'inclusione.
    * Il DSK può essere letto senza che il GDC-3 sia acceso, quindi è possibile preparare il gateway per includere il dispositivo prima di installare e accendere il controllo della porta del garage.
    * Se GDC-3 è già stato**incluso**(appreso) in un altro gateway/pannello di controllo Z-Wave, escluderlo prima (vedi\_**Esclusione**\_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave. GDC-3 non invierà una richiesta di inclusione SmartStart se è già in un gateway/pannello di controllo Z-Wave.
* _**Rimozione di GDC-3 dal sistema (esclusione)**_

![](<.gitbook/assets/9 (46).png>)

Il controllo della porta del garage deve essere rimosso dalla rete Z-wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

*
  *
    *
      * Inserisci il gateway Z-wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale utente del gateway Z-wave o del pannello di controllo).
      * Entro 1 secondo, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero, non incluso in nessuna rete Z-wave).

*
  *
    *
      * Tieni premuto il pulsante funzione del dispositivo per 10 secondi per eseguire il ripristino delle impostazioni di fabbrica.
  * _NOTA>_
    * Prima di rimuovere o ripristinare le impostazioni di fabbrica del GDC-3, assicurati che le informazioni DSK del dispositivo siano state rimosse o non esistano nel gateway. Se rimuovi o ripristini le impostazioni di fabbrica del dispositivo, ma le relative informazioni DSK sono ancora presenti nel gateway, il gateway includerà nuovamente automaticamente il dispositivo.
* _**Prova di portata**_

![](<.gitbook/assets/10 (48).png>) ![](<.gitbook/assets/11 (40).png>)

Per verificare se il Garage Door Control è in grado di comunicare con il gateway Z-Wave o il pannello di controllo:

* Mettere il gateway/pannello in modalità test di portata (Walk Test).
* Premere il pulsante funzione sul dispositivo.
* Il gateway/pannello di controllo dovrebbe visualizzare se il dispositivo si trova nel raggio d'azione (fare riferimento al manuale utente del gateway/pannello di controllo).

**Installazione**

![](<.gitbook/assets/12 (25).jpeg>)

**Montaggio del sensore di inclinazione della porta del garage (Tilt-GDC3)**

* Il sensore di inclinazione della porta del garage è progettato per essere montato su porte del garage basculanti o basculanti, non per essere utilizzato su porte del garage avvolgibili. Viene utilizzato per segnalare lo stato di quando la porta del garage è “aperta”, “chiusa” o in movimento.
* Il dispositivo deve essere montato verticalmente rispetto al suolo (non deve essere inclinato più di +-5 gradi una volta montato).
* Montare il dispositivo su una superficie asciutta e pulita. Assicurarsi che il dispositivo sia montato con l'indicatore LED in alto.
* Il sensore di inclinazione della porta del garage deve essere montato sul pannello superiore della porta del garage, come mostrato di seguito.

![](<.gitbook/assets/13 (31).jpeg>)

* Esistono due modi per montare il sensore di inclinazione della porta del garage. Montaggio a vite:
  1. Trova una posizione adatta per installare il sensore di inclinazione della porta del garage. La superficie di montaggio deve essere pulita e asciutta. Se necessario, pulire accuratamente la superficie di montaggio.
  2. Utilizzare i due fori di montaggio come modello per contrassegnare e praticare i fori di montaggio.
  3. Utilizzare i tasselli forniti per l'installazione su intonaco/mattone. Avvitare il sensore di inclinazione della porta del garage nei tasselli forniti. Assicurarsi che i tasselli siano a filo con la superficie di montaggio.

![](<.gitbook/assets/14 (29).png>)

5

* ![](<.gitbook/assets/15 (29).png>)_NOTA>_
  * Utilizzare questo tipo di metodo di montaggio solo quando le porte del garage sono più spesse della lunghezza delle viti.

![](<.gitbook/assets/16 (31).png>)

Montaggio adesivo:

1. Trova una posizione adatta per installare il sensore di inclinazione della porta del garage. La superficie di montaggio deve essere pulita e asciutta. Se necessario, pulire accuratamente la superficie di montaggio.
2. Rimuovere un lato dei rivestimenti sul cuscinetto adesivo biadesivo. Applicalo sul retro del sensore di inclinazione della porta del garage e premi con decisione per 30 secondi per garantire un buon contatto.
3. Rimuovere la pellicola rimanente sul cuscinetto adesivo e premere con decisione il sensore di inclinazione della porta del garage nella posizione desiderata per altri 30 secondi. Si prega di evitare di applicare il cuscinetto adesivo su superfici irregolari o di riapplicarlo.

**Montaggio del contatto della porta del garage (DC-16SL-GDC3)**

* Il contatto porta è progettato per essere utilizzato sulla porta del garage con apertura orizzontale per segnalare lo stato della porta del garage quando la porta del garage è "aperta" o "chiusa".
* Installare il contatto porta sull'oggetto più fisso (come il telaio della porta) e montare il magnete sull'oggetto più mobile (come la porta del garage).

![](<.gitbook/assets/17 (20).jpeg>)

* Montare il magnete utilizzando le viti in dotazione. Allineare il magnete in base al segno della nervatura sul contatto della porta.
* Ove necessario, utilizzare il distanziatore magnetico per allineare meglio il magnete ai segni delle nervature.
  *
    * _NOTA >_
      * Il magnete non deve trovarsi a più di 15 mm dal contatto della porta quando la porta è chiusa.
      * I due cappucci bianchi forniti possono essere inseriti nei fori delle viti del magnete per integrità estetica.
* Esistono due modi per montare il contatto porta: montaggio autoadesivo o montaggio con viti. Montaggio autoadesivo:
  1. La superficie di montaggio deve essere pulita, asciutta e liscia. Se necessario, pulire la superficie di montaggio con uno sgrassatore adatto.
  2. Rimuovere un lato dei rivestimenti sul cuscinetto adesivo biadesivo. Applicare il cuscinetto adesivo sul retro del dispositivo e premere con decisione per 30 secondi per garantire un buon contatto.
  3. Rimuovere la pellicola rimanente sul cuscinetto adesivo e premere con decisione il contatto della porta nella posizione desiderata per 30 secondi.

_\\_

*
  *
    *
      * Non utilizzare il metodo di installazione del tampone adesivo su una superficie con vernice scrostata o screpolata o su una superficie ruvida.
      * Si prega di non riapplicare il tampone adesivo 3M. Non può essere riutilizzato

![](<.gitbook/assets/18 (30).png>) ![](<.gitbook/assets/19 (31).png>) ![](<.gitbook/assets/20 (22).png>)

Montaggio a vite:

La base ha due fori, dove la plastica è più sottile, per il montaggio.

Per montare il contatto porta:

1. Rimuovere il coperchio svitando la vite di fissaggio del coperchio con un cacciavite a croce.
2. Sfonda i fori sulla base.
3. Utilizzare i fori come modello e praticare due fori.
4. Inserire i tasselli se si fissa su intonaco o mattoni.
5. Avvitare la base nella presa a muro con un cacciavite Phillips.
6. Attaccare il coperchio alla base e serrare la vite di fissaggio del coperchio.

**Montaggio del contatto della porta del garage esterna (DC-32-EX-GDC3)**

* Il contatto impermeabile per porta è progettato per essere utilizzato sulla porta del garage con apertura orizzontale per segnalare lo stato del 6

porta del garage quando la porta del garage è “aperta” o “chiusa”.

* Si consiglia di posizionare il contatto porta sul telaio fisso della porta del garage e il magnete sulla porta del garage.
* I segni delle nervature sul magnete e sul contatto della porta devono essere allineati (**FICO. 1**).
* Il magnete non deve trovarsi a più di 3 cm dal lato contrassegnato del contatto porta quando la porta è chiusa.
* Il contatto della porta è dotato di un interruttore antimanomissione sul coperchio posteriore. Assicurarsi che il dispositivo sia posizionato all'interno della staffa in modo che la molla dell'interruttore antimanomissione sia premuta contro l'area di distacco collegata allentatamente alla staffa.

Se il contatto della porta viene rimosso con la forza dalla parete, l'area di distacco si staccherà dalla staffa e rimarrà attaccata alla superficie di montaggio, attivando l'interruttore antimanomissione.

**FICO. 1**

* Per montare il contatto porta:
  *
    1. La staffa di montaggio fornita ha 3 fori in cui la plastica è più sottile e può essere rotta per il montaggio. (**FICO. 2**)
    2. Utilizzare la staffa di montaggio come sagoma per praticare i fori sulla parete per i tasselli. (**FICO. 3**)
    3. Inserire i tasselli e fissare la staffa di montaggio alla parete con le viti.
    4. Montare il contatto per porta con i ganci sul coperchio posteriore del contatto per porta agganciati ai fori di chiusura della staffa di montaggio, quindi spingere verso il basso per bloccare il gancio. (**FICO. 4**)
  * _NOTA >_
    *
      * Assicurarsi che l'interruttore antimanomissione posteriore del contatto porta sia premuto contro l'area di distacco sulla staffa di montaggio.

**FICO. 2**

 Fissare le viti di fissaggio inferiori.

5\)Riposizionare il coperchio protettivo.

 Esistono due modi per montare il magnete: montaggio adesivo e montaggio con viti.

 Montaggio a vite:

1. Avvitare la staffa di montaggio alla porta con le due viti in dotazione.
2. Fissare il magnete alla staffa di montaggio.

_\\_

* È possibile utilizzare il distanziale magnetico fornito, facendo in modo che il lato con le parole nere tocchi la staffa di montaggio,

tra il magnete e la porta per facilitare l'allineamento e l'installazione.

7

* Montaggio adesivo:
  1. In alternativa, utilizzare il nastro biadesivo fornito per fissare direttamente il magnete alla porta.

_\\_

*
  *
    * Assicurarsi che la superficie di montaggio sia pulita, asciutta e liscia prima di fissare il magnete fissato con il nastro biadesivo alla porta e che il magnete sia premuto saldamente contro la porta per 30 secondi.
  * L'installazione è ora completata.

**FICO. 3**

**FICO. 4**

**Montaggio del controllo della porta del garage (GDC-3)**

* Il controllo della porta del garage viene solitamente montato sul soffitto vicino all'apriporta del garage e alla presa di corrente.

8

_**AVVERTIMENTO :**_

*
  1. Prima dell'installazione, assicurarsi di scollegare l'alimentazione dall'apriporta del garage.
     1. Il controllo della porta del garage GDC-3 deve essere installato in vista della porta del garage, dove sia gli allarmi visivi che quelli acustici possono essere chiaramente visti e uditi.

1. Utilizzare la staffa di montaggio come modello, contrassegnare i due fori di montaggio, praticare i fori nella posizione di montaggio e inserire i tasselli se necessario.
2. Avvitare la staffa di montaggio nella posizione contrassegnata con i due ganci rivolti verso l'esterno.
3. Agganciare il comando della porta del garage alla staffa di montaggio a parete (con i fori di montaggio del comando della porta del garage).
4. Spingere il controllo della porta del garage (nella direzione indicata nella figura seguente) per bloccarlo nella staffa di montaggio.
5. Collegare i terminali GDC-3 ai terminali della console a parete con pulsanti sull'apriporta del garage. Entrambi i fili possono essere collegati a entrambi i terminali. (I terminali della console a parete possono essere denominati “PWC”, “WC”, “PB”, “PUSHBUTTON” o “RED” e “WHITE”. I nomi e le posizioni dei terminali variano in base al modello.)
6. Collegare l'adattatore di alimentazione in uscita CC 9 V 1 A e collegarlo all'alimentazione.
7. Ripristina l'alimentazione all'apriporta del garage.

9

**Operazione**

* _**Funzionamento della porta del garage**_
  * Dopo che GDC-3 è stato incluso nella rete Z-Wave, il gateway Z-Wave può aprire o chiudere da remoto la porta del garage con Z-Wave

comando\[COMANDO\_CLASSE\_BARRIERA\_OPERATORE] e\[BARRIERA\_OPERATORE\_SET], utilizzando i parametri seguenti:

*
  *
    * Aperto: valore target = 0xFF
    * Chiudi: valore target = 0x00
  * Gli utenti possono anche premere una volta il pulsante funzione per aprire/chiudere la porta del garage.
  * Prima che la porta del garage attivata inizi a muoversi, gli indicatori LED di avviso (verde e rosso) lampeggeranno e verranno emessi segnali acustici di allarme per 5 secondi. Quando la porta del garage inizia a muoversi, la posizione della porta del garage verrà segnalata al gateway Z-Wave.

\[COMANDO\_CLASSE\_BARRIERA\_OPERATORE]\[BARRIERA\_OPERATORE\_RAPPORTO] stato:

|  | BARRIERA\_OPERATORE\_CHIUSO   | 0x00 |
| - | ----------------------------- | ---- |
|  | BARRIERA\_OPERATORE\_CHIUSURA | 0xFC |
|  | BARRIERA\_OPERATORE\_FERMATO  | 0xFD |
|  | BARRIERA\_OPERATORE\_APERTURA | 0xFE |
|  | BARRIERA\_OPERATORE\_APRIRE   | 0xFF |

*
  * Una volta che GDC-3 avvia il movimento della porta del garage, dovrai attendere 35 secondi affinché la porta del garage si apra o chiuda completamente prima di poter inviare un secondo comando di apertura/chiusura o premere il pulsante funzione per aprire/chiudere. Se viene inviato un secondo comando o viene premuto il pulsante funzione entro 35 secondi, GDC-3 invierà un segnale di occupato al gateway Z-Wave.

\[COMANDO\_CLASSE\_APPLICAZIONE\_STATO]\[APPLICAZIONE\_OCCUPATO]

*
  *
    *
      * Stato: 0x00
      * Tempo di attesa: 0x00
    * Quando la porta del garage è in stato aperto, GDC-3 ignorerà qualsiasi comando di apertura dal gateway Z-Wave. Quando la porta del garage è chiusa, GDC-3 ignorerà qualsiasi comando di chiusura proveniente dal gateway Z-Wave.
* _**Volume del suono dell'allarme**_
  *
    * Prima che la porta del garage attivata inizi a muoversi, gli indicatori LED di avvertenza lampeggeranno e verranno emessi segnali acustici di allarme per 5 secondi. Gli utenti possono regolare il volume del suono dell'allarme inviando il comando dal gateway Z-Wave con il comando Configuration CC, utilizzando i parametri seguenti:

10

* S: Taglia
* D: Predefinito

| NO. | Nome                        | S | minimo | Massimo | D | Descrizione   |
| --- | --------------------------- | - | ------ | ------- | - | ------------- |
|     |                             |   |        |         |   |               |
| 1   | Livello sonoro dell'allarme | 1 | 0      | 2       | 2 | 0: silenzioso |
|     |                             |   |        |         |   | 1:piccolo     |
|     |                             |   |        |         |   | 2: forte      |
|     |                             |   |        |         |   |               |

* _**Caratteristiche del sensore di inclinazione della porta del garage (Tilt-GDC3)/contatto della porta (DC-16SL-GDC3)/contatto della porta esterna (DC-32-EX-GDC3)**_
  * Rilevamento della posizione della porta del garage

Ogni volta che cambia la posizione della porta del garage, Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 segnalerà la posizione della porta a GDC-3 e GDC-3 segnalerà al gateway Z-Wave con Z -Comando d'onda

\[COMANDO\_CLASSE\_BARRIERA\_OPERATORE]\[BARRIERA\_OPERATORE\_RAPPORTO].

|  | BARRIERA\_OPERATORE\_CHIUSO   | 0x00                      |
| - | ----------------------------- | ------------------------- |
|  | BARRIERA\_OPERATORE\_CHIUSURA | 0xFC (solo per Tilt-GDC3) |
|  | BARRIERA\_OPERATORE\_FERMATO  | 0xFD (solo per Tilt-GDC3) |
|  | BARRIERA\_OPERATORE\_APERTURA | 0xFE (solo per Tilt-GDC3) |
|  | BARRIERA\_OPERATORE\_APRIRE   | 0xFF                      |

* Protezione antisabotaggio

Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 è protetto da un interruttore antimanomissione. Quando il dispositivo viene rimosso dalla superficie di montaggio o quando il coperchio del dispositivo viene aperto, l'interruttore antimanomissione verrà attivato. Il dispositivo invierà quindi un segnale di apertura antimanomissione a GDC-3 e GDC-3 segnalerà al gateway Z-Wave con il comando Z-Wave\[COMANDO\_CLASSE\_NOTIFICA]\[NOTIFICA\_RAPPORTO].

*
  * Aperto: 00 00 00 FF 07 03 00 00
  * Chiuso: 00 00 00 FF 07 00 01 03
* Segnale di vigilanza

Il Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 trasmetterà il segnale di supervisione insieme alla posizione della porta del garage al GDC-3 ogni 15-20 minuti. GDC-3 riporterà al gateway Z-Wave utilizzando\[BARRIERA\_OPERATORE\_RAPPORTO].

Se il gateway Z-Wave non riesce a ricevere alcun segnale di supervisione dal Tilt-GDC3 / DC-16SL-GDC / DC-32-EX-GDC per un periodo di tempo preimpostato, verrà visualizzato un messaggio di errore "Out-Of-Order". generato.

*
  * Errore di supervisione: 00 00 00 FF 06 49 00
  * Ripristino: 00 00 00 FF 06 00 00 (Sia lo stato della batteria che il segnale di supervisione devono essere riportati alla normalità)
* Batteria scarica

Il Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 è dotato della funzione di rilevamento batteria scarica. Quando la tensione della batteria è bassa, il sensore di inclinazione/contatto porta trasmetterà un segnale di batteria scarica a GDC-3 e GDC-3 segnalerà al gateway Z-Wave con il comando Z-Wave\[COMANDO\_CLASSE\_NOTIFICA]\[NOTIFICA\_RAPPORTO].

*
  * Batteria scarica: 00 00 00 FF 06 4A 00
  * Ripristino: 00 00 00 FF 06 00 00 (Sia lo stato della batteria che il segnale di supervisione devono essere riportati alla normalità)

**Informazioni sull'onda Z**

\*\*Tipo di dispositivo:\*\*GENERICO\_TIPO\_ISCRIZIONE\_CONTROLLO

\*\*Tipo specifico:\*\*SPECIFICA\_TIPO\_SICURO\_BARRIERA\_AGGIUNGI SU

\*\*Tipo di icona:\*\*ICONA\_TIPO\_GENERICO\_BARRIERA

\*\*Tipo di ruolo:\*\*Sempre attivo come schiavo (AOS)

\*\*Sicurezza:\*\*Cattivo\_NON AUTENTICATO

\*\*Identificativo del produttore:\*\*0x018E

\*\*ID tipo prodotto:\*\*0x0004

\*\*Codice prodotto:\*\*0x0127

* _**Classe di comando supportata**_

11

| **Classe di comando**                     | **Versione** | **Classe di sicurezza richiesta**      |
| ----------------------------------------- | ------------ | -------------------------------------- |
|                                           |              |                                        |
| Associazione                              | 2            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Informazioni sul gruppo dell'associazione | 3            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Di base                                   | 2            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Reimpostazione del dispositivo localmente | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Metadati di aggiornamento del firmware    | 5            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Specifico del produttore                  | 2            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Multicanale                               | 4            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Associazione multicanale                  | 3            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Livello di potenza                        | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Configurazione                            | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Notifica                                  | 8            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Operatore di barriera                     | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Stato dell'applicazione                   | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Versione                                  | 3            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Servizio di trasporto                     | 2            | Nessuno                                |
|                                           |              |                                        |
| Informazioni su Z-Wave Plus               | 2            | Nessuno                                |
|                                           |              |                                        |
| Sicurezza 2                               | 1            | Nessuno                                |
|                                           |              |                                        |
| Supervisione                              | 1            | Nessuno                                |
|                                           |              |                                        |

* _**Gruppi associativi**_

| **ID** | **Nome**           | **Massimo** | **Descrizione**                                                                           |
| ------ | ------------------ | ----------- | ----------------------------------------------------------------------------------------- |
|        |                    | **Nodo**    |                                                                                           |
|        |                    |             |                                                                                           |
| 1      | Ancora di salvezza | 5           | Supporta le seguenti classi di comandi:                                                   |
|        |                    |             |  Report di notifica: attivato da manomissione, batteria scarica, errore di supervisione. |
|        |                    |             |  Report Operatore Barriera: GDC aperto/chiuso.                                           |
|        |                    |             |  Report Applicazione occupata: attivato dal Set Operatore Barriera entro 35 secondi.     |
|        |                    |             |  Reset del dispositivo localmente: attivato al momento del reset                         |
|        |                    |             |                                                                                           |

12
