# Large Language Model–Based Data Augmentation for Sentiment Analysis

This repository contains the datasets used in the master's thesis:

## Thesis Title

**Large Language Model–Based Data Augmentation for Sentiment Analysis: A Comparative Analysis of Raw and Synthetic Data Configurations in Terms of Performance and Consistency**

Turkish Title:

**Büyük Dil Modelleri Tabanlı Veri Artırımı ile Duygu Analizi: Ham ve Sentetik Veri Konfigürasyonlarının Performans ve Tutarlılık Açısından Karşılaştırmalı Analizi**

---

# Institution

İzmir Katip Çelebi University  
Department of Software Engineering

---

# Dataset Configurations

This repository includes the following dataset scenarios:

- Raw
- Raw + GPT
- Raw + Claude
- Raw + GPT + Claude
- GPT-only
- Claude-only

---

# Dataset Format

All datasets use the following CSV structure:

| Column | Description |
|---|---|
| category | Review category |
| review | Review text |
| sentiment | Sentiment label |

---

# Label Definitions

| Label | Meaning |
|---|---|
| 0 | Negative |
| 1 | Positive |

---

# Synthetic Data Generation

Synthetic reviews were generated using:
- GPT
- Claude

Generation method:
- Zero-shot prompting

---

# Original Dataset Source

The original raw data was derived from the HUMIR dataset.

---

# License

This repository is intended for academic and research purposes.

# Notes

Some datasets are shared in compressed (.zip) format due to GitHub file size limitations.

The synthetic samples were generated solely for academic and research purposes.
