# Sri Lanka Dengue Surveillance Dashboard
An interactive Quarto dashboard analyzing 19+ years (2006 - 2025) of weekly dengue 
surveillance data across all 26 districts of Sri Lanka.

## Data Source
Data obtained from the [`denguedatahub`](https://thiyangt.github.io/denguedatahubweb/srilanka.html) 
R package developed by Thiyanga S. Talagala, which provides weekly dengue surveillance 
datasets derived from the *Weekly Epidemiological Reports* published by the Epidemiology 
Unit, Ministry of Health, Sri Lanka.

## Features
- National trend and 12 - week moving average
- Seasonal pattern analysis (STL decomposition)
- Outbreak detection (mean + 2×SD threshold)
- Interactive choropleth map by district
- ARIMA-based forecasting with a year-lookup widget
- Filterable, exportable data explorer

## Live dashboard
[View it here](your-github-pages-link)

## Tools
R, Quarto, Plotly, Leaflet, forecast (ARIMA), STL decomposition

## Reference
Talagala, T. S. (2024). *denguedatahub*: An R package providing dengue surveillance 
datasets for data analysis and visualization. CRAN.
