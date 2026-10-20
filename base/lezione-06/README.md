# Lezione 6 · Questa parte va bene. Cambiamo il resto

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-06/)

Correggere tono e destinatario senza perdere i fatti già controllati, poi lasciare una nota chiara a chi riprende la bozza.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Materiali di partenza

### Bozza P1 — da correggere

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/materiale-01.txt)

```text
Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Al fine di consentire l'espletamento della pratica, si richiede l'invio di una fotografia dell'articolo e di una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.
```

### Bozza P2 — esempio completo

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/materiale-02.txt)

```text
Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Può inviarci una foto della tazza e una dell'imballaggio? Ci aiuteranno a valutare la segnalazione. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.
```

### Fonti del caso Nora

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/materiale-03.txt)

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

### Confronto A, B e C — testi integrali

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/materiale-04.txt)

```text
 Tre bozze, stesso incarico

Ho preparato tre email per confrontarle. Datevi **2–3 minuti**: quale terreste, quale cambiereste, quale così non usereste? Spiegate il motivo con le cinque domande dei materiali. Quando diciamo «la uso», intendiamo che la teniamo per farla approvare: non la stiamo inviando.

**Bozza A.**

> Oggetto: Ordine Q-184 — rimborso
>
> Buongiorno Nora, ci dispiace che la tazza sia arrivata con il manico rotto e che non possa usarla. Abbiamo registrato la sua richiesta e le confermiamo il rimborso entro cinque giorni. Per completare la pratica, ci invii una foto della tazza e una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci segnalato il problema e per la collaborazione.
>
> Assistenza Quercia

Nota interna A: «Bozza da approvare; decisione della responsabile non registrata.»

**Bozza B.**

> Oggetto: Ordine Q-184 — segnalazione
>
> Gentile Nora, in riferimento alla comunicazione relativa all'ordine Q-184, abbiamo preso atto della rottura del manico da lei segnalata e della sua preferenza per il rimborso. Ai fini dell'istruttoria, si richiede l'inoltro di documentazione fotografica dell'articolo e dell'imballaggio. Acquisiti entrambi gli elementi, le forniremo un aggiornamento entro due giorni lavorativi. L'esito relativo a rimborso o sostituzione resta subordinato alla valutazione della responsabile. Comprendiamo il disagio arrecato dall'impossibilità di utilizzare il prodotto e la ringraziamo per la collaborazione.
>
> Assistenza Quercia

Nota interna B: «Bozza da approvare; decisione della responsabile non registrata.»

**Bozza C.**

> Oggetto: Ordine Q-184 — foto per la segnalazione
>
> Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso. Può inviarci una foto della tazza e una dell'imballaggio? Ci aiuteranno a valutare la segnalazione. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Il rimborso deve ancora essere valutato dalla responsabile; al momento non possiamo confermarlo. Grazie per averci scritto.
>
> Assistenza Quercia

Nota interna C: «Bozza da approvare; decisione della responsabile non registrata.»

Nello svolgimento commenteremo queste stesse email. Non scegliete solo quella che suona meglio: riguardate anche quello che sta promettendo.


```

### Nota interna — esempio completo

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/materiale-05.txt)

```text
Nora chiede il rimborso per la tazza Q-184. Mancano le foto della tazza e dell'imballaggio. La decisione sul rimborso non è registrata. La bozza chiede le foto e un aggiornamento condizionato al loro arrivo; resta da approvare prima dell'invio.
```

## Richieste da copiare

### Chiediamo una modifica precisa


```text
Nella bozza che trovi sotto queste istruzioni sostituisci soltanto la frase che inizia con «Al fine di consentire». Chiedi una foto della tazza e una dell'imballaggio usando parole comuni e dando del lei. Non cambiare nessun'altra frase. Restituisci la bozza completa e, sotto, indica la frase sostituita.
```

Copia questa richiesta e, subito sotto nello stesso messaggio, incolla Bozza P1 — da correggere dai Materiali. Poi invia tutto insieme.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-01.txt)

### Prepariamo la nota interna


```text
Dalla bozza corretta ricava una nota interna di massimo 45 parole per la responsabile di Quercia. Indica richiesta di Nora, foto ancora mancanti, decisione sul rimborso ancora da registrare e approvazione della bozza ancora necessaria. Non aggiungere date o decisioni.
```

Invia nella stessa chat, dopo aver controllato l'email corretta. La nota resta separata dal messaggio per Nora.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-02.txt)

## Esempi da confrontare con il tuo lavoro

Sono esempi preparati per ragionare sui risultati, non risposte garantite dello strumento.

### La bozza da cui ripartiamo

ESEMPIO PREPARATO · Versione con i fatti già corretti

Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Al fine di consentire l'espletamento della pratica, si richiede l'invio di una fotografia dell'articolo e di una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/esempi/esempio-01.txt)

### Una versione che possiamo valutare

ESEMPIO PREPARATO · Versione rivista

Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Può inviarci una foto della tazza e una dell'imballaggio? Ci aiuteranno a valutare la segnalazione. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/esempi/esempio-02.txt)

## Prima di chiudere

- Cambiare solo la richiesta delle foto nella prima revisione.
- Conservare il lei e il dispiacere per il problema.
- Conservare due foto, due giorni lavorativi dopo entrambe, rimborso non confermato.
- La nota interna distingue bozza, approvazione e invio.
- Riaprire il file salvato.
