# 3-AirBnb-Analysis
This repository is specifically created for the purpose of showcasing my Data Science Capstone Projects done during my course at GUVI

[!Note]: Since the airbnb sample json data transformation file and Power BI file are too big to upload, a copy of the files are available in my drive. You can view them from the links below: 
- Airbnb Data transformation - [download link](https://drive.google.com/file/d/1Hzq3pNNmGlsQSYPacafGqqp61s4Hnbhv/view?usp=sharing)
- Power BI Analysis report - [download link](https://drive.google.com/file/d/1icXvw0A52epm-sT1OedBbA07-pJG16Z6/view?usp=sharing)

## What is AirBnB:
**Airbnb, Inc.**, is an American company operating an online marketplace for short- and long-term homestays and experiences, founded in August 2008 in San Francisco, California, U.S. by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia. Airbnb is a shortened version of its original name, AirBedandBreakfast.com. The company acts as a broker and harges a commission from each booking.
Learn more about Airbnb: [Click here](https://www.airbnb.co.in/)

## How does AirBnB work:
The idea behind Airbnb is simple: matching local people with a spare room or entire home to rent to others who are visiting the area. Hosts using the platform get to advertise their rentals to millions of people worldwide, with the reassurance that a big company will handle payments and offer other support. And for guests, Airbnb can provide a homey place to stay, perhaps with a kitchen to save on dining out, often at a lower price than hotels charge. Today, the company operates in over 220 countries and regions, including the US, Europe, Australia, and Asia.

## Introduction to Project:
This project is around Airbnb Analysis: delving into the Travel Industry, Property Management and Tourism domain. 

### Tools used:
* Python (VS Code editor used)
* MYSQL
* Streamlit
* Plotly
* Power BI

### Skills:
Python scripting, Data Preprocessing, Visualization, EDA, Streamlit and PowerBI

## Project Steps:
* Pandas: Leveraged the powerful Pandas library to transform the dataset from JSON format into a structured dataframe. Pandas facilitated data manipulation, cleaning, and preprocessing, ensuring the data was ready for analysis.
* MySQL Connector: (Not a mandatory step) Utilized MySQL Connector to establish a connection to MySQL database, enabling seamless integration of the transformed dataset and the data was efficiently inserted into relevant tables for storage and retrieval.
* Streamlit: Developed an interactive web application using Streamlit, a user-friendly framework for data visualization and geo-analysis of the airbnb data.
* Plotly: Integrated Plotly, a versatile plotting library, to generate insightful visualizations from the dataset. Plotly's interactive plots, including geospatial plots and other data visualizations, provided users with a comprehensive understanding of the dataset's contents.
* Power BI: Made use of Power BI's impressive dashboarding tools to better visualise all the data in a single view.

## Overview:

### Data Extraction :
Data extraction involved retrieving information from the 2019 Airbnb dataset, comprising property listings with details such as descriptions, pricing, location, and reviews.

### 🔁 Data Preprocessing & transform:
Utilizing Python, the Airbnb dataset from 2019 underwent transformation and preprocessing, resulting in structured DataFrames. This process involved cleaning, organizing, and preparing the data for analysis, ensuring its quality and usability for insights extraction

### 🗃️ Database Integration:
Mysql connector used for connection between Python and MySQL Workbench database, enabling data transfer. This facilitates efficient querying, simplifying database interactions for Python

### 📊 Data Visualization And Analysis:
With the assistance of Streamlit and Plotly, a dashboard and charts are created, offering geospatial visualizations and top insights. This setup empowers users to explore and reveal trends within the dataset, facilitating insightful analysis.

## Libraries used:

``` python
import pandas as pd
import streamlit as st
import numpy as np
from streamlit_option_menu import option_menu
import mysql.connector as sql
from PIL import Image
import plotly.express as px 
import plotly.graph_objects as go
import warnings
warnings.filterwarnings("ignore")
```

## Streamlit App:
* In the 'Home' section of our project, We have information relating to **AirBnB** - all information on what it is, it's working and chronological development with reference videos to get started with what it is.
  
* In the 'Discover' section, users have the opportunity to explore countries through dynamic geo-visualizations with the country, street and property type filters, supplemented with price, rating insights. Additionally, we have a section below that can provide all the information regarding a particular property drilling down to the host and reviews as well.

* In the 'Insight' section, users can explore the data more with some pre-built charts and graphs. We have also included filters for some of those visuals and interestingly, we have used **st.metrics** for some BI level dashboard experience in streamlit.

* In the 'About' section, we have details on the project as mentioned above.

## Power BI Dashboard:
Power BI dashboard provides interactive visualizations and insights derived from the Airbnb dataset. It allows you to explore various aspects of Airbnb listings, including pricing trends, property types, and geographical distributions.

* Summary (sheet 1)
<img width="593" alt="Summary" src="https://github.com/user-attachments/assets/030f50f3-1f35-410c-aaaa-454fee8ca9c1">

* Charting (sheet 2)
 <img width="593" alt="Charting" src="https://github.com/user-attachments/assets/073b4c7c-0322-4cf5-9a3f-9e71dbd73c6e">


### Contact me:
* Email : sanjuhwork@gmail.com
* LinkedIn : https://www.linkedin.com/in/sanju-hyacinth/
