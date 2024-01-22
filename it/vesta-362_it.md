# VESTA 362

**Sirena interna cablata (SR-35-BUS)**

SR-35-BUS è una sirena interna cablata utilizzata per l'indicazione degli allarmi del sistema. Quando viene ricevuto un segnale di allarme dal pannello di controllo, la sirena interna cablata si attiverà per attirare l'attenzione. Il dispositivo può anche funzionare con il pannello di controllo per emettere suoni di ritardo di entrata e uscita e anche avvisare in caso di violazione di manomissione.

![](<.gitbook/assets/0 (3).jpeg>)

**Identificazione delle parti**

![](<.gitbook/assets/1 (4).jpeg>)

1.  **Pulsante Impara**
2.  **Interruttore a ponticello della resistenza terminale**

Quando la sirena interna cablata è collegata come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale della sirena interna cablata e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da terminazione

resistori. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/2 (4).png>)

**Ponticello acceso**

**Ponticello spento**

Viene inserito il ponticello che collega i due pin.

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.
    -   Se il ponticello è su ON, la capacità di comunicazione è migliorata.

1.  **Capolinea autobus**
2.  **Vite di fissaggio inferiore**
3.  **Interruttore antimanomissione**

L'interruttore antimanomissione verrà attivato quando la sirena viene rimossa dalla staffa di montaggio.

1.  **Area Breakaway per cablaggio BUS**
2.  **Staffa di fissaggio**

![](<.gitbook/assets/3 (4).png>)

1

![](<.gitbook/assets/4 (4).jpeg>)**Alimentazione elettrica**

-   Quando l'SR-35-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.

![](<.gitbook/assets/5 (1) (1).jpeg>)

**Supervisione**

La sirena interna cablata trasmetterà un segnale di supervisione ogni 20-30 secondi in modalità di funzionamento normale.

Se questo segnale non viene ricevuto, il Pannello di Controllo indicherà che quella particolare Sirena sta riscontrando un problema di fuori servizio.

![](<.gitbook/assets/6 (4).png>)

**Panoramica delle funzioni**

-   **Memoria allarme**

Se un allarme è stato attivato in tua assenza e il sistema non è stato disinserito prima della scadenza della durata dell'allarme, la sirena interna cablata emetterà un breve allarme quando il sistema è disinserito per avvisare l'utente che un allarme è stato attivato quando è assente. Ciò suggerisce che l'intruso potrebbe essere ancora all'interno dei locali.

-   **Durata dell'allarme**

Quando un allarme viene attivato dalla centrale, la centrale avviserà la sirena interna cablata di avviare l'allarme in base alla durata dell'allarme della centrale. Quando la durata dell'allarme del Pannello scade, il Pannello avviserà il dispositivo di interrompere l'allarme.

Se la sirena interna cablata non riceve il segnale della centrale di controllo per interrompere l'allarme, suonerà per un massimo di 15 minuti, quindi interromperà l'allarme.

Per esempio:

-   -   Se la durata dell'allarme della centrale è impostata su più di 15 minuti, dopo l'attivazione di un allarme, invece di attendere la scadenza della durata dell'allarme della centrale, l'allarme si interromperà dopo 15 minuti.
    -   Se la centrale è in modalità disinserita e l'interruttore antimanomissione della sirena è attivato, la sirena interna cablata non attiverà l'allarme poiché la centrale è in modalità disinserita e attiverà l'allarme per 15 minuti a causa dell'attivazione della manomissione.
-   **Tamper sirena**

La sirena interna cablata è protetta contro qualsiasi tentativo di aprire il coperchio o di staccare il dispositivo dalla superficie di montaggio.

Se il dispositivo rileva una condizione di manomissione, attiverà la sirena per la durata dell'allarme programmata. Un segnale di manomissione verrà inviato alla centrale di controllo insieme alle regolari trasmissioni di segnali affinché la centrale di controllo visualizzi di conseguenza lo stato. Se la condizione di manomissione continua, il dispositivo emetterà una serie di cinque segnali acustici per indicare un guasto ogni volta che il sistema viene inserito o quando la manomissione è abilitata.

-   **Indicazione dello stato dell'audio**

Durante l'inserimento/disinserimento del sistema, vengono utilizzati diversi metodi per distinguere i vari stati per l'utente, come elencato nella tabella seguente.

![](<.gitbook/assets/7 (5).png>)![](<.gitbook/assets/8 (5).png>)![](<.gitbook/assets/9 (6).png>)

| **Stato**                     | **Audio della sirena**                            |
| ----------------------------- | ------------------------------------------------- |
|                               |                                                   |
| Inserimento/Home              | 1 segnale acustico                                |
| Disarmare                     | 2 bip                                             |
| Inserimento (manomissione)    | 5 bip                                             |
| Disinserimento (manomissione) | 5 bip                                             |
| Suono ritardo ingresso/uscita | Il conto alla rovescia emette un segnale acustico |

![](<.gitbook/assets/10 (8).png>)![](<.gitbook/assets/11 (4).jpeg>)![](<.gitbook/assets/12 (2).jpeg>)

**Attenzione**

-   Il cablaggio della sirena interna cablata deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate sulle apparecchiature elettriche.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.

![](<.gitbook/assets/13 (2).jpeg>)

**Cablaggio della sirena**

-   Prima di collegare la sirena interna cablata al bus di sistema, spegnere l'alimentazione.
-   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/14 (2).jpeg>)

| **Rosso**  | VDD   |
| ---------- | ----- |
| **Nero**   | TERRA |
| **Giallo** | 485A  |
| **Verde**  | 485B  |

2

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale dei dispositivi della linea BUS collegati, assicurarsi che gli interruttori a ponticello della resistenza terminale del primo (normalmente il pannello ibrido) e dei dispositivi BUS più lontani su una linea BUS siano impostati su ON per fungere da resistenze di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

![](<.gitbook/assets/15 (4).png>)

_\\<NOTE>_

-   -   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
    -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/16 (7).png>)

**Apprendimento**

Seguire i passaggi seguenti per apprendere la sirena interna cablata nel pannello ibrido.

Passaggio 1. Collegare il dispositivo al pannello. Quindi, accendere il pannello.

Passaggio 2. Nella pagina Web del Pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3. Fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

Passaggio 4. Fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

Passaggio 5. Se il dispositivo viene acquisito con successo nel Pannello, verrà visualizzato nella sezione "Dispositivo acquisito".

![](<.gitbook/assets/17 (3).jpeg>)

**Identificazione**

IL "**Identificare**La funzione ” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per localizzare la Sirena Interna Filare nel sistema BUS:

**Passo 1.**Nella pagina Web della centrale ibrida, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo della sirena.

**Passo 2.**Se SR-35-BUS riceve il segnale dalla centrale ibrida, la pagina web visualizzerà un messaggio di successo e la sirena interna cablata emetterà 10 bip per indicare dove si trova all'utente.

![](<.gitbook/assets/18 (7).png>)

_\\<NOTE>_

-   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che la sirena interna cablata non ha ricevuto il segnale dalla centrale.

Verificare se l'SR-35-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

![](<.gitbook/assets/19 (6).png>)

3

![](<.gitbook/assets/20 (2).jpeg>)**Prova della camminata**

-   Per assicurarsi che la sirena interna cablata sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale di controllo in modalità Walk Test e premere il pulsante di apprendimento sull'SR-35-BUS per trasmettere un segnale di test alla centrale.
-   Quando la centrale riceve il segnale di test, emetterà un segnale acustico e visualizzerà le informazioni della sirena in cima all'elenco dei dispositivi.

_\\<NOTE>_

-   Se non c'è risposta dal pannello dopo aver premuto il pulsante di apprendimento, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se l'SR-35-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Installazione**

Passo 1. Trova la posizione in cui deve essere montata la sirena interna cablata.

Passaggio 2. Utilizzare la staffa di montaggio come modello per praticare 3 fori sulla parete per i tasselli.

Passaggio 3. Inserire i tasselli e avvitare la staffa di montaggio alla parete con 3 viti.

Passaggio 4. Agganciare la sirena alla staffa di montaggio e quindi spingere verso il basso finché non si sente un clic.

_\\<NOTE>_

-   Assicurarsi che il dispositivo sia correttamente agganciato alla staffa di montaggio, in modo che l'interruttore antimanomissione sia completamente premuto.

Passaggio 5. Verificare se l'installazione ha avuto esito positivo effettuando un test dal Pannello di controllo con funzione di inserimento e disinserimento.

L'inserimento/disinserimento riuscito sarà indicato dalla tabella fornita sopra**Indicazione dello stato dell'audio**sezione.

_\\<NOTE>_

-   Se durante l'inserimento/disinserimento si notano 5 segnali acustici brevi, significa che il tamper non è completamente premuto. Verificare che la manomissione sia impostata correttamente ed eseguire nuovamente il test dal pannello di controllo.

Passaggio 6. L'installazione è ora completa.

4
