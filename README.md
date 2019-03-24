# A study of factors effecting the price & quality of Airbnb listings

Airbnb is a popular accomodation listings site that operates around the world. In this study I will seek to get a better understanding of factors that effect the price and quality of listings.

I will seek to do this by trying to answer the following specific questions:

1. What factors help predict price?
2. Are superhosts more expensive than non-superhosts?
3. What factors help us predict a 'superhost' ?

To help me answer these questions, I have access to a dataset of listings data that relates to Airbnb listings in Seattle, USA. While my findings therefore may include particularities to Seattle Airbnb listings - my findings may suggest answers that may also be true for listings more generally anywhere in the world.

## Files included in project

- airbnb.ipynb: Notebook of code of the study
- README.md: This readme file

## Code libraries used in project

numpy, pandas, matplotlib, seaborn, sklearn.linear_model, sklearn.model_selection, sklearn.metrics, sklearn.preprocessing, statsmodels.api.

## Results

So from this study we got the following answers to the questions posed:

**1. What factors help predict price?**

Biggest features related postively to price:
- neighbourhood_group_cleansed: 'University District' has a positive impact on price
- room_types: Entire home/apt, Private room, Shared room

Biggest features related negatively to price:
- neighbourhood_cleansed: 'University District' has a negative impact on price
- Several cancellation polices have a negative impact on price (moderate, flexible, strict)
- Various host response times have a negative impact on price

**2. Are superhosts more expensive than non-superhosts?**

Despite an observed small difference in price between superhosts and non-superhosts from the data - we have evidence to suggest that this difference is not significant i.e. that superhosts are not more expensive than superhosts overall.

**3. What factors help us predict a 'superhost' ?**

Good review scores for communication and cleanliness are key features that can help predict a superhost.

While it should be emphasised that these findings relate specifically to Airbnb lisitings in Seattle, this findings may also be suggestive of answers to these questions that may also be true for listings anywhere in the world. Further study and analysis of listings data from around the world would be needed to confirm this.
