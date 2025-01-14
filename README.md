# T20-WorldCup2022-BestXI-Dashboard
Power BI dashboard analyzing T20 World Cup 2022 data to determine the best XI players based on their performance.
# T20 World Cup 2022: Best XI Dashboard

## Overview
This project analyzes data from the T20 World Cup 2022 to identify the best-performing players and create an optimized XI team. The analysis was performed using Python for data preprocessing and Power BI for visualization.

## Objective
- To determine the best possible team based on player performance during the T20 World Cup 2022.
- To visualize insights and trends using an interactive Power BI dashboard.

## Project Workflow
### Data Preprocessing (Python)
1. Collected data from an online source in JSON format.
2. Processed data to:
   - Generate required columns.
   - Perform transformations.
3. Exported cleaned data into four CSV files:
   - `dim_match_summary.csv`
   - `dim_players.csv`
   - `fact_batting_summary.csv`
   - `fact_bowling_summary.csv`

### Data Visualization (Power BI)
1. Loaded data into Power BI using a folder query.
2. Performed data transformations:
   - Renamed columns.
   - Removed duplicates.
   - Created calculated and custom columns.
3. Conducted data modeling and created DAX measures.
4. Built dashboards to:
   - Highlight top-performing players.
   - Visualize batting and bowling statistics.
   - Present the final Best XI team.

## Repository Structure
T20-WorldCup2022-BestXI-Dashboard/
│
├── data/                  # Raw and processed data files
│   ├── dim_match_summary.csv
│   ├── dim_players.csv
│   ├── fact_batting_summary.csv
│   ├── fact_bowling_summary.csv
│
├── scripts/               # Python scripts used for data processing
│   └── process.ipynb
│
├── powerbi/               # Power BI related files

## Tools & Technologies
- **Python**: Data preprocessing
- **Power BI**: Data visualization
- **DAX**: Measures and calculations
- **Power Query**: Data transformation

## How to Use
1. Clone this repository:
2. Open the Power BI file (`T20_World_2022_dashboard.pbix`) to explore the dashboards.
3. Access raw and processed data in the `data/` folder.

## Dashboards
Screenshots of the dashboards are available in the `powerbi/screenshots/` folder.
