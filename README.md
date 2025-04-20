# Crime Data Analysis Project in Colchester

## Introduction

In this project, we explore the `Crime23` dataset, which contains information about crimes in Colchester during a specific time period. By using data visualization techniques, we aim to gain a deeper understanding of crime distribution across categories, identify high-risk areas, and analyze temporal trends. This project uses graphs, charts, and interactive maps to uncover patterns and relationships in the data, helping us understand why crimes occur and how they can be prevented in the future.

---

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Analysis Highlights](#analysis-highlights)
5. [Contributing](#contributing)
6. [License](#license)

---

## Features

This project includes the following features:
- **Descriptive Statistics**: Summarizing crime categories and outcomes.
- **Visualization**: Interactive plots and maps to explore crime patterns.
  - Line charts for crime trends.
  - Pie charts for category distributions.
  - Density plots for temporal trends.
  - Leaflet maps for spatial analysis.
- **Correlation Analysis**: Examining relationships between latitude, longitude, and crime occurrences.
- **Time Series Analysis**: Identifying seasonal or monthly trends in crime rates.
- **Interactive Tools**: Dynamic visualizations using `plotly` and `leaflet`.

---

## Installation

To run this project locally, follow these steps:

### Prerequisites
- Install [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/).
- Ensure you have Git installed: [Git Downloads](https://git-scm.com/downloads).

### Clone the Repository
```bash
git clone https://github.com/your-username/colchester-crime-analysis.git
cd colchester-crime-analysis
```

### Install Required Libraries
Run the following commands in your R console to install the necessary libraries:
```R
install.packages(c("ggplot2", "dplyr", "tidyr", "reshape2", "GGally", "zoo", "ggmap", "leaflet", "plotly", "mapview"))
```

### Load the Dataset
Place the `crime23.csv` file in the root directory of the project. Ensure the file path matches the one specified in the script.

---

## Usage

1. Open the R script (`analysis.R`) in RStudio.
2. Set the working directory to the project folder:
   ```R
   setwd("path/to/colchester-crime-analysis")
   ```
3. Run the script step-by-step to generate visualizations and analyses.
4. Explore the outputs:
   - Static visualizations (e.g., histograms, scatter plots).
   - Interactive maps and plots (e.g., leaflet maps, plotly charts).

---

## Analysis Highlights

### Key Findings
1. **Violent Crimes**: The most prevalent category with 2,633 incidents. These cases often result in challenges such as "Unable to prosecute suspect" or "No suspect identified."
2. **Anti-Social Behavior**: 677 incidents indicate ongoing public order disturbances.
3. **Temporal Trends**: Crime rates peak at the start of the year and decline gradually.
4. **Spatial Clusters**: High-density crime areas are concentrated around specific latitude and longitude coordinates (e.g., 51.89, 0.89).
5. **Outcome Patterns**: A significant number of cases (2,656) have "No suspect identified," highlighting investigative challenges.

### Visualizations
- **Pie Chart**: Distribution of crime categories.
- **Density Plot**: Temporal trends in crime occurrences.
- **Leaflet Map**: Geographical distribution of crimes.
- **Violin Plot**: Spatial density of crime categories.

---

## Contributing

We welcome contributions to this project! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

---

## Acknowledgments

- Thanks to the creators of the R libraries used in this project.
- Special thanks to the contributors of the `Crime23` dataset for making this analysis possible.
