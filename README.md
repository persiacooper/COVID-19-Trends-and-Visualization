# COVID-19 Data Trends and Visualization
Exploratory data analysis of global COVID-19 confirmed, death, and recovery trends using Python (Pandas, Matplotlib). Includes time-series reshaping, country-specific plots, and reproducible Jupyter Notebook.
# COVID-19 Global Data Analysis

**Author:** Persia Cooper 
**Date:** August 10, 2025  

This project analyzes global COVID-19 data from the Johns Hopkins University CSSE dataset.  
It reshapes the data from wide to long format, merges confirmed, deaths, and recovered cases,  
and visualizes trends for selected countries.

---

## 📂 Project Structure

```
project-folder/
│
├── data/
│   ├── covid19_confirmed_global.csv
│   ├── covid19_deaths_global_data.csv
│   └── covid19_recovered_global.csv
│
├── outputs/
│   └── US_trends.png
│
├── covid_analysis_cleaned.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

- **Source:** [Johns Hopkins University CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)  
- **Files used:**
  - covid19_confirmed_global.csv
  - covid19_deaths_global_data.csv
  - covid19_recovered_global.csv

> ⚠️ Data is updated daily by JHU CSSE. The analysis results depend on the date you download the data.

---

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/covid19-analysis.git
cd covid19-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Place the dataset CSV files in the `data/` folder.

---

## 🚀 Usage

1. Open the notebook in Jupyter or Google Colab:
   - **Jupyter:**  
     ```bash
     jupyter notebook covid_analysis_cleaned.ipynb
     ```
   - **Google Colab:** Upload the notebook and the `data/` folder.

2. Run all cells to reproduce the analysis.

3. To plot a different country, change:
```python
plot_country_trends("US")
```
to your desired country name.

---

## 📈 Example Output

![Example Output](outputs/US_trends.png)

---

## 📌 Next Steps

- Automate plots for multiple countries.
- Normalize data by population size.
- Add interactive dashboards using Plotly.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
