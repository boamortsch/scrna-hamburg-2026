# scRNA-seq — Hamburg Summer School 2026

Lern- und Arbeitsrepo zur Vorbereitung auf die Hamburg Bioinformatics Summer School (BNITM, 24.–28.08.2026) und als Basis für spätere eigene Analysen (u. a. TellMeGen-Selbstanalyse).

## Ziel
Sichere Grundlagen im scRNA-seq-Workflow (Python/Scanpy) vor Hamburg: QC → Normalization → Feature Selection → Dimensionsreduktion → Clustering → Annotation. Parallel R/Bioconductor-Perspektive (Cambridge-Kurs).

## Umgebung einrichten
```bash
conda env create -f environment.yml
conda activate scrna
jupyter lab
```

## Struktur
```
notebooks/    Jupyter-Notebooks (ein Notebook pro Kapitel/Thema)
notes/        Textnotizen, Zusammenfassungen, offene Fragen
data/         lokale Datensätze (NICHT versioniert, siehe .gitignore)
```

## Fortschritt (Heumos et al., sc-best-practices.org)
- [ ] Kap. 1 — Raw data & pre-processing
- [ ] Kap. 2 — Quality Control (Doublets, Ambient RNA, MT)
- [ ] Kap. 3 — Normalization
- [ ] Kap. 4 — Feature Selection + PCA/UMAP
- [ ] Kap. 5 — Clustering
- [ ] Kap. 6 — Cell-type Annotation
- [ ] Eigene End-to-End-Analyse (PBMC 3k)

## Lern-Log
| Datum | Thema | Key-Learning | Offene Frage |
|-------|-------|--------------|--------------|
| 17.07.2026 | Setup | Repo + conda-Umgebung aufgesetzt | — |
