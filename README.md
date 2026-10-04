# Gnarly Gorilla Sportsbooks

Settled-bet ledger for the daily Gnarly Gorilla pick cards. Chrome and the Chromebook. No sportsbook login.

Colors match the pick-card PDFs: page #0A0A0A, titles #39FF14, body #D6FFD0, warnings #F0E14A.

## How it fits the daily cards

1. The pick card is the analysis. This page does not write picks.
2. After the card is saved, paste the logged plays here. They land as pending $10 BetMGM slips.
3. Next day, grade those slips Win / Loss / Push before the new card.
4. Copy the report-card block into that day's grade-yesterday section.

Paste one play per line:

```
NFL | Spread | Chiefs -3.5 | -110 | High 62%
NBA | Total | Over 224.5 | -105 | Medium 55%
```

Date is today unless the line starts with YYYY-MM-DD.

## Run it

1. Settings → Pages → Branch `main` / root → Save.
2. Open https://cwaggoner.github.io/gnarly-gorilla-sportsbooks/
3. Bookmark it on the Chromebook.

Data stays in this browser. Export CSV before clearing site data.
