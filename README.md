# Lock-in · diario di Nicola

App da telefono per peso, alimentazione (piano del dott. Mazza e tabelle INRAN), sonno, wellness, BIA e partite del Rugby Rovato.

**Apri l'app:** https://furlinicola04-ux.github.io/loackkaiin/

## Installarla sull'iPhone
1. Apri il link qui sopra con **Safari**.
2. Tocca **Condividi** → **Aggiungi alla schermata Home**.
3. Da lì si apre a schermo intero e funziona anche **senza rete**.

## Dove stanno i dati
I dati restano **solo su quel telefono**, nella memoria del browser: niente server, niente account.
Fai ogni tanto **Altro → Backup dati → Scarica il backup**. Con **Importa** porti i dati su un altro dispositivo (o dalla versione dentro Claude).

## File
- `index.html`: l'app intera, dati alimenti e piano inclusi.
- `sw.js`: service worker che tiene l'app in cache per l'uso offline.
- `manifest.webmanifest`, `icons/`: nome e icona per la schermata Home.
