# Bikesharing
 
# Overview of Project

Here is the list of deliverables:

Deliverable 1: Change Trip Duration to a Datetime Format
Deliverable 2: Create Visualizations for the Trip Analysis
Deliverable 3: Create a Story and Report for the Final Presentation


The tools we will be using are Anaconda, Pandas, Jupyter Notebook, Tableau.  

Specifically,

The files we will be using are :

- 201908-citibike-tripdata.csv from online data source
- NTC_Citibike_Challenge.ipynb from coursework
- NEWcitibike1.csv from export generated from Pandas

# Overview of the analysis

Create a set of visualizations in Tableau to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

# Results & Visualizations 

1.The data in the "tripduration" column is converted to a datetime datatype
![D1](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D1.PNG)
1.a) The DataFrame is exported as a new file without the index column
![D1a](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D1a.PNG)

2.This is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour 
![D2](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D2.PNG)
2.a) This is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender 
![D2a](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D2a.PNG)
2.b) This heatmap is created showing the number of bike trips for each hour of each day of the week
![D2b](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D2b.PNG)
2.c) This heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
![D2c](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D2c.PNG)
2.d) This heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
![D2d](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D2d.PNG)

###[link to dashboard](https://public.tableau.com/app/profile/leslie.debassige/viz/Challenge-BikeSharing/Story1?publish=yes "link to dashboard")

# Summary 

### What can you conclude about the outcomes?
![D3](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D3.PNG)
The customer dynamics are that there are two types of customers, one being subscribers, and the other regular customers. The customers of Citi bike bikeshare, are prodominatly men while only 25% are female and the rest are unknown. The unknown customers are perhaps not choosing to indentify or they are bikes that customers purchase for their friends or family. Subcribing Men are renting every day of the week more than Women, and mostly on Wednesdays. However customers are mostly unknown gender, and renting predominatley on Saturday and Sunday. This could be due to tourisum or family purchasing with one buyer.The starttime of the rentals are mainly during 4 and 7 PM, which may indicate commuters; people traveling to and from work, or the city.  
![D3a](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D3a.PNG)
The top starting Locations and ending locations are very similar, and since they are mostly subscribers, this would mean that bikeshare is likely used for communiting to and from work. While there is some variation they are not from off from eachother.   

### What are some limitations of this dataset?

![D3b](https://github.com/735713038455163/Bikesharing/blob/master/Screenshots/D3b.PNG)
There are some problems with the data, interms of birthdays, which may indicate the need to be cleaned. The data of dates that are from 1880 - 1920 are impossible, or they might be data entry errors. The age by trip graph indicates that the avg trip is 1k, and as the age increases there is a negative coorlation whereby there is a decrease in kilometers as they age. The bike repair graph indicates that there are a number of Bikes with the same ID, which is listed in the data set as a number, versus a string. This may need to me reviewed further. Bike utilization indicates that there are a number of bikes with a large amount of trip duration, however that my need to be further reviewed as the untins are not identified and with the Bike IDs not listed as a string, ithe data is likey added up versus uniquely identifying.  

