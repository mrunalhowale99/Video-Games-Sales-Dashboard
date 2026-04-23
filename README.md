
# 🎮 Level Up Analytics: Global Video Game Sales Insights Dashboard

A dynamic, interactive data visualization tool built to explore video game sales data worldwide focusing on platform and genre comparisons, regional performance, publisher dominance, and sales trends across decades.

---

## 📋 Short Description / Purpose

The **Level Up Analytics Dashboard** is a visually engaging and analytical Power BI report designed to help users explore and compare thousands of video game titles across multiple platforms, genres, and global regions. The dashboard focuses on surfacing key sales trends including year-over-year performance, regional dominance, and platform-level breakdowns to reveal how the gaming industry has evolved over time.

This tool is intended for use by gaming industry analysts, market researchers, publishers, game developers, and data enthusiasts who seek to understand patterns and characteristics of video game sales globally.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** — Main data visualization platform used for report creation and publishing.
- 📂 **Power Query** — Data transformation and cleaning layer used to reshape, filter, and prepare the raw CSV data for modeling.
- 🧠 **DAX (Data Analysis Expressions)** — Used for calculated measures, KPI cards, dynamic titles, and conditional logic across visuals.
- 📝 **Data Modeling** — Relationships and calculated columns established within the data model to enable cross-filtering and aggregation across dimensions (platform, genre, publisher, year, region).
- 📁 **File Format** — `.pbit` (Power BI Template) for portability and `.png` for dashboard previews.

---

## 📂 Data Source

**Source:** [Kaggle — Video Game Sales Dataset (vgsales)](https://www.kaggle.com/datasets/gregorut/videogamesales)

The dataset contains sales figures for over **16,500 video games** across major global markets, scraped from VGChartz. It includes:

| Column | Description |
|---|---|
| `Name` | Title of the video game |
| `Platform` | Console or platform (e.g., PS2, Wii, Xbox 360, DS) |
| `Year` | Year of release |
| `Genre` | Game genre (e.g., Action, Sports, RPG, Platform) |
| `Publisher` | Publisher of the game |
| `NA_Sales` | Sales in North America (millions of units) |
| `EU_Sales` | Sales in Europe (millions of units) |
| `JP_Sales` | Sales in Japan (millions of units) |
| `Other_Sales` | Sales in rest of the world (millions of units) |
| `Global_Sales` | Total worldwide sales (millions of units) |

---

## ✨ Features / Highlights

### 🔴 Business Problem

The video game industry is one of the largest entertainment sectors in the world, yet understanding historical sales performance across platforms, regions, and genres remains fragmented. Publishers, analysts, and developers often lack an intuitive way to compare performance across markets.

Key questions such as:
- Which platforms generated the most global sales?
- How have sales trended over the past three decades?
- Which regions drive the most revenue and for which genres?
- Who are the most dominant publishers across different markets?

…are difficult to answer quickly with raw spreadsheet data.

---

### 🎯 Goal of the Dashboard

To deliver an interactive visual tool that:

- Enables users to explore video game sales trends across time, region, platform, and genre.
- Supports decisions such as market entry strategy, platform prioritization, or publishing investment.
- Uncovers regional preferences and decade-level shifts in gaming consumption.

---

### 🖥️ Walkthrough of Key Visuals

**Key KPIs (Top Section)**
- Total games tracked
- Total global sales (in millions of units)
- Top-selling platform
- Top-selling genre
- Top publisher by global revenue

**Regional Sales Breakdown (Donut / Map Chart)**
Visualizes the split of total sales across North America, Europe, Japan, and the rest of the world, making it easy to identify which regions dominate overall consumption.

**Sales Trend Over the Years (Line Chart)**
A time-series line chart showing global and regional sales from the 1980s through the mid-2010s. Highlights the industry's growth peaks, platform generation cycles, and eventual sales decline as digital distribution replaced physical media.

**Top Platforms by Sales (Bar Chart)**
Ranks gaming platforms (PS2, DS, Wii, Xbox 360, PS3, etc.) by total global sales, helping identify the hardware generation leaders.

**Sales by Genre (Horizontal Bar Chart)**
Compares genres Action, Sports, Shooter, RPG, Platform, and more, by total global revenue, segmented by region to reveal cultural preferences (e.g., RPGs in Japan vs. Sports titles in North America).

**Top Publishers (Ranked Table / Bar Chart)**
Identifies the highest-grossing publishers (Nintendo, Electronic Arts, Activision, etc.) by total units sold globally.

---

### 💡 Business Impact & Insights

- **Market Strategy:** Publishers can identify which platforms and genres yield the highest returns in specific regions, informing localization and marketing decisions.
- **Platform Investment:** Hardware manufacturers can benchmark their platform's commercial performance against competitors across different eras.
- **Historical Benchmarking:** Developers can contextualize their game's sales performance against genre averages and industry trends.
- **Regional Planning:** Studios targeting global launches can use regional breakdowns to understand where their genre resonates most.
- **Trend Forecasting:** The year-over-year sales trend provides a baseline for identifying the decline of physical game sales and the industry's structural shift toward digital.

---

## 📸 Dashboard Preview

---
<img width="571" height="395" alt="Video Games sales dashboard screenshot" src="https://github.com/user-attachments/assets/bfcb63f6-211d-4f22-9560-f0f2824f7865" />


## 👤 Author

**Mrunal Howale**
[GitHub](https://github.com/mrunal03howale) · [Email](mailto:mrunal03howale@gmail.com)

---

*Built with ❤️ using Power BI*
