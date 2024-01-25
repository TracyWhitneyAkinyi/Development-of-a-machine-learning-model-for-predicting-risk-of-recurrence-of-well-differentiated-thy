# Thyroid-Machine-Learning-Analysis

Development of a machine learning model for predicting risk of recurrence of well-differentiated thyroid cancer

This task was to identify key variables in data as well as train machine learning models for predicting the likelihood of recurrence in patients diagnosed with well-differentiated thyroid cancer.

While the overall survival rate for thyroid cancer is relatively high, ranging from 93% to 98% depending on the stage and subtype of the tumor, recurrence of the disease remains a major concern [Julienne Sanchez Perez, 2023 ](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10555853/). A study has shown that more than 30% of patients with Well-Differentiated Thyroid Cancer (WDTC) recurrence are diagnosed after the first decade of follow-up [Cavalheiro, 2023](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9913047/).

The original dataset was published in [Borzooei, S., Briganti, G., Golparian, M. et al. Machine learning for risk stratification of thyroid cancer patients: a 15-year cohort study. Eur Arch Otorhinolaryngol (2023)](https://link.springer.com/article/10.1007/s00405-023-08299-w). This data can be accessed on [Differentiated Thyroid Cancer Recurrence](https://archive.ics.uci.edu/dataset/915/differentiated+thyroid+cancer+recurrence).

The following are our variable names

* Age
* Gender
* Smoking
* Hx Smoking
* Hx Radiotherapy
* Thyroid Function
* Physical Examination
* Adenopathy
* Pathology
* Focality
* Risk
* T
* N
* M
* Stage
* Response
* Recurred

** Table of contents**
* Summary Statistics
* Testing of machine learning models
* Permutation Importance
  * SHAP Plot
  * LIME
*Model construction and performance validation
