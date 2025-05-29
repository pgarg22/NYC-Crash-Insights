
# NYC Road Crash Analysis & Visualization (2018–2021)

This project analyzes over 1.88 million motor vehicle collisions reported in New York City from 2018 to 2021. It aims to uncover spatiotemporal accident patterns, understand contributing factors, and provide actionable insights to improve urban road safety. The work aligns with the UN Sustainable Development Goal 3.6: reducing road injuries and fatalities.

## 🚀 Project Highlights

- 🔍 Cleaned and analyzed NYC OpenData crash dataset (~384MB, 29 columns).
- 📊 Temporal analysis: identified high-risk hours, weekdays, and seasonal trends.
- 🌎 Geospatial analysis: borough-wise accident hotspots and heatmaps.
- 📈 Visual storytelling: interactive charts via Plotly, Bokeh; dynamic map via Folium.
- 📦 Feature engineering: custom features like `vehicle_count`, `combined_factors`, and time-based breakdowns.
- 🧠 Data science-ready: prepared features for predictive modeling of accident frequency and severity.
- 🎯 COVID-19 impact: observed dramatic reduction in accident frequency in 2020.

---

## 📁 Folder Structure

```
.
├── basic_stats.html                  # Pandas profiling report (static)
├── deepnote_exports/                # Output files or charts exported from Deepnote
├── genres.png                       # Image used in the project
├── heatmap.html                     # Folium heatmap of accident locations
├── history_weather_data.csv         # Weather data for potential correlation
├── init.ipynb                       # Initial setup/experiment notebook
├── Motor_Vehicle_Collisions_-_Crashes.csv  # Main dataset
├── notebook.html                    # Rendered notebook (HTML)
├── notebook.ipynb                   # Main analysis notebook
├── Projected_Population_2010-2040_–_Summary.csv  # Demographic data (optional use)
├── requirements.txt                 # Python dependencies
└── SD_website-main/                 # Website files (if deploying as a project showcase)
```

---

## 📊 Dataset

- **Source**: [NYC Open Data – Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Size**: ~1.88 million records, 29 features
- **Time Range**: Filtered from 2018–2021 for meaningful contrast with COVID-19 year (2020)

---

## 📦 Setup & Installation

To run the notebook and view results:

```bash
git clone https://github.com/yourusername/nyc-crash-insights.git
cd nyc-crash-insights
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

## 📍 Key Visualizations

- 📆 Hourly, daily, monthly, and yearly accident trends
- 🗺️ Borough-level heatmaps and injury/death distributions
- 📉 Accident trends before and during COVID-19

---

## 🔮 Potential Extensions

- Predictive modeling of crash likelihood (XGBoost, Random Forest, etc.)
- Integration with real-time traffic APIs
- Correlation with weather and population density
- Deploy as an interactive web dashboard

---

## 🌐 Live Demo / Website

If applicable, hosted project site under `SD_website-main/`:
```
coming soon / insert link
```

---

## 📄 License

MIT License. Feel free to use, remix, and share with attribution.

---

## 👥 Contributors

- [Your Name] (you@example.com)
- Collaborators can be listed here.
