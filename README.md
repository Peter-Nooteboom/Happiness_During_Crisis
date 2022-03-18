# Global Happiness During Crisis
---

![Global Happiness During Crisis](https://i.imgur.com/32sz4Qo.jpeg)

In this project I explore global happiness ratings recorded in years of global crisis. I explore how happiness has changed overtime and what factors contribute to feelings of happiness during these times. Finally, I evaluate the predictive ability of these factors in predicting happiness scores.

## Happiness and Crisis
Traditionally, many world leaders have focused on indicators such as the stock market, unemployment, and GDP as the main focus for informing policy and leadership. Unfortunately, these financial indicators lack empathy for the individual human experience. As citizens, these global financial factors certainly play an important role in our lives. However, other factors such as our individual happiness are a critical part of our day-to-day experience.

Happiness as an indicator is beginning to be more recognized for its importance. As people, we can strive for wealth, relationships, and success, but if we are not happy, it is all for nothing. The World Happiness Report is a global survey of happiness across the world. The reports overviews the current state of global happiness and describes how emerging science of happiness explains personal and national variations in happiness. Additionally, we are beginning to see more recognition of happiness as an important indicator in media. For example, the book “[The Algebra of Happiness: Finding the Equation for a Life Well Lived](https://www.goodreads.com/book/show/42872963-the-algebra-of-happiness)” by Scott Galloway was released in 2019 and became a New York Times Bestseller. The book focused on paths to a happier life, and clearly resonated with many individuals.

Despite being more frequently recognized as an important indicator, the policies and leadership we see across the globe still seem to ignore happiness as a real priority. This neglect for prioritizing it is no more relevant than during times of crisis. Individuals and countries go into “survival mode” and seem to lose sight of factors that could drastically improve the day-to-day human experience.

In 2009 the world’s economy had entered into crisis following the implosion of the US housing market in late 2008. This crisis has now come to be know as The Great Recession. Many individuals lost their jobs, their homes, and were struggling to recover for many years. While this crisis originated in the US, its effects were certainly felt across the world.

In 2020 and 2021 the world experienced another global-level crisis. The COVID-19 pandemic had a large scale impact on the health and wellbeing of many individuals across the globe. Even for those whose health was not directly impacted, great grief and disruption was felt in our lives.

While much changed in the world from 2009 to 2021, many similar patterns and unrest occurred during these years. While the crises of The Great Recession and COVID-19 are different, the global impact of both are undeniable. Unfortunately, during these times of crisis, a prioritization of empathetic factors such as happiness were absent. However, I would argue that in times of crises, when the previously mentioned financial and global factors are threatened, a focus on happiness is even more important than usual.

To help prepare society for future crises, and to better the experience of many during these crises, a continued effort to understand happiness during these times is needed. Additionally, an understanding of the factors that contribute to and predict happiness during these times is also needed.

## Project Summary

**Problem:** During times of crisis, happiness is often jeopardized on both an individual and global level. Happiness can be an important priority, but can be impacted greatly when other societal factors begin to fall apart. In future crises, knowing which societal factors are most relevant for increasing happiness would allow for a better and more targeted response, and would allow regulators to recognize the importance of happiness during such times.

**Goal:** In this project, I aim to explore global happiness scores in 2009 and 2021, the changes they undergo, and the factors that influence them. Additionally, I aim to create predictive models of societal factors that can predict happiness scores in 2009 and 2021.

## Data

The World Happiness Report strives to survey global happiness each year. For this report, happiness scores and rankings use data from the Gallup World Poll. The data used for this project contains happiness scores, as well as several societal factors (social support, perceptions of corruption, freedom to make life choices, healthy life expectancy, generosity, GDP). The present project used data from 2009 and 2021. The full dataset includes data from other years as well as a few additional variables. Natural Earth data was also utilized for this project to create geospatial visualizations.

All of the data used for this project can be found in this repository, or the full Happiness Index data can be found on [Kaggle](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021).

## Happiest and Unhappiest Countries
In both 2009 and 2021, the happiest countries had happiness scores around the mid-to-high sevens. The unhappiest countries had scores around mid-threes to low fours. In general, we can see that in 2021, the extremes got slightly more extreme. Additionally, over half of the top ten happiest and unhappiest countries were different comparing 2009 to 2021. We also see that Afghanistan had dramatically lower scores than the second unhappiest country in 2021.

![Happiest and Unhappiest Countries](https://i.imgur.com/BRCg6Yx.png)

## Happy and Unhappy Locations
Investigating the happy and unhappy countries even further, the following visualizations show the locations of the top 50% and bottom 50% (mean split) of countries by happiness. For both years, we see that the Western hemisphere has a dramatically higher proportion of above mean happiness scores than the Eastern Hemisphere. North America, South America, and Europe appear to be mostly happy, while Asia and Africa appear to be mostly unhappy. Overall, we also see the first indications that there were only modest overall changes in the mean happiness score from 2009 (5.45) to 2021 (5.53). However, a lack of overall change may be impacted by various factors such as changes in which countries are included in the survey from year to year. We still may see important changes when looking on a smaller scale.

![Happy and Unhappy Locations 2009](https://i.imgur.com/wo5Blui.png)
![Happy and Unhappy Locations 2021](https://i.imgur.com/OMst0TU.png)

## Continental Happiness
Zooming in even more and investigating the continental differences in happiness, we see similar trends as before. South America, North America, and Europe show high average happiness scores compared to Asia and Africa. South America and North America both had average happiness scores higher in 2009 than 2021, while Europe, Asia, and Africa had lower 2009 ratings compared to 2021. Afghanistan, Haiti, and Venezuela all were outside the typical ranges for their regions. Most dramatically, Venezuela went from being the happiest country in South America in 2009 to the unhappiest in 2021. While in both these years there were global crises occurring, the anomalies seen for these three countries could likely also be attributed the local crises that occurred between 2009 and 2021 in each.

![Continental Happiness](https://i.imgur.com/LwJhhdF.png)

## Changes in Happiness: 2009 to 2021
Investigating changes further, we see that overall global happiness increased by only 1.34%, and also confirmed the flattening of the distribution with the extremes becoming more extreme. North America saw a 7.74% decrease in happiness scores from 2009 to 2021, with more low end scores emerging in 2021. South America saw a similar pattern of change with a drop of 6.58%. Europe has an increase in happiness scores of 10.03%, and started to show a slight bimodal distribution. Africa saw a 2.55% increase, and Asia showed a very slight increase of 0.51%. Overall we see changes on the global and continental levels that vary in size.

![Changes in Happiness: 2009 to 2021](https://i.imgur.com/LUvmdNg.png)

## Largest Changes in Happiness: 2009 to 2021
To better understand what is driving aggregated changes in happiness from 2009 to 2021, we can also look at the individual countries that showed the biggest decreases and increases. The following visualization shows that the largest changes seen were roughly between 1 and 2 points. The countries that saw the largest decreases mostly experienced factors that impacted their day-to-day quality of life and safety. Such societal factors that may be impacted include things such as GDP, perceptions of corruption, freedom, life expectancy, and social activity. On the other hand, many of the largest increases were seen in countries in parts of the world that saw increased development between 2009 and 2021.

![Largest Changes in Happiness: 2009 to 2021](https://i.imgur.com/9AI5gZQ.png)


## Relationship Between 2009 and 2021 Happiness
Despite the large changes seen by some countries, overall the general happiness scores in 2009 were correlated strongly (r = 0.75). That is, if a country was unhappy in 2009 it would likely remain unhappy in 2021. The countries that showed the largest changes from year to year defied this overall pattern.

![Relationship Between 2009 and 2021 Happiness](https://i.imgur.com/34cG6HP.png)

## Societal Factors
As mentioned previously, crisis and strife may be acting on happiness through its impact on a variety of factors. Some of these factors might include GDP, perceptions of corruption, freedom to make life choices, healthy life expectancy, social support, and generosity. In each of these variables, we saw moderate changes from 2009 to 2021. The least changed factor between the years appeared to be generosity. Additionally, generosity and perceptions of corruption both showed the presence of many outliers.

![Societal Factors](https://i.imgur.com/D4bMBLD.png)

## Changes in Societal Factors: 2009 to 2021
Looking at the changes in these factors more closely, we can see that social support (-0.52%), perceptions of corruption (-4.64%), and generosity (-135.27%) all had decreases from 2009 to 2021. While the percentage change for generosity is very large, this can be attributed to the fact that its 2009 mean rating was a decimal score very close to zero, which makes even small magnitude changes appear very large. Conversely, GDP (1.8%), healthy life expectancy (4.14%), and freedom to make life choices (14.81%) saw increases from 2009 to 2021.

![Changes in Societal Factors: 2009 to 2021](https://i.imgur.com/jKy5Ss3.png)

## Societal Factors in Happy vs. Unhappy Countries
To get a further sense of how these factors may individually influence happiness, we can compare their means and distributions in the happiest and unhappiest (mean-split) countries. In the happiest half of countries, social support, GDP, healthy life expectancy and freedom to make life choices were all much higher than in the unhappiest countries. Perceptions of corruption and generosity had fairly similar distributions and means for both happy and unhappy countries. This pattern of results was consistent in both 2009 and 2021. Together this suggests that amongst these factors, social support, healthy life expectancy, GDP, and freedom to make life choices are most relevant for happiness.

![Societal Factors in Happy vs. Unhappy Countries](https://i.imgur.com/6ACEL2A.png)

## Relationships Between Societal Factors and Happiness
We can investigate the relevancy of each factor for happiness further by looking at the association between each factor and happiness scores. Across all factors the associations comparing 2009 and 2021 were fairly consistent. As suggested above, social support, GDP, healthy life expectancy, and freedom to make life choices were the most strongly related to happiness scores.

![Relationships Between Societal Factors and Happiness](https://i.imgur.com/daIrhQ5.png)

## Predicting Happiness

As discussed, in both 2009 and 2021 the world was experiencing crises. These crises likely had an impact on societal factors, which in turn impacts happiness. Through these analyses we see that social support, GDP, healthy life expectancy, and freedom to make life choices were the most relevant for happiness during these times of crisis related to happiness scores. During future crises, knowing which countries are at risk for wavering happiness, we can use these factors as indicators. To further establish these factors as good indicators of happiness, their predictive ability can be evaluated in both 2009 and 2021.

To conduct this evaluation, two linear regression models were trained with social support (SS), GDP, healthy life expectancy (HLE), and freedom to make life choices (FLC) predicting happiness scores. The 2009 model showed the following:

- **Coefficients:**
  - **Intercept:** -2.45
  - **SS:** 2.26
  - **GDP:** 0.27
  - **HLE:** 0.04
  - **FLC:** 1.31
- **Root Mean squared error (RMSE):** 0.71
- **Mean squared error (MSE):** 0.50
- **Train Coefficient of determination (R^2):** 0.69
- **Test Coefficient of determination (R^2):** 0.41
- **Crossvalidation:**
  - **Average R-Squared Score:** 0.55
  - **Maximum R-Squared Score:** 0.62
  - **Minimum R-Squared Score:** 0.48

In 2009, we see that together these factors were moderately reliable predictors of happiness scores. That is, for each 1.00 unit increase in social support, a 2.26 unit increase is expected in happiness. For each 1.00 unit increase in GDP, an increases of 0.27 is expected in happiness. For each 1.00 unit increase in healthy life expectancy, an increases of 0.04 is expected in happiness. For each 1.00 unit increase in freedom to make life choices, an increases of 1.31 is expected in happiness.

The 2021 model showed the following:

- **Coefficients:**
  - **Intercept:** -2.42
  - **SS:** 2.06
  - **GDP:** 0.32
  - **HLE:** 0.02
  - **FLC:** 2.31
- **Root Mean squared error (RMSE):** 0.59
- **Mean squared error (MSE):** 0.35
- **Train Coefficient of determination (R^2):** 0.72
- **Test Coefficient of determination (R^2):** 0.80
- **Crossvalidation:**
  - **Average R-Squared Score:** 0.62
  - **Maximum R-Squared Score:** 0.68
  - **Minimum R-Squared Score:** 0.53

In 2021, we again see that together these factors were reliable predictors of happiness scores. That is, for each 1.00 unit increase in social support, a 2.06 unit increase is expected in happiness. For each 1.00 unit increase in GDP, an increases of 0.32 is expected in happiness. For each 1.00 unit increase in healthy life expectancy, an increases of 0.02 is expected in happiness. For each 1.00 unit increase in freedom to make life choices, an increases of 2.31 is expected in happiness.

Comparing 2009 to 2021, we can see that these factors were better at predicting happiness in 2021 (RMSE = 0.59), compared to 2009 (RMSE = 0.71).

## Conclusions

The present analyses explored global happiness in 2009 and 2021. In both years, the world was experiencing crises. During these times of crisis, happiness is not often a priority and suffers greatly. However, as discussed, it can still be an important indicator for many individuals. Over time, we have seen global increases in happiness, but on a continental level, these changes were not as consistent. Additionally, several relevant societal factors that inform happiness were identified. Perceptions of corruption and generosity did not seen to have a major impact on happiness. However, in predictive models, social support, GDP, healthy life expectancy, and freedom to make life choices were reliable predictors. Additionally, the trained model performed better in 2021 than 2009. This suggests that as time has progressed, these societal factors have become more relevant indicators of happiness.

Given that social support, GDP, healthy life expectancy, and freedom to make life choices were the related to happiness scores during these times of crises, this can inform priorities and response in future crises. Future analyses should explore the role of these factors in times of relative stability. It may be the case that these factors have differing relevancy, and that other factors also show importance.

---

If you enjoyed this project, please consider following me on [Twitter](https://twitter.com/Peter_Nooteboom) and [Linkedin](https://www.linkedin.com/in/peter-nooteboom/).

