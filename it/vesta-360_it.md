# VESTA 360

**Contatto porta cablato/Sensore d'urto (DCSV-29-BUS)**

DCSV-29-BUS è un contatto porta/sensore di urto cablato in grado di inviare segnali cablati tramite BUS al pannello di controllo al rilevamento dell'apertura di porte/finestre o del rilevamento di rottura e urto del vetro della finestra.

Il design del contatto porta cablato/sensore d'urto è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

**Identificazione delle parti**

![](<.gitbook/assets/0 (3).png>)

1. **Indicatore LED/Pulsante Test**

\-Premere il pulsante una volta per accedere alla modalità test per 3 minuti.

1. **Vite di fissaggio del coperchio**
2. **Interruttore a ponticello della resistenza terminale**

Quando il contatto porta/sensore di scossa è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello della resistenza terminale del contatto porta/sensore di scossa e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/1 (2).jpeg>) ![](<.gitbook/assets/2 (2).png>)

**Ponticello acceso**

![](<.gitbook/assets/3 (2).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “parcheggiato” su un pin.

*
  * Se il ponticello è su ON, la capacità di comunicazione è migliorata.
  * Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.

1. **Capolinea autobus**
2. **Interruttore antimanomissione**
   * Fornisce protezione antimanomissione contro l'apertura e/o la rimozione non autorizzata del dispositivo dalla superficie di montaggio.
3. **Interruttore a ponticello con interruttore reed**

![](<.gitbook/assets/4 (3).jpeg>) ![](<.gitbook/assets/5 (5).png>)

**Ponticello acceso**

![](<.gitbook/assets/6 (3).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “parcheggiato” su un pin.

*
  * Ponticello ON: l'interruttore Reed è attivo**abilitato**. Il dispositivo funziona come contatto porta e sensore d'urto (impostazione di fabbrica).
  * Jumper OFF: l'interruttore Reed è attivo**Disabilitato**e il dispositivo funziona solo come sensore d'urto.

1. **Fori di montaggio**
2. **Fori di cablaggio**
3. **Magnete**
4. **Foro per vite magnetica**
5. **Distanziatore magnetico**

1

**Caratteristiche**

![](<.gitbook/assets/7 (2).jpeg>)

* _**Indicatore LED**_
  * Nella modalità di funzionamento normale, il LED non si accende quando il dispositivo è attivato.
  * Quando l'interruttore antimanomissione viene attivato, il LED lampeggia una volta. Quando la condizione di manomissione continua, il LED lampeggerà una volta ogni volta che il dispositivo viene attivato.
  * In modalità Test, il LED lampeggerà una volta ogni volta che il dispositivo viene attivato.
  * Il LED non lampeggerà se la manomissione del dispositivo è normale e il dispositivo non è in modalità test.
* _**Rilevamento apertura porta e rilevamento urti**_

![](<.gitbook/assets/8 (1) (1).jpeg>)

Il dispositivo viene attivato dall'apertura di una porta/finestra o da un rilevamento di urto che supera la soglia di rilevamento.

![](<.gitbook/assets/9 (1).jpeg>)

* _**Materiali della superficie di montaggio**_

Il dispositivo supporta il rilevamento degli urti su vari materiali tra cui vetro, legno, metallo e cemento. Dopo l'installazione è possibile selezionare il materiale della superficie di montaggio sul pannello di controllo. L'impostazione predefinita è impostata come**Legna**.

![](<.gitbook/assets/10 (6).png>)

* _**Sensibilità**_
  * La sensibilità richiesta per attivare il contatto porta cablato/sensore d'urto è determinata dal pannello di controllo.
  * Sono selezionabili tre livelli di sensibilità:**Basso**,**medio**, E**Alto**. L'impostazione predefinita è impostata come**medio**.
* _**Alimentazione elettrica**_
  * Quando DCSV-29-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.
* _**Protezione antisabotaggio**_
  * Il contatto porta/sensore d'urto cablato è protetto da un interruttore antimanomissione che viene premuto contro la superficie di montaggio quando il contatto porta/sensore d'urto è montato in posizione. Ogni volta che il contatto porta cablato/sensore d'urto viene rimosso dalla superficie di montaggio o il suo coperchio viene aperto, l'interruttore antimanomissione verrà attivato e il dispositivo invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione.
  * Il segnale di apertura antimanomissione verrà trasmesso con la normale trasmissione del segnale del dispositivo alla Centrale. Lo stato di guasto manomissione verrà visualizzato nella zona del dispositivo DC e nella zona del dispositivo Shock Sensor sulla centrale.
* _**Supervisione**_
  * Durante il normale funzionamento, il contatto porta cablato/sensore d'urto invierà un segnale di supervisione al pannello di controllo separatamente a intervalli casuali di 20-30 secondi.
  * Se il pannello di controllo non ha ricevuto il segnale di supervisione dal contatto porta cablato/sensore di shock per un periodo di tempo preimpostato, il pannello di controllo indicherà che quel particolare contatto porta cablato/sensore di shock sta riscontrando un problema di mancanza di segnale.
* _**Modalità di prova**_
  * In modalità normale, premere il pulsante Test per trasmettere un segnale di test al pannello di controllo. Il contatto porta cablato/sensore d'urto entrerà in modalità test per 3 minuti.
  * In modalità test, il LED lampeggerà una volta ogni volta che viene attivato il contatto porta cablato/sensore di shock.
  * Ogni ulteriore pressione del pulsante Test ripristinerà il tempo della modalità test a 3 minuti.
* _**Attenzione**_
  *
    * Il cablaggio del contatto porta/sensore d'urto deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate in apparecchiature elettriche.
    * Before installation or any maintenance work, make sure the power supply has been disconnected.

![](<.gitbook/assets/11 (2).jpeg>) ![](<.gitbook/assets/12 (1).jpeg>) ![](.gitbook/assets/13.jpeg) ![](<.gitbook/assets/14 (1).jpeg>) ![](<.gitbook/assets/15 (3).jpeg>) ![](<.gitbook/assets/16 (6).png>)

2

* ![](<.gitbook/assets/17 (2).jpeg>)_**Cablaggio contatto porta/sensore d'urto**_
  * Prima di collegare il contatto porta cablato/sensore di shock al BUS del sistema, spegnere l'alimentazione.
  * Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](.gitbook/assets/18.jpeg)

| **Rosso**  | VDD   |
| ---------- | ----- |
| **Nero**   | TERRA |
| **Giallo** | 485A  |
| **Verde**  | 485B  |

* È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale tra i dispositivi della linea BUS collegati, assicurarsi che i ponticelli della resistenza terminale del primo (normalmente la centrale ibrida) e dei dispositivi BUS più lontani su una linea BUS siano impostati. su ON per fungere da resistori di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

_\\_

*
  * Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
  * Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
* Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/19 (5).png>)

* _**Apprendimento**_

Seguire i passaggi seguenti per apprendere il dispositivo al pannello ibrido.

Passaggio 1. Collegare il dispositivo al pannello. Quindi, accendere il pannello.

Passaggio 2. Nella pagina Web del Pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3. Fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

_Una volta acquisito nella centrale, il DCSV-29-BUS verrà riconosciuto come 2 dispositivi separati (contatto porta e sensore di shock) e occuperà 2 zone nella centrale._

Passaggio 4. Fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

3

Passaggio 5. Se il dispositivo viene acquisito con successo nel Pannello, verrà visualizzato nella sezione "Dispositivo acquisito".

![](<.gitbook/assets/20 (1).jpeg>)

* _**Impostazione del livello di materiale e sensibilità**_

Passaggio 1. Selezionare il materiale e il livello di sensibilità dalla pagina Web del Pannello di controllo (pagina Impostazione del sensore).

Passo 2. Quando DCSV-29-BUS riceve il comando di programmazione dal pannello, il LED prima si spegne, quindi diventa più luminoso e poi si spegne. L'impostazione del livello di materiale e sensibilità è ora completa.

* _**Identificazione**_

IL "**Identificare**La funzione ” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere quale dispositivo è, soprattutto in un'installazione di grandi dimensioni in cui sono inclusi numerosi dispositivi.

Per individuare DCSV-29-BUS nel sistema BUS:

\*\*Passo 1.\*\*Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo DCSV-29-BUS.

\*\*Passo 2.\*\*Se il contatto porta cablato/sensore d'urto riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e l'indicatore LED del contatto porta cablato/sensore d'urto lampeggerà 10 volte per indicare all'utente dove si trova.

_\\_

*
  *
    * Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il contatto porta cablato/sensore d'urto non ha ricevuto il segnale dal pannello.

Verificare se DCSV-29-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

* _**Prova della camminata**_
  * Per assicurarsi che il contatto porta cablato/sensore di shock sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale di controllo in modalità Walk Test e premere il pulsante Test sul DCSV-29-BUS per trasmettere un segnale di test al Pannello di controllo.
  * Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà di conseguenza le informazioni sul contatto porta cablato/sensore d'urto in cima all'elenco dei dispositivi.

_\\_

* Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se DCSV-29-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Installazione**

* _**Montaggio del contatto porta cablato/sensore d'urto**_

**Montaggio come contatto porta:**

* Il contatto porta deve essere installato con il lato contrassegnato dalla nervatura rivolto verso il magnete.
* La distanza tra il contatto porta e il magnete non deve essere superiore a 15 mm quando la porta è chiusa.
* Montare il dispositivo il più in alto possibile.

4

**Montaggio come sensore d'urto:**

Fare riferimento alla tabella seguente per informazioni sulla posizione di installazione e sullo spessore dei diversi materiali:

|                                |                        |                       | Finestra di vetro | Porta in legno/metallo | Muro di cemento |   |
| ------------------------------ | ---------------------- | --------------------- | ----------------- | ---------------------- | --------------- | - |
|                                |                        |                       |                   |                        |                 |   |
|                                | **Spessore**           | >5mm                  | <40 mm            | -                      |                 |   |
|                                |                        |                       |                   |                        |                 |   |
| **Posizione di installazione** | Cornice della finestra | Porta                 | Parete            |                        |                 |   |
|                                |                        |                       |                   |                        |                 |   |
|                                |                        | **Bassa sensibilità** | 0,5 milioni       | 0,5 milioni            | 0,25 milioni    |   |
| **Rilevamento degli urti**     |                        |                       |                   |                        |                 |   |
| **Sensibilità media**          | 1M                     | 1M                    | 0,5 milioni       |                        |                 |   |
| **Raggio**                     |                        |                       |                   |                        |                 |   |
|                                |                        |                       |                   |                        |                 |   |
|                                |                        | **Alta sensibilità**  | 1,5 milioni       | Madre                  | 1M              |   |
|                                |                        |                       |                   |                        |                 |   |

* _**Procedura di montaggio**_
  1. Utilizzare i 2 fori di montaggio sul coperchio posteriore come modello e praticare i fori sulla superficie da montare.
  2. Inserire i tasselli forniti quando il dispositivo deve essere montato su telai di finestre/pareti in cemento.
  3. Avvitare il contatto porta cablato/sensore d'urto sui tasselli. (Si consiglia di forare in caso di montaggio su acciaio, oppure è anche possibile utilizzare l'adesivo fornito nella confezione).
  4. Montare il magnete sulla porta utilizzando un piccolo pezzo di nastro biadesivo o con le viti fornite.
  5. Per montare il magnete, utilizzare i 2 fori per le viti del magnete come modello per il posizionamento e la perforazione del foro._\\_
     * Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.
  6. Avvitare il magnete e inserire i due cappucci bianchi nei fori delle viti del magnete per integrità estetica.
  7. L'installazione è ora completa.

5
