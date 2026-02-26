
Traffic Analysis Project

📄 Project Overview

This project focuses on analyzing traffic data to build predictive models. The goal is to understand traffic patterns and predict future conditions using machine learning techniques.

The project implements two distinct modeling approaches to tackle different aspects of the data:

Linear Regression: Used for predicting continuous variables (e.g., exact traffic volume or travel time).

Decision Tree: Used for classification tasks or capturing non-linear patterns (e.g., classifying traffic as "High", "Medium", or "Low").

📊 Dataset

Source: (https://catalog.data.gov/dataset/sdot-collisions-all-years-2a008?utm_source=chatgpt.com)

Description: The dataset contains historical traffic data.

Key Features:

Feature 1 :- DateTime

Feature 2 :- Junction_ID

Feature 3 :- Vehicles


🛠 Technologies Used

Language: Python

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn (Linear Regression, Decision Tree, Metrics)

Environment: Jupyter Notebook / Google Colab

🧠 Methodology

1. Data Preprocessing

Imported necessary libraries (pandas, matplotlib, sklearn).

Handled missing values and cleaned the dataset.

Split the data into training and testing sets.

2. Model Implementation

I implemented and compared two algorithms:

Linear Regression:

Goal: To establish a baseline for linear relationships in the traffic data.

Metric: R² Score (Coefficient of Determination).

Decision Tree:

Goal: To capture complex, non-linear decision boundaries.

Metric: Accuracy Score.

📈 Results & Visualization

The models were evaluated based on their respective metrics. A comparative analysis was performed to visualize the performance differences.

| **Model**         | **Metric Used** | **Score** |
| ----------------- | --------------- | --------- |
| Linear Regression | R² Score        | **0.87**  |
| Decision Tree     | Accuracy        | **100%**  |

![WhatsApp Image 2025-11-18 at 21 49 48_48c25367](https://github.com/user-attachments/assets/865298ad-f07c-4f0f-9755-4b4893388c49)


Visual Comparison:
The notebook includes a bar chart comparing the performance of the Linear Regression model (R²) against the Decision Tree (Accuracy) to visualize the strengths of each approach.

💻 Installation & Usage

Clone the repository

git clone [https://github.com/your-username/traffic-prediction.git](https://github.com/your-username/traffic-prediction.git)
cd traffic-prediction


Install dependencies

pip install pandas matplotlib scikit-learn


Run the Notebook
Launch Jupyter Notebook and open Traffic.ipynb:

jupyter notebook Traffic.ipynb


🔮 Future Improvements

[ ] Hyperparameter Tuning: Optimize the Decision Tree depth to prevent overfitting.

[ ] Time Series Analysis: Implement LSTM or ARIMA models for better temporal predictions.

[ ] Feature Engineering: Extract more insights from timestamps (e.g., "Rush Hour" flag).

👤 Author

Abu Zyan
Jeevan KS
Saurav Singh

GitHub: @abuzyan
        @Jeevan K S
        @Sauravgsingh
