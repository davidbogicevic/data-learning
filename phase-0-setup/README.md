# Faza 0 — Setup i radno okruženje

**Trajanje:** nedelja 1 (predlog — uskladi sa PDF planom u `docs/`)

## Cilj faze

Sređeno radno okruženje i navika da učiš kroz repo: terminal, Git/GitHub, VS Code, uv, Docker i Claude kao tutor.

## Ciljni nivo po temi

Skala: 1 — svestan · 2 — osnovno (uz pomoć) · 3 — samostalno · 4 — napredno (mogu da učim druge)

| Tema | Ciljni nivo | Moj nivo |
|------|-------------|----------|
| Terminal (zsh) osnove | 2 — osnovno | |
| Git + GitHub (commit, push, branch, PR) | 2 — osnovno | |
| VS Code + ekstenzije | 2 — osnovno | |
| uv i Python okruženja | 2 — osnovno | |
| Docker (pokreni container, port, volume) | 1 — svestan | |
| Rad sa Claude Code-om kao tutorom | 2 — osnovno | |

## Checkpoint lista

- [ ] Repo kloniran/otvoren u VS Code-u, preporučene ekstenzije instalirane
- [ ] `uv sync` prolazi i `uv run python -c "import duckdb"` radi
- [ ] Napravio sam branch, commit i PR na sopstvenom repo-u
- [ ] Pokrenuo sam Postgres u Dockeru i povezao se iz SQLTools-a
- [ ] Napisan prvi unos u `learning-log/`

## Struktura

- `exercises/` — vežbe (režim tutora: Claude ne piše rešenja)
- `notes/` — moje beleške
- `datasets/` — lokalni podaci (nisu u Git-u)
