# aws
完成 Module 2 Knowledge Check
<img width="1579" height="878" alt="{3C219134-7B33-4AA3-865B-66D8613AD95B}" src="https://github.com/user-attachments/assets/3732eed2-e2dc-4739-a0e7-7e929e45779f" />
Lab 3.1 - Amazon SageMaker - Creating and importing data
<img width="1713" height="955" alt="螢幕擷取畫面 2026-10-12 160602" src="https://github.com/user-attachments/assets/a5372d0c-8b1b-464c-abc1-6040aa8aa3f8" />
Lab 3.2 - Amazon SageMaker - Exploring Data
<img width="1909" height="1069" alt="1791962843_{2509E473-B096-494B-B267-80D7A78F9EF6}" src="https://github.com/user-attachments/assets/2c849cd5-6c84-4937-8950-a0d26ac1e021" />
完成 Lab 3.3 及 Lab 3.4 - Amazon SageMaker - Encoding Categorical Data - Amazo
<img width="1615" height="908" alt="1793138726_image(1)" src="https://github.com/user-attachments/assets/610281fd-a66c-47fb-a845-dba82cb2425e" />
<img width="1589" height="881" alt="1793138737_image(2)" src="https://github.com/user-attachments/assets/800a469a-44bb-4425-9efc-2481580c79aa" />
Lab 3.5 Amazon SageMaker - Deploying a model
<img width="1850" height="925" alt="1793168137_image(3)" src="https://github.com/user-attachments/assets/a959469c-a051-446e-b70d-e901e75caf69" />
Lab 3.6 Amazon SageMaker - Generating model performance metrics
<img width="1509" height="937" alt="1793173050_image(4)" src="https://github.com/user-attachments/assets/14c4259d-0871-43bd-8e72-542f1d51f98a" />
Lab 3.7 - Amazon SageMaker - Hyperparameter Tuning
<img width="1356" height="913" alt="1794383520_image(5)" src="https://github.com/user-attachments/assets/0e7f1709-af75-4bc9-a4d3-40556f2313a1" />
完成 Module 3 Knowledge Check
<img width="1409" height="876" alt="1794383571_image(6)" src="https://github.com/user-attachments/assets/1797cb42-a9bd-4b4b-b195-88377e8b690a" />
Challenge lab
<img width="1339" height="873" alt="1794921600_image(7)" src="https://github.com/user-attachments/assets/af304071-98f2-4fd3-a2a6-6f51a5fdcab4" />
# Hyperparameter Tuning Impact:
# Yes, tuning hyperparameters (such as max_depth, eta, subsample, and min_child_weight) using SageMaker HPO improved the model's ROC-AUC and overall generalization compared to the default XGBoost settings.

# 1. Did your model performance meet your business goal? If not, what would you do differently with more time?
# The final XGBoost model with HPO achieved a much better balance between Precision and Recall, moving closer to our business goal of predicting flight delays. With more time, I would address class imbalance using techniques like SMOTE or scale_pos_weight, incorporate real-time hourly weather forecasts, and test ensemble stacking methods.

# 2. How much did your model performance improve after modifying the dataset, features, and hyperparameters? Which techniques had the greatest impact?
# Performance improved steadily across iterations—from the baseline LinearLearner (~0.60 ROC-AUC) to adding holiday/weather features, switching to XGBoost, and finally running HPO (~0.70+ ROC-AUC). Switching to a tree-based model (XGBoost) and performing feature engineering (adding weather and temporal features) had the greatest impact on performance.

# 3. What were the biggest challenges you encountered in this project?
# The biggest challenges were handling the large multi-year dataset (merging files and managing memory), dealing with severe class imbalance (80% on-time vs. 20% delayed), and imputing missing weather station records accurately.

# 4. Are there any aspects of the pipeline that remain unclear to you?
# The end-to-end ML pipeline is clear, though fine-tuning the exact probability threshold for different business cost trade-offs and optimizing distributed HPO resource limits in production would benefit from further practice.

# 5. What are the three most important things you learned about machine learning during this project?
# 1) Data quality and domain-specific feature engineering matter more than the algorithm alone.
# 2) Machine learning is an iterative process of building a baseline, evaluating errors, and refining features and models.
# 3) Selecting the right evaluation metric (such as Recall and ROC-AUC instead of just Accuracy) is critical when working with imbalanced real-world datasets.
完成 Module 5 Knowledge Check
<img width="1464" height="802" alt="1795593135_image(9)" src="https://github.com/user-attachments/assets/1b6f210e-0c2b-4485-a438-09dc72a45cb1" />
lab 5
<img width="1426" height="842" alt="image" src="https://github.com/user-attachments/assets/b89445df-fd20-4cf1-992e-df8224158b2b" />
