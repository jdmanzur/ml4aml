# Machine Learning Decision Support System for Acute Myeloid Leukemia

This study presents a decision support system that automatically recommends appropriate oncology therapy protocol for a given AML patient based on the survival/decease prediction.
The system proposed in this work combines prediction models computed by three established machine learning methods: Random Forests, Support Vector Machines and Logistic Regression. 
The purpose of this system is to automatically recommend the best set of treatments for patients with AML based on the automatic prediction of clinical outcome (survival/decease).
The datasets used to train and evaluate the prediction models that compose our decision support system come from studies by The Cancer Genome Atlas Program (TCGA) and Oregon Health and Science University (OHSU). 
These datasets comprise clinical and genetic data of patients with AML. Both are real and available in the public domain at [cBioPortal for Cancer Genomics](https://www.cbioportal.org/). The datasets taken from the TCGA and OHSU studies contained three subsets of data, collected from the same patients: clinical data gene mutation data, and gene expression data.

With the help of domain experts, the data collected was processed to avoid spurious, ambiguous or irrelevant data, and the most relevant features were selected. The treatment type received by the patient was also labeled by domain experts, to help the decision support system with the task of predicting the best treatment for maximized survival.

In this repository, the processed databases used in our study are available.

## Descriptive Analysis

Below we have the graphs generated for descriptive analysis of the numerical and categorical clinical features.

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/diagnosis_age_boxplot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/bone_marrow_boxplot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/mutation_count_boxplot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/pb_blast_boxplot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/wbc_boxplot.png)


![Image](https://github.com/jdmanzur/ml4aml_databases/figures/eln_risk_plot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/race_plot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/gender_plot.png)

![Image](https://github.com/jdmanzur/ml4aml_databases/figures/treatment_intensity_plot.png)
