# Lezione 7 · Quando una richiesta migliore non basta

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-07/)

Riconoscere perché una risposta non funziona e scegliere se chiarire, fornire una fonte, dividere il compito, ripartire o fermarsi.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Materiali di partenza

### Procedura Quercia e fonti complete

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/materiale-01.txt)

```text
# Materiali — ordine Q-184, tazza arrivata danneggiata

Versione 0.2.0 · 12 ottobre 2026. Questo negozio non esiste: nome, ordine e messaggio sono inventati per l'esercizio. Anche le condizioni sono inventate; non sono una spiegazione dei diritti dei consumatori.

## C — condizioni operative del caso, versione corrente

**C1.** Quercia vende tazze. L'assistenza scrive la risposta; la responsabile deve approvarla prima che venga inviata. È lei a decidere come gestire il reclamo.

**C2.** Se una cliente dice che l'articolo è arrivato danneggiato, chiediamo una foto dell'articolo e una dell'imballaggio, se non le ha già mandate. Per questa prima risposta non servono indirizzo, documento o altri dati.

**C3.** La responsabile deve ancora valutare se rimborsare o sostituire l'articolo. Finché non abbiamo la sua decisione, non promettiamo il rimborso, una data o la spedizione di una nuova tazza.

**C4.** Possiamo dire alla cliente che la aggiorneremo entro due giorni lavorativi dopo aver ricevuto entrambe le foto. Entro quei due giorni le daremo notizie: non stiamo dicendo che il problema sarà già risolto. Non calcoliamo una data sul calendario per questo esercizio.

**C5.** Scriviamo in modo chiaro: ci dispiace per il problema, chiediamo le foto e spieghiamo cosa succede dopo. Non diamo la colpa alla cliente o al corriere: non sappiamo come si è rotta la tazza. Nell'esercizio prepariamo la risposta senza inviarla.

## R — messaggio della cliente

**R1.** «Buongiorno, la tazza dell'ordine Q-184 è arrivata con il manico rotto. L'ho aperta oggi e non posso usarla. Non ho allegato foto. Vorrei il rimborso, non un'altra tazza. Come facciamo? Grazie, Nora.»

È Nora a dirci che la tazza è rotta. Le foto non le abbiamo ancora. Vuole il rimborso: questo lo sappiamo, ma nessuno lo ha ancora approvato.

## O — scheda interna dell'ordine

**O1.** Ordine Q-184: una tazza, consegna registrata. La scheda non riporta una data da usare nella risposta.

**O2.** Non sono presenti foto dell'articolo o dell'imballaggio.

**O3.** Non è registrata alcuna decisione della responsabile su rimborso o sostituzione.

## V — esempio di voce, da altro caso

**V1.** «Mi dispiace per il problema. Può inviarci una foto dell'etichetta? Ci aiuta a capire quale articolo ha ricevuto.»

Qui ci interessa come è scritta: chiede una cosa precisa e spiega a cosa serve. L'etichetta riguarda un altro ordine: per Nora ci servono tazza e imballaggio. Confrontiamola con «Al fine di consentire l'espletamento della pratica, si richiede idonea documentazione probatoria».

## Che cosa sappiamo e che cosa manca

| Tipo | Informazione disponibile | Fonte |
|---|---|---|
| Confermato dalla scheda | Ordine Q-184, una tazza, consegna registrata. | O1 |
| Segnalato | Manico rotto, apertura oggi, impossibilità di usare la tazza. | R1 |
| Preferenza | La cliente chiede il rimborso, non una sostituzione. | R1 |
| Confermato dalla scheda | Foto assenti e decisione assente. | O2/O3 |
| Vincolo | Chiedere due foto; approvazione umana; aggiornamento condizionato entro due giorni lavorativi. | C1–C4 |
| Ignoto | Causa del danno, esito della valutazione, eventuale disponibilità di una sostituzione, data/esecuzione del rimborso. | Non stabiliti nei materiali |

Per questa email non ci servono prezzo, recapiti o data esatta della consegna. Per decidere il rimborso servirebbero altre informazioni. Le foto dobbiamo chiederle a Nora: ChatGPT non può averle se non gliele diamo.

## La risposta che ci serve e come la controlliamo

Scrivi un'email in italiano, con oggetto, **60–100 parole** nel corpo e firma «Assistenza Quercia». Nora deve capire che abbiamo letto il suo problema e la richiesta di rimborso, quali foto deve mandarci e quando le daremo notizie. A parte, lascia una riga per chi riprende il lavoro: il rimborso è ancora da decidere e l'email è da approvare. Non inviarla.

I codici K servono a ritrovare i controlli nei documenti di preparazione. A chi segue bastano le domande:

| Criterio | Controllo concreto |
|---|---|
| K1 · Ha usato le informazioni giuste? | Ordine e richiesta devono corrispondere al messaggio e alla scheda. Non aggiungere cause del danno o decisioni che non ci sono. Controlla R1/O1/O3. |
| K2 · Ha promesso qualcosa di troppo? | Niente rimborso o sostituzione già confermati. I due giorni lavorativi per l'aggiornamento partono dopo entrambe le foto. Controlla C3/C4. |
| K3 · Nora capisce cosa deve fare? | Deve mandare una foto della tazza e una dell'imballaggio. Niente altri dati. Deve essere chiaro che abbiamo capito che vuole il rimborso. Controlla C2/R1/O2. |
| K4 · Si legge senza fatica? | Parole comuni, richiesta chiara, oggetto e firma. Il corpo resta tra 60 e 100 parole. |
| K5 · Sappiamo cosa manca? | La nota ricorda che il rimborso non è deciso e l'email è da approvare. Aver scritto la bozza non significa poterla inviare. |

Possiamo scrivere due email diverse e farle funzionare entrambe. Ma se una promette soldi che nessuno ha approvato, il fatto che sia scritta bene non la salva.


```

### P0 — bozza sbagliata

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/materiale-02.txt)

```text
Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso: le confermiamo che lo riceverà entro cinque giorni. Al fine di consentire l'espletamento della pratica, si richiede l'invio di una fotografia dell'articolo e di una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.
```

### P2 — esempio corretto dopo estrazione e revisione

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/materiale-03.txt)

```text
Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Può inviarci una foto della tazza e una dell'imballaggio? Ci aiuteranno a valutare la segnalazione. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.
```

### Caso data vecchia — errore ed esempio corretto

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/materiale-04.txt)

```text
ERRORE PREPARATO
Ciao Luca, confermo il nostro incontro del 12 novembre 2026 alle 10:00.

ESEMPIO CORRETTO
Ciao Luca, possiamo spostare l'incontro dal 12 novembre 2026 alle 10:00 al 13 novembre 2026 alle 15:00? Restano 30 minuti online. Se per te va bene, ti invio il link dopo la tua conferma. Grazie, Elisa.

CONTROLLO
Entrambe le date; la nuova data è una proposta; durata e modalità conservate; nessun motivo inventato.
```

### Otto problemi riconoscibili nei tre video su Nora

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/materiale-05.txt)

```text
1. Richiesta generica → precisare il risultato (lezione 5).
2. Promessa inventata → verificare sulla fonte (5 e 7).
3. Risposta al compito sbagliato → distinguere bozza e decisione (5).
4. Tono burocratico → sostituire la frase precisa (6).
5. Modifica delle parti corrette → dichiarare cosa preservare e confrontare (6).
6. Vincolo ignorato o incompatibile → verificarlo o risolverlo (7).
7. Informazione superata nel contesto → riepilogare dati validi (7).
8. Risultato non verificabile → lasciare aperto il punto o fermarsi (7).
```

## Richieste da copiare

### Prima leggiamo le condizioni


```text
Leggi questa procedura inventata di Quercia. Chiedere una foto della tazza e una dell'imballaggio. Dare un aggiornamento entro due giorni lavorativi dalla ricezione di entrambe. Rimborso e sostituzione richiedono una decisione della responsabile, non ancora registrata. Elenca: che cosa chiedere; che cosa possiamo promettere e a quale condizione; che cosa non è ancora deciso. Non scrivere l'email.
```

Invia questa richiesta in una nuova chat. Prima di proseguire, confronta le condizioni estratte con la procedura nei Materiali.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-01.txt)

### Ora correggiamo la bozza


```text
Usa soltanto le condizioni appena controllate. Nella bozza che trovi sotto queste istruzioni elimina la promessa di rimborso entro cinque giorni. Spiega che la responsabile deve ancora valutarlo. Conserva le informazioni corrette; chiedi le due foto con parole semplici, dando del lei. Restituisci una bozza da approvare, senza inviarla.
```

Nello stesso messaggio incolla, sotto la richiesta, P0 — bozza sbagliata dai Materiali. Poi invia e confronta la nuova email con la procedura.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-02.txt)

### Ripartiamo con un contesto pulito


```text
Elisa deve proporre a Luca di spostare l'incontro dal 12 novembre 2026 alle 10:00 al 13 novembre 2026 alle 15:00. Durata 30 minuti, online. Luca non ha ancora confermato; il link sarà inviato dopo la conferma. Non conosco il motivo dello spostamento. Scrivi una bozza breve dando del tu, senza inventare altri fatti.
```

Apri una nuova chat e incolla questa richiesta completa. Nella risposta cerca entrambe le date e la domanda di conferma.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-03.txt)

## Prima di chiudere

- Le condizioni estratte coincidono con la procedura.
- Il rimborso non è promesso.
- La data vecchia non sostituisce quella proposta.
- La scelta fra riassunto e testo integrale è esplicita.
- Sa motivare quando chiedere un dato o fermarsi.
