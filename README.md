# 📈 Exploratory Data Analysis (EDA) Project

## 🎯 Objective
This project is part of the **Thiranex Data Science Internship** (Task 3). The objective is to develop strong analytical thinking and data exploration skills by analyzing a dataset to uncover hidden patterns, correlations, and actionable trends.

## 📊 Dataset Description
The dataset focuses on **Student Performance**. It includes features such as gender alongside academic performance metrics across three subjects: Math, Reading, and Writing. This dataset is perfect for practicing statistical summarization and multi-variate correlation analysis.

## 🛠️ Key Features & Methodology
1. **Statistical Summaries:** Utilized Pandas to generate overarching descriptive statistics (mean, standard deviation, quartiles) for all numerical features.
2. **Missing Value Verification:** Confirmed data integrity by running checks for null/missing values.
3. **Correlation Analysis:**
   - Isolated numerical features and generated a **Correlation Matrix**.
   - Visualized the matrix using a Seaborn Heatmap (`vmin=-1`, `vmax=1`) to easily identify strong positive or negative relationships between subjects (e.g., Reading vs. Writing scores).
4. **Trend Visualization:**
   - Used **Pairplots** categorized by gender to identify multi-dimensional clustering and trends.
   - Plotted individual histogram distributions with KDE overlays for Math, Reading, and Writing scores using subplots to visualize performance skews.

## 📈 Expected Outcome Achieved
Successfully developed analytical thinking and data exploration skills. Insights were structured and presented clearly through visual dashboards/plots, successfully identifying key influencing factors in student performance.

## 💻 Technologies Used
- **Python 3.10**
- **Pandas** (Data aggregation and statistics)
- **Matplotlib & Seaborn** (Advanced statistical plotting and correlation heatmaps)
- **Jupyter Notebook**

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/eda_project.ipynb
   ```
4. Run all cells to view the statistical summaries and correlation graphs.
