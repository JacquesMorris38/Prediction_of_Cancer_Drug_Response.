Reproducibility Guide

This document explains how to reproduce every experiment reported in the accompanying manuscript.

⸻

Step 1

Clone the repository.

git clone https://github.com/<username>/<repository>.git

⸻

Step 2

Install dependencies.

conda env create -f environment.yml

or

pip install -r requirements.txt

⸻

Step 3

Download the datasets described in DATASET.md.

⸻

Step 4

Place the datasets inside

datasets/

⸻

Step 5

Open

notebook/cibm-final-notebook.ipynb

⸻

Step 6

Run every notebook cell sequentially.

The notebook automatically performs

* preprocessing
* feature engineering
* model training
* evaluation
* SHAP analysis
* pathway enrichment
* dimensionality reduction
* external validation
* classification

⸻

Experiment Mapping

RQ1

Drug-agnostic prediction

Outputs

* Summary table
* Observed vs predicted figure

⸻

RQ2

Multimodal feature integration

Outputs

* Ablation figure
* Performance summary

⸻

RQ3

Biomarker discovery

Outputs

* SHAP values
* Consensus biomarker landscape
* Pathway enrichment

⸻

RQ4

LODO validation

Outputs

* Unseen drug performance
* Publication summary

⸻

RQ5

Dimensionality reduction

Outputs

* PCA comparison
* Runtime analysis

⸻

RQ6

Drug sensitivity classification

Outputs

* ROC
* PR
* Calibration
* Classification summary

⸻

RQ7

Biomarker transferability

Outputs

* Shared biomarkers
* Drug-specific biomarkers
* Transferability summary

⸻

Expected execution time

Approximately 2–6 hours depending on hardware.
