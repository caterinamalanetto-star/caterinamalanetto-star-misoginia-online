# Misoginia online e violenza sulle ragazze – dataviz Radar QN

Pagine pubblicate su GitHub Pages. Ogni grafico legge i propri dati in `data/`: per aggiornarlo basta cambiare il CSV.

- **Instagram, dal calcio alla misoginia in 122 video**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/percorso/
- **Stessa parola, due feed diversi**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/feed-dating/
- **Violenza sulle donne per età, 2014 e 2025**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/violenza-eta/
- **Violenza sessuale per area geografica, 2014 e 2025**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/mappa-aree/
- **Prova a indovinare**: https://caterinamalanetto-star.github.io/caterinamalanetto-star-misoginia-online/indovina/

## Dati e fonti

- `data/audit-percorso.csv`, `data/audit-sessioni.csv`, `data/feed-tossico.csv`: ActionAid, «Suggerito per te. Manosfera, femosfera e prevenzione primaria della violenza di genere in Italia» (novembre 2026), audit algoritmico su Instagram, 10-24 settembre 2026: tabelle 1, 7 e 8, figure 10, 12 e 17 e paragrafo 1.3. Nel grafico «Altri contenuti tossici» è la differenza tra la quota tossica totale e quella di misoginia e antifemminismo.
- `data/feed-composizione.csv`: ActionAid, figura 17 (sessione 6, ricerca «dating», 50 video per profilo) e tabella 8 (sessione finale, 30 video). Profilo maschile, sessione 6: i 9 video non tossici sono riuniti in «Altri contenuti» perché nella figura la distinzione tra domestici e altri non è leggibile con certezza. Sessione finale, profilo maschile: «Altri contenuti tossici» = 27 tossici − 19 apertamente ostili.
- `data/violenza-eta-2014-2025.csv`, `data/violenza-ripartizioni.csv`: Istat, «La violenza contro le donne dentro e fuori la famiglia. Primi risultati 2025» (21 novembre 2025), prospetto 5. Donne italiane di 16-70 anni, violenze subite nei cinque anni precedenti l'intervista.
- `data/indovina.csv`: Istat (prospetto 5 dell'indagine 2025; «Stereotipi sui ruoli di genere: il punto di vista di ragazze e ragazzi», 25 luglio 2025, dati 2023) e ActionAid (tabella 7).
- `data/regioni-italia.geojson`: confini regionali Openpolis (geojson-italy), semplificati; ogni regione ha la sua ripartizione Istat.

## Snippet per il CMS

Vedi `index.html`: per ogni dataviz c'è l'iframe con lo script inline. Se ci sono più dataviz nello stesso articolo, lo script può restare in ognuna (il controllo `__radarQNv2` evita doppioni).
