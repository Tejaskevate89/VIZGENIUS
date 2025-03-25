# VIZGENIUS

## Overview
Vizgenious is an automated data visualization tool designed to simplify and enhance the process of generating insightful visualizations. It leverages Python and various data visualization libraries to create compelling graphical representations of datasets with minimal user intervention.

## Features
- Automated generation of visualizations
- Support for multiple chart types (bar, line, scatter, pie, heatmaps, etc.)
- Intelligent selection of the best visualization based on data
- Interactive and customizable charts
- Export options for saving visualizations in different formats
- Machine learning integration for data analysis
- Statistical analysis with t-tests and chi-square tests

## Technologies Used
- **Python**
- **Pandas** for data handling
- **Matplotlib & Seaborn** for static visualizations
- **Plotly** for interactive visualizations
- **Streamlit** for UI
- **Scikit-learn** for machine learning integration
- **SciPy** for statistical analysis

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Tejaskevate89/Vizgenious.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Vizgenious
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script:
   ```sh
   python main.py
   ```
2. Upload or provide a dataset.
3. Select or let the tool recommend the best visualization.
4. Interact with or export the generated visualizations.

## Example
```python
from vizgenious import Vizgenious

# Initialize
viz = Vizgenious("data.csv")

# Generate visualization
viz.generate_chart(chart_type="bar")
```




