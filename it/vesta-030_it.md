# VESTA030

**Ripetitore (RP-29)**

Il Ripetitore è progettato per aumentare l'efficacia e la versatilità del sistema di allarme. È un dispositivo che rende il tuo sistema più potente aumentando la massima distanza possibile tra l'Unità Principale (Pannello di Controllo) e i Dispositivi.

-   **Identificazione delle parti**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 20140415.jpg](<.gitbook/assets/0 (5) (1).jpeg>)

1.  **LED di alimentazione (verde)**

**SU**– Alimentato da un alimentatore o da una batteria ricaricabile

**Veloce**– Batteria ricaricabile quasi scarica

1.  **LED modalità (giallo)**

**SU**– Il ripetitore è in modalità apprendimento (pannello) o modalità cancellazione

**Veloce**(1 lampeggio al secondo) – Il ripetitore è in modalità Walk Test

**Flash lento**(1 lampeggio ogni 2 secondi) – Il ripetitore è in modalità di apprendimento (dispositivo)

1.  **Trasmissione: LED di ricezione (blu)**

Il LED blu si accende quando il ripetitore riceve una trasmissione di segnale

1.  **Trasmissione: LED di trasmissione (rosso)**

Il LED rosso si accende quando il ripetitore trasmette un segnale.

1.  **Blocco interruttori funzionali**
2.  **Pulsante di prova**
3.  **Interruttore della batteria**
4.  **Copertura rimovibile**
5.  **Interruttore antimanomissione**
6.  **Foro di montaggio**
7.  **Jack di alimentazione CC**
8.  **Staffa di fissaggio**

-   **Alimentazione elettrica**

Per il collegamento a una presa di corrente a muro è necessario un adattatore di alimentazione. Assicurarsi di utilizzare solo un adattatore con la tensione CA appropriata per evitare danni ai componenti. Per alimentare il ripetitore viene generalmente utilizzato un adattatore di alimentazione con uscita CC 12 V 1 A.

**Applicazione dell'adattatore di alimentazione:**

Per collegare l'adattatore di alimentazione:

1.  Individua l'alimentatore e collegalo al jack di alimentazione CC.
2.  Collega l'alimentatore a una presa di corrente a muro.
3.  Il ripetitore emetterà un segnale acustico lungo e il LED verde si accenderà.

**Guasto CA/Ripristino CA:**

Il ripetitore invierà un segnale di guasto CA al pannello di controllo quando l'adattatore di alimentazione viene scollegato per 30-60 secondi. Quando l'adattatore di alimentazione viene ricollegato per 30-60 secondi, il ripetitore invierà un segnale di ripristino CA al pannello di controllo.

**Batteria ricaricabile:**

Oltre all'adattatore, all'interno del ripetitore è presente una batteria ricaricabile che funge da alimentazione di riserva in caso di interruzione di corrente.

Quando l'adattatore di alimentazione è collegato al jack di alimentazione CC, far scorrere l'interruttore della batteria in posizione ON in modo che l'adattatore di alimentazione fornisca alimentazione al ripetitore e allo stesso tempo ricarichi la batteria. Per caricare completamente la batteria sono necessarie circa 72 ore.

Quando l'adattatore di alimentazione è scollegato, il ripetitore sarà alimentato dalla batteria ricaricabile.

Il ripetitore può rilevare la tensione della batteria. Quando la tensione della batteria è bassa, il LED verde lampeggerà per indicare lo stato di batteria scarica.

-   **Blocco interruttori funzionali**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 switch block.jpg](<.gitbook/assets/1 (2) (1).jpeg>)Il blocco interruttori funzionali determina in quale modalità si trova il ripetitore. Un interruttore in posizione alta indica (**SU**) Modalità. Allo stesso modo, un interruttore in posizione abbassata indica il (**SPENTO**) Modalità.

|                    | Funzione                                  | SU                                      | SPENTO                       |
| ------------------ | ----------------------------------------- | --------------------------------------- | ---------------------------- |
| DIP-interruttore 1 | Impara il dispositivo                     | Modalità di apprendimento (Dispositivo) | Modalità normale             |
| DIP-interruttore 2 | Test di portata o di camminata            | Modalità test di camminata              | Modalità normale             |
| DIP-interruttore 3 | Ripristino delle impostazioni di fabbrica | Modalità Cancella                       | Modalità normale             |
| DIP-interruttore 4 | Impara nel Pannello di controllo          | Modalità di apprendimento (pannello)    | Modalità normale             |
| DIP-interruttore 6 | Impostazione unidirezionale/bidirezionale | A due vie                               | Senso Unico                  |
| DIP-interruttore 8 | Funzione antimanomissione                 | disattivare                             | Modalità normale (abilitata) |

I DIP Switch 5 e 7 sono riservati.

\\<Note>

-   Modificare l'impostazione dell'interruttore DIP 1-4 quando il ripetitore è alimentato, poiché la modifica dell'interruttore DIP 1-4 è valida solo quando il ripetitore è alimentato. Ad esempio, il DIP Switch 3 viene fatto scorrere sulla posizione On quando il ripetitore è spento. Quando il ripetitore è acceso, NON entrerà in modalità Cancella. Tuttavia, se il DIP Switch 3 viene fatto scorrere prima sulla posizione Off e poi sulla posizione On quando il ripetitore è acceso, il ripetitore entrerà in modalità Cancella.
-   Impostare la posizione dell'interruttore DIP 6 per il dispositivo unidirezionale/bidirezionale quando il ripetitore è spento. Una volta completata l'impostazione, accendere il ripetitore e apprenderlo/riapprenderlo nel pannello affinché l'impostazione abbia effetto.
-   Per l'impostazione del DIP Switch 8, spegnere il ripetitore prima di modificare l'impostazione del DIP Switch. Le nuove impostazioni del Dip Switch 8 avranno effetto quando il ripetitore verrà riacceso.
-   **Segnale di vigilanza**
-   Dopo essere stato appreso dalla centrale, il ripetitore trasmetterà automaticamente segnali di supervisione ogni 30-50 minuti quando funziona come dispositivo unidirezionale. Se funziona come dispositivo bidirezionale, il ripetitore trasmetterà automaticamente segnali di supervisione ogni 90-120 minuti.
-   Se la Centrale non riceve il segnale dal Ripetitore per un periodo di tempo prestabilito, la Centrale lo indicherà sul suo display per mostrare che il Ripetitore sta riscontrando un problema di mancanza segnale.
-   **Impostazione unidirezionale/bidirezionale**
-   Il ripetitore può funzionare sia come dispositivo unidirezionale che bidirezionale. Quando programmato come dispositivo bidirezionale, il ripetitore può ricevere un riconoscimento dalla centrale per garantire la corretta trasmissione.
-   Il ripetitore funzionerà come a**bidirezionale**dispositivo quando il DIP Switch 6 viene spostato su**SU**posizione. Funzionerà come a**Senso Unico**dispositivo quando il DIP Switch 6 viene spostato su**SPENTO**posizione.
-   Impostare la posizione dell'interruttore DIP 6 per il dispositivo unidirezionale/bidirezionale quando il ripetitore è spento. Una volta completata l'impostazione, accendere il ripetitore e apprenderlo/riapprenderlo nel pannello affinché l'impostazione abbia effetto.
-   **Impara nel Pannello di controllo**

1.  Per acquisire il ripetitore nel pannello di controllo, far scorrere l'interruttore DIP 4 sulla posizione On in modalità normale. Il Ripetitore emetterà 1 bip lungo e il LED Giallo si accenderà.
2.  Mettere il Pannello di Controllo in Modalità Apprendimento (fare riferimento al manuale del Pannello di Controllo).
3.  Premere il pulsante Prova. Il Ripetitore trasmetterà un Codice Test alla Centrale di Controllo mentre il LED Rosso si accende ed il Ripetitore emette 1 bip.
4.  Se il Ripetitore riceve un segnale di riconoscimento dalla Centrale entro 60 secondi, l'apprendimento ha avuto successo. Il LED blu si accenderà per 1 secondo mentre il ripetitore emette 1 segnale acustico lungo.

Se il Ripetitore non riesce a ricevere un segnale di riconoscimento dalla Centrale entro 60 secondi, l'apprendimento non è riuscito ed è indicato dal LED Giallo che lampeggia 3 volte. Si prega di ripetere nuovamente i passaggi 3-4.

1.  Far scorrere l'interruttore DIP 4 in posizione Off. Il ripetitore emetterà 1 segnale acustico lungo e il LED giallo si spegnerà quando il ripetitore ritorna alla modalità normale.

-   **Apprendimento del ripetitore nel ripetitore**

Se il ripetitore A sta imparando dal ripetitore B:

1.  Mettere il ripetitore B in modalità di apprendimento: in modalità normale, far scorrere l'interruttore DIP 1 del ripetitore B in posizione On. Il Ripetitore B emetterà 1 beep lungo e il LED Giallo lampeggerà lentamente (1 lampeggio ogni 2 secondi).
2.  Premere il pulsante Test sul ripetitore A per inviare un codice di apprendimento. Il ripetitore A emetterà 1 beep e il LED rosso si accenderà.

Se il Ripetitore B riceve il codice di apprendimento dal Ripetitore A, emetterà 1 bip lungo e il LED Blu si accenderà per 1 secondo per indicare l'avvenuto apprendimento.

Se il ripetitore B riceve il codice di apprendimento dal ripetitore A e il ripetitore A era già stato appreso, il ripetitore B emetterà 2 bip e il LED blu si accenderà per 1 secondo.

\\<Note>

-   Si prega di non eseguire il cross-learning dei ripetitori, ad es. Apprendimento del ripetitore A nel ripetitore B e apprendimento del ripetitore B nel ripetitore A.
-   Tutti i ripetitori dovranno essere memorizzati nel Pannello di Controllo.

1.  Una volta completato l'apprendimento, far scorrere l'interruttore DIP 1 del ripetitore B in posizione Off. Il ripetitore B emetterà 1 segnale acustico lungo e il LED giallo si spegnerà quando il ripetitore B ritorna in modalità normale.

-   **Dispositivo di apprendimento nel ripetitore**

1.  In modalità normale, far scorrere il DIP Switch 1 in posizione On. Il Ripetitore emetterà 1 beep lungo e il LED Giallo lampeggerà lentamente (1 lampeggio ogni 2 secondi).
2.  Fare riferimento ai manuali del dispositivo su come inviare il codice di apprendimento dai dispositivi.

**Per la telecamera PIR, premere una volta il pulsante di prova per inviare un codice di apprendimento al ripetitore.**

Se il Ripetitore riceve un codice di apprendimento da un nuovo dispositivo, emetterà 1 bip lungo e il LED Blu si accenderà per 1 secondo per indicare l'avvenuto apprendimento.

Se il Ripetitore riceve un codice di apprendimento da un dispositivo già appreso nel Ripetitore, emetterà 2 bip e il LED Blu si accenderà per 1 secondo.

**Nel ripetitore è possibile acquisire un massimo di 60 dispositivi (inclusi i ripetitori) e sono supportate fino a 8 telecamere PIR. Se l'utente tenta di apprendere in un 61° dispositivo, il Ripetitore emetterà 4 bip.**

\\<Note>

-   Se vengono utilizzati più ripetitori, apprendere i dispositivi solo nei ripetitori più vicini alle aree operative dei dispositivi.
-   Tutti i dispositivi appresi nel Ripetitore devono essere appresi anche nella Centrale.

1.  Una volta completato l'apprendimento, far scorrere il DIP Switch 1 in posizione Off. Il ripetitore emetterà 1 segnale acustico lungo, il LED giallo si spegnerà quando il ripetitore ritorna alla modalità normale.

-   **Modalità test di camminata**

La centrale di controllo acquisita o i dispositivi acquisiti possono verificare la portata del segnale con il ripetitore se il ripetitore entra in modalità test di copertura.

1.  In modalità normale, far scorrere il DIP Switch 2 in posizione On. Il Ripetitore emetterà 1 beep lungo e il LED Giallo lampeggerà (1 lampeggio ogni secondo).
2.  Quando il Ripetitore riceve segnali dalla Centrale o dai dispositivi appresi, emetterà un lungo segnale acustico e il LED Blu si accenderà per 1 secondo. Il segnale viene quindi ritrasmesso mentre il LED rosso si accende per 1 secondo.
3.  Per uscire dalla modalità Walk Test, far scorrere il DIP Switch 2 in posizione Off. Il Ripetitore emetterà 1 bip lungo e il LED Giallo si spegnerà.

-   **Modalità Cancella (Ripristino delle impostazioni di fabbrica)**

Cancellare la memoria precedentemente programmata e ripristinare le impostazioni di fabbrica del ripetitore

1.  In modalità normale, far scorrere il DIP Switch 3 in posizione On. Il Ripetitore emetterà 1 bip lungo e il LED Giallo si accenderà.
2.  Tenere premuto il pulsante Test per 5 secondi. Il ripetitore emetterà 1 lungo segnale acustico per indicare che tutti i dispositivi acquisiti e la centrale di controllo sono stati cancellati dal ripetitore.
3.  Per uscire dalla modalità Cancella, far scorrere il DIP Switch 3 in posizione Off. Il Ripetitore emetterà 1 bip lungo e il LED Giallo si spegnerà.

\\<Note>

-   Ogni volta che il ripetitore viene rimosso dalla centrale, è necessario ripristinare le impostazioni di fabbrica anche per cancellare la memoria della centrale.
-   **Operazione**

Se il Ripetitore riceve un segnale dalla Centrale (ad esempio un comando), il segnale viene ritrasmesso al/ai dispositivo/i corrispondente/i dal Ripetitore. I LED di trasmissione si accenderanno di conseguenza.

Se il Ripetitore riceve un segnale da un dispositivo (ad esempio un segnale di allarme), il segnale viene ritrasmesso alla Centrale dal Ripetitore. I LED di trasmissione si accenderanno di conseguenza.

-   **Come montare il ripetitore**

Il Ripetitore può essere posizionato sul tavolo, montato a parete o dove desiderato. Seguire i passaggi seguenti per montare il ripetitore:

1.  Utilizzando i fori della staffa di montaggio come modello, praticare dei fori nella superficie di montaggio.
2.  Inserire i tasselli in caso di fissaggio su intonaco o mattoni. Avvitare la staffa di montaggio alla parete.

![](<.gitbook/assets/2 (17).png>)

1.  Agganciare il ripetitore alla staffa di montaggio a parete (con i fori di montaggio del ripetitore).

![](<.gitbook/assets/3 (16).png>)

1.  Tenere il ripetitore e spingerlo delicatamente verso il basso come mostrato di seguito.

![](<.gitbook/assets/4 (15).png>)

-   **Protezione antisabotaggio**
-   L'interruttore antimanomissione è nella posizione operativa normale (antimanomissione chiuso) quando il ripetitore è agganciato alla staffa di montaggio a parete. La violazione del Tamper avviene quando il Ripetitore viene rimosso dal gancio dove viene rilasciato l'Interruttore Tamper (Tamper Aperto).
-   La funzione di protezione antimanomissione può essere**Disabilitato**quando il DIP Switch 8 viene fatto scorrere in posizione ON. È**abilitato**quando il DIP Switch 8 viene spostato in posizione OFF. La modifica all'impostazione del Dip Switch 8 diventerà valida quando il ripetitore verrà riacceso.
-   **Raccomandazioni**

Si consiglia vivamente di mantenere una distanza tra ciascun ripetitore e/o pannello di controllo principale per evitare segnalazioni incrociate.

Se un particolare dispositivo si trova entro un intervallo accettabile affinché la Centrale possa ricevere il segnale di trasmissione, si consiglia vivamente di apprendere il dispositivo direttamente nella Centrale invece che nel Ripetitore.

Quando si collegano i ripetitori in cascata per formare un relè di trasmissione, si consiglia vivamente di collegare non più di 2 strati di ripetitori.

\\<Note>

-   Per i dispositivi controllati direttamente dal Pannello per l'accensione/spegnimento, ad es. interruttori di alimentazione, interruttori del misuratore di potenza, regolatori di valvole, controlli per tapparelle o interruttori di ingresso e uscita, collegare solo uno strato di ripetitori.
-   Per la tastiera, si consiglia inoltre di collegare solo uno strato di ripetitori.

**Ripetitori multipli**

Se vengono utilizzati più ripetitori, seguire le linee guida riportate di seguito per ottenere prestazioni ottimali:

1.  Quando si collegano i ripetitori per formare una riproduzione di trasmissione, si consiglia di collegare non più di due strati di ripetitori.

Dall'esempio seguente (dal dispositivo B ad A fino alla centrale), è necessario acquisire il ripetitore A, il ripetitore B e il dispositivo nella centrale.

Il dispositivo deve essere appreso dal ripetitore più vicino (Ripetuto B). Il ripetitore B deve essere appreso nel ripetitore A. (Non apprendere il ripetitore A nel ripetitore B.)

Esempio:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage device.jpg](<.gitbook/assets/5 (2) (1).jpeg>)

1.  Se un dispositivo si trova tra la copertura RF di più ripetitori e la Centrale:

Esempio 1:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg1.jpg](<.gitbook/assets/6 (5) (1).jpeg>)

Dal diagramma visualizzato, il dispositivo si trova tra le aree di copertura RF del ripetitore B e C. Gli utenti possono scegliere di apprendere il dispositivo solo nel ripetitore B, solo nel ripetitore C o in entrambi i ripetitori B e C.

È**consigliato**per apprendere il dispositivo solo nel ripetitore B (e non nel ripetitore C) per ridurre il traffico del segnale.

\\<Note>

-   Per il sistema di cui sopra, il Ripetitore C viene acquisito anche nel Ripetitore A o B o in entrambi, in modo che i segnali dal Ripetitore C possano essere inoltrati alla Centrale di controllo attraverso il Ripetitore A o B, o uno dei due.

Esempio 2:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg2.jpg](<.gitbook/assets/7 (4) (1).jpeg>)

Dal diagramma visualizzato, il dispositivo si trova tra le aree di copertura RF del ripetitore A, B e C. Gli utenti possono scegliere di apprendere il dispositivo solo nel ripetitore A, apprendere solo nel ripetitore B, apprendere solo nel ripetitore C o apprendere nei ripetitori A, B e C.

È**consigliato**per apprendere il dispositivo solo nel ripetitore A o solo nel ripetitore B (e non nel ripetitore C) per ridurre il traffico del segnale.

\\<Note>

-   Per il sistema di cui sopra, il Ripetitore C viene acquisito anche nel Ripetitore A o B o in entrambi, in modo che i segnali dal Ripetitore C possano essere inoltrati alla Centrale di controllo attraverso il Ripetitore A o B, o uno dei due.

1.  In genere, la maggior parte dei dispositivi si trova nella stessa area di copertura RF. Per le eccezioni come un telecomando, apprendere il dispositivo in tutti i ripetitori (e pannello di controllo) del sistema.
