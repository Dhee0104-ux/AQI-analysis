# 🌍 Air Quality Index (AQI) Analysis and Prediction

A Data Science and Machine Learning project that analyzes air pollution across Indian cities, visualizes pollutant concentrations, identifies AQI patterns, and predicts Air Quality Index (AQI) using Random Forest Regression.

## 📌 Project Overview

Air pollution is a major environmental challenge affecting public health and quality of life. This project explores historical air quality data from different Indian cities to understand pollution patterns and identify the pollutants that contribute most to AQI predictions.

The project uses Python, Pandas, Matplotlib, Seaborn, and Scikit-learn to perform data analysis, visualization, and machine learning.

## 🎯 Objectives

- Analyze historical AQI data across Indian cities.
- Identify major air pollutants and their concentrations.
- Understand relationships between pollutants using correlation analysis.
- Classify air quality into different AQI categories.
- Visualize daily and city-wise AQI trends.
- Build a machine learning model to predict AQI.
- Evaluate model performance using regression metrics.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| Google Colab | Development environment |

## 📂 Dataset

**Dataset:** India Air Quality Dataset (2015–2020)

**Source:** [Kaggle – Air Quality Data in India](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

The dataset contains historical air quality measurements from multiple Indian cities.

### Important Files

| File | Description |
|---|---|
| `city_day.csv` | Daily city-wise air quality measurements |
| `city_hour.csv` | Hourly city-wise air quality measurements |
| `station_day.csv` | Daily monitoring station data |
| `station_hour.csv` | Hourly monitoring station data |
| `stations.csv` | Air quality monitoring station details |

**Primary dataset used:** `city_day.csv`

### Important Features

- City
- Date
- PM2.5
- PM10
- NO
- NO2
- NOx
- NH3
- CO
- SO2
- O3
- AQI
- AQI_Bucket

## 📊 Project Workflow

1. Dataset Upload and Loading
2. Data Exploration
3. Data Cleaning and Preprocessing
4. Missing Value Handling
5. AQI Distribution Analysis
6. Pollutant Concentration Analysis
7. Correlation Analysis
8. AQI Category Classification
9. Time-Series AQI Analysis
10. City-Wise AQI Comparison
11. Machine Learning Model Development
12. Model Evaluation
13. Feature Importance Analysis
14. AQI Prediction
15. Exporting the Cleaned Dataset

## 📈 AQI Classification

The project uses the following Indian CPCB-style AQI categories:

| AQI Range | Category |
|---|---|
| 0–50 | Good |
| 51–100 | Satisfactory |
| 101–200 | Moderate |
| 201–300 | Poor |
| 301–400 | Very Poor |
| 401–500 | Severe |

## 🤖 Machine Learning Model

**Algorithm:** Random Forest Regression

The model uses pollutant concentrations as input features and predicts the AQI value.

### Model Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help evaluate how accurately the model predicts AQI values.

## 📉 Visualizations

The project generates the following visualizations:

- AQI Distribution Histogram
- Average Pollutant Concentration Bar Chart
- Pollutant Correlation Heatmap
- AQI Category Distribution
- AQI Trends Over Time
- City-Wise AQI Comparison
- Actual vs Predicted AQI
- Pollutant Feature Importance

## 🚀 How to Run the Project

### Option 1: Google Colab (Recommended)

1. Download or clone this repository.
2. Open Google Colab: https://colab.research.google.com/
3. Create a new notebook.
4. Copy the project code into a notebook cell.
5. Run the notebook.
6. Upload the `city_day.csv` dataset when prompted.
7. Execute the analysis and view the generated visualizations.

### Option 2: Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/AQI-Analysis.git
```

Navigate into the project directory:

```bash
cd AQI-Analysis
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Run the Python notebook using Jupyter Notebook or Google Colab.

## 📁 Project Structure

```text
AQI-Analysis/
│
├── AQI_Analysis.ipynb
│
├── dataset/
│   └── city_day.csv
│
├── output/
│   └── AQI_Analysis_Cleaned.csv
│
├── requirements.txt
│
└── README.md
```

*Note: The dataset and output directories are optional. Large datasets can be downloaded separately from Kaggle.*

## 🔍 Expected Outcomes

- Better understanding of air pollution patterns in Indian cities.
- Identification of major pollutants.
- Comparison of air quality across cities.
- Understanding of pollutant relationships.
- AQI prediction using machine learning.
- Insights into historical air quality trends.

## ⚠️ Limitations

- The model's accuracy depends on dataset quality and completeness.
- Historical data may not represent current air quality.
- Random Forest predictions are not equivalent to future AQI forecasting.
- Feature importance indicates predictive contribution, not causal relationships.
- Missing values and unusual measurements can influence results.

## 🔮 Future Enhancements

- Integrate real-time AQI data through an external API.
- Develop an interactive AQI dashboard using Streamlit.
- Implement advanced models such as XGBoost and Gradient Boosting.
- Add future AQI forecasting using time-series models.
- Integrate geographical maps to visualize pollution levels.
- Develop an automated air quality monitoring system.

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/YOUR_USERNAME

## 📜 License

This project is intended for educational and research purposes. Refer to the original dataset source for its licensing and usage conditions.
