# 🌍 COVID-19 Global Impact Analysis

This project explores the global impact of the COVID-19 pandemic using interactive visualizations and data analysis. It draws from the rich dataset provided by **Our World in Data**, covering confirmed cases, deaths, and more across countries and over time.

We dig deep into trends, compare mortality rates between regions, and create animated **choropleth maps** to bring the data to life.

---

## 📂 Dataset

- **Source**: [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/coronavirus)
- **Records**: ~460,000+
- **Features**: 61 variables including cases, deaths, testing, vaccination, hospital admissions, and economic indicators

---

## 🎯 Project Goals

- Analyze confirmed cases and total deaths by country
- Identify countries with highest mortality rates
- Explore the relationship between socio-economic indicators and pandemic outcomes
- Create interactive choropleth maps of COVID-19 evolution

---

## 📊 Main Insights

### 🔹 Total Cases (Top 5 countries)
1. United States
2. China
3. India
4. France
5. Germany

### 🔹 Total Deaths (Top 5 countries)
1. United States  
2. Brazil  
3. India  
4. Russia  
5. Mexico  

### 🔹 Highest Mortality Rates (Deaths / Cases)
- Yemen – 18.07%  
- Sudan – 7.88%  
- Syria – 5.51%  
- Somalia – 4.97%  
- Peru – 4.88%

These rates often reflect deeper issues like lack of healthcare infrastructure or underreporting.

---

## 🗺️ Interactive Visualizations

Using **Plotly Express**, we created two choropleth maps:
1. **Total Deaths Over Time by Country**
2. **Total Cases Over Time by Country**

These maps animate the progression of the pandemic worldwide, allowing users to visually track which regions were most affected and when.

---

## 🧹 Data Cleaning

- Removed non-country entries (e.g., continents, regions, Olympic games)
- Handled missing values, with emphasis on variables like `life_expectancy`, `hospital_beds`, and `testing`
- Converted `date` to datetime format and extracted the year for easier time-based analysis

---

## 📌 Tools & Libraries

- Python (Pandas, NumPy)
- Plotly Express (for choropleth maps)
- Jupyter / Google Colab

---

## ✍️ Author

Project by Augusto de Jesus  
Built as part of a personal learning journey in data visualization and global health analytics.

---

## 📎 License

This project is for educational use only. Data courtesy of **Our World in Data**.
