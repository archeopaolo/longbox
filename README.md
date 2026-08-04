# Longbox PWA

Caricare nella root di GitHub Pages: `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon-192.png`, `icon-512.png`.

## Google Drive
Longbox usa automaticamente questa struttura:

- `Longobox/longbox-data.json`
- `Longobox/Covers/`

Le copertine vengono migrate gradualmente dal JSON alla cartella `Covers` e restano conservate localmente per l'uso offline. Non è richiesto alcun intervento manuale.

## Dati e sicurezza
I dati locali restano in IndexedDB. Non caricare su GitHub JSON della collezione, token OAuth, client secret o backup personali.

## Aggiornamento
La cache PWA è `longbox-shell-v8`.

- Nella sidebar, gli albi e le raccolte sono ordinati per Numerazione assoluta (Legacy), non per Numero.
- Cache PWA: `longbox-shell-v11`.


## Sidebar
La numerazione assoluta è mostrata in forma abbreviata come `LGY #...` nelle voci dei singoli fumetti.


## Correzione stabilità interfaccia
Il caricamento delle copertine da Drive aggiorna soltanto la card interessata e non ricostruisce continuamente la pagina. La cache locale delle immagini viene preservata durante il merge con il JSON remoto.
