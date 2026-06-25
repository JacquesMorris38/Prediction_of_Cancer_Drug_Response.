Dataset Information

This repository accompanies the manuscript:

A Leakage-Safe Multimodal Machine Learning Framework for Cancer Drug-Response Prediction Using Pharmacogenomic Data

Overview

The study uses publicly available pharmacogenomic datasets. Due to licensing restrictions, the datasets are not redistributed in this repository.

Users should download the datasets from the original providers and place them in the appropriate directory before running the notebook.

⸻

1. Genomics of Drug Sensitivity in Cancer (GDSC)

Purpose

* Primary training dataset
* Gene-expression profiles
* Drug response (LN_IC50)
* Drug annotations

Official website

https://www.cancerrxgene.org/

Recommended citations

* Garnett et al., Nature (2012)
* Yang et al., Nucleic Acids Research (2013)

⸻

2. Genentech Cell Line Screening Initiative (gCSI)

Purpose

* Independent external validation

Accessed through

https://pharmacodb.ca/

Recommended citations

* Haverty et al., Nature (2016)
* Smirnov et al., Nucleic Acids Research (2018)

⸻

Expected directory structure

datasets/

GDSC/
    expression.csv
    drug_response.csv
    drug_features.csv
gCSI/
    expression.csv
    drug_response.csv

⸻

Notes

Users are responsible for complying with the licensing terms of the original datasets.

No raw pharmacogenomic data are redistributed in this repository.
