# Twitter-sentiment-anaylsis 
[1.2]: http://i.imgur.com/wWzX9uB.png 
Used NLP(Natural Language Processing) determine weather given US Airline Sentiment Dataset, which contains data for over 14000 tweets is positive, negative or neutral.


# Using the following classifier :
1. Random Forest Classifier
2. KNeighborsClassifier
3. Svc( Support vector classifier )



# Method Used in the process:
1. Fetching data from **.CSV** file.
2. spilting test and train data
3. On test data using **TfidfVectorizer**(which gives unqiue indexes to each word)
4. Train model on **RandomForestClassifier** 
    - predict accuracy 
     - print score
5. Train model again on **SVC**
    - predict accuracy
     - print score
6. Finally we use our above trained feautres to go through **KNeighborsClassifier**
7. The final prediction gives us the result in three category 
    ** NEGATIVE **, **POSITIVE**, **NEUTRAL**
 
# Conclusion
  A MODEL WHICH CLASSIFIES THE FEED-IN FEATURES INTO THE NEGATIVE , POSITIVE , NEUTRAL
  ON THE BASE OF TRAINED FEATURED.
