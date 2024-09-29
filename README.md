# End-to-End Analysis of Internship Dataset

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies](#technologies)
- [Analysis Breakdown](#analysis-breakdown)
  - [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Statistical, Sectoral, and Geospatial Analysis](#statistical-sectoral-and-geospatial-analysis)
- [Results](#results)
- [Tableau Dashboard](#tableau-dashboard)

## Project Overview
This project involves a comprehensive analysis of an internship dataset obtained from Kaggle. It focuses on cleaning and preprocessing the dataset, followed by exploratory data analysis (EDA), and conducting statistical, sectoral, and geospatial analysis. The key insights are visualized using an interactive Tableau dashboard.

## Objective
The aim of this project is to:
- Clean and preprocess the internship dataset.
- Perform detailed statistical, sectoral, and geospatial analysis.
- Derive actionable insights such as:
  - Top locations providing internships.
  - Highest-paying sectors in terms of stipends.
  - Average stipend trends across different locations and sectors.
  - Geospatial distribution of internships to identify regional hotspots.

These insights are presented through an interactive Tableau dashboard, enabling better visualization and decision-making.

## Dataset
The dataset was obtained from Kaggle and consists of the following fields:
- Organization
- Location
- Start Date
- Duration (in Months)
- Average Monthly Stipend
- Added Incentives

## Features
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Statistical & Geospatial Analysis
- Interactive Tableau Dashboard

## Technologies
- **Excel and SQL**: Cleaning and preprocessing the dataset.
- **Python**: Scripting and data manipulation.
- **Pandas**: Data processing and analysis.
- **Tableau**: Interactive dashboard creation.

## Analysis Breakdown

### Data Cleaning and Preprocessing
The data was cleaned to remove null values, duplicate records, and invalid entries, ensuring consistent data quality for the analysis. Furthermore, the data was preprocessed and insights were pulled out using Microsoft Excel and Google BigQuery SQL.

The original dataset had several discrepancies, which were addressed by thoroughly cleaning, adding new fields, and eliminating redundant ones. This process was carried out using Microsoft Excel. Various insights were derived using Excel pivot tables and Google BigQuery SQL. The updated dataset Excel sheet features the various details obtained in individual sheets.

### Exploratory Data Analysis
EDA was conducted to identify trends, distributions, and relationships between various fields in the dataset, such as average stipend across sectors and locations.

### Statistical, Sectoral, and Geospatial Analysis
The following key analyses were performed:
- **Statistical**: Analyzing average monthly stipends and duration trends across various sectors.
- **Sectoral**: Identifying which sectors offer the most internships and which provide the highest stipends.
- **Geospatial**: Using maps to display the concentration of internship opportunities across different geographic locations.

### Results
The analysis provided key insights into:
- Popular internship locations.
- High-paying sectors.
- Geographic distribution of internships.

## Tableau Dashboard
The Tableau dashboard created for this project showcases the key insights:
- **Top Locations** for internships.
- **Sector-based Stipend Comparison**.
- **Geospatial Heatmap** showing regional distributions of internships.
- **Sectoral Breakdown** of internships based on stipend distribution.

To view the Tableau dashboard, visit: [View Tableau Dashboard](https://public.tableau.com/views/my_project_17261572432260/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
