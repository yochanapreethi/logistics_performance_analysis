# Logistics Performance Analysis

## Overview

This project analyzes logistics and supply chain delivery performance using historical shipment data. The Jupyter Notebook provides in-depth insights into delivery trends, late shipment causes, cost analysis, and fulfillment performance. The analysis supports data-driven decision-making for optimizing logistics efficiency and reliability.

## File Contents

| File/Folder                          | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| `Logistics_Performance_Analysis.ipynb` | Jupyter Notebook with full exploratory data analysis and visualizations     |
| `SCMS_Delivery_History_Dataset.csv`   | Dataset containing historical delivery performance logs                     |
| `assets/`                             | Custom charts, images, or icons used in documentation/visuals (optional)    |
| `README.md`                           | Documentation and usage instructions                                        |

## Key Features

- **Delivery Performance Metrics**  
  Track KPIs such as on-time delivery rate, lead time, order quantity, and shipment delays  

- **Trend Analysis**  
  Explore delivery performance across countries, products, and time periods  

- **Late Shipment Insights**  
  Identify common factors leading to delivery delays (e.g., transport mode, supplier, region)  

- **Cost & Quantity Analysis**  
  Examine procurement cost patterns and shipment volumes for efficiency opportunities  

- **Supplier & Transport Evaluation**  
  Compare supplier performance and assess transport modes for reliability  

- **Interactive Visuals**  
  Visualize trends through bar plots, line charts, and correlation heatmaps  

## Tools & Technologies

- **Python (Jupyter Notebook)** – Core analysis and visualization  
- **Pandas** – Data manipulation and cleaning  
- **Matplotlib & Seaborn** – Charts and visual insights  
- **NumPy** – Numerical analysis and calculations  
- **CSV Dataset** – SCMS Delivery History dataset as primary data source  

## Getting Started

1. **Clone the Repository**  
    ```bash
    git clone https://github.com/your-username/logistics_performance_analysis.git
    cd logistics_performance_analysis
    ```

2. **Install Dependencies**  
   Ensure Python 3.x is installed. Then install required packages:  
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3. **Run the Notebook**  
    ```bash
    jupyter notebook Logistics_Performance_Analysis.ipynb
    ```

4. **Explore the Data**  
   - The dataset `SCMS_Delivery_History_Dataset.csv` contains key columns such as:  
     `Shipment Mode`, `Supplier`, `Country`, `Item Description`, `Delivery Recorded Date`,  
     `Planned Delivery Date`, `Freight Cost`, `Unit Price`, `Line Item Quantity`  

## Use Cases

- Monitor logistics KPIs like on-time delivery and shipment costs  
- Detect inefficiencies in supplier performance and transport mode choices  
- Identify delivery delay factors and optimize lead times  
- Support supply chain managers with actionable performance insights  

> For suggestions, improvements, or collaboration, feel free to contribute or raise an issue.
