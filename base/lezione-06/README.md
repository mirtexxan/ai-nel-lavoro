# Lezione 6 · Stessi fatti, persone diverse: cambiamo come li scriviamo

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-06/)

Rivedere una frase e adattare le stesse informazioni a un collega e a un cliente, conservando ciò che devono sapere.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Parti da qui

I dati necessari sono tutti in questa pagina. Per fare il caso non devi recuperare una tua vecchia chat.

**Ti serve:** Scheda Olmo e frase di ripasso sulle foto, entrambe incluse. Nessun file della lezione 5 è necessario.

**Alla fine avrai:** olmo-clienti.txt e olmo-colleghi.txt, con gli stessi fatti e istruzioni adatte ai due destinatari.

- Rivedi la breve frase sulle foto. Poi passa alla Scheda Olmo.
- Prepara avviso clienti e nota ai colleghi; confronta le informazioni scelte.
- Prova la riga breve e l’esempio di voce. Salva i due testi per destinatario.

**Senza accesso allo strumento:** Prepara i due testi a mano dalla Scheda Olmo e usa le soluzioni per confrontarli.

[Scarica il pacchetto della lezione](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-06/pacchetto-lezione.zip)

## Materiali di partenza e confronti

### Ripasso completo — richiesta delle foto

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/ripasso-nora.txt)

```text
CASO INVENTATO — Una cliente segnala una tazza rotta. Mancano foto della tazza e dell’imballaggio. Aggiornamento entro due giorni lavorativi dopo entrambe le foto. Rimborso ancora da valutare.
Frase da cambiare: «Al fine di consentire l’espletamento della pratica, si richiede l’invio di una fotografia dell’articolo e di una dell’imballaggio».
Deve restare il lei. Vogliamo una richiesta semplice delle due foto.
```

### Scheda Olmo

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/scheda-olmo.txt)

```text
CASO INVENTATO — Negozio Olmo, avviso del 1 dicembre 2026.
Il 2 dicembre, dalle 18:00 alle 18:30, il sito sarà consultabile ma non si potranno inviare nuovi ordini. Gli ordini già ricevuti restano registrati.
Paolo deve preparare l’avviso entro le 17:00. Lina controlla che sia visibile prima delle 18:00.
Non sono previsti sconti e non è fornito un recapito alternativo per ordinare.
Occorrono due testi: una nota operativa per Paolo e Lina, e un avviso entro 60 parole per i clienti del sito. I nomi e le scadenze interne non servono nell’avviso pubblico.
```

<details>
<summary>Testi completi — confronto e salvataggio · apri per confrontare</summary>

### Testi completi — confronto e salvataggio

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/materiali/olmo-soluzioni.txt)

```text
AVVISO CLIENTI
Il 2 dicembre, dalle 18:00 alle 18:30, non potrai inviare nuovi ordini. Il sito resterà consultabile e gli ordini già ricevuti resteranno registrati. Potrai tornare a ordinare dalle 18:30.

RIGA BREVE, CON AVVISO ESTESO SOTTO
2 dicembre,18:00–18:30: invio di nuovi ordini sospeso. Il sito resta consultabile.

NOTA PER I COLLEGHI
Paolo, prepara entro le 17:00 l’avviso per il 2 dicembre: nuovi ordini sospesi dalle 18:00 alle 18:30, sito consultabile e ordini ricevuti ancora registrati. Lina, controlla che l’avviso sia visibile prima delle 18:00.

CONTROLLO
Fonte: Scheda Olmo. Intervallo e servizi disponibili coincidono; Paolo prepara, Lina controlla; nessuno ha promesso sconti o spedizioni. I nomi interni non compaiono nell’avviso pubblico.
```

</details>

## Richieste da copiare

### Cambiamo una frase, teniamo le due foto


```text
Riscrivi questa frase con parole comuni e dando del lei. Deve chiedere una foto della tazza e una dell’imballaggio: «Al fine di consentire l’espletamento della pratica, si richiede l’invio di una fotografia dell’articolo e di una dell’imballaggio». Non aggiungere promesse o tempi. Restituisci solo la frase.
```

Prova questa richiesta in una nuova chat. Confronta quali foto chiede la risposta.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-01.txt)

### La richiesta per l’avviso


```text
Dalla Scheda Olmo riportata sotto scrivi un avviso per i clienti del sito, entro 60 parole. Di’ quando non si potranno inviare nuovi ordini, che il sito resta consultabile e che gli ordini già ricevuti restano registrati. Usa parole comuni. Togli nomi e incarichi interni. Non aggiungere sconti, cause tecniche o recapiti per ordinare.
```

Aggiungi sotto la Scheda Olmo e invia tutto insieme nella nuova chat.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-02.txt)

### Adesso scriviamo a Paolo e Lina


```text
Dalla stessa Scheda Olmo prepara una nota operativa per Paolo e Lina, entro 80 parole. Indica cosa fa ciascuno e le rispettive scadenze. Riporta data, intervallo della sospensione dei nuovi ordini e ciò che rimane disponibile. Non aggiungere incarichi. Usa un tono diretto fra colleghi.
```

Continua nella stessa chat, dove hai già dato la Scheda Olmo.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-03.txt)

### Facciamone anche una riga breve


```text
Dalla versione corretta per i clienti ricava una riga di massimo 25 parole. Conserva il 2 dicembre, l’intervallo 18:00–18:30 e la sospensione dei nuovi ordini. Non scrivere che tutto il sito è chiuso. Il testo esteso resterà subito sotto la riga breve.
```

Invia nella stessa chat. Leggi riga breve e testo esteso insieme, come compariranno sul sito.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-04.txt)

### Prendiamo il modo di scrivere, non i fatti dell’esempio


```text
Rivedi la nota operativa per Paolo e Lina usando frasi dirette e parole comuni, come in questo esempio di voce: «Ciao Giulia, puoi mandarmi il file entro le 16? Mi serve per chiudere il lavoro di oggi. Grazie». Usa l’esempio solo per il modo di scrivere: non copiarne nomi, orario o incarico. Conserva tutti i dati e gli incarichi della Scheda Olmo.
```

Confronta la nuova nota con la scheda, cercando anche eventuali dettagli copiati dall’esempio.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/prompt/prompt-05.txt)

## Esempi da confrontare con il tuo lavoro

Sono esempi preparati per ragionare sui risultati, non risposte garantite dello strumento.

### Un avviso che i clienti possono capire

ESEMPIO PREPARATO PER IL CORSO

Il 2 dicembre, dalle 18:00 alle 18:30, non potrai inviare nuovi ordini. Il sito resterà consultabile e gli ordini già ricevuti resteranno registrati. Potrai tornare a ordinare dalle 18:30.

Non abbiamo scritto «sito chiuso»: si può ancora consultare. Non abbiamo promesso che gli ordini siano già spediti.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/esempi/esempio-01.txt)

### Nella nota interna mettiamo gli incarichi

ESEMPIO PREPARATO PER IL CORSO

Paolo, prepara entro le 17:00 l’avviso per il 2 dicembre: nuovi ordini sospesi dalle 18:00 alle 18:30, sito consultabile e ordini ricevuti ancora registrati. Lina, controlla che l’avviso sia visibile prima delle 18:00.

La nota dice chi deve fare cosa. Non è il testo da incollare sul sito.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-06/esempi/esempio-02.txt)

## Prima di chiudere

- Nell’avviso restano data, intervallo e stato degli ordini ricevuti.
- Il sito consultabile non diventa sito chiuso.
- Paolo prepara entro le 17:00; Lina controlla prima delle 18:00.
- L’esempio di voce non introduce Giulia o le 16 nei dati di Olmo.
- Due file distinti, aperti dopo il salvataggio.
