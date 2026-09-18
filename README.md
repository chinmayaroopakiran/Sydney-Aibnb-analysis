# Sydney Airbnb Price Analysis


I chose this project as my first hands-on step into business analytics working with real, messy Airbnb data instead of a pre-cleaned or perfect dataset felt like a more honest way to build practical skills. I picked Sydney specifically because it's where I live and study, and short-term rental pricing is a genuinely current, relevant topic here given ongoing conversations about housing affordability and tourism in the city. This project explores what actually drives Airbnb pricing across Sydney suburbs.  

# Which Sydney suburb is the most and least expensive to stay in?
Answer : Pittwater is the most expensive suburb on average of $996/night, followed by Mosman $931 and Woollahra $795. 

# Does room type affect price?
Answer : Yes, significantly. An entire home/apartment averages $515/night, more than double a hotel room which is AUD 204, nearly 4 times a private room $139, and almost 7 times a shared room $77 which is not surprising, but confirmed clearly in the data.

Tools used:-
Python - pandas, matplotlib, Jupiter notebook

Data source: Inside Airbnb (insideairbnb.com), Sydney listings - Summary information and metrics for listings in Sydney

# Data cleaning:-
1. The raw dataset contained 20,573 listings across 19 columns.
2. 8 listings were missing a minimum_nights value and were removed for the same reason.
3. 2,787 listings were missing a price value and were removed, since price is the core variable this analysis depends on.
4. The neighbourhood_group column was removed entirely, as it contained no data at all, every single row was blank.
5. Columns like last_review, reviews_per_month, and license were left with missing values intentionally as these gaps reflect real listings that simply have no reviews or no licence yet, not broken or incorrect data.
6. After cleaning, 17,778 rows with 18 columns remained, forming a reliable base for the analysis and visualizations later. 
7. 






