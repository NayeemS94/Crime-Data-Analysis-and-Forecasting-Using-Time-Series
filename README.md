# Crime Data Analysis and Forecasting Using Time Series

## Project Overview
This project analyzes crime data and applies machine learning techniques for clustering and time series forecasting. It includes:
- **Clustering**: Grouping states with similar crime patterns using K-Means.
- **Geospatial Analysis**: Visualizing crime distribution on an interactive map.
- **Time Series Forecasting**: Predicting future crime trends using Facebook Prophet.

## Features
### 1. Data Analysis
- Exploratory Data Analysis (EDA) to understand crime trends.
- Statistical insights into crime patterns across states.

### 2. Clustering (K-Means)
- Standardizing crime data for better clustering.
- Grouping states into clusters based on crime statistics.
- Visualization of clusters using scatter plots.

### 3. Geospatial Analysis
- Interactive crime distribution map using Folium.
- Marker clustering to manage large datasets effectively.
- State-wise crime information displayed in tooltips.

### 4. Time Series Forecasting
- Using Facebook Prophet to predict future crime trends.
- Analyzing seasonal trends and anomalies.
- Visualization of predicted trends.

## Dataset
- The dataset contains crime statistics across different states.
- Key columns: `STATE/UT`, `MURDER`, `THEFT`, `ASSAULT`, `TOTAL IPC CRIMES`, etc.
- **Additional latitude/longitude data added for mapping.**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nayeemsam/crime-data-analysis.git
   cd crime-data-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn folium fbprophet
   ```

## Usage
- Run the clustering script:
  ```bash
  python crime_clustering.py
  ```
- Run the geospatial analysis:
  ```bash
  python crime_map.py
  ```
- Run the time series forecasting:
  ```bash
  python crime_forecasting.py
  ```
- Open `crime_map.html` in a browser to view the crime map.

## Results
- **Clustered States**: States grouped by similar crime patterns.
- **Interactive Crime Map**: View crime distribution geographically.
- **Crime Forecasting**: Insights into future crime trends.

## Contributing
Feel free to fork this repository, raise issues, or submit pull requests.

## License
This project is licensed under the MIT License.
