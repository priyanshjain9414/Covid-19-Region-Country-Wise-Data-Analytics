#  COVID-19 Data Analytics Project

##  Overview
The **COVID-19 Data Analytics Project** aims to analyze and visualize the global impact of the COVID-19 pandemic through data-driven insights.  
This project involves two main components:
1. **Exploratory Data Analysis (EDA)** — Performed using Python to uncover trends and patterns in the data.
2. **Interactive Dashboard** — Built using Power BI to visualize key findings for better interpretation and decision-making.

---

##  Objective
The primary objective of this project is to **analyze COVID-19 data** to understand:
- The spread of the virus across different regions.
- Trends in confirmed cases, recoveries, and deaths.
- Comparative analysis of countries and continents.
- The effectiveness of measures taken over time.

By leveraging Python for data analysis and Power BI for visualization, this project demonstrates the integration of analytical and business intelligence tools for impactful reporting.

---

## ⚙️ Tools & Technologies Used
###  **Python (for EDA)**
- **Libraries:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- **Tasks Performed:**  
  - Data Cleaning & Preprocessing  
  - Handling missing values  
  - Data transformation and filtering  
  - Exploratory Data Analysis (EDA)  
  - Visualization of trends and correlations  

###  **Power BI (for Dashboard)**
- Interactive Dashboard creation for visual storytelling  
- Country-wise and global trend comparison  
- Visualization of key metrics:
  - Total confirmed, recovered, and death cases  
  - Daily growth rates and moving averages  
  - Recovery and fatality rates over time  

---

##  Data Source
The datasets used for this analysis were obtained from reliable public sources:
- [Our World in Data](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

The dataset includes:
- Date-wise confirmed, recovered, and death cases  
- Country and continent information  
- Testing and vaccination data (where available)

---

##  Exploratory Data Analysis (EDA)
The EDA phase focuses on understanding and cleaning the data for meaningful insights.  
Key steps include:
1. **Data Cleaning** – Removing null values and duplicates.  
2. **Feature Engineering** – Creating new attributes like active cases, mortality rate, recovery rate, etc.  
3. **Trend Analysis** – Observing time-based changes in cases.  
4. **Visualization** – Using Python libraries to display:
   - Country-wise case distribution  
   - Growth trends over time  
   - Comparison of top affected countries  
   - Heatmaps and correlation plots  

Example Plots:
- Line plots showing case progression over time  
- Bar charts for country comparisons  
- Heatmaps to visualize correlations  

---

##  Power BI Dashboard Highlights
The **Power BI Dashboard** presents the analyzed data in an interactive visual form, featuring:
-  **Global Summary:** Total cases, recoveries, and deaths  
-  **Time-Series Visuals:** Daily and cumulative case trends  
-  **Map View:** Geographical distribution of COVID-19 cases  
-  **Country Comparison:** Identify top affected and least affected regions  
-  **Insights Panel:** Key takeaways and data-driven conclusions  

---
## Dashboard Screenshots
**Home(Page 1)**
![Home (Page1)](Dashboard%20Images/Home(page%201).JPG)

**Global View(Page 2)**
![Global View (Page 2)](Dashboard%20Images/Global%20View(Page%202).JPG)

**Region View(Page 3)**
![Region View (Page 3)](Dashboard%20Images/Region%20View(Page%203).JPG)

**Country View(Page 4)**
![Country View (Page 4)](Dashboard%20Images/Country%20View(Page%204).JPG)

##  Project Structure
```
COVID19-Data-Analytics/
├── Country_wise_Covid19_data.csv
├── Covid19_Dashboard.pbix
├── Covid19_eda.ipynb
├── Covid19_Report.pdf
├── Icons/icons.jpg
├── Dashboard Images/
├   ├── Home(Page 1)
├   ├── Global View(Page 2) 
├   ├── Region View(Page 3)
├   ├── Country View(Page 4)
├── README.md
```
---

##  How to Run the EDA Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/COVID19-Data-Analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd COVID19-Data-Analytics
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/covid19_eda.ipynb
   ```
4. Run all cells to perform the analysis and view the visualizations.

---

##  Key Insights
- The spread of COVID-19 varied significantly across continents.  
- Recovery rates improved over time as vaccination rates increased.  
- Countries with early lockdowns and vaccination programs showed better control.  
- Death rates correlated strongly with healthcare infrastructure availability.  

---

##  Future Scope
- Integrate real-time API data for live updates.  
- Build a web-based dashboard using Plotly Dash or Streamlit.  
- Add machine learning models for case prediction and trend forecasting.  
- Incorporate vaccination impact analysis.  

---

## Author
**Priyansh Jain**    
 [GitHub: @priyanshjain9414](https://github.com/priyanshjain9414)  
 [Email: priyanshjain903@gmail.com](mailto:priyanshjain903@gmail.com)


---

##  Conclusion
This project showcases how data analytics and visualization can provide valuable insights into global health crises like COVID-19.  
By combining Python EDA and Power BI Dashboards, we can transform raw data into actionable knowledge and support data-driven decision-making.
