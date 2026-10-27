# Lezione 2 · Come fa a rispondere? E perché a volte sbaglia?

[Tutte le lezioni](../../README.md)

[Apri i materiali con i pulsanti per copiare](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-02/)

Capire la differenza fra applicare una formula, classificare una mail e generare un testo; scegliere una prova adatta a ciascun risultato.

Qui trovi i dati degli esercizi e i testi da copiare nella chat. I casi sono inventati. Le risposte di esempio sono preparate per il corso: la tua risposta può essere diversa.

Puoi leggere tutto qui senza un account GitHub. Il riquadro di ogni richiesta permette di copiare il testo. Per avere un file sul computer, apri il TXT collegato e salvalo. Le tue prove vanno nella cartella personale `corso-base`.

## Parti da qui

I dati necessari sono tutti in questa pagina. Per fare il caso non devi recuperare una tua vecchia chat.

**Ti serve:** I tre casi e la tabella delle sei mail. Bastano un foglio e una calcolatrice; non serve una chat.

**Alla fine avrai:** Una riga per formula, filtro e messaggio: errore possibile e controllo adatto.

- Applica la regola a 9, 10 e 12.
- Nelle sei mail trova i due errori del filtro.
- Confronta il messaggio con gli appunti di Luca e scegli un controllo per ciascun caso.

**Senza accesso allo strumento:** Il lavoro completo si può fare sui materiali, anche senza usare un chatbot.

[Scarica il pacchetto della lezione](https://mirtexxan.github.io/ai-nel-lavoro/base/lezione-02/pacchetto-lezione.zip)

## Materiali di partenza e confronti

### Tre casi: formula, spam e messaggio

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-02/materiali/materiale-01.txt)

```text
A. Una formula scritta da una persona mostra «da riordinare» quando la quantità è minore di 10. Prova con 9, 10 e 12.
B. Un modello addestrato su esempi prova a distinguere spam e mail utili. Due errori inventati: una fattura attesa finisce nello spam; una pubblicità non richiesta rimane in arrivo. Non sono misurazioni di un filtro.
C. Un modello linguistico scrive a un cliente usando gli appunti forniti.
Per ogni caso scrivi una riga: che cosa fa il sistema, un errore possibile, una prova per accorgertene. B e C usano entrambi un modello addestrato: il compito è diverso.
```

### Sei mail per provare il controllo

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-02/materiali/sei-mail.txt)

```text
CASO INVENTATO — Non è un test di un filtro reale.
Mail | Contesto noto | Filtro
1. Fattura del fornitore | Acquisto atteso | Spam
2. Vinci un premio | Nessuna richiesta | Spam
3. Conferma riunione | Incontro concordato | Posta in arrivo
4. Sconto del 90% | Promozione non richiesta | Posta in arrivo
5. Documento del collega | File atteso | Posta in arrivo
6. Offerta non richiesta | Nessun rapporto con il mittente | Spam

PROVA
Indica le due classificazioni sbagliate e la loro conseguenza.

CONFRONTO
Mail 1: comunicazione utile persa nello spam; controllo anche quella cartella per ritrovare la fattura. Mail 4: promozione indesiderata rimasta in arrivo; devo filtrarla. Gli altri quattro esiti sono coerenti con il contesto del caso. Queste sei mail servono a capire gli errori, non a stimare quanto sia affidabile un prodotto.
```

### Appunti del messaggio — per fare il caso anche partendo da qui

[Apri il TXT](https://raw.githubusercontent.com/mirtexxan/ai-nel-lavoro/main/base/lezione-02/materiali/appunti-messaggio.txt)

```text
Caso inventato. Elisa scrive a Luca. Incontro iniziale: 12 novembre 2026, ore 10:00. Proposta: 13 novembre 2026, ore 15:00. Durata: 30 minuti. Modalità: online. Il link arriverà dopo la conferma di Luca. Disponibilità di Luca: non nota. Motivo dello spostamento: non fornito. Preparare una bozza senza inviarla.
```

## Richieste da copiare

Questa lezione lavora sui casi e sui confronti riportati nei materiali di partenza.

## Prima di chiudere

- Prova la formula con 9, 10 e 12: l’avviso deve comparire soltanto con 9.
- Nel filtro distingui una mail utile finita nello spam da uno spam lasciato in arrivo.
- Per il messaggio, cerca negli appunti la conferma attribuita a Luca: se manca, la frase va corretta.
- Distingui l’addestramento del modello dalle informazioni aggiunte nella chat.
- Scegli un controllo sul caso: formula e scorte, mail classificate oppure appunti originali.
