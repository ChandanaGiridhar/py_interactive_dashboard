# Python Interactive Dashboard SuperStore Data Visualizations

## Description

This project provides interactive data visualizations for the SuperStore dataset using Streamlit, Plotly, and Pandas. The application allows users to filter data by date, region, state, and city, and visualize sales data through various charts and tables.

## Features

- **Date Filtering**: Filter data by start and end date.
- **Region, State, and City Filtering**: Filter data by region, state, and city using multi-select dropdowns.
- **Category-wise Sales**: Display sales data categorized by product category.
- **Region-wise Sales**: Display sales data categorized by region.
- **Time Series Analysis**: Visualize sales data over time.
- **Tree Map**: Group sales data by region, category, and sub-category.
- **Segment and Category Pie Charts**: Display sales distribution by segment and category.
- **Month-wise Sub-Category Sales Summary**: Show sales data for sub-categories by month.
- **Scatter Plot**: Visualize the relationship between sales and profits.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/ChandanaGiridhar/py_interactive_dashboard.git
    cd py_dashboard
    ```

2. **Create a virtual environment** (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```sh
    streamlit run dashboard.py
    ```

## Requirements

- Python 3.8+
- Pandas
- Plotly
- Streamlit
- Matplotlib

## Configuration

Ensure that `matplotlib` is included in the `requirements.txt` file:
```plaintext
pandas==2.2.2
plotly==5.22.0
streamlit==1.36.0
matplotlib<4.0.0
