# Applied Data Science Capstone Project

This repository is part of IBM Applied Data Science Course Capstone Project which is offered through Coursera.
In this repository, I highlights my approach in analyzing and clustering neighborhoods in the city of Surabaya. 

## Introduction/ Business Problems
In this project, I take a role as an analyst that help hotel managers or owners in deciding which part of Surabaya is the best location to establish a new luxury (5 stars) hotel. Location is the most crucial aspect for hotel owners, because different locations may have different surroundings and venues that also attract different types of travelers. The success of a hotel depends largely on the location of its site. For this reason, hotel owners must carefully decide which parts of the city to choose according to the type and price of the hotel. In order to decide the most appropriate location, there are several factors that should be considered in advanced. For this project, the factor to be considered is the surrounding location offering, such as restaurants, bus line, banks, and so forth. In addition, this project will focus only on the city of Surabaya, as the second largest city in Indonesia and the capital of the province of East Java.

In order to address the business problems, I am going to do the following steps:
1. Analyze the neighborhoods and venues data
2. Visualize each neighborhoods as well as its total of venues in the city of Surabaya on a map
3. Cluster and profile each neighborhoods into 4 different groups
4. Predit the cluster area that is most likely be the best location to setup a new luxury hotel

## Data Section
The data required to solve the problem of deciding the best location to establish a new hotel in Surabaya area are:
1. Neighborhoods' unique code and name  
Data Source: Wikipedia page (https://id.wikipedia.org/wiki/Daftar_kecamatan_dan_kelurahan_di_Kota_Surabaya).  
Description: The Wikipedia page contains the neighborhood basic information in the form of HTML which will be scrapped to get the data.

2. Neighborhoods' coordinates (latitude, longitude)  
Data Source: The neighborhoods data are provided in a CSV file.  
Description: The CSV file contains a dataset of each Indonesia districts coordinate information. So, to obtain data only for the city of Surabaya, a portion of the dataset will be selected.

3. The venues information in each neighborhood  
Data Source: Foursquare.  
Description: By using the Foursquare API, a list of venues can be obtained along with information, such as categories and coordinates.
