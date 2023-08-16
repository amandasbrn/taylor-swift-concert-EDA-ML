# Taylor Swift Concert Data Wrangling, EDA, Revenue Prediction

As one of Taylor Swift's listeners since 2010, I thought it will be fun to do a data science and machine learning project using a dataset of her concert from Fearless Tour to Reputation Stadium Tour. Not gonna lie, I'm having so much fun doing this project! Not to mention, this is my first ever proper data science project yet it is so complex because the dataset is pretty dirty.

A little bit of background about this project, basically I analyzed Taylor Swift's concert and made a revenue prediction. I unexpectedly got the dataset from Kaggle.com. I got to learn and practice a LOT of data wrangling, data manipulation, data visualization, and lastly, did feature engineering and built my first ML model independently. Prior to this project, I learned basic-intermediate statistics from Krish Naik's youtube and learn machine learning algorithms (so far I have learned regression and classification), feature scaling, and encoding on Udemy since July 14, 2023.

## What is in my project...
This project consists of 4 parts;
1) Data wrangling
2) Exploratory Data Analysis
3) Machine Learning - Revenue prediction with Decision Tree Regressor
4) Revenue prediction for Taylor Swift's The Eras Tour in Singapore

and Machine Learning part is divided into three experiments:
1) Multiple Linear Regression
2) Decision Tree Regressor model with LabelEncoder method
3) Decision Tree Regressor model with One Hot Encoding method
as they all gave different results.

## What is in the dataset...
1) City: The name of the city where the concert took place.
2) Country: The name of the country where the city is located.
3) Venue: The name of the venue where the concert was held.
4) Opening act(s): The names of the artists or bands who performed as the opening act before the main performer(s).
5) Attendance (tickets sold / available): The number of tickets sold and the total number of tickets available for the concert.
6) Revenue: The revenue generated from ticket sales during the concert.
7) Tour: The name of the concert tour associated with the event.

## Result of this project...
1) Data wrangling:
   I managed to clean the dataset by checking and removing duplicates, filling NaN with mean, replacing characters (the dataset has unreadable symbols like '\x97', counting values from strings that are separated by a delimiter, etc.
2) Exploratory Data Analysis
   I do a little bit of descriptive statistics and make a few visualizations, mostly with Seaborn. I analyzed ticket price and tour revenue. Since most of the shows had opening acts, I attempted to analyze the price and revenue with/without opening acts. I got a meal full of insights right there.
3) Revenue Prediction
   I attempted to do 2 different algorithms; Multiple Linear Regression & Decision Tree Regressor.
   For Multiple Linear, I got a 94% score but the error is too huge, around 25%
   While on Decision Tree Regressor, I got a 97% score with a 9% error (using LabelEncoding)
   and 95% score with a 12% error (with One-Hot Encoding)
   I also did cross-validation. For the one that used LabelEncoding, I got a 94% average score
   and for one-hot encoding, I got a 93% average score.

## What I should improve next...
1) try to implement oversampling, because there are hundreds of shows with opening acts and only around 20+ shows without opening acts. I think it can be a bias
2) try to reduce error
3) pay attention to the correlations
4) use another advanced algorithm

## My resources...
1) Krish Naik's youtube
2) Udemy
3) A lot of google searches (geeksforgeeks, kaggle, github, medium articles)
4) ChatGPT: I use chatGPT to help me check if my code syntax is correct or not. I also asked a lot about what is oversampling and how to do it, how to count two strings within the same row that are separated by a delimiter, etc. It answers complex parts well.
