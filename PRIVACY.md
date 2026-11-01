# Informativa sulla privacy di Tagly

Ultimo aggiornamento: 1 novembre 2026

**Tagly non ha account, pubblicità né statistiche d'uso.** Le foto e i video si riconoscono **sul telefono**: le immagini non escono mai, salvo che tu colleghi la tua chiave Gemini personale (vedi sotto).

- **Foto e video**: Tagly legge solo i file che scegli tu o che condividi con Tagly. Non chiede l'accesso alla Galleria: usa il selettore di Android.
- **Riconoscimento sul telefono**: Tagly capisce cosa mostrano le immagini con due modelli che stanno dentro l'app (Google ML Kit Image Labeling ed EfficientNet-Lite0), senza rete: le immagini e la nota non escono dal telefono. Tagly ha spento le statistiche d'uso tecniche che la libreria ML Kit invierebbe a Google (modello del telefono, tempi, errori): non partono.
- **Solo con la tua chiave Gemini** (facoltativa, *Impostazioni › Collega Gemini*): l'analisi passa prima da *Google Gemini*, con la tua chiave e alle regole di Google. Partono solo immagini rimpicciolite (al massimo 1024 pixel) e **senza dati di posizione né altri metadati**; per i video, alcuni fotogrammi, mai il video intero; insieme alle immagini la nota che scrivi tu («Di cosa parla? Dove sei?»), se la scrivi. La chiave resta sul telefono, cifrata. Se Gemini non risponde, Tagly riconosce le immagini sul telefono.
- Didascalie, statistiche e post programmati non partono mai.
- **Dati aggiornabili**: ogni 12 ore al massimo Tagly scarica da GitHub gli elenchi degli hashtag, gli orari e i limiti delle app, e controlla se c'è una versione nuova (la versione di Google Play riceve gli aggiornamenti da Google Play). GitHub vede l'indirizzo IP della richiesta, come per qualsiasi pagina web.
- **Sul telefono restano**: le statistiche dei tuoi follower, i post programmati (file, nota, didascalia, hashtag, orario del promemoria) e le impostazioni. Se Android non permette di tenere l'accesso a un file fino al promemoria, Tagly ne conserva una copia nella sua memoria e la cancella dopo la pubblicazione o 7 giorni dopo l'orario del promemoria.
- **Permessi**: Internet; notifiche, solo per i promemoria (Android 13 e successivi, chieste al primo «Ricordamelo»); avvio del telefono, per rimettere i promemoria dopo un riavvio; installazione di app, solo nella versione scaricata da GitHub, per installare gli aggiornamenti che accetti.
- **Rapporti per migliorare Tagly** (solo se rispondi "Sì, invia" alla domanda del primo avvio; si spengono quando vuoi in *Impostazioni › Invia rapporti anonimi*, e spegnendoli si cancellano anche quelli non ancora partiti):
  - *quando*: dopo ogni analisi e dopo una chiusura improvvisa dell'app;
  - *cosa contengono*: modello del telefono, versione di Android, processore, versione di Tagly, un codice casuale dell'installazione (non legato a te: cambia se cancelli i dati dell'app), e per ogni analisi solo dati tecnici (numero di foto e video, durata dei video in secondi, servizio usato e tempi (per esempio «locale» con i modelli «mlkit» ed «efficientnet», oppure «gemini»), categoria riconosciuta, quanti hashtag sono stati proposti, eventuali errori e il punto del codice in cui sono successi);
  - *cosa non contengono mai*: immagini, note, didascalie, hashtag, nomi o indirizzi dei file, statistiche dei follower, orari dei promemoria, account o numero di telefono;
  - *come viaggiano*: il rapporto viene cifrato sul telefono (AES-256-GCM con una chiave RSA a 3072 bit) prima di partire; passa da un piccolo servizio su Cloudflare, che non lo può leggere e non salva l'indirizzo IP, e finisce in un archivio privato su GitHub. Lo può aprire solo lo sviluppatore di Tagly;
  - *quanto restano*: il tempo necessario a correggere i problemi; non vengono venduti né condivisi con nessuno;
  - l'ultimo rapporto preparato si può leggere nel telefono, in *Impostazioni › Mostra l'ultimo rapporto*.
- **Pubblicazione, Dona, Suggerimenti**: questi pulsanti aprono altre app (Instagram, TikTok) o il browser (Ko-fi, GitHub). Da lì valgono le regole di quei servizi.

Per domande: [apri una segnalazione](https://github.com/vincenzociriello91-hub/TaglyApp-download/issues).
