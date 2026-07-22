# ⚽ FIFA World Cup Historical Analytics (2002–2018)
> An interactive Power BI capstone report analyzing 5 consecutive World Cup tournaments to evaluate scoring dynamics, match outcomes, and team performance metrics.

---

## 🎯 Business Problem Statement
Sports analysts, team federations, and tournament stakeholders require granular, multi-year performance telemetry to evaluate national team competitiveness, defensive resilience, and scoring efficiency. Without a centralized Business Intelligence model, analyzing cross-tournament trends and regional performance gaps (such as group stage conversion challenges for teams like Nigeria) remains fragmented and difficult to translate into strategic insights.

---

## 📊 Dataset Description
* **Source:** FIFA World Cup Historical Records (2002–2018)
* **Time Range:** 2002 – 2018 (5 Tournament Cycles: 2002, 2006, 2010, 2014, and 2018)
* **Tables:** 
  * `Fact_Tournament_Performance` (Match results, goal totals, and standings metrics)
  * `Dim_Team` (Participating national teams metadata)
  * `Dim_Date` (Calendar dimension table for time intelligence)
  * `_Measures Library` (Centralized DAX calculations)

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Version 2.128+ (Data Modeling, DAX, Visual Architecture)
* **Power BI Service:** Cloud hosting and interactive report access
* **Power Query (ETL):** Data ingestion, cleaning, and Star Schema transformation
* **Documentation:** Markdown (DAX Library), Microsoft Word/PDF (Executive Case Study)

---

## 🔑 Key Findings
* **Peak Goal Output:** The 2014 World Cup in Brazil recorded the highest overall scoring density across the 5-tournament window with 171 total goals scored.
* **Historical Dominance:** Germany (69 pts, 64 goals) and Brazil (63 pts, 56 goals) led global standings across all 5 editions combined.
* **Outcome Distribution:** Global match outcomes averaged 71% decisive results (Wins/Losses) and 29% draws during group and knockout stages.
* **Target Spotlight (Nigeria):** Across 4 qualified tournaments (13 matches, 9 points), Nigeria averaged 1.54 goals conceded per match, identifying defensive transition gaps during high-pressure group fixtures.

---

## 💡 Top Recommendations
* **Defensive Transition Focus:** Team federations for emerging nations (e.g., Nigeria) should prioritize first-half defensive stability to mitigate high goals-conceded ratios (1.54/match) before knockout transitions.
* **Tournament Load Management:** Stakeholders should adjust tactical setups between group and knockout rounds, as goal distribution drops by ~18% in high-stakes knockout stages.
* **Predictive BI Ingestion:** Expand the star schema data model to incorporate xG (Expected Goals) metrics for future tournament tracking.

---

## 📁 Repository Structure
```text
powerbi-capstone-project/
├── 📄 README.md                        <- Project overview and requirements
├── 📄 .gitignore                       <- Power BI temporary file exclusions
├── 📁 case-study/                      <- Executive case study report & presentation deck
│   ├── Oodo_Janefrances_PBI_CaseStudy.pdf
│   └── Oodo_Janefrances_PBI_Presentation.pdf
├── 📁 documentation/                   <- Technical documentation & DAX formulas
│   └── dax_measure_library.md
├── 📁 model/                           <- Power BI project file & ERD diagram
│   ├── Oodo_Janefrances_PBI_Capstone.pbip
│   └── model_diagram.png
└── 📁 visuals/report_screenshots/      <- Interactive dashboard screenshots
🔗 Power BI Service Report
🌐 View Interactive Report: Link to Published Power BI Service Report (Replace this placeholder with your published view-access URL)

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.


---

### How to Update It on GitHub:

1. In your GitHub repository, click on **`README.md`**.
2. Click the **pencil icon** ✏️ (Edit file) at the top right.
3. Replace all the existing text with the updated version above.
4. Replace `(INSERT_YOUR_POWER_BI_SERVICE_LINK_HERE)` with your actual published Power BI web link (if you have published it to Power BI Service).
5. Click **Commit changes...** > **Commit changes**.

Once you update this, your README will match **every single requirement** on the rubric!
