# Cancer-predictive-model
<img src="https://github.com/user-attachments/assets/450675c3-a520-468c-9c9d-50f77750eb2c" alt="Prostate-Cancer" width="1000" height="500"/>

This project aims to develop a predictive model to assess cancer risk based on various health, dietary, and demographic factors. We use a structured process to clean, preprocess, and model the data, applying advanced machine learning techniques, including transformers for feature extraction, to improve prediction accuracy.

Table of Contents
Project Description
Data Description
Installation
Usage
Analysis & Visualizations
Results
Contributing
License
Project Description
This analysis uses dietary records and cancer-related literature to examine possible links between nutrient intake and cancer. Using machine learning models, statistical tests, and visualizations, the project aims to identify dietary factors that may correlate with cancer risk or serve as protective elements against cancer development.

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

