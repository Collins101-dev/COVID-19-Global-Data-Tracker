# COVID-19 Global Data Tracker

**Track, analyze, and visualize the global progression of the COVID-19 pandemic with real-world data.** 🌍📊

---

### 🚀 Project Overview

This project utilizes the **Our World in Data (OWID)** COVID-19 dataset to provide a comprehensive analysis of the pandemic's spread, its effects on global health, and the vaccination progress across several countries. Specifically, it focuses on **Kenya, India, and the United States**.

The analysis covers:
- **Cases and deaths over time** 📈
- **Vaccination rollouts and percentages** 💉
- **Country-specific comparisons** 🌎

---

### 🔍 Key Features

- **Data Analysis:** Cleaned, processed, and visualized global COVID-19 data.
- **Comparative Insights:** Compare metrics like total cases, deaths, and vaccinations between countries.
- **Trend Visualization:** Track changes over time with line charts and heatmaps.
- **Interactive Maps (Optional):** Visualize global vaccination rates with Plotly choropleths.

---

### 💡 Why This Project?

With the ever-changing nature of the COVID-19 pandemic, it's crucial to have **up-to-date insights** to inform policy decisions and public health strategies. This project aims to provide clear, accessible, and insightful data visualizations that can aid in understanding global pandemic trends.

---

### 📦 Requirements

To run the project, you'll need the following Python packages:

- `pandas` — for data handling
- `matplotlib` & `seaborn` — for static visualizations
- `plotly` — for interactive maps
- `jupyter` — for running the analysis in a Jupyter notebook

---

### ⚙️ Installation

1. **Clone the repository:**
   ```bash
     git clone https://github.com/Collins101-dev/ COVID-19-Global-Data-Tracker.git
     cd COVID-19-Global-Data-Tracker
   ```

2.Create and activate a virtual environment:
  ```bash
    python -m venv env
    source env/bin/activate  # On Windows: .\env\Scripts\activate
  ```

3.Install dependencies:
```bash
    pip install -r requirements.txt
```
4. Download the COVID-19 dataset from [OWID](https://covid.ourworldindata.org/data/owid-covid-data.csv) and place it in the data/ folder. 
   
5. Run the analysis in Jupyter Notebook:
   ```bash
    jupyter notebook notebooks/covid_analysis.ipynb
   ```

## 🖼️ Project Output

The notebook will display the following:

Graphs:

Total COVID-19 cases and deaths over time.

Vaccination progress compared across countries.

Maps:

An optional choropleth map showing vaccination rates globally.

Insights:

Key findings and a summary report of the pandemic trends.

## 📊 Sample Output
Total Cases Over Time: Track how different countries' infection rates evolved.

Vaccination Trends: Visualize the percentage of populations fully vaccinated across nations.

Country Comparisons: View the stark differences in cases and deaths between countries like India, the US, and Kenya.

## 📄 Insights
By the end of the project, you’ll be able to identify:

How vaccination rates correlate with declining death rates.

Which countries experienced the fastest vaccine rollouts.

The overall impact of COVID-19 across various regions.

## 🤖 Future Enhancements
Add regional comparisons (e.g., EU vs. Africa).

Build an interactive dashboard using Streamlit or Dash for real-time data exploration.

Integrate hospitalization and variant-specific data for deeper insights.

## 🌱 Acknowledgments
Data provided by Our World in Data.

Visualizations inspired by the need for accessible, actionable public health insights.

## ✅ Steps for Setup and Running

Step 1: Clone the Repository
Start by cloning the repository and navigating to the project folder:

```bash
git clone https://github.com/Collins101-dev/COVID-19-Global-Data-Tracker.git
cd COVID-19-Global-Data-Tracker
```

Step 2: Set Up a Virtual Environment
Create a virtual environment to manage dependencies:

```bash
python -m venv env
```
Activate the environment:
On Windows:
```bash
    .\env\Scripts\activate
    ```

    On Mac/Linux:
    ```bash
    source env/bin/activate
    ```

Step 3: Install Dependencies
Install the required libraries from requirements.txt:
```bash
pip install -r requirements.txt
```
Step 4: Run the Analysis
Start the Jupyter notebook and open the analysis file:
```bash
jupyter notebook notebooks/covid_analysis.ipynb
```

## 🖼️ Final Thoughts
Once everything is up and running, you’ll have a dynamic tool for analyzing COVID-19 trends across different countries. The analysis will help to visualize both the pandemic's spread and how vaccination efforts have impacted different regions.

Feel free to extend the project by adding more countries, tracking hospitalization rates, or integrating more advanced visualizations! Let me know if you need further tweaks or a custom dashboard.
