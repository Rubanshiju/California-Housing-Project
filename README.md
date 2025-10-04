
California Housing Price Prediction Project


🏠 Project Description
This project focuses on predicting the median house value for districts in California using a regression model. The analysis involves exploring the dataset, preparing the features, training a machine learning model, and evaluating its performance.

🎯 Goal
The primary objective is to build a predictive model that accurately estimates the **Median House Price** (`Price`) based on various socio-economic and geographical features of the California housing districts.

📊 Dataset
The project utilizes the California Housing dataset.

| Feature Name | Description |
| :--- | :--- |
| **Income** | Median Income for the district. |
| **Age** | Median age of the houses in the district. |
| **Rooms** | Average number of rooms. |
| **Bedrooms** | Average number of bedrooms. |
| **Population** | District population. |
| **Occupancy** | Average house occupancy. |
| **Latitude** | District latitude. |
| **Longitude** | District longitude. |
| **Price** | **Target variable:** Median House Price (in hundreds of thousands of dollars). |

The dataset contains **20,640 entries** and was found to have **no missing values** or **duplicates** during the initial data inspection.

🧪 Methodology
The project follows a standard machine learning workflow, including:

1.  **Data Loading and Inspection**: Initial review of the dataset structure and summary statistics.
2.  **Data Cleaning**: Verification and handling of missing values and duplicate records.
3.  **Model Training**: A **Linear Regression model** was likely used to predict the house prices, as indicated by the subsequent assumption checks.
4.  **Assumptions Check**: The notebook includes diagnostic plots to verify the core assumptions of linear regression, such as:
    * **Normality** of residuals (using a histogram).
    * **Homoscedasticity** (Predicted vs Residuals plot).
    * **Linearity/Independence** (Residuals vs Order plot).
5.  **Evaluation**: The model performance was assessed using key regression metrics.

📈 Evaluation Metrics
The model's performance was evaluated using the following error metrics:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**

🛠️ Requirements & Dependencies
The notebook uses standard Python data science libraries. You will need the following to run the project:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn` (for model and metrics)
