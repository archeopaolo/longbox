# Longbox PWA

Caricare nella root di GitHub Pages: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon-192.png`, `icon-512.png`.

## Dati e sicurezza
- I dati sono salvati localmente in IndexedDB e sincronizzati con `Longobox/longbox-data.json` su Google Drive.
- Le copertine sono conservate separatamente in `Longobox/Covers`.
- Non caricare su GitHub file JSON della collezione, token OAuth, client secret o backup personali.

## Gestione copertine
- Le nuove copertine vengono caricate automaticamente nella cartella `Covers`.
- Se una copertina viene sostituita, Longbox aggiorna lo stesso file Drive: non crea un duplicato.
- Se una copertina o una scheda vengono eliminate, il relativo file viene eliminato da Drive alla sincronizzazione successiva.
- Il vecchio processo di migrazione delle copertine è stato rimosso.

## Aggiornamento
La cache PWA è `longbox-shell-v13`.
