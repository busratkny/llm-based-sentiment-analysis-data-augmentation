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

---

# DOI

This dataset is permanently archived on Zenodo:

https://doi.org/10.5281/zenodo.20342933

---

# Citation

If you use this dataset in your research, please cite the following publication:

B. Tekinay and M. Alp Tocoglu,  
"From Raw to Synthetic: Evaluating LLM-Based Data Augmentation for Sentiment Analysis,"  
IEEE Access, vol. 14, pp. 25747-25769, 2026.  
doi: 10.1109/ACCESS.2026.3664756
---

# Notes

Some datasets are shared in compressed (.zip) format due to GitHub file size limitations.

The synthetic samples were generated solely for academic and research purposes.
