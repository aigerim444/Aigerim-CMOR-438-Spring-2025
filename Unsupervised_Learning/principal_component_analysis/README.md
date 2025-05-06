
# Principal Component Analysis
PCA is an unsupervised dimensionality reduction technique used to project a higher dimensional data into a lower dimensional space. it does so by identifying the directions along which the data varies the most (to preserve as much variance as possible) and transforms the original features into a new set of orthogonal components ranked by variance.

## Application
In this section, PCA is applied to the Breast Cancer Wisconsin dataset. It is applied to:
- Reduce dimensionality for visualization
- Observe class separation in the transformed space
- Analayze how much variance is captured by the two top components

The dataset contains 30 numeric features extracted from images of breast masses, such as radius, area, texture, and other characteristics.
The target variable was the diagnosis: either M = malignant, or B = benign. These are descriptors for a tumor.

The preprocessing steps that were taken:
- Removing missing values
- Scaling features
- Mapping Diagnosis label to a numeric format

### Dependencies

Install if not already installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn