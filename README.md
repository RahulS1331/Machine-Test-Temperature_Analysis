# # Machine-Test-Temperature_Analysis

This repository contains a detailed analysis and visualization of temperature data near Ann Arbor, Michigan, using NOAA datasets. The project includes record high and low temperatures from 2005-2014, along with a 2015 overlay for any records broken during that year. The analysis also features a geographic visualization of data stations and a temperature summary for 2015.


## Files in the Repository

- `assignment.ipynb`: The Jupyter notebook containing the code for the analysis and visualization.
- `temperature.csv`: The dataset with temperature records.
- `BinSize.csv`: The dataset with station locations.
- `ann_arbor_stations_map.html`: A map visualization of stations near Ann Arbor, Michigan.
  
### Data Source:
- **NOAA Daily Global Historical Climatology Network (GHCN-Daily)**

### Datasets:
- `temperature.csv`
- `BinSize.csv`

### Analysis Tasks:
1. **Record High and Low Temperatures (2005-2014):**
   - Line graph visualization with shaded areas between the record high and low temperatures for each day of the year.
   
2. **2015 Data Overlay:**
   - Scatter plot overlay for 2015 data, highlighting points where the ten-year record was broken.
   
3. **Leap Day Consideration:**
   - February 29th data removed to ensure consistency in year-over-year comparisons.
   
4. **Station Visualization:**
   - Mapping of data collection stations near Ann Arbor, Michigan.

5. **2015 Temperature Summary:**
   - Visualization summarizing temperature data near Ann Arbor for 2015.

## Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib : For creating visualizations.
- **Folium: For creating interactive maps that can be easily customized and integrated with other data analysis results
  

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Machine-Test-Temperature_Analysis.git
2. Open the `assignment.ipynb` in Jupyter Notebook.
3. Ensure you have the necessary libraries installed (`pandas`, `matplotlib`, `folium`).
4. Run the cells to generate plots and maps.

## Approach

- Plotted record high and low temperatures for each day of the year from 2005-2014.
- Identified and highlighted records broken in 2015.
- Visualized station locations near Ann Arbor using Folium.
