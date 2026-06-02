<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:003822,70:0e4429,100:39d353&height=160&section=header&text=Ivy%20Wangari%20Kimenju&fontSize=36&fontColor=ffffff&fontAlignY=55&fontAlign=50&desc=Data%20Analyst%20%20%E2%80%A2%20%20Business%20Intelligence%20%20%E2%80%A2%20%20Nairobi%2C%20Kenya&descSize=14&descAlignY=75&descColor=39d353&animation=fadeIn" />
</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=560&lines=Turning+raw+data+into+policy-relevant+findings;Spatial+analysis+%7C+Inequality+measurement;Python+%7C+SQL+%7C+GeoPandas+%7C+Tableau;Open+to+Data+Analyst+%26+BI+roles)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ivy-kimenju)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kimenjuivy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/kimenjuivy)
[![Phone](https://img.shields.io/badge/+254_743_834_201-25D366?style=flat-square&logo=whatsapp&logoColor=white)](tel:+254743834201)

</div>

---

<img align="right" width="320" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>

### `whoami`

```python
analyst = {
  "name"     : "Ivy Wangari Kimenju",
  "location" : "Nairobi, Kenya 🇰🇪",
  "focus"    : ["spatial inequality", "public sector data",
                "reproducible research"],
  "building" : "original portfolio from Kenyan public datasets",
  "open_to"  : "Data Analyst & BI roles",
  "ask_me"   : "Python, SQL, or maps"
}
```

<br clear="right"/>

---

### `$ ls ./tech-stack`

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Analysis & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Spatial**

![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=python&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=python&logoColor=white)

**Visualisation & BI**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

**Databases & Tooling**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### `$ cat ./projects/featured.md`

---

#### 🏥 [Nairobi Healthcare Access Inequality Analysis](https://github.com/kimenjuivy/nairobi-healthcare-access-analysis)

**What it does**
Builds a Healthcare Access Inequality Index (HAII) for all 17 Nairobi constituencies using 2017 KMHFL facility data and 2019 KNBS population estimates. The index combines facility density, KEPH-weighted facility levels, and population pressure — normalised to a 0–100 scale where higher = worse access.

**Methodology**
- Facility density per 10,000 people per constituency
- Weighted scoring by KEPH facility level (Level 2 → Level 6)
- Population pressure adjustment for high-density areas
- Confidence tiering for constituencies with missing or reconstructed census data
- Interactive choropleth maps built with GeoPandas + Folium

**Key findings**

```
┌─────────────────────────────────────────────────────────────────┐
│  11 of 17 constituencies  →  below 2 facilities per 10,000     │
│  75.7% of Level 4+ hospitals  →  in just 5 constituencies      │
│  Kasarani (780,656 residents)  →  zero Level 4+ hospital access │
│  Mathare facility density  →  2.7× below the Nairobi average   │
│  71.2% of Nairobi's population  →  living in underserved areas  │
└─────────────────────────────────────────────────────────────────┘
```

**Policy recommendations**
1. Build 2 new Level 3 health centres in Mathare as immediate intervention
2. Develop a shared Level 4 facility for the Embakasi West/South/North cluster
3. Moratorium on new hospitals in well-served constituencies until each constituency has at least one Level 3 facility
4. KNBS to publish a clean constituency-level population table from the 2019 census

**Data sources**

![KMHFL](https://img.shields.io/badge/KMHFL-2017-555?style=flat-square)
![KNBS](https://img.shields.io/badge/KNBS_Census-2019-555?style=flat-square)
![HDX](https://img.shields.io/badge/HDX-GeoJSON-555?style=flat-square)

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=python&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

> 🔄 *More projects in progress — each built from real Kenyan public datasets with documented methodology and policy-facing output.*

---

### `$ cat ./certifications`

```
✅  Google Data Analytics Professional Certificate      [completed]
✅  Advanced SQL for Data Analytics                     [completed]
✅  Python for Data Science Specialisation              [completed]
🔄  Microsoft Power BI Data Analyst Associate           [in progress]
🔄  Tableau Desktop Specialist                          [in progress]
🔄  ALX Data Analytics Programme                        [in progress]
```

---

### `$ ./github-stats`

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=kimenjuivy&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&rank_icon=github"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimenjuivy&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9"/>

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=kimenjuivy&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39d353&fire=39d353&currStreakLabel=39d353&sideLabels=8b949e&dates=8b949e)

</div>

---

<div align="center">
<sub><i>"The data already knows the answer. The analyst's job is to ask the right question."</i></sub>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,30:0e4429,70:003822,100:0d1117&height=100&section=footer"/>
</div>
