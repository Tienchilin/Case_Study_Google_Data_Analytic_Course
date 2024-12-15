# Case_Study_Google_Data_Analytic_Course
This is case study 1 in the Google Data Analytics Capstone: Complete a Case Study
## Scenario
I am a junior data analyst at a fictional bike-share company in Chicago. The director believes that future success depends on maximizing the number of annual memberships. Therefore, the task is to understand how casual riders and annual members use bikes differently.
## Data
[The previous 12 months of trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) is under the [license](https://divvybikes.com/data-license-agreement). This is public data that we can use to explore how different customer types are using our bikes. But note that data-privacy issues
prohibit us from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the service area or if they have purchased multiple single passes.
## Work in R
The approach in R is as follows:
* Joined these datasets by rows and transformed the date time for analysis. 
* Calculated the riding duration to clear all the bad data that contained negative values. 
* Verified the rider type that should only contain "member" and "casual". 
* Calculated the number of trips and the average riding duration during a week, both monthly and throughout the previous year.
* Visualized both in R and export results for Tableau.
For more details, please check the [RMarkDown](R_for_case_study/case_study_1.Rmd) file.
## Visualization in Tableau
After the data analysis in R, the results are put into Tableau for visualization. Currently, there are two versions: [Analysis result throughout the previous year](https://public.tableau.com/app/profile/tien.chi.lin/viz/Case_study1_17342928667420/Weekly_Num_Ride_by_Year) and [monthly analysis result](https://public.tableau.com/app/profile/tien.chi.lin/viz/Case_study1_17342948870680/Dashboard).
