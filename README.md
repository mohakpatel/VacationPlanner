# Vacation Planner

In this project, I look to find the cheapest and best time for a ski trip in Colorado. 

As a budget traveller, I like to keep the price of travel low. And usually I just optimize my travel dates based on airticket prices alone. I always wondered if I could save extra money if I also optimized on other variable costs like accommodation. 


So here I collect data of flight prices, Airbnb listing prices, weather patterns for snow conditions and other data to plan the best budget ski-trip. Here is the combined figure showing breakdown of various variable costs for a 5-day ski trip vacation in Colorado. 

![](https://raw.githubusercontent.com/mohakpatel/VacationPlanner/master/data/Variable_price.png)

### Results

1. The cheapest time to travel is 2nd February 2019 from Madison to Colorado with a total variable cost of $513.
2. On an average, I save about $221.83 dollars on variable cots with this optimization. This effort was worth it.  
3. Compared to optimizing only based on flight prices, I save an extra $90.75 using my approach. 


### Files:
1. [Flight price data collect, clean and explore ](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Flight-price%20Scrap%20Clean%20Explore.ipynb)  
2. [Airbnb data clean and explore](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Airbnb%20Data%20Cleaning%20Exploration.ipynb) 
3. [Weather data clean and explore](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Weather%20Clean%20Explore.ipynb)
4. [Secondary costs](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Create%20vacation%20day%20and%20peak%20travel%20cost.ipynb) (Vacation day and peak time travel cost)
5. [Combined cost analysis](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Combined%20cost%20analysis.ipynb)


# Airbnb listing price prediction

While working on this project, I got interested in the Airbnb listing data. I was wondering if I could predict the prices of Airbnb listing using the listing feature. So I do sub-project where I explore various 


### Results
My best model is based on xgboost regression and it achieved a median absolute percentage error of 20.85% or median absolute error of $20.12.

### File
[Airbnb listing price prediction](https://github.com/mohakpatel/VacationPlanner/blob/master/src/Airbnb%20Price%20Prediction.ipynb)

# Requirements
I used the following version of libraries in Python 3 for my model

- Pandas 0.23.4
- Numpy 1.15.1
- Scipy 1.1.0
- scikit-learn 0.19.2
- xgboost 0.81
- Seaborn 0.9.0
- matplotlib 2.2.3
- BeautifulSoup
- urllib
- time
- os
- warnings
