# METIS Project 3 report

the project was building a model to Classifying games popularity in steam platform.

**Steam** is a video game digital distribution service platform developed by [Valve Corporation](https://en.wikipedia.org/wiki/Valve_Corporation).
It was launched in September 2003 as a way for Valve to provide 
automatic updates for their games, but eventually expanded to include 
games from third-party publishers. 

steam currently have more than 14 million active users and 30,000 game.

the records was taken from [kaggle](https://www.kaggle.com/nikdavis/steam-store-games)



### The Target 

##### the game owners.

### The Features 

- game platforms.
- age rating.
- positive ratings.
- negative ratings.
- average playtime.
-  price.

## The working process

after cleaning the data I plot them to see the distribution of the game's owners

![owners distribution]({{ site.url }}/images/project3/Full_owners.png)

as shown in the plot. most games have 20,000 or fewer owners. So I decided to have two classes in my model (0-20,000, AND <20,000)

after preparing the samples there was unbalancing between the two class that be handled using over-sampling techniques (ADASYN)

![balancing]({{ site.url }}/images/project3/balancing the sample.jpg)



##  The Final Model

after trying several models I ended-up using the ensembling model as shown in the following figure.

![final model]({{ site.url }}/images/project3/ensampling.png)

## The Result

Confusion Matrix

![the matrix]({{ site.url }}/images/project3/confusion_Matrix.png)

Classification
Report

![report]({{ site.url }}/images/project3/classification_report.png)