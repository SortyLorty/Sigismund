# Sigismund · scheda

Scheda interattiva di Sigismund (D&D 5e 2024, Paladino della Vendetta liv. 6, Crociato Astartes) come web app installabile.

- `index.html` – la scheda, tutto in un file, ritratto compreso
- `manifest.webmanifest`, `icons/` – nome e icona sulla schermata Home (l'elmo di Sigismund)
- `sw.js` – copia offline: dopo la prima apertura online funziona anche senza rete, font compresi

I dati (PF, slot, risorse, zaino, storia) si salvano nel browser del dispositivo.

## Aggiornare
Sostituisci i file e cambia `VERSION` in `sw.js` (es. `sigismund-v2`), così il dispositivo scarica la nuova versione.
