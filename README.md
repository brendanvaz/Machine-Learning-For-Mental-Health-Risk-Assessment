Advanced Machine Learning for Mental Health Risk Assessment in the Technology Sector

Overview:
This project investigates the use of advanced machine learning methodologies to predict mental health risks in the technology industry. By analyzing the 2016 Open Sourcing Mental Illness (OSMI) Mental Health in Tech Survey dataset, we identified critical workplace factors influencing mental health. The project also introduces a clustering-based risk indicator to categorize employees into mental health risk levels, enabling targeted organizational interventions.

Objectives:

Predict mental health risks among tech employees using machine learning models.
Identify key predictors such as workplace stress, social support, and demographic factors.
Develop a clustering-based risk indicator to classify employees into risk levels.
Provide actionable insights for tech companies to improve employee mental health.

Dataset

Source: OSMI Mental Health in Tech Survey 2016.
Description: The dataset includes 1,433 responses covering:
Employment status and workplace environment.
Demographic details like age, gender, and location.
Mental health history and attitudes toward mental health discussions.

Methodology

Data Preprocessing:

Handled missing values with imputation techniques.
Encoded categorical variables and standardized numerical features.
Balanced the dataset to ensure fair model evaluation.

Exploratory Data Analysis (EDA):

Visualized trends in age distribution, mental health benefits, and employer support.
Investigated correlations between workplace factors and mental health outcomes.

Machine Learning Models:

Tested multiple algorithms: Logistic Regression, SVM, Random Forest, Gradient Boosting, LightGBM, etc.
Applied hyperparameter tuning using Optuna to optimize performance.

Cluster Analysis:

Developed a risk indicator using clustering techniques like K-Means++, Spectral Clustering, and Agglomerative Clustering.
Categorized employees into High, Medium, and Low-risk clusters.

Evaluation Metrics:

Accuracy, Precision, Recall, F1 Score, ROC-AUC.
Statistical tests like the Kolmogorov-Smirnov test for distribution analysis.

Results

Best Model: LightGBM
Accuracy: 91.74%
Precision (weighted): 91.8%
Recall (weighted): 91.5%
Key Predictors Identified:
Workplace stress, insufficient social support, and past mental health issues.
Younger employees and women were found to be at higher risk.
Risk Indicator: Successfully categorized employees into actionable mental health risk levels.

Technologies Used

Programming Language: Python
Libraries:
Pandas, NumPy, Scikit-learn, LightGBM, Matplotlib, Seaborn, Optuna.

Future Work

Expand the dataset to improve model generalization.
Incorporate longitudinal studies for better causal insights.
Explore the integration of physiological data for more robust models.
Develop interventions tailored to specific demographic groups.

Author

Brendan Ezekiel Agnelo Vaz
MSc Data Science, University of Nottingham

Acknowledgments

I express my sincere gratitude to my supervisor, Dr. Jamie Twycross, for his invaluable guidance and support. I also thank the University of Nottingham, my family, and friends for their encouragement throughout this research.
