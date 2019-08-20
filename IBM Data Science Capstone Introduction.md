
 # <p style="text-align: center;"> Is there a correlation between a restaurants ratings and the income levels of a neighborhood ? </p>

## <p style="text-align: center">IBM Data Science Certificate Capstone Project</p>

### Introduction

#### Background

A few weeks ago, my girlfriend and her friends went out for a Saturday girls lunch at an upmarket and expensive restaurant in Johannesburg. The restaurant is set in an exculsive estate and boasts of very scenic views however my girlfriend and her friends did not enjoy it. The drinks were over-priced, the meal portions were little, the service was terrible and the food was mediocre at best. The ladies had to pass by a local KFC to get some chicken to soothe their appetite.

This experience made me wonder. Do we assume that expensive restaurants will have better service than less expensive restaurants. Is the service better in restaurants in higher income areas than in lower income areas? Is there a correlation between income levels and restaurant ratings? This is an interesting question because conventional opinion would say that restaurants in higher income areas have better service which leads to better ratings because the restaurant’s patrons will demand better service and/or the restaurant will offer better service when in a high income neighborhood because they can charge more. But can the data science prove that or is this biased thinking?

My study will look at the data and see whether we can confirm that restaurant service does differ depending on the income levels of the neighborhood. If the study shows there is a link between poor Foursquare ratings and income levels, this would be of major interest to business owners, to restaurant patrons and to a city's management team. For business owners running a restaurant, they might spot an opportunity to gain customers by improving their customer service especially in low income areas. Patrons living in low income neighborhoods would have the ammunition to demand better customer service in the restaurants they frequent. City hall officials might also see this as a form of income segregation and work harder to ensure restaurants in low income areas have the same amenities and service levels as those in middle or high income areas.

The city I have chosen for this study is Toronto, Canada. It’s a relatively wealthy city with a population of approximately 6.5 million people (2016 Canada census). It is also one of the most diverse, multicultural and multiracial cities in the world with 51% of the population made up of visible minorities according to the 2016 Canada census. The big and varied population has resulted in a large number of restaurants and fast food places offering all types of cuisine from Indian to Chinese to South Korean to Ethiopian. This is good for our study as it means we can get a diverse number of restaurants to sample.

### Data acquisition and cleaning

#### Data Sources

We will use the following datasets to work on this study

* A Toronto neighborhood dataset showing average income per neighborhood in Toronto. We have sourced this dataset from the Open Data website for the City of Toronto, http://map.toronto.ca/wellbeing . The dataset has the following features that we need; all the Toronto neighborhoods including their after tax income, the neighborhood population and the neighborhood area in square kilometres.
* A Toronto neighborhood restaurant dataset with average restaurant ratings. We will source this data from Yelp by collecting the ratings of restaurants in each Toronto neighborhood using the Toronto dataset above and the Yelp API. We initially wanted to use Foursquare however the Foursquare API has very little api calls when compared to Yelp. The Foursquare API allows 500 api calls per day for free while the Yelp api allows 5000 api calls per day for free. On top of that Yelp was built for reviews and ratings and has a much larger restaurant reviews database then Foursquare therefore it made more sense to use Yelp. We will query the Yelp API to get a list of restaurants per neighborhood and other information like the restaurant name, location, speciality, rating, review count and opening times. From that we will pick only the specialization, the review count and the rating


```python

```


```python

```
