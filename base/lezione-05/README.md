# Lezione 5 · Rispondiamo a una cliente, con le informazioni che abbiamo

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-05/)

Preparare una prima risposta a un reclamo, trovare una promessa non autorizzata e correggerla mantenendo le parti valide.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Parti da qui

I dati necessari sono tutti in questa pagina. Per fare il caso non devi recuperare una tua vecchia chat.

**Ti serve:** Messaggio, scheda e condizioni inventate di Nora, tutti inclusi qui. Una nuova chat e due documenti da salvare.

**Alla fine avrai:** nora-risposta.txt e nora-nota-interna.txt, coerenti con le foto effettivamente ricevute nel caso.

- Leggi messaggio, scheda e condizioni prima di chiedere la bozza.
- Confronta l’email; correggi promessa e tono fino a una versione utilizzabile.
- Applica l’aggiornamento della foto già ricevuta e cambia anche la nota interna.

**Senza accesso allo strumento:** Correggi le bozze fornite in un editor e confronta con condizioni e variante della foto ricevuta.

[Scarica il pacchetto della lezione](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-05/pacchetto-lezione.zip)

## Materiali di partenza e confronti

### Materiali integrali del caso Nora

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/materiali/materiale-01.txt)

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

<details>
<summary>Nota interna comune a P0 e P1 · apri per confrontare</summary>

### Nota interna comune a P0 e P1

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/materiali/materiale-02.txt)

```text
Nora chiede il rimborso. Aspettiamo le foto e la decisione della responsabile. L'email va approvata prima dell'invio.
```

</details>

<details>
<summary>Email completa — pronta da far approvare · apri per confrontare</summary>

### Email completa — pronta da far approvare

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/materiali/nora-completa.txt)

```text
Oggetto: Ordine Q-184 — foto per la segnalazione

Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso: la responsabile deve ancora valutarlo. Può inviarci una foto della tazza e una dell’imballaggio? Ci aiuteranno a valutare la segnalazione. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.

Assistenza Quercia

NOTA INTERNA SEPARATA
Mancano entrambe le foto e la decisione sul rimborso. Bozza da approvare prima dell’invio.
```

</details>

### Variante — è arrivata una foto

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/materiali/nora-una-foto.txt)

```text
AGGIORNAMENTO INVENTATO
Nora ha mandato la foto della tazza. Manca quella dell’imballaggio. Rimborso ancora da valutare.

EMAIL COMPLETA DI CONFRONTO
Oggetto: Ordine Q-184 — foto dell’imballaggio

Buongiorno Nora, grazie per la foto della tazza. Mi dispiace per il problema che ci ha segnalato. Può inviarci anche una foto dell’imballaggio? Appena avremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Abbiamo preso nota che preferisce il rimborso: la responsabile deve ancora valutarlo e al momento non possiamo confermarlo. Grazie per averci scritto.

Assistenza Quercia

NOTA INTERNA SEPARATA
Foto della tazza ricevuta; manca l’imballaggio. Rimborso da valutare. Bozza da approvare.
```

## Richieste da copiare

### Diamo i materiali, poi l'incarico


```text
Usa i materiali del caso Nora che ti ho fornito. Prepara una risposta per l'ordine Q-184: riconosci il problema e la richiesta di rimborso, chiedi una foto della tazza e una dell'imballaggio. L'aggiornamento arriverà entro due giorni lavorativi dopo entrambe le foto. Il rimborso è ancora da valutare: non prometterlo. Non aggiungere date, cause o altri dati da chiedere. Scrivi oggetto, email di 60–100 parole e firma «Assistenza Quercia». A parte ricorda che rimborso e approvazione sono ancora da decidere. Non inviare nulla.
```

Prima incolla Materiali integrali del caso Nora dalla pagina Materiali. Poi invia questo prompt nella stessa chat.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/prompt/prompt-01.txt)

### Chiediamo una modifica precisa


```text
Cambia solo questa frase: «Abbiamo preso nota che preferisce il rimborso: le confermiamo che lo riceverà entro cinque giorni». La scheda dice che il rimborso non è ancora deciso. Scrivi che abbiamo capito la richiesta di Nora, ma deve ancora valutarla la responsabile. Non promettere il rimborso né una data. Lascia identico tutto il resto, compresi oggetto e firma. Ridammi l’email completa. A parte aggiungi: «Rimborso da valutare; foto mancanti; bozza da approvare».
```

Usa la chat con la bozza sbagliata. Se la tua risposta non ha questo errore, copia l'esempio dai Materiali e lavora su quello.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/prompt/prompt-02.txt)

### Usiamo anche l’informazione appena arrivata


```text
Aggiorna la risposta a Nora: abbiamo ricevuto la foto della tazza; manca solo quella dell’imballaggio. Ringraziala per la foto e chiedi soltanto quella mancante. L’aggiornamento arriva entro due giorni lavorativi da quando avremo entrambe. Il rimborso resta da valutare. Conserva ordine Q-184, tono semplice e firma. Tieni separata la nota interna.
```

Usa la chat con la bozza completa e confronta la nuova richiesta delle foto con il dato ricevuto.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/prompt/prompt-03.txt)

## Esempi da confrontare con il tuo lavoro

Sono esempi preparati per ragionare sui risultati, non risposte garantite dello strumento.

### Leggiamo una risposta con due problemi

ESEMPIO PREPARATO PER IL CORSO

Oggetto: Ordine Q-184 — segnalazione

Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso: le confermiamo che lo riceverà entro cinque giorni. Al fine di consentire l'espletamento della pratica, si richiede l'invio di una fotografia dell'articolo e di una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.

Assistenza Quercia

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/esempi/esempio-01.txt)

### La promessa è stata tolta

ESEMPIO PREPARATO PER IL CORSO

Oggetto: Ordine Q-184 — segnalazione

Buongiorno Nora, mi dispiace per il problema con la tazza e per il fatto che non possa usarla. Abbiamo preso nota che preferisce il rimborso; deve ancora essere valutato dalla responsabile e al momento non possiamo confermarlo. Al fine di consentire l'espletamento della pratica, si richiede l'invio di una fotografia dell'articolo e di una dell'imballaggio. Appena riceveremo entrambe le foto, la aggiorneremo entro due giorni lavorativi. Grazie per averci scritto.

Assistenza Quercia

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/esempi/esempio-02.txt)

### Chiediamo ciò che ci manca

ESEMPIO PREPARATO PER IL CORSO

Grazie per la foto della tazza. Può inviarci anche una foto dell’imballaggio? Appena avremo entrambe, la aggiorneremo entro due giorni lavorativi. La richiesta di rimborso è ancora in valutazione.

Questo è il passaggio da sostituire nell’email. Nella nota interna scriviamo: foto della tazza ricevuta, imballaggio ancora mancante.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-05/esempi/esempio-03.txt)

## Prima di chiudere

- Nessuna promessa di rimborso o data inventata.
- Sono richieste entrambe le foto.
- I due giorni partono dopo entrambe le foto e riguardano l'aggiornamento.
- La nota dice che la bozza è da approvare.
- Confronto P0/P1: una sola frase è cambiata.
