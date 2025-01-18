# 🚀 Rossmann Store Sales Prediction 📊

Welcome to the **Rossmann Store Sales Prediction** project! This repository contains the code and analysis for the Kaggle competition. The goal is to predict future sales for Rossmann stores based on historical data, promotions, holidays, and weather conditions.

## 📈 Project Overview

The competition task is to predict daily sales for Rossmann stores using various machine learning models. The dataset includes historical sales, store details, promotional activities, and weather conditions.


### Models Used:
- **Linear Models** 📉: For initial regression and baseline predictions.
- **Linear Models** 📊: Linear Regression, Ridge , Lasso, Elastic Net.
- **Decision Trees** 🌳: To capture non-linear relationships and analyze feature importance.
- **Random Forests** 🌲: An ensemble model to improve accuracy and prevent overfitting.

### Key Goals:
- 🔍 **Analyze Historical Sales**: Understand trends, seasonal patterns, and effects of promotions.
- ✨ **Feature Engineering**: Create new features based on promotions, holidays, and dates.
- 🔮 **Sales Prediction**: Build predictive models to forecast future sales.

## 🗃 Dataset

Due to the large size of the dataset, it is not included in this repository. You can download it directly from Kaggle using the link below:

[**Download Dataset**](<https://www.kaggle.com/competitions/rossmann-store-sales/data>)

### Dataset Details:
- `train.csv`: Historical sales data along with store details.
- `test.csv`: Data for which sales predictions need to be made.
- `store.csv`: Additional store-related information.
- `sample_submission.csv`: Example submission format.

## 📂 Project Structure

- `data/`: Folder to store the dataset files (make sure to download them).
- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA), model training, and predictions.
- `src/`: Python scripts for data preprocessing, feature engineering, and model training.
- `models/`: Directory to save the trained models.

  
## ⚙️ Installation

To run this project locally, clone the repository:


```bash
git clone https://github.com/yourusername/rossmann-sales-prediction.git
cd rossmann-sales-prediction
```

## 💡 Model Performance

The models used include linear regression, decision trees, and random forests. Each model was evaluated using cross-validation and tested on out-of-sample data.

### Evaluation Metrics:
- **Mean Absolute Error (MAE)**: The average absolute error between predicted and actual sales.
- **Root Mean Squared Error (RMSE)**: A metric emphasizing larger errors.

## 🛠 How to Use

1. Download the dataset from Kaggle.
2. Run the Jupyter notebooks for EDA, feature engineering, and model training.
3. Use the trained model to predict sales and generate the submission file.


## 🤝 Contributing

Feel free to fork this repository, open issues, and submit pull requests. Your contributions are welcome! If you have suggestions or find issues, don't hesitate to reach out.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
