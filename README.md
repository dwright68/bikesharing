# bikesharing

## Project Overview

The purpose of this project is to put together a business proposal for a Citibike like product in the city of Des Moines, Iowa.

### Resources

The below analysis is accomplished using the following tools and data: 

 - Tabluea Public
 - Citibike Rideshare Data [(publically accessible here)](https://s3.amazonaws.com/tripdata/index.html)
 - Pandas For Some Small Data Conversion


## Findings

See the following dashboard for a broad overview of the topics being discussed here
[Tableau Dashboard](https://public.tableau.com/app/profile/destin6675/viz/Citibike_16385650714340/NYCCitibike?publish=yes)

![Dashboard](https://user-images.githubusercontent.com/88564212/144672868-4e54dee2-7d3b-4517-85ef-06eb5c9ae389.png)


Using the information above we can identify a few key points: 

### Southern Manhattan Traffic
We can see that southern Manhattan has the highest usage. High tourist traffic may be a contributor to this.


### Subscriber vs Customer Count
While tourist traffic may be a contributing factor to high usage, we can see that the majority of traffic in driven by subscribers. 

### Peak Hours
The main peaks we see are at 7 AM and 5 PM, showing that commuters are frequently using thesse. Commuters can prove to be a massive recurring revenue stream. Additionally the hours between 1 and 5 AM see the lowest usage time, identifying a prime to to take bikes out of services for maintenance. 


## Usage By Gender

Below we can see overall checkout times for all users and then a comparison of the same time frame broken down by gender. 

![checkout time](https://user-images.githubusercontent.com/88564212/144675312-455c37ba-8b13-4ada-8edc-a5c48c6a830f.png)

![Checkout time gender](https://user-images.githubusercontent.com/88564212/144675325-4b02358a-98bf-4fb1-8b4e-62fe07464ea4.png)

We can see in the info above that the overall usage is dominated by Males. This trend is persistent throughout the day.


## Usage By Day

Below is a heatmap indicating the overall usage by hour for each day of the week. 

Here we can see that that during the normal work week The most popular times are during commuting huors. On weekends there is a general uptick in usage starting at 9 AM and slowing down around 7 PM. 

![heatmap weekday](https://user-images.githubusercontent.com/88564212/144676050-c387c100-b23c-4af9-9cd9-cdf356bf6dd6.png)


Using the heatmap below we can see that it confirms the usage information per gender as mentioned above. Men and Women see peaks at the same times, but men are using these far more. 
![heatmap gender](https://user-images.githubusercontent.com/88564212/144676194-0c8893dd-a7c2-46ce-8b90-5f40d30af026.png)


Using the final heatmap we can see that the bulk of usage on each week day primarily comes from subscribers, indicating a strong recurring revenue stream.

![heatmap weekday](https://user-images.githubusercontent.com/88564212/144676544-5c9c0698-4c49-479b-a3ce-f8ec0cbb91aa.png)

