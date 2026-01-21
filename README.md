# 🌍 Climate Pulse: CO₂ & Temperature Trends Explorer

## 📖 Introduction
**Climate Pulse** is a modular R project developed to analyze historical global CO₂ concentrations and temperature anomalies. The project investigates patterns, correlations, and potential tipping points in climate data, culminating in an **interactive Shiny dashboard**. 

The goal is to provide a dynamic exploration tool that demonstrates professional project structuring, data reproducibility, and impactful visualization of critical environmental trends.

---

## 🛠️ Technologies Used
| Category | Tools / Packages |
| :--- | :--- |
| **Language** | R |
| **Data Wrangling** | `tidyverse`, `lubridate` |
| **Visualization** | `ggplot2`, `gganimate`, `plotly` |
| **Dashboarding** | `shiny`, `shinydashboard`, `DT` |
| **Reporting** | `RMarkdown`, `knitr` |
| **Data Sources** | `hockeystick` (Mauna Loa/Ice Cores), Our World in Data |

---

## ✨ Features
- **Historical Analysis:** Explores atmospheric CO₂ from Mauna Loa and ice core records.
- **Anomaly Tracking:** Visualizes global surface temperature deviations from the 20th-century average.
- **Correlation Engine:** Dynamic scatter plots showing the relationship between CO₂ levels and temperature rise.
- **Interactive Dashboard:** User-friendly Shiny interface with tabs for data trends and insights.
- **External Integration:** Incorporates global emissions data from *Our World in Data* for broader context.

---

## ⚙️ Development Process
1. **Data Acquisition:** Utilized the `hockeystick` package to pull high-fidelity climate data and integrated the `owid-co2-data` global dataset.
2. **Data Wrangling:** Performed cleaning and preparation using the `tidyverse` to ensure CO₂ and temperature measurements were aligned for time-series analysis.
3. **Exploratory Visualization:** Created initial `ggplot2` visualizations to identify long-term trends and post-1950 acceleration patterns.
4. **Dashboard Construction:** Architected a `shinydashboard` to host interactive elements, allowing users to filter and engage with the data in real-time.
5. **Optimization & Documentation:** Structured the repository for full reproducibility and documented the workflow to professional standards.

---

## 📚 What I Learned
- **R Project Architecture:** Managing modular scripts and data folders for professional reproducibility.
- **Time-Series Analysis:** Handling and cleaning historical climate data with different measurement frequencies.
- **Reactive Programming:** Understanding the logic of Shiny inputs/outputs for dashboard interactivity.
- **Scientific Storytelling:** Using data visualization to communicate complex global trends clearly.

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/malek-khadhraoui/Climate-Pulse.git](https://github.com/malek-khadhraoui/Climate-Pulse.git)
   ```
2. **Open the project** in RStudio.
3. **Install required packages** by running this in your R console:
   ```R
   install.packages(c("tidyverse", "shiny", "shinydashboard", "plotly", "hockeystick", "DT"))
   ```
4. **Prepare the data** by running:
   ```R
   source("scripts/data_load.R")
   ```
5. **Launch the dashboard** by running:
   ```R
   shiny::runApp("scripts/app.R")
   ```

---

## 🎥 Project Demonstration
Check out the interactive dashboard in action:  

**▶️ [Climate Pulse: Dashboard Walkthrough]**

---

## 👤 Author
**Malek Khadhraoui** Software Engineering Graduate & Data Science Master’s Degree Student
