 <div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:003822,70:0e4429,100:39d353&height=140&section=header&text=Ivy%20Wangari%20Kimenju&fontSize=32&fontColor=ffffff&fontAlignY=50&fontAlign=50&desc=Data%20Analyst%20%20%E2%80%A2%20%20Business%20Intelligence%20%20%E2%80%A2%20%20Nairobi%2C%20Kenya&descSize=13&descAlignY=70&descColor=39d353&animation=fadeIn" />
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=500&lines=Public+sector+data+%7C+Spatial+and+statistical+analysis;Python+%7C+SQL+%7C+Excel+%7C+Power+BI;Open+to+Data+Analyst+%26+BI+roles)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ivy-kimenju)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kimenjuivy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/kimenjuivy)

</div>

---

<img align="right" width="310" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>

```python
analyst = {
  "name"     : "Ivy Wangari Kimenju",
  "location" : "Nairobi, Kenya 🇰🇪",
  "focus"    : ["public sector data", "spatial inequality",
                "statistical analysis"],
  "building" : "an honest, defensible analytics portfolio",
  "open_to"  : "Data Analyst & BI roles",
}
```

<br clear="right"/>

---

### Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=python&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### Projects

#### ✈️ [Global Airline Performance Analytics](https://github.com/kimenjuivy/airline-performance)
> A full-pipeline analysis of 7,001,619 US domestic flights (2025, BTS data) — raw CSVs through a MySQL database, statistical testing, and an interactive 6-page Power BI dashboard. Along the way: diagnosed a Windows CRLF encoding bug that silently corrupted a loaded column, caught two stale entries in a third-party reference dataset, and found (and fixed) an unweighted-average statistical error independently in two separate calculations.

| Finding | Value |
|:---|:---|
| Correlation: carrier & late-aircraft delay vs. weather delay | 0.6–0.67 vs. 0.32 |
| Seasonal delay swing, July vs. September | 24.55 min vs. 12.05 min |
| Worst single route (≥100 flights) | CKB→SFB, 93.98 min avg (5.4× dataset average) |
| Third-party reference-data errors found & corrected | 4 (2 missing airports, 2 mislabeled airline codes) |

`MySQL` `Python` `pandas` `dask` `SciPy` `statsmodels` `Power BI` `Excel`

---

#### 🛒 [Olist E-Commerce: Customer Retention & Delivery Analysis](https://github.com/kimenjuivy/Olist-customer-retention-and-delivery-analysis)
> An end-to-end analysis of 96,478 delivered orders from Brazil's Olist marketplace (September 2016 – August 2018), investigating why customers do not return and how delivery performance relates to customer satisfaction. Combines customer segmentation, cohort retention analysis, delivery-performance analysis, statistical testing, and an interactive Tableau dashboard.

| Finding | Value |
|:---|:---|
| Customers who purchased only once | 97.0% (90,557 of 93,358) |
| Month-1 retention (size-weighted) | 0.48% |
| Loyal repeat customers | 0.24% (228 customers) |
| Average spend: loyal vs. one-time customers | R$506.79 vs. approximately R$160 |
| Orders delivered later than Olist's estimate | 8.11% |
| Average review score: on-time vs. late delivery | 4.29 vs. 2.57 |
| Effect size of delivery delay on review scores | Cohen's d = 1.45 |
| Monthly late-delivery rate vs. average review score | r = -0.86 (20 months, 500+ orders) |
| Late-delivery rate: Rio de Janeiro vs. São Paulo | 13.5% vs. 5.9% |

**Analysis Highlights**
- Developed customer-level RFM segments to distinguish recent buyers, lapsed customers, occasional repeat buyers, and loyal customers.
- Conducted cohort-based retention analysis to measure how quickly customers stopped purchasing.
- Used Welch's t-test and effect-size analysis to examine the relationship between delivery delays and customer reviews.
- Identified geographic differences in late-delivery rates, including the gap between Rio de Janeiro and São Paulo.
- Prepared analytical datasets and visualizations for an interactive Tableau Public dashboard.

`Python` `pandas` `NumPy` `SciPy` `Matplotlib` `Jupyter` `Tableau Public`

[View Repository](https://github.com/kimenjuivy/Olist-customer-retention-and-delivery-analysis)

**Dashboard:** Add your Tableau Public URL here.

---

#### 🇰🇪 [Kenya County Development and Opportunity Index (KCDOI)](https://github.com/kimenjuivy/kenya-development-index)
> A county-level socioeconomic development index for all 47 Kenyan counties, built from raw KNBS government publications — census data, poverty reports, financial inclusion surveys, and county GDP figures. Extracted and validated 8 independent data domains from source PDFs, built a composite Development Score two independent ways and cross-validated them, and tested a real ASAL vs non-ASAL development gap.

| Finding | Value |
|:---|:---|
| Development score gap, non-ASAL vs ASAL counties | 0.84 pts (Cohen's d = 1.13, p < 0.001) |
| GDP variance explained by poverty + electricity alone | 67% (Adj. R² = 0.670) |
| Rank agreement between equal-weight and PCA scoring | Spearman r = 0.9993 |
| Domains excluded due to no reliable data source | 2 of 10 (healthcare, urbanization) |

`Python` `pandas` `SciPy` `statsmodels` `scikit-learn` `pdfplumber` `SQLite` `Excel`

---

#### 🏥 [Nairobi Healthcare Access Inequality Analysis](https://github.com/kimenjuivy/nairobi-healthcare-access-analysis)
> Built a Healthcare Access Inequality Index (HAII) for Nairobi's constituencies, combining facility density, KEPH-weighted facility levels, and population pressure, using 2017 KMHFL facility data and 2019 KNBS population estimates.

| Finding | Value |
|:---|:---|
| Level 4+ hospitals concentrated in just 5 constituencies | 75.7% |
| Mathare facility density vs Nairobi average | 0.73 vs 1.96 per 10,000 (≈2.7× below) |
| Kasarani population with no Level 4+ access | 780,656 residents |

`Python` `pandas` `GeoPandas` `Folium` `KMHFL 2017` `KNBS 2019`

---

> 🔄 More projects in progress, built the same way — real data, documented methodology, and honest about what the data can't support.

---

### Currently

```
✅  Power Learn Project Africa — Software Engineering (16 weeks, completed, Certificate of Achievement)
✅  Global Airline Performance Analytics — full SQL/Python/Power BI/Excel pipeline
✅  Olist E-Commerce Customer Retention & Delivery Analysis — Python/statistical analysis/Tableau
🔄  Applying for Data Analyst and BI Analyst roles / internships
```

---

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimenjuivy&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9"/>

![Streak](https://streak-stats.demolab.com?user=kimenjuivy&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39d353&fire=39d353&currStreakLabel=39d353&sideLabels=8b949e&dates=8b949e)

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,30:0e4429,70:003822,100:0d1117&height=100&section=footer"/>
</div> <div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:003822,70:0e4429,100:39d353&height=140&section=header&text=Ivy%20Wangari%20Kimenju&fontSize=32&fontColor=ffffff&fontAlignY=50&fontAlign=50&desc=Data%20Analyst%20%20%E2%80%A2%20%20Business%20Intelligence%20%20%E2%80%A2%20%20Nairobi%2C%20Kenya&descSize=13&descAlignY=70&descColor=39d353&animation=fadeIn" />
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=500&lines=Public+sector+data+%7C+Spatial+and+statistical+analysis;Python+%7C+SQL+%7C+Excel+%7C+Power+BI;Open+to+Data+Analyst+%26+BI+roles)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ivy-kimenju)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kimenjuivy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/kimenjuivy)

</div>

---

<img align="right" width="310" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>

```python
analyst = {
  "name"     : "Ivy Wangari Kimenju",
  "location" : "Nairobi, Kenya 🇰🇪",
  "focus"    : ["public sector data", "spatial inequality",
                "statistical analysis"],
  "building" : "an honest, defensible analytics portfolio",
  "open_to"  : "Data Analyst & BI roles",
}
```

<br clear="right"/>

---

### Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=python&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### Projects

#### ✈️ [Global Airline Performance Analytics](https://github.com/kimenjuivy/airline-performance)
> A full-pipeline analysis of 7,001,619 US domestic flights (2025, BTS data) — raw CSVs through a MySQL database, statistical testing, and an interactive 6-page Power BI dashboard. Along the way: diagnosed a Windows CRLF encoding bug that silently corrupted a loaded column, caught two stale entries in a third-party reference dataset, and found (and fixed) an unweighted-average statistical error independently in two separate calculations.

| Finding | Value |
|:---|:---|
| Correlation: carrier & late-aircraft delay vs. weather delay | 0.6–0.67 vs. 0.32 |
| Seasonal delay swing, July vs. September | 24.55 min vs. 12.05 min |
| Worst single route (≥100 flights) | CKB→SFB, 93.98 min avg (5.4× dataset average) |
| Third-party reference-data errors found & corrected | 4 (2 missing airports, 2 mislabeled airline codes) |

`MySQL` `Python` `pandas` `dask` `SciPy` `statsmodels` `Power BI` `Excel`

---

#### 🛒 [Olist E-Commerce: Customer Retention & Delivery Analysis](https://github.com/kimenjuivy/Olist-customer-retention-and-delivery-analysis)
> An end-to-end analysis of 96,478 delivered orders from Brazil's Olist marketplace (September 2016 – August 2018), investigating why customers do not return and how delivery performance relates to customer satisfaction. Combines customer segmentation, cohort retention analysis, delivery-performance analysis, statistical testing, and an interactive Tableau dashboard.

| Finding | Value |
|:---|:---|
| Customers who purchased only once | 97.0% (90,557 of 93,358) |
| Month-1 retention (size-weighted) | 0.48% |
| Loyal repeat customers | 0.24% (228 customers) |
| Average spend: loyal vs. one-time customers | R$506.79 vs. approximately R$160 |
| Orders delivered later than Olist's estimate | 8.11% |
| Average review score: on-time vs. late delivery | 4.29 vs. 2.57 |
| Effect size of delivery delay on review scores | Cohen's d = 1.45 |
| Monthly late-delivery rate vs. average review score | r = -0.86 (20 months, 500+ orders) |
| Late-delivery rate: Rio de Janeiro vs. São Paulo | 13.5% vs. 5.9% |

**Analysis Highlights**
- Developed customer-level RFM segments to distinguish recent buyers, lapsed customers, occasional repeat buyers, and loyal customers.
- Conducted cohort-based retention analysis to measure how quickly customers stopped purchasing.
- Used Welch's t-test and effect-size analysis to examine the relationship between delivery delays and customer reviews.
- Identified geographic differences in late-delivery rates, including the gap between Rio de Janeiro and São Paulo.
- Prepared analytical datasets and visualizations for an interactive Tableau Public dashboard.

`Python` `pandas` `NumPy` `SciPy` `Matplotlib` `Jupyter` `Tableau Public`

[View Repository](https://github.com/kimenjuivy/Olist-customer-retention-and-delivery-analysis)

**Dashboard:** Add your Tableau Public URL here.

---

#### 🇰🇪 [Kenya County Development and Opportunity Index (KCDOI)](https://github.com/kimenjuivy/kenya-development-index)
> A county-level socioeconomic development index for all 47 Kenyan counties, built from raw KNBS government publications — census data, poverty reports, financial inclusion surveys, and county GDP figures. Extracted and validated 8 independent data domains from source PDFs, built a composite Development Score two independent ways and cross-validated them, and tested a real ASAL vs non-ASAL development gap.

| Finding | Value |
|:---|:---|
| Development score gap, non-ASAL vs ASAL counties | 0.84 pts (Cohen's d = 1.13, p < 0.001) |
| GDP variance explained by poverty + electricity alone | 67% (Adj. R² = 0.670) |
| Rank agreement between equal-weight and PCA scoring | Spearman r = 0.9993 |
| Domains excluded due to no reliable data source | 2 of 10 (healthcare, urbanization) |

`Python` `pandas` `SciPy` `statsmodels` `scikit-learn` `pdfplumber` `SQLite` `Excel`

---

#### 🏥 [Nairobi Healthcare Access Inequality Analysis](https://github.com/kimenjuivy/nairobi-healthcare-access-analysis)
> Built a Healthcare Access Inequality Index (HAII) for Nairobi's constituencies, combining facility density, KEPH-weighted facility levels, and population pressure, using 2017 KMHFL facility data and 2019 KNBS population estimates.

| Finding | Value |
|:---|:---|
| Level 4+ hospitals concentrated in just 5 constituencies | 75.7% |
| Mathare facility density vs Nairobi average | 0.73 vs 1.96 per 10,000 (≈2.7× below) |
| Kasarani population with no Level 4+ access | 780,656 residents |

`Python` `pandas` `GeoPandas` `Folium` `KMHFL 2017` `KNBS 2019`

---

> 🔄 More projects in progress, built the same way — real data, documented methodology, and honest about what the data can't support.

---

### Currently

```
✅  Power Learn Project Africa — Software Engineering (16 weeks, completed, Certificate of Achievement)
✅  Global Airline Performance Analytics — full SQL/Python/Power BI/Excel pipeline
✅  Olist E-Commerce Customer Retention & Delivery Analysis — Python/statistical analysis/Tableau
🔄  Applying for Data Analyst and BI Analyst roles / internships
```

---

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimenjuivy&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9"/>

![Streak](https://streak-stats.demolab.com?user=kimenjuivy&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39d353&fire=39d353&currStreakLabel=39d353&sideLabels=8b949e&dates=8b949e)

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,30:0e4429,70:003822,100:0d1117&height=100&section=footer"/>
</div>
