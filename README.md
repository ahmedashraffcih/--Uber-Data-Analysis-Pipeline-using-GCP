# Uber Data Analysis Pipeline using GCP


## 🪄 Introduction

This project focuses on performing data analytics on Uber data using various tools and technologies within the Google Cloud Platform (GCP) ecosystem. The project utilizes GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio to achieve the data engineering objectives.

## 👏 Project Goals

The main objectives of this project are as follows:

- Perform data analytics on Uber data
- Build a data pipeline for data transformation and integration
- Store the transformed data in Google BigQuery
- Visualize the data using Looker Studio for insights and analysis

---

## 💿 Project Datasets:

TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

---

## Architecture 
<img src="/imgs/architecture.jpg">

---

## Data Model
<img src="/imgs/DataModel.png">

---
## ⚡ Project Steps

1. Understanding the Data:
   - Analyze the Uber dataset and handle any special cases or considerations.

2. Loading CSV Data into Pandas DataFrame:
   - Load the Uber dataset into a Pandas DataFrame for easy data manipulation and analysis using Python.

3. Creating a Data Model:
   - Design a data model to represent the relationships between different entities within the dataset.

4. Data Transformation:
   - Perform various transformations on the data, such as adjusting data types, removing duplicates, resetting indexes, reordering columns, and mapping specific fields.

5. Creating Dimensions and Fact Table:
   - Based on the data model, create dimensions and a fact table to facilitate efficient data analysis and reporting.

6. Uploading Data to GCS:
   - Upload the transformed dataset to Google Cloud Storage (GCS)

7. Deploying Mage Data Pipeline:
   - Deploy Mage, an open-source data pipeline tool, on a Compute Engine instance to automate the data transformation process.

8. Building the Pipeline in Mage:
   - Construct a comprehensive data pipeline in Mage to orchestrate the required data transformations and integrations.

9. Loading Data into BigQuery:
   - Load the transformed data into Google BigQuery, a scalable and flexible data warehousing solution within GCP.
<img src="/imgs/BQ.png">

10. Visualizing Data with Looker Studio:
    - Utilize Looker Studio, a powerful data exploration and visualization tool, to create intuitive and insightful visualizations of the Uber data stored in BigQuery.
<img src="/imgs/Dashboard.png">

---

## 🔧 Tools and Technologies:
- Python 3.
- Jupyter Notebook.
- GCP: Google Cloud Storage, Compute Engine, BigQuery
- Mage 

----

## 📜 Resources
* [Uber Dataset](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
* [Uber Data Analytics | End-To-End Data Engineering Project](https://www.youtube.com/watch?v=WpQECq5Hx9g)
* [Mage Data Pipeline](link-to-mage) for the open-source data pipeline tool used.

---
## ✨ Contribution

Contributions and feedback are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.


To contribute to this project, see the GitHub documentation on **[creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)**.

---

## 👏 Support

Give a ⭐️ if you like this project!
___________________________________

<p>&copy; 2022 Ahmed Ashraf</p>
