# Data science portfolio

## Table of content
  - [Projects](#projects)
    * [project0 IMBD movies analysis.](##project0-imbd-movies-analysis.)
    * [project_1 - Analysis of sales of an online store.](#proj1-)
    * [project_2 - What make chocolate bars popular among people?](#proj2-)
    * [project_3 - Preventing bad scores on your math exam.](#proj3-)
    * [project_4 - TripAdvisor fake reviews research.](#proj4-)
    * [project_5 - Telegram bot that collects, analyzes and saves data about TikTok videos.](#proj5-)
  - [Contacts](#contacts)

# Projects
Evolution of my data science skills. Step by step - project by project.

## project0 IMBD movies analysis.
### Description:
This is my first pet-project where i analyse IMDB dataset. Which actor has starred in more high-budget films? For which director is winter the most productive time of the year? What actors are most often filmed together? I answer these and other 20+ interesting questions from movie industry.
### Tools:
- Python
- Pandas
- Numpy
- Collections
- Itertools
- Patplotlib.pyplot
- Seaborn
### Goal:
Main goal of this work is practising my data-managing skills such as: data visualization, insight mining and basic EDA.


## project_1 - Analysis of sales of an online store.
### Description:
In this work i had datasets for an every month containing sales information so in fact it is Analysis of annual sales of an online electronics store. Also data wasnt really clean: bunch of missing values, mistakes and wrong data types. So before main analysis i had to carry out some preprocessing. Big thanks to youtube video-maker Keith Galli for inspiring and great educational videos. 
### Tools:
- Python
- Pandas
- Numpy
- Collections
- Itertools
- Patplotlib.pyplot
- Seaborn
- Datetime
- os
### Goal:
Despite of big practising in writing code with python and working with pandas dataframes - this project made me also explore some buisiness questions, such as: When and why we should display advertisements to maximize the likelihood of purchases? What product sold the most and why? And so on..but main one for me was how actually use data to answer questions like this?


# project_2 - What make chocolate bars popular among people?
### Description:
What features have the most affect on chocolate bar Rating? Data required great preprocessing: managing missing values(firstly detect them using IQR rule vs. common sense, secodnly decide wether it real value or a mistake and then choosing the best way to fill them), find and solve non-Gaussian distributions (as i used basic linear model here) and so on. After that i did a correlation analysis and analysis of nominative variables as well. In this project i used corr.matrix and student's t-test of course with extra help i gain from visualization. After every step i write analytical results, conclusions and my personal thoughts. 
### Tools:
- Python
- Pandas
- Numpy
- Collections
- Itertools
- Patplotlib.pyplot
- Seaborn
- Scipy.stats
- re
### Goal:
Learn how pipelines work - i tried to make my analysis as strctures as possible. Practise python skills defining functions wich helped me alot during this work. I also wanted to use statistics tests here so i can get a more interpreted insights and results. Moreover i used great opportunity to improve my English skills while reading lots of documentations and data sciense articles.


# project_3 - Preventing bad scores on your math exam.
### Description:
This work as all about Analysis of the results of the math exam for students between 15 and 22 years. What features affect the exam result? By finding this out, it is possible to identify the risk group in advance and prevent bad results. Doing this project i had great opportunity to improve my skills. Thanks to stackoverflow i got to know some new techniques and improved my English as well. Furthermore i spend some days just to dive into the subject area so i can get a better understanding of data. I can say this analysis is very vert interesting.
### Tools:
- Python
- Pandas
- Numpy
- Collections
- Itertools
- Patplotlib.pyplot
- Seaborn
- Scipy.stats
- re
### Goal:
Main goal was to get a clear undesrtanding why people fail their math exams. How we can prevent it? How we can easily find and recognize risk group and help these students? Does something else apart of real math skills afect stusents' results? How i can concat my investigation work with statistical testing to answer those questions?


# project_4 - TripAdvisor fake reviews research.
### Description:
There is a TripAdvisor restaurants database which contains lots of interesting for analysis features. It seems like some resraurants be 'boosting' their rating with fake reviews. I built a model which predict Restaurant Rating so we can compare my predict and real value. In case there is a large difference - we should check if this restaurant's reviews are fair. I build and test hypotheses using statistics, do Feature engenireeng including polynomial features. I also create and train regression model and test it with specific metrics. Big preprocessing(missing values, outliers, mistakes) was required as well.
### Tools:
- Python
- Pandas
- Numpy
- Collections
- Itertools
- Patplotlib.pyplot
- Seaborn
- Scipy.stats
- ast
- re
- Datetime
- Sklearn
### Goal:
Main task was buidling a model wich can help TripAdvisor to get rid of scammers - people who wind up a restaurant rating and thereby deceive visitors. As for me a great goal was also a starting to learn ML.


# project_5 - Telegram bot that collects, analyzes and saves data about TikTok videos.
### Description:
Best way to descrive this project is just share a link [https://tg.telepult.pro/ttbooster_bot] - bot is 100% free and working 24/7. Tasks this bot perporms are: regularly collecting data through surveys(20+ features), displays number of observations, performing statistical test for numerical,categorical and binary data types to gain insights, plotting categorial data in case there is statistically significant differences for the feature, cleaning your data in case you need it, collecting all data from all users and saving it to .csv for further analysis.  
### Tools:
- Python
- aiogram
- SQLAlchemy
- Scipy
- async
- Pandas
- Numpy
- Seaborn
### Goal:
My girlfriend doing tiktok and i came up with an idea to build a bot wich will provide her some kind of a premium statistics - finding what are those 'parts' of video that makes it popular/unpopular. As a junior data scientist i also had a goal to collect data and do some research on people who do tiktok and their videos. To do this, i need to wait a little while people use the bot so that there will be enough collected data for interesting and quality investigation.




