# BustaPaga Check

Progetto Android in italiano per importare buste paga PDF o immagini e riconoscere il testo tramite ML Kit OCR sul dispositivo.

## Stato della versione iniziale
- Selezione di un PDF o di un'immagine.
- Estrazione OCR del testo.
- Tentativo di individuazione della voce del netto tramite alcune diciture comuni.

Questa versione non esegue ancora un controllo completo della correttezza retributiva, fiscale o contrattuale e non sostituisce un consulente del lavoro.

## Compilazione automatica
Il workflow GitHub Actions in `.github/workflows/build-apk.yml` compila un APK di debug a ogni push sul branch `main` e lo pubblica come artifact della workflow run.

## Privacy
Non caricare buste paga reali nel repository. Il documento selezionato viene elaborato localmente.
