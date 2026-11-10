# Faza 3 — Modelovanje podataka

**Trajanje:** nedelje 11–14 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Dizajniram analitički model (star schema) sa jasnim grain-om, fact i dim tabelama.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| Normalizacija vs denormalizacija | 2 — osnovno | |
| Dimenzionalno modelovanje (Kimball) | 3 — samostalno | |
| Fact i dimension tabele, grain | 3 — samostalno | |
| SCD tip 1 i 2 | 2 — osnovno | |
| Surrogate ključevi | 2 — osnovno | |
| Slojevi: staging → intermediate → marts | 2 — osnovno | |

## Checkpoint lista

- [ ] Za zadati biznis proces definisan grain jednom rečenicom
- [ ] Nacrtan star schema (dijagram u `notes/`)
- [ ] Implementiran SCD tip 2 u SQL-u nad DuckDB-om
- [ ] Model provereni upitima: nema duplikata po grain-u
- [ ] Mini-projekat: model za izabrani domen + dokumentacija

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
