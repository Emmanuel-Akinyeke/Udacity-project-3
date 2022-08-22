# Udacity-project-3
Exploratory and Explanatory analysis of forGobike system data for 2019-02 


The Ford GoBike system dataset provides anonymized, timestamped data about the start- and end- station for a bike, the user type (subscriber or casual rider), as well as some customer-reported attributes like birth year and gender.
The dataset used in this exploration consist of the dataset from San Francisco Bay Area, CA alone. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

## Dataset

> The 2019-02 Ford GoBike system dataset provides anonymized of information regarding the members in San Francisco Bay Area, CA alone. the dataset consist of 183412 trip entries with 16 attributes. The attributes recorded in the dataset includes members birth year, start stations , trip durations, bikers id etc.



## Summary of Findings

> In the exploration, I found that there was a strong relationship between the user type and trip duration. The relationship possed by the user types cut across the users age, gender and trip duration. The distribution of members trip duration appears is fairly symmetrical(at least as symmetric as a real data set). This values stated expressly that majority bikers in San Francisco Bay Area, CA have a tendency towards using the bikes for a more than 10 minutes. The effect of start and end stations on trip duration are relatively equal seeing that the distribution are almost equal. for further informations, this feature need to be investigated further.
Over 70% of the member are between the age of 19 and 45 years of age and this distribution of members has higher trip duration. we can also see that most of the ride with higher trip duration occured during the week(on thursday). As opposed to my prediction, an average female tend to embark on long trip duration(i.e over 9 mins) while members in male category tend to be lesser.
I verified the effect that the user type, start period and members has on the trip duration. in all cases, The user type has the strongest effect on the trip duration.


## Key Insights for Presentation

> For presentation, i focused on the main variables of interest(membera age, user type and start period). To start with, i introduced the members age distribution followed by the categorical variable that has strong influence on the trip duration. i left out  most of the intermediate derivations seeing that they need further explorations. i ensured that the main factors affecting the trip durations we're visible. this i achieved using a logarithmic scale and appropriate plot types and limits.
