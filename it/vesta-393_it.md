# VESTA 393

![](<.gitbook/assets/0 (6).png>)**Lettore di tag cablato (TG-15N-BUS)**

-   _**introduzione**_

TG-15N-BUS è un lettore di tag in grado di comunicare e alimentare la centrale ibrida tramite connessione BUS.

Il lettore di tag cablato è integrato con etichette NFC per attivare o disattivare rapidamente il sistema di allarme con un semplice tocco.

Il dispositivo è costituito da una struttura in due parti composta da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo di fissaggio. L'interruttore antimanomissione protegge l'involucro dall'apertura o dalla rimozione dalla superficie di montaggio.

![](<.gitbook/assets/1 (4).png>)

-   _**Identificazione delle parti**_

1.  **LED verde LED rosso LED arancione Pulsante di attivazione**
2.  **Zona sensore (per tag)**
3.  **Capolinea autobus**
4.  **Interruttore a ponticello della resistenza terminale**

Quando il lettore di tag cablato è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del lettore e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/2 (6).jpeg>)![](<.gitbook/assets/3 (5).png>)

**Ponticello acceso**

![](<.gitbook/assets/4 (6).jpeg>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, la capacità di comunicazione è a livello normale.
    -   Se il ponticello è su ON, la capacità di comunicazione è migliorata.

1.  **Pulsante Impara**
2.  **Manomettere**
3.  **Vite di fissaggio**
4.  **Aperture per viti di montaggio**
5.  **Foro per cablaggio BUS**

![](<.gitbook/assets/5 (3).jpeg>)

1

-   ![](<.gitbook/assets/6 (6).png>)_**Indicatore LED:**_
    -   **LED verde:**
        -   Luce accesa per 3 secondi: quando il pannello di controllo è in modalità disinserimento
        -   Lampeggia per 5 secondi: quando viene premuto il pulsante di attivazione (_Posizionare il tag vicino alla zona del sensore per inserire il sistema durante questi 5 secondi_)
        -   Lampeggia 10 volte: quando si clicca su “identifica” sulla pagina web del Pannello.
    -   **LED rosso:**
        -   Luce accesa per 3 secondi: quando il pannello di controllo è in modalità inserimento
        -   Lampeggia per 3 secondi: quando il sistema è disinserito dopo l'allarme
    -   **LED arancione:**
        -   Luce accesa per 3 secondi: quando TG-15N-BUS rileva un tag poiché perde la connessione con la Centrale
-   _**Energia:**_

![](<.gitbook/assets/7 (3).jpeg>)![](<.gitbook/assets/8 (3).jpeg>)![](<.gitbook/assets/9 (8).png>)

Quando TG-15N-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.

![](<.gitbook/assets/10 (9).png>)

-   _**Protezione antisabotaggio:**_
    -   Il Lettore di Tag Cablato è protetto contro qualsiasi tentativo di aprire il coperchio o di staccare il Lettore dalla sua superficie di montaggio (vedi**Lettore di tag di montaggio**per dettagli).
    -   Quando viene attivata la manomissione del Lettore, un segnale di manomissione verrà inviato alla Centrale di Controllo affinché la Centrale visualizzi lo stato. Una volta inviato il segnale, il Lettore torna in modalità inattiva.
-   _**Supervisione**_
    -   Dopo l'installazione, il lettore di tag cablato trasmetterà automaticamente periodicamente i segnali di supervisione alla centrale di controllo a intervalli casuali di 20-30 secondi.
-   _**Attenzione**_
    -   Il cablaggio del lettore di tag cablato deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate sulle apparecchiature elettriche.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   _**Cablaggio del lettore di tag:**_
    -   Prima di collegare il lettore di tag cablato al bus di sistema, spegnere l'alimentazione.
    -   Per facilitare il collegamento dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/11 (4).png>)![](<.gitbook/assets/12 (6).png>)![](<.gitbook/assets/13 (6).png>)![](<.gitbook/assets/14 (3).jpeg>)

| **Rosso**  | VDD   |
| ---------- | ----- |
|            |       |
| **Nero**   | TERRA |
|            |       |
| **Giallo** | 485A  |
|            |       |
| **Verde**  | 485B  |
|            |       |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale dei dispositivi della linea BUS collegati, assicurarsi che gli interruttori a ponticello della resistenza terminale del primo (normalmente il pannello ibrido) e dei dispositivi BUS più lontani su una linea BUS siano impostati su ON per fungere da resistenze di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

![](<.gitbook/assets/15 (5).png>)

_\\<NOTE>_

-   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
-   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.

2

-   Collegamenti errati causeranno guasti o malfunzionamenti. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/16 (8).png>)

-   _**Per iniziare: apprendimento del lettore di tag cablato nel pannello di controllo**_

Seguire i passaggi seguenti per apprendere il dispositivo al pannello ibrido.

**Passo 1.**Collegare il dispositivo al Pannello. Quindi, accendere il pannello.

**Passo 2.**Nella pagina web del Pannello, fare clic su "**Learning**" per accedere alla pagina di apprendimento.

**Passaggio 3.**Fare clic su "**Inizio**” per accedere alla modalità di apprendimento; il lettore di tag cablato verrà visualizzato subito dopo che la centrale è entrata in modalità di apprendimento.

**Passaggio 4.**Fare clic su "**Aggiungere**" per includere il dispositivo nel Pannello.

**Passaggio 5.**Se il dispositivo viene appreso con successo nel Pannello, verrà visualizzato nella sezione “Dispositivo appreso”.

![](<.gitbook/assets/17 (5).png>)

-   _**Identificazione**_

La funzione “Identifica” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il Lettore Tag Cablato nel sistema BUS:

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo del lettore di tag.

**Passo 2.**Se TG-15N-BUS riceve il segnale dal pannello ibrido, la pagina web visualizzerà un messaggio di successo e il LED verde di TG-15N-BUS lampeggerà 10 volte per indicare dove si trova all'utente.

![](<.gitbook/assets/18 (8).png>)

_\\<NOTE>_

-   -   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che TG-15N-BUS non ha ricevuto il segnale dalla centrale.

Verificare se il TG-15N-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Prova della camminata**_

![](<.gitbook/assets/19 (7).png>)

-   Per assicurarsi che il lettore di tag cablato sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale di controllo in modalità Walk Test e premere il pulsante di apprendimento su TG-15N-BUS per trasmettere un segnale di test alla centrale di controllo.

3

-   Quando il Pannello riceve il segnale di test, emetterà un segnale acustico e visualizzerà le informazioni del Lettore di conseguenza in cima all'elenco dei dispositivi.

![](<.gitbook/assets/20 (5).png>)

_\\<NOTE>_

-   -   Se non c'è risposta dal pannello dopo aver premuto il pulsante di apprendimento, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Verificare se il TG-15N-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

-   _**Montaggio del lettore di tag cablato:**_

La base ha tre fori per il montaggio. Per montare il lettore di tag cablato:

-   -   1.  Svitare la vite di fissaggio.
        2.  Rimuovere il coperchio dal Lettore.
        3.  Inserire il Terminale BUS sulla scheda; passare i cavi attraverso il foro di cablaggio del BUS come mostrato in figura.
        4.  Sfonda i fori sulla base.
    -   Utilizzare i fori come modello e praticare dei fori sulla superficie da montare.
        1.  Inserire i tasselli se l'apparecchio deve essere fissato su intonaco o mattoni.
        2.  Avvitare la base sui tasselli.
    -   Rimontare il coperchio sulla base e avvitare la vite di fissaggio.

_**\\<NOTE>**_

-   -   Se il Lettore montato viene rimosso forzatamente, l'Area Breakaway verrà lasciata sulla parete separata dal Lettore e quindi verrà attivata la manomissione.
-   _**Tag Apprendimento/Rimozione**_
    -   -   Prima di apprendere un tag nel pannello di controllo, assicurarsi che il lettore di tag cablato sia stato acquisito nel pannello di controllo.
        -   Dopo aver acceso per la prima volta il lettore di tag cablato, attendere 10 secondi affinché il lettore abiliti la funzione del sensore di tag.
-   A_**Imparare**_il tag nel Pannello di controllo:**Passo 1.**Disinserire il sistema.

**Passo 2.**Vai alla pagina web locale >**Codice PIN**. Selezionare**La zona**. Posiziona il tag vicino alla zona del sensore e il lettore invierà il numero ID del tag al pannello di controllo. Il Lettore emetterà 4 bip. Clic**Carico**pulsante sulla pagina web.

_**\\<NOTE>**_

-   -   Se il tag è stato acquisito nel sistema, quando si posiziona il tag vicino alla zona sensore, emetterà 2 bip e il LED verde si accenderà per 3 secondi per accedere alla modalità Disinserimento.

**Passaggio 3.**Quando il numero ID del tag viene visualizzato sulla pagina web, inserisci un codice utente di 4 cifre e assegna un nome utente al tag.

4

**Passaggio 4.**Clic**OK**pulsante sulla pagina Web per salvare le impostazioni.

**Passaggio 5.**L'apprendimento dei tag è completo.

-   A_**Rimuovere**_il tag dal Pannello di Controllo:**Passo 1.**Disinserire il sistema.

**Passo 2.**Vai alla pagina web locale >**Codice PIN**. Selezionare**La zona**. Posiziona il tag vicino alla zona del sensore e il lettore invierà il numero ID del tag al pannello di controllo. Il Lettore di Tag emetterà 2 bip e il LED verde si accenderà per 3 secondi. Trova una colonna di numeri di tag vuota e fai clic**Carico**per verificare il numero ID del tag da eliminare.

_**\\<NOTE>**_

-   Se il tag non è stato appreso nel sistema, quando si avvicina il tag al Lettore Tag Cablato, questo emetterà 4 beep per avvisare gli utenti dell'anomalia.

**Passaggio 3.**In base al numero ID del tag, trova il numero ID dello stesso tag nell'elenco e spunta**Eliminare**.

-   **Esempio:**Come mostrato nelle immagini, il n. 1 e il n. 2 nell'elenco sono i tag appresi esistenti. Dopo aver posizionato il tag vicino al lettore e fare clic**Carico** in the blank No.3 column, the tag’s ID number shown in No. 3 is the same as that in No. 2, so No. 2 is the tag to be removed. Tick **Eliminare**nelle colonne n. 2 e n. 3 per rimuovere il tag.

**Passaggio 4.**Clic**OK**sulla pagina Web per salvare la modifica.

**Passaggio 5.**La rimozione del tag è completata.

-   _**Operazione:**_

Dopo aver completato l'apprendimento del tag nel lettore di tag cablato, ora puoi passare il sistema in modalità inserimento o disinserimento:

1.  **Controllo della modalità di disinserimento:**Applicare il tag in prossimità della Zona Sensori in modalità armata; il Lettore emetterà 2 bip quando la centrale riceve il segnale di disinserimento e passa con successo alla modalità di disinserimento.
2.  **Controllo della modalità di inserimento:**Premere una volta il pulsante di attivazione e il LED verde lampeggerà rapidamente per 5 secondi; quindi applicare il tag vicino alla zona del sensore durante questi 5 secondi, il lettore di tag emetterà 1 lungo segnale acustico per indicare che la centrale ha ricevuto con successo la richiesta di inserimento.
3.  **Lampeggio LED:**Se il sistema è armato, il LED rosso si accenderà per 3 secondi. Quando disarmato, il LED verde si accenderà per 3 secondi.
4.  **Manomettere:**Quando viene attivata la manomissione, il lettore di tag cablato trasmetterà immediatamente un segnale di allarme manomissione alla centrale di controllo e tornerà alla modalità inattiva.

5
