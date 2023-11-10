# R-Studio-Data-Cleaning-and-Descriptive-Statistics and Visualisation- Part 1 of 2 of Assignment 


![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/f1572101-954a-474c-9564-e23be93ccff1)


**Assignment 3 on Level 3 Data Technician Bootcamp** 

****Task: ** The task set involves cleaning the data given to us in relation to Hollywood’s Greatest Stories on a R file, visualising data on an R file and the importing into Power BI once the cleaned data has been exported thus creating a dashboard to show the following visualisations**

Step 1- Load the data and file paths and view data
 
![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/a3ce81df-f142-488b-b6ce-e1ea9aaa591a)



**Check data types with str(df)**


![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/0fe13d8f-c05b-4115-955e-d1fc2cea1a2e)

 

**Check for missing values and then drop them:**

![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/91b5937d-120b-4fa2-8904-39d998a53f47)

  
**-as seen in images used df -< na.omit(df) to achieve**


![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/84f886aa-cee7-4590-b447-273cc69cdb09)



****Descriptive Statistics and Visualisations in R Studio** 
**Summary statistics**
Use summary(df) to show the statistics of the dataset in R Studio

![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/ce4171c0-21c7-45dd-aa83-f1d940ca4065)

 
**Use ggplot(df1, aes(x=Lead.Studio, y=Rotten.Tomatoes..)) + geom_point()+ scale_y_continuous(labels = scales::comma)+coord_cartesian(ylim = c(0, 110))+theme(axis.text.x = element_text(angle = 90))
to show a scatterplot**
 
As seen in the image the code resulted in a scatterplot of Rotten Tomato ratings against studio

![image](https://github.com/insights000/R-Studio-Data-Cleaning-and-Descriptive-Statistics/assets/150028138/337d2334-94ac-44b4-b4cf-dd2529ebc2fb)

The final part of the task involved me then importing the cleaned data file onto a new CSV file which could then be imported into Power BI 










