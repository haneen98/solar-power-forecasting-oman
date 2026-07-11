# Long-Term Solar Power Forecasting in Oman

This repository contains the dataset used in the published research:

> **A Cross-Location Evaluation of Temporal Fusion Transformers and LSTM for Long-Term Solar PV Forecasting in Arid Environments**

**Authors**
- Haneen M. Ibrahim
- Hamza Zidoum

Published in **Energy Informatics (2026)**

https://doi.org/10.1186/s42162-026-00672-3

---

## Overview

This repository provides operational photovoltaic (PV) power generation and environmental measurements collected from **10 grid-connected solar PV systems** distributed across multiple governorates of the Sultanate of Oman.

The dataset was used to evaluate deep learning models for **long-term solar power forecasting**, including:

- Long Short-Term Memory (LSTM)
- Temporal Fusion Transformer (TFT)

The published study investigates both **month-ahead** and **year-ahead** forecasting under cross-location evaluation, with particular emphasis on model generalization to unseen solar PV sites.

---

## Dataset

The repository contains processed datasets for each PV site together with a merged dataset used for multi-site model training.

### Files

| File | Description |
|-------|-------------|
| merged_df.xls | Combined dataset from all locations |
| df_Barka.xls | Barka PV system |
| df_Duqm.xls | Duqm PV system |
| df_Ibra.xls | Ibra PV system |
| df_Ibri.xls | Ibri PV system |
| df_Mudhaibi.xls | Mudhaibi PV system |
| df_Murbat.xls | Murbat PV system |
| df_Nizwa.xls | Nizwa PV system |
| df_Yunqul.xls | Yunqul PV system |
| df_Al-Kahil.xls | Al-Kahil PV system |
| df_Al-Kamel.xls | Al-Kamel PV system |

---

## Data Description

Each dataset contains photovoltaic power measurements together with meteorological observations collected from on-site sensors.

Typical variables include:

- Date and Time
- Total Power
- Global Horizontal Irradiance (GHI)
- Plane of Array Irradiance (POA)
- Air Temperature
- Relative Humidity
- Wind Speed
- Wind Direction
- Air Pressure
- Additional derived variables used for forecasting

The datasets were preprocessed for the experiments described in the accompanying publication.

---

## Related Publication

If you use this dataset, please cite the following paper:

> Zidoum, H., Ibrahim, H. *A Cross-Location Evaluation of Temporal Fusion Transformers and LSTM for Long-Term Solar PV Forecasting in Arid Environments.* Energy Informatics (2026).

DOI:

https://doi.org/10.1186/s42162-026-00672-3

---

# Citation Requirement

**If you use this dataset in any publication, thesis, report, software, or derivative work, you must cite the accompanying journal paper.**

Proper citation helps acknowledge the original authors and supports continued sharing of research datasets.

---

## Repository Structure

```
solar-power-forecasting-oman/

│── README.md
│── LICENSE
│── CITATION.cff
│
├── data/
│   ├── merged_df.xls
│   ├── df_Barka.xls
│   ├── df_Duqm.xls
│   ├── df_Ibra.xls
│   ├── df_Ibri.xls
│   ├── df_Mudhaibi.xls
│   ├── df_Murbat.xls
│   ├── df_Nizwa.xls
│   ├── df_Yunqul.xls
│   ├── df_Al-Kahil.xls
│   └── df_Al-Kamel.xls
│
└── paper/
    └── EnergyInformatics_Paper.pdf
```

---

## License

This repository is intended for academic and research use.

Users are welcome to download and reuse the data provided that the accompanying journal paper is properly cited.

Please see the LICENSE file for details.

---

## Contact

**Hamza. zidom**

Department of Computer Science

Sultan Qaboos University

Muscat, Sultanate of Oman

zidoum@squ.edu.om
