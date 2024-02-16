**Introduction**
Welcome to the **Medical Diagnosis & Drug Treatment Prediction Project🗂️**!


**Workflow**
Step 1: I cleaned the 17 missing data since their cancer type and text are both missing. I then converted cancer type into numeric form by using function and if statement instead of LabelEncoder to review some basic concepts of Python.

Step 2: Now it is time to clean dirty text! The steps are

covert all the characters to lowercase
remove unwanted space and non-English characters
tokenize the text into words
create the stopword list
print out the new text without stopwords
You can access the clean text example here 👉 Text_after_cleaning.csv

Step 3: One new thing I added this time is this cool figure Word Cloud, where we can easily visualize the occurrence frequency of the words depending on their size. I would say this is the most fun thing I have added to this project :)

Step 4: Again, after vectorizing the data, it is time to train the Naive Bayes classifier model and predict the outcome.

**Result and Discussion**
The accuracy is 0.8. It is better than the Netflix Genre Classification Project. The medical text is long so I think more unnecessary words can be removed!
