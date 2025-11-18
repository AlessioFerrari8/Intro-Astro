# Installazione 

Controllo npm e node.js

```
node -v
npm -v
```

In alternativa si potrebbe usare yarn o pnpm, per quanto riguarda i pacchetti e moduli necessari.
In alternativa a node.js si potrebbe usare deno o bun.

Installiamo 
```
npm create astro@latest
```

Dopo aver eseguito il comando, risponderemo alle domande che ci verranno poste per configurare il progetto Astro.
E arriviamo a creare il nostro primo progetto Astro.

## Aggiunta frameworks / librerie
Per aggiungere framework o librerie al nostro progetto Astro, possiamo usare i comandi astro add

## Per guardare la preview
Solito
```
npm run dev
```

## Per buildare il progetto
```
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