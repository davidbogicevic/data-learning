# Faza 4 — Modern data stack

**Trajanje:** nedelje 15–19 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Gradim reproducibilan pipeline: dbt modeli i testovi, orkestracija, Docker i CI.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| dbt (modeli, ref, source, testovi, docs) | 3 — samostalno | |
| Data quality testovi | 3 — samostalno | |
| Orkestracija (npr. Dagster/Airflow/Prefect) | 2 — osnovno | |
| Docker compose za lokalni stack | 2 — osnovno | |
| CI (GitHub Actions) za dbt/pytest | 2 — osnovno | |
| Cloud warehouse osnove (BigQuery/Snowflake/Fabric) | 1 — svestan | |

## Checkpoint lista

- [ ] dbt projekat nad DuckDB-om sa staging i marts slojem
- [ ] Svaki model ima bar jedan test (unique/not_null/relationships)
- [ ] Pipeline se pokreće jednom komandom ili iz orkestratora
- [ ] GitHub Actions pokreće testove na svakom PR-u
- [ ] Dokumentovan način pokretanja u README-u faze

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
