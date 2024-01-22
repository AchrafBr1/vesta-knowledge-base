# VESTA032

Rilevatore di fumo e monossido di carbonio (serie SDCO-1-F1)

introduzione

La serie SDCO-1-F1 è un rilevatore di fumo e monossido di carbonio. È in grado di inviare segnali wireless al pannello di controllo al rilevamento di particelle di fumo o monossido di carbonio. L'SDCO-1 è progettato per essere montato sul soffitto o sulla parte superiore delle scale dove il fumo si concentrerebbe per attivare tempestivamente l'allarme e proteggere la casa dai rischi di incendio.

La serie SDCO-1 comprende i seguenti modelli:

| **Nome del modello** | **Calore** | **2 vie** | **Connessione seriale** |
| -------------------- | ---------- | --------- | ----------------------- |
| SDCO-1-F1            |            |           |                         |
| SDCO-1H-SC           | In         |           | In                      |
| SDSU-1-F1-2F         |            | In        |                         |
| SDCO-1H-F1           | v          |           |                         |
| SDSU-1H-F1-2F        | In         | In        |                         |

Identificazione delle parti

![](<.gitbook/assets/0 (11).png>)

1.  **Pulsante di prova**

-   Premere una volta il pulsante per inviare un segnale di test/apprendimento.
-   Premere il pulsante una volta durante l'allarme per accedere alla modalità di silenzio dell'allarme.
-   Tieni premuto il pulsante per 10 secondi. Rilasciare il pulsante quando l'SDCO emette 2 bip per accedere alla calibrazione del fumo e al CO

processo di autodiagnosi.

-   Premere due volte il pulsante per scaricarla completamente prima di inserire nuove batterie.

1.  **Indicatore LED**

**LED rosso**

-   Si accende brevemente: trasmissione del segnale di test/apprendimento.
-   Lampeggio veloce: allarmante.
-   Lampeggia ogni secondo: in modalità silenzio allarme.
-   Lampeggia ogni 2 secondi: processo di riscaldamento e calibrazione in corso.

**LED ambra**

-   Lampeggia ogni 5 secondi: malfunzionamento del dispositivo
-   Lampeggia ogni 45 secondi: condizione di batteria scarica

**LED rosso e ambra (arancione guardando dall'esterno)**

-   Lampeggia ogni 4 secondi: le batterie sono estremamente scariche e devono essere sostituite.

1.  **Cicalino**
2.  **Fori di montaggio (per ganci)**

I ganci della staffa di montaggio possono agganciarsi ai relativi fori di montaggio.

1.  **Staffa di fissaggio**
2.  **Coperchio del vano batteria**
3.  **Vite di fissaggio del coperchio del vano batteria**
4.  **Tacche**
5.  **Porta di aggiornamento firmware (USB tipo C)**

-   Solo per aggiornamento firmware con cavo personalizzato.**Notare che:**L'uso improprio del normale cavo USB di tipo C può causare il malfunzionamento del dispositivo.

Caratteristiche

-   Rilevamento batteria e batteria scarica
-   L'SDCO-1 utilizza tre batterie al litio EL123AP come fonte di alimentazione. Le batterie sono incluse nella confezione.
-   L'SDCO è dotato di un meccanismo infallibile che impedisce la chiusura del coperchio senza prima installare la batteria.
-   Quando la batteria dell'SDCO è scarica, verrà trasmesso un segnale di batteria scarica insieme alle normali trasmissioni del segnale. Il LED ambra lampeggerà con un segnale acustico a basso volume una volta ogni 45 secondi.
-   Sia il LED rosso che quello ambra lampeggeranno una volta ogni 4 secondi quando le batterie sono estremamente scariche e devono essere sostituite.
-   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte il pulsante Test per scaricarle completamente prima di inserire nuove batterie.
-   Iniziare

**Passo 1:**Utilizzare un cacciavite Phillips per allentare la vite di fissaggio del vano batteria e rimuovere il coperchio del vano batteria.

**Passo 2:**Inserire 3 batterie nel vano batterie.

**Passaggio 3:**Il rilevatore SDCO emetterà 2 brevi segnali acustici e inizierà il processo di riscaldamento**1**minuto. Il LED lampeggerà ogni 2 secondi.

**Passaggio 4.**Durante il periodo di 1 minuto, impara nel rilevatore di fumo.

1.  Premere una volta il pulsante di apprendimento/test per trasmettere un codice di apprendimento del sensore IR.
2.  Tenere premuto il pulsante di apprendimento/test per 3 secondi per trasmettere un codice di apprendimento del sensore di fumo/temperatura**(il passaggio a. e il passaggio b. sono entrambi richiesti per i modelli collegati in serie)**.

Se la Centrale riceve il segnale, il Rilevatore di Fumo emetterà un segnale acustico a 2 toni. Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.

**Passaggio 5:**Allo scadere del periodo di riscaldamento di 1 minuto, il rilevatore SDCO emetterà un segnale acustico per indicare che sta entrando nel processo di calibrazione. IL

il processo di calibrazione richiede 1~7 minuti; il LED continuerà a lampeggiare durante la calibrazione.

**Passaggio 6:**Una volta completata la calibrazione, il rilevatore SDCO emetterà un suono a 2 toni e il LED smetterà di lampeggiare per indicare che è ora sotto

operazione normale. Se la calibrazione fallisce, il rilevatore SDCO emetterà segnali acustici continui.

-   _**Rilevamento allarme**_

Il rilevatore SDCO attiverà l'allarme antincendio quando viene attivata la funzione di rilevamento del fumo o di rilevamento del calore elevato. Quando viene attivato un allarme, il rilevatore SDCO trasmetterà il segnale di allarme e attiverà l'allarme con il cicalino integrato. Il LED rosso lampeggerà rapidamente.

**Rilevazione del fumo:**

-   Il rilevatore SDCO controlla la concentrazione di fumo ogni 8 secondi
-   Ogni volta che la concentrazione di fumo supera la soglia di rilevamento, SDCO invierà un segnale attivo al pannello di controllo e attiverà l'allarme.
-   Se la concentrazione di fumo persiste, il Rivelatore SDCO continuerà ad inviare il segnale attivo ogni 2 minuti alla Centrale.
-   Se non viene rilevato fumo per 20 tempi di rilevamento continui, l'SDCO trasmetterà un segnale di ripristino e interromperà l'allarme.

**Rilevamento del calore (solo per i modelli SDCO-1H-F1 e SDCO-1H-F1-2W):**

-   Il rilevatore SDCO controlla la temperatura ogni 10 secondi.
-   L’allarme verrà attivato nelle seguenti condizioni:

\-Quando la temperatura aumenta di 8,25°C al minuto (velocità di aumento).

\-Quando la temperatura supera i 57,25°C (calore elevato).

-   Se non viene rilevato alcun calore elevato per 20 tempi di rilevamento continui, l'SDCO trasmetterà un segnale di ripristino e interromperà l'allarme.
-   Se l'allarme è stato attivato da una condizione di calore elevato (57,25°C), la temperatura deve scendere sotto i 49°C affinché il rilevatore interrompa l'allarme.
-   Se l'allarme è stato attivato dalla condizione di velocità di aumento (8,25°C al minuto o più), la temperatura deve scendere a 4°C al di sotto della temperatura massima rilevata affinché il rilevatore interrompa l'allarme.

**Rilevamento del monossido di carbonio:**

-   Il sensore di CO controlla il livello di concentrazione di CO ogni 16 secondi. Se il livello di concentrazione supera la soglia di rilevamento, il rilevatore SDCO trasmetterà un segnale di allarme e attiverà l'allarme con il cicalino integrato.
-   Il sensore di CO è dotato di funzione di autodiagnosi e controlla regolarmente la salute o lo stato del sensore ogni 12 ore.
-   L'allarme verrà attivato dopo che viene rilevata la concentrazione di CO in base alla durata di tempo nella tabella seguente: (conforme allo standard EN-50291)

| **Livello di concentrazione di CO** | **Tempo impiegato prima di allarmare** |
| ----------------------------------- | -------------------------------------- |
| 30 +/- 10% ppm                      | N / A                                  |
| 50 +/- 10% ppm                      | 60~90 minuti                           |
| 100 +/- 10% ppm                     | 10~40 minuti                           |
| 300 +/- 10% ppm                     | Meno di 3 minuti                       |

-   L'allarme verrà attivato una volta rilevata la concentrazione di CO in base al periodo di tempo indicato nella tabella seguente: (conforme allo standard UL-2034)

| **Livello di concentrazione di CO** | **Tempo impiegato prima di allarmare** |
| ----------------------------------- | -------------------------------------- |
| 30 +/- 3% ppm                       | N / A                                  |
| 70 +/- 5% ppm                       | N / A                                  |
| 70 +/- 5% ppm                       | 60~240 minuti                          |
| 150 +/- 5% ppm                      | 10~50 minuti                           |
| 400 +/- 10% ppm                     | 4~15 minuti                            |

-   Una volta che il livello di concentrazione di CO supera la soglia e persiste per il periodo di tempo elencato nella tabella sopra, il rilevatore SDCO trasmetterà il segnale al pannello di controllo e lancerà l'allarme con la sirena incorporata.
-   Test del rilevatore SDCO

Premendo il pulsante Test sul rilevatore SDCO, è possibile verificare se l'SDCO funziona normalmente.

-   Se il rilevatore SDCO funziona normalmente, il LED rosso lampeggerà una volta seguito da un segnale acustico a 2 toni.
-   Se vengono emessi tre segnali acustici bitonali (DO-DI DO-DI DO-DI), significa che il sensore di fumo è fuori servizio.
-   Se vengono emessi 5 bip (DO-Bi-Bi-Bi-DO), significa che il sensore di calore è fuori servizio.
-   Se vengono emessi 7 bip (Bi-Bi-Bi-DO-Bi-Bi-Bi), significa che il sensore CO è fuori servizio.
-   _**Supervisione**_
-   Per i modelli SDCO-1(H)-F1, il rilevatore SDCO trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione ogni 30-50 minuti.
-   Per i modelli SDCO-1(H)-F1-2W, il rilevatore SDCO trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione ogni 90-110 minuti.
-   Se la centrale di controllo non riceve il segnale dal rilevatore di fumo per un periodo di tempo preimpostato, determinerà che il rilevatore di fumo è fuori servizio.
-   _Connessione seriale__(solo modello collegato in serie)_
-   Il rilevatore di fumo è collegato in serie con altri rilevatori di fumo nel sistema di allarme. Quando un rilevatore di fumo attiva l'allarme, il pannello di controllo avviserà anche gli altri rilevatori di fumo di attivare l'allarme anche se non hanno ancora rilevato il fumo. La durata dell'allarme sarà conforme all'impostazione del pannello di controllo.
-   Non è possibile premere il pulsante funzione per silenziare l'allarme attivato da altri rilevatori di fumo.
-   L'allarme verrà ripristinato solo dopo un timeout di 3 minuti o finché l'altro rilevatore di fumo che ha attivato l'allarme non trasmette un segnale di ripristino.
-   Silenziamento allarme
-   Quando il rilevatore di fumo è in allarme, premendo il pulsante Test si metterà il rilevatore di fumo in modalità Silenziamento allarme per silenziare l'allarme per 9 minuti. Il cicalino smetterà di suonare solo dopo che l'allarme è stato attivato per almeno 1 minuto. Se il pulsante viene premuto prima che l'ora dell'allarme raggiunga 1 minuto, il rilevatore di fumo attenderà fino a quando l'ora dell'allarme raggiunge 1 minuto prima di silenziare l'allarme.
-   Durante il periodo di silenzio allarme di 9 minuti, il LED rosso lampeggerà una volta al secondo. Il rilevatore di fumo continuerà a monitorare la concentrazione di fumo durante il periodo di silenzio dell'allarme:

1.  Una volta scaduto il periodo di silenziamento dell'allarme di 9 minuti, se la concentrazione di fumo è scesa al di sotto della soglia di allarme, il rilevatore di fumo emetterà un segnale acustico a 2 toni e tornerà al funzionamento normale senza far suonare l'allarme.
2.  Se la concentrazione di fumo supera ancora la soglia di allarme, il rilevatore di fumo inizierà nuovamente a emettere allarme.
3.  Se la concentrazione di fumo continua ad aumentare durante il periodo di silenziamento dell'allarme e supera una seconda soglia di allarme, il rilevatore di fumo inizierà nuovamente ad emettere allarme. Un allarme attivato dal superamento della seconda soglia di allarme non può essere silenziato premendo il pulsante di test.

-   Ricalibrazione

L'SDCO calibrerà il sensore del rilevatore di fumo ogni volta che viene applicata l'alimentazione per garantire una sensibilità al fumo ottimale. Dopo l'installazione, le condizioni operative del rilevatore di fumo possono variare nel tempo, il che potrebbe influire sulla sua funzione di rilevamento del fumo e richiedere la ricalibrazione. Esistono due modi per ricalibrare il rilevatore di fumo: calibrazione automatica e calibrazione manuale.

**Calibrazione automatica:**

-   Dopo l'accensione, il rilevatore di fumo eseguirà la calibrazione automatica dopo 4 ore.
-   Dopo la prima calibrazione automatica, il rilevatore di fumo eseguirà la calibrazione automatica ogni mese. Durante il processo di calibrazione automatica, il rilevatore di fumo non emetterà alcun suono.
-   Se la calibrazione automatica fallisce, il LED ambra lampeggerà ogni secondo insieme a segnali acustici continui e il rilevatore di fumo trasmetterà un segnale di calibrazione fallita.
-   Quando la calibrazione automatica del rilevatore di fumo fallisce, la funzione di allarme fumo continuerà a funzionare normalmente utilizzando il valore di soglia preso dall'ultima calibrazione riuscita.

**Calibrazione manuale:**

-   La calibrazione manuale può essere eseguita in qualsiasi momento, se lo si desidera:

1.  Tenere premuto il pulsante Impara/Test per 10 secondi e rilasciarlo quando il rilevatore di fumo emette 2 segnali acustici.
2.  Il rilevatore di fumo entrerà nel processo di calibrazione. L'indicatore LED lampeggerà ogni 2 secondi.
3.  Una volta terminata la ricalibrazione, il rilevatore di fumo emetterà due rapidi segnali acustici per indicare. Il LED si spegnerà.
4.  Se il processo di calibrazione fallisce, il rilevatore di fumo emetterà un suono di allarme. Rimuovere e reinserire la batteria per riavviare nuovamente il processo.

![100-2](<.gitbook/assets/1 (15).png>)Installazione

-   Linee guida per l'installazione
-   It is recommended that the installation site be in the center area of the ceiling.
-   L'altezza di montaggio ideale per il rilevatore SDCO è compresa tra 2,4 e 3 metri. Il montaggio a una distanza superiore a 3 metri può influire sulle prestazioni di rilevamento.
-   Non posizionare il rilevatore nelle seguenti posizioni:
-   La cucina – Il fumo proveniente dalla cucina potrebbe causare un allarme indesiderato.
-   ![100-3](<.gitbook/assets/2 (18).png>)Vicino a ventilatori, lampade fluorescenti o apparecchiature di condizionamento dell'aria: le correnti d'aria provenienti da essi possono influenzare la sensibilità del rilevatore.
-   Vicino alle travi del soffitto o sopra un armadio: l'aria stagnante in queste aree può influire sulla sensibilità del rilevatore.
-   Nella parte superiore di un soffitto con struttura ad “A”.
-   Raccomandazione per l'installazione
-   **Limitazioni**
-   Non installare il rilevatore SDCO esposto alla luce solare diretta.
-   Evitare di installare il rilevatore SDCO in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
-   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
-   Non puntare direttamente verso fonti di calore, ad es. Fuochi o caldaie e non sopra i termosifoni.
-   Montaggio del rilevatore SDCO

**Passo 1.**Posizionare il rilevatore SDCO nella posizione di montaggio desiderata e utilizzare la funzione Test di portata per assicurarsi che il rilevatore SDCO possa essere ricevuto dal pannello di controllo nella posizione di montaggio.

**Passo 2.**Il rilevatore SDCO è dotato di una staffa di montaggio per l'installazione a soffitto. La staffa offre flessibilità bidirezionale.

**Passaggio 3.**Utilizzare i 4 fori sulla staffa come dima per praticare i fori e inserire i tasselli, se necessario.

**Passaggio 4.**L'utente può ruotare la staffa di montaggio in senso orario o antiorario per bloccare il gancio. Assicurarsi che i tasselli siano a filo con la superficie di montaggio.

**Passaggio 5.**Quando la posizione è soddisfacente, avvitare la staffa di montaggio al soffitto.

**Passaggio 6.**Rimuovere accuratamente la polvere, altrimenti potrebbe sporcare il sensore e impedirne il corretto funzionamento in caso di emergenza.

**Passaggio 7.**L'SDCO ha tre tacche sul retro della copertina per facilitarne l'identificazione, come mostrato di seguito.

![](<.gitbook/assets/3 (17).png>)

**Passaggio 8.**Tenere il rilevatore SDCO con particolare attenzione e allineare le tre tacche con i ganci sulla staffa di montaggio.

**Passaggio 9.**Ruotare il rilevatore SDCO in senso orario per bloccare il gancio. L'installazione è ora completa.
