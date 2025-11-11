# Data visualisation project - PAC 2
This repository contains the code and datasets used for PAC2 of the visualització de dades course.
The goal is to show a sample of three assigned visualisation types using open data and the R language.

# 1. Repository structure
```text
.
├── data-visualization_files/    # Automatically generated folder by R Markdown/knitr
│   └── figure-latex             # Contains figures and auxiliary output elements
├── 2024_accidents_gu_bcn.csv      # Barcelona city guard accidents data (input data)
├── Data-visualization-project.Rproj # RStudio project file
├── LICENSE                      # License file 
├── README.md                    # Main project documentation (This file)
├── data visualization.Rmd       # R Markdown file containing code for analysis and visualization
├── data-visualization.html      # Final report in HTML format generated from the Rmd
├── index.html                   # Landing page presentation file
├── meteo_2024.csv               # Meteorological data for 2024 (input data).
└── meteo_23_24.csv              # Consolidated meteorological data 2023-2024 (input data).
```
# 2. Dependencies
R packages: 

- Tidyverse

- Dygraphs

- Xts

- Lubridate

- Fmsb

- Stringr

- Showtext

# 3. Data sources
- **Area chart**- Monthly evolution of the average temperature in Barcelona during 2024: https://opendata.aemet.es/centrodedescargas/productosAEMET
- **Radar chart**- Comparison of daily weather patterns between 2023 and 2024 in the city of Barcelona: https://opendata.aemet.es/centrodedescargas/productosAEMET
- **Rose chart**- Frequency of traffic accidents in BCN by day of the week: https://opendata-ajuntament.barcelona.cat/data/ca/dataset/accidents-gu-bcn
# 4. License
GPL-3.0 License
# 5. Visualizations web page
https://gemmbs.github.io/Data-visualization-project/
# 6. Author
**Gemma Bargalló Solé**
