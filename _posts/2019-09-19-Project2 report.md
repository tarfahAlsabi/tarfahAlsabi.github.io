# METIS Project 2 Post

the project was building a model to predicates the prices of the laptops based on some of its features 



### The Target 

##### the price of the laptops 

### The Features 

|  Numerical   |   Categorical    |
| :----------: | :--------------: |
| Memory (RAM) |      Brand       |
|     SSD      | Operating System |
|     HDD      |     CPU Type     |
| Screen Size  |                  |



## The Methodology

as shown on the work-flow under.  my methodology was to scrape the data form [new egg](https://www.newegg.com/global/sa-en/) website using selenium and beautiful soup libraries then cleaning  the data and building the model using python .

![methodology work flow]({{ site.url }}/images/METHODOLOGY.jpg)



## Selecting Model process

after cleaning the data. 

I build a baseline model with R^2 = 0.463.

then I tried to improve it by using:

1. power transformation on the 'HDD' and 'Screen size' features.

2.  take the log of the target ' price' in order to have a semi gaussian distribution.

3. replace the categorical  features with dummies.

4. trying different Linear Regression models (Ridge Regressio, Lasso Regression
   , Elastic Net Regression, and OLS Regression)and compare their result. 

   

## The Result

My final Model was : OLS Regression model with R^2 = 0.522

![the OLS result]({{ site.url }}/images/OLS result.png)

![OLS feature result]({{ site.url }}//images/features result table .png)