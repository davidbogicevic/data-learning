# data-learning

Moj repo za učenje **Data Analyst / Analytics Engineer / Data Engineer** veština uz AI.
Učim gradeći: svaka faza ima vežbe, beleške i isporuku koja ostaje u repo-u.

📈 **Napredak:** [PROGRESS.md](PROGRESS.md)

## Plan — 28 nedelja, 8 faza

| Faza | Tema | Nedelje |
|-----:|------|---------|
| 0 | [Setup i radno okruženje](phase-0-setup/README.md) | 1 |
| 1 | [SQL](phase-1-sql/README.md) | 2–6 |
| 2 | [Python za podatke](phase-2-python/README.md) | 7–10 |
| 3 | [Modelovanje podataka](phase-3-modeling/README.md) | 11–14 |
| 4 | [Modern data stack](phase-4-modern-stack/README.md) | 15–19 |
| 5 | [BI i Microsoft Fabric](phase-5-bi-fabric/README.md) | 20–22 |
| 6 | [AI sloj](phase-6-ai-layer/README.md) | 23–25 |
| 7 | [Portfolio](phase-7-portfolio/README.md) | 26–28 |

Detaljan plan (PDF) je u [`docs/`](docs/).

## Kako se koristi

1. Na početku nedelje: otvori `PROGRESS.md`, označi nedelju 🟨 i napravi `learning-log/YYYY-Www.md` iz [šablona](learning-log/_template.md).
2. Radi vežbe u `phase-N-*/exercises/`. Claude je tu **tutor**: daje hintove i ocenjuje, ne piše rešenja (vidi [CLAUDE.md](CLAUDE.md)).
3. Pojmove i pitanja za kasnije zapiši u [parking-lot.md](parking-lot.md).
4. Na kraju nedelje: popuni learning-log, upiši sate i status u `PROGRESS.md`, commit.

## Okruženje

```bash
uv sync                      # instalira zavisnosti (Python 3.12)
cp .env.example .env         # pa upiši svoje vrednosti; .env nikad ne ide u Git
uv run jupyter lab           # notebook-ovi
uv run pytest                # testovi
uv run ruff check .          # lint
```

Alati: Git, GitHub CLI, uv, VS Code, Docker, DuckDB.
