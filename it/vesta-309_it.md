# VESTA 309

![](<.gitbook/assets/0 (57).png>)**Rilevatore di fumo e monossido di carbonio (SDCO-3-RhTHM-ZW-SC-AC-OTA) Introduzione**

SDCO-3-RhTHM-ZW-SC-AC-OTA è un rilevatore di fumo e monossido di carbonio Z-Wave con sensore PIR integrato, rilevamento di temperatura, umidità e calore, nonché comandi vocali e consente l'accesso all'interfaccia "S2 Unauthenticated" e supporta sia l'inclusione Z-Wave SmartStart che l'inclusione classica. È in grado di inviare segnali wireless al gateway/pannello di controllo Z-Wave al rilevamento di particelle di fumo o monossido di carbonio. Il dispositivo è inoltre collegato in serie con altri sensori nel gateway Z-Wave per fungere da sirena aggiuntiva. Quando qualsiasi altro sensore nella rete Z-Wave viene attivato e invia un segnale di allarme, anche il rilevatore di fumo attiverà l'allarme con il suo cicalino integrato come sirena per aiutare l'avviso sonoro (per i modelli con connessione seriale).

L'SDCO-3 è progettato per essere montato sul soffitto o sulla parte superiore delle scale quando il fumo si concentra per attivare tempestivamente l'allarme e proteggere la casa dai rischi di incendio.

Il rilevatore SDCO è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza.

![](<.gitbook/assets/1 (72).png>)

_**Identificazione delle parti**_

1.  **Altoparlante**
2.  **Pulsante**
    -   Premere una volta il pulsante per inviare un test di allarme, un test di allarme disattivato e segnali di temperatura e umidità per testare il rilevatore di fumo e monossido di carbonio.
    -   Premere il pulsante per 5 secondi, rilasciare il pulsante fino all'accensione del LED ambra. Quindi il LED color ambra inizierà a lampeggiare per indicare che è entrato in modalità snooze. Per ulteriori dettagli, vedere Modalità snooze temporanea nella sezione Funzionalità.
    -   Premere il pulsante una volta durante l'allarme per silenziarlo.
    -   Premi il pulsante 3 volte entro 1,5 secondi per inviare un codice di inclusione.
    -   Tieni premuto il pulsante per 10 secondi. Rilasciare il pulsante quando si sentono 2 segnali acustici per accedere al processo di calibrazione del fumo e autodiagnosi del CO.
    -   Tieni premuto il pulsante per 20 secondi. Rilascia il pulsante quando senti 3 segnali acustici per eseguire il ripristino delle impostazioni di fabbrica.
    -   Premere due volte il pulsante prima di inserire nuove batterie.
3.  **Sensore di movimento PIR**
4.  **Indicatore LED**

**LED rosso**

-   Si accende brevemente: trasmissione del segnale.
-   Lampeggio veloce: allarmante.
-   Lampeggia ogni secondo: in modalità silenziamento allarme.
-   Lampeggia ogni 2 secondi: processo di riscaldamento e calibrazione in corso.
-   Lampeggia velocemente per 3 volte ogni 8 secondi: viene rilevato fumo durante il periodo di verifica dell'incendio.
-   Lampeggia rapidamente per 2 volte ogni 5 secondi: in modalità snooze

**LED ambra**

-   Lampeggia ogni secondo: accensione del dispositivo/calibrazione non riuscita.
-   Lampeggia due volte ogni 5 secondi: malfunzionamento del dispositivo.
-   Lampeggia ogni 45 secondi: condizione di batteria scarica

**LED rosso e ambra (arancione guardando dall'esterno)**

-   Si accende: sensore di temperatura/umidità guasto.
-   Lampeggia ogni 4 secondi: Batteria scarica.

1

1.  **Cicalino**
2.  **Fori di montaggio**
3.  **Staffa di fissaggio**
4.  **Interruttore antimanomissione**
5.  **Coperchio del vano batteria**
6.  **Interruttore batteria (interno)**
7.  **Foro preforato per il cablaggio**
8.  **Vite di fissaggio del coperchio del vano batteria**
9.  **Tacche**
10. **Porta di aggiornamento firmware (USB tipo C)**
    -   Solo per aggiornamento firmware con cavo personalizzato.**Notare che:**L'uso improprio del normale cavo USB di tipo C può causare il malfunzionamento del dispositivo.

**Caratteristiche**

![](<.gitbook/assets/2 (80).png>)

-   _**Rilevamento batteria e batteria scarica**_
    -   Il modello SDCO-3-RhTHM-ZW-SC-AC-OTA utilizza CA 100-240 V come fonte di alimentazione e dispone di tre batterie ricaricabili AAA Ni-MH da 600 mAh come batteria di backup in caso di interruzione di corrente. La batteria è inclusa nella confezione.
    -   Quando la batteria ricaricabile è in carica, il rilevatore SDCO segnalerà la percentuale della batteria al gateway/pannello di controllo rispettivamente al 100%, 90%, 80%, 70%, 60%, 50%, 40%, 30% e 20% (batteria scarica).
    -   Se viene rilevata un'interruzione dell'alimentazione CA, il rilevatore SDCO invierà un rapporto di guasto CA al pannello di controllo.
    -   Quando il livello della batteria del rilevatore SDCO è basso, verrà trasmesso un segnale di batteria scarica insieme alle normali trasmissioni del segnale. Il LED ambra lampeggerà accompagnato da un segnale acustico a basso volume una volta ogni 45 secondi.
    -   Sia il LED rosso che quello ambra lampeggeranno una volta ogni 4 secondi quando la batteria è scarica.
-   _**Interruttore antimanomissione**_
    -   Il rilevatore SDCO è protetto da un interruttore antimanomissione che viene compresso quando il rilevatore SDCO viene agganciato alla staffa di montaggio. Quando il rilevatore SDCO viene rimosso dalla staffa di montaggio, l'interruttore antimanomissione verrà attivato e il rilevatore SDCO invierà un segnale di apertura antimanomissione al pannello di controllo del sistema per ricordare all'utente questa condizione.
    -   Il rilevatore SDCO invierà un segnale di chiusura antimanomissione alla centrale di controllo dopo che il dispositivo è stato agganciato alla staffa di montaggio. Tieni presente che il rilevatore SDCO deve prima essere incluso nella rete Z-Wave.
-   _**Modalità sensibilità**_
    -   Il livello di sensibilità del dispositivo può essere regolato utilizzando il comando di configurazione di Z-Wave. È possibile configurare fino a otto livelli di sensibilità (impostazione predefinita: 0x04). Impostare 0x01 per il livello di sensibilità più alto. Fare riferimento a pagina 11**“Configurazioni”**sezione per i dettagli.
-   _**Modalità snooze temporanea**_
    -   Questa funzione consente di mettere in pausa la funzione di rilevamento del movimento per un periodo di tempo specificato per evitare avvisi di movimento indesiderati senza dover disarmare il dispositivo.
    -   Per impostazione predefinita, la funzione è disabilitata e può essere attivata premendo il pulsante per 5 secondi, che abilita la modalità per 5 minuti. Puoi anche attivare la modalità utilizzando il comando di configurazione di Z-Wave e puoi configurare fino a 36 ore. La modalità snooze verrà interrotta non appena si preme un pulsante qualsiasi o si utilizza il dispositivo. Fare riferimento a pagina 12**“Configurazioni”**sezione per i dettagli.
-   _**Aggiunta di dispositivi (inclusione)**_

![](<.gitbook/assets/3 (78).png>)![](<.gitbook/assets/4 (83).png>)![](<.gitbook/assets/5 (82).png>)![](<.gitbook/assets/6 (62).png>)

Il dispositivo supporta sia il processo di inclusione classico che il processo di inclusione SmartStart.

**Inclusione classica**

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Per aggiungere il rilevatore SDCO al pannello di controllo, è necessario prima collegarlo all'alimentazione CA (rete). Si prega di seguire i passaggi seguenti per procedere.

**Passo 1.**Prima di iniziare, trova l'interruttore automatico o la scatola dei fusibili.

**Passo 2.**Una volta trovato, apri la porta e spegni l'interruttore principale.

**Passaggio 3.**Sono forniti due connettori di giunzione Wago 221. Estrarre un connettore. Tirare la leva verso l'alto e inserire il filo bianco.**Passaggio 4.**Spingere nuovamente la leva verso il basso. L'alloggiamento trasparente consente di verificare se il cavo è collegato correttamente.**Assicurati che**

**il filo sia tenuto saldamente in posizione prima di procedere.**

**Passaggio 5.**Ripetere i passaggi 3 e 4 per inserire il filo nero. L'inserimento dei due fili sullo stesso lato (a destra), come mostrato di seguito, dei due connettori semplifica l'installazione nei passaggi successivi.

**Passaggio 6.**Inserire i cavi CA rispettivamente nei due connettori, come mostrato di seguito. Se si gira l'interruttore della batteria in posizione ON, la batteria ricaricabile inizierà a caricarsi.

![](<.gitbook/assets/7 (56).png>)

_Figura 1. Inserire i fili bianco e nero._

![](<.gitbook/assets/8 (57).png>)

_Figura 2. Controllare se i cavi sono collegati correttamente._

![](<.gitbook/assets/9 (52).png>)

_Figura 3. Inserire i cavi CA._

![](<.gitbook/assets/10 (54).png>)

2

**Passaggio 7.**Capovolgere il rilevatore SDCO. Si sentirà "Benvenuto, allarme fumo e rilevatore di monossido di carbonio", a indicare che è pronto per ulteriori configurazioni (solo per modelli collegati in serie).

-   Il rilevatore SDCO consente agli utenti di impostare una richiesta di posizione per un'area, per visualizzare l'elenco completo delle posizioni e le istruzioni di configurazione, fare riferimento a "_**Suggerimento vocale**_” Sezione per i dettagli. Si consiglia di eseguire il processo di riscaldamento e calibrazione**Prima**includendo il tuo dispositivo nel coordinatore Z-Wave.

**\\<Warm-up and calibration>**

1.  Il rilevatore SDCO emetterà 2 brevi segnali acustici e inizierà il processo di riscaldamento**1**minuto. Il LED lampeggerà ogni 2 secondi.
2.  Allo scadere del periodo di riscaldamento di 1 minuto, il rilevatore SDCO emetterà un segnale acustico per indicare che sta entrando nel processo di calibrazione. Il processo di calibrazione richiede 1~7 minuti; il LED continuerà a lampeggiare durante la calibrazione.
3.  Una volta completata la calibrazione, il rilevatore SDCO emetterà un suono a 2 toni e il LED smetterà di lampeggiare per indicare che ora è in normale funzionamento. Se la calibrazione fallisce, il rilevatore SDCO emetterà segnali acustici continui.

**\\<Including to the Z-Wave coordinator>**

1.  Mettere il gateway Z-Wave o il pannello di controllo in modalità Inclusione (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
2.  Entro 1,5 secondi, premere il pulsante 3 volte.
3.  Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di inclusione.
4.  Se il sensore è già stato incluso in un altro gateway/pannello di controllo Z-Wave, o se il sensore non può essere incluso nell'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere Esclusione) prima di tentare di includerlo nell'attuale gateway/pannello di controllo Z-Wave.

**Inclusione SmartStart**

![](<.gitbook/assets/11 (29).jpeg>)

Z-Wave SmartStart utilizza il DSK del dispositivo per migliorare e semplificare il processo di inclusione. DSK è la chiave specifica del dispositivo utilizzata per la comunicazione di autenticazione. Le informazioni DSK vengono archiviate nel formato del codice QR stampato su un'etichetta e incollata all'esterno del dispositivo.

Con un controller Z-wave che fornisce l'inclusione di SmartStart, il dispositivo abilitato SmartStart può essere aggiunto a una rete Z-Wave eseguendo la scansione del codice QR Z-Wave sul prodotto. Senza ulteriori azioni, il dispositivo verrà aggiunto automaticamente entro 10 minuti dall'accensione nelle vicinanze della rete.

-   -   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Eseguire la scansione del codice QR sul rilevatore SDCO per recuperarlo**DSK**.
    -   Accendi il rilevatore SDCO, una richiesta di inclusione SmartStart verrà inviata automaticamente al gateway.
    -   Il gateway includerà automaticamente il dispositivo al momento del riconoscimento del dispositivo abbinando la richiesta di inclusione al DSK ottenuto
        -   Il DSK del dispositivo viene utilizzato solo durante l'inclusione.
        -   Il DSK può essere letto senza accendere il rilevatore SDCO, quindi è possibile preparare il gateway per includere il dispositivo prima di installare e accendere il rilevatore SDCO.
        -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, escluderlo prima (vedi_**Rimozione del dispositivo**_) prima di tentare di includerlo nell'attuale gateway/pannello di controllo Z-Wave. Il dispositivo non invierà un file

Richiesta di inclusione di SmartStart se è già in un gateway/pannello di controllo Z-Wave.

-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/12 (46).png>)

Il rilevatore SDCO deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra.

-   -   Mettere il gateway Z-Wave o la centrale di controllo in modalità di esclusione (fare riferimento al manuale del gateway Z-Wave o della centrale di controllo).
    -   Entro 1,5 secondi, premere il pulsante 3 volte e il rilevatore SDCO verrà rimosso dalla rete Z-Wave.
-   _**Messaggio vocale (per modelli con connessione seriale)**_

![](<.gitbook/assets/13 (34).png>)

Il rilevatore SDCO consente all'utente di impostare una richiesta di posizione per un'area (ad esempio, cucina o seminterrato). Quando viene attivato un allarme, il rilevatore SDCO riprodurrà il messaggio vocale preprogrammato per avvisare l'utente di evacuare. Per la prima configurazione, procedi nel seguente modo:

**Passo 1.**Accendere l'interruttore della batteria.

**Passo 2.**Verrà riprodotto il messaggio n. 1 "Benvenuto, rilevatore di fumo e monossido di carbonio".

**Passaggio 3.**Verrà riprodotto il messaggio n. 2 “Nessuna posizione programmata”.

**Passaggio 4.**Verrà riprodotto il messaggio n. 3 "Per selezionare la posizione, tenere premuto il pulsante ora".

**Passaggio 5.**Continuare a tenere premuto il pulsante e verrà riprodotto il messaggio n. 4 "Per programmare la posizione, tenere premuto il pulsante dopo aver sentito la posizione".**Passaggio 6.**Continua a tenere premuto il pulsante e verrà riprodotto il messaggio n. 6 "Posizione" seguito dalle posizioni da selezionare

(dal suggerimento n. 11-31).

**.Passaggio 7.**Per impostare la richiesta della posizione desiderata, rilasciare semplicemente il pulsante.

**. ..****.Passaggio 8.**Il dispositivo riprodurrà il messaggio n. 7 "Programmato" dopo aver rilasciato il pulsante ed emetterà 2 segnali acustici di conferma.

| NO | Suggerimento vocale                                                                      | Condizione                                  |   |   |
| -- | ---------------------------------------------------------------------------------------- | ------------------------------------------- | - | - |
| 1  | Benvenuto, Rilevatore di fumo e Rilevatore di monossido di carbonio                      | Riprodotto quando il dispositivo è acceso.  |   |   |
| 2  | Nessuna posizione programmata                                                            | Giocato per la prima configurazione.        |   |   |
| 3  | Per selezionare la posizione, tieni premuto il pulsante ora.                             | Giocato per l'impostazione della posizione. |   |   |
| 4  | Per programmare la posizione, tenere premuto il pulsante dopo aver sentito la posizione. | Giocato per l'impostazione della posizione. |   |   |
|    |                                                                                          |                                             |   |   |
| 5  | Nessuna posizione programmata                                                            | Giocato per l'impostazione della posizione. |   |   |
| 6  | Posizione                                                                                | Giocato per l'impostazione della posizione. |   |   |
| 7  | Programmato                                                                              | Giocato per l'impostazione della posizione. |   |   |

3

| 8  | Emergenza, presenza di monossido di carbonio\[nome del luogo]. | Riprodotto quando viene attivato un allarme.          |   |
| -- | -------------------------------------------------------------- | ----------------------------------------------------- | - |
| 9  | Emergenza, fumo dentro\[nome del luogo].                       | Riprodotto quando viene attivato un allarme.          |   |
|    |                                                                |                                                       |   |
| 10 | Evacuare                                                       | Riprodotto quando viene attivato un allarme.          |   |
| 11 | Seminterrato                                                   | Giocato per la selezione della posizione.             |   |
| 12 | Sala                                                           | Giocato per la selezione della posizione.             |   |
| 13 | Ufficio                                                        | Giocato per la selezione della posizione.             |   |
| 14 | Camera da letto principale                                     | Giocato per la selezione della posizione.             |   |
| 15 | Camera da letto                                                | Giocato per la selezione della posizione.             |   |
| 16 | Stanza degli ospiti                                            | Giocato per la selezione della posizione.             |   |
| 17 | Cucina                                                         | Giocato per la selezione della posizione.             |   |
| 18 | Sala da pranzo                                                 | Giocato per la selezione della posizione.             |   |
| 19 | Soggiorno                                                      | Giocato per la selezione della posizione.             |   |
| 20 | Lavanderia                                                     | Giocato per la selezione della posizione.             |   |
| 21 | Attico                                                         | Giocato per la selezione della posizione.             |   |
| 22 | Asilo                                                          | Giocato per la selezione della posizione.             |   |
| 23 | Toilette                                                       | Giocato per la selezione della posizione.             |   |
|    |                                                                |                                                       |   |
| 24 | Locale tecnico                                                 | Giocato per la selezione della posizione.             |   |
|    |                                                                |                                                       |   |
| 25 | Armadio                                                        | Giocato per la selezione della posizione.             |   |
|    |                                                                |                                                       |   |
| 26 | Soggiorno mansardato                                           | Giocato per la selezione della posizione.             |   |
|    |                                                                |                                                       |   |
| 27 | Soggiorno nel seminterrato                                     | Giocato per la selezione della posizione.             |   |
| 28 | Scala                                                          | Giocato per la selezione della posizione.             |   |
| 29 | Box auto                                                       | Giocato per la selezione della posizione.             |   |
| 30 | Appartamento in affitto                                        | Giocato per la selezione della posizione.             |   |
| 31 | Nessuna posizione                                              | Riprodotto quando non è selezionata alcuna posizione. |   |

-   Quando viene attivato un allarme di monossido di carbonio, fumo e/o temperatura, la sirena verrà attivata in base al periodo di tempo indicato di seguito e seguita da istruzioni vocali per avvisare l'utente di evacuare.

|                | Tipo di allarme |   |                                                                |                                                                | Schema di allarme e avviso vocale |                                                               |                                                            |                                                                     |                                       |          | Condizione  |   |   |   |   |   |   |   |   |   |   |
| -------------- | --------------- | - | -------------------------------------------------------------- | -------------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------- | -------- | ----------- | - | - | - | - | - | - | - | - | - | - |
|                |                 |   |                                                                | **(Ripetere)**                                                 |                                   |                                                               | Riprodotto dopo il suono di avviso intermittente           |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                | Fumo/Calore     |   |                                                                | Bip ----- Bip ------ Bip ------ Bip ----- Bip                  |                                   |                                                               | quando viene attivato un allarme fumo o calore. Per favore |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   | Emergenza, fumo dentro\[nome del luogo].                       | Posizione                                                      | .                                 |                                                               |                                                            | nota che verrà riprodotto il messaggio di richiesta della posizione |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Evacuare.                                                      |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   | in base al nome della posizione preprogrammata.               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | **(Ripetere)**                                                 |                                   |                                                               | Riprodotto dopo il suono di avviso intermittente           |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                | CO              |   |                                                                | Bip-bip-bip-bip                                                |                                   |                                                               | quando viene attivato un allarme di monossido di carbonio. |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   | Emergenza, presenza di monossido di carbonio\[nome del luogo]. |                                                                |                                   | Tieni presente che verrà riprodotta la richiesta di posizione |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Posizione. Evacuare.                                           |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   | in base al nome della posizione preprogrammata.               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | **(Ripetere)**                                                 |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Bip---Beep---Beep---Beep-Beep-Beep-Beep-----                   |                                   |                                                               | Riprodotto dopo il suono di avviso intermittente           |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Bip --- Bip --- Bip                                            |                                   |                                                               | quando c'è fumo/calore e monossido di carbonio             |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
| Fumo/Calore+CO |                 |   | Emergenza, fumo dentro\[nome del luogo]. Posizione.            |                                                                |                                   | viene rilevato l'allarme. Si prega di notare la posizione     |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Evacuare.                                                      |                                   |                                                               |                                                            |                                                                     | il prompt verrà riprodotto in base al |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Emergenza, presenza di monossido di carbonio\[nome del luogo]. |                                   |                                                               | nome della posizione preprogrammata.                       |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | Posizione. Evacuare.                                           |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | **(Ripetere)**                                                 |                                   |                                                               | Giocato                                                    | un suono di avvertimento                                            | Quando                                | un ladro |             |   |   |   |   |   |   |   |   |   |   |
|                | Bug             |   |                                                                | Suono di allarme per 6,5 secondi                               |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                | viene rilevato l'allarme.         |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                | **(Ripetere)**                                                 |                                   |                                                               | Giocato                                                    |                                                                     | emette un segnale acustico quando a   | Acqua    | l'allarme è |   |   |   |   |   |   |   |   |   |   |
|                | Acqua           |   |                                                                | Bip-Beep-Beep-Beep per 6,5 secondi                             |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                | rilevato.                         |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |
|                |                 |   |                                                                |                                                                |                                   |                                                               |                                                            |                                                                     |                                       |          |             |   |   |   |   |   |   |   |   |   |   |

![](<.gitbook/assets/14 (34).png>)

-   _**Verifica del fuoco**_
    -   La verifica antincendio può essere utilizzata per impostare il timer di verifica utilizzando il comando di configurazione di Z-Wave per il rilevatore SDCO. Quando è impostato il timer di verifica incendio, il rilevatore SDCO inizierà il conto alla rovescia del timer di verifica incendio quando il dispositivo viene attivato. È possibile impostare fino a 150 secondi (impostazione predefinita: 0 secondi). Fare riferimento a pagina 10**“Configurazioni”**sezione per i dettagli.
    -   Se la funzione di verifica incendio è abilitata, il LED rosso lampeggerà rapidamente per 3 volte ogni 8 secondi se viene rilevato fumo durante questo periodo. Una volta scaduto il timer di verifica incendio, il rilevatore SDCO attiverà l'allarme incendio se la concentrazione di fumo supera la soglia di rilevamento.
-   _**Rilevamento allarme**_

![](<.gitbook/assets/15 (34).png>)

Il rilevatore SDCO attiverà l'allarme antincendio quando viene attivata la funzione di rilevamento del fumo o di rilevamento del calore elevato. Quando viene attivato un allarme, il rilevatore SDCO trasmetterà il segnale di allarme e lancerà l'allarme con il cicalino integrato, il LED rosso lampeggerà rapidamente.

**Rilevazione del fumo:**

-   Il rilevatore SDCO controlla la concentrazione di fumo ogni 8 secondi

4

-   Ogni volta che la concentrazione di fumo supera la soglia di rilevamento, il rilevatore SDCO invierà un segnale attivo al pannello di controllo e attiverà l'allarme.
-   Se la concentrazione di fumo persiste, il Rivelatore SDCO continuerà ad inviare ogni minuto il segnale attivo alla Centrale.
-   Se non viene rilevato fumo per 20 tempi di rilevamento continui, il rilevatore SDCO trasmetterà un segnale di ripristino.

**Rilevamento del calore:**

-   Il rilevatore SDCO controlla la temperatura ogni 10 secondi.
-   L’allarme verrà attivato nelle seguenti condizioni:
    -   Quando la temperatura aumenta di 8,25°C al minuto (velocità di aumento).
    -   Quando la temperatura supera i 57,25°C (calore elevato).
-   Se non viene rilevato alcun calore elevato per 16 tempi di rilevamento continui, il rilevatore SDCO trasmetterà un segnale di ripristino.
-   Se l'allarme è stato attivato da una condizione di calore elevato (57,25°C), la temperatura deve scendere sotto i 49°C affinché il rilevatore interrompa l'allarme.

**Rilevamento del monossido di carbonio:**

 Il sensore di CO controllerà il livello di concentrazione di CO ogni 16 secondi, se il livello di concentrazione supera la soglia di rilevamento, il rilevatore SDCO trasmetterà un segnale di allarme e attiverà l'allarme con il cicalino integrato.

 Il sensore di CO è dotato di funzione di autodiagnosi e controlla regolarmente la salute o lo stato del sensore ogni 12 ore.

 L'allarme verrà attivato dopo che viene rilevata la concentrazione di CO in base al periodo di tempo indicato nella tabella seguente: (conforme allo standard EN-50291)

| **Livello di concentrazione di CO** | **Tempo impiegato prima di allarmare** |
| ----------------------------------- | -------------------------------------- |
| 30 +/- 10% ppm                      | N / A                                  |
| 50 +/- 10% ppm                      | 60~90 minuti                           |
| 100 +/- 10% ppm                     | 10~40 minuti                           |
| 300 +/- 10% ppm                     | Meno di 3 minuti                       |

 L'allarme verrà attivato dopo che viene rilevata la concentrazione di CO in base al periodo di tempo indicato nella tabella seguente: (conforme allo standard UL-2034)

| **Livello di concentrazione di CO** | **Tempo impiegato prima di allarmare** |               |
| ----------------------------------- | -------------------------------------- | ------------- |
| 30                                  | +/- 3% ppm                             | N / A         |
| 70                                  | +/- 5% ppm                             | N / A         |
| 70                                  | +/- 5% ppm                             | 60~240 minuti |
| 150 +/- 5% ppm                      | 10~50 minuti                           |               |
| 400                                 | +/- 10% ppm                            | 4~15 minuti   |

 Una volta che il livello di concentrazione di CO supera la soglia e persiste per il periodo di tempo elencato nella tabella sopra, il rilevatore SDCO trasmetterà il segnale al coordinatore Z-Wave e lancerà l'allarme con la sua sirena incorporata.

 Se il CO scende al di sotto di 30 ppm per 10 tempi di rilevamento continuo, l'SDCO trasmetterà un segnale di ripristino.

**Rilevamento della temperatura e dell'umidità:**

Il sensore di temperatura e umidità trasmetterà regolarmente segnali di temperatura e umidità in base all'impostazione. L'intervallo predefinito di fabbrica è compreso tra 30 e 33 minuti.

-   -   Il rilevatore SDCO invierà un segnale di temperatura quando la temperatura cambia di +/- 2°C.
    -   È anche possibile premere una volta il pulsante per trasmettere manualmente un segnale di temperatura.
-   _**Rilevamento IR**_
    -   Il rilevatore SDCO trasmetterà il segnale al pannello di controllo se viene rilevato un movimento all'interno della copertura di rilevamento IR. Il cicalino non suonerà e il LED non lampeggerà. Per i dettagli fare riferimento al Pannello di controllo.
    -   Entro 60 secondi, se non vengono rilevati ulteriori movimenti o avvisi, l'IR verrà ripristinato e tornerà al normale funzionamento.
-   _**Test del rilevatore SDCO**_

![](<.gitbook/assets/16 (36).png>)![](<.gitbook/assets/17 (29).png>)

Premendo il pulsante sul rilevatore SDCO, è possibile verificare se il rilevatore SDCO funziona normalmente.

-   -   Se il rilevatore SDCO funziona normalmente, il LED rosso lampeggerà una volta seguito da un segnale acustico a 2 toni.
    -   Se vengono emessi tre segnali acustici bitonali (DO-DI DO-DI DO-DI), significa che il sensore di fumo è fuori servizio.
    -   Se vengono emessi 5 bip (DO-Bi-Bi-Bi-DO), significa che il sensore di calore è fuori servizio.
    -   Se vengono emessi 7 bip (Bi-Bi-Bi-DO-Bi-Bi-Bi), significa che il sensore CO è fuori servizio.
-   _**Silenziamento allarme**_
    -   Esistono due modi per mettere manualmente l'SDCO in modalità Silenziamento allarme: premendo il pulsante o inviando**Controllo scena/sirena o controllo attivazione/disattivazione sirena**comando. In entrambi i casi, l'SDCO entrerà in modalità Silenziamento allarme. Trascorso il periodo verrà inviato un segnale di ripristino. Fare riferimento a pagina 8**“Emergenza fumo/Emergenza fumo cancellata**_**, Emergenza calore cancellata ed Emergenza CO/**_**Emergenza CO cancellata"**sezione per i dettagli.

![](<.gitbook/assets/18 (35).png>)

**Premendo il pulsante:**

-   Quando il rilevatore di fumo è in allarme, premendo il pulsante si metterà il rilevatore di fumo in modalità Silenziamento allarme per silenziare l'allarme.

**Invio comando scenario/controllo sirena o controllo accensione/spegnimento sirena:**

-   Il comando Scena/Sirena consente di programmare diversi tipi di allarme con indicazione della posizione.**Si prega di notare che questo comando NON PUÒ essere utilizzato per interrompere la sirena e i messaggi vocali di un allarme reale.**
-   Per disattivare la sirena e i messaggi vocali utilizzando questo comando, impostare Basic Set: 0x00. Il rilevatore SDCO entrerà quindi in modalità Silenziamento allarme.
-   Il comando Controllo On/Off Sirena consente di controllare la sirena di un rilevatore di fumo.**Si prega di notare che questo comando NON PUÒ essere utilizzato per interrompere la sirena e i messaggi vocali di un allarme reale.**
-   Per spegnere la sirena utilizzando questo comando impostare Basic Set: 0x00. Il rilevatore SDCO entrerà quindi in modalità Silenziamento allarme.
-   Durante il periodo di silenziamento dell'allarme, il LED rosso lampeggerà una volta al secondo. Il rilevatore di fumo continuerà a monitorare la concentrazione di fumo durante il periodo di silenzio dell'allarme:
    1.  Una volta scaduto il periodo di silenziamento dell'allarme, se la concentrazione di fumo è scesa al di sotto della soglia di allarme, il rilevatore di fumo emetterà un segnale acustico a 2 toni e tornerà al funzionamento normale senza far suonare l'allarme.

5

-   1.  Se la concentrazione di fumo supera ancora la soglia di allarme, il rilevatore di fumo inizierà nuovamente a emettere allarme.
    2.  Se la concentrazione di fumo continua ad aumentare durante il periodo di silenziamento dell'allarme e supera una seconda soglia di allarme, il rilevatore SDCO inizierà nuovamente ad emettere allarme. Un allarme attivato dal superamento della seconda soglia di allarme può essere tacitato premendo il pulsante.
-   _**Ricalibrazione**_

![](<.gitbook/assets/19 (35).png>)

Il rilevatore SDCO calibrerà il sensore del rilevatore di fumo ogni volta che viene applicata l'alimentazione per garantire una sensibilità al fumo ottimale. Dopo l'installazione, le condizioni operative del rilevatore di fumo possono variare nel tempo, il che potrebbe influire sulla sua funzione di rilevamento del fumo e richiedere la ricalibrazione. Esistono due modi per ricalibrare il rilevatore di fumo: calibrazione automatica e calibrazione manuale.

**Calibrazione automatica:**

-   Dopo l'accensione, il rilevatore di fumo eseguirà la calibrazione automatica dopo 4 ore.
-   Dopo la prima calibrazione automatica, il rilevatore di fumo eseguirà la calibrazione automatica ogni mese. Durante il processo di calibrazione automatica, il rilevatore di fumo non emetterà alcun suono.
-   Se la calibrazione automatica fallisce, il LED ambra lampeggerà ogni secondo insieme a segnali acustici continui.
-   Quando la calibrazione automatica del rilevatore di fumo fallisce, la funzione di allarme fumo continuerà a funzionare normalmente utilizzando il valore di soglia preso dall'ultima calibrazione riuscita.

**Calibrazione manuale:**

-   La calibrazione manuale può essere eseguita in qualsiasi momento, se lo si desidera:
    1.  Tenere premuto il pulsante per 10 secondi e rilasciarlo quando il rilevatore di fumo emette 2 bip.
    2.  Il rilevatore di fumo entrerà nel processo di calibrazione. L'indicatore LED lampeggerà ogni 2 secondi.
    3.  Una volta terminata la ricalibrazione, il rilevatore di fumo emetterà due rapidi segnali acustici per indicare. Il LED si spegnerà.
    4.  Se il processo di calibrazione fallisce, il rilevatore di fumo emetterà un suono di allarme. Rimuovere e reinserire la batteria per riavviare nuovamente il processo.
-   _**Identificazione del dispositivo**_

![](<.gitbook/assets/20 (25).png>)

È disponibile la funzione per identificare il rilevatore SDCO tra i tuoi dispositivi inviando comandi Z-Wave al Gateway. Se il dispositivo riceve il segnale con successo, il LED del dispositivo inizierà a lampeggiare. Il numero di cicli lampeggianti è programmabile utilizzando i comandi CC dell'indicatore Z-Wave. Per favore riferisci a "_**Formato dati classe comando”**_sezione per i dettagli.

-   _**Ripristino delle impostazioni di fabbrica**_

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Tenere premuto il pulsante sul rilevatore SDCO per 20 secondi. Rilascia il pulsante quando senti 3 segnali acustici per eseguire il ripristino delle impostazioni di fabbrica.

_\\<NOTE>_

-   Il ripristino delle impostazioni di fabbrica dell'SDCO lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway o il pannello di controllo Z-Wave manterrà comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave dell'SDCO.

**Manutenzione e pulizia**

La manutenzione e la pulizia regolari contribuiranno a mantenere il rilevatore SDCO in buone condizioni.

-   Testare settimanalmente il rilevatore SDCO per verificare che i suoni e gli indicatori di allarme funzionino correttamente.
-   Pulire il rilevatore SDCO almeno una volta ogni 6 mesi.
    -   Aspirare delicatamente lo sporco/polvere/piccole particelle accumulate nella camera e nelle feritoie di rivelazione fumo.
    -   Pulisci l'involucro strofinandolo accuratamente con un panno umido e asciugalo. Non far entrare acqua all'interno dell'allarme.
    -   Non utilizzare mai detergenti, detergenti o solventi sul rilevatore.
-   Evitare di spruzzare deodoranti per ambienti, lacca per capelli o altri aerosol vicino al rilevatore SDCO.
-   Non verniciare né modificare in nessun caso il rilevatore.

**Scadenza**

Il rilevatore SDCO ha una durata massima di**10 anni**dalla data di installazione. È necessario sostituire il rilevatore SDCO immediatamente dopo 10 anni di servizio.

Si consiglia di scrivere la data "Sostituire entro" (10 anni dalla data di installazione) sul retro del rilevatore prima dell'installazione.

**Installazione**

-   _**Linee guida per l'installazione**_
    -   Si consiglia di installare il dispositivo nella zona centrale del soffitto. Se montato a soffitto, il PIR offre prestazioni di rilevamento migliori contro il movimento orizzontale.
    -   L'altezza di montaggio ideale per il rilevatore SDCO è compresa tra 2,4 e 3 metri. Il montaggio a una distanza superiore a 3 metri può influire sulle prestazioni di rilevamento.
    -   Non installare il rilevatore nelle seguenti posizioni:
        -   La cucina – Il fumo proveniente dalla cucina potrebbe causare un allarme indesiderato.
        -   Vicino a una ventola, una lampada fluorescente o un condizionatore d'aria: le correnti d'aria provenienti da essi possono influenzare la sensibilità del rilevatore.
        -   Vicino alle travi del soffitto o sopra un armadio: l'aria stagnante in queste aree può influire sulla sensibilità del rilevatore.
        -   Nel culmine di un “**UN**” tipo di telaio del soffitto.
    -   Il rilevatore SDCO può supportare la copertura di rilevamento entro un raggio di 4 metri.

6

-   _**Raccomandazione per l'installazione**_
    -   **Limitazioni**
        -   Non esporre il rilevatore SDCO alla luce solare diretta.
        -   Evitare di installare il rilevatore SDCO in aree in cui dispositivi come condizionatori d'aria o riscaldatori possono causare rapidi cambiamenti di temperatura nell'area di rilevamento.
        -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
        -   Non puntare direttamente verso fonti di calore, ad esempio fuochi o caldaie, e non sopra i radiatori.
-   _**Montaggio del rilevatore SDCO**_

**Passo 1.**Prima di iniziare, trova l'interruttore automatico o la scatola dei fusibili.

**Passo 2.**Una volta trovato, apri la porta e spegni l'interruttore principale.

**Passaggio 3.**Posizionare il rilevatore SDCO nella posizione di montaggio desiderata e utilizzare il test della portata per assicurarsi che l'SDCO possa essere ricevuto dal pannello di controllo nella posizione di montaggio.

**Passaggio 4.**Sono forniti due connettori di giunzione Wago 221. Estrarre un connettore. Tirare la leva verso l'alto e inserire il filo bianco.

**Passaggio 5.**Spingere nuovamente la leva verso il basso. L'alloggiamento trasparente consente di verificare se il cavo è collegato correttamente.**Assicurati che il filo sia tenuto saldamente in posizione prima di procedere.**

**Passaggio 6.**Ripetere i passaggi 4 e 5 per inserire il filo nero. L'inserimento dei due fili sullo stesso lato (a destra), come mostrato di seguito, dei due connettori semplifica l'installazione nei passaggi successivi.

**Passaggio 7.**Inserire i cavi CA rispettivamente nei due connettori, come mostrato di seguito.

_Figura 1. Inserire i fili bianco e nero._

_Figura 2. Controllare se i cavi_

_siano collegati correttamente._

_Figura 3. Inserire i cavi CA._

**Passaggio 8.**Il rilevatore SDCO è dotato di una staffa di montaggio per l'installazione a soffitto. La staffa offre flessibilità bidirezionale.

**Passaggio 9.**Utilizzare i 4 fori sulla staffa come dima per praticare i fori e inserire i tasselli, se necessario.

**Passaggio 10.**L'utente può ruotare la staffa di montaggio in senso orario o antiorario per bloccare il gancio. Assicurarsi che i tasselli siano a filo con la superficie di montaggio.

**Passaggio 11.**Una volta che la posizione è soddisfacente, avvitare la staffa di montaggio al soffitto.

**Passaggio 12.**Rimuovere accuratamente la polvere, altrimenti potrebbe sporcare il sensore e impedirne il corretto funzionamento in caso di emergenza.

**Passaggio 13.**Utilizzare un cacciavite Phillips per rimuovere la vite di fissaggio del vano batteria. Rimuovere il coperchio del vano batteria e collegare il cavo alla scheda PCB del rilevatore SDCO. Il design infallibile fornisce una procedura di installazione semplice.

**Passaggio 14.**Inserisci i due connettori di giunzione nello spazio accanto alla batteria ricaricabile.

**Passaggio 15.**Riposizionare il coperchio del vano batteria nella posizione corretta e serrare la vite di fissaggio. Il foro preforato sul coperchio ne migliora la flessibilità.

**Passaggio 16.**L'SDCO è dotato di tre tacche sul coperchio posteriore (come mostrato di seguito) per agganciare il dispositivo alla staffa di montaggio.

**Passaggio 17.**Tenere il rilevatore SDCO con particolare attenzione e agganciarlo alla staffa di montaggio.

**Passaggio 18.**Ruotare il rilevatore SDCO in senso orario per bloccare il gancio. L'installazione è ora completa.

**Passaggio 19.**Accendere l'interruttore di alimentazione principale per ulteriori operazioni.

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Sensore di notifica allarme fumo

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Identificativo del produttore:**0x018E

**ID tipo prodotto:**0x0003

**Codice prodotto:**0x0115

**Gruppo di associazione massimo:**3

**Classe di comando supportata:**

| **Classe di comando**                     | **Versione** | **Classe di sicurezza richiesta**      |
| ----------------------------------------- | ------------ | -------------------------------------- |
|                                           |              |                                        |
| Associazione                              | 2            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Informazioni sul gruppo dell'associazione | 3            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Di base                                   | 2            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Batteria                                  | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Sensore multilivello                      | 11           | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
| Attivazione della scena                   | 1            | Classe di sicurezza più alta garantita |
|                                           |              |                                        |
|                                           |              | 7                                      |

| Notifica                                  | 8 | Classe di sicurezza più alta garantita |
| ----------------------------------------- | - | -------------------------------------- |
|                                           |   |                                        |
| Reimpostazione del dispositivo localmente | 1 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Metadati di aggiornamento del firmware    | 5 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Specifico del produttore                  | 2 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Multicanale                               | 4 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Associazione multicanale                  | 3 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Livello di potenza                        | 1 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Cambia binario                            | 2 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Configurazione                            | 1 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Stato operativo del termostato            | 2 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Versione                                  | 3 | Classe di sicurezza più alta garantita |
|                                           |   |                                        |
| Servizio di trasporto                     | 2 | Nessuno                                |
|                                           |   |                                        |
| Informazioni su Z-Wave Plus               | 2 | Nessuno                                |
|                                           |   |                                        |
| Sicurezza                                 | 1 | Nessuno                                |
|                                           |   |                                        |
| Sicurezza 2                               | 1 | Nessuno                                |
|                                           |   |                                        |
| Supervisione                              | 1 | Nessuno                                |
|                                           |   |                                        |

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”: (nodi max: 5)

Batteria CC (COMANDO_CLASSE_BATTERIA)

SensoreMutilevel CC, V11 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Notifica CC,V8 (COMANDO_CLASSE_NOTIFICA)

CC di base(COMANDO_CLASSE_DI BASE)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

Gruppo 2 per “Set sensore base”: (nodo massimo: 5)

CC di base (COMANDO_CLASSE_DI BASE)

Quando il rilevatore di fumo è attivo, invierà l'impostazione base (0xFF) nel Gruppo 2.

Quando il rilevatore di fumo viene ripristinato, invierà il set di base (0x00) nel Gruppo 2.

Gruppo 3 per “Set di scene”: (nodo max: 5)

CC di attivazione della scena (COMMAND_CLASSE_SCENA_ATTIVAZIONE)

Dopo aver aggiunto il Gruppo 3, invierà il comando di attivazione della scena in caso di allarmi SC, HD o CO.

Dopo aver aggiunto il Gruppo 3, invierà il comando di attivazione della scena quando viene ripristinato SC, HD o CO.

Per favore riferisci a_Tavolo 2_Controllo sirena, invierà 00 00 quando il rilevatore di fumo verrà ripristinato.

-   _**Formato dei dati della classe di comando**_
    -   **Guasto/ripristino CA:\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**
-   Quando viene rilevata un'interruzione dell'alimentazione CA, l'SDCO invierà un segnale di guasto CA al pannello di controllo. Quando l'alimentazione CA viene ripristinata, l'SDCO invierà un segnale di ripristino al pannello di controllo.

|  | Guasto CA:     | 00 00 00 FF 08 02 00 00 |
| - | -------------- | ----------------------- |
|  | Ripristino CA: | 00 00 00 FF 08 03 00 00 |

-   **Batteria:\[COMANDO_CLASSE_BATTERIA]\[BATTERIA_RAPPORTO]**
    -   0x64 --- Batteria carica al 100%.
    -   0x5A --- Batteria al 90%.
    -   0x50 --- Batteria all'80%.
    -   0x46 --- Batteria al 70%.
    -   0x3C --- Batteria al 60%.
    -   0x32 --- Batteria al 50%.
    -   0x28 --- Batteria al 40%.
    -   0x1E --- Batteria al 30%.
    -   0x14 --- Batteria scarica al 20%.
    -   0xFF --- Batteria scarica (spenta)
    -   Interrotto --- Il dispositivo smetterà di funzionare ed entrambi i LED rosso e ambra lampeggeranno ogni 4 secondi.
    -   Se l'interruttore della batteria è impostato su OFF, l'SDCO invierà 00% per avvisare l'utente. Tieni presente che quando è impostata su OFF, la batteria non verrà caricata quando l'alimentazione CA è collegata e non fungerà nemmeno da fonte di alimentazione di backup quando manca l'alimentazione CA.

8

-   -   Quando viene applicata l'alimentazione CA, la batteria ricaricabile si caricherà contemporaneamente e l'SDCO segnalerà la percentuale della batteria al gateway/pannello di controllo rispettivamente al 20%, 30%, 40%, 50%, 60%, 70% , 80%, 90% e 100%.
    -   Quando l'alimentazione CA viene rimossa o si verifica un'interruzione di corrente, SDCO utilizzerà la batteria ricaricabile integrata e riporterà la percentuale della batteria. Dopo aver riapplicato l'alimentazione CA, l'SDCO riporterà la percentuale di batteria rilevata. Quando la tensione della batteria rilevata è pari o superiore a 4,3 V, l'SDCO riporterà la percentuale della batteria al 60% e inizierà a caricare la batteria. Quando la tensione della batteria rilevata è inferiore a 4,3 V, l'SDCO riporterà rispettivamente la percentuale della batteria e inizierà a caricare la batteria.
-   **Rapporto temperatura/umidità:\[COMANDO_CLASSE_SENSORE_MULTILIVELLO]\[SENSORE_MULTILIVELLO_RAPPORTO]**
    -   L'utente può premere il pulsante una volta per inviare le informazioni sulla temperatura e l'umidità al pannello di controllo.

|  Temperatura: | 01 42 08 CC |
| -------------- | ----------- |

-   Se segnale temperatura 01 42**08CC**viene trasmesso:

**08CC**può essere visualizzato come 0x**08CC**in numero esadecimale. È possibile convertire l'esadecimale in decimale e dividerlo per 100 per verificare i dati della temperatura (in gradi Celsius).

0x08CC=2252=25,52℃.

-   -   Se segnale umidità 05 02**00 nido**viene trasmesso:

**003C**può essere visualizzato come 0x**003C**in numero esadecimale. È possibile convertire l'esadecimale in decimale per verificare il livello di umidità (in percentuale).

003C=0x003C=60%

-   **Test Allarme Fumo/Test Allarme Fumo Disattivato::\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**
    -   L'utente può premere una volta il pulsante per inviare segnali di test allarme fumo e test allarme fumo disattivato alla centrale di controllo.
    -   Test allarme fumo: 00 00 00 FF 01 03 00
    -   Test Allarme Fumo Disattivato: 00 00 00 FF 01 00 01 03
    -   01=tipo allarme; 03=test allarme fumo
-   **Emergenza fumo/Emergenza fumo cancellata:\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**

 Allarme fumo: 00 00 00 FF 01 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Nota: 0B 77 06 00 42 61 73 65 6D 65 6E 74 è quando la posizione è "Seminterrato".

-   Un allarme fumo verrà attivato dopo che la concentrazione di fumo supera la soglia di rilevamento oppure attivato manualmente inviando comandi, l'SDCO può essere silenziato ed entrare in modalità Silenziamento allarme. Per favore riferisci a "_**Silenziamento allarme**" per i dettagli._L'SDCO invierà un report di tacitazione allarme nelle seguenti tre condizioni:

|  Quando la concentrazione di fumo scende sotto la soglia di allarme, l'SDCO invierà:                      | 00 00 00FF 01 06 01 01 |   |   |   |   |
| ---------------------------------------------------------------------------------------------------------- | ---------------------- | - | - | - | - |
|  Quando l'utente preme il pulsante per interrompere l'allarme, l'SDCO invierà:                            |                        |   |   |   |   |
| 00 00 00FF 01 06 01 02                                                                                     |                        |   |   |   |   |
|  Quando l'utente invia un comando di spegnimento della sirena per interrompere l'allarme, l'SDCO invierà: |                        |   |   |   |   |
| 00 00 00FF 01 06 01 03                                                                                     |                        |   |   |   |   |
| Per favore riferisci a "**Comando di controllo accensione/spegnimento sirena**" per dettagli.              |                        |   |   |   |   |

-   -   Nota: se sono attivati ​​più allarmi, verranno inviati rispettivamente gli eventi di tacitazione allarme.
    -   Dopo aver tacitato l'SDCO, se non viene rilevato fumo per 20 tempi di rilevamento continui, l'SDCO trasmetterà un segnale di ripristino: 00 00 00 FF 01 00 01 01.
-   **Emergenza calore/Emergenza calore cancellata:\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**

|  Allarme calore: | 00 00 00 FF | 04 01 | 0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч                   |
| ----------------- | ----------- | ----- | --------------------------------------------------------- |
| Nota:             | 0B 77 06 00 | 42 61 | 73 65 6D 65 6E 74 è quando la posizione è "Seminterrato". |

-   Un allarme di calore verrà attivato dopo che l'SDCO soddisfa la condizione di velocità di aumento o di calore elevato, oppure attivato manualmente inviando comandi, l'SDCO può essere silenziato ed entrare in modalità Silenziamento allarme. Per favore riferisci a "_**Silenziamento allarme**" per i dettagli._L'SDCO invierà un report di tacitazione allarme nelle seguenti tre condizioni:

|  Quando la temperatura scende sotto la soglia di allarme, l'SDCO invierà:                                 | 00 00 00 FF 04 09 01 01 |   |   |   |   |
| ---------------------------------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|  Quando l'utente preme il pulsante per interrompere l'allarme, l'SDCO invierà:                            |                         |   |   |   |   |
| 00 00 00 FF 04 09 01 02                                                                                    |                         |   |   |   |   |
|  Quando l'utente invia un comando di spegnimento della sirena per interrompere l'allarme, l'SDCO invierà: |                         |   |   |   |   |
| 00 00 00FF 01 06 01 03                                                                                     |                         |   |   |   |   |
| Per favore riferisci a "**Comando di controllo accensione/spegnimento sirena**" per dettagli.              |                         |   |   |   |   |

-   -   Nota: se sono attivati ​​più allarmi, verranno inviati rispettivamente gli eventi di tacitazione allarme.
    -   Dopo aver silenziato l'SDCO, se non viene rilevato un calore elevato per 16 tempi di rilevamento continui, l'SDCO trasmetterà un segnale di ripristino: 00 00 00 FF 04 00 01 01.
-   **Emergenza CO/Emergenza CO cancellata:\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**

 Allarme CO: 00 00 00 FF 02 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Nota: 0B 77 06 00 42 61 73 65 6D 65 6E 74 è quando la posizione è "Seminterrato".

-   Un allarme CO verrà attivato dopo che la concentrazione di CO supera la soglia di rilevamento oppure attivato manualmente inviando comandi, l'SDCO può essere silenziato ed entrare in modalità Silenziamento allarme. Per favore riferisci a "_**Silenziamento allarme**" per i dettagli._L'SDCO invierà un report di tacitazione allarme nelle seguenti tre condizioni:

|                                                                              | Quando la concentrazione di CO scende al di sotto di 30 ppm, l'SDCO invierà: | 00 00 00 FF 02 06 01 01 |   |   |   |   |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|                                                                              |                                                                              |                         |   |   |   |   |
| Quando l'utente preme il pulsante per interrompere l'allarme, l'SDCO invierà: | 00 00 00 FF 02 06 01 02                                                      |                         |   |   |   |   |
|                                                                               |                                                                              |                         |   |   |   |   |

**Si prega di notare che un allarme attivato dal superamento della seconda soglia di allarme può essere tacitato premendo il pulsante.**

|  Quando l'utente invia un comando di spegnimento della sirena per interrompere l'allarme, l'SDCO invierà: | 00 00 00FF 01 06 01 03 |   |   |   |
| ---------------------------------------------------------------------------------------------------------- | ---------------------- | - | - | - |
|                                                                                                            |                        |   |   |   |

-   -   Nota: se sono attivati ​​più allarmi, verranno inviati rispettivamente gli eventi di tacitazione allarme.
    -   Dopo aver silenziato l'SDCO, se il CO scende al di sotto di 30 ppm per 10 tempi di rilevamento continui, l'SDCO trasmetterà un segnale di ripristino: 00 00 00 FF 02 00 01 01.
-   **Posizione:**
    -   Quando viene attivato un allarme fumo, un allarme calore o un allarme CO, invierà una notifica con il nome della posizione. Per i modelli collegati in serie, verrà trasmessa anche la posizione preprogrammata.
    -   Se viene attivato un allarme fumo nel seminterrato, 00 00 00 FF 01 01**0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч**verrà inviato, come mostrato nella Tabella 1 di seguito

_**Tabella 1**_

| 1 | V1 | Tipo di allarme    | 0x00 | Non implementato |
| - | -- | ------------------ | ---- | ---------------- |
|   |    |                    |      |                  |
| 2 | V1 | Livello di allarme | 0x00 | Non implementato |
|   |    |                    |      |                  |

9

| 3  | Riservato                  | 0x00            | Campo riservato                          |
| -- | -------------------------- | --------------- | ---------------------------------------- |
|    |                            |                 |                                          |
| 4  | Stato della notifica       | 0xFF            | La segnalazione non richiesta è attivata |
|    |                            |                 |                                          |
| 5  | Tipo di notifica           | 0x01            | Allarme antincendio                      |
|    |                            |                 |                                          |
| 6  | Evento                     | 0x01            | Rilevato fumo                            |
|    |                            |                 |                                          |
| 7  | Lunghezza parametri evento | 0x0B            | Lunghezza parametro evento = 11          |
|    |                            |                 |                                          |
| 8  | Evento Parm 1              | 0spazzare       | Nodo e posizione ID CC del nodo          |
|    |                            |                 |                                          |
| 9  | Evento Parm 2              | 0x06            | ID comando report posizione nodo         |
|    |                            |                 |                                          |
| 10 | Evento Parm 3              | 0x00            | Cmd Parm: Char = ASCII                   |
|    |                            |                 |                                          |
| 11 | Evento Parm 4              | 0x42            | Cmd Parm: Posizione nodo Char 1 = B      |
|    |                            |                 |                                          |
| 12 | Evento Parm 5              | 0x61            | Cmd Parm: Posizione nodo Char 2 = a      |
|    |                            |                 |                                          |
| 13 | Evento Parco 6             | 0 come spazzata | Cmd Parm: Posizione del nodo Char 3 = s  |
|    |                            |                 |                                          |
| 14 | Evento Parco 7             | 0x65            | Cmd Parm: Posizione nodo Char 4 = e      |
|    |                            |                 |                                          |
| 15 | Evento Parm 8              | 0x6D            | Cmd Parm: Posizione nodo Char 5 = m      |
|    |                            |                 |                                          |
| 16 | Evento Parco 9             | 0x65            | Cmd Parm: Posizione del nodo Char 6 = e  |
|    |                            |                 |                                          |
| 17 | Evento Parco 10            | 0x6E            | Cmd Parm: Posizione nodo Char 7 = n      |
|    |                            |                 |                                          |
| 18 | Evento Parco 11            | 0x74            | Cmd Parm: Posizione del nodo Char 8 = t  |
|    |                            |                 |                                          |

-   **Rapporto apertura/chiusura manomissione:\[COMANDO_CLASSE_NOTIFICA]\[NOTIFICA_RAPPORTO]**
    -   L'SDCO è protetto da un interruttore antimanomissione che viene compresso quando l'SDCO viene agganciato alla staffa di montaggio. Quando l'SDCO viene rimosso dalla staffa di montaggio, l'interruttore antimanomissione verrà attivato e l'SDCO invierà un segnale di apertura antimanomissione al pannello di controllo del sistema per ricordare all'utente questa condizione.
    -   Apertura antimanomissione: 00 00 00 FF 07 03 00 00
    -   Dopo aver agganciato l'SDCO alla staffa di montaggio, invierà un segnale di chiusura antimanomissione alla centrale di controllo.

|  Chiusura antimanomissione: | 00 00 00FF 07 00 01 03 |
| ---------------------------- | ---------------------- |

-   **Sensore PIR**
    -   -   L'SDCO trasmetterà il segnale al pannello di controllo se viene rilevato un movimento all'interno della copertura di rilevamento IR.
    -   PIR attivo: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74
    -   Nota: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74 è quando la posizione è "Seminterrato".
    -   Ripristino PIR: 00 00 00 FF 07 00 01 07
-   **Controllo Scena/Sirena:\[COMANDO_CLASSE_SCENA_ATTIVAZIONE]\[SCENA_ATTIVAZIONE_SET] (per modelli collegati in serie):**
    -   ID scena: tipo di allarme (Tabella 2)
    -   Durata oscuramento: 0x00~0x14

_**Tavolo 2**_

| Comunque~7 | Pezzo 4 | Pezzo 3       | Pezzo 2    | Pezzo 1    | Bit 0      |   |
| ---------- | ------- | ------------- | ---------- | ---------- | ---------- | - |
|            |         |               |            |            |            |   |
|            |         |               |            |            |            |   |
|            |         |               |            |            | Allarme SD |   |
| 0          | Bug     | Allarme acqua | Allarme CO | Allarme HD |            |   |
|            |         |               |            |            |            |   |

-   Nome della posizione /Bit4~0/Num, come mostrato nella Tabella 3 di seguito

_**Tabella 3**_

-   -   Suggerimento inglese

| Numero (esadecimale) | Nome del luogo             | Numero (esadecimale) | Nome del luogo             |
| -------------------- | -------------------------- | -------------------- | -------------------------- |
|                      |                            |                      |                            |
| 0                    | Seminterrato               | B                    | Asilo                      |
| 1                    | Sala                       | C                    | Toilette                   |
| 2                    | Ufficio                    | D                    | Locale tecnico             |
| 3                    | Camera da letto principale | E                    | Armadio                    |
| 4                    | Camera da letto            | F                    | Soggiorno mansardato       |
| 5                    | Stanza degli ospiti        | 10                   | Soggiorno nel seminterrato |
| 6                    | Cucina                     | 11                   | Scala                      |
| 7                    | Sala da pranzo             | 12                   | Box auto                   |
| 8                    | Soggiorno                  | 13                   | Appartamento in affitto    |
| 9                    | Lavanderia                 | 14                   | Nessuna posizione          |
| UN                   | Attico                     |                      |                            |

-   Suggerimento norvegese

Numero (esadecimale)

Nome del luogo

Numero (esadecimale)

10

Nome del luogo

| 0  | Soggiorno                  | B  | Ripostiglio       |
| -- | -------------------------- | -- | ----------------- |
| 1  | Cucina                     | C  | Toilette          |
| 2  | Corridoio                  | D  | Sala Tecnica      |
| 3  | Camera da letto principale | E  | Armadio           |
| 4  | Camera dei bambini         | F  | Di sopra          |
| 5  | Camera da letto            | 10 | Piano inferiore   |
| 6  | Cenare                     | 11 | Scala             |
| 7  | Lavanderia                 | 12 | Box auto          |
| 8  | Attico                     | 13 | Unità di noleggio |
| 9  | Ufficio                    | 14 | L'edificio        |
| UN | Seminterrato               |    |                   |

-   -   -   Per attivare il campanello della porta, impostare ID scena: 0x00 e Durata attenuazione: 0xF1.
        -   Per interrompere la sirena e i messaggi vocali generati da questo comando, impostare ID scena: 0x00 e Durata oscuramento: 0x00.**Si prega di notare che questo comando NON PUÒ essere utilizzato per interrompere la sirena e i messaggi vocali di un allarme reale.**
        -   Per interrompere la sirena e i messaggi vocali di un allarme reale, impostare ID scena: 0xFF e Durata attenuazione: 0x00.
-   **Controllo accensione/spegnimento della sirena:\[COMANDO_CLASSE_DI BASE]\[DI BASE_IMPOSTATO]**
    -   -   La sirena di SDCO può essere controllata utilizzando i comandi On/Off del Set Base (solo per allarme fumo, senza indicazione della posizione).
        -   Per accendere la sirena utilizzando questo comando impostare Basic Set: 0xFF. Il modello di suono della sirena è lo stesso di un rilevatore di fumo.
        -   Per spegnere la sirena utilizzando questo comando impostare Basic Set: 0x00.**Si tenga presente che questo comando NON PUÒ essere utilizzato per fermare la sirena di un allarme reale.**L'SDCO entrerà in modalità Silenziamento allarme e invierà il segnale di ripristino dell'allarme dopo il periodo.
    -   **Indicatore**Controllo**:\[COMANDO_CLASSE_INDICATORE]\[INDICATORE_IMPOSTATO]**
        -   L'indicatore LED di SDCO può essere controllato utilizzando i comandi Indicator Set.
        -   I seguenti comandi possono essere utilizzati per impostare il comando indicatore:

|   | 7 |           |   | 6                                                           | 5                              | 4               | 3 |   | 2 |   | 1 | 0 |
| - | - | --------- | - | ----------------------------------------------------------- | ------------------------------ | --------------- | - | - | - | - | - | - |
|   |   |           |   |                                                             |                                |                 |   |   |   |   |   |   |
|   |   |           |   | Classe di comando = COMANDO_CLASSE_INDICATORE               |                                |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             |                                |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             | Comando = INDICATORE_IMPOSTATO |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             |                                |                 |   |   |   |   |   |   |
|   |   |           |   | Valore indicatore 0 (ID indicatore 0=00, ID proprietà 0=01) |                                |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             |                                |                 |   |   |   |   |   |   |
|   |   | Riservato |   |                                                             | Conteggio oggetti indicatore   |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             |                                |                 |   |   |   |   |   |   |
|   |   |           |   |                                                             |                                | ID indicatore 1 |   |   |   |   |   |   |

ID proprietà 1

Valore 1

-   Indicatore impostato su (0xFF) --- funzione indicatore attivata
-   Indicatore disattivato (0x00) --- funzione indicatore disattivata
-   Conteggio oggetti indicatore (0x01) --- per controllare l'ID indicatore LED 1
-   ID indicatore (0x43) --- indicazione del pulsante

|   | Identificativo dell'indicatore |   |   | Descrizione           |   |                                                      | Aspetto e utilizzo |   |   |
| - | ------------------------------ | - | - | --------------------- | - | ---------------------------------------------------- | ------------------ | - | - |
|   |                                |   |   |                       |   |                                                      |                    |   |   |
|   |                                |   |   |                       |   |                                                      |                    |   |   |
|   | 0x43                           |   |   | PULSANTE1_INDICAZIONE |   | Utilizzare per attirare l'attenzione sul pulsante 1. |                    |   |   |

-   ID indicatore (0x44) --- Riavvio dell'MCU

|                                                           |   | Identificativo dell'indicatore |   |   | Descrizione           |                      |                                                     | Aspetto e utilizzo |                                                  |               |   |   |   |
| --------------------------------------------------------- | - | ------------------------------ | - | - | --------------------- | -------------------- | --------------------------------------------------- | ------------------ | ------------------------------------------------ | ------------- | - | - | - |
|                                                           |   |                                |   |   |                       |                      |                                                     |                    |                                                  |               |   |   |   |
|                                                           |   |                                |   |   |                       |                      |                                                     |                    |                                                  |               |   |   |   |
|                                                           |   | 0x44                           |   |   | PULSANTE2_INDICAZIONE |                      | Utilizzare per attirare l'attenzione sul pulsante 2 |                    |                                                  |               |   |   |   |
|  ID proprietà (0x00-0xFE) --- LED acceso_orari di riposo |   |                                |   |   |                       |                      |                                                     |                    |                                                  |               |   |   |   |
|                                                           |   | Valore                         |   |   |                       | Descrizione generale |                                                     |                    |                                                  | Uso specifico |   |   |   |
|                                                           |   | 0x04                           |   |   |                       | SU_Spento_Cicli      | Numero di On_Spento_Periodo da eseguire             |                    |                                                  |               |   |   |   |
|                                                           |   |                                |   |   |                       |                      |                                                     |                    | 0x00 – 0xFE = 0-254 volte                        |               |   |   |   |
|                                                           |   |                                |   |   |                       |                      |                                                     |                    | 0xFF = Esegui fino all'arresto tramite On_Spento |               |   |   |   |
|                                                           |   |                                |   |   |                       |                      |                                                     |                    |                                                  |               |   |   |   |

 Se desideri che l'SDCO lampeggi 5 volte per mostrare la sua posizione, invia: 0xFF 01 43 04 05

 Se desideri che l'SDCO smetta di lampeggiare una volta che sei a conoscenza della sua posizione, invia: 0x00 01 43 04 05  Per maggiori dettagli, fare riferimento a “_**SDS-13781-1 Specifica della classe di comando dell'applicazione Z-Wave**_”.

**Configurazioni:\[COMANDO_CLASSE_CONFIGURAZIONE]\[CONFIGURAZIONE_IMPOSTATO]**

 Numero parametro: 0x01~0x0A

 Dimensioni: 0x01

 Riservato: 0x00

 Impostazione predefinita: 0x00

 Valore di configurazione: 0xXX

| Numero del parametro | Valore di configurazione |
| -------------------- | ------------------------ |
|                      |                          |
| 0x01, Sensibilità    | 0x01~0x08 (0~70),        |
|                      | predefinito: 0x04        |

0x02, Periodo di verifica

0x00~0x96 (0~150 secondi),

11

|                                      | predefinito 0x00                  |
| ------------------------------------ | --------------------------------- |
|                                      |                                   |
| 0x03, versione hardware SD           | 0/1 (0:vecchio, 1:nuovo) sempre 1 |
|                                      |                                   |
| 0x04, Soglia di temperatura          | 4~50 (2~25 gradi),                |
|                                      | predefinito: 4                    |
|                                      |                                   |
| 0x05, Orario rapporto automatico     | 0~240 minuti                      |
|                                      | predefinito: 30                   |
|                                      |                                   |
| 0x06, Posizione                      | 0~20                              |
| (per favore riferisci a_Tabella 3_)  |                                   |
|                                      |                                   |
| 0x07, Regola la temperatura          | +127~-128                         |
|                                      | (0,1 gradi per ciascun valore)    |
|                                      |                                   |
| 0x08, Regola l'umidità               | +127~-128                         |
|                                      | (1% per ciascun valore)           |
|                                      |                                   |
| 0x09, guasto hardware                | 0x00~0xFF                         |
| (per favore riferisci a_Tabella 4_   |                                   |
| errore hardware elencato di seguito) |                                   |
|                                      |                                   |
| 0x0A, posticipazione temporanea      | 0~7                               |
| (per favore riferisci a_Tabella 5_)  |                                   |
|                                      |                                   |
| 0x0B, Lingua                         | 01~05                             |
|                                      | 01: inglese                       |
|                                      | 02: norvegese (predefinito)       |
|                                      | 03: svedese                       |
|                                      | 04: finlandese                    |
|                                      | 05: danese                        |
|                                      |                                   |

_**Tabella 4**_0x09 (guasto hardware)

| Sta arrivando                                                                     | Bit6 | Comunque     |        |             | Bit4        | l'ho comprato                                         | Beta      | Bit1      | Bit0      |   |
| --------------------------------------------------------------------------------- | ---- | ------------ | ------ | ----------- | ----------- | ----------------------------------------------------- | --------- | --------- | --------- | - |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
| X                                                                                 | X    | AC           |        | Batteria SW | Manomettere | CO                                                    | HD        | SD        |           |   |
|                                                                                   |      | 0:Ripristina |        |             | 0:attivato  | 1:Apri                                                | 1: Rotto  | 1: Rotto  | 1: Rotto  |   |
|                                                                                   |      | 1: Fallito   |        |             | 1: Spento   | 0:Chiudi                                              | 0:Normale | 0:Normale | 0:Normale |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|  SD rotta: se Bit0=1, invierà un comando di notifica “00 00 00 FF 01 FE 00”      |      |              |        |             |             |                                                       |           |           |           |   |
|  HD rotto: se Bit1=1, invierà un comando di notifica “00 00 00 FF 04 FE 00”      |      |              |        |             |             |                                                       |           |           |           |   |
|  CO interrotto: se Bit2=1, invierà un comando di notifica “00 00 00 FF 02 FE 00” |      |              |        |             |             |                                                       |           |           |           |   |
| _**Tabella 5**_0x10 (Snooze temporaneo)                                          |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | Valore |             |             | Durata                                                |           |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 0      |             |             | Disabilita (il timer verrà interrotto immediatamente) |           |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 1      |             |             |                                                       | 5 minuti  |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 2      |             |             |                                                       | 30 minuti |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 3      |             |             |                                                       | 60 minuti |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 4      |             |             |                                                       | 8 ore     |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 5      |             |             |                                                       | 12 ore    |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 6      |             |             |                                                       | 24 ore    |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |
|                                                                                   |      |              | 7      |             |             |                                                       | 36 ore    |           |           |   |
|                                                                                   |      |              |        |             |             |                                                       |           |           |           |   |

-   **Ripristino delle impostazioni di fabbrica**

Se il dispositivo viene appreso e si tiene premuto il pulsante Test per 20 secondi insieme a 3 segnali acustici per il ripristino delle impostazioni di fabbrica, invierà

\[COMANDO_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE]\[DISPOSITIVO_RIPRISTINA_LOCALMENTE_NOTIFICA]

 Il dispositivo verrà automaticamente escluso per la nuova versione di PC Controller.

12
