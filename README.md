# Omicron Pokédeck

App web per la collezione personale e l'inventario del negozio Emporio Omicron: carte Pokémon con prezzi Cardmarket e TCGplayer, scanner da foto, wishlist e andamento di mercato.

**Apri l'app:** https://mircomirco666-max.github.io/omicron-pokedeck/

## Installarla su iPhone
1. Apri il link in Safari.
2. Tocca Condividi, poi «Aggiungi alla schermata Home».

## Dove stanno i dati
- Le carte, la wishlist e lo storico dei valori restano nel browser del dispositivo (IndexedDB). Non vengono inviati a nessun server.
- Per spostarli su un altro dispositivo: Altro → Esporta backup, poi Importa backup sull'altro.
- Catalogo, immagini e prezzi arrivano da [TCGdex](https://tcgdex.dev) (prezzi Cardmarket in euro e TCGplayer in dollari).
- Lo scanner usa [Tesseract.js](https://github.com/naptha/tesseract.js) nel browser per leggere il numero e il nome della carta.

## File
- `index.html`: l'app intera (HTML, CSS e JavaScript).
- `manifest.webmanifest`, `icons/`: installazione sulla schermata Home.
- `sw.js`: funzionamento offline.
