# TalentManagement
This repository contains experiments and analyses on Talent Management using various machine learning models to support objective decision-making in employee selection.

# Authors
Siska Komala Sari - Sari Dewi Budiwati - Sugondo Hadiyoso - Halomoan Filipus Simarmata - Siti Nurajijah - Putri Adelya Zahra - Baskoro Pradito

# Abstract 
Talent Management is a strategic process implemented by organizations to optimize human resource potential. It encompasses various stages, including talent acquisition, selection, development, and retention of high-performing individuals aligned with institutional goals. At Institution X, Talent Management not only focuses on recruiting new employees but also on managing and developing existing staff to maximize organizational contributions. However, the manual analysis of numerous
evaluation criteria is often complex and subjective, particularly when relying on traditional recommendation systems. To address this issue, a machine learning-based decision support system was developed to provide objective recommendations for structural positions. This study utilized a real-world dataset from a higher education institution in Indonesia. Five machine learning models were implemented: Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), eXtreme Gradient
Boosting (XGBoost), and a Neural Network model. The models were evaluated in two phases: default settings and hyperparameter optimization (HPO), to assess the impact of tuning on performance. Results showed that Random Forest and XGBoost achieved the highest accuracy scores of 80% and 78%, respectively, while KNN demonstrated noticeable improvement after HPO. To ensure fair learning, the class imbalance was handled using the Synthetic Minority Over-sampling Technique (SMOTE), applied only to the training data. Train-test accuracy analysis confirmed minimal overfitting across models.
Furthermore, a hybrid feature selection method combining model-based selection (RandomForestClassifier) and statistical testing (Kruskal-Wallis) was proposed to improve both model interpretability and domain relevance.

# Acknowledgement
This work is part of The Applied Research for Leading Higher Education initiative. We sincerely express our gratitude to Telkom University for providing financial support for this research. Additionally, we acknowledge the contributions of all collaborators and researchers involved in this study, whose insights and efforts have been invaluable in achieving these results.

# Publication
- Third publication: under consideration 
- B. Pradito, S. D. Budiwati, E. Hernawati and S. K. Sari, "Classification for Human Resource Talent Management Using Support Vector Machine Model," 2024 4th International Conference of Science and Information Technology in Smart Administration (ICSINTESA), Balikpapan, Indonesia, 2024, pp. 282-287, doi: 10.1109/ICSINTESA62455.2024.10747875.
- S. Nurajijah, D. R. Wijaya and S. K. Sari, "Gradient Tree Boosting for HR Talent Management Application," 2022 10th International Conference on Information and Communication Technology (ICoICT), Bandung, Indonesia, 2022, pp. 264-269, doi: 10.1109/ICoICT55009.2022.9914833.
