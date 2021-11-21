# PROJECT: WRITE A DATA SCIENCE BLOG POST

The current project at Udacity is about analyzing AirBnB data for Seattle and writing a blog article based on my analysis. In my analysis, I followed the typical procedure for data analysis. First, I gathered data and assessed it visually and programmatically. In the end, I analysed the data based on three questions:

1. In what range are the listings prices distributed?
2. How does the listings price correlate with other numerical variables?
3. In what time frame do the hosts respond?

Lastly, I developed a model to predict listing prices.

## Libraries

(have a look at `project-1-ipynb` in the section 'packages')
- Jupyter Notebooks
- NumPy
- Pandas
- SciKit
- Matplotlib
- Seaborn

## Files

- `project-1.ipynb`: Jupyter with analysis of the datasets
- `listings.csv`: CSV file with data about the listings, for example name or ratings
- `calendar.csv`: CSV file with calendar data about the listings
- `reviews.csv`: CSV file with critics about the listings (NOT USED)
- `blog.md`: Blog article about the dataset
- `cover.jpg`: Cover photo for blog article
- `*.png`: Photos for blog article questions
- README

## Results

The available AirBnB data from Seattle gives the opportunity in many areas to siphon off interesting knowledge via listings. Therefore, it was important to focus on one subarea. In my case, it was price and the variables that depend on it. 

- Most apartments are rented in the price range between $50 and $200
- The price of the apartments correlates with the accommodations, bathrooms, bedrooms and beds, not with the host's response time, number of listings or number of reviews
- Most hosts respond quite quickly. However, there are also hosts who take a very long time to respond.

## Acknowledgements
- [Kaggle](https://www.kaggle.com/airbnb/seattle)  for the dataset
- Udacity with necessary code and knowledge
- Stackoverflow for [custom color palettes](https://stackoverflow.com/questions/50192121/custom-color-palette-intervals-in-seaborn-heatmap) and [approach to missing data](https://stackoverflow.com/questions/37366717/pandas-print-column-name-with-missing-values)
- Photo by [Stephen Plopper](https://unsplash.com/@splopper14?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) from [Unsplash](https://unsplash.com/photos/UmEYn_GYqFo)