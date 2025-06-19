# Earthquake Data Visualization & Analysis

An interactive Jupyter Notebook for fetching, visualizing, and analyzing global earthquake data using real-time information from the USGS Earthquake API.

## Features
- **Fetch Real-Time Data:** Retrieve earthquake data for any date and magnitude range from the USGS API.
- **Interactive Widgets:** Select date range and magnitude thresholds using intuitive widgets.
- **Comprehensive Analysis:**
  - Basic statistics (totals, averages, ranges)
  - Magnitude and depth categorization
  - Most active regions and time periods
  - Tsunami risk and alert levels
- **Visualizations:**
  - Interactive world map of earthquake locations and magnitudes
  - Analytical dashboard: histograms, scatter plots, timelines, and pie charts
- **Regional Analysis:** Focus on specific geographic regions.
- **Export:** Save analyzed data to CSV for further use.

## Technologies Used
- Python 3
- Jupyter Notebook
- [Plotly](https://plotly.com/python/) (for interactive maps and charts)
- [Pandas](https://pandas.pydata.org/) (data processing)
- [ipywidgets](https://ipywidgets.readthedocs.io/) (for interactivity)
- [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd Earthquake
   ```
2. **Install dependencies:**
   Open the notebook and run the first cell, or install manually:
   ```bash
   pip install plotly pandas requests jupyter-dash ipywidgets
   ```
3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Open `Earthquake Map.ipynb` and run all cells.**

## Usage
- Use the date pickers and magnitude sliders to select your desired analysis range.
- Click **Run Analysis** to fetch data, view statistics, and see interactive visualizations.
- Use the export function to save results as CSV.
- Optionally, analyze specific regions by latitude/longitude.

## Example
![Example Screenshot](#) <!-- Add a screenshot if available -->

## Data Source
- [USGS Earthquake Catalog API](https://earthquake.usgs.gov/fdsnws/event/1/)

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Credits
Developed by [Your Name].

---
*Feel free to contribute or suggest improvements!* 