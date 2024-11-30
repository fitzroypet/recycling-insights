# Global Recycling Insights Dashboard

An interactive data visualization dashboard that explores the relationship between recycling rates, GDP, population density, and other environmental metrics across different countries and continents.

## Overview

This project visualizes global recycling data through multiple interactive charts to help understand:
- Relationship between GDP and recycling rates
- Impact of population density on recycling scores
- Multi-dimensional analysis of environmental metrics
- Top performing countries in recycling

## Features

- **Interactive Visualizations:**
  - GDP vs Recycling Score Scatter Plot
  - Population Density vs Recycling Score Analysis
  - Multi-dimensional Bubble Chart
  - Top Recycling Countries Bar Chart

- **Filtering Capabilities:**
  - Filter by continent
  - Interactive tooltips
  - Responsive design for all screen sizes

## Data Sources

The dashboard combines data from multiple sources:
- Environmental Performance Index (EPI) 2022
- World Bank GDP Data
- Population Density Statistics
- Continental Classification

## Tech Stack

- **Frontend:**
  - D3.js for data visualization
  - HTML5/CSS3 for layout and styling
  - Vanilla JavaScript for interactions

- **Data Processing:**
  - Python for data cleaning and merging
  - Pandas for data manipulation
  - JSON for data storage

## Project Structure 

DataVisualizationProject/
├── analysis/
│ └── eda/ # Exploratory Data Analysis outputs
├── data/ # Raw and processed data files
├── scripts/ # Python scripts for data processing
│ ├── data.py # Data processing script
│ └── eda.py # Exploratory data analysis
└── src/ # Frontend source code
├── css/ # Stylesheets
├── js/ # JavaScript files
└── data/ # Processed data for visualization

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/fitzroypet/recycling-insights.git
   ```

2. Set up Python environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Process the data:
   ```bash
   python scripts/data.py
   python scripts/setup.py
   ```

4. Start a local server:
   ```bash
   cd src
   python -m http.server 8000
   ```

5. Open in browser:
   ```
   http://localhost:8000
   ```

## Usage

- Use the continent filter to focus on specific regions
- Hover over data points to see detailed information
- Observe relationships between different metrics
- Identify top-performing countries in recycling initiatives

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Fitzroy Meyer-Petgrave - [@fitzroypet](https://github.com/fitzroypet)

Project Link: [https://github.com/fitzroypet/recyclinginsights](https://github.com/fitzroypet/recycling-insights)