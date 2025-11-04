# Indian-Air-Quality-ETL-Project
This project is a Data Analyst Workflow from extracting Data of multiple sources to analyse the content.
The goal is to extract, transform and load data. The Power BI Dashboard and the Analysis is to complete the Workflow, but remains in the background.
The project is about pollutants in the Air to analyse the Air Quality. The decision for Carbon monoxide and India was made through SQL queries using BigQuery.
INFO: As I mentioned the important part is the ETL-Process, there is a gap in the data from 07/2020 to 01/2021 and the two data source could have a different conversion system what explain the fast raise from 2020 to 2021

## Project Overview
- **Type**: Data Analysis with Python
- **Datasets**: Air Quality Data in India (2015 - 2020) from Kaggle/     
                AQI Data of India (2021-2023) from Kaggle/     
                bigquery-public-data.openaq.global_air_quality from BigQuery
- **Language**: Python
- **Libraries**: Pandas, NumPy
- **Tools**: Cleaning script

## Workflow
### Extracting Data
First of all checking for informations in BigQuery with SQL Queries 
-> Carbon monoxide(CO) has the highest value in the Air
-> India produced the most CO
Then getting this information to strengthen my decision as a dataset
Searching for datasets to analyse the CO in India

### Transform Data
Joining the datasets together
changing the date format to get a better view of this data
cleaning the datasets

### Load Data
After joining the data together I save them as an excel-file, due to missing seperators as csv-file
changing the other files and load them into Power BI

### Creating a Dashboard in Power BI
Choosing my SQL results as bar charts to underwrite my decision
Using a line chart to analyse the changing by time
The Cards-KPI shows the total value of CO emissions in a range giving from the slicer
I choose a Card-KPI with multiple rows to show up the total amount of CO emissions by year instantly

### Data Analysis
CO damaged the Air Quality the most
Especially in India CO is a big Problem
From 2015 to 2020 the amount of CO in India rised up
From 2021 to 2023 the CO in the Air is lowering
The highest value from 2015 to 2020 is two times higher than the lowest value -> 163,56 and 349,67
In 2021 the value is 2132 as highest and the lowest in 2023 with 1909,97

## Structure
README.md
LICENSE
Indian-Air-Quality/
│
├── Dashboard/
│   ├── Analyzing_Screenshots/
│   │   ├── Dashboard_from_2015_to_2020.png
│   │   └── Dashboard_from_2021_to_2023.png
│   └── Indian_Air_Quality_Dashboard.pdf
│
├── Getting_Data/
│   ├── Python_Scripts/
│   │   ├── cleaning_script.py
│   │   └── india_air_quality_etl.py
│   └── SQL_Queries/
│       ├── Country_with_highest_amount_of_CO.png
│       └── Highest_amount_of_pollutant.png

## My path
I learned more about Pandas and the work with multiple data and data of other sources. I learned something about licenses and Use Policy. 
For the first time I used multiple sources and datasets. Also the complete ETL-Process was my first time.
In addition it was my first time including my SQL-knowledge in a project and using it in a useful way.
What I learned:
- The ETL-Prozess
- Working with keep looking on Licenses and Use Policies
- Using SQL in a useful way
- Working with multiple data sources and datasets is not that easy like using one dataset
- The whole process from getting data to analyse my found information
