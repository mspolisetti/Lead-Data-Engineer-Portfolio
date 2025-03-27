# Data Engineering Leader Portfolio   (In Progress)

Welcome! Within this repository , you'll find a catalog of work I developed/led in various data engineering/architect roles and/or passion projects, each of which covers my top skills and techniques.


#
## Datawarehousing

### [Enterprise-Wide Datawarehouse for Real Estate Investment Management]()
#
For this project, our team set-up data integration from various vendor sources into a centralized data warehouse for a Real Estate Investment Management firm.

Historical Analysis:
By consolidating data over time, Operations/Asset Management teams can track performance trends, Occupancy rates, Renewal Conversions, Net Operating Income, and expenses. This historical perspective is critical for identifying long-term patterns and making informed strategic decisions.

Investor Reporting:
A centralized data repository enabled detailed, data-driven daily emailed reports and dashboards. Reports offered transparency and timely insights, enhancing communication with investors and building trust.

Advanced Analytics:
Combining property management data with property asset data opens the door to a wide range of analytics: Predictive Modeling for Forecast of market trends, benchmark performance against comparable properties, and optimize operational efficiency.

Overall, warehousing data empowered the company to make smarter investment decisions, manage risks effectively, and continuously improve portfolio performance.
![Datawarehousing Architecture](https://github.com/user-attachments/assets/7acdcdfa-3aba-41b2-b747-b9db7aa94442)
#


### [AWS RedShift Datamart from Real Estate data]()
#
Real estate property/investment management firm wanting to track and analyze real-time occupancy trends, Property maintenance requests and turn/rehab patterns from their property management system (running on MySQL) to identify top-performing properties and areas needing immediate attention. By leveraging zero-ETL integration, our team replicated the data from MySQL to Amazon Redshift and build Datamarts for Power BI dashboards for property managers and executives in near real-time eliminating the hours-long delays often associated with traditional ETL processes.
#
![image](https://github.com/user-attachments/assets/e98311d4-7fe5-4645-971d-bff99d52cc60)

### [Datawarehousing - Snowflake Single Source of Truth Warehouse Location Database]()

#### [Location Data Pipeline]()
![image](https://github.com/user-attachments/assets/f6091d6e-56f5-47b6-952c-6d07747111c6)
This pipeline refreshes the location database by integrating new warehouse locations and updating existing features within our location intelligence system. Data is sourced from various internal products, including XRS, ROADNET, LANDMARKS, SYLECTUS, MACRO MESSAGES, and additional sources in the future. Prior to updating the database, addresses are standardized using the SmartyStreets API. The pipeline is deployed on AWS EC2.


### 
# 
### IoT Data / Data Science/Engineering

### [Failure Prediction for Array of Things Sensors](https://github.com/mspolisetti/AoTNodeHealthAnalysis)
The Array of things (AoT) project is an urban sensing project involving collaboration of the University of Chicago, Argonne National Laboratory, and the School of the Art Institute of Chicago. As part of the new Smart Cities Initiative announced in 2015, AoT provides real-time, location-based data about urban environment, infrastructure and activity to researchers and the public. 

The purpose of this project was to develop data-driven evaluation of the existing AoT Node health and explain the various factors affecting Node’s health.  In addition, our team developed a Machine Learning that can predict possible malfunctions based on historical data. 

#
### [Geofence Warehouse using Python, Google Maps API](https://github.com/mspolisetti/geofence)
Project Overview:
The Geofence Project is a Python-based tool that generates geofence boundaries for buildings by processing static map images from the Google Maps API. It leverages image processing libraries (OpenCV, PIL, and Matplotlib) and custom algorithms to extract building contours, apply configurable offsets, and visualize the resulting geofences on a map.
#
### [Geofences for Warehouses using Microsoft Buildings Dataset](https://github.com/mspolisetti/build_geofences)
Geofence Pipeline is a Python-based geospatial data processing project that computes dynamic geofence polygons from building footprint data.

Leveraging Dask for scalable processing and Shapely for geometry operations, the pipeline calculates building areas, applies area-dependent offsets to generate buffered geofences, and integrates seamlessly with Snowflake for data staging and updates. This project showcases efficient handling of large datasets, advanced geospatial computation, and robust cloud data integration.


## DataBricks/ Azure
### [ML model to predict Rent Growth of RealEstate markets in the upcoming year]()

#
### [Data Analysis, Cleaning and Data Wrangling of Oil well dataset]()

#
### [Logic apps, Power Robots, Power BI - Investor Emails]
