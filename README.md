# Cancer-predictive-model
<img src="https://github.com/user-attachments/assets/450675c3-a520-468c-9c9d-50f77750eb2c" alt="Prostate-Cancer" width="1200" height="600"/>


# Team Members



Marion Macharia

Wilson Mutungu

Kelvin Letimalo

Zacharia Komu




# PROJECT OVERVIEW



This project aims to develop a predictive model to assess cancer risk based on various health, dietary, and demographic factors. We use a structured process to clean, preprocess, and model the data, applying advanced machine learning techniques, including transformers for feature extraction, to improve prediction accuracy.




# Table of Contents



Business Understanding

Problem Statement

Data Understanding

Data Preparation

Exploratory Data Analysis

Modeling and Evaluation




# Business Understanding


**This project tackles the critical issue of early and accurate prostate cancer risk prediction. Prostate cancer is a significant health concern, being one of the most common cancers in men. Early detection is crucial for successful treatment and improved patient outcomes.**

**Currently, prostate cancer risk assessment often relies on limited factors like age, family history, and PSA levels. However, these methods may not always provide a comprehensive risk profile, leading to potential missed diagnoses or unnecessary biopsies.**

**Our project addresses this problem by:**

    Leveraging a broader range of factors: By incorporating health, dietary, and demographic data, your model aims to build a more complete picture of individual risk.
    Employing advanced machine learning: Using these techniques allows for the identification of complex patterns and relationships within the data, leading to more accurate predictions.
    Improving prediction accuracy: Enhanced accuracy translates to better-informed decisions about screening, diagnosis, and treatment.

**The business impact of our project includes:**

    Improved early detection: Leading to timely intervention and improved patient survival rates.
    Reduced healthcare costs: By avoiding unnecessary procedures and optimizing resource allocation.
    Personalized risk assessment: Empowering individuals to make informed decisions about their health.
    Advancements in prostate cancer research: Providing valuable insights into the factors influencing risk.

**In essence, our project is addressing a significant healthcare challenge by developing a predictive model that can lead to more effective and personalized prostate cancer management.**





# Problem Statement


Prostate cancer is one of the most common cancers affecting men worldwide, with more new cases reported annually. Despite advancements in screening techniques such as the Prostate-Specific Antigen (PSA) test, the current methods of diagnosing prostate cancer are limited in their predictive accuracy. These traditional methods rely heavily on a few factors such as age, family history, and PSA levels, which do not capture the full spectrum of potential risk indicators. This leads to two major issues:

 Missed Early Diagnoses:
 
Current methods might fail to identify high-risk individuals, leading to delayed diagnosis and missed opportunities for early intervention. Without early detection, patients may not receive timely treatment, which can severely impact survival rates and quality of life.

Unnecessary Biopsies and Overdiagnosis:

On the other hand, reliance on limited factors can result in overdiagnosis, leading to unnecessary biopsies and treatments. These invasive procedures can cause anxiety, unnecessary costs, and sometimes even harm to patients, especially when the risks of cancer are overestimated.


# Data Understanding

We have 2 datasets for this project:

Data Sources:

○ Health record datasets: MIMIC-III, NHANES.

○ Genetic data: 1000 Genomes Project, HapMap.

○ Prostate - cancer - Genomics from SEER

 Prostate_Cancer_Genomics_DSLanders


**This dataset is a carefully curated compilation of genomic data related to prostate cancer,
created by merging four GEO Series (GSE) datasets from the NCBI database.**

**The selection process involved identifying datasets associated with three specific GPL
platforms (GPL570, GPL96, and GPL571) to ensure compatibility and consistency acrossthe data.**

**The final dataset provides a comprehensive resource for analyzing gene
expression and genomic variations across different prostate cancer conditions.**
## Data Sources:
Initially, several GSE datasets with different GPL platforms were downloaded from the
NCBI database. After an in-depth analysis, it was determined that GPL570, GPL96, and
GPL571 platforms share significant overlap. Therefore, datasets corresponding to these
three platforms were selected for further analysis. The raw data for each GSE was
downloaded from the NCBI GEO database

(https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi). If a dataset lacked raw data, it was
excluded from the selection.
The four selected GSE datasets are:
1. • GSE32448
2. • GSE46602
3. • GSE7307
4. • GSE69223

# Data Preparation

Data Cleaning
Checking for duplicates
Checking for missing values

## Exploratory Data Analysis

![EDA](https://github.com/user-attachments/assets/69d9a2f5-5d5a-4ada-b77a-e0331ecf54d2)

The descriptive statistics have been generated successfully, providing insights into the central tendency, dispersion, and shape of the dataset's distribution. This information will help us understand the data better and identify any potential outliers or trends.

## correlation matrix of key numerical features
![Correlation](https://github.com/user-attachments/assets/735a6a50-4356-4c9f-bf9e-a411d7c42ab7)




Contributing
Contributions are welcome! If you would like to contribute, please submit a pull request or reach out to the project maintainer.

License
This project is licensed under the MIT License. See the LICENSE file for details.

