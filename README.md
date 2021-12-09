###115_personal_dataset
#Seattle Demographics
 ##Motivation
I have lived off and on in Seattle for my whole life and love the city. I have seen it really change over the course of growing up here, and I want to look a little bit closer at some of the data. As a black person, I was definitely curious about some of the racial demographics and wanted to look into them further. And from there, I just kept having more and more questions, which is what this dataset has set out to examine and answer. 

##Data Sources
All of the data I got from the US Census Bureau, The US Bureau of Labor Statistics, and the American Community Survey. 

I will analyze and go through the processing steps of each visualization. 


###Race and Education
This visualization is the amount of bachelor's degrees in Seattle, Washington seperated by race and colored by the year. As you can see, this one has some pretty big outliers. This is a good example of when you want to really think about the outliers in your EDA. In this case, you wouldn't want to remove these outliers because they are obviously very relevant. The amount of degrees awarded to white students far outshadows those given to any other race. This made me wonder why this is. Is it because colleges are purposely being racist? Well not exactly. This is most likely because there are a lot less non-white students in Seattle in the first place. According to the 2000 US Census, the population of black people in seattle was 7%, 14% Asian, 65% white, .4% Native American, .9% Pacific Islander, 2.3% from other races, and 5.6% multiracial. With that context, white students being a large outlier makes sense. 
<img src= https://github.com/tianajaded/115_personal_dataset/blob/main/Screenshot%20(145).png>


This is a visualization of different Wages in 2019 for the same jobs, seperated by race. I picked some specific jobs that I feel most of my friends fall under, and then analyzed them according to race. I didn't really specifically have a reason for doing this, other than I was just very curious to see how different races got paid in each profession they chose. I had to clean the data, there was definitely some missing data, most of which I just deleted. It was difficult because there was not data for every race in each profession. There were very little to no Native American/Pacific Islander entries. I just included the entries that were there, so that's why some of it is missing. There are definitely some big outliers in the jobs that tend to pay more - software engineering and management. Registered nurses tended to be the most consistent, with not a big gap in race or wage. However, there are some serious gaps in pretty much every other category, and it certainly begs many questions. As a black woman going into tech, I was a bit surprised and taken aback at the difference in software engineering. It seems that white people make around 170k, while their black counterparts make about 140k. What does this mean exactly, and what story is this data telling us? 
Drivers-Truck Drivers/Drivers
sde- Software Developer/Engineers
RNs-Registered Nurses
Retail- Retail Workers
Managers- Management 
![000091](https://user-images.githubusercontent.com/75195983/145333771-97017702-38b5-4bd7-8aea-b25d1acceb82.png)

These two barcharts are comparing the average household income of a Seattleite, and the average household American. It should be noted that these statistics are for household, not necessarily single people. So whoever is the head of household, and any spouses or dependents that live with them as well. This one was interesting. It took me a while to figure out how to label the percentages properly. I decided on just creating a dataframe with individual values, rather than referencing the csv so I didn't have to deal with turning the ranges into numeric factors and all that. Anyway, the data is interesting because it shows how wealthy Seattle is compared to the rest of America. 22% of the average household income in Seattle is over 200k. Only 8% of the rest of America falls into that income range. It's also interesting to see how 32% of America makes less than 50k a year, and 26% of Seattle residents. Acccording to the US Census, the poverty income is about 27k, which means that about 20%, or 1/5 of Americans live in poverty, and about 12% of Seattle residents. Most American households make between 75k-100k, and most Seattle households make over 200k. 
![seattleincomeranges](https://user-images.githubusercontent.com/75195983/145333868-bb7df04d-0ce6-429b-8d2b-788b4086968c.png)

![usincomeranges](https://user-images.githubusercontent.com/75195983/145333957-546469ed-4e08-41fc-b5b4-4bf4e575f0bb.png)

This lead me to my last inquiry: which industries as a whole make the most money in Seattle? The graph below is pretty self-explanatory. The winning industries are Information, Management& Enterprises, and Professional, Scientific, and Tech services. So if you want to move to Seattle, or if you live in Seattle and want to pick a lucrative career, choose one of those fields. 
![industrywage](https://user-images.githubusercontent.com/75195983/145334301-d2e95640-ff14-4b41-9108-e6b3632ef21f.png)
