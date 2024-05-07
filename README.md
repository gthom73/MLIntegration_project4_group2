# Machine Learning
KU-VIRT-DATA-PT-11-2023-U-LOLC-MWTH

# Overview

Analysis of USA Real Estate Dataset (2.2M+ listings from Kaggle.com) 
For businesses, employees and people looking to move their permanent residence location, it is important to know and understand the cost of purchasing a home in the new location. Often times, wages/salaries may be similar, between locations. However the cost of housing maybe considerably different depending on where you live. At HME Inc., business owned by Jon Haas, there are times where employees are moved to different branch locations due to needs at the branch. We wanted to see if we could create a model using Machine Learning that can predict housing prices based on certain features of a house (such as number of bedrooms, city, state, zip code and house size) so that the employee can decide what fits their needs. The headquarters of HME Inc. are located in Topeka, KS with satellite offices located in Denver, CO, Kansas City, MO, Kansas City, KS, and Dallas, TX. These are the cities that we filtered our data to look at in order to find the right zip code for our relocated employee(s).

# How to Navigate Through the Data 
project_4_datamanipulation.ipynb
 - This file is where it all starts - this shows how the data was manipulated so that we could use the features deemed important and necessary to train our model. In this file you will find what columns were used, what cities we needed to look at, and graphs showing pricing averages.
 
Project_4_ML.ipynb
- In this file, you will find the manipulated data. Data was fine-tuned so that we could use multiple model learning techniques in order to create the most accurate prediction of housing prices within a zip code. Graphs are shown to see which model worked best.
 
testModelsBy_zip_and_city.ipynb
- To use this file, you must use your own Kaggle username and password to see the dataset. The dataset used is updated every 7-8 weeks - by using the API key, this means that predictions in this file are updated as well. Once entered, you can run all cells and then scroll to the bottom. Here, you will find a dropdown menu for dataset (filtered by city and state), as well as a dropdown that houses zip codes associated with that specific dataframe. This is how you can change which city and zip code is more appeasing to you as the employee. You can also change how many bedrooms and square feet you are looking for in the same cell under the comment "#Prediction". Use this piece to help you choose what is best!
** This code takes approximately 7 minutes to run

Tableau Visual
- Lastly, you can click on the link below to see where each zip code is in the city you are thinking about living in. Each city shows the poverty rate and average price of housing within a zip code. Use this to your advantage to see if this is an area you would like to live in.
[Tableau Visual](https://public.tableau.com/app/profile/hilari.waters/viz/Project4_Viz/AvgPricebyZip)

project_4_slide_deck.pdf
- Check out this PowerPoint .pdf to see what was presented.

# Data Sources
* https://data.census.gov
* https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset
  
