# Google Search Trends Analysis 🔍📈

A Python-based analysis of Google Search interest data using the **Google Trends API (pytrends)**, exploring keyword popularity across regions and over time.

## 🎯 Objective
Analyze search interest trends for key technology-related keywords to understand geographic popularity and interest patterns over time — useful for market research, content strategy, and trend spotting.

## 🛠️ Tools & Libraries Used
- Python
- **pytrends** (Google Trends API wrapper)
- Pandas — data handling
- Matplotlib & Seaborn — static visualizations
- Plotly Express — interactive choropleth map

## 🔍 Analysis Performed
- **Regional interest analysis**: Pulled Google Trends data for the keyword *"cloud computing"* and identified the top 15 countries by search interest
- **Choropleth world map**: Built an interactive country-wise heatmap of search interest using Plotly
- **Time-series trend**: Plotted search interest over the last 12 months to spot growth/decline patterns
- **Multi-keyword comparison**: Compared search interest trends across 4 tech keywords —
  `cloud computing`, `data science`, `machine learning`, `software developer`

## 📊 Key Visuals
- Bar chart — Top countries searching "cloud computing"
- Interactive choropleth map — global search interest distribution
- Line chart — search interest trend over time (12 months)
- Multi-line comparison chart — keyword popularity trends side-by-side

## 📁 Files
- `Google Search Analysis.ipynb` — Full Jupyter notebook with code, charts, and outputs
- `data-export (1).csv` — Exported search interest data
- `Google search analysis project Youtube.pdf` — Project walkthrough / reference document


**Author:** Manoj Sharma (Pandat)
