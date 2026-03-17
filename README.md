# Running Performance Analysis

This project analyzes sports activity data to better understand training habits, performance trends, and workout patterns over time.

The goal of this project is to demonstrate practical **data analysis skills** through a complete workflow including:

- data cleaning
- feature engineering
- exploratory data analysis
- data visualization

---

# Project Objectives

The objectives of this project are to:

- Clean and structure raw activity data
- Build relevant training metrics and KPIs
- Analyze training volume and performance trends
- Identify training habits and seasonality
- Create clear visualizations to highlight insights

---

# Dataset

The dataset contains sports activity records exported from a training platform.

It includes information such as:

- activity date
- activity type
- distance
- moving time
- average speed
- elevation gain
- relative effort

The original dataset contained more than 80 columns and required significant preprocessing before analysis.

The preprocessing steps included:

- column selection
- renaming variables
- date parsing
- type conversion
- feature engineering

---

# Tech Stack

The project was built using:

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Workflow

The project follows a standard data analysis pipeline:

1. Raw data ingestion
2. Data cleaning and preprocessing
3. Feature engineering
4. Exploratory data analysis
5. Data visualization

---

# Feature Engineering

The following features were created during preprocessing:

- `year`
- `month`
- `week`
- `day_of_week`
- `pace_min_km`
- `training_load`
- `rolling_speed`

These variables enable time-based analysis and performance trend evaluation.

---

# Key Analyses

The project includes the following analyses:

### Training Volume
- Weekly training volume
- Monthly training volume

### Performance Analysis
- Average speed evolution over time
- Distance vs average speed relationship
- Rolling performance trend

### Terrain Impact
- Elevation gain vs speed

### Training Load
- Weekly training load
- Training load vs rolling average

### Training Habits
- Weekly training heatmap
- Monthly training activity patterns

---

# Key Insights

Some insights obtained from the analysis include:

- Training volume shows strong variability across weeks with identifiable peaks of higher workload.
- Training activity tends to concentrate on specific days of the week.
- Monthly training volume reveals seasonal patterns.

---

# Sample Visualizations

### Weekly Training Volume

(visuals/weekly_training_volume.png)

### Average speed over Tome

(visuals/vaverage_speed_over_time.png)

### Training activity

(visuals/training_activity_heatmap.png)

### Training load vs Rolling Average

(visuals/training_load_vs_rolling_avg.png)


---

# Repository Structure

running-performance-analysis/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ └── 02_exploratory_analysis.ipynb
│
├── visuals/
│
├── src/
│
├── requirements.txt
└── README.md

---

# Future Improvements

Potential improvements for the project include:

- Activity type filtering (run / ride / walk)
- Weather impact analysis
- Training block comparison
- Interactive dashboard (Power BI / Tableau / Streamlit)

---

# Author

Nathan Perney
