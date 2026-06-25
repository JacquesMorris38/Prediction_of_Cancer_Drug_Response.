Cancer Drug-Response Prediction Using Leakage-Safe Multimodal Machine Learning

Overview

This repository accompanies the research paper:

Predictionn of Cancer Treatment Response Using Machine Learning 

The project presents a reproducible machine-learning framework for predicting cancer drug response by integrating gene-expression profiles with molecular drug descriptors. The framework emphasizes leakage-safe experimental design, multimodal feature integration, explainable artificial intelligence (SHAP), biomarker discovery, external validation, dimensionality reduction, and drug sensitivity classification.

⸻

Key Features

* Leakage-safe machine learning workflow
* Drug-agnostic prediction framework
* Multimodal integration of gene-expression and drug molecular descriptors
* Random Forest and XGBoost modelling
* SHAP-based explainability
* Consensus biomarker discovery
* Pathway enrichment analysis
* Leave-One-Drug-Out (LODO) validation
* Dimensionality reduction experiments
* Calibrated drug sensitivity classification
* External validation using an independent pharmacogenomic dataset

⸻

Research Questions

The repository reproduces all experiments presented in the manuscript.

RQ1

Can a leakage-safe drug-agnostic machine learning framework accurately predict cancer drug response across multiple therapeutic compounds?

RQ2

Does multimodal integration of genomic and drug-specific molecular descriptors improve predictive performance compared with unimodal feature representations?

RQ3

Which molecular biomarkers consistently influence cancer drug-response predictions across diverse therapeutic compounds?

RQ4

How effectively can the proposed framework generalize to previously unseen drugs under Leave-One-Drug-Out (LODO) validation?

RQ5

What impact do dimensionality-reduction and feature-selection techniques have on predictive accuracy, computational efficiency, and model interpretability?

RQ6

Can cancer cell-line sensitivity and resistance be reliably classified using a calibrated machine-learning framework?

RQ7

To what extent are predictive biomarkers shared across drugs versus drug-specific, and what does this reveal about common and compound-specific mechanisms of drug response?

⸻

Repository Structure

.
├── notebook/
│   └── cibm-final-notebook.ipynb
│
├── figures/
│
├── tables/
│
├── datasets/
│
├── docs/
│
├── manuscript/
│
├── requirements.txt
├── environment.yml
├── LICENSE
├── CITATION.cff
└── README.md

⸻

Workflow

1. Download pharmacogenomic datasets
2. Perform preprocessing and quality control
3. Generate genomic and drug molecular features
4. Train leakage-safe machine-learning models
5. Evaluate predictive performance
6. Perform SHAP explainability analysis
7. Identify consensus biomarkers
8. Conduct pathway enrichment analysis
9. Evaluate generalization using LODO validation
10. Evaluate dimensionality reduction strategies
11. Perform calibrated drug sensitivity classification
12. Validate using an independent dataset

⸻

Datasets

The datasets are publicly available.

Training Dataset

Genomics of Drug Sensitivity in Cancer (GDSC)

https://www.cancerrxgene.org/

External Validation Dataset

Genentech Cell Line Screening Initiative (gCSI)

Accessed through PharmacoDB

https://pharmacodb.ca/

The datasets are not redistributed in this repository. Users should download them directly from the original providers and place them in the datasets/ directory.

⸻

Installation

Clone the repository

git clone https://github.com/<username>/<repository>.git

Create the environment

conda env create -f environment.yml
conda activate cancer-drug-response

or

pip install -r requirements.txt

⸻

Running the Experiments

Open

notebook/cibm-final-notebook.ipynb

Execute the notebook sequentially to reproduce all analyses presented in the manuscript.

⸻

Results

The repository reproduces the principal findings reported in the manuscript, including:

* Drug-agnostic multimodal prediction
* Multimodal feature integration
* SHAP-based biomarker discovery
* Consensus biomarker identification
* Pathway enrichment analysis
* Leave-One-Drug-Out validation
* Dimensionality reduction experiments
* Drug sensitivity classification
* External validation

⸻

Citation

If you use this repository in your research, please cite the accompanying journal article.

Citation details will be updated upon publication.

⸻

License

This repository is released under the MIT License.

⸻

Contact

Jacques Morris Nuekpe
jnuekpe@gmail.com

For questions regarding this repository, please open an issue on GitHub.
