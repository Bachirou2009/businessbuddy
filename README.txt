BUSINESSBUDDY — PROTOTIPO DEMO PER GESTIONE APPUNTAMENTI

Descrizione
- Applicazione web single-page pronta per mostrare e gestire appuntamenti, clienti e servizi.
- Ideale per barbiere, studio estetico, consulenti e piccoli negozi con agenda locale.
- I dati restano nel browser del dispositivo e non richiedono backend.

Struttura
- index.html: interfaccia e logica dell'applicazione
- manifest.webmanifest: installazione come app web progressiva
- sw.js: cache offline e supporto PWA
- icon.svg: icona del progetto
- render.yaml: configurazione per Render static site

Main features
- agenda giornaliera e calendario mensile
- aggiunta, modifica e cancellazione appuntamenti
- gestione servizi e prezzi
- rubrica clienti e report statistici
- esportazione CSV/JSON
- supporto offline attraverso service worker

Pubblicazione
1. Carica i file in un repository GitHub.
2. Connetti il repo a Render o GitHub Pages.
3. Imposta Publish Directory a . (punto) se usi Render static site.
4. Verifica che index.html sia salvato nella root del progetto.

Note
- Questa è una demo locale e non sostituisce un sistema con autenticazione, database, pagamenti o sincronizzazione tra dispositivi.
- Per una versione reale, è consigliabile aggiungere backend, autenticazione, database persistente e sicurezza.
