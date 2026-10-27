# Lezione 11 · Quale offerta conviene? Prima rimettiamo in ordine i numeri

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-11/)

Confrontare due offerte sullo stesso periodo, controllare i calcoli e distinguere differenza in euro, percentuale e scelta finale.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Parti da qui

I dati necessari sono tutti in questa pagina. Per fare il caso non devi recuperare una tua vecchia chat.

**Ti serve:** Le due offerte inventate e una calcolatrice. Puoi fare il confronto anche senza chat.

**Alla fine avrai:** Tabella dei costi del primo anno e dei due anni, conti rifatti e punti ancora da chiedere.

- Metti le offerte sullo stesso periodo e scrivi le formule.
- Rifai totali e percentuale in calcolatrice.
- Confronta solo secondo anno, totale di due anni e variante con costo iniziale sconosciuto.

**Senza accesso allo strumento:** Usa offerte e calcolatrice: sono sufficienti per fare e controllare tutti i conti.

[Scarica il pacchetto della lezione](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-11/pacchetto-lezione.zip)

## Materiali di partenza e confronti

### Offerte complete

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/materiali/materiale-01.txt)

```text
OFFERTE INVENTATE — Stesso servizio di prenotazione, un solo utente, stesse funzioni, nessuno sconto. Importi IVA esclusa.
OFFERTA A: 29 euro al mese, costo iniziale una tantum di 120 euro. Confronto su dodici mesi completi. Nessun altro costo nel caso.
OFFERTA B: 360 euro per dodici mesi, pagati in anticipo, costo iniziale una tantum di 40 euro. Nessun altro costo nel caso.
Non stiamo valutando condizioni di recesso, qualità o funzioni aggiuntive: non sono descritte. Il primo confronto richiesto riguarda solo il costo totale dei primi dodici mesi.
```

<details>
<summary>Soluzione completa — primo e secondo anno · apri per confrontare</summary>

### Soluzione completa — primo e secondo anno

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/materiali/materiale-02.txt)

```text
PRIMO ANNO
A: 29 × 12 + 120 = 468 euro.
B: 360 + 40 = 400 euro.
Differenza: 468 − 400 = 68 euro.
Risparmio di B rispetto ad A: 68 / 468 × 100 = 14,5299...%, arrotondato 14,5%.
A costa il 17% in più rispetto a B: 68 / 400 × 100.

SOLO SECONDO ANNO, A PREZZI INVARIATI
A: 29 × 12 = 348 euro.
B: 360 euro.
A costa 12 euro in meno in quel solo anno.

NOTA DA SALVARE
Confrontati primi dodici mesi, stesso servizio e utente, importi IVA esclusa, costi iniziali contati una sola volta. Controllati con calcolatrice i totali e la percentuale. Recesso e altre condizioni non descritte restano da chiedere.
```

</details>

### Variante — costo iniziale sconosciuto

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/materiali/costo-mancante.txt)

```text
CAMBIA UN SOLO DATO
L’offerta B indica 360 euro per dodici mesi, ma non specifica il costo iniziale. Tutto il resto del caso è uguale.

PROVA
Possiamo ancora dire che B costa meno nel primo anno? Scrivi il conto senza inventare il dato.

CONFRONTO
A = 468 euro. B = 360 euro + costo iniziale non noto. B costa meno soltanto se il costo iniziale è inferiore a 108 euro; con 108 i totali coincidono. Prima della scelta chiedo quel costo. Il prezzo più basso non risolve le altre condizioni mancanti.
```

<details>
<summary>Due anni — soluzione completa · apri per confrontare</summary>

### Due anni — soluzione completa

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/materiali/due-anni.txt)

```text
A prezzi invariati, primi 24 mesi: A = 29 × 24 + 120 = 816 euro; B = 360 × 2 + 40 = 760 euro. Differenza 56 euro a favore di B.
Controllo: primo anno più secondo anno = 468 + 348 e 400 + 360.
Solo secondo anno: A348, B360. Tutti gli importi IVA esclusa, stesso servizio e utente.
```

</details>

## Richieste da copiare

### Facciamo mostrare dati e formula


```text
Confronta il costo dei primi dodici mesi. A costa 29 euro al mese più 120 euro iniziali una tantum; B costa 360 euro per dodici mesi più 40 euro iniziali una tantum. Stesso servizio e utente, IVA esclusa, nessun altro costo nel caso. Mostra costi ricorrenti, iniziali, formule e totali. Calcola la differenza in euro e quanto B costa in meno in percentuale rispetto ad A. Non dedurre condizioni non fornite.
```

Copia la richiesta dai Materiali in una nuova chat. Tieni accanto le offerte e la calcolatrice per rifare i conti.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/prompt/prompt-01.txt)

### Correggiamo l'interpretazione, poi il conto


```text
Hai moltiplicato anche i 120 euro iniziali per dodici. Sono un costo una tantum. Per A usa 29 × 12 + 120. Mantieni il periodo di dodici mesi e gli importi IVA esclusa. Ricalcola il totale e confrontalo con B, che costa 360 + 40.
```

Se il tuo conto è già giusto, usa l'errore preparato per provare la correzione. Ricalcola anche con la calcolatrice.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/prompt/prompt-02.txt)

### E nei primi due anni, messi insieme?


```text
Riprendi le offerte A e B già confrontate. A prezzi invariati, calcola il costo cumulato dei primi ventiquattro mesi. Conta i costi iniziali una sola volta. Distingui il totale dei due anni dal costo del solo secondo anno. Mostra le formule e la differenza in euro.
```

Invia nella stessa chat. Prima di guardare il risultato, scrivi le due formule sul foglio.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-11/prompt/prompt-03.txt)

## Prima di chiudere

- Totali del primo anno: 468 e 400 euro.
- Costo iniziale contato una sola volta.
- Differenza di 68 euro; risparmio del 14,5% rispetto ad A.
- Solo secondo anno distinto dal totale dei primi due anni.
- Nessuna condizione di recesso inventata.
