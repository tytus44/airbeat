AIRBEAT è una moderna applicazione web Single-Page (SPA) per la riproduzione di stazioni radio internet. Costruita con un'interfaccia "Cyber-Violet" accattivante, offre accesso a migliaia di stazioni globali grazie all'integrazione con le API di Radio Browser, il tutto senza necessità di un backend dedicato.

✨ Caratteristiche Principali
🔍 Ricerca Globale: Integrazione diretta con Radio-Browser API per accedere a oltre 30.000 stazioni.

🎨 UI Cyber-Violet: Design moderno, scuro e responsivo, ottimizzato per Desktop e Mobile.

🧘 Zen Mode: Modalità a schermo intero senza distrazioni per godersi la musica.

🖼️ Smart Covers: Generazione automatica di copertine vettoriali basate sul nome della stazione (hash-based colors) se l'immagine originale manca.

❤️ Libreria Personale:

Salvataggio dei preferiti.

Ordinamento per Nome, Paese o Preferiti.

Aggiunta manuale di stream URL personalizzati.

Modifica dei dettagli (Nome, URL, Cover) delle stazioni salvate.

💾 Persistenza Dati:

Salvataggio automatico nel localStorage del browser.

Sistema di Backup (Esportazione/Importazione file .json) per non perdere mai le tue frequenze.

📱 Mobile Friendly: Player "a pillola" flottante e navigazione ottimizzata per il touch.

🚀 Installazione e Utilizzo
AIRBEAT è un'applicazione Client-Side al 100%. Non richiede Node.js, PHP o database.

Metodo 1: Esecuzione Locale
Scarica il file index.html.

Apri il file direttamente con il tuo browser preferito (Chrome, Firefox, Edge, Safari).

Fatto! L'app è pronta all'uso.

Metodo 2: Hosting (Opzionale)
Puoi caricare il file index.html su qualsiasi servizio di hosting statico gratuito come:

GitHub Pages

Netlify

Vercel

Altervista

🛠️ Tecnologie Utilizzate
Il progetto è realizzato in Vanilla JS (puro), mantenendo il codice leggero e performante in un singolo file.

HTML5: Struttura semantica e Audio API.

CSS3: Variabili CSS (Custom Properties), Flexbox, Grid, Animazioni.

JavaScript (ES6+): fetch API, localStorage, gestione DOM asincrona.

Icone: Lucide Icons (via CDN).

📂 Struttura del Codice
L'intero progetto risiede in un singolo file per la massima portabilità:

Plaintext

index.html
├── <head>
│   ├── Meta tags & Fonts (Montserrat)
│   ├── Lucide Icons Script
│   └── <style> (Tutto il CSS e il tema Cyber)
├── <body>
│   ├── Audio Element Globale
│   ├── Componenti UI (Top Bar, Player Pill, Zen Mode)
│   ├── Viste (Galleria, Gestione, Dettagli)
│   └── <script> (Logica applicativa, API, Player)
🔌 API Reference
Questo progetto utilizza le API pubbliche di Radio Browser:

Endpoint: https://de1.api.radio-browser.info/json/stations/search

Documentazione: api.radio-browser.info

🎨 Personalizzazione
Vuoi cambiare i colori? Cerca la sezione :root all'inizio del blocco <style> nel file index.html:

CSS

:root {
    --bg-deep: #130b1b;       /* Sfondo principale */
    --accent: #d946ef;        /* Colore primario (Fucsia) */
    --accent-sec: #06b6d4;    /* Colore secondario (Ciano) */
    /* ... */
}
📝 Changelog
v1.2: Aggiunta modifica cover, Zen Mode statico, pulsante Zen neutro.

v1.1: Rimozione registrazione, introduzione Dynamic Covers (SVG).

v1.0: Rilascio iniziale, fork da Pod.Caster.

Programmato con ❤️ da NeRO
