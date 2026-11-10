# Faza 6 — AI sloj

**Trajanje:** nedelje 23–25 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Koristim LLM-ove nad podacima odgovorno: text-to-SQL, RAG nad dokumentacijom, evaluacija.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| LLM API osnove (promptovi, tokeni, troškovi) | 2 — osnovno | |
| Text-to-SQL nad sopstvenim modelom | 2 — osnovno | |
| Embeddings i RAG | 2 — osnovno | |
| Evaluacija i provera odgovora | 2 — osnovno | |
| AI-asistirano pisanje i review koda | 3 — samostalno | |

## Checkpoint lista

- [ ] Skripta koja preko API-ja (ključ iz `.env`) odgovara na pitanje o podacima
- [ ] Text-to-SQL sa proverom: generisani upit se izvršava i rezultat se poredi sa očekivanim
- [ ] Mali RAG nad dokumentacijom modela
- [ ] Set od 10 test pitanja sa ocenom tačnosti

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
