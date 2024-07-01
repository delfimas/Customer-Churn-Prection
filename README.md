# Customer-Churn-Prediction

# Project Overview
This project aims to predict customer churn for a telecommunications company. The goal is to identify customers who are likely to leave the service and to understand the factors influencing their decision.

## Repository Structure
- `data/`: Contains raw and processed data.
- `notebooks/`: Jupyter notebooks for data preprocessing, modeling, and prediction.
- `src/`: Python scripts for data preprocessing, modeling, and prediction.
- `results/`: Contains figures and saved models.
- `README.md`: Project overview and instructions.
- `requirements.txt`: Required Python packages.
- `LICENSE`: Project license.
## Notebooks
- **Preprocessing**: Data cleaning, feature engineering, and data transformation. The notebook includes:
  - Exploratory Data Analysis (EDA)
  - Data cleaning: Handling missing values, outliers, and duplicates.
  - Feature engineering: Creating new features and transforming existing ones.
  - Encoding categorical variables using Ordinal Encoder and One-Hot Encoding.
  - Removing features with high correlation and low variance.
- **Modeling**: Model training, evaluation, and hyperparameter tuning.
- **Prediction**: Making predictions on new data and evaluating model performance. The notebook replicates preprocessing steps from the training data, including:
  - Removing the same variables.
  - Imputing missing values using the same approach.
  - Applying the same encoding for categorical variables.
  - Ensuring consistency with the variables used to train the model.

## Usage
### Download the Data
To run the notebooks, you need to download the dataset:

1. **Download the data**:
   - https://drive.google.com/drive/folders/1qfo7-dIfIbDM8vFXxJqWy6LD9PwHdoYz?usp=drive_link

2. **Place the downloaded data in the `data/raw/` directory**.

### Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/delfimas/Customer-Churn-Prediction.git
   cd customer-churn-prediction

   
