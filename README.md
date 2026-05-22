# New-Dreamworks-Films-Analysis
Films Performance Evaluation - Power Bi dashboards

<img width="1284" height="718" alt="Screenshot 2026-05-11 222156" src="https://github.com/user-attachments/assets/aee263ab-306f-418a-ba58-3a454a0c8259" />


## Overview 📋

This project presents an interactive business intelligence dashboard analyzing the **box office performance** of DreamWorks Animation films. The dashboard spans two pages — a **Box Office Performance** view and a **Critical Score & Relationship Analysis** view — giving a full picture of how DreamWorks films performed commercially and critically.

---

## Dashboard Views 🖥️

### Page 1: Box Office Performance

Highlights the top-performing DreamWorks films by revenue across North America and worldwide markets.

**KPI Cards:**
- **Highest Rotten Tomatoes Score:** How to Train Your Dragon
- **Highest Metacritic Score:** Chicken Run

**Visuals Included:**
- Top 5 Films by North American Performance (clustered bar + line chart — Gross vs. Opening Weekend)
- Top 10 Films by Worldwide Gross (treemap)
- Top 5 Films by Overseas Gross (horizontal bar chart)
- Top 5 Films by Worldwide Gross (horizontal bar chart)
- Top 5 Films by Budget (bar chart)

**Top Performers:**
| Metric | Film | Value |
|---|---|---|
| North America Gross | Shrek 2 | $441M |
| Overseas Gross | Madagascar 3: Europe's Most Wanted | $531M |
| Worldwide Gross | Shrek 2 | $929M |
| Highest Budget | Monsters vs. Aliens | $175M |

---

### Page 2: Critical Score & Relationship Analysis 🔗

Explores the relationship between critical scores (Metacritic, Rotten Tomatoes) and box office revenue.

**KPI Cards:**
- **Highest North America Gross:** Shrek 2
- **Highest North America Opening:** Shrek the Third
- **Highest Overseas Gross:** Madagascar 3: Europe's Most Wanted
- **Highest Worldwide Gross:** Shrek 2

**Visuals Included:**
- Metacritic vs. Worldwide Gross (scatter plot)
- Metacritic vs. Overseas Gross (scatter plot)
- North America Opening vs. North America Gross (scatter plot)
- Metacritic vs. North America Gross (scatter plot)

---

## Filters & Interactivity 🎛️

**Page 1:**
- **Name Selection** — filter by individual film title
- **Budget Adjustment** — range slider ($30M–$175M)

**Page 2:**
- **Name Selection** — filter by individual film title
- **Rotten Tomatoes Score** — range slider (0.36–0.99)
- **Metacritic Score** — range slider (39–88)

---

## Tools Used 🛠️

- **Power BI** — dashboard design and interactive visualizations
- **DreamWorks Animation Film Dataset** — box office figures, budgets, and critical scores

---

## Key Insights 🔍

- **Shrek 2** is the top-grossing DreamWorks film across all revenue metrics, reaching $929M worldwide
- **Madagascar 3: Europe's Most Wanted** leads overseas gross at $531M, showing strong international appeal
- There is a **weak positive correlation** between Metacritic score and worldwide gross — critical acclaim alone does not predict box office success
- **North America Opening Weekend** has a strong positive correlation with overall North America Gross, making opening weekend a reliable early performance indicator
- The **Shrek franchise** dominates the top 5 lists across North American and worldwide gross categories

---

## Author ✍️

**Steven Nguyen**
