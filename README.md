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





# Data Preparation

Primary dataset used:

Total Nutrient Intake (First Day and Second Day)
Files: DR1TOT_J Data, DR2TOT_J Data
Size: ~16.9 MB total
Date Published: June 2020
The dataset includes records of nutrient intake, such as:

Macronutrients: Protein, Carbohydrates, Fats
Micronutrients: Vitamins A, C, D, E, K, Calcium, Iron, Magnesium, Zinc
Fiber and specific phytochemicals linked to cancer prevention.
Supplementary Datasets
Dietary Supplement Use (24-Hour and 30-Day): Information on supplement consumption patterns, including antioxidant supplements.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/username/NutritionalIntake_CancerRisk.git
cd NutritionalIntake_CancerRisk
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Usage
Data Cleaning: Run data_cleaning.py to preprocess and clean the data files.

bash
Copy code
python data_cleaning.py
Exploratory Data Analysis (EDA): Execute eda_analysis.py to generate initial visualizations of nutrient distributions, daily variances, and correlations with potential cancer biomarkers.

bash
Copy code
python eda_analysis.py
Statistical Analysis: Use stat_analysis.py to perform correlation tests and regression analysis, identifying nutrients with significant associations to cancer risk.

bash
Copy code
python stat_analysis.py
Machine Learning Model: Run cancer_risk_model.py to train and test a classification model predicting cancer risk based on nutrient intake patterns.

bash
Copy code
python cancer_risk_model.py
Analysis & Visualizations
1. Nutrient Distribution Analysis
Objective: Identify the distribution of key nutrients (fiber, vitamins A, C, E) across participants.
Visualization: Box plots and histograms showing nutrient distribution and skewness.
2. Correlation Matrix of Nutrients and Cancer Incidence
Objective: Identify correlations between nutrient intake and cancer-related biomarkers or self-reported diagnoses.
Visualization: Heatmap showing correlations, with high-risk nutrients highlighted.
3. Nutrient Intake vs. Cancer Risk Model
Objective: Use logistic regression to predict cancer risk based on nutrient patterns.
Visualization: ROC curves and confusion matrix showing model accuracy and performance.
Example Visualizations
Visualization	Description
Nutrient Distribution	Box plots of nutrients like fiber, vitamin C, showing intake variation across participants.
Correlation Heatmap	Heatmap visualizing correlations between nutrient intake (e.g., fiber, fats) and cancer biomarkers.
Cancer Risk Prediction	ROC curve for logistic regression model predicting cancer risk based on nutrient data.
Results


##Preprocessing:
The selected datasets were categorized into three groups based on the "Gillison"
classification:

1. Normal
2. Benign
3. Tumor

Subsequently, the quality of the data was assessed using the MetaQC package in R. The
results confirmed that these four datasets were of the highest quality and suitable for
further analysis.
##Column Descriptions:
>**• First Row (GSE Names):** The first row contains the names of the GEO Series (GSE)
datasets from which the data were sourced. Each column corresponds to a specific GSE,
indicating the origin of the sample data.

>**• Second Row (GSM Identifiers):** The second row includes the GEO Sample (GSM)
identifiers, which are unique identifiers for each sample within the GSE datasets. These
identifiers help trace back each sample to its original source in the NCBI GEO database.

>**• Gillison Classification (Parameter after ):** The numbers following the underscore ()

in the second row represent the Gillison classification of each sample. This classification
categorizes the samples into three groups based on their clinical status:

1: Normal

2: Benign

3: Tumor

Data Description
Primary dataset used:

Total Nutrient Intake (First Day and Second Day)
Files: DR1TOT_J Data, DR2TOT_J Data
Size: ~16.9 MB total
Date Published: June 2020
The dataset includes records of nutrient intake, such as:

Macronutrients: Protein, Carbohydrates, Fats
Micronutrients: Vitamins A, C, D, E, K, Calcium, Iron, Magnesium, Zinc
Fiber and specific phytochemicals linked to cancer prevention.
Supplementary Datasets
Dietary Supplement Use (24-Hour and 30-Day): Information on supplement consumption patterns, including antioxidant supplements.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/username/NutritionalIntake_CancerRisk.git
cd NutritionalIntake_CancerRisk
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Usage
Data Cleaning: Run data_cleaning.py to preprocess and clean the data files.

bash
Copy code
python data_cleaning.py
Exploratory Data Analysis (EDA): Execute eda_analysis.py to generate initial visualizations of nutrient distributions, daily variances, and correlations with potential cancer biomarkers.

bash
Copy code
python eda_analysis.py
Statistical Analysis: Use stat_analysis.py to perform correlation tests and regression analysis, identifying nutrients with significant associations to cancer risk.

bash
Copy code
python stat_analysis.py
Machine Learning Model: Run cancer_risk_model.py to train and test a classification model predicting cancer risk based on nutrient intake patterns.

bash
Copy code
python cancer_risk_model.py
Analysis & Visualizations
1. Nutrient Distribution Analysis
Objective: Identify the distribution of key nutrients (fiber, vitamins A, C, E) across participants.
Visualization: Box plots and histograms showing nutrient distribution and skewness.
2. Correlation Matrix of Nutrients and Cancer Incidence
Objective: Identify correlations between nutrient intake and cancer-related biomarkers or self-reported diagnoses.
Visualization: Heatmap showing correlations, with high-risk nutrients highlighted.
3. Nutrient Intake vs. Cancer Risk Model
Objective: Use logistic regression to predict cancer risk based on nutrient patterns.
Visualization: ROC curves and confusion matrix showing model accuracy and performance.
Example Visualizations
Visualization	Description
Nutrient Distribution	Box plots of nutrients like fiber, vitamin C, showing intake variation across participants.
Correlation Heatmap	Heatmap visualizing correlations between nutrient intake (e.g., fiber, fats) and cancer biomarkers.
Cancer Risk Prediction	ROC curve for logistic regression model predicting cancer risk based on nutrient data.
Results
Key findings:

High Fiber Intake: Correlated with a reduced risk of colorectal cancer.
Vitamin D and Calcium: Inverse correlation with several cancer types, supporting a protective role.
High Fat Diets: Showed increased risk correlations, especially with high saturated fat intake.
These results offer insight into dietary modifications that may lower cancer risk.

Contributing
Contributions are welcome! If you would like to contribute, please submit a pull request or reach out to the project maintainer.

License
This project is licensed under the MIT License. See the LICENSE file for details.

