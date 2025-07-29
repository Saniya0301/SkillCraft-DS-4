# 🚗 Task-5: Traffic Accident Data Analysis

## 📝 Task Description
Analyze traffic accident data to identify patterns related to **road conditions**, **weather**, and **time of day**. Visualize accident hotspots and contributing factors.

---

## 📊 Overview
Understanding the factors contributing to traffic accidents is crucial for improving road safety and implementing preventive measures. This project explores a dataset of traffic accidents and extracts actionable insights to support safer travel.

---

## 🔍 Features

- **📂 Data Loading**  
  Load traffic accident data from a CSV file into a pandas DataFrame.

- **📈 Exploratory Data Analysis**  
  Understand accident distribution across:
  - States
  - Weather conditions
  - Road conditions
  - Timing of the day (e.g., morning, night, peak hours)

- **📊 Data Visualization**  
  Generate charts and plots to highlight:
  - Accident hotspots (if latitude/longitude is available)
  - Accidents by weather and road surface
  - Time-of-day accident trends
  - Contributing factors to fatality/injury

- **📉 Pattern Recognition**  
  Identify consistent trends and relationships between environmental and temporal factors.

- **⚠️ Total Death Timing Ratio**  
  Calculate and visualize death ratios across time-of-day segments for each state.

---

## 🛠️ Tech Stack

- Python 3+
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 How to Run

1. Clone the repository or download the code files.
2. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the analysis script or Jupyter Notebook to explore the visualizations and insights.

---

## 📁 Project Structure

```
📄 accident_analysis.ipynb        # Main notebook with code and visualizations
📊 accidents.csv                  # Raw dataset used for analysis
```

---

## 📌 Output Highlights

- Count plots by weather and road condition
- Histogram of accident times
- Scatter/heatmap for accident hotspots (if geodata is present)
- State-wise death timing ratios visualized using bar charts

---

## 👩‍💻 Author

**Saniya Chhabra**  
B.Tech AI/DS | GGSIPU  
[LinkedIn](https://www.linkedin.com/in/saniya-chhabra) • [GitHub](https://github.com/saniyachhabra)

---

⭐ *Data saves lives—analyze it well, visualize it better.*
