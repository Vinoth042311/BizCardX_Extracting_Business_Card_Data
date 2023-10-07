# BizCardX - Extracting -Business -Card -Data

## BisCardX is a Streamlit application that facilitates the extraction of information from images. It utilizes the EasyOCR library to recognize text content in the uploaded images and then extracts relevant details such as names, designations, phone numbers, email addresses, websites, addresses, and pin codes

# Developer Guide
## 1. Tools Install
* ###   Virtual code
* ###   Python 3.11.0 or higher.
* ###   PostgreSQL

# 2. Requirement Libraries to Install
* ###  pip install pandas easyocr numpy Pillow opencv-python-headless os re  postgresql-connector-python streamlit:

# 3. Import Libraries
* ### import easyocr
* ### import re
* ### from PIL import Image
* ### import numpy as np
* ### import pandas as pd
* ### import time
* ### import psycopg2
* ### import streamlit as st

# 4. E T L Process
## a) Extract data
* ### Extract relevant information from business cards by using the easyOCR library
## b) Process and Transform the data
* ### After the extraction process, process the extracted data based on name, Designation, Mobile Number, Email, Website, Area, City, State, and Pincode is converted into a data frame.
## c) Load data
* ### After the transformation process, the data is stored in the postgreSQL database
# USER GUIDE

# Step 1. Data collection zone
### Click the 'Browse Files' button and select an image
# step 2. Extract data 
### Click the Extract button 
# Step 3. Create Id and password
### Create new user id and new password 
## Step 2. Data upload
### Click the 'Upload into PostgreSQL' button to upload the data into the Postgresql database
## Step 3. Modification zone
### In this 'Modification zone' you can able to view or update the information also you can able to delete the data





