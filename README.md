# Mobile Features Analysis

## Table of Contents
1. [Overview](#overview)
2. [Key Objectives](#key-objectives)
3. [Dataset Details](#dataset-details)
4. [Tools and Technologies Used](#tools-and-technologies-used)
5. [Project Structure](#project-structure)
6. [Features of the Dashboard](#features-of-the-dashboard)
7. [How to Use](#how-to-use)
8. [Insights and Findings](#insights-and-findings)
9. [Challenges Faced](#challenges-faced)
10. [Future Scope](#future-scope)
11. [Contributing](#contributing)
12. [License](#license)

---

## Overview
The Mobile Features Analysis project explores mobile device features to provide insights into customer preferences, pricing trends, and technological developments. The analysis is presented through interactive dashboards in Power BI.

---

## Key Objectives
- To identify key mobile features that influence purchasing decisions.
- To analyze pricing trends across brands and models.
- To uncover correlations between mobile features and market performance.

---

## Dataset Details
- **Source**: The dataset was sourced from [Kaggle](https://www.kaggle.com).
- **Key Features**:
  - **Brand**: The manufacturer of the mobile device (e.g., Samsung, Apple, Xiaomi).
  - **Model**: The model name or identifier of the mobile device.
  - **Battery Life**: Battery capacity or usage time (measured in mAh or hours).
  - **Camera Quality**: Camera specifications such as megapixels (MP).
  - **RAM**: Memory capacity of the device (measured in GB).
  - **Storage**: Internal storage capacity (measured in GB or TB).
  - **Price**: The cost of the device (measured in USD or other currencies).
  - **Release Year**: The year the device was released to the market.
- **File Format**: The dataset is provided in `.csv` format.

---

## Tools and Technologies Used
- **Power BI**: Used for data modeling, visualization, and creating interactive dashboards.
- **SQL**:Utilized for advanced data extraction, transformation, and loading (ETL).

---

## Project Structure
```
MobileFeaturesAnalysis/
│
├── MobileFeaturesAnalysis.pbix    # Power BI file containing the dashboards
├── README.md                      # Documentation file
├── data/                          # Folder for raw and processed datasets
│   ├── raw_data.csv
│   ├── processed_data.csv
├── screenshots/                   # Folder containing dashboard screenshots
│   ├── dashboard_1.png
│   ├── dashboard_2.png
└── LICENSE                        # License file
```

---

## Features of the Dashboard
- **Interactive Filters**: Allow users to explore specific brands, price ranges, or features.
- **Key Metrics Visualization**: Display insights such as average price, feature comparisons, and market trends.
- **Custom Visuals**: Use unique visuals to highlight significant data points and patterns.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Sneha-janapurkar/MobileFeaturesAnalysis.git
   ```
2. Open `MobileFeaturesAnalysis.pbix` in Power BI Desktop.
3. Interact with the dashboards to explore various insights.

---

## Insights and Findings
- Customers prioritize **battery life** and **camera quality** when purchasing a mobile device.
- Pricing trends reveal a steady rise in mid-range devices offering flagship-level features.
- Brands that focus on **RAM and storage upgrades** have a competitive advantage in the market.

---

## Challenges Faced
- **Data Cleaning**: Handling missing or inconsistent data entries.
- **Feature Correlation**: Identifying meaningful correlations between diverse features.
- **Visualization Choices**: Balancing data complexity with user-friendly visuals.

---

## Future Scope
- Integrate additional datasets, such as customer reviews and sales data.
- Expand the analysis to include emerging mobile brands and markets.
- Develop predictive models for market trends using machine learning.

## License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project as long as proper credit is given to the original author. For more details, please refer to the [LICENSE](LICENSE) file.

---

