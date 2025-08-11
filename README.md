# Automotive-analysis

## Overview
This project analyzes a dataset of car specifications including attributes like Make, Model, Type, Origin, DriveTrain, MSRP, Horsepower, MPG, Weight, and more. The goal is to clean, explore, and visualize the data to gain insights into car performance and pricing.

## Dataset
The dataset contains the following columns:
- Make
- Model
- Type
- Origin
- DriveTrain
- MSRP
- Invoice
- EngineSize
- Cylinders
- Horsepower
- MPG_City
- MPG_Highway
- Weight
- Wheelbase
- Length

## Key Features and Analyses
- Handling missing values by filling with mean values.
- Counting unique car Makes and occurrences.
- Filtering cars by Origin (e.g., Asia, Europe).
- Removing records where Weight > 4000.
- Group-wise average calculations (e.g., average MSRP by Make).
- Identifying top and bottom performers in Horsepower and MPG.
- Visualizations including histograms and boxplots.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Jeseenacodes/car-data-analysis.git
