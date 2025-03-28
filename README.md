# Data Engineering Leader Portfolio   (In Progress)

Welcome! Within this repository , you'll find a catalog of work I developed/led in various data engineering/architect roles and/or passion projects, each of which covers my top skills and techniques.


#
# Datawarehousing

#### [Datawarehousing - Enterprise-Wide Datawarehouse for Real Estate Investment Management]()
#
For this project, our team implemented a data integration solution, consolidating information from multiple vendor sources into a centralized data warehouse for a Real Estate Investment Management firm. This initiative achieved the following key objectives:
#
**Historical Analysis:**
By aggregating data over time, operations and asset management teams are empowered to monitor performance trends—including occupancy rates, renewal conversions, net operating income, and expenses. This perspective is essential for uncovering long-term patterns and making well-informed strategic decisions.
#
**Investor Reporting:**
The unified data repository underpins the generation of detailed, data-driven daily reports and dashboards. These insights, delivered through automated email communications, enhance transparency, foster investor confidence, and strengthen stakeholder relationships.
#
**Advanced Analytics:**
Integrating property management data with comprehensive property asset information unlocks robust analytical capabilities. This integration facilitates predictive modeling for forecasting market trends, benchmarking performance against comparable properties, and optimizing overall operational efficiency.
#
![Warehouse Architecture](https://github.com/user-attachments/assets/23683816-a0aa-4f2c-852a-94f56ada6eaf)

#### [Datawarehousing - AWS RedShift Datamart from Real Estate BI & Analytics]()
#
Our team developed a robust BI/Analytics solution—centered around a datamart—for a leading single-family real estate property and investment management firm. This solution enables leadership to track and analyze real-time occupancy trends, property maintenance requests, and renovation timelines. The data is proprietary, collected by the firm's MySQL-based property management system. These dashboards empower management to identify top-performing properties and quickly address areas within the Property Management Team that need attention.

Leveraging a zero-ETL integration approach, we seamlessly replicated data from MySQL into Amazon Redshift and built dedicated datamarts to power near real-time Power BI dashboards for property managers and executives. This innovative solution eliminates the delays typical of traditional ETL processes, delivering timely insights that drive informed decision-making.
#
#### [Bi/Analytics - Real Estate Investment Management]()
#

![image](https://github.com/user-attachments/assets/e98311d4-7fe5-4645-971d-bff99d52cc60)

#### [Datawarehousing - Snowflake Single Source of Truth Warehouse Location Database]()

Developed a single Source of Truth Warehouse Location Database that empowers a truck navigation software company by centralizing all critical location data in one reliable repository. This unified solution offers several key benefits:

**Data Consistency:** Every team accesses the same accurate, up-to-date warehouse location information, minimizing errors and discrepancies.

**Enhanced Route Optimization:** Comprehensive and precise location data enables navigation algorithms to generate more efficient routes, saving time and reducing fuel costs.

**Advanced Analytics:** The consolidated data supports predictive analytics and machine learning, driving more informed decision-making.

**Streamlined Product Development:** A single, reliable data source accelerates the testing and refinement of navigation features, fostering faster innovation and more competitive products.

#### [Location Data Pipeline]()
![image](https://github.com/user-attachments/assets/f6091d6e-56f5-47b6-952c-6d07747111c6)
This pipeline refreshes the location database by integrating new warehouse locations and updating existing features within our location intelligence system. Data is sourced from various internal products, including XRS, ROADNET, LANDMARKS, SYLECTUS, MACRO MESSAGES, and additional sources in the future. Prior to updating the database, addresses are standardized using the SmartyStreets API. The pipeline is deployed on AWS EC2.

# 
#### IoT Data / Data Science/Engineering

#### [Failure Prediction for Array of Things Sensors](https://github.com/mspolisetti/AoTNodeHealthAnalysis)
The Array of things (AoT) project is an urban sensing project involving collaboration of the University of Chicago, Argonne National Laboratory, and the School of the Art Institute of Chicago. As part of the new Smart Cities Initiative announced in 2015, AoT provides real-time, location-based data about urban environment, infrastructure and activity to researchers and the public. 

The purpose of this project was to develop data-driven evaluation of the existing AoT Node health and explain the various factors affecting Node’s health.  In addition, our team developed a Machine Learning that can predict possible malfunctions based on historical data. 

#
#### [Geofence Warehouse using Python, Google Maps API](https://github.com/mspolisetti/geofence)
Project Overview:
The Geofence Project is a Python-based tool that generates geofence boundaries for buildings by processing static map images from the Google Maps API. It leverages image processing libraries (OpenCV, PIL, and Matplotlib) and custom algorithms to extract building contours, apply configurable offsets, and visualize the resulting geofences on a map.
#
#### [Geofences for Warehouses using Microsoft Buildings Dataset](https://github.com/mspolisetti/build_geofences)
Geofence Pipeline is a Python-based geospatial data processing project that computes dynamic geofence polygons from building footprint data.

Leveraging Dask for scalable processing and Shapely for geometry operations, the pipeline calculates building areas, applies area-dependent offsets to generate buffered geofences, and integrates seamlessly with Snowflake for data staging and updates. This project showcases efficient handling of large datasets, advanced geospatial computation, and robust cloud data integration.


## DataBricks/ Azure
### [ML model to predict Rent Growth of RealEstate markets in the upcoming year]()

#
### [Data Analysis, Cleaning and Data Wrangling of Oil well dataset]()

#
### [Logic apps, Power Robots, Power BI - Investor Emails]
