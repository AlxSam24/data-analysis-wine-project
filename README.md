
# Wine Classification Analysis

## Project Description
This project uses machine learning to classify wines based on their chemical composition. The dataset contains 178 wine samples from three different producers in Italy, each characterized by 13 chemical properties including alcohol content, acidity, phenols, and proline levels.

## Objective
Determine the origin of wine (one of three cultivars) using supervised classification models, enabling quality control, fraud detection, and food authenticity verification.

## Dataset
- **Samples:** 178 wines
- **Classes:** 3 wine cultivars (balanced distribution)
- **Features:** 13 chemical properties (alcohol %, malic acid, ash, magnesium, total phenols, flavanoids, color intensity, hue, proline, etc.)

## Requirements
```
numpy
pandas
scikit-learn
matplotlib
seaborn
```

## Methodology
1. **Exploratory Data Analysis (EDA)** - Distribution analysis, correlation heatmaps, outlier detection
2. **Data Preprocessing** - Standardization and Principal Component Analysis (PCA)
3. **Model Development** - Neural Networks and Decision Trees
4. **Evaluation** - Accuracy scores and confusion matrices

## Key Findings
- **Decision Tree:** 94.44% accuracy (superior performance)
- **Neural Network:** 91.67% accuracy (with hyperparameter tuning)
- Strong correlations identified between alcohol/proline and total phenols/flavanoids
- Decision trees recommended for this dataset; neural networks better for larger, complex datasets

## Notes
This was my first machine learning project, where I applied foundational concepts using pandas and numpy for data manipulation, scikit-learn for model implementation, and Jupyter notebooks for interactive development and visualization. It provided hands-on experience with the complete machine learning workflow from data exploration to model evaluation.
