# Lezione 7 · La risposta non funziona: che cosa cambiamo?

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-07/)

Scegliere una correzione adatta al problema: risolvere un vincolo impossibile, dare i dati aggiornati, ottenere un’informazione mancante o fare a mano.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Parti da qui

I dati necessari sono tutti in questa pagina. Per fare il caso non devi recuperare una tua vecchia chat.

**Ti serve:** Procedura del banco prestiti, versioni del laboratorio e preventivo incompleto. Sono tre casi distinti, tutti inclusi.

**Alla fine avrai:** Un riepilogo breve, un avviso aggiornato e un preventivo completato solo dopo il dato mancante.

- Scegli fra testo integrale e riepilogo prima di chiedere la sintesi.
- Correggi data, ora e sala del laboratorio; se serve riparti dai dati validi.
- Nel preventivo chiedi il costo mancante. Solo dopo il nuovo dato calcola il totale.

**Senza accesso allo strumento:** Tutti i casi si possono risolvere a mano; resta da provare come risponde la chat.

[Scarica il pacchetto della lezione](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-07/pacchetto-lezione.zip)

## Materiali di partenza e confronti

### Procedura del banco prestiti

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/procedura-prestiti.txt)

```text
CASO INVENTATO
Prima di ritirare un attrezzo, controlla con il referente quali accessori sono inclusi e registra il prestito. Usa l’attrezzo soltanto per il lavoro previsto. Prima di restituirlo, puliscilo, controlla che tutti gli accessori siano presenti e segnala eventuali danni al referente. Non sostituire un pezzo danneggiato senza parlarne con lui. La restituzione viene registrata quando il referente ha controllato attrezzo e accessori. Se manca qualcosa, annota che cosa manca e concorda come completare la restituzione. Conserva la copia della registrazione.
```

### Laboratorio — versioni e dati validi

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/date-laboratorio.txt)

```text
CASO INVENTATO
VECCHIA BOZZA: laboratorio il 4 dicembre 2026 alle 15:00, sala A.
AGGIORNAMENTO CONFERMATO DALL’ORGANIZZATRICE: 5 dicembre 2026 alle 10:00, sala C, 90 minuti; portare il computer.
ERRORE DA CORREGGERE: «Ci vediamo il 4 dicembre in sala A».
NOTA DA USARE PER RIPARTIRE: laboratorio 5 dicembre 2026, ore 10:00, sala C, 90 minuti; portare il computer.
ESEMPIO: Il laboratorio si terrà il 5 dicembre 2026 alle 10:00, in sala C. Durerà 90 minuti. Porta il computer.
```

### Preventivo — prima il dato, poi il totale

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/preventivo-incompleto.txt)

```text
CASO INVENTATO
Servizio 120 euro, IVA esclusa. Consegna a parte, prezzo non indicato.
ERRORE: totale 130 euro, consegna inclusa.
DOMANDA POSSIBILE: Può indicarci il costo della consegna e il totale del preventivo? Il servizio è indicato a 120 euro, IVA esclusa.
NUOVO DATO, DA LEGGERE DOPO LA DOMANDA: il fornitore indica 18 euro per la consegna, IVA esclusa.
TOTALE CORRETTO: 120 + 18 = 138 euro, IVA esclusa. Prima del nuovo dato il totale era incompleto.
```

<details>
<summary>Come sceglierei il prossimo passo · apri per confrontare</summary>

### Come sceglierei il prossimo passo

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/materiali/soluzioni-tre-problemi.txt)

```text
Istruzioni incompatibili: scelgo fra integrale e riepilogo.
Versioni confuse: confronto con l’aggiornamento; se serve riparto da una nota controllata.
Dato mancante: lo chiedo a chi lo conosce; non tratto una stima come prezzo.
Modifica ovvia e breve: posso farla a mano.
Se non posso controllare un’affermazione importante, lascio il punto aperto.

RIEPILOGO DI CONFRONTO DEL BANCO PRESTITI
Prima della restituzione, pulisci l’attrezzo, controlla gli accessori e segnala eventuali danni. Per gli altri passaggi consulta la procedura.
```

</details>

## Richieste da copiare

### Adesso il compito si può fare


```text
Riassumi in massimo 20 parole le azioni da fare prima di restituire un attrezzo, usando la procedura riportata sotto. Il testo integrale resterà allegato. Conserva pulizia, controllo degli accessori e segnalazione dei danni. Non presentare il riepilogo come sostituto dell’intera procedura.
```

Incolla sotto Procedura del banco prestiti e invia tutto insieme.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-01.txt)

### Mettiamo in chiaro quali dati usare


```text
Correggi l’avviso del laboratorio. L’organizzatrice ha confermato il 5 dicembre 2026 alle 10:00, sala C, durata 90 minuti; portare il computer. Questi dati sostituiscono il 4 dicembre alle 15:00 in sala A. Restituisci soltanto l’avviso aggiornato e non mescolare le due versioni.
```

Usa il caso inventato nei Materiali. Controlla data, ora e sala nella risposta.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-02.txt)

### Ripartiamo dalla nota controllata


```text
Scrivi un avviso breve per i partecipanti al laboratorio: 5 dicembre 2026, ore 10:00, sala C, durata 90 minuti. Portare il computer. L’organizzatrice ha confermato questi dati. Non aggiungere indirizzi, link o altre informazioni.
```

Invia in una nuova chat. Confronta l’avviso con la nota dei dati validi, non con la vecchia bozza.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-03.txt)

### Chiediamo il dato alla persona giusta


```text
Dal preventivo inventato sappiamo che il servizio costa 120 euro, IVA esclusa, e che la consegna si paga a parte ma il costo non è indicato. Prepara una domanda breve al fornitore per conoscere quel costo e il totale. Non proporre un prezzo e non inviare il messaggio.
```

Leggi la domanda: chiede ciò che manca, oppure lo ha già deciso al nostro posto?

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/prompt/prompt-04.txt)

## Esempi da confrontare con il tuo lavoro

Sono esempi preparati per ragionare sui risultati, non risposte garantite dello strumento.

### Abbiamo deciso che cosa poteva essere tagliato

ESEMPIO PREPARATO PER IL CORSO

Prima della restituzione, pulisci l’attrezzo, controlla gli accessori e segnala eventuali danni. Per gli altri passaggi consulta la procedura.

Il riepilogo rientra nelle 20 parole. La richiesta iniziale era incompatibile; aggiungere «mi raccomando» non avrebbe risolto il problema.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/esempi/esempio-01.txt)

### L’avviso aggiornato

ESEMPIO PREPARATO PER IL CORSO

Il laboratorio si terrà il 5 dicembre 2026 alle 10:00, in sala C. Durerà 90 minuti. Porta il computer.

Il 4 dicembre e la sala A non devono più comparire. Abbiamo conservato durata e cosa portare.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-07/esempi/esempio-02.txt)

## Prima di chiudere

- La richiesta di riepilogo rinuncia al vincolo di riportare tutto.
- La data valida è 5 dicembre 2026, ore 10:00, sala C.
- Il prezzo della consegna arriva dal fornitore del caso.
- Prima di conoscere i 18 euro, il totale resta incompleto; dopo è 138 euro.
- Ogni intervento è motivato sul problema specifico.
