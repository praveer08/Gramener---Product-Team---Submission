# Task Assignment-


## Python Programming Assignment 

### Q1>

In 1st part of Q1  we use set property and form set of unique elements of both list and take intersection of both set .

In 2nd part of Q1  we use set property and form set of unique elements of both list and subtract set2 from set1 .

### Q2>

I have imported datatime library and run a loop for year_range and check whether this year is leap or not and if not leap we check last day 
and if it is thrusday we add 1 to 52 because there are 52 weeks in a year and if it is a leap year then i check last two days and 
if it is thrusday any day we add 1 to 52 

## JavaScript Programming Assignment 
 
 I have used filter filter function for this array and pass 0 to filter.

## Data Analysis Case Study 

First we import following library :

(a) Numpy - For array, Matrix and common calculation.
(b) Pandas for reading csv files and to store data in datframe.
(c) Matplotlib for Ploting of data for better Visulation
(d) GeoPandas for reading ShapeFile(.shp) file for reading location to plot map

Here i use ggplot for plotting and figure sie as (10,8)

After this we read data and and store data in dataframe .

then we furter print first 5 head rows and desribe its all column and its data type .

Then we find Categorical columns and we focus on our Case Study.

### 1st Case Study : Create a geographic map of states with low literacy rates.
 For this first we group our data using State Column and use groupby function for this and sum all values of literate people and then
 calculate total population data of each state and divide first column with second column to get %Literacy rate.
 
 After this we read location data from shape file and plot intensity map of india with state boundry and intensity propotional to Literacy rate
 
 ### 2nd Case Study : Most similar districts in Bihar and Tamil Nadu. Similarity can be based on any of the columns from the data.
 For this problem we have selected a single parameter and calculated the absolute difference between each districts of the given parameter. Further we 
 found the minimum of this difference, store its index and displayed the resulting districts as tuples.
 
### 3rd Case Study : Mobile Penetration Variation with regions (districts or states) with high or low agricultural workers

Here in this method In worker_phone_corr() method we  find correlation between Agricultural_Workers number and number of mobiles phones for 
each region in state and pass them in corr_mat_plot method and plot map and visulise correlation between them using intensity plot.
This Intensity show which Region have more corelation between between Agricultural_Workers number and number of mobiles phones they have.


### Extra Case Study

Here we implemented a method state_demography() with takes a parameter 'state' which is state name and do bar 
plot of % of each religion which live in that state 

Here we implemented a method religion_propotion() with takes a parameter 'val' which is index corresponding Religion Name which is mentioned 
above function and corresponding to this i have plotted Map intensity which shows % of Particular Religion in india.
