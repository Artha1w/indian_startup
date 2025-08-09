

# 📊 Startup Funding Analysis GUI

A Python-based **graphical user interface** (GUI) for analyzing, cleaning, and visualizing startup funding datasets.
This tool is built using **Tkinter**, **Pandas**, **Seaborn**, and **Matplotlib** to help users quickly explore and understand funding trends, top sectors, cities, startups, and investors.

---

## 🚀 Features

* **Upload Dataset**: Import CSV data (e.g., Kaggle startup funding dataset).
* **Data Cleaning**:

  * Standardizes column names.
  * Handles missing values.
  * Cleans currency and date formats.
* **Analysis**:

  * Funding trends over time.
  * Top sectors, cities, startups, and investors.
  * Investment type distribution.
* **Visualization**:

  * Line plots for funding trends.
  * Bar plots for sectors, cities, startups, and investors.
  * Count plots for investment types.
* **Recommendations**:

  * Provides data-driven suggestions based on analysis.

---

## 📂 Project Structure

```
main.py        # Main Python script with GUI and functionality
README.md      # Documentation (this file)
```

## 🛠️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/startup-funding-analysis.git
cd startup-funding-analysis
```

### 2️⃣ Install dependencies

```bash
pip install pandas seaborn matplotlib
```

---

## ▶️ Usage

Run the application:

```bash
python main.py
```

### Steps in the GUI:

1. **Upload Kaggle Dataset** → Choose a CSV file.
2. **Show Cleaning Steps** → View issues before cleaning.
3. **Clean Data** → Apply standardization and fill missing values.
4. **Analyze Data** → Display top insights in the text panel.
5. **Visualize Insights** → Generate plots for trends and distributions.
6. **Recommendations** → See suggestions for startup funding strategies.


## 📊 Example Visualizations

* **Funding Trends Over Time**: Line chart of yearly total funding.
* **Top 5 Sectors**: Bar chart of sector counts.
* **Top 5 Cities**: Bar chart of startup locations.
* **Top 5 Investors**: Bar chart of most active investors.
* **Investment Type Distribution**: Count plot of funding types.


## 📌 Requirements
* Python 3.7+
* Pandas
* Seaborn
* Matplotlib
* Tkinter (comes with standard Python installation)
