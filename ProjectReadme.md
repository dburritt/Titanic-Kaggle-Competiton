Here is where you include:
  - Background on your code files
      Lab3 was used as a template and modified as necessary
  - How to run your code, guide to install any additional packages
      Only packages used in the labs are needed (pandas, numpy, matplotlib, seaborn, sklearn)
      The training dataset is "train.csv"
      The test dataset is "test.csv" 
      The predictions for the test dataset are output into "submission.csv" - This is what was uploaded to kaggle

  - Results, interpretation and reflection
  In conclusion, crossvalidation and grid search were used to get the best the model. This was RandomForestClassifier which had a training accuracy of 0.93. This model scored 0.78708 on Kaggle test data. Looking at other scores on kaggle, it is possible to score a 1 with this dataset. To obtain a better score it is likely more feature engineering has to be done. I did not use the cabin data as most of the values were missing, but it is likely that something useful could be extracted from it. I also used the mean to fill in the missing values for age, a different approach could have been used to fill them. Other methods could be tried, such as filling random ages to based on the standard deviation. The name column also contains the persons title, this could also be considered when filling the ages. Title could also be added as a separate feature. Other features could be created such as grouping Age and Fare into ranges instead of using the raw values. 

  Reflection
    Its interesting applying the course material to a real world example and dealing with a real dataset that isn't perfect. Trying to determine which features to use and how to improve the performance. Its not as easy as the labs where you know the dataset will work. Also interesting thinking about how other features could be created from the ones that are provided.