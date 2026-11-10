# Faza 2 — Python za podatke

**Trajanje:** nedelje 7–10 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Pišem Python skripte koje čitaju, čiste i snimaju podatke (fajlovi, API, baza), sa testovima.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| Python osnove (tipovi, funkcije, moduli) | 3 — samostalno | |
| pandas / polars transformacije | 3 — samostalno | |
| Fajlovi: CSV, JSON, Parquet | 3 — samostalno | |
| API pozivi (requests, paginacija, .env) | 2 — osnovno | |
| DuckDB iz Pythona | 2 — osnovno | |
| pytest osnove | 2 — osnovno | |
| Jupyter za istraživanje | 2 — osnovno | |

## Checkpoint lista

- [ ] Napisana funkcija sa type hint-ovima i pytest testom
- [ ] Isti zadatak urađen u pandas-u i u polars-u
- [ ] Skripta povlači podatke sa javnog API-ja (ključ iz `.env`) i snima Parquet
- [ ] Mini ETL: CSV → čišćenje → DuckDB tabela, sa proverom broja redova
- [ ] `ruff check` prolazi bez grešaka

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
