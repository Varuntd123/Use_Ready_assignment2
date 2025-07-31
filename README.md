# Power Load Classification Project

## Overview
This project aims to classify power load types using machine learning techniques based on electrical usage and related features. The workflow includes data preprocessing, feature engineering, model training, and evaluation.

## Dataset
The dataset contains the following columns:
- `Date`: Date of the record
- `Usage_kWh`: Power usage in kilowatt-hours
- `Lagging_Current_Reactive_Power_kVarh`: Lagging current reactive power
- `Leading_Current_Reactive_Power_kVarh`: Leading current reactive power
- `CO2`: CO2 emissions
- `NSM`: Number of seconds from midnight
- `Load_Type`: The target variable (type of load)

## Project Structure
- `Power_Load_Classification_Project.ipynb`: Main Jupyter Notebook with code and analysis
- `README.md`: Project documentation
- (Add your dataset file here, e.g., `data.csv`)

## Setup Instructions
1. **Clone or download this repository** to your local machine.
2. **Install dependencies** (recommended: use Anaconda or a virtual environment):
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Power_Load_Classification_Project.ipynb
   ```

## Main Steps
1. **Data Preprocessing**: Clean and encode data, handle missing values, and standardize features.
2. **Feature Selection**: Select relevant features for modeling.
3. **Model Training**: Train machine learning models to classify the load type.
4. **Evaluation**: Assess model performance using appropriate metrics.

## Results
- The notebook includes visualizations and evaluation metrics for the trained models.

## Requirements
- Python 3.7+
- pandas
- scikit-learn
- matplotlib

## Author
Varun TD

---
Feel free to modify this README as your project evolves!
