# Lezione 8 · Da questi appunti si capisce che cosa dobbiamo fare?

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-08/)

Ricavare un riepilogo e una lista di azioni da appunti, senza trasformare proposte e scadenze mancanti in decisioni.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Materiali di partenza

### Appunti integrali

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-08/materiali/materiale-01.txt)

```text
CASO INVENTATO — Riunione del laboratorio Betulla, 6 novembre 2026.
Sito: Giulia manda a Omar i testi dei tre servizi entro il 10 novembre. Omar pubblica dopo il via libera di Giulia; nessuna data fissata per pubblicare.
Ordini: Davide controlla entro il 9 novembre quante scatole piccole sono rimaste e manda il numero a Giulia.
Orari: Giulia propone di aprire anche il sabato mattina. Omar chiede di sentire prima le altre due persone del laboratorio. Decisione rimandata, nessun incaricato né scadenza assegnati.
Foto: quelle attuali sono scure. Davide si offre di fare una prova con luce naturale; accettiamo la prova, senza fissare una data.
Prossimo incontro: da concordare. Budget fotografie non discusso.
```

### Tabella completa — esempio preparato

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-08/materiali/materiale-02.txt)

```text
AZIONE | PERSONA | SCADENZA | CONDIZIONE
Inviare a Omar i testi dei tre servizi | Giulia | 10 novembre 2026 | —
Contare scatole piccole e comunicare il numero a Giulia | Davide | 9 novembre 2026 | —
Pubblicare il sito | Omar | Da definire | Dopo il via libera di Giulia
Fare una prova fotografica con luce naturale | Davide | Da definire | Prova accettata

PROPOSTA APERTA
Apertura del sabato: decisione rimandata, dopo aver sentito le altre due persone. Incaricato e scadenza da definire.

DOMANDE
Chi raccoglie i pareri sul sabato, ed entro quando?
Quando si tiene il prossimo incontro?

NOTA
Il budget delle foto non è stato discusso. La prova fotografica non equivale a un acquisto approvato.
```

## Richieste da copiare

### Chiediamo un riepilogo e una tabella delle azioni


```text
Ti invio nel prossimo messaggio gli appunti di una riunione inventata di Betulla. Prepara un riepilogo entro 70 parole, poi una tabella con azione, persona, scadenza e condizione. Separa le proposte non approvate e le domande aperte. Dove manca persona o data scrivi «da definire». Non inventare decisioni. Non assegnare incarichi che gli appunti non assegnano.
```

Invia il prompt; nel messaggio successivo incolla Appunti integrali dai Materiali. Aspetta il risultato prima di correggere.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-08/prompt/prompt-01.txt)

### Correggiamo il punto sul sabato


```text
La riga sul sabato trasforma una proposta in decisione e inventa incaricato e scadenza. Eliminala dalle azioni concordate. Mettila fra i punti aperti: apertura del sabato da valutare dopo aver sentito le altre persone. Persona incaricata e data sono da definire. Conserva le quattro azioni confermate dagli appunti.
```

Se la tua risposta contiene quell'errore, correggila nella stessa chat. Altrimenti usa la riga errata preparata nei Materiali.

[Apri il TXT della richiesta](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-08/prompt/prompt-02.txt)

## Esempi da confrontare con il tuo lavoro

Sono esempi preparati per ragionare sui risultati, non risposte garantite dello strumento.

### Un riepilogo possibile

ESEMPIO PREPARATO

Betulla aggiorna i testi dei tre servizi e controlla le scatole piccole. La pubblicazione del sito resta subordinata al via libera di Giulia. È stata accettata una prova fotografica di Davide, senza scadenza. L'apertura del sabato è solo una proposta; il prossimo incontro è da concordare.

[Apri il TXT dell’esempio](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-08/esempi/esempio-01.txt)

## Prima di chiudere

- Quattro azioni effettivamente concordate.
- Pubblicazione dopo via libera, senza data inventata.
- Sabato come proposta aperta.
- Foto senza budget o scadenza inventati.
- Originale e risultato salvati insieme.
