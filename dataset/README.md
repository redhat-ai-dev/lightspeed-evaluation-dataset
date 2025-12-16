# Q&A Dataset

This directory contains the raw and processed Q&A dataset used for analysis and evaluation. 


## 📝 Detailed Descriptions

### 1. Source Data
* **`dataset_raw.yaml`**
    * **Purpose:** Original raw Q&A pairs
    * **Usage:** Use this file if you need to re-run classification logic.

### 2. Processed & Classified Data
These files contain Q&A pairs that have been grouped and processed based on [categories_rhdh.yaml](../categories_rhdh.yaml):

* **`dataset-ClassificationStrategy.yaml`**
    * Grouped questions based on the categories defined in [categories_rhdh.yaml](../categories_rhdh.yaml).

* **`dataset-ClassificationStrategy.csv`**
    * Grouped questions in csv format. Best for quick manual review in spreadsheet software (Excel/Sheets) or simple data loading.

* **`dataset-ClassificationStrategy.parquet`**
    * Grouped questions in parquet format. 

* **`dataset-ClassificationStrategy.evaluation_dataset_yaml`**
    * This file format adheres to the strict schema required by the [lighspeed-evaluation](https://github.com/lightspeed-core/lightspeed-evaluation) tool

* **`category_histogram.png`**
    * Q&A categories distribution graph


