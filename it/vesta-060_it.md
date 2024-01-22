# VESTA060

Sensore di contatto porta/vibrazione d'urto (DCSV-23)

DCSV-23 è un contatto porta/sensore di shock in grado di inviare un segnale di porta aperta al pannello di controllo al rilevamento dell'apertura di porte/finestre o al rilevamento di urti/vibrazioni.

![DCSV-23ZBS](<.gitbook/assets/0 (13).jpeg>)Il design del contatto porta/sensore vibrazione shock è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

Identificazione delle parti

1.  **Indicatore LED/Pulsante Test**

-   Premere il pulsante una volta per inviare un codice di apprendimento o accedere alla modalità test per 3 minuti.

1.  **Vite di fissaggio del coperchio**
2.  **Fori di montaggio**
3.  **Interruttore antimanomissione**

-   Fornisce protezione antimanomissione contro l'apertura e/o la rimozione non autorizzata del dispositivo dalla superficie di montaggio.

1.  **Isolante della batteria**
2.  **Ponticello modalità rilevamento (JP3)**

-   Fare riferimento alla sezione_**Modalità di rilevamento urti/vibrazioni**_per dettagli.

1.  **Ponticello di regolazione della sensibilità (JP4,JP5)**

-   Fare riferimento alla sezione_**Regolazione della sensibilità**_per dettagli.

1.  **Ponticello dell'interruttore Reed (JP1)**

-   Fare riferimento alla sezione_**Interruttore a lamella**_per dettagli.

1.  **Compartimento della batteria**
2.  **Magnet**
3.  **Foro per vite magnetica**
4.  **Distanziatore magnetico**

Caratteristiche

Maglione**SU**(Il collegamento del ponticello è inserito): L'interruttore Reed è_**Disabilitato.**_

![jumper open](<.gitbook/assets/3 (21).png>)

Maglione**SPENTO**(Il collegamento del ponticello è rimosso o parcheggiato su un pin): L'interruttore Reed sì_**abilitato**_e il dispositivo ora funziona come contatto porta. (_**Predefinito**_)

-   L'interruttore Reed deve essere disabilitato se il dispositivo non viene utilizzato come contatto porta.
-   _**Modalità di rilevamento urti/vibrazioni**_
-   La funzione di rilevamento di urti/vibrazioni del dispositivo può essere attivata in base alla diversa modalità selezionata.
-   **Modalità a impulso singolo**

Il dispositivo viene attivato dal rilevamento di un singolo impulso che supera la soglia di rilevamento.

-   **Modalità conteggio impulsi/vibrazione accumulata**

Il dispositivo viene attivato da una delle seguenti condizioni:

1.  Quando**3**i conteggi degli impulsi vengono rilevati all'interno**20****secondi**.
2.  Quando si accumulano vibrazioni minori rilevate con**2 minuti**supera la soglia di rilevamento.

-   Le modalità di rilevamento vengono selezionate utilizzando il ponticello JP3:

![jumper close](<.gitbook/assets/4 (20).png>)Maglione**SU**(Il collegamento del ponticello è inserito):**Modalità a impulso singolo**. (_**Predefinito**_)

![jumper open](<.gitbook/assets/5 (13).png>)Maglione**SPENTO**(Il collegamento del ponticello viene rimosso o parcheggiato su un pin):**Modalità conteggio impulsi/vibrazione accumulata**

-   _**Regolazione della sensibilità**_
-   Utilizzare l'interruttore jumper JP4 e JP5 per determinare la sensibilità richiesta per attivare il contatto porta/sensore vibrazione shock. Fare riferimento alla tabella seguente per selezionare la sensibilità desiderata.

| JP4    | JP5    | Sensibilità agli urti     |
| ------ | ------ | ------------------------- |
| SU     | SPENTO | Basso                     |
| SPENTO | SU     | Medio (_**predefinito**_) |
| SU     | SU     | Alto                      |

-   _**Batteria**_
-   Il contatto porta/sensore vibrazione shock utilizza una batteria al litio CR123 da 3 V come fonte di alimentazione. La batteria è installata nel vano batteria con un isolante della batteria inserito. Per attivare la batteria è sufficiente estrarre l'isolante della batteria.
-   Il contatto della porta/sensore di vibrazione d'urto è in grado di rilevare la condizione di batteria scarica. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per notificare la condizione. Il LED si accende quando il contatto porta/sensore vibrazione shock viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il contatto porta/sensore vibrazione shock interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
-   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _**Protezione antisabotaggio**_
-   Il contatto porta/sensore vibrazione d'urto è protetto da un interruttore antimanomissione che viene compresso contro la superficie di montaggio quando il contatto porta/sensore vibrazione d'urto è montato. Ogni volta che il contatto porta/sensore vibrazione shock viene rimosso dalla superficie montata o il coperchio viene aperto, l'interruttore antimanomissione verrà attivato e il dispositivo invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione.
-   _**Supervision**_
-   Il contatto della porta/sensore di vibrazione d'urto trasmetterà automaticamente periodicamente il segnale di supervisione al pannello di controllo a intervalli casuali di 30-50 minuti.
-   Se il pannello di controllo non ha ricevuto il segnale dal contatto della porta/sensore di vibrazione d'urto per un periodo di tempo prestabilito, il pannello di controllo indicherà che il particolare contatto della porta/sensore di vibrazione d'urto sta riscontrando un problema di mancanza di segnale.
-   _**Modalità di prova**_
-   In modalità normale, premere il pulsante Test per trasmettere un segnale di test e un codice di apprendimento al pannello di controllo. Anche il contatto porta/sensore vibrazione shock entrerà in modalità test per 3 minuti.
-   In modalità test, il LED si accende ogni volta che viene attivato il contatto porta/sensore vibrazione shock.
-   Ogni ulteriore pressione del pulsante Test ripristinerà il tempo della modalità test a 3 minuti.
-   _**Iniziare**_
-   Rimuovere l'isolante della batteria sul contatto porta/sensore vibrazione shock per accendere.
-   Mettere il pannello di controllo in modalità apprendimento (fare riferimento al manuale operativo del pannello)
-   Premere il pulsante Test sul contatto porta/sensore vibrazione shock
-   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
-   Dopo l'apprendimento del contatto porta/sensore vibrazione shock, posizionare il pannello di controllo in (**Prova della camminata**), tenere il contatto porta/sensore vibrazione shock nella posizione desiderata e premere il pulsante Test per trasmettere il segnale di test al pannello di controllo. Se il pannello di controllo si trova nel raggio d'azione del segnale del contatto porta/sensore vibrazioni d'urto, il pannello visualizzerà di conseguenza le informazioni sul contatto porta/sensore vibrazioni d'urto.
-   Procedere con il montaggio e l'installazione una volta accertato che la posizione del contatto porta/sensore vibrazioni-shock funziona correttamente.

Installazione

-   _Montaggio del contatto porta/sensore vibrazione shock_

![](<.gitbook/assets/6 (9).png>)**Montaggio come contatto porta:**

-   Il contatto porta/sensore vibrazione shock deve essere installato in posizione verticale o invertita per garantire che il lato contrassegnato dalla nervatura sia rivolto verso il magnete.
-   La distanza tra il contatto della porta/sensore di vibrazione e shock e il magnete non deve essere superiore a 15 mm quando la porta è chiusa.
-   Evitare di montare il sensore di contatto porta/vibrazione d'urto su una superficie metallica. In caso di montaggio su una superficie metallica, verificare se il contatto della porta/il sensore di vibrazione d'urto può essere attivato quando la porta viene aperta.
-   Montare il dispositivo il più in alto possibile.

**Montaggio come sensore di vibrazioni d'urto:**

-   Montare_**Cemento, cassetta di sicurezza, infissi esterni.**_
-   Se montato sul telaio di una porta/finestra, il dispositivo funge anche da Contatto Porta.
-   Fare riferimento alla tabella seguente per informazioni sul campo di rilevamento di urti/vibrazioni e sull'impostazione della sensibilità in base ai diversi materiali della superficie. Utilizzare il ponticello di regolazione della sensibilità per selezionare la sensibilità desiderata.

|                                                        | Finestra di vetro                       | Porta                                           | Muro di cemento | Scatola di sicurezza                   |   |
| ------------------------------------------------------ | --------------------------------------- | ----------------------------------------------- | --------------- | -------------------------------------- | - |
| Spessore                                               | >5mm                                    | &lt;40 mm                                       | -               | 3 mm                                   |   |
| Materiale                                              | <p>Normale/Temprato/</p><p>Laminato</p> | Legno/Acciaio                                   | Calcestruzzo    | Acciaio + Biossido di silicio          |   |
| Posizione di installazione                             | Cornice della finestra                  | Telaio della porta                              | Parete          | 2 cm di distanza dal perno della porta |   |
| Modalità di rilevamento                                | Modalità a impulso singolo              |  Conteggio degli impulsi/vibrazioni accumulate |                 |                                        |   |
| <p>Sensibilità agli urti</p><p>(area di copertura)</p> | Basso                                   | 2000 mm                                         | 1000 mm         | 500 mm                                 | - |
| medio                                                  | 3000 mm                                 | 2000 mm                                         | 1500 mm         | -                                      |   |
| Alto                                                   | 4000 mm                                 | 3000 mm                                         | 2000 mm         | 1400 mm                                |   |

![](<.gitbook/assets/7 (6) (1).png>)

-   _Procedura di montaggio_

1.  Utilizzare i 2 fori di montaggio sul coperchio posteriore come modello per il posizionamento.
2.  Utilizzare i tasselli forniti per l'installazione su telai di finestre/muri di cemento/cassette di sicurezza.
3.  Avvitare il contatto porta/sensore vibrazione-shock nei tasselli. (Si consiglia di forare quando si monta su acciaio come una cassetta di sicurezza, oppure è anche possibile utilizzare l'adesivo fornito nella confezione).
4.  Montare il magnete sulla porta utilizzando un piccolo pezzo di nastro biadesivo o con le viti fornite.
5.  Per montare il magnete, utilizzare i 2 fori per le viti del magnete come modello per il posizionamento appropriato del foro.

&lt;Nota>

-   Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.

1.  Avvitare il magnete e inserire i due cappucci bianchi nei fori delle viti del magnete per integrità estetica.
2.  L'installazione è ora completa.

\\<NOTE>

-   Non montare il dispositivo su superfici soggette a vibrazioni frequenti, per evitare falsi allarmi.
-   ![](<.gitbook/assets/8 (6) (1).png>)Durante il montaggio su una cassetta di sicurezza, montare il contatto porta/sensore d'urto a non più di 2 cm di distanza dal perno della porta (fare riferimento all'immagine seguente).
