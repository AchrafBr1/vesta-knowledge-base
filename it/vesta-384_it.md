# VESTA 384

![](<.gitbook/assets/0 (116).jpeg>)**Rilevatore di fumo cablato (SD-32-BUS)**

**introduzione**

SD-32-BUS è un rilevatore di fumo cablato progettato per proteggerti da potenziali rischi di incendio. Il rilevatore di fumo utilizza una tecnologia di sensori multicriterio per rilevare tra fiamme a combustione rapida e incendi a combustione lenta, e allo stesso tempo include una tecnologia intelligente per distinguere tra fumo di cottura e reali emergenze di incendio domestico potenzialmente letali, eliminando virtualmente i fastidiosi allarmi.

Il rilevatore di fumo cablato può anche essere interconnesso con altri rilevatori di fumo nel sistema di allarme e attiva l'allarme quando viene attivato un rilevatore di fumo nel sistema.

**Identificazione delle parti**

![](<.gitbook/assets/1 (85).png>)

**1. Indicatore LED/Pulsante Test**

**LED rosso**

-   Lampeggio veloce: allarmante.
-   Lampeggia ogni secondo: rilevatore di fumo in modalità silenzio allarme.
-   Lampeggia ogni 2 secondi: rilevatore di fumo in fase di riscaldamento e calibrazione.
-   Lampeggia brevemente: quando si preme il pulsante Learn per vedere se il dispositivo funziona normalmente.
-   Si accende brevemente: trasmissione del segnale.

**LED arancione**

-   Lampeggia ogni secondo: calibrazione non riuscita.
-   Lampeggia ogni 5 secondi: Rilevazione fumo fallita o malfunzionamento del dispositivo.

**Pulsante di prova**

-   -   Premere il pulsante una volta per:
        -   Invia un segnale di prova.
        -   Controllare la camera di rilevazione del fumo.
        -   Silenzia l'allarme quando il rilevatore di fumo è in allarme.
    -   Tenere premuto il pulsante per 10 secondi per accedere al processo di calibrazione.

1.  **Cicalino**
2.  **Vano Terminale BUS**
3.  **Ganci**
4.  **Foro preforato per il cablaggio**
5.  **Vite di fissaggio del coperchio del vano morsettiera BUS**
6.  **Capolinea autobus**
7.  **Interruttore a ponticello della resistenza terminale**

Quando il rilevatore di fumo è collegato come dispositivo BUS più lontano su una linea BUS, impostare il ponticello del resistore terminale del rilevatore di fumo e l'interruttore ponticello del primo dispositivo BUS (solitamente il pannello ibrido) su ON per fungere da resistori di terminazione. La capacità di comunicazione della linea BUS connessa verrà potenziata.

![](<.gitbook/assets/2 (83).jpeg>)

-   -   -   Se il ponticello è disattivato (il collegamento del ponticello è rimosso o “parcheggiato” su un pin), la capacità di comunicazione è a livello normale.
    -   Se il ponticello è su ON, la capacità di comunicazione verrà migliorata.

1.  **Staffa di fissaggio**
2.  **Fori di montaggio**
3.  **Foglio di montaggio**

![](<.gitbook/assets/3 (81).jpeg>)

1

**Caratteristiche**

![](<.gitbook/assets/4 (96).png>)

-   _**Alimentazione elettrica**_
    -   Quando l'SD-32-BUS è cablato a una centrale ibrida, l'alimentazione da 13,5 V può essere fornita dalla centrale ibrida.
-   _**Testing the Smoke Detector**_

![](<.gitbook/assets/5 (98).png>)

Premendo il pulsante Test sul rilevatore di fumo, è possibile verificare se il rilevatore di fumo funziona normalmente.

-   -   Se il rilevatore di fumo funziona normalmente, il LED rosso si accenderà per 2 secondi seguito da un segnale acustico a 2 toni.
    -   Se il cicalino emette segnali acustici a 2 toni per 3 volte, il messaggio “**Camera ottica**" sul rilevatore di fumo è sporco o fuori servizio.
-   _**Rilevamento dell'accumulo di polvere**_
    -   Il rilevatore controlla regolarmente l'eventuale accumulo eccessivo di polvere all'interno della camera ottica.
    -   Se nella camera si accumula polvere, il rilevatore lo segnalerà al Pannello per avvisare l'utente di pulirlo.
    -   Se la camera non viene ancora pulita e si accumula troppa polvere da non funzionare più, il rilevatore segnalerà al pannello un avviso di manutenzione.
-   _**Supervisione**_
    -   Il rilevatore di fumo cablato trasmetterà automaticamente il segnale di supervisione alla centrale ogni 75 secondi.
    -   Se la centrale di controllo non riceve il segnale dal rilevatore di fumo cablato per un periodo di tempo preimpostato, indicherà che quel particolare rilevatore di fumo sta riscontrando un problema di mancanza di segnale.
-   _**Attivazione dell'allarme**_

![](<.gitbook/assets/6 (80).png>)![](<.gitbook/assets/7 (70).png>)![](<.gitbook/assets/8 (69).png>)

Il rilevatore di fumo attiverà l'allarme antincendio quando viene attivato il rilevamento del fumo. Quando viene attivato un allarme, il rilevatore di fumo trasmetterà il segnale di allarme e attiverà l'allarme con il cicalino integrato.

**Rilevazione del fumo:**

-   -   Il rilevatore di fumo controlla la concentrazione di fumo ogni 8 secondi
    -   L'allarme viene attivato ogni volta che la concentrazione di fumo supera la soglia di rilevamento e continuerà finché la concentrazione di fumo non scenderà al di sotto della soglia di allarme.
    -   Il LED rosso lampeggerà rapidamente durante l'allarme.
-   _**Silenziamento allarme**_
    -   Quando il rilevatore di fumo è in allarme, premendo il pulsante Test si metterà il rilevatore di fumo in modalità Silenziamento allarme per silenziare l'allarme per 9 minuti. Il cicalino smetterà di suonare solo dopo che l'allarme è stato attivato per almeno 1 minuto. Se il pulsante viene premuto prima che l'ora dell'allarme raggiunga 1 minuto, il rilevatore di fumo attenderà fino a quando l'ora dell'allarme raggiunge 1 minuto prima di silenziare l'allarme.
    -   Durante il periodo di silenzio allarme di 9 minuti, il LED rosso lampeggerà una volta al secondo. Il rilevatore di fumo continuerà a monitorare la concentrazione di fumo durante il periodo di silenzio dell'allarme:
    -   Una volta trascorso il periodo di silenzio allarme di 9 minuti, se la concentrazione di fumo è scesa al di sotto della soglia di allarme, il rilevatore di fumo emetterà un segnale acustico a 2 toni e tornerà al funzionamento normale senza far suonare l'allarme.
    -   Se la concentrazione di fumo supera ancora la soglia di allarme, il rilevatore di fumo inizierà nuovamente a emettere allarme.
    -   Se la concentrazione di fumo continua ad aumentare durante il periodo di silenziamento dell'allarme e supera una seconda soglia di allarme, il rilevatore di fumo inizierà nuovamente ad emettere allarme. Un allarme attivato dal superamento della seconda soglia di allarme non può essere silenziato premendo il pulsante di test.
-   _**Interconnessione**_
    -   Il rilevatore di fumo è interconnesso con altri rilevatori di fumo nel sistema di allarme. Quando un rilevatore di fumo attiva l'allarme, il pannello di controllo avviserà anche gli altri rilevatori di fumo di attivare l'allarme anche se non hanno ancora rilevato il fumo. La durata dell'allarme sarà conforme all'impostazione del pannello di controllo.
    -   Il disinserimento del sistema interromperà l'allarme degli altri rilevatori di fumo attivati ​​dal pannello di controllo. L'allarme attivato dal rilevatore di fumo che rileva il fumo si interromperà solo quando la concentrazione di fumo scende al di sotto della soglia di allarme.
    -   Premendo il pulsante Test di un rilevatore di fumo verrà silenziato solo l'allarme di quello specifico rilevatore di fumo, ma non sarà possibile silenziare l'allarme di tutti i rilevatori di fumo interconnessi.
-   _**Attenzione**_
    -   Il cablaggio del rilevatore di fumo deve essere eseguito solo da tecnici certificati con conoscenza e formazione adeguate sulle apparecchiature elettriche.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   _**Cablaggio del rilevatore di fumo**_
    -   Prima di collegare il rilevatore di fumo cablato al BUS del sistema, spegnere l'alimentazione.
    -   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

![](<.gitbook/assets/9 (67).png>)![](<.gitbook/assets/10 (29).jpeg>)![](<.gitbook/assets/11 (53).png>)![](<.gitbook/assets/12 (56).png>)![](<.gitbook/assets/13 (40).jpeg>)

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   È possibile collegare più dispositivi BUS in serie alla centrale ibrida. Per una comunicazione ottimale tra i dispositivi della linea BUS collegati, assicurarsi che gli interruttori a ponticello della resistenza terminale del primo (normalmente il pannello ibrido) e dei dispositivi BUS più lontani su una linea BUS siano impostati su ON per fungere da resistenze di terminazione. Assicurarsi di abilitare solo i 2 interruttori jumper sopra menzionati e di non impostare gli interruttori jumper su ON per nessun altro dispositivo BUS intermedio.

_\\<NOTE>_

2

-   -   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dalla scheda PCB per facilità d'uso e ricollegarle dopo il cablaggio.
    -   Dopo aver scollegato il terminale, quando si reinstalla il terminale sulla scheda, assicurarsi di installare il terminale nella stessa direzione per evitare potenziali pericoli.
-   Collegamenti errati causeranno guasti o malfunzionamenti. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

![](<.gitbook/assets/14 (47).png>)

-   _**Iniziare**_

**Passo 1**Collegare il rilevatore al pannello. Quindi, accendere la centrale e anche il rilevatore di fumo si accenderà.

**Passo 2**Dopo aver fornito alimentazione al rilevatore di fumo, emetterà 2 brevi segnali acustici e inizierà**riscaldarsi per 1 minuto**. Il LED rosso lampeggerà ogni 2 secondi**.**

**Passaggio 3.**Quando il rilevatore di fumo completa il riscaldamento, emetterà un segnale acustico per indicare che è entrato**calibration mode**. La modalità di calibrazione dura per**1 minuto**(Se la calibrazione fallisce, il rilevatore di fumo ritenterà la calibrazione, la modalità di calibrazione durerà al massimo 9 minuti). Il LED rosso continuerà a lampeggiare ogni due secondi durante la calibrazione.

**Passaggio 4.**Una volta completata la calibrazione, il rilevatore di fumo emetterà 2 brevi segnali acustici e spegnerà il LED per tornare alla modalità normale._\\<NOTE>_

![](<.gitbook/assets/15 (44).png>)

-   Se la calibrazione fallisce, il rilevatore di fumo emetterà un segnale acustico continuo. Spegnere il rilevatore di fumo, quindi riaccenderlo per riprovare dal passaggio 1.

Una volta completati con successo il processo di riscaldamento e calibrazione, è possibile procedere all'apprendimento.

**Passaggio 5.**Inserisci il Pannello di controllo in**modalità di apprendimento**.

**Passaggio 6**Il rilevatore di fumo verrà rilevato se è collegato correttamente alla centrale ibrida.

**Passaggio 7.**Fare clic su "**Aggiungere**” per includere il rilevatore di fumo rilevato nel Pannello di controllo.

![](<.gitbook/assets/16 (49).png>)

-   _**Identificazione**_

La funzione “Identifica” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare il rilevatore di fumo cablato nel sistema BUS:

**Passo 1.**Nella pagina web del pannello ibrido, fare clic su "Identifica" sotto l'elenco dei dispositivi dopo la voce della colonna del dispositivo SD-32-BUS.

**Passo 2.**Se il rilevatore di fumo cablato riceve il segnale dalla centrale ibrida, la pagina web visualizzerà un messaggio di successo e l'indicatore LED rosso del rilevatore di fumo cablato lampeggerà 10 volte per indicare all'utente dove si trova.

![](<.gitbook/assets/17 (39).png>)

_\\<NOTE>_

-   -   -   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il rilevatore di fumo cablato non ha ricevuto il segnale dalla centrale. Verificare se l'SD-32-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.
-   _**Prova della camminata**_
    -   Per assicurarsi che il rilevatore di fumo cablato sia in grado di comunicare con la centrale dopo l'apprendimento, posizionare la centrale di controllo in modalità Walk Test e premere il pulsante Test su SD-32-BUS per trasmettere un segnale di test alla centrale.
    -   Quando la centrale riceve il segnale di test, emette un segnale acustico e visualizza le informazioni del rilevatore di fumo cablato in cima all'elenco dei dispositivi.

![](<.gitbook/assets/18 (49).png>)![](<.gitbook/assets/19 (48).png>)

_\\<NOTE>_

-   -   Se non c'è risposta dal pannello dopo aver premuto il pulsante test, significa che il pannello non ha ricevuto il segnale di test dal dispositivo.

Controllare se il rilevatore di fumo è collegato correttamente alla centrale entro una distanza di cablaggio adeguata.

-   _**Ricalibrazione**_

![](<.gitbook/assets/20 (35).png>)

Poiché le condizioni operative del rilevatore di fumo possono variare dopo essere stato installato per un certo periodo, potrebbe essere necessario ricalibrare Smoke 3

Rilevatore di fumo per acquisire un nuovo valore di soglia di rilevamento del fumo e garantire prestazioni ottimali del rilevatore di fumo. Per fare questo:

-   Tenere premuto il pulsante Test per 20 secondi e rilasciarlo quando il rilevatore di fumo emette 3 segnali acustici. Il dispositivo inizierà la calibrazione e il LED rosso lampeggerà ogni 2 secondi per indicare.
-   Il processo di calibrazione dura per**1 minuto**(Se la calibrazione fallisce, il rilevatore di fumo ritenterà la calibrazione, la modalità di calibrazione durerà al massimo 9 minuti).
-   Al termine della calibrazione, il rilevatore di fumo emetterà un segnale acustico bitonale. Il LED rosso smetterà di lampeggiare per indicare che è tornato alla modalità normale.
-   Se la calibrazione fallisce, il rilevatore di fumo emetterà un segnale acustico continuo e il LED arancione lampeggerà ogni secondo. Spegnere il rilevatore di fumo, quindi riaccenderlo per riavviare il rilevatore di fumo.

**Manutenzione e pulizia**

La manutenzione e la pulizia regolari contribuiranno a mantenere il rilevatore di fumo in buone condizioni.

-   Testare settimanalmente il rilevatore di fumo per verificare che i suoni e gli indicatori di allarme funzionino correttamente.
-   Pulire il rilevatore di fumo almeno una volta ogni 6 mesi.
    -   Aspirare delicatamente lo sporco/polvere/piccole particelle accumulate nella camera e nelle feritoie di rivelazione fumo.
    -   Pulisci l'involucro strofinandolo accuratamente con un panno umido e asciugalo. Non far entrare acqua all'interno dell'allarme.
    -   Non utilizzare mai detergenti, detergenti o solventi sul rilevatore.
-   Evitare di spruzzare deodoranti per ambienti, lacca per capelli o altri aerosol vicino al rilevatore di fumo.
-   Non verniciare né modificare in nessun caso il rilevatore.

**Scadenza**

Il rilevatore di fumo ha una durata massima di**10 anni**dalla data di installazione. È necessario sostituire il rilevatore di fumo immediatamente dopo 10 anni di servizio.

Si consiglia di scrivere la data "Sostituire entro" (10 anni dalla data di installazione) sul retro del rilevatore prima dell'installazione.

**Installazione**

_**Linee guida per l'installazione**_

 Si consiglia che il luogo di installazione sia nella zona centrale del soffitto.

 Non posizionare il rilevatore nelle seguenti posizioni:

 La cucina – Il fumo proveniente dalla cucina potrebbe causare un allarme indesiderato.

 Vicino a ventilatori, lampade fluorescenti o apparecchiature di condizionamento dell'aria: le correnti d'aria provenienti da essi possono influenzare la sensibilità del rilevatore.

-   Vicino alle travi del soffitto o sopra un armadio: l'aria stagnante in queste aree può influire sulla sensibilità del rilevatore.

 Nel culmine di un “**UN**” tipo di telaio del soffitto.

-   _**Montaggio del rilevatore di fumo**_

**Passo 1.**Posizionare il rilevatore di fumo nella posizione di montaggio desiderata.

**Passo 2.**Estrarre il foglio di montaggio incluso nella confezione. Le dimensioni dell'immagine corrispondono alle dimensioni effettive del rilevatore di fumo e il design perforato consente un facile strappo dopo l'installazione.

**Passaggio 3.**Posizionare il telo ben aderente al soffitto e utilizzare i quattro fori come dima per praticare i fori e inserire i tasselli, se necessario.

Assicurarsi che i tasselli siano a filo con la superficie di montaggio.

**Passaggio 4.**Posizionare la staffa di montaggio sopra la lamiera di montaggio e avvitarla alla parete.

**Passaggio 5.**Il rilevatore di fumo è dotato di 4 ganci sul coperchio posteriore. Tenere il rilevatore di fumo con particolare attenzione e allineare le 4 tacche sulla staffa di montaggio con i 4 ganci.

**Passaggio 6.**Ruotare in senso orario per bloccare il gancio.

**Passaggio 7.**L'installazione è ora completa. Ora puoi strappare il foglio di montaggio.

4
