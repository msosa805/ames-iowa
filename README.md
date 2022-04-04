![](https://hosting.photobucket.com/images/p734/sosan4/welcome-ames-iowa.png)   


## Problem Statement 
The city is a growing community boasting a [promising  economy and many great job opportunities](https://www.amestrib.com/story/news/2020/10/16/ames-ranked-top-15-places-live/3678012001/). Ames is also home to Iowa State University. Go Cyclones! It is a college town where sports and academic achievement fill the air with school spirit. Make Ames, Iowa your home today! At Ames Realty, we can help you identify exactly what you need and want in a home. By using machine learning, a number of characteristics can be used to define a property. Some add value; others hurt value. This analysis aims to identify which characteristics are most useful predictors of the price for home buyers in Ames, Iowa. 


## Executive Summary

Training data set from [Ames,Iowa home sales](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt) were catalogued by features of the property and sale price. 2,051 observations from sales between 2006 and 2010 were used to generate the model and tested against 878 homes sold during the same period.


## Models 
Model Name | Training Score | Testing Score
-|-|-
Linear Regression|80%|82%
Ridge|82%|78%
Logistic Regression|81%|81%


## Conclusions

* Holding all else constant, model identified 3 neighborhoods that were associated with higher than average sale prices while 15 or so more were associated with lower sale price.

* Holding all else constant, central air conditioning was associated with an approximately $12,000 higher sale price. This may be worth it! It gets hot in the summer, the average temperature can exceed 80 degrees.

* Having favorable conditions (parks nearby) had a positive association with sale price, holding all else constant. Meanwhile, unfavorable conditions like proximity to railroads and being adjacent to main roads are associated with lower prices. But not everyone views these "unfavorable conditions" the same way--you might find a bargain here. 

* Square Feet is a very valuable predictor of sale price, and it appears to have a more substantial association than outdoor (deck, proch) and finished basement square feet.

* Older homes had lower sale prices than newer homes, holding all else constant.

* My index for usable garage area (#cars) and garage condition (not bad, vs bad) also was a valuable feature. Larger garages with better conditions were associated with higher sale prices.

