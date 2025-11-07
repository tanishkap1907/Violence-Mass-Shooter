# 🔍 The Violence Project: Mass Shooting Data Analysis (1966–2019)

## 📘 Overview

This project investigates **socio-demographic, psychological, and situational factors** associated with mass shootings in the United States using *The Violence Project* database (1966–2019).
Our objective is to uncover patterns and correlations that could help inform **preventive strategies**, **policy formulation**, and **community awareness** through data-driven insights.

This project was developed as part of the **CSE 501 Course Project** at **Arizona State University**.

---

## 🧩 Team Members

* **Vedant Jayant Padole** ([vpadole@asu.edu](mailto:vpadole@asu.edu))
* **Tanishka Padalkar** ([tpadalka@asu.edu](mailto:tpadalka@asu.edu))

---

## 📊 Dataset Description

**Source:** [The Violence Project: Database of Mass Shootings in the United States, 1966–2019](https://www.theviolenceproject.org)
**Creators:** Dr. Jillian K. Peterson & Dr. James A. Densley
**Funding:** U.S. Department of Justice, National Institute of Justice

### Key Variable Categories

* **Incident Information:** Date, location, setting type, urbanicity
* **Victim Details:** Fatalities, injuries, victim–shooter relationship
* **Offender Demographics:** Age, gender, race, education, employment, military status
* **Psychological/Social Background:** Mental health, trauma, family history, suicidal tendencies
* **Motivations:** Grievances (workplace, hate crime, psychosis, fame-seeking)
* **Weapons & Acquisition:** Firearm types, legality, purchase method
* **Community Factors:** Population size, education levels, unemployment rate, local resources
* **Resolution:** Shooter outcome (suicide, arrest, death)

---

## 🧠 Project Objectives

1. **Analyze firearm usage** patterns (types, calibers, modifications).
2. **Identify demographic disparities** among victims and offenders.
3. **Investigate community-level correlations** with education, population, and homicide rates.
4. **Study temporal trends** (1966–2022) in incidents and fatalities.
5. **Formulate and test hypotheses** to validate statistically significant relationships.

---

## 📈 Initial Findings

* **Handguns and semiautomatic pistols** dominate weapon types.
* Around **14–18 %** of recorded weapons had extended magazines or modifications.
* **Temporal analysis** shows rising frequency and lethality of incidents since the 1980s.
* **Victim demographics** reveal variance by gender and race.
* **Community education levels** inversely correlate with homicide rates.

---

## 🧩 Hypotheses (H1 – H10)

| ID         | Focus Area          | Summary                                                                                            |
| ---------- | ------------------- | -------------------------------------------------------------------------------------------------- |
| **H1–H2**  | Weapons             | Modified or extended-magazine firearms have increased over time and dominate incidents.            |
| **H3–H6**  | Victim Demographics | Mean victim age differs significantly by gender, relationship, race, and decade.                   |
| **H7–H8**  | Community Factors   | Lower education quartiles correspond to higher homicide rates and more workplace/retail incidents. |
| **H9–H10** | Temporal Trends     | Both incident count and fatality rate have increased significantly since 1966.                     |

---

## ⚙️ Methodology (Planned)

1. **Data Pre-processing:** Handle nulls, normalize variables, encode categories.
2. **Exploratory Data Analysis:** Visualization via `matplotlib`, `seaborn`, `plotly`.
3. **Statistical Testing:**

   * t-tests and ANOVA for mean-difference hypotheses.
   * Correlation and regression for community factors.
4. **Visualization Dashboard (optional):**

   * Built using `Flask + Plotly Dash` or `Streamlit` for interactive exploration.
5. **Documentation:** Final report & presentation summarizing methods and findings.

---

## 💻 Tech Stack

* **Languages:** Python 3.x
* **Libraries:** pandas, numpy, seaborn, matplotlib, plotly, scipy, statsmodels
* **Tools:** Jupyter Notebook / VS Code, Git & GitHub
* **Version Control:** Git (main branch for final report)

---

## 🚀 Future Work

* Extend the model for **predictive risk mapping** based on community features.
* Integrate **interactive dashboards** for public or academic visualization.
* Explore **machine-learning models** for cluster-based shooter profiling.

---

## 📄 References

1. J. K. Peterson & J. A. Densley, *The Violence Project: Database of Mass Shootings in the United States, 1966–2019*, National Institute of Justice, 2022.
2. Dataset documentation and course materials provided by the instructor.

---

## 🏁 Deliverables

* **Comprehensive Report:** Detailed preprocessing, methodology, and statistical results.
* **Presentation Slides:** Concise summary of insights and visuals.
* **(Optional)** Web Dashboard / Prototype Model for data interaction.

---

> *This README accompanies the “Project Proposal and Overview Report” for CSE 501 and serves as documentation for dataset understanding, research hypotheses, and implementation roadmap.*
