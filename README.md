# Cyclistic Bike-Share Member Conversion Strategies
![intro-page](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/0241e714-4ca7-47e6-bd96-3226289cd438)
## DESCRIPTION OF THE BUSINESS PROBLEM
The goal of this project is to find the ways that annual members and casual riders use Cyclistic bikes differently in order to convert more customers into annual members.

## DESCRIPTION OF THE DATA 
The data is located on a website that hosts an index of different datasets for the bike sharing trip data.
https://divvy-tripdata.s3.amazonaws.com/index.html

The data is credible and unbiased and has a data license https://divvybikes.com/data-license-agreement 

This data will allow me to see how many riders are members or casual riders and allow me to determine the different riding behaviors that the two different riders tend to have. The problem with the data is that I will not be able to determine if the casual riders live in the Cyclistic service area or if they purchased multiple single passes instead.

## CONCLUSION
The data shows that in December both casual riders and annual members ride their bikes for a shorter duration than in March. This shows that riders of both types typically ride their bikes for longer in warmer months. The data also shows that casual riders ride bikes longer than riders who are members. This suggests that annual members are using the bikes as more of a means to commute to and from places they are required to be while casual riders are using the bikes more leisurely. The data also shows that both types of riders typically ride for the longest on Sundays. The number of annual members is typically double or triple the number of casual members. During March the most members ride their bikes on the weekends (Sunday, Saturday) and during December the most members ride their bikes in the middle of the week (Tuesday, Wednesday, Thursday). With all this mind I believe the company should have two different strategies to convert more riders to become members. The company should advertise the convenience the bike share service provides for those who need a way to commute to the places they need to be and save money on car expenses. The company should also advertise the benefits of purchasing an annual membership instead of remaining a casual rider. These benefits could include saving money on a one-time purchase versus paying every time you ride, rewards relating to the amount of miles you ride, and other perks. Advertisements should be prioritized during warmer months in the Spring and Summer since that is when more casual riders use the service.

## DATA CLEANING PROCESS
* Since the time data for date and bike times were combined in the same cells for the ‘started_at’ and ‘ended_at’ columns, the data had to be split up into different columns.
* The ‘start_date’ and ‘end_date’ columns were created by using the INT function to separate the data for the date from the bike times.
* The ‘start_time’ and ‘end_time’ columns were created by subtracting the date from the bike times in columns C and D.
* The ‘ride_length’ column was created by subtracting the times in the ‘start_time’ columns from the times in the ‘end_time’.
* The ‘day_of_week’ column was created by using the WEEKDAY function on the data on dates in column C.
#### - Raw March data
![raw-cyclist-data-march](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/b8571f3e-85e9-4892-a397-9e09bf0e7335)
#### - Cleaned March data
![cleaned-cyclist-data-march](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/2de2864a-c2db-49f5-9389-b68cbcb84ba3)
#### - Raw December data
![raw-cyclist-data-december](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/05f50e73-dcff-42ac-ba82-6d50aad0f5c3)
#### - Cleaned December data
![cleaned-cyclist-data-december](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/b967eebd-19a3-42ca-aa9e-893aadfc3c57)


## DATA VISUALIZATION
![who-rides-longer](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/e69b5be7-dcce-4096-8d07-dbdaa39203ed)
![what-days-do-people-ride](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/79150ad3-fc94-4dc5-b40e-a283b9201d2e)
![what-days-do-people-ride-most](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/3f0fb58d-9b9d-48d6-a91f-2f71c2105a37)
![why-do-members-ride](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/b4ad5c9c-b61b-48cc-8385-b93d9c8fe477)
![why-do-people-ride-casually](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/17292a99-5645-4ad9-8ebe-6f2b5dc63401)
![strategies-to-convert-members](https://github.com/dwhite256/Cyclist-Bike-Share-Company-Analysis/assets/170587320/8c4a3481-e99b-416d-8f0b-4d16a52f9ceb)




