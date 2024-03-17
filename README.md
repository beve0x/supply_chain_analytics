# supply_chain_analytics
# Supply Chain Logistics Optimization

## Overview
This project aims to optimize carrier and origin port selection for shipments to PORT09. The goal is to minimize shipping costs and ensure timely delivery within a single operational day. Using Python and libraries like pandas for data manipulation, matplotlib, and seaborn for data visualization, the project analyzes freight rates, order lists, and warehouse costs. Advanced optimization techniques involving linear programming, discrete event simulation, and genetic algorithms are employed to find cost-effective shipping solutions.

## Installation

### Prerequisites
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- SimPy (Optional for simulation)
- DEAP (Optional for genetic algorithms)

### Setup
1. Clone the repository to your local machine.
2. Ensure Python 3.x is installed.
3. Install the required Python packages:
   ```shell
   pip install pandas matplotlib seaborn
For optional simulation and optimization sections:
pip install simpy deap
Data Description
The analysis is based on data from an Excel file Supply chain logistics problem.xlsx, which contains the following sheets:

FreightRates: Contains freight rate information, including carrier details, weight ranges, and costs.
OrderList: Lists orders with details on order ID, order date, origin port, carrier, and other relevant shipping information.
WhCosts: Warehouse costs associated with different plant codes.
Ensure the file path in the script matches the location of the Excel file on your machine.

Usage
To run the project:

Update the file_path variable in the script to point to your Excel file.
Execute the script in sections to follow the analysis steps, which include:
Data loading and preprocessing
Exploratory data analysis (EDA) to understand shipping costs and identify patterns
Optimization tasks to minimize total logistics costs using various methods
Key Components
Data Cleaning: Identify and handle missing values and anomalies in the dataset.
Data Analysis: Use descriptive statistics and visualizations to explore freight rates and order details.
Optimization:
Linear Programming: Apply linear programming to minimize logistics costs.
Discrete Event Simulation (DES): Simulate the order processing and shipping to identify cost reduction opportunities.
Genetic Algorithm (GA): Employ genetic algorithms to find the optimal carrier and port selection.
