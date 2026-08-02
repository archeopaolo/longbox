# Longbox PWA

Caricare nella root di GitHub Pages: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon-192.png`, `icon-512.png`.

## Dati e sicurezza
- I dati sono salvati localmente in IndexedDB e sincronizzati con `longbox-data.json` su Google Drive.
- Non caricare su GitHub file JSON della collezione, token OAuth, client secret o backup personali.
- Il Client ID OAuth può essere configurato dall'interfaccia; non usare mai un client secret in questa PWA.

## Aggiornamento
Sostituire tutti i file del pacchetto. La cache PWA è `longbox-shell-v3`; l'app mostra un avviso quando è disponibile una nuova versione.
