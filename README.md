# Sampling_assignment
**#Assignment:** Sampling Techniques on Imbalanced Dataset

**#Objective:**
To analyze how different sampling techniques affect performance of machine learning models on an imbalanced dataset.

**#Dataset Used:**
Creditcard_data.csv

**#Steps Performed:**
Loaded dataset
Balanced dataset using SMOTE
Created 5 samples
Applied 5 sampling techniques
Trained 5 ML models
Compared accuracy

**#Sampling Techniques Used:**
Random Under Sampling
Random Over Sampling
SMOTE
Tomek Links
NearMiss

**#Models Used:**
Logistic Regression
Decision Tree
Random Forest
SVM
KNN

**#Result Summary:**

<img width="560" height="163" alt="image" src="https://github.com/user-attachments/assets/b93a43a3-58af-457d-b743-33d7ad33e87a" />


**#Conclusion:**
The objective of this assignment was to analyze the effect of different sampling techniques on machine learning models when applied to an imbalanced dataset. From the experimental results, it is clear that sampling methods significantly influence model performance.

Among the five machine learning models tested, Model M3 (Random Forest Classifier) delivered the best performance, achieving 100% accuracy with Sampling1, and maintaining consistently high accuracy across all sampling techniques. This indicates that Random Forest is highly robust and well-suited for handling balanced as well as imbalanced datasets.

In terms of sampling techniques, Sampling1 emerged as the most effective overall, providing the highest accuracy for three out of five models (M1, M3, and M4). However, the results also show that different models respond differently to sampling strategies. For example, Sampling5 worked best for Model M2, while Sampling4 performed best for Model M5.

On the other hand, Model M4 (SVM) showed comparatively poor performance across all techniques, suggesting that it is more sensitive to class imbalance and sampling variations.

Overall, it can be concluded that:
- Random Forest is the most reliable model for this dataset
- Sampling1 is the most effective general-purpose sampling technique
- Choice of sampling technique should depend on the specific model being used

Thus, selecting an appropriate combination of sampling technique and machine learning model is crucial for achieving optimal performance on imbalanced datasets.
