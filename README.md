# Khowar–English Low-Resource Machine Translation

This repository contains the research code and resources for **Khowar–English Neural Machine Translation (NMT)**, focusing on the challenges of machine translation for the low-resource Khowar language.

The research investigates the use of multilingual pretrained neural machine translation models for translating between **Khowar and English**, with particular emphasis on data preprocessing, model training, tokenization, and translation evaluation.

## Research Information

**Researcher:** Tariq Ullah <br>
**Supervisor:** Prof. Dr. Maryam Mahsal Khan <br>
**Research Collaboration:** Center of Digital Governance and Agentic Innovation (CDGAI), CECOS University, Peshawar, Pakistan

## Research Objectives

The main objectives of this research are to:

* Develop and prepare a Khowar–English parallel dataset.
* Perform data cleaning and preprocessing for Khowar text.
* Investigate neural machine translation approaches for Khowar.
* Evaluate multilingual pretrained translation models.
* Analyze tokenization and subword representation for Khowar.
* Evaluate translation quality using standard machine translation metrics.
* Contribute toward the development of language technology resources for Khowar.

## Models

The research includes experiments with multilingual pretrained models, including:

* **NLLB-200**
* **mBART-50**

Additional models or experiments may be added as the research progresses.

## Dataset

The research uses a Khowar–English parallel dataset collected and processed for machine translation experiments.

The data-processing workflow includes:

* Data collection
* Data cleaning
* Text normalization
* Sentence preparation
* Dataset validation
* Train/validation/test splitting
* Tokenization analysis

The experimental dataset is divided into:

* **Training:** 70%
* **Validation:** 15%
* **Testing:** 15%

> **Note:** Dataset availability and redistribution are subject to the permissions, sources, and applicable policies associated with the collected data. Please do not redistribute restricted data without appropriate permission.

## Evaluation Metrics

The translation models are evaluated using multiple machine translation and semantic evaluation metrics, including:

* BLEU
* SacreBLEU
* chrF
* chrF++
* TER
* METEOR
* BERTScore
* COMET

Training and evaluation loss are also monitored during the experiments.

## Repository Structure

```text
khowar-english-low-resource-mt/
│
├── Khowar_English_Dataset.csv
├── 01_mBART_Style_IEEE_Review_Khowar_NMT.ipynb
├── 02_mBART-50_Khowar_English_Translation.ipynb
├── 03_NLLB-200_Khowar_English_Translation.ipynb
├── requirements.txt
└── README.md

```

> The notebook names above are examples. Rename them according to the actual purpose of your three notebooks.

## Environment

The experiments are implemented in **Python** using commonly used machine learning and natural language processing libraries.

The required Python packages are listed in:

```text
requirements.txt
```

To install the dependencies:

```bash
pip install -r requirements.txt
```

## Research Status

This repository represents ongoing research in **low-resource Khowar–English machine translation**.

The code, experiments, preprocessing procedures, and results may be updated as the research progresses.

## Publication

A research paper based on this research has been **submitted for peer review** to the **FIT 2026 Conference at COMSATS University Islamabad**.

The paper is currently under peer review. Publication or acceptance details will be added to this repository when they become publicly available.

## Supervision and Collaboration

This research was conducted under the supervision of:

**Prof. Dr. Maryam Mahsal Khan**

The research was carried out in collaboration with:

**Center of Digital Governance and Agentic AI (CDGAI)**
**CECOS University, Peshawar, Pakistan**

## Acknowledgments

The researcher gratefully acknowledges the guidance and supervision of **Prof. Dr. Maryam Mahsal Khan** throughout this research.

The researcher also acknowledges the support and research environment provided through the **Center of Digital Governance and Agentic AI (CDGAI), CECOS University, Peshawar, Pakistan**.

## Citation

If you use the publicly available code or resources from this repository in academic or research work, please cite the associated publication when it becomes publicly available.

## Contact

**Tariq Ullah**
Researcher – Khowar–English Machine Translation <br>
CDGAI, CECOS University, Peshawar, Pakistan <br>
**Email:** [tariqullahcs@gamil.com](mailto:tariqullahcs@gamil.com)

