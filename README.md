# Pursuit of Happiness
## DATA 512 Human-Centered Data Science Final Project

The main source of data is 3 CSV files from [Kaggle](https://www.kaggle.com/unsdsn/world-happiness): 2015, 2016, and 2017 World Happiness dataset.
Each dataset contains a column of 
* Country: Country name
* Happiness Rank: Country rank based on happiness score. Lower rank means happier
* Happiness Score: Happiness score of the particular country
* Lower Quartile: Denotes the upper boundary of 95% confidence region
* Upper Quartile: Denotes the lower boundary of 95% confidence region
* Economy (GDP per Capita): Natural log of GDP per capita for the particular country, adjusted on 2011 international dollar value. 
* Family: Average response to family or social support questions, such as "If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?"
* Health (Life Expectancy): Constructed from World Health Organization (WHO) data. It basically measures life birth expectancy to life expectancy 
* Freedom: Average response to questions related to freedom to make life choices, such as "Are you satisfied or dissatisfied with your freedom to choose what you do with your life?"
* Generosity: Average response to altruism questions, such as "Have you donated money to a charity in the past month?" 
* Trust (Government Corruption): Average response to question "Is corruption widespread throughout the government/business or not?"
* Dystopia Residual: Unexplained component for each country.

Each key predictors (Economy, Family, Health, Freedom, Generosity, and Trust in Government) are scored relative to a fictious place, referred as "Dystopia", where all the key predictors are at absolute worst among all countries in the world. For example, Argentina is rated 1.440 for Family, meaning it is 1.440 better than Dystopia in term of Family.  

Initially I used World Bank dataset, in addition to World Happiness dataset, to replace the GDP per Capita score with actual dollar number for each country. However, the licensing has changed in the last few days to restricted.

#### Licenses
Kaggle datasets are released under [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/).