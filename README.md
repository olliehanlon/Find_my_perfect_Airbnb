A data analytics project which creates an advanced filtering function to make finding your perfect Airbnb much easier. Motivation for this project stems from the often overwhelming number of Airbnb options, even after traditional filters such as price and number of beds. I wanted to streamline a users Airbnb search by analysing themes within the listing descriptions and reviews of Airbnbs. My final function allows the user to select Airbnb options based on features such as cozy, spacious and quiet.

This project uses natural language processing and unsupervised learning models on a large data set from kaggle (https://www.kaggle.com/datasets/erikbruin/airbnb-amsterdam?select=listings.csv), containing Airbnb listings/reviews in Amsterdam. Methods used include K-means clustering and Topic Modelling.

Table of Contents: 
1. Load Data Sets
2. Data Checks
  2.1 Listings Data Checks
  2.2 Reviews Data Checks
3. Natural Language Processing
  3.1 Natural Language Processing of Listings Data Set
  3.2 Natural Language Processing of Reviews Data Set
4. Exploring Key Trends
5. Simplistics Model
  5.1 Divide Listings into Categories
  5.2 Divide Reviews into Categories
6. Topic Modelling
7. K-means Clustering
8. Advanced Filter
