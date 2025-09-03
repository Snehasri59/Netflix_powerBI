# 🎬 Netflix Insights Dashboard — Power BI

**Turn raw titles into popcorn-worthy insights.** 🍿📊

<img width="1370" height="772" alt="image" src="https://github.com/user-attachments/assets/a3dcad4d-adb3-4ed4-af70-619bb7d3f318" />


> A sleek, dark-themed Power BI dashboard that explores Netflix titles by type, genre, country, directors, and release timeline. Perfect for portfolio/showcase and data-storytelling.

## ✨ What’s inside

* **KPI cards**: Total **Titles**, **Directors**, **Genres**, **Movies**, **TV Shows**
* **Donut**: **Movies vs TV Shows** split with share %
* **World map**: **Titles by Countries** 🌍
* **Timeline**: **Titles Over Years** (spot the streaming boom!)
* **Bars**: **Top 10 Genres** and **Top 10 Directors**
* Thoughtful theming: neon reds, soft shadows, rounded containers, and readable contrast.

---

## 🧠 Insights at a glance

* Movies form the larger share of the catalog, but TV shows have surged in recent years.
* A few genres dominate globally (International Movies, Dramas, Comedies).
* Production is highly clustered across specific regions and countries.
* Long-tail of directors with a few standouts leading the counts.

---

## 🗂️ Data & Model

* **Source**: Public Netflix titles dataset (e.g., Kaggle).
* **Core fields**: `title`, `type`, `country`, `release_year`, `listed_in (genre)`, `director`.
* **Model**: A tidy single-table star-lite setup with calculated measures to keep visuals fast.

---

## 🎛️ How to use the report

* **Hover** for contextual tooltips on each visual.
* **Click** any bar/point to cross-filter the rest.
* **Ctrl/Cmd-click** to multi-select.
* Use the **map** to focus on specific regions and see how genres shift.
* The **timeline** helps spot catalog growth bursts and content cycles.

---

## 🎨 Theming & UX

* Dark background with subtle glassmorphism panels.
* Accent red (#E50914 / #B20710) for Netflix vibes ❤️‍🔥
* Rounded corners and soft shadows to reduce visual fatigue.
* Clear typography and axis titles for portfolio reviewers.

---

## 🧩 Project structure

```
.
├─ assets/                      # screenshots & visuals for README
├─ data/                        # (optional) csv or parquet dataset
├─ measures/                    # (optional) .dax snippets
├─ Netflix_Dashboard.pbix       # the Power BI file
└─ README.md
```

---

## 🛠️ Built with

* **Power BI Desktop**
* **Power Query** for cleaning
* **DAX** for measures

---

## 📜 Disclaimer

This project is for educational/portfolio purposes. All trademarks and brand assets belong to their respective owners. Verify the dataset license before redistribution.

---

## 🙋‍♀️ About

If you like this dashboard, star ⭐ the repo and connect with me.
Happy analyzing — and enjoy the show! 🍿🎥
