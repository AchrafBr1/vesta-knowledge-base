# VESTA148

**EIRP-J1/EIRC-J2 Impara nelle istruzioni**

Il trasmettitore GEN-TX è installato all'interno di EIRP-J1 e EIRC-J2, consentendo loro di inviare segnali RF wireless al pannello di controllo.

Le antenne del GEN-TX sono diverse in base alla frequenza 433 e 868.

**EIRP-J1****EIRC-J2****Frequenza 433****Frequenza 868**

![](<.gitbook/assets/0 (43).png>)

-   _**Identificazione delle parti**_

1.  **Pulsante Apprendi/Test**
2.  **Batteria (CR2)**
3.  **Interruttore Jumper di supervisione (JP2)**
4.  **Indicatore LED (rosso)**

![](<.gitbook/assets/1 (49).png>)![](<.gitbook/assets/2 (54).png>)

-   _**Indicatore LED**_

Nella modalità di funzionamento normale, l'indicatore LED rimane spento tranne:

-   -   Quando il rilevatore di movimento è in condizioni di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED lampeggerà per 6 volte.
    -   Quando l'interruttore antimanomissione viene attivato, il LED lampeggerà per 6 volte per indicare che sta trasmettendo "**Manomettere**" segnale.
    -   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED lampeggerà per 6 volte.
    -   Quando la batteria è scarica, il LED lampeggerà ogni 4 secondi.
-   _**Apprendimento**_
    -   Per EIRP-J1, staccare prima la scatola posteriore e la piastra di montaggio. Per EIRC-J2, staccare prima la base di montaggio. (Per i dettagli fare riferimento alle istruzioni di installazione di VXI-R e FTN-R-PT.)
    -   Estrarre l'isolante della batteria per attivare la batteria.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Premi il pulsante Impara.
    -   Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.

![](<.gitbook/assets/3 (53).png>)

1

-   ![](<.gitbook/assets/4 (53).png>)_**Prova della camminata**_
    -   Dopo aver appreso il rilevatore, inserire il pannello di controllo in “**Prova della camminata**", tenere il rilevatore nella posizione desiderata e premere il pulsante Test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
    -   Quando sei sicuro che il rilevatore funzioni nella posizione scelta, puoi procedere al montaggio.
-   _**Batteria**_
    -   Il rilevatore utilizza una batteria al litio “CR2” da 3 V come fonte di alimentazione.
    -   Quando viene rilevata una batteria scarica, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo possa visualizzare lo stato di conseguenza.
    -   Quando la batteria è scarica, il rilevatore interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
    -   Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte il pulsante Learn per scaricarla completamente prima di inserire la nuova batteria.
-   _**Supervisione**_
    -   Dopo l'installazione, il rilevatore trasmetterà automaticamente periodicamente i segnali di supervisione alla centrale di controllo a intervalli casuali da 30 a 50 minuti.
    -   Se la Centrale di Controllo non ha ricevuto il segnale dal rilevatore per il periodo di tempo preimpostato, la Centrale di Controllo indicherà sul suo display che quel particolare rilevatore sta riscontrando un problema di mancanza di segnale.

![](<.gitbook/assets/5 (52).png>)![](<.gitbook/assets/6 (34).png>)![](<.gitbook/assets/7 (32).jpeg>)

**Ponticello OFF (impostazione di fabbrica)**

\-Quando il ponticello (JP2) è impostato su OFF, la supervisione è abilitata.

**Ponticello ON**

![](<.gitbook/assets/8 (25).jpeg>)

-   Quando il ponticello (JP2) è impostato su ON, la supervisione è disabilitata.

2
