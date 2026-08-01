# CourtWatch — monitor pubblico

Monitor automatico delle pagine pubbliche FITP, Tennis Europe, ITF e TennisTalker.

- `players.json` contiene le identità da monitorare.
- `monitor.mjs` usa un browser headless soltanto sulle pagine pubbliche.
- `data.json` contiene i riscontri con fonte e testo.
- `index.html` visualizza esclusivamente i dati del monitor.
- GitHub Actions esegue il controllo due volte ogni ora.

Il sistema non effettua login, non usa password e non aggira protezioni. Un riscontro viene classificato come iscrizione o ordine di gioco soltanto quando il testo pubblico contiene indicatori coerenti.
