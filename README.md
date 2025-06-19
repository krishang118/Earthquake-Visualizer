# Earthquake Visualizer

A system for fetching, visualizing, and analyzing real-time global earthquake data using the USGS Earthquake API.

## Features
- Fetch Real-Time Data: Retrieve earthquake data for any date and magnitude range from the USGS API.
- Interactive Widgets: Select date range and magnitude thresholds using intuitive widgets.
- Comprehensive Analysis:
  - Basic statistics (totals, averages, ranges)
  - Magnitude and depth categorization
  - Most active regions and time periods
  - Tsunami risk and alert levels
- Visualizations:
  - Interactive world map of earthquake locations and magnitudes
  - Analytical dashboard: histograms, scatter plots, timelines, and pie charts

## Technologies Used
- Plotly (for interactive maps and charts)
- Pandas (for data processing)
- ipywidgets (for interactivity)
- [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)

## How to Run
1. Clone this repository on your local machine.
2. Open the `Earthquake Visualizer.ipynb` Jupyter Notebook and run the first cell to install the required dependencies.
3. Run the second cell and set the required ranges to see the visualizations and analysis.

## Contributing

Contributions are welcome!

## License

Distributed under the MIT License.  
