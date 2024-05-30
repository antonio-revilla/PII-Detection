# PII-Detection
This project is intended for detecting **personal identifiable information** in educational data, such as, student essays. The goal is to be able to remove PII data to enable the utilization educational data without sacrificing privacy. 

### deberta.ipynb
This notebook is used to train a base deBERTa model for token classification on the educational dataset.

### ensemble_deberta.ipynb
This notebook is used to train and ensemble approach with deBERTa base model train on different folds of the data. 
