# Approximation linearer Modelle durch neuronale Netze

Begleit-Repo zu meiner Bachelor-Seminararbeit am KIT (IOR, Analytics and Statistics, SS 2026, Betreuer: Leonard Vetter).

Hier liegen das Notebook mit allen acht Experimenten aus Kapitel 4 und die daraus erzeugten Abbildungen. Alles ist auf synthetischen Daten, dementsprechend läuft es auch ohne Datensätze.

## Was ist wo

- `notebook.ipynb` – Datengenerator, Trainings-Wrapper und alle Experimente E1–E8. Reihenfolge im Notebook entspricht Kapitel 4 der Arbeit.
- `seminararbeit/figures/` – die im Notebook erzeugten Plots als PDF.

## Reproduzieren

Kurz:
```bash
jupyter nbconvert --to notebook --execute --inplace notebook.ipynb
```

Ausführlich: Python 3.12, `numpy 1.26`, `torch 2.11`, `scikit-learn 1.5`, `matplotlib 3.10`. Der Standard-Seed ist 42, alle wiederholten Läufe nutzen `SEED + r`.

## Lizenz

MIT (siehe `LICENSE`). Nutzung/Weitergabe des Codes gerne, Zitierhinweis auf die Seminararbeit ist nett aber nicht Pflicht.

— Samuel
