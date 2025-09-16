# Wind Speed Data Visualisation Assignment

## Overview
This project visualises daily mean wind speed data from the Hong Kong Observatory. It demonstrates both informative and artistic approaches to data visualisation using Python, Jupyter Notebook, and SVG graphics.

## Data Source
- **Natural phenomenon:** Daily mean wind speed (weather data)
- **Source:** Hong Kong Observatory
- **Format:** CSV file (downloaded via URL in `.env`)

## Features
- Data download, cleaning, and processing
- Multiple visualisation types:
  - Line plot
  - Scatter plot
  - Histogram
  - Box plot
  - Artistic SVG bar chart (abstract layout)
- Step-by-step beginner-friendly notebook

## Artistic SVG Chart
The notebook includes a creative SVG chart where wind speed statistics are represented as radiating polygons, with playful colors, curved wind lines, and stylised text.

## How to Run
1. Open `data_visualisation_assignment.ipynb` in Jupyter Notebook or VS Code.
2. Ensure you have Python 3.8+ and the following packages installed:
   - pandas
   - matplotlib
   - requests
   - python-dotenv
   - drawsvg
3. Add your data URL to the `.env` file as `DATA_URL`.
4. Run the notebook cells in order.

## Dependencies
Install required packages with:
```
pip install pandas matplotlib requests python-dotenv drawsvg
```

## Folder Structure
- `data_visualisation_assignment.ipynb` — Main notebook
- `.env` — Stores your data URL
- `wind_speed.csv` — Downloaded data
- `wind-speed-abstract.svg` — Artistic SVG chart output

## Credits
- Data: Hong Kong Observatory
- Assignment: SD5913 Creative Programming for Designers And Artists

## Author
- Lin Kong Kit
