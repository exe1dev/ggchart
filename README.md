<!-- GG Chart modification (2026): documentation rewritten for the GG Chart fork. -->
# GG Chart

**Grafici gratuiti. Il tuo trading, le tue regole.**

GG Chart e un fork open source di [KLineChart Pro](https://github.com/klinecharts/pro), basato sul motore [KLineChart](https://github.com/klinecharts/KLineChart). Il progetto e parte dell'ecosistema GG Tracker, ma il grafico e pensato come strumento autonomo e gratuito.

## Stato del progetto

Rebranding iniziale in corso. Questo repository **non e ancora un'applicazione web pubblicata**: contiene la libreria originale con branding GG Chart e richiede ancora un frontend di distribuzione e una sorgente dati configurata.

## Avvio e sviluppo

Requisiti: Node.js e npm.

```bash
npm install
npm run build
npm run docs:dev
```

Il codice mantiene per ora l'API pubblica e i nomi di bundle originali di KLineChart Pro per evitare rotture durante il primo rebranding. Non si tratta di una pubblicazione su npm con il nome GG Chart.

## Dati di mercato

La classe `DefaultDatafeed` utilizza Polygon.io e richiede una chiave API valida e autorizzazioni coerenti con i dati utilizzati. **La licenza open source del codice non include dati di mercato in realtime o diritti di redistribuzione.** Sono possibili datafeed alternativi conformi all'interfaccia `Datafeed`.

## Roadmap minima

- Completare la personalizzazione visuale GG Chart.
- Allestire un'app web standalone che utilizzi la libreria.
- Collegare un provider di dati con condizioni adeguate alla pubblicazione.
- Testare build, grafici, indicatori, ricerca simboli e strumenti di disegno prima del rilascio.

## Licenze e attribuzioni

Il codice derivato e soggetto alla [Apache License 2.0](LICENSE). Conserviamo i copyright e gli avvisi nei file sorgente, piu le attribuzioni in [NOTICE](NOTICE).

- Progetto originale: [KLineChart Pro](https://github.com/klinecharts/pro) (liihuu).
- Motore: [KLineChart](https://github.com/klinecharts/KLineChart).
- Gli avvisi originali di KLineChart includono riferimenti a TradingView Lightweight Charts; questo fork **non** e affiliato a TradingView.

GG Tracker e GG Chart sono marchi del progetto GG Tracker; le attribuzioni ai progetti originali non implicano affiliazione o approvazione.
