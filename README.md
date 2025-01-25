**Project**: Cryptocurrency Price Prediction Using CatBoost
**Overview**
This project demonstrates a machine learning pipeline for predicting cryptocurrency prices using the CatBoost algorithm. It highlights the practical implementation of data preprocessing, model training, and performance evaluation for time-series forecasting in the financial domain.

**Features**
Data Handling: Efficiently loads and preprocesses large cryptocurrency datasets.
Exploratory Data Analysis (EDA): Provides insights into data trends, distributions, and relationships.
Modeling: Leverages CatBoost for its efficiency and ability to handle categorical features without extensive encoding.
Performance Evaluation: Assesses model performance using key metrics, including Pearson's coefficient and RMSE.

**Datasets**
The following datasets from the G-Research crypto forecasting competition are used: https://www.kaggle.com/code/dipikajiandani/crypto-prediction-catboost/input

train.csv: Historical cryptocurrency data for training.
supplemental_train.csv: Additional training data for enhanced learning.
example_test.csv: A test set for pipeline validation.
asset_details.csv: Metadata on cryptocurrencies included in the datasets.

**Outputs**
Average Pearson's Coefficient: 0.00796
This metric indicates little to no linear correlation between the predicted and actual cryptocurrency prices, suggesting that while the model predicts small changes, it struggles to capture broader trends or relationships effectively.

Average RMSE: 0.00404
The model achieves a low root mean squared error, implying that the magnitude of prediction errors is small. However, this alone does not guarantee strong predictive ability due to the low Pearson's coefficient.

**Visualization**: Includes plots illustrating data trends, model predictions, and performance comparisons.

**Feature Importance**: Identifies the most impactful features driving the model’s predictions.

**Conclusion**
The project successfully demonstrates that CatBoost is a capable tool for predicting cryptocurrency prices, achieving low RMSE values. However, the low Pearson's coefficient highlights the need for improvement in feature engineering and model optimization to capture better correlations and trends in the data. These results provide a solid foundation for further experimentation and refinement.

**How to Run**
Clone the repository.
Install dependencies listed below.
Execute the Jupyter notebook to preprocess data, train the model, and evaluate results.

**Dependencies**
Python 3.8+
CatBoost
NumPy
Pandas
Matplotlib

**Future Improvements**
Extend feature engineering with advanced time-series techniques to improve correlation metrics.
Experiment with hyperparameter tuning for CatBoost to optimize model performance.
Explore ensemble methods or alternative algorithms to enhance predictive accuracy.
