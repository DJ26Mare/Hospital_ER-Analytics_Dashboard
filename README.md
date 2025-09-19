# Hospital_ER-Analytics_Dashboard

![Hospital Dashboard Final ](https://github.com/user-attachments/assets/b786b0e3-f21a-41c9-ab42-3b7e4cdfb026)

## Overview
- This project is a **Hospital Emergency Room Dashboard** designed using **Power Query**, **Power Pivot**, and other Excel-based tools.
- The dashboard provides key insights into emergency room operations, patient flow, wait times, and other critical metrics.
- Helps hospital administrators make data-driven decisions.
- Extended with **Machine Learning analysis** (K-Means clustering) to segment patients by wait-time patterns and support better resource allocation.

## Features
- **Data Integration**: Utilizes Power Query to import, clean, and transform raw hospital data.
- **Data Modeling**: Implements Power Pivot to create relationships between tables and perform complex calculations.
- **Interactive Dashboard**: Provides dynamic visualizations and reports for key hospital performance indicators.
- **Performance Metrics**: Tracks metrics such as patient wait times, treatment times, doctor availability, and emergency case severity.
- **Filters & Slicers**: Enables users to filter and analyze data based on different time periods, departments, and patient demographics.
-  **Clustering Analysis**: Applied **K-Means clustering** on patient wait times to segment patients into short, moderate, and long wait groups, helping identify operational bottlenecks and optimize staff allocation.

## Technologies Used
- **Power Query** for data extraction, transformation, and loading (ETL).
- **Power Pivot** for data modeling and DAX calculations.
- **Excel PivotTables & Charts** for visualization.
- **Python (Scikit-learn, Pandas, Matplotlib)** for machine learning clustering analysis.

## How to Use
1. Open the provided **Excel file** containing the dashboard.
2. Refresh the data using **Power Query** if needed.
3. Navigate through the interactive **PivotTables and Charts** to explore insights.
4. Use available slicers and filters to focus on specific data segments.
5. Run the provided **Jupyter Notebook** to reproduce the clustering analysis and explore patient segmentation results.

## Installation
- Ensure you have **Microsoft Excel (2016 or later)** with Power Query and Power Pivot enabled.
- Download and open the Excel file.
- If prompted, enable macros and external connections for full functionality.
- For clustering analysis, install Python with required libraries:
  ```bash
  pip install pandas scikit-learn matplotlib



