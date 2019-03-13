**Drug use patterns and correlations**


One of the things that seemed interesting to me in the war on drugs debate is the details of usage of various drugs and how they might correlate with those of other drugs and in particular those of cannabis as legalization is a hotly debated political issue. In this article we shall use data points and visualizations to gain insight into these patterns.

We are using the National Survey on Drug Use and Health dataset for this project. It has over 55,000 responses spanning across 2500 parameters. It is representative of the general population for most substances. I have mainly explored 2 questions in this analytical project. The first is observing the various usage statistics of 4 different substances, Cannabis, Alcohol, Cocaine and Heroine. In the second part we shall look at how the usage of various drugs correlates with that of cannabis and try to visualize some of the relationships. There is no concrete answer we are looking for but we can observe many interesting datapoints.

For the first part of the analysis we shall be looking at the usage statistics and basic visualizations associated with them for the 4 substances to learn more about their usage. We shall look the overall usage statistics, the % of people who partake in their consumption,the age at which they have started to do so and also the frequency with which they do so.

**Cannabis usage**

Lets start from the basics and see how many people in the dataset have used cannabis. We shall examine both the absolute number and the percentage. This will help us see if this is representative of the general population.

No of people in the dataset who have used cannabis 24022. 
Percent of users surveyed = 42.68%

This is inline with the national average which is estimated at 44%. This is the substance with the highest number of people using it after alcohol which is legal.

For the people who have used Cannabis, lets look at the age they have started to do so in the form of a histogram. Visualization of this can let us understand how and when cannabis usage starts.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/weed_age_histogram.png)


Here we can see that most people tend to start using cannabis between the ages of 15 and 25. This again lines up with the estimated mean age of 17-19 years in the United States. This also lends to the theory that most users start off in the social settings of high school or college


Next, lets look at usage by seeing the number of times cannabis was used in the last year. This can help us understand how it affects the lives of its users

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/weed_usage_cdf.png)


Here in this graph we can see that around 25% of cannabis users have not consumed it in the past year and 50% of the users use it less than once a week. We then have a fairly linear graph from there onwards where around 75% of users use it less than 3 times a week. We see that the top 20% of the users use it almost 5 times a week.

**Coke usage**

Now lets move on to something harder and see how many people in the dataset have used coke. Again we shall see both the absolute and percentage numbers which shall help us compare to national statistics.

No of people in the dataset who have used coke = 6745 

Percent of users surveyed = 11.98 %

This lines up with the 38 million people in the US estimated to have tried cocaine at some point in their life.

For the people who have used Coke, lets look at the age they have started do so in a histogram. Again this shall help us understand when and how coke use starts.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/coke_age_histogram.png)

We can see in the graph that most people start between age 18 and age 25. The median age is definitely higher than that for cannabis suggesting most people try harder(more dangerous) drugs later on in life.

Again Lets look at usage by seeing the number of times coke was used in the last year by people who have used it atleast once in their lives. I have binned data by to nearest 10 for clearer plotting.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/coke_usage_cdf.png)

Over 60% of people have not used coke in the trailing 12 months which suggests most people who tried it have not stuck to it in the long term. We then see above 90%, the 10% of users who use it over 100 times a year.

**Heroin usage**

Heroin again is a "hard" drug and considered very addictive. It is thought to be far less prevalent than the previous two. Lets explore the basic numbers for it.

No of people in the dataset who have used heroin 1029.
Percent of users surveyed = 1.828 %

Heroin when compared to the other drugs is far less prevalent and only about 2% of the users surveyed have ever tried it. 

For the people who have used Heroin, lets look at the age they have started do so in a histogram. Again this shall allows us to observe and deduct how and when Heroin use might have occurred. 

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/heroin_age_histogram.png)

Heroin has a latter and a broader onset compared to the other drugs we have observed, with most people starting between the age of 18 and 35. This suggests unlike the other substances we have surveyed here, it is not something linked to the college social setting.

Lets look at usage by seeing the number of time heroine was used in the last year by people have tried it atleast once in their lives. This is especially useful for heroin as it shall help us gauge its addictiveness and effect on users.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/heroin_usage_cdf.png)

Less than 30% of the people who have tried at somepoint in their life have not used Heroin in the past year which is the lowest we have in the drugs we have examined till now. More than 50% of the people use it over 2 times a week suggesting its highly addictive.

**Alcohol usage**

 Alcohol is the one legal drug we are examining and thereby its prevalence is expected to much higher than the rest.

No of people in the dataset who have used Alcohol = 40548.
Percent of users surveyed = 72.05 %

This is pretty close to the statistics reported by the National Institute on Alcohol abuse which states around 75% of Americans have consumed alcohol at some point in their life. 


For the people who have used Alcohol, lets look at the age they have started do so in a histogram. This visualization will allow us to again understand how and when they have first consumed this substance.


![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/alcohol_age_histogram.png)

It is very obvious for us to infer here that most people have first consumed alcohol between the ages of 10 & 20 confirming the general theory that many have their first brush with alcohol in a high school or college setting.

Lets look at usage by seeing the no of times alcohol was used in the last year. Again this shall give us more data to infer its usage patterns from.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/alcohol_usage_cdf.png)


More than 80% of the people who have ever had alcohol consumed it in the past year. This can be attributed to its social acceptability and legal nature. We can see then see an exponential trend with fewer and fewer people consuming it on a more frequent basis.

**Correlations in drug use**


For the second part, we are looking at the correlations in usage between cannabis and other substances and will try to visualize some these relationships. This is highly interesting as legalization is a very much debated issue with cannabis labeled as the "gateway" drug.

**Cannabis and alcohol**

Cannabis and alcohol are the 2 most prevalent drugs with 72% and 45% of the users surveyed respectivley replying that they have tried them at some point of their lives. 

We shall look at the mean ages at which users who have done both substances started each substance to see if there are any interesting correlations.

The average age cannabis users have first tried alcohol = 15.66

The average age alcohol users have first tried cannabis = 17.196

The average age alcohol users(who have not done cannabis) have first tried alcohol = 18.27

The average age cannabis users(who have not done alcohol) have first tried cannabis = 15.78

Cohen effect size between the age difference of people who have done only alcohol and people who have done both alcohol and marijuana= -0.233

This leaves us with 2 interesting points to note, the first being that cannabis use in alcohol users lowers the age of first brush with alcohol by a very significant amount but alcohol use in cannabis users shows a much smaller difference and the second saying cannabis users start off much younger than alcohol which is suprising considering the legalities of both.

Visualizing this relationship as a scatter plot with a line of regression added helps us understand how the age of first alcohol use varies with the age of first use of cannabis.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/weed_alcohol.png)

Interpreting this scatter plot, we can infer that, at lower ages, a lower age of alcohol use correlates with a lower age of weed use and vice versa. At later ages, we just see outliers which don't provide us with much information

**Cannabis and coke**

Next, lets look at patterns between the usage of cannabis and coke, This is a correlation which is interesting as we are examining the link in usage between two illegal drugs of varying intensities.

The average age cannabis users have first tried coke = 20.68.

The average age coke users have first tried cannabis = 15.70.

The average age coke users(who have not done cannabis) have first tried coke = 22.51.

The average age cannabis users(who have not done coke) have first tried cannabis = 17.14.

Cohen effect size between the age difference of people who have done only cocaine and people who have done both cocaine and cannabis= -1.860

We can see here that cocaine users who have used weed have started using coke almost two years earlier compared to those who haven't. This suggests that people who have consumed cannabis have used harder drugs earlier compared to those who haven't. There is nothing conclusive to be drawn from this but it is an interesting pattern.

We shall again plot the scatter plot and regression to visualize the relationship.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/weed_coke.png)


We see correlation on both sides of this relationship. A lower age of first cannabis use means a lower age of first coke use and vice-versa. This correlation interestingly exists at relatively higher ages compared to the one between cannabis and alcohol.

**Heroin and coke**

The relation between Heroin and cannabis should be interesting as heroin is the drug which had the highest overlap of users with cannabis. Over 95% of all Heroin users have consumed cannabis.

The % of heroine users who have consumed cannabis =  96.98

The average age cannabis users have first tried heroin = 22.69

The average age heroin users have first tried cannabis = 14.24

The average age heroin users(who have not done cannabis) have first tried heroine = 24.14

The average age cannabis users(who have not done heroin) have first tried 
cannabis = 17.14


Cohen effect size between the age difference of people who have done only heroin and people who have done both heroin and cannabis = -2.63

The high overlap is something we definitely need to think about as we intrepet any correlations using these relations. The fact that less than 5% of Heroin users have not used cannabis means that the age heroin users who have not used cannabis first tried heroin might not be a very important parameter as it is less than 50 people in a dataset of 50,000.

The difference between the age heroin users first tried cannabis and the age cannabis only users have used cannabis is pretty large suggesting users of harder drugs are probably more likely to have tried cannabis at an earlier age.

We shall now plot the scatter plot between the age at which people have tried heroin and the age they have tried cannabis along with a regression to visualize the correlation.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/weed_heroin.png)

There appears to be no significant correlation outside the fact that age of first cannabis use between the ages of 15 and 20 correlates with earlier Heroin use. Heroin age later seems to be an independent variable not dependent on cannabis use.


I am now going to plot four CDFs indicating the age at which people have tried various substances. This is just to view the trends.

![alt text](https://github.com/ssreekanth2000/project_1/blob/master/photos/age_cdf.png)

What we see here broadly is that the age at which people try cannabis and alcohol are relatively lower compared to the harder drug.

**Conclusions**

There are clear differences in ages at which people who have not done cannabis and people who have done, start using each of the other substances. We also see a clear pattern where correlation between cannabis use and other drugs is strong. Both of these results suggest that cannabis might have acted as a gateway drug but we have no clear way to prove that. Looking at this correlations and distributions, we can try to infer data regarding how these usages impact people and how they might have started off. 














