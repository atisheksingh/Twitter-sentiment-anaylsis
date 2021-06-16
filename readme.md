#Twitter-sentiment-anaylsis 

**using the following classifier :**
-Random Forest Classifier 
-KNeighborsClassifier
-Svc( Support vector classifier )

Method Used in the process:
1. Fetching data from **.CSV** file.
2. spilting test and train data
3. On test data using **TfidfVectorizer**(which gives unqiue indexes to each word)
4. Train model on **RandomForestClassifier** 
    4.1 predict accuracy 
    4.2 print score
5. Train model again on **SVC**
    5.1 predict accuracy
    5.2 print score
6. Finally we use our above trained feautres to go through **KNeighborsClassifier**
7. The final prediction gives us the result in three category 
    ** NEGATIVE **, **POSITIVE**, **NEUTRAL**
 
# Conclusion
  A MODEL WHICH CLASSIFIES THE FEED-IN FEATURES INTO THE NEGATIVE , POSITIVE , NEUTRAL
  ON THE BASE OF TRAINED FEATURED.
