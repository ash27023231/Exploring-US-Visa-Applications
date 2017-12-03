# ABOUT THE PROJECT

In this project we have made visualizations by which we can see a trend in the number of Applications filed over the years. This includes mainly few common visas in which maximum people file such as : F1, H1B, L1 etc. so as to show the trend. The designs also tells us about the Economic Sectors in which the maximum number of visa applications are filed. Overall we can infer from the designs what the trend is currently and will be worth reckoning to know more details. Our goal is to make visualizations synchronised with each other so that it’s easy to deduce the learning from it.

## Project Resources

1. [Project Website]()

2. [Screencast]()
 
3. [Process Book]()

## Data Source + Processing

Our Dataset has appropriate data from 2011 to 2016. It also includes information on employer, position, wage offered, job posting history, employee education and past visa history, associated lawyers, and final decision.

The complete link to our dataset is provided below: 
[KAGGLE DATA SOURCE](https://www.kaggle.com/ambarish/eda-us-permanent-visas-with-feature-analysis/data)
 
There were many redundant and duplicate columns present in the original dataset. We took only distinct columns in our final dataset which we plan to use towards our project.
Also, there were many rows which had Null values for some of the attributes/columns. We did not include those records in our final dataset as well.
Moreover, there were many columns in the original dataset which had no data. We did not include those columns as well.We did many data validation checks also on our dataset and chose only those records which had correct values for Dates, numbers in Salary and text in Employer_Name, Country_Of_Citizenship etc.


## Visualization Designs Implemented

 ### MAP CHART

The first chart we will draw is Map Chart. In this ,we are going to show total number of applications statewise displayed by shade of the color. Darker the color it means more is the number of applications in that. Apart from this, we will have a tooltip on each state showing the count of applications shown with a normal bar chart. We can also filter the year using the year wise filter which is placed just above it. Map tells us the number of state-wise applications seen from the first expression.   

2. ###LINE CHART

In this chart, we have apply the ScrollyTelling method which is being implemented to show the number of applications of each Case Status such as Certified, Denied , Certified- Expired with respect to the years from 2011-2016.  We will make sure that lines are being identified individually so we have given a different color to each line with legend showing the text name of that line.

3. ####STACKED BAR CHART

This is our third design in which we will show the data of different economic sectors over 5 years using the stacked bar chart of each case status (Certified, Denied, Withdrawn and Certified Expired). This helps in showing the data visualization for the different sectors as that’s an important attribute to showcase which sector visa is getting Certified ,Denied, Withdrawn and Certified-Expired.

4. ###PARALLEL COORDINATE CHART

This was the last design which we will use to show the data for different attributes at the same particular time and with the use of brush we can easily see the focus on that particular thing which we want to see.

Thank You For Visiting Our Webpage!!!
