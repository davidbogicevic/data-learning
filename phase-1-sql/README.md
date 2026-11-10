# Faza 1 — SQL

**Trajanje:** nedelje 2–6 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Samostalno pišem čitljiv i tačan analitički SQL (DuckDB + PostgreSQL) i razumem grain, NULL i fan-out.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| SELECT, WHERE, ORDER BY, LIMIT | 3 — samostalno | |
| JOIN-ovi (INNER/LEFT/FULL, anti/semi join) | 3 — samostalno | |
| GROUP BY, agregacije, HAVING | 3 — samostalno | |
| CTE i podupiti | 3 — samostalno | |
| Window funkcije (ROW_NUMBER, LAG, running total) | 3 — samostalno | |
| NULL, duplikati, grain, fan-out | 3 — samostalno | |
| Indeksi i EXPLAIN osnove | 1 — svestan | |

## Checkpoint lista

- [ ] Rešio 10+ vežbi iz osnovnog SELECT/WHERE bez hinta
- [ ] Objasnim razliku INNER vs LEFT JOIN na svom primeru i pronađem fan-out
- [ ] Napišem upit sa CTE-ovima koji drugi može da pročita
- [ ] Rešim top-N po grupi i running total window funkcijama
- [ ] Mini-projekat: analiza javnog dataseta u DuckDB-u sa 5 pitanja i odgovora

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
