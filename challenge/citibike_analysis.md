# Bootcamp: UCB-VIRT-DATA-PT-03-2020-U-B-TTH

## Bootcamp Challenge #14 - 6/14/2020
Bootcamp Challenge 14: NYC and Des Moines Citibikes Bikesharing

## Data Used
- [NYC Citibikes ridesharing data](https://www.citibikenyc.com/system-data)
- [NYC McDonalds](https://courses.bootcampspot.com/courses/140/files/38364/download?wrap=1)
- [Des Moines McDonalds](https://courses.bootcampspot.com/courses/140/files/38414/download?wrap=1)

## Challenge Description
**Objectives**
- Display data professionally and accurately.
- Professionally style a Tableau story.
- Utilize previously created Tableau worksheets to create a new story.
- Create a Tableau story based on starting a bike-sharing company in Des Moines.

## Challenge Questions raised
1. How does the Population of Des Moines compare to NYC, will the population make a difference in ridesharing?
2. What is the gender diversity of Des Moines as compared to NYC
3. What is the density of McDonald's in NYC and Des Moines, will this affect the ridesharing business?

## External Sources Used
1. [NYC McDonalds](https://www.census.gov/quickfacts/desmoinescityiowa)
2. [Des Moines McDonalds](https://courses.bootcampspot.com/courses/140/files/38414/download?wrap=1)
3. [Des Moines Census Data](https://www.census.gov/quickfacts/desmoinescityiowa)
4. [Des Moines Tourism Website](https://www.catchdesmoines.com/things-to-do/)
5. [NYC Citibikes ridesharing data](https://www.citibikenyc.com/system-data)

## Link to Public Tableau Story
- [Citibikes Tableau Story](https://public.tableau.com/profile/paul.bryzek#!/vizhome/nyc_citi_bike/DesMoinesStory?publish=yes)

# Written Analysis

To provide our potential investors with the summary of our data analysis whether or not it is advisable to invest in ridesharing in Des Moines, we will first take a look at all of the data presented page by page in the Tableau Public Story, providing our trusted investors with the data required to come to our conclusions. We will begin by takiing a deep dive into the bikesharing data provided free online from citibikes for New York City. Then we will analyze how Des Moines compares to New York and finally the conclusions that can be reached using data for our premises.

### Tableau Story Page 1: NYC: Top Starting Locations
The first page in our story originates from the citibikes data source. I utilized Tableau's map feature to display the longitude and latitude of all the various starting stations on a Map layer, displaying the various starting locations for the bikes as a dot within the various borough of New York. I utilzied the Map Layer to display the population density as distributed across Zip Code using a Temperature Diverging color scheme. I utilized the Station Name in the Pages functionality of Tableau to all the user to either click through or allow Tableau to play through each dot to provide a case by case analysis of where each station is located. What becomes immediately apparent is that every single starting station in the NYC region is found within a zip code that represents the densest population category: 18,000-123,000. This shows that NYC is a very densely populated region and thus every station is within a location that has high traffic and high visibility so a lot of people have access to every station.

### Tableau Story Page 2: NYC: Top Ending Locations
The second page shows the destinations for where the rides finished. This map effectively shows the same details as Page 1 but with perhaps a bit more of a distribution to locations farther away from Manhattan itself such as New Jersey and Queens. For the most part, the two maps are indistinguishable and indicate that the ending locations for all the bikes are within the most densely populated areas that the map allows.

### Tableau Story Page 3: Citibikes Utilization
Page 3 is a fascinating graph showing with a variety of circle sizes how many seconds were put onto each bike. In NYC, we can observe that many individual bicyles have put more than 3 million seconds on them, while the more modest instances still boasting over 100,000 seconds. From an investor mindset, this is great news - a single bicycle can serve the public for millions and millions of seconds, not bad for a vehicle that is low in price and maintenance.

### Tableau Story Page 4: Bike Repairs
This page presents in a beautiful fashion the distribution of all bicycles utilized in the data sample set. The legend immediately shows us there is a range from a min of 1 to 479 rides per bike. We utilized Tableau's functionality to adjust each square to be a size proportional to the number of rides, and also it's blue hue proportional to the number of rides. When analyzing the overall cost and ROI of each bicycle, it is imperative to know the number of rides that can be expected from each bicycle, and also identifying the bikes with the highest number of rides will inform us which are most likley to need repair and maintenance. Highlighting the middle entries indicate that the median number of rides in the citibikes used in NYC is around 175 - again not bad for a vehicle that has a relatively total cost of ownership.

### Tableau Story Page 5: NYC: August Hours - Ride Distribution
This page displays a bar graph of how many rides occurred at each hour of the day through the month of August in NYC. Due to the high density of NYC, we can see that even at the hour with the fewest rides, 4am, there were still over 5,300 rides through the month! NYC shows that throughout the month, the most popular times to ride were 8am and then between 4pm and 7pm. This data makes sense since there could be a subset of the population using the bikes to get to work (8am datapoint), then using the bike after work either to get home or for recreational purposes, displayed by the larger dataset between 4pm and 7pm. The most popular time to ride was at 5pm with nearly 225,000 rides in the month. The data shows a dramatic dropoff in usage starting at 8pm and not really picking up to the daytime strides until 8am. Knowing the utilization is critical as we can determine the best time to schedule maintenance of the bikes between  3am-4am, and even 1am-2am provide a good opportunity to perform maintenance with minimal impact to the users.

### Tableau Story Page 6: NYC: Average Trip Duration
The page displaying in an area chart the distribution of average trip duration as related to the birth year of the rider. The dataset contains birthyears from 1880 to 2000. The birth years starting from 1880 are questionable and lead me to think that either there were a few outliers of very senior bike riders that still enjoy their time on a bike, or that the user's entered in incorrect information. Starting with Birthyears at 1930, we can see a general positive correlation that younger users tend to use the bikes for a longer period of time. We see a spike with users born around 1970, then with the other users peak with birthyears after 1990. From an investor standpoint, its important to understand which user group is most likely to enjoy the product the most and thereby allowing our marketing team to focus in on that segment - in general we can see that the 18-65 age group is most likely the best segement to target.

### Tableau Story Page 7: NYC McDonald's
The significance of a McDonald's location is that there is a lot of analysis, strategy, and care put into the determination where a McDonald's location will be allowed to exist. They are only found in locations that sufficient traffic that will increase the probability of having a successful franchise. They are often found at traffic intersections and corner locations to maximize the traffic that flows by. In general you would not expect to find a McDonald's in the countryside that does not have a dense population base or a lot of drive by traffic. We can say that if an area has a lot of McDonald's in its area, that its likely has a strong traffic flow that could make for potential good candidates for other businesses including bikesharing. This map shows most of the McDonald's to be found in the most densely populated zip codes withonly a few exceptions in New Jersey and a couple in NYC with the 2nd most densely populated zip codes. The locations in the 2nd most densely populated are off of major freeways and in locations that definitely have a lot of traffic passing through.

### Tableau Story Page 8: Des Moines McDonald's
Comparing the McDonald's distribution in Des Moines shows an encouraging sign: nearly the same number of McDonalds franchises as NYC, almost all in the most densely populated color segment, with the remainder found in the 2nd most densely populated regions. This map immediately shows us that Des Moines is not a countryside locaiton without any traffic because then McDonald's franchisees would not be invested in the location. This map gives a good idea of where the busiest parts of Des Moines are expected to be with a combination of population density and expected flow of traffic.

### Tableau Story Page 9: NYC Des Moines Population
This dataset was acquired from the Census Data Website listed above. The top charts show NYC's population as compared to Des Moines, population per square mile, and land area. We can see that NYC wins in all 3, population 8M+ vs 214k, 27,013 people /sq mile vs 2,516 people/sq mile, and 302 miles vs 80 miles. This is no surprise as NYC is the most densely populated city in the US but the numbers are telling, clearly more people per mile and more people overall should lead to more utilization of bikes in NYC and more people having access to them. On the other hand, Des Moines has a small land area than NYC, this is perhaps a good thing for bikesharing as people can cover the entire city with ease as compared to the many miles in NYC.

The bottom part of the page shows the populate density as acquired from the Census. Here we see the percentage distribution of population under 5, population under 18, population betwen 18 and 65, and population over 65. There are some minor differences between the two cities, but overall the distribution in the age groups are more or less the same between the two. Importantly we see the most valuable segment for bikesharing (18-65) is 59% for NYC and 57% for Des Moines, indicating that Des Moines has the population segment to have a successful bikesharing company.

### Tableau Story Page 10: NYC vs Des Moines Gender
The top pie chart show the distribution of gender for the data obtained from the citibikes CSV. The trend is obvious, the majority of riders are Male with nearly 3 times as many males as females. Note, there is a significant chunk of users that are unknown from the data so their gender can not be determined. Even if all the unknowns were female, its clear that males were still the predominent force for bikesharing.

The charts below compare the gender distribution for NYC and Des Moines as obtained from the Census Data. We can see the distribution is nearly the same NYC has 52.3% female compared to Des Moines with 50.8 and likewise the male distribution was very similar in the two cities, but Des Moines actually boasted a higher male distribution than NYC. As the breakdown of ridesharing data shows Males to be the more frequent user type of bikesharing, as Des Moines has a higher percentage of Males, it shows that the gender distribution is in its favor for a bikesharing company.

### Tableau Story Page 11: NYC vs Des Moines Average Travel Time
This page compares the average travel time to work as obtained from the Census data between NYC and Des Moines. We can see Des Moines average travel time is much lower than NYC's (19min vs 41min). This is important to know how far people are traveling to work, if they are traveling a shorter distance then perhaps given the opportunity to ride on a bike they are more likely to take it.

### Summary
Through the Tableau story, we learned many important items about Des Moines and the opportunity for a bikesharing branch. The first obvious conclusion is that Des Moines is a much smaller, less densely populated area than NYC. We see that Des Moines has a shorter time to travel to work, with a higher percentage of Males, and about the same percent distribution of age groups, in particular the 18-65 age group which are the most frequent user of the bikesharing. We also saw the most popular time to ride in NYC in August was 8am, and 4-7pm after work hours. From the NYC data we see that bikes have a long utilization time and we see the best hours for maintenance was between 3am-4am. The McDonald's distribution was encouraging for Des Moines, with about as many franchies as NYC - showing that Des Moines is indeed an urban area with a lot of traffic flow. For a bikesharing program to be succesful in Des Moines, we would need to be realistic, since there are far fewer people than NYC, it would require far fewer bikes to serve the population. Also the placement of the bikes would need to be carefully calculated, just as the placement of the McDonald's are carefully evaluated to be in key locations with a lot of traffic. Since the average travel time to work is relatively low in Des Moines, it provides a good evidence that people could utilize the bikes to travel to work if given the chance. There may be a lower overall profit expectation to run a bikesharing business in Des Moines, but at the same time, a lower maintenance cost and overall complexity of running a successful business there than compared to NYC. Likewise there would be lower competition and barrier of entry. As we can see from the Des Moines tourism website, people love to be outdoors in Des Moines so long as the temperature permits. There are definitely cold months from Nov-Feb which would have an expected impact on number of riders - these would be optimal months to perform massive maintenance on the bikes if needed. On a day to day basis, we would use the lower usage times(3am-4am) to do the maintenance. Overall the bikesharing can be successful in Des Moines, but must be held with a grain of salt not to expect the explosive numbers we experience in NYC.