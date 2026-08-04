# Longbox PWA

Caricare nella root di GitHub Pages: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon-192.png`, `icon-512.png`.

## Dati e sicurezza
- I dati sono salvati localmente in IndexedDB e sincronizzati con `longbox-data.json` su Google Drive.
- Non caricare su GitHub file JSON della collezione, token OAuth, client secret o backup personali.

## Modello editoriale
- Numero: numero dell'albo nella specifica run.
- Numerazione assoluta (Legacy): progressivo storico della testata.
- Volume / Run e Ciclo narrativo sono campi distinti.
- Mercato e Lingua distinguono edizioni italiane, USA e altre.
- I Contenuti originali possono essere associati a qualsiasi formato e comprendono Mercato, Serie originale, Volume / Run, dal/al numero.

## Aggiornamento
La cache PWA è `longbox-shell-v7`.


## Cartella Google Drive
- Longbox crea o riutilizza automaticamente la cartella `Longobox`.
- `longbox-data.json` viene conservato dentro questa cartella.
- Se il file esistente si trova nella root di Drive, viene spostato automaticamente alla prima sincronizzazione.
