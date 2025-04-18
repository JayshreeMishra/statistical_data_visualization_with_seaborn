# Statistical Data Visualization with Seaborn

## Overview
This project employs the statistical data visualization library, Seaborn, to discover and explore relationships in the Breast Cancer Wisconsin (Diagnostic) dataset. The analysis includes exploratory data analysis (EDA), feature selection, and the application of a boosted decision tree classifier with XGBoost to classify tumors as either malignant or benign.

## Case Study
### Dataset Information
The Breast Cancer Diagnostic dataset, available on the UCI Machine Learning Repository, consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image. The dataset includes:
- **ID number**
- **Diagnosis** (M = malignant, B = benign)
- Ten real-valued features computed for each cell nucleus, including radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

### Attribute Information
1. **radius (mean of distances from center to points on the perimeter)**
2. **texture (standard deviation of gray-scale values)**
3. **perimeter**
4. **area**
5. **smoothness (local variation in radius lengths)**
6. **compactness (perimeter^2 / area - 1.0)**
7. **concavity (severity of concave portions of the contour)**
8. **concave points (number of concave portions of the contour)**
9. **symmetry**
10. **fractal dimension ("coastline approximation" - 1)**

## Objectives
- **Perform Exploratory Data Analysis (EDA):** Gain insights into the dataset by visualizing distributions, relationships, and variances of the features.
- **Drop Correlated Features:** Reduce redundancy by identifying and removing highly correlated features.
- **Implement Feature Selection:** Utilize several feature extraction methods, including correlation-based feature selection, univariate feature selection, recursive feature elimination, principal component analysis (PCA), and tree-based feature selection.
- **Build a Classifier:** Develop a boosted decision tree classifier using XGBoost to accurately classify tumors as malignant or benign.

## Impact
### Data Analysis
- **Distribution Analysis:** Visualized the distribution of each feature and compared distributions between malignant and benign diagnoses using violin plots, box plots, and swarm plots.
- **Correlation Analysis:** Generated heatmaps to observe correlations between features, helping identify redundant features to drop.
- **Feature Selection:** Applied various feature selection methods to reduce dimensionality and improve model performance.

### Classification Model
- **XGBoost Classifier:** Built a boosted decision tree classifier using XGBoost. The classifier achieved high accuracy in classifying tumors, with an accuracy score of approximately 97%.
- **Model Evaluation:** Evaluated model performance using confusion matrices and accuracy scores. The model demonstrated robust performance in distinguishing between malignant and benign tumors.

## Conclusion
This project highlights the importance of data visualization and feature selection in improving machine learning model performance. By leveraging Seaborn for data visualization and applying multiple feature selection techniques, the project successfully developed an accurate classifier for breast cancer diagnosis.
