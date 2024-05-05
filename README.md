# BigData_FinalProject
## Project Overview
This project is developed as part of the Big Data course (CSGY 6513-D) by Hao Wu, Yanliang Chen, and Huatian Pang. The main goal of the project is to harness big data analytics and machine learning to improve traffic safety in New York City by analyzing motor vehicle collisions. Using the comprehensive Motor Vehicle Collisions - Crashes dataset, which includes over 2.07 million police-reported incidents, the project focuses on spatial and temporal dynamics of traffic crashes, identifies critical contributing factors, and predicts crash severity.

## Project Objectives
- **Spatial and Temporal Analysis:** Analyze the geographic distribution and temporal patterns of traffic crashes to identify crash hotspots and high-risk times.
- **Contributing Factor Analysis:** Identify and analyze prevalent contributing factors to traffic crashes.
- **Prediction of Accident Severity:** Develop machine learning models to predict the severity of traffic accidents.
- **Future Accident Trend Prediction:** Utilize analytics to predict future traffic accident trends and provide insights for proactive safety measures.

## Notebooks Description
The project is divided into multiple parts, each handled in separate Jupyter notebooks:

1. **bigdata_project_part1&2.ipynb**
   - **Content:** This notebook covers the initial data processing, exploratory data analysis, and spatial analysis of the crash data. It provides insights into the distribution of accidents across different boroughs and identifies key hotspots.

2. **bigdata_project_part3.ipynb**
   - **Content:** Focuses on temporal analysis of accidents, examining patterns over different time scales (daily, weekly, monthly) and during specific high-risk periods such as holidays and rush hours.

3. **bigdata_project_part4.ipynb**
   - **Content:** Develops predictive models using machine learning techniques to forecast accident severity and predict future trends. This notebook also explores the correlation between various factors and the severity of accidents.

## Data Source
The analysis is based on the 'Motor Vehicle Collisions - Crashes' dataset from NYC Open Data. Download the dataset from [here](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data) and place it in the root directory of the project folder.

## Technologies Used
- **Data Processing and Analysis:** Apache Spark, Spark SQL, PySpark, NumPy, Pandas
- **Machine Learning:** Spark MLlib
- **Data Visualization:** Matplotlib, Seaborn
- **Programming Language:** Python

## Setup and Installation

To run these notebooks, you will need to have access to the following datasets, :

1. **Motor Vehicle Collisions - Crashes**: This dataset contains details about every motor vehicle collision in NYC reported by the police through the NYPD's TrafficStat reporting system. Please download the dataset from [here](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data) and place it in the root directory of the project folder.

2. **NYC Zip Code Tabulation Areas Polygons**: This geospatial data is necessary for mapping and geospatial analysis. It provides the polygon shapes of NYC zip codes and can be used to overlay collision data geographically. This dataset is included in this repository.

### Prerequisites

- Google Colab
- Access to Google Drive (for data storage and direct data reading in Colab)
- **Python Installation:** Ensure Python 3.6 or later is installed. Download from [Python.org](https://www.python.org/downloads/).
- **Library Installation:** Install required Python libraries using pip:
  ```bash
  pip install pyspark numpy pandas matplotlib seaborn
