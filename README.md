# LCA 2 - K-Means Clustering on Heart Disease Dataset

## Student Details
**Name:** Shreya Jakkulwar
**PRN:** 1262241674
**Roll No:** 61
**Class:** TY CSE B
**Batch:** C

## Subject
Basics of Machine Learning (BML)

## Aim
To train the system using the Heart Disease dataset obtained from the UCI ML Repository and determine the accuracy using the K-Means Clustering classifier.

## Dataset
- **Source:** UCI Machine Learning Repository - Heart Disease Dataset (id = 45)
- **Instances:** 303
- **Features:** 13 clinical attributes (age, sex, cholesterol, chest pain type, etc.)
- **Target:** Presence of heart disease (converted to binary: 0 = no disease, 1 = disease)

## Steps Performed
1. Loaded dataset using `ucimlrepo`
2. Handled missing values by filling with median
3. Converted target column to binary classes
4. Scaled features using `StandardScaler`
5. Applied `KMeans` clustering with `n_clusters = 2`
6. Mapped cluster labels to actual labels using majority matching
7. Calculated accuracy using `accuracy_score`

## Libraries Used
- pandas
- numpy
- scikit-learn
- ucimlrepo

## Result
The K-Means clustering model was trained on the Heart Disease dataset and the accuracy achieved is printed in the notebook output.

## How to Run
1. Open the `.ipynb` file in Google Colab
2. Run all cells in order
3. Accuracy will be displayed at the end
