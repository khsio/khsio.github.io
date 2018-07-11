---
layout: post
title: Project Benson - Volunteers Allocation Recommendation
---

### Problem
In this project, as a team of five from The Awesome Data Scientist, Inc. We need to help WomenTechWomenYes, a non-profit that focusing on helping women to be successful in the tech industry, to identify what is the best way to allocate their volunteers giving a limit amount of resources that they have. 

WomenTechWomenYes (WTWY) is a young and new organization, their annual big event - Summer Gala 2018 - is coming up. They would like to use this event to help raise their awareness and reach. In previous years, they have been sending their volunteers street teams to subways stations that they think could collect the most email contacts and possibly have the most people to donate based on their knowledge about these subway stations. But the result is not as good as what they would thought to be. 

Recently they heard that Data Science could help organizations make better decisions, so they reached to us and wondering if we could help them. After a few consultations and better understand their needs, we have designed this project to help them better relocate their street teams using data science.

### Approach

Our purpose is to create a solution that could give them a peace of mind, a list of subway entrances to place their street teams and a safer experience. To do that, first we will use turnstiles data from NY MTA as our main focus. Second, we will use data from Yelp to support our findings. Lastly, we will use crime data to reinforce our analysis. 

### Analysis

For the NY MTA turnstile data, since we are trying to find out subway stations that has the most traffic during the summer time, we have decided to obtain data only for summer months (Jun, Jul, Aug) of 2016-2018. From that, we were able to find out that Friday is the day of week that has the most traffic. To inspect further, we found out that the prime time of each station that has the most traffic is at the evening of 8pm. 

Then we move forward to look at the Yelp data. From our research shows that most people would like to have dinner at a restaurant in a Friday evening. And since we want to target people that has more money to donate, we want to target people that go to NYC Michelin restaurants or restaurants that has 4 $ sign on Yelp. Using Yelp api, we were able to locate those 4 $ sign restaurant that near our highest traffic subway entrances. The top 10 locations would be 3 AV-149 ST, Brighton Beach, 167 ST, 161/Yankee Stad, 149/Grand Conc, Flushing-main, Kings Hwy, 5 Ave, 103 St-Corona and Forham Rd.

Lastly, we use the crime data to help us understand when would be an unsafe time for our street teams to work. From our data, we could see that 7pm to 9pm of Friday has a relatively low robberies crime rate.

### Recommendation

Putting all our analysis together, we would like to recommend WTWY to place their street teams at recommended locations between 6pm to 9pm of Friday to maximize their odds of reaching to potential donors and have a high donation rate.

### Future Improvement

Upon our partnership, we would like to extend our project and see if we could improve our recommendations. Possible future extensions could be refine target audience based on census data (income based), refine target locations to include tech companies close to subway stations, and project donations based on results, instead of assumptions.




Credit to Martha Cassetti, Dahlia Ma, Paru Jayaprakash, Brenden Rossin from Metis SF Summer cohort 2018.