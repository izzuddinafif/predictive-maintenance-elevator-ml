# Predictive Maintenance in Elevator Industry Using Machine Learning

## Project Overview
This project explores predictive maintenance for the elevator industry, focusing on using machine learning to anticipate maintenance needs based on sensor data. The dataset includes readings related to **ball bearings**, **humidity**, and **vibration**, which are critical indicators of elevator door performance. By implementing various machine learning models, we aim to detect early signs of mechanical issues, thereby improving safety and operational efficiency.

## Contents
- **Dataset**: `predictive-maintenance-dataset.csv`
- **Source Code**: `source-code.ipynb` (Jupyter Notebook implementing the ML models and preprocessing)
- **Explanation Video**: `explanation-ml.mp4` (provides a brief walkthrough of the project)

## Models Implemented
1. **Linear Regression**: Provides a baseline understanding of linear relationships in the data.
2. **Decision Tree Regressor**: Captures more complex, non-linear relationships.
3. **Random Forest Regressor**: An ensemble model that outperforms simpler models due to its ability to generalize and reduce overfitting.

## Data Preprocessing
The dataset undergoes several preprocessing steps to improve model accuracy:
- **Data Type Conversion**: Ensures consistent numeric formats.
- **Handling Missing Values**: Cleans incomplete records.
- **Outlier Detection and Treatment**: Identifies and manages anomalous values.
- **Feature Scaling**: Normalizes features to improve model performance.

## Results
Each model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) metrics. The **Random Forest Regressor** shows the highest predictive accuracy, making it the most suitable model for this dataset.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/izzuddinafif/predictive-maintenance-elevator-ml.git
    ```
2. Install dependencies (e.g., pandas, scikit-learn, matplotlib, seaborn).
3. Run the Jupyter Notebook `source-code.ipynb` to view the model training, evaluation, and results.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
This project was completed as part of coursework at Coventry University, under the module **6006CEM Machine Learning and Related Applications** from Faculty of Engineering, Environment and Computing.
