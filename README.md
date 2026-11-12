# RepLog — prototipo iPhone

Piccola web app in italiano per registrare allenamenti Push/Pull, carichi, ripetizioni e serie.

## Funzioni presenti

- Schede Push Day e Pull Day iniziali, con gli esercizi leggibili dalle foto.
- Per ogni singola seduta puoi aggiungere/rimuovere esercizi e serie e modificare peso e ripetizioni. Le modifiche non alterano le schede di partenza.
- Durante l’allenamento mostra serie e risultati dell’ultima seduta dello stesso esercizio.
- Le variazioni delle ripetizioni sono indicate con un valore: blu se aumentano, arancione se diminuiscono; i pesi sono viola.
- Supporta anche esercizi a corpo libero lasciando vuoto il campo kg.
- Storico, carichi migliori, obiettivo settimanale e backup JSON.
- Dati salvati localmente nel browser; non vengono sincronizzati o inviati a un server.

## Prova rapida

Apri `index.html` in un browser desktop per esplorare il prototipo. I file `manifest.webmanifest`, `sw.js` e le icone preparano la versione per l’installazione su iPhone.

## Aggiunta alla schermata Home dell’iPhone

Per installarla come web app, pubblica tutti i file del pacchetto su un hosting HTTPS. Poi apri il link in Safari → **Condividi** → **Aggiungi alla schermata Home**. La chat non l’ha pubblicata online.

I dati rimangono nel browser/dispositivo usato per l’app. Esporta periodicamente un backup JSON da **Profilo**; cancellare i dati di Safari può rimuoverli.
