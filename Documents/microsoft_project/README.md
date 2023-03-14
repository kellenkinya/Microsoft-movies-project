#        MICROSOFT MOVIE PRODUCTION PROJECT
![pexels-ds-stories-9227661.jpg](attachment:pexels-ds-stories-9227661.jpg)


## Project Overview
This project aims to explore the types of films currently doing well at the box office in the year 2010 to 2018 and provide actionable insights for Microsoft's new movie studio to decide what type of films to create. We will use explanatory data analysis to generate insights for microsoft company

# Business problem
Microsoft wants to enter into movies production. Explore what kind of films are currently doing best at box office and translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create. This project will allow Microsoft to better decide what kind of movies to create in order to match its competitors.

This project will allow Microsoft to better decide what kind of movies to create in order to match its competitors.

# Data understanding
Datasets used for this project are
1. [Box Office Mojo](https://www.boxofficemojo.com/)
2. [IMDB](https://www.imdb.com/)
3. [Rotten Tomatoes](https://www.rottentomatoes.com/)
4. [TheMovieDB](https://www.themoviedb.org/)
5. [The Numbers](https://www.the-numbers.com/)

This data will be collected from publicly available sources such as IMDb, Box Office Mojo, and Rotten Tomatoes which are open source movies platforms. Variables of interest collected from different dtasets and merged into one include , movies genres, movies studios, averagerating,years of release, gross earnings and production budgets.
This project explores:

1.Should Microsoft enter into movie creation?
2.What type of films are currently doing best at the box office.
3.What type of films should Microsoft create.
6.What genres should microsoft produce
4.What  movie studios are doing good for microsoft to emulate
5.The value or success of starting a new movie studio.

# Methods
 1. I prepared data for explanatory data analysis through combining three CSV files  and two SQL tables into one dataframe called movies_data using movie title  then cleaning it by remeving outliers, missing values and duplicates.
2. Performed explanatory data analysis on the dataframe through statistical techniques
3. Present results and findings through visuals like graphs and charts.

# Results and analysis.

#  1. Should microsoft enter into movie production

A positive correlation between production budget and profits, or production budget and profit margins show positive return on investment.

![pdp1.png](/Downloads/pdp1.png)
![pdp1.png](/Downloads/pdp2.png)

Microsoft should enter into movie creation

# 2.What are the most profitable movies in terms of profit margins
 Frozen, Despicable Me 3 and The Secret life Of Pets have the highest profit in terms of value from the top 25 movies that we did subset. but when we cosider profit margin  which is the company's  income when divided by sales or revenue  Table 19 , Thats my Boy and Stocker movies have the highest profit margin.

All movies combined have a mean profit margin of 0.35 and a median profit margin of 0.3 with a production budget of 35,077,795 US dollars , while the top 25 movies have a mean profit margin of 0.96 and a median profit margin of 0.97 with a production budget of 78,460,000 US dollars
![pdp1.png](/Downloads/mpm1.png)
![pdp1.png](/Downloads/mpm2.png)

Microsoft should budget a minumum of 78,460,000 US dollars so as to obtain a profit margin of above 96%. This will make them be among the 10 ten competitors.


# 3. Which movies genres are the most profitable
Drama, Comedy and Action are the most produced movie genres.
Drama Comedy and Adventure have the highest  total gross in millions.
Adventure, Animation and Comedy are the most profitable genres in term of profit margin.
![pdp1.png](/Downloads/mpg1.png)
![pdp1.png](/Downloads/mpg1.png)
![pdp1.png](/Downloads/mpg3.png)


Microsoft should produce  movies genres like Drama, Comedy ,Adventure and Animations.They have higher profits,good  returns on invesment and or on demand.

# 4. Which studios are best perfoming
Microsoft will have to implement some of the strategies from best movies studios.
Unilever, Fox and Buena vista companies were the top gainers during the year 2013 to 2018.

Fox company will be the biggest competitor for microsoft company followed by unilever company.
![pdp1.png](/Downloads/s1.png)



Microsoft should research  Unilever and Fox company's  best practices and try to build off the success of this well established studios

# Conclusion
Based on this analysis, this project will provide actionable insights for Microsoft's new movie studio to help decide what type of films to create.
This project can be expanded to include additional factors that influence box office performance, such  marketing strategies, and audience demographics.









