# Writing-a-Data-Science-Blog
This project entails writing exploratory data analysis for Seattle Airbnb dataset to identify factors that could be determinants of quality of service and pricing

# Motivation
Air BnB has become a popular sourse of short-term stays for modern travellers. Pricing and quality service are critically crucial in an individual’s decision-making process of whether to go with an AirBnB listing. Additionally, these elements are also crucial for hosts in their process of maximizing returns. Having an opportunity to observe the Seattle Airbnb and identify some of the factors that affect listing prices and host service delivery is intriguing.

# Datasets
listings.csv - has all the listings in Seattle including full descriptions and average review score
calendar.csv - contains listing id and the price and availability for that day
reviews.csv - has all the reviews for these listings including unique id for each reviewer and detailed comments

# Libraries needed
#Import libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings
import seaborn as sns
from re import sub
from decimal import Decimal

# Results and Analysis
The AirBnB dataset has different interesting attributes that can identify quality of service of a host and the price of a listing. One of the observation is that whether a listing is made by super-host or non-super-host and the number of reviewers per listing can be used among the factors to determine the price of a listing. On the other hand, reviews per month cannot be classified among factors that can determine the price of a listing. Additionally, the faster the response of a host to a request, the higher probability that the host will offer high quality services.
