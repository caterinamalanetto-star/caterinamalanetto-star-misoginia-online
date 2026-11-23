# Misoginia online e violenza sulle ragazze – dataviz Radar QN

Pagine pubblicate su GitHub Pages. Ogni grafico legge i propri CSV in `data/`: per aggiornarlo basta cambiare il CSV.

- **Instagram, dal calcio alla misoginia in 122 video**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/percorso/
- **Violenza sulle donne per età, 2014 e 2025**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/violenza-eta/

## Dati e fonti

- `data/audit-percorso.csv`, `data/audit-sessioni.csv`, `data/feed-tossico.csv`: ActionAid, «Suggerito per te. Manosfera, femosfera e prevenzione primaria della violenza di genere in Italia» (novembre 2026), audit algoritmico su Instagram, 10-24 settembre 2026: tabelle 1, 7 e 8, figure 10, 12 e 17 e testo del paragrafo 1.3. Le quote sono quelle dichiarate nel rapporto (82% e 30% nella sessione «dating», 94% e 46% nella sessione 7, 90% e 57% nella sessione finale di 30 video, profilo maschile; 16%, 26% e 40% per il femminile). Nel grafico «Altri contenuti tossici» è la differenza tra la quota tossica totale e quella di misoginia e antifemminismo.
- `data/violenza-eta-2014-2025.csv`: Istat, «La violenza contro le donne dentro e fuori la famiglia. Primi risultati 2025» (21 novembre 2025), prospetto 5. Donne italiane di 16-70 anni, violenze subite nei cinque anni precedenti l'intervista.

## Snippet per il CMS

Vedi `index.html`: per ogni dataviz c'è l'iframe con lo script inline. Se ci sono più dataviz nello stesso articolo, lo script può restare in ognuna (il controllo `__radarQNv2` evita doppioni).
