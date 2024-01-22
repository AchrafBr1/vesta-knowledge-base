# VESTA 361

**Campanello da esterno cablato (BX-32-BUS)**

BX-32-BUS è un campanello cablato utilizzato per l'indicazione dell'allarme di sistema all'esterno di un edificio. Quando viene ricevuto un segnale di allarme dal pannello di controllo, il campanello attiverà la sirena e la luce stroboscopica per attirare l'attenzione.

Il campanello può anche funzionare con il pannello di controllo per emettere suoni di ritardo di entrata e uscita e anche avvisare in caso di violazione di manomissione.

![](<.gitbook/assets/0 (4).png>)

**Identificazione delle parti**

1.  **Fori per il montaggio a parete x 3**
2.  **Interruttore antimanomissione**

L'interruttore antimanomissione verrà attivato quando il campanello viene rimosso dalla superficie montata o quando il suo coperchio viene aperto.

1.  **Pulsante Impara**
2.  **LED 3, 2 e 1 (da sinistra a destra)**
3.  **Interruttore ponticello resistenza terminale (J3)**

Quando il campanello è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del campanello e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/1 (3).jpeg>)![](<.gitbook/assets/2 (3).png>)

**Ponticello acceso**

![](<.gitbook/assets/3 (3).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.
    -   Se il ponticello è su ON, la capacità di comunicazione è migliorata.

1.  **Terminale di collegamento autobus**
2.  **Foro per cablaggio (per terminale BUS)**
3.  **Terminale di alimentazione (ingresso CC 12 V/GND) (opzionale)**

Collegare all'alimentazione.

1.  **Foro di cablaggio (per terminale di alimentazione)**

**Alimentazione elettrica**

-   Quando BX-32-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.
-   Il BX-32-BUS può anche essere alimentato collegandolo all'adattatore CA-CC da 12 V a due fili tramite il terminale CC 12 V. Si consiglia di utilizzare l'adattatore quando è collegato a carichi che richiedono un assorbimento di energia maggiore.

1

**Supervisione**

Il campanello trasmetterà un segnale di supervisione ogni 20-30 secondi in modalità di funzionamento normale. Se questo segnale non viene ricevuto, il Pannello di Controllo indicherà che il particolare campanello sta riscontrando un problema di fuori servizio.

**Panoramica delle funzioni**

![](<.gitbook/assets/4 (3).png>)

-   **Memoria allarme**

Se un allarme è stato attivato in tua assenza e il sistema non è stato disinserito prima della scadenza della durata dell'allarme, il campanello emetterà un breve allarme quando il sistema è disinserito per avvisare l'utente che un allarme è stato attivato quando è assente. Ciò suggerisce che l'intruso potrebbe essere ancora all'interno dei locali.

-   **Durata dell'allarme**

Quando un allarme viene attivato dal pannello di controllo, il pannello di controllo avviserà il campanello di avviare l'allarme in base all'impostazione della durata dell'allarme del pannello. Quando la durata dell'allarme del pannello scade, avviserà il campanello di interrompere l'allarme.

Se il campanello non riceve il segnale del pannello di controllo per interrompere l'allarme, suonerà per un massimo di 15 minuti, quindi interromperà l'allarme.

Per esempio:

-   -   Se la durata dell'allarme del pannello è impostata su più di 15 minuti, dopo l'attivazione di un allarme, invece di attendere la scadenza della durata dell'allarme del pannello, il campanello smetterà di emettere l'allarme dopo 15 minuti.
    -   Se la centrale è in modalità disinserita e l'interruttore antimanomissione del campanello è attivato, il campanello non attiverà l'allarme poiché la centrale è in modalità disinserita e attiverà l'allarme per 15 minuti a causa dell'attivazione della manomissione.
-   **Tamper sirena**

Il campanello è protetto contro qualsiasi tentativo di aprire il coperchio o di staccare il campanello dalla sua superficie di montaggio.

Se il campanello rileva una condizione di manomissione, attiverà la sirena e la luce stroboscopica per la durata dell'allarme programmata. Un segnale di manomissione verrà inviato alla centrale di controllo insieme alle regolari trasmissioni di segnali affinché la centrale di controllo visualizzi di conseguenza lo stato. Se la condizione di manomissione continua, il campanello emetterà una serie di cinque segnali acustici ogni volta che il sistema viene inserito o quando la manomissione è abilitata, per indicare un guasto.

-   **Indicazione dello stato audio e visivo**

Durante l'inserimento/disinserimento del sistema, il campanello utilizza diversi metodi per distinguere i vari stati per l'utente, come elencato nella tabella seguente.

![](<.gitbook/assets/5 (6).png>)![](<.gitbook/assets/6 (3).png>)![](<.gitbook/assets/7 (4).png>)

|                               | **Audio della sirena**     |                                   | **Indicazione della luce stroboscopica** |
| ----------------------------- | -------------------------- | --------------------------------- | ---------------------------------------- |
|                               |                            |                                   |                                          |
| Inserimento/Home              | 1 segnale acustico         | 3                                 | I gruppi LED lampeggiano una volta       |
| Disarmare                     | 2 bip                      | Lampeggia in sequenza per 1 ciclo |                                          |
| Inserimento (manomissione)    | 5 bip                      | 3                                 | I gruppi LED lampeggiano per 5 volte     |
| Disinserimento (manomissione) | 5 bip                      | Lampeggia in sequenza per 5 cicli |                                          |
| Ritardo di ingresso/uscita    | Conto alla rovescia        |                                   |                                          |
| Suono                         | emette un segnale acustico |                                   |                                          |

![](<.gitbook/assets/8 (2).jpeg>)![](<.gitbook/assets/9 (1) (1).jpeg>)![](<.gitbook/assets/10 (7).png>)

**Attenzione**

-   Il cablaggio del campanello per esterni deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate sulle apparecchiature elettriche.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.

**Cablaggio del campanello**

2

-   Prima di collegare il campanello al bus di sistema, spegnere l'alimentazione.
-   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/11 (3).jpeg>)

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale tra i dispositivi della linea BUS collegati, assicurarsi che i ponticelli della resistenza terminale del primo (normalmente la centrale ibrida) e dei dispositivi BUS più lontani su una linea BUS siano impostati. su ON per fungere da resistori di terminazione. Assicurati di abilitare solo i 2 jumper sopra menzionati e di non impostare il jumper

passa a ON per tutti gli altri dispositivi BUS intermedi.

![](<.gitbook/assets/12 (5).png>)

_\\<NOTE>_

-   -   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
    -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/13 (1).jpeg>)

**Apprendimento**

Seguire i passaggi seguenti per apprendere l'uso del campanello nel pannello ibrido.

Passaggio 1: collegare il campanello al pannello. Quindi, accendere il pannello.

Passaggio 2: nella pagina Web del pannello, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

Passaggio 3: fare clic su "**Inizio**" per accedere alla modalità di apprendimento.

Passaggio 4: fare clic su "**Aggiungere**" per includere la casella del campanello nel pannello.

Passo 5: Se il campanello viene appreso con successo nel pannello, verrà visualizzato nella sezione "Dispositivo appreso".

3

**Identificazione**

La funzione “Identifica” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il campanello nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo del campanello.

**Passo 2.**Se il campanello riceve il segnale dalla centrale ibrida, la pagina web visualizzerà un messaggio di successo e i 3 gruppi LED del campanello lampeggeranno 10 volte per indicare all'utente dove si trova.

![](<.gitbook/assets/14 (5).png>)

_\\<NOTE>_

-   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il campanello non ha ricevuto il segnale dalla centrale.

Controllare se il campanello è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Prova della camminata**

-   Per assicurarsi che il campanello sia in grado di comunicare con la centrale dopo l'apprendimento, inserire la centrale di controllo**Prova della camminata**modalità e premere il pulsante di apprendimento sul campanello per trasmettere un segnale di test al pannello di controllo.
-   Quando il pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà le informazioni del campanello di conseguenza in cima all'elenco dei dispositivi.

![](<.gitbook/assets/15 (3).png>)

_\\<NOTE>_

-   Se non c'è risposta dal pannello dopo aver premuto il pulsante di apprendimento, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Controllare se il campanello è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Installazione**

![](.gitbook/assets/16.jpeg)

Passaggio 1. Trova la posizione in cui deve essere montato il campanello.

Passaggio 2. Svitare la vite inferiore con un cacciavite Phillips e rimuovere il coperchio superiore.

Passaggio 3. Tenere il campanello nella posizione in cui deve essere montato.

Step 4. Identify the 3 mounting holes, mount and fix the Bell box on the wall using the large screws and wall plugs provided. Secure the screws with a Phillips screwdriver. Make sure the Tamper Switch is fully depressed against the wall

![](<.gitbook/assets/17 (4).png>)

_\\<NOTE>_

-   L'interruttore antimanomissione sporge dal retro della sirena quando il campanello non è montato in posizione. Quando la sirena viene staccata dal muro, l'allarme verrà attivato. Assicurarsi che sia completamente premuto quando la sirena è montata. Se c'è uno spazio vuoto, imballare con un materiale distanziatore adeguato.

Passaggio 5. Riposizionare il coperchio superiore e serrare la vite inferiore con un cacciavite Phillips.

Passaggio 6. Verificare se l'installazione ha avuto esito positivo effettuando un test dal Pannello di controllo con funzione di inserimento e disinserimento.

L'inserimento/disinserimento riuscito sarà indicato dalla tabella fornita sopra**Indicazione dello stato audio e visivo**sezione.

![](<.gitbook/assets/18 (6).png>)

_\\<NOTE>_

-   Se durante l'inserimento/disinserimento si notano 5 segnali acustici brevi, significa che il tamper non è completamente premuto. Verificare che la manomissione sia impostata correttamente ed eseguire nuovamente il test dal pannello di controllo.

Passaggio 7. L'installazione è ora completa.

4
