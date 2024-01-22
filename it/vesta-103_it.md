# VESTA 103

**Controllo otturatore (SCM-8)**

**introduzione**

SCM-8 è un controllo per tapparelle che fornisce un comodo funzionamento, avvolgimento su, giù o arresto a distanza delle tapparelle motorizzate.

Il controllo per tapparelle ha due uscite motore per il controllo automatico e remoto e due interruttori locali per il controllo manuale opzionale. L'utente può controllare l'SCM-8 tramite il pannello di controllo a distanza o manualmente attivando gli interruttori locali.

SCM-8 è inoltre dotato di un morsetto pressacavo e di una fibbia di cablaggio per l'integrità elettrica e meccanica, le prestazioni generali e la sicurezza.

**Identificazione delle parti**

1.  **Pulsante di prova**
    -   Premere una volta: trasmette il segnale di supervisione.
    -   Segnala la posizione attuale al pannello di controllo.
    -   Tenere premuto per 3 secondi: invia un codice di apprendimento.
    -   Tieni premuto il pulsante mentre accendi il controllo otturatore, mantieni premuto il pulsante per circa 4 secondi, quindi rilascia il pulsante quando il LED

lampeggia 3 volte per ripristinare le impostazioni di fabbrica.

-   -   Tenere premuto per 10 secondi: accedere alla modalità di calibrazione.

1.  **Indicatore LED**

![](<.gitbook/assets/0 (48).jpeg>)

L'indicatore LED viene utilizzato per indicare lo stato del controllo dell'otturatore:

-   -   -   Lampeggia una volta: quando è acceso.
        -   Lampeggia due volte: quando l'apprendimento ha avuto successo.
        -   Lampeggia 3 volte: il controllo dell'otturatore è stato ripristinato alle impostazioni di fabbrica.
        -   Si accende fisso: in modalità di apprendimento.
        -   Lampeggia continuamente: quando è in modalità di calibrazione.

1.  **Fori di montaggio**
2.  **Interruttore locale S1 (direzione di apertura)**
    -   Collegare un interruttore esterno a questo terminale. Attivare questo interruttore per controllare che la tapparella si sposti verso la direzione "Aperta" attivando l'uscita motore O1.
    -   L'attivazione di questo interruttore quando la tapparella si muove verso la direzione "Chiuso" fermerà la tapparella.
3.  **Interruttore locale S2 (direzione di chiusura)**
    -   Collegare un interruttore esterno a questo terminale. Attivare

questo interruttore per controllare il movimento della tapparella verso la direzione "Chiuso" attivando l'uscita motore O2

-   -   L'attivazione di questo interruttore quando la tapparella si sta muovendo verso la direzione "Apertura" fermerà la tapparella.

1.  **Uscita motore O1 (direzione di apertura)**

Collegare al terminale di apertura del motore dell'otturatore.

**7. Uscita motore O2 (direzione di chiusura)**

Collegare al terminale di chiusura del motore dell'otturatore.

1.  **Ingresso alimentazione L (cavo sotto tensione)**
2.  **Ingresso alimentazione N (cavo neutro)**
3.  **Morsetto antistrappo**

Il morsetto viene utilizzato per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.

**11. Fibbia di cablaggio**

La fibbia di cablaggio viene utilizzata per la gestione dei cavi.

1

**Specifica**

-   Alimentazione: 100 - 240 V CA, 50/60 Hz
-   Corrente di carico supportata: 1/2 HP (potenza del cavallo); 3,6A per motori con fattore di potenza compensato (carichi induttivi)

![](<.gitbook/assets/1 (40).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
-   Collegare il dispositivo solo al motore alimentato in CA.

**Cablaggio**

-   SCM-8 deve essere collegato secondo lo schema seguente:

![](<.gitbook/assets/2 (35).jpeg>)

-   -   Collegare il terminale N dell'SCM al terminale N dell'alimentatore.
    -   Collegare il terminale L dell'SCM al terminale L dell'alimentatore.
    -   Collegare il terminale O1 dell'SCM al terminale di apertura del motore dell'otturatore.
    -   Collegare il terminale O2 dell'SCM al terminale di chiusura del motore dell'otturatore.
    -   **(Interruttore locale opzionale)**Collegare i terminali S2 e S1 dell'SCM al terminale L dell'alimentatore.
-   Inserire ciascun filo nel terminale a cui deve essere collegato, serrare ciascuna vite per chiudere le clip e mantenere i fili in posizione.
-   Dopo aver collegato i cavi, utilizzare la fibbia di cablaggio per gestire i cavi e posizionare la fibbia di cablaggio sulla base con il suo spazio (apertura) posizionato a sinistra.

![](<.gitbook/assets/3 (32).jpeg>)

2

**Apprendimento**

Passaggio 1: collegare l'alimentazione al controllo otturatore secondo le istruzioni di installazione nella sezione precedente e accendere il controllo otturatore.

Passaggio 2: mettere il pannello di controllo in modalità apprendimento.

Passaggio 3: tenere premuto il pulsante Test sul controllo dell'otturatore per 3 secondi per inviare un codice di apprendimento.

Passaggio 4: il LED lampeggerà una volta e poi si accenderà fisso dopo aver rilasciato il pulsante, indicando che il controllo dell'otturatore è in modalità di apprendimento.

Passaggio 5: Se il pannello di controllo riceve il segnale dal controllo dell'otturatore, visualizzerà le informazioni di conseguenza. Fare riferimento al manuale del Pannello di controllo per completare il processo di apprendimento.

Passo 6: Quando il controllo dell'otturatore riceve il codice di apprendimento dal pannello di controllo, il LED del controllo dell'otturatore lampeggerà due volte e poi si spegnerà per indicare che il processo di apprendimento è completo.

_\\<NOTE>_

-   Dopo essere entrato nella modalità di apprendimento, se il controllo dell'otturatore non riceve conferma dal pannello di controllo per 1 minuto, uscirà automaticamente dalla modalità di apprendimento.
-   Se il controllo dell'otturatore esiste già in un sistema con pannello di controllo, sarà necessario rimuovere prima il controllo dell'otturatore dal pannello di controllo prima di poterlo apprendere in un pannello di controllo diverso.

**Prova della camminata**

Per verificare se il controllo dell'otturatore è in grado di comunicare con il pannello di controllo:

-   Mettere il Pannello di Controllo in modalità Walk Test.
-   Premere il pulsante Test sul controllo dell'otturatore.
-   Il pannello di controllo dovrebbe visualizzare se il controllo dell'otturatore è all'interno del raggio operativo (fare riferimento al manuale operativo del pannello di controllo).

**Montaggio**

-   Dopo aver terminato il test di copertura e se sei sicuro che il dispositivo sia in grado di comunicare con la centrale nella posizione scelta, procedi al montaggio.
-   Scollegare l'alimentazione principale.
-   Allentare la vite di fissaggio inferiore e rimuovere il coperchio superiore del controllo otturatore.
-   Utilizzare i fori di montaggio sulla base per contrassegnare la posizione di montaggio sulla parete.
-   Praticare i fori nella posizione contrassegnata e inserire i tasselli se necessario, avvitare la base nella posizione di montaggio.
-   Riposizionare il coperchio superiore e serrare la vite di fissaggio inferiore.

**Supervisione**

-   Dopo che il controllo dell'otturatore è stato acquisito con successo nel pannello di controllo, il dispositivo trasmetterà automaticamente il segnale di supervisione insieme al rapporto sulla posizione corrente al pannello di controllo a intervalli casuali da 30 a 50 minuti.
-   If the Control Panel has not received the signal from the Shutter Control for the preset period of time, the Control Panel will indicate on its display that the particular Shutter Control is experiencing an out-of-signal problem.

**Operazione**

-   _**Calibrazione**_
    -   L'orario di attivazione predefinito del controllo otturatore è**4**minuti. Quando si preme il pulsante Su/Giù o la centrale invia una richiesta Su/Giù, attiverà il motore della tapparella per 4 minuti.
    -   Affinché il Controllo Otturatore funzioni correttamente, il suo tempo di attivazione deve essere calibrato manualmente. Calibrare il tempo di attivazione secondo le procedure seguenti:
        1.  Prima della calibrazione, gli interruttori locali esterni devono essere collegati al controllo della tapparella.
        2.  Tenere premuto il pulsante Test per 10 secondi, quindi rilasciarlo per accedere alla modalità Calibrazione (il LED lampeggerà due volte). Il controllo dell'otturatore ruoterà verso la direzione "Apertura" per 4 minuti dopo essere entrati nella modalità di calibrazione.
        3.  Attendere 4 minuti affinché il motore dell'otturatore smetta di scorrere, quindi premere il pulsante "Giù" per abbassare l'otturatore. (Se in meno di 4 minuti la tapparella ha già raggiunto la posizione aperta, è possibile premere il pulsante “Giù” per arrestare il motore della tapparella. Quindi premere nuovamente il pulsante “Giù” per abbassare la tapparella.)

3

1.  Premere il pulsante “Su” nel momento in cui la tapparella è completamente chiusa. Il controllo dell'otturatore registrerà il tempo impiegato dall'otturatore per scorrere dall'apertura alla chiusura come nuovo "**ora di chiusura**”.
2.  Il controllo dell'otturatore ruoterà verso la direzione di apertura dopo il passaggio 4 (quando si preme il pulsante "Su" nel momento in cui l'otturatore è completamente chiuso).
3.  Premere il pulsante “Giù” nel momento in cui l'otturatore è completamente aperto. Il controllo dell'otturatore registrerà il tempo impiegato dall'otturatore per scorrere dalla chiusura all'apertura come nuovo "**orario aperto**”.
4.  Una volta completata la calibrazione, il controllo dell'otturatore invierà un rapporto sulla posizione corrente al pannello di controllo e funzionerà con il nuovo orario di chiusura/apertura.

Esempio

Se la tapparella impiega 30 secondi per spostarsi da Aperto a Chiuso e 40 secondi per spostarsi da Chiuso ad Aperto, il nuovo**ora di chiusura**sarà**30**secondi e nuovi**orario aperto**sarà**40**secondi.

Dopo la calibrazione, ogni volta che il controllo dell'otturatore riceve una richiesta di chiusura, ruoterà nella direzione di chiusura per 30 secondi. Quando riceve una richiesta di apertura, ruoterà verso l'apertura per 40 secondi.

-   -   L'orario di attivazione verrà reimpostato**4**minuti ogni volta che il controllo dell'otturatore viene ripristinato alle impostazioni di fabbrica.
-   _**Controllo dell'otturatore**_

**Telecomando**

-   Dopo aver appreso con successo il controllo dell'otturatore nel pannello di controllo, l'utente può controllare in remoto l'apertura, la chiusura o l'arresto dell'otturatore tramite la pagina Web del pannello di controllo.
-   Quando il controllo dell'otturatore riceve una richiesta di apertura/chiusura dal pannello di controllo, ruoterà nella direzione di apertura/chiusura in base al tempo di attivazione calibrato per aprire/chiudere completamente l'otturatore.
-   Lo stato dell'otturatore può anche essere regolato in percentuale da 0%, 10%, 20%... a 100% tramite la pagina Web del Pannello di controllo.
-   Anche la percentuale di apertura corrente viene trasmessa al Pannello di Controllo.

![](<.gitbook/assets/4 (48).png>)

**Commutatore locale**

-   Se è collegato un interruttore locale opzionale, gli utenti possono anche premere il pulsante dell'interruttore per aprire/chiudere l'otturatore.
-   Premere e rilasciare l'interruttore per meno di 1 secondo per controllare l'apertura o la chiusura completa dell'otturatore.
-   Premendo l'interruttore quando l'otturatore si muove nella direzione opposta si fermerà l'otturatore. Premere nuovamente l'interruttore per aprire/chiudere l'otturatore.

Ad esempio, premendo l'interruttore verso il basso mentre l'otturatore si sta aprendo si fermerà l'otturatore, premere nuovamente l'interruttore verso il basso per avviare la chiusura dell'otturatore.

**Ripristino delle impostazioni di fabbrica**

-   Il ripristino delle impostazioni di fabbrica del controllo otturatore ne cancellerà la memoria e lo ripristinerà alle impostazioni predefinite di fabbrica.
-   Tieni premuto il pulsante mentre accendi il controllo otturatore, continua a tenere premuto il pulsante per circa 4 secondi, quindi rilascia il pulsante quando il LED lampeggia 3 volte per ripristinare le impostazioni di fabbrica.

4
