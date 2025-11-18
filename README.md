# Installazione 

Controllo npm e node.js

```bash
node -v
npm -v
```

In alternativa si potrebbe usare yarn o pnpm, per quanto riguarda i pacchetti e moduli necessari.
In alternativa a node.js si potrebbe usare deno o bun.

Installiamo 
```bash
npm create astro@latest
```

Dopo aver eseguito il comando, risponderemo alle domande che ci verranno poste per configurare il progetto Astro.
E arriviamo a creare il nostro primo progetto Astro.

## Aggiunta frameworks / librerie
Per aggiungere framework o librerie al nostro progetto Astro, possiamo usare i comandi astro add

## Per guardare la preview
Solito
```bash
npm run dev
```

## Per buildare il progetto
```bash
npx astro build
npm run build
```

## Tipologia di siti
Siti statici


# Build
Quando facciamo il build del progetto, Astro genera una cartella `dist/` che contiene tutti i file statici pronti per essere distribuiti su un server web o un servizio di hosting statico.
Tutti i file contenuti in /public vengono copiati direttamente nella cartella `dist/` durante il processo di build. 

```bash
cd dist
npx five-server
```

# Lezione 18/11/2025
Differenza tra ```npm run dev``` e ```npm run build``` 
- npm run dev: avvia un server di sviluppo locale che consente di visualizzare e testare il sito in tempo reale durante lo sviluppo. Le modifiche apportate al codice sorgente vengono riflesse immediatamente nel browser senza dover eseguire nuovamente il build.
- npm run build: genera una versione ottimizzata e pronta per la produzione del sito. Questo comando esegue il processo di build, compila il codice sorgente e crea i file statici nella cartella `dist/`.

## tailwind

Per aggiungere Tailwind CSS al nostro progetto Astro, possiamo seguire questi passaggi:

1. Installiamo Tailwind CSS e le sue dipendenze:
```bash
npx astro add tailwind
```
