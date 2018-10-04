==============================================================================
Sentiment Analysis on the reviews of customers' e-commerce purchase experience 
and Naive Bayes Classification to predict whether customers will recommend 
their purchase based on their sentiment category
==============================================================================

=========================================
Background 
=========================================
One of the challenges that businesses face is how to gain a better understanding of the voice of the customer. This issue can be addressed by extracting additional information from customer reviews, using sentiment analysis. Customer feedback provides a useful platform to discover a huge range of customer-initiated reactions to the product(s) that they have purchased. Text analytics provide businesses a more holistic picture of customers’ satisfaction or dissatisfaction. It is insufficient to rely on customers’ ratings alone to find out their experiences. This is because reviews can provide important feedback to businesses, that would not be captured using a Likert scale. For instance, a five-star review can contain important requests for improved delivery time or customer support. Uncovering deeper insights about customers’ reviews enable businesses to respond to reviews more strategically and effectively and consider modifying their current systems and approaches so that they can better serve their customers.

=========================================
Associated tasks
=========================================

- Regression: 
Predicting of bike rental demand for registered users vis a vis casual users based on the environmental factors 
	In particular, decision tree regression is used because it captures the non linearity of the dataset and is more robust to outliers.
   

=========================================
Files
=========================================

	- Readme.txt
	- Womens-Clothing-E-Commerce-Reviews.csv : bike sharing counts aggregated on hourly basis. 23486 Records
    Dataset obtained from Kaggle (https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews/home) 

=========================================
Dataset characteristics
=========================================	

	- Clothing ID: Specific product being reviewed
	- Age : Reviewers' age.
	- Title : Title of the review
	- Review Text: Review body.
    - Rating: Product's score given by the customer from 1 Worst, to 5 Best.
    - Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
    - Positive Feedback Count: Number of other customers who found this review positive.
    - Division Name: Categorical name of the product high level division.
    - Department Name: Categorical name of the product department name.
    - Class Name: Categorical name of the product class name.
	
