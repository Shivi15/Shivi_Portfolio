# Shivi_Portfolio
Data Science Portfolio

# [Project 1: Covid-19 Spread in US - Project Overview](https://github.com/Shivi15/Covid-19-Spread-in-US)
* Analyzed the spread and gradual shift of Covid-19 prone counties in the US.
* Found out the counties with most covid positive cases, and the highest infection rate.
* Cleaned and performed an inner merge on the two datasets, i.e. Population of each county and Covid-19 cases of these counties.
* Using tableau's racing bar charts and animation found out, only 1.04% of LA counties are infected, 3.3% of Arizona counties are infected, and New York had an alarming infection rate of 13.5%.

Let’s look more closely at the top 10 counties by number of cases.

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Covid-19%20Spread%20images/Counties%20ranked%20by%20Cumulative%20cases%20and%20deaths.gif" alt="Your image title" width="500"/>
</p">
  
Percentage of Population infected by County over time.

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Covid-19%20Spread%20images/Percentage%20of%20population%20infected%20over%20time.gif" alt="Your image title" width="500"/>
</p>

The clustering of dark red counties seems to shift dramatically away from major metropolitan areas and into rural areas with lower population density. Suddenly, Los Angeles County looks fairly under control, while Arizona, Mississippi, and a smattering of counties in the Midwest look devastated.

To put numbers to this:

1. Only 1.05% of LA County is infected, whereas Maricopa County in Arizona (home to the state capital of Phoenix) has an infection rate of 3.3%.
2. New York County (Manhattan) is still alarming with an infection rate of 13.52%!
3. Trousdale County in Tennessee, with a population of only 7816, has an infection rate of 13.2%. It would be impossible to live here and not know at least one person who’s been infected.


# [Project 2: Movie Recommendation System](https://github.com/Shivi15/Movie-Rec_System)
* Developed a Collaborative Filtering Recommender System. Considering only user preferences into account, and if the two users share the same interests.
* Using one-hot encoding, extracted and created a search for a movie by genres.
* Performed data cleaning before learning about the distribution of rating data.
* Implemented two modelling techniques, IBCF and UBCF. Evaluating the ROC curve and Precision-Recall curve, UBCF became the top model with 88.2% accuracy.

Output for the User ID 364 (picked just for example), the following movies are recommended:

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Movie%20Recommendation%20System/Output.png" alt="Your image title" width="500"/>
</p>

# [Project 3: Airbnb Data Analysis - Project Overview](https://github.com/LohithChowdary/Airbnb-Data-Analysis)
* Analyzed Airbnb listings in New York City to understand if nonstandard amenities can be added to increase the revenue.
* Cleaned and performed Exploratory Data Analysis, by implementing techniques like a word cloud, Term generation matrix, visualizing neighbourhoods with high Airbnb listings using tableau on a map and carrying out a sentimental analysis on reviews dataset draw insights.
* Created features from Amenities by performing feature engineering.
* Finally, evaluated 5 different models, and found out that XGBoost showed maximum accuracy in predicting Airbnb listings' prices.

EDA on the price variable was one of the crucial steps in the complete EDA process. It was found that Manhattan’s average price was greater than the rest of the neighborhood groups. Brooklyn also has higher prices and is mostly because it's closer to Manhattan. Staten Island has higher prices because it's near to the central park.

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Images/Airbnb%20Data%20Analysis/Tableau%20Images/Amenities%20Wordcloud.png" alt="Your image title" width="500"/>
</p>

Now, in the image below, you can see that Average price is high for Manhattan. Since, Brooklyn neighbourhoods are close to Manhattan, they tend to have higher average prices. And in Staten Island areas close to state park tend to have higher prices.

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Images/Airbnb%20Data%20Analysis/Tableau%20Images/Neighbourhoods%20with%20high%20prices.png" alt="Your image title" width="500"/>
</p>

A review dataset is taken to derive more insights about the amenities. Customer reviews can provide a wealth of information if mined properly. 

A term document matrix has been created which uses the Airbnb customer reviews to find word associations, given a word it gives back closest words in reviews. Keywords like near, close, around, great, place, transit, store are used to find word associations. Finding associations has revealed some interesting insights. New amenities that interest Airbnb customers are found. These are the amenities that are missing in the primary dataset. As this information is missing in our primary dataset, we relied on foursquare API to get information about nearby amenities.

<p align="center">
<img src="https://github.com/Shivi15/Shivi_Portfolio/blob/main/Images/Airbnb%20Data%20Analysis/Tableau%20Images/Tweets.png" alt="Your image title" width="500"/>
</p>


