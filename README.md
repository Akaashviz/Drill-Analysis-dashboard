# Drill Throw Analysis Dashboard

An interactive Power BI dashboard for monitoring manufacturing production quality and machine performance — tracking rejection rates, machine failures, downtime, energy consumption, and sensor readings across batches and machines.

![Dashboard Preview](screenshots/drill-analysis.png)

## Features

- **Key stats cards** — Total Actual (quantity), Total Rejected, Total Repair Cost, and Sum of Machine count
- **Rejection Rate by batch_id** — line chart tracking rejection rate trends across production batches
- **Machine Failure Rate by machine_id** — bar chart comparing failure rates across individual machines
- **Down Time by machine_id** — horizontal bar chart ranking machines by total downtime
- **Actual Quality by product_type** — donut chart showing quality output distribution across product types
- **Temperature vs Vibration** — scatter plot correlating average temperature and vibration readings
- **Energy and Energy1 by Month** — dual-axis line chart tracking two energy metrics across the year

## Tech Stack

- **Power BI** (`drill throw.pbix`) — dashboard and data modeling
- Data source: manufacturing/production sensor and batch dataset (CSV/Excel — see `/data`)

## Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — Windows only

### Setup

1. Clone the repository
```bash
   git clone https://github.com/<your-Akaashviz>/drill-throw-analysis.git
   cd drill-throw-analysis
```
2. Open `Drill_Throw_Analysis.pbix` in Power BI Desktop
3. If prompted, update the data source path to point to the dataset in `/data`
4. Click **Refresh** to load the latest data

## Project Structure
