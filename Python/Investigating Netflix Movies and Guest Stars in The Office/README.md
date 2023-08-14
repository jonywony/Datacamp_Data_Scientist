# Investigating Netflix Movies and Guest Stars in The Office

## Background

Netflix! What started in 1997 as a DVD rental service has since exploded into the largest entertainment/media company by market capitalization, boasting over 200 million subscribers as of January 2021.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex our data manipulation skills and dive into the entertainment industry. Our friend has also been brushing up on their Python skills and has taken a first crack at a CSV file containing Netflix data. For their first order of business, they have been performing some analyses, and they believe that the average duration of movies has been declining.

As evidence of this, they have provided us with the following information. For the years from 2011 to 2020, the average movie durations are 103, 101, 99, 100, 100, 95, 95, 96, 93, and 90, respectively.

## Insight

#### Netflix Movie Durations 2011-2020

![Netflix durations](https://github.com/jonywony/Datacamp_Data_Scientist/blob/main/Python/Investigating%20Netflix%20Movies%20and%20Guest%20Stars%20in%20The%20Office/pictures/durations.png)

On the graph, we can see that there are some declining in movie durations between that year. But, does this trend is applicable in longer time frame? From the further analysis we can say that the average durations is slightly declining but there are a lot of movies with durations less than 80 minutes in the last decades.

#### Netflix movie Durations by Category

![Durations by Category](https://github.com/jonywony/Datacamp_Data_Scientist/blob/main/Python/Investigating%20Netflix%20Movies%20and%20Guest%20Stars%20in%20The%20Office/pictures/durations_cat.png)

Plot Legends:
- Red : Children Genre
- Blue : Documentaries Genre
- Green : Stand-up Genre
- Black : Other Genre

On this graph we breakdown the movies by category, we can see that  non-typical genres such as children's movies and documentaries are all clustered around the bottom half of the plot.

So, it can be suspected that the durations might not be shorter because the durations is affected by the categories.
