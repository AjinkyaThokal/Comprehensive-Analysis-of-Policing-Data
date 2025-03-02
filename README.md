
# Crime Analysis in Colchester (2023)

## Overview

This project analyses street-level criminal occurrences in Colchester during 2023 using data retrieved from the UK Police Data API. The dataset, `colchester_data`, includes detailed information about individual incidents such as crime categories, dates, geographical coordinates, street names, and outcome statuses. 

The goal of this analysis is to provide actionable insights into the nature, frequency, and spatial distribution of reported crimes. By leveraging advanced data visualization techniques in R, this project aims to support evidence-based decision-making for law enforcement agencies, policymakers, and community stakeholders.

---

## Objectives

- Analyse the frequency and distribution of crime categories in Colchester.
- Identify spatial and temporal patterns of criminal activity.
- Provide actionable insights for resource allocation and targeted interventions.
- Foster collaboration between law enforcement, policymakers, and community stakeholders.

---

## Dataset

The dataset (`colchester_data`) contains the following key attributes:
- **Crime Categories**: Types of crimes (e.g., violent crime, anti-social behaviour, shoplifting).
- **Dates**: Timestamps of reported incidents.
- **Geographical Coordinates**: Latitude and longitude of crime locations.
- **Street Names**: Locations where crimes occurred.
- **Outcome Statuses**: Results of investigations or legal proceedings.
---

## Methodology

### Tools and Libraries
We utilized the following R packages for data visualization and analysis:
- **`ggplot2`**: For creating customizable and publication-quality plots.
- **`tidyr`**: To reshape and tidy data for visualisation.
- **`plotly`**: For interactive visualizations like bar charts, scatter plots, and 3D plots.
- **`leaflet`**: For creating interactive maps to visualize spatial data.

### Workflow
1. **Data Preparation**: Cleaned and transformed the dataset to ensure consistency.
2. **Exploratory Data Analysis (EDA)**: Summarized crime categories and identified trends.
3. **Visualization**:
   - Pie chart: Distribution of crime categories.
   - Histogram: Frequency distribution of crime types.
   - Box plot: Spatial distribution of crimes based on latitude.
   - Scatter plot: Geographical distribution of crime incidents.
   - Time series plot: Temporal trends in crime occurrences.
   - Leaflet map: Interactive map showing crime locations.
4. **Correlation Analysis**: Examined the relationship between latitude and longitude values.

---

## Key Findings

1. **Most Common Crime Category**: Violent crime accounted for 2,633 incidents, making it the most frequent category.
2. **Other Notable Categories**:
   - Anti-social behavior: 677 incidents.
   - Criminal damage/arson: 581 incidents.
   - Shoplifting: 554 incidents.
   - Public order offenses: 532 incidents.
3. **Spatial Patterns**: Certain areas in Colchester exhibit higher concentrations of specific crime types.
4. **Temporal Trends**: January 2023 had the highest number of reported crimes, with notable seasonal variations.

---

## Visualizations

### 1. Pie Chart
- Displays the distribution of crime categories.
- Highlights that violent crime is the most prevalent.

### 2. Histogram
- Shows the frequency distribution of crime types.
- Identifies variability in the occurrence of different crimes.

### 3. Box Plot
- Illustrates latitude distributions for each crime category.
- Identifies hotspots and outliers in crime locations.

### 4. Scatter Plot
- Visualizes the spatial distribution of crimes using longitude and latitude.
- Helps identify crime clusters and anomalies.

### 5. Time Series Plot
- Tracks crime occurrences over time.
- Reveals trends, seasonal patterns, and peak periods.

### 6. Leaflet Map
- Interactive map showing crime locations with pop-up details.
- Useful for identifying spatial trends and hotspots.

---

## Implications

The insights gained from this analysis can guide:
- **Resource Allocation**: Targeting high-crime areas with increased patrols or community programs.
- **Policy Development**: Designing strategies to address specific crime categories.
- **Community Engagement**: Encouraging proactive measures to reduce anti-social behavior and property-related crimes.

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/AjinkyaThokal/Comprehensive-Analysis-of-Policing-Data
   ```
2. Install the required R packages:
   ```R
   install.packages(c("ggplot2", "tidyr", "plotly", "leaflet"))
   ```
3. Load the dataset (`crime23.csv`) into your working directory.
4. Run the R script to generate visualizations and perform the analysis.

---

## Dependencies

- **R Version**: >= 4.0
- **R Packages**:
  - `ggplot2`
  - `tidyr`
  - `plotly`
  - `leaflet`

---



