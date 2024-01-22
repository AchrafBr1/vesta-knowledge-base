# VESTA158

![](<.gitbook/assets/0 (47).png>)**Sensore di temperatura (TAS-9/TAS-9E)**

TAS-9E è un dispositivo sensore wireless di temperatura. Trasmette la condizione di temperatura al pannello di controllo ogni 30-50 minuti e segnala l'allarme quando la temperatura supera o scende al di sotto del normale intervallo di funzionamento impostato tramite Dip Switch.

Il sensore di temperatura comprende i seguenti modelli:**TAS-9:**Sensore di temperatura con sensore di temperatura integrato.**Fiducia:**Sensore di temperatura con sonda di temperatura esterna.

![](<.gitbook/assets/1 (50).jpeg>)

-   _**Identificazione delle parti**_

Rimuovere il coperchio allentando la vite di fissaggio inferiore, l'interno del sensore di temperatura verrà rivelato come mostrato.

-   1.  **Morsettiera per sonda di temperatura esterna (solo TAS-9E)**

Morsettiera opzionale per collegare una sonda di temperatura esterna.

-   1.  **Interruttore antimanomissione**

Quando il sensore di temperatura è installato correttamente, l'interruttore antimanomissione verrà compresso.

UN**Chiusura antimanomissione**il segnale viene trasmesso quando il Tamper viene compresso.

UN**Manomissione aperta**il segnale viene trasmesso quando il Tamper viene rilasciato.

-   1.  **LED interno**

Lampeggia velocemente per 2 secondi –

Interruttore antimanomissione chiuso/aperto, pulsante Apprendimento/Test premuto. Lampeggia ogni 4 secondi – Batteria scarica

Il LED lampeggia una volta ogni 4 secondi per indicare batteria scarica e tutte le operazioni vengono interrotte. Fare riferimento a**Batteria**per modificare e ripristinare la funzione del sensore di temperatura.

-   1.  **Blocco funzionale DIP Switch**
    2.  **Pulsante Impara/Test**

Premere il pulsante una volta per inviare un codice di apprendimento insieme al codice di stato per informare la centrale sullo stato del sensore di temperatura.

-   1.  **Compartimento della batteria**
    2.  **Connettore sonda temperatura esterna (solo TAS-9E)**
    3.  **Sonda di temperatura esterna (solo TAS-9E)**
    4.  **Sonda di temperatura interna**
-   _**Batteria**_

![](<.gitbook/assets/2 (47).jpeg>)![](<.gitbook/assets/3 (42).jpeg>)

Il sensore di temperatura ne utilizza uno**CR123 - Batteria al litio da 3 V**. Si prega di sostituire sempre la batteria con la dimensione e il voltaggio corretti.

Quando il sensore di temperatura ha la batteria scarica, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.

Quando la batteria è scarica, il LED lampeggia ogni 4 secondi e il sensore di temperatura interromperà tutte le funzioni.

-   **Cambio batteria**

1.  Rimuovere il coperchio allentando la vite di fissaggio inferiore. Quindi rimuovere la vecchia batteria.

II. Premere alcune volte l'interruttore antimanomissione o il pulsante di apprendimento/test.

III. Inserire una nuova batteria nel vano batteria. Si prega di orientare la batteria secondo la polarità corretta.

IV. Sostituire la copertura.

1

-   ![](<.gitbook/assets/4 (42).jpeg>)_**Supervisione**_
    -   Un segnale di supervisione viene inviato ogni 30-50 minuti insieme alla lettura della temperatura attuale e allo stato della batteria.
    -   Il tempo di supervisione viene ripristinato ogni volta che viene trasmesso un segnale. (ad esempio**Tamper open**segnale,**Chiusura antimanomissione**segnale, ecc.).
-   _**Iniziare**_
    -   Rimuovere la vite di fissaggio e il gruppo coperchio
    -   Inserire la batteria nel portabatteria facendo attenzione a collegare correttamente la polarità.
    -   Metti il ​​Pannello di Controllo in modalità apprendimento. Fare riferimento al manuale utente del pannello di controllo.
    -   Premere una volta il pulsante Apprendimento/Test per inviare un codice di apprendimento al Pannello di controllo.
    -   Fare riferimento al manuale utente del pannello di controllo per completare il processo di apprendimento.
    -   Per verificare la portata, mettere il pannello di controllo in modalità Walk Test, posizionare il dispositivo nella posizione di montaggio desiderata e premere il pulsante Impara/Test per trasmettere il segnale per il test di rabbia.
    -   Quando sei soddisfatto che il sensore di temperatura funzioni nella posizione scelta, puoi procedere con l'installazione.
-   _**Installazione**_

![](<.gitbook/assets/5 (26).jpeg>)![](<.gitbook/assets/6 (36).jpeg>)

Esistono due modi per montare il sensore di temperatura: montaggio autoadesivo o con viti.

-   **Montaggio autoadesivo**

1.  Pulire la superficie con uno sgrassatore idoneo.
2.  Rimuovere la copertura protettiva da un lato del cuscinetto biadesivo e applicarlo saldamente sul retro del dispositivo.

III. Quindi rimuovere l'altro coperchio e premere con decisione l'oggetto nella posizione desiderata.

![](<.gitbook/assets/7 (31).png>)

_\\<NOTE>_

-   -   Non utilizzare il metodo di installazione del tampone adesivo su una superficie con vernice scrostata o screpolata o su una superficie ruvida.
-   **Montaggio a vite**

La base ha due fori, dove la plastica è più sottile, per il montaggio. Per montare il sensore di temperatura

1.  Rimuovere il coperchio e sfondare i fori sulla base

II. Utilizzando i fori come sagoma, praticare dei fori sulla superficie III. Inserire i tasselli in caso di fissaggio su intonaco o mattoni

IV. Avvitare la base nei tasselli, quindi riavvitare il coperchio sulla base.

![](<.gitbook/assets/8 (28).jpeg>)

-   _**Funzionamento e attivazione degli allarmi**_
    -   Il sensore di temperatura può essere selezionato per utilizzare la sonda di temperatura interna o esterna in base all'impostazione del Dip Switch
    -   Le impostazioni del DIP Switch determinano anche quattro intervalli di temperatura per il funzionamento normale e la soglia di attivazione dell'allarme.
    -   Un segnale di attivazione dell'allarme viene trasmesso se la temperatura supera la soglia di attivazione dell'allarme**per 10 minuti**.
    -   Viene trasmesso un segnale di ripristino allarme se la temperatura scende al di sotto della Soglia ripristino allarme**per 4 minuti**.
    -   Si prega di fare riferimento alla tabella seguente per maggiori dettagli:

| IMMERSIONE     | IMMERSIONE     | Normale    | Allarme    | Allarme    | Sonda di rilevamento |   |
| -------------- | -------------- | ---------- | ---------- | ---------- | -------------------- | - |
| Operazione     | Attivazione    | Restauro   | (Interno o |            |                      |   |
| Interruttore 1 | Interruttore 2 |            |            |            |                      |   |
| Allineare      | Soglia         | Soglia     | Esterno)   |            |                      |   |
|                |                |            |            |            |                      |   |
| Spento         | Spento         | 7°C - 35°C | &lt; 7°C   | > 9°C      | Interno              |   |
| > 35°C         | &lt; 33°C      |            |            |            |                      |   |
|                |                |            |            |            |                      |   |
|                |                |            |            |            |                      |   |
| Spento         | SU             | &lt; -12°C | > -12°C    | &lt; -14°C | Esterno              |   |
| > 7°C          | &lt; 7°C       | > 9°C      |            |            |                      |   |
|                |                |            |            |            |                      |   |
|                |                |            |            |            |                      |   |
| SU             | Spento         | 7°C - 24°C | &lt; 7°C   | > 9°C      | Interno              |   |
| > 24°C         | &lt; 22°C      |            |            |            |                      |   |
|                |                |            |            |            |                      |   |
|                |                |            |            |            |                      |   |
| SU             | SU             | &lt; 6°C   | > 6°C      | &lt; 4°C   | Esterno              |   |
| > 7°C          | &lt; 7°C       | > 9°C      |            |            |                      |   |
|                |                |            |            |            |                      |   |
|                |                |            |            |            |                      |   |

-   Per passare da una modalità all'altra, regolare semplicemente gli interruttori DIP in base all'impostazione desiderata.

2
