# :earth_americas: GDP dashboard template

A simple Streamlit app showing the GDP of different countries in the world.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)


Markdown
# 🌎 GDP Dashboard Template

An interactive [Streamlit](https://github.com/dyyland23-glitch/gdp-dashboard/blob/main/streamlit_app.py) web application designed to visualize and analyze the Gross Domestic Product (GDP) of different countries around the world.

---

## 📂 Repository Structure & File Breakdown

* **[`streamlit_app.py`](https://github.com/dyyland23-glitch/gdp-dashboard/blob/main/streamlit_app.py)**: 
  * *What it is*: The core Python entry point containing the Streamlit user interface, reactive layout controls, and charting logic.
  * *What it does*: Renders country selection filters, economic indicators, and dynamic data visualizations directly in your browser.
* **[`data/`](https://github.com/dyyland23-glitch/gdp-dashboard/tree/main/data)**: 
  * *What it is*: Directory storing raw and processed datasets (such as global economic metrics and country codes).
* **[`.devcontainer/`](https://github.com/dyyland23-glitch/gdp-dashboard/tree/main/.devcontainer)**: Configuration files for containerized development environments in Visual Studio Code.
* **[`.github/`](https://github.com/dyyland23-glitch/gdp-dashboard/tree/main/.github)**: Automated workflows and actions for continuous integration.
* **[`requirements.txt`](https://github.com/dyyland23-glitch/gdp-dashboard/blob/main/requirements.txt)**: Pins essential dependencies (`streamlit`, `pandas`) for deterministic environments.

---

## 🛠️ Tech Stack & Key Libraries & Functions

* **Language**: Python 3.10+
* **Data Manipulation & Analysis**: `pandas`, `numpy`
  * **Key Functions**: `pd.read_csv()`, `df.groupby()`, `df.pivot()`
* **Interactive Frontend & Visualization**: [Streamlit](https://github.com/dyyland23-glitch/gdp-dashboard/blob/main/streamlit_app.py)
  * **Key Functions**: `st.title()`, `st.selectbox()`, `st.dataframe()`, `st.line_chart()`

---

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
