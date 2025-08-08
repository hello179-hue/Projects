# 🧪 Air Quality Data Analysis & Visualization

## 📌 Objective
To analyze historical air pollution data using Python, uncovering trends and relationships between key pollutants and the Air Quality Index (AQI). The aim is to perform exploratory data analysis (EDA) and generate visual insights to support environmental monitoring and policy decisions.

---

## 📁 Dataset Description

- **File Name**: `final_dataset.csv`
- **Location**: `C:\Users\srish\OneDrive\Desktop\Project\Dataset`
- **Key Columns**:
  - Temporal: `Year`, `Month`, `Day`, `Date`
  - Pollutants: `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `Ozone`
  - Target Variable: `AQI`

---

## 🛠 Tools & Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for data visualization

---

## 🔄 Data Preprocessing Steps

1. **Date Handling**:
   - Combined `Year`, `Month`, `Day` into a unified datetime column called `proper_date`.
   - Dropped redundant `Date` column.
   - Sorted data chronologically.

2. **Data Cleaning**:
   - Checked for and removed duplicates.
   - Verified and handled missing values.
   - Evaluated data types and ensured consistency.

---

## 📊 Exploratory Data Analysis (EDA)

### 📌 Correlation Matrix
- Created using Seaborn heatmap to analyze relationships between AQI and pollutants.

### 📌 AQI Histogram
- Histogram plotted to visualize the distribution of AQI values across the dataset.

### 📌 Pollutant Distribution
- Individual histograms for `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, and `Ozone` to understand variability and behavior.

---

## ✅ Conclusion

### 🔍 Key Insights:

- **AQI Distribution**:
  - Skewed distribution observed; may indicate seasonal spikes or pollution episodes.

- **Pollutant Correlation**:
  - Strong correlation found between AQI and specific pollutants, especially particulate matter (PM2.5, PM10).

- **Pollutant Spread**:
  - Some pollutants show wide variance and possible outliers, requiring closer monitoring.

- **Data Quality**:
  - Dataset is well-structured, clean, and suitable for modeling or time-series analysis.

### 💼 Business/Policy Application:

- Identifies the most critical pollutants affecting air quality.
- Supports data-driven policymaking (e.g., seasonal bans on industrial activities).
- Can assist in public health advisories and environmental awareness campaigns.

---

## 🗂 Future Work (Optional Suggestions)

- Time series forecasting using ARIMA or LSTM.
- Geographical analysis if spatial data is available.
- Integration with meteorological parameters like temperature and humidity.

