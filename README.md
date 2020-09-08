# Prediction-Assignment-Writeup
Prediction Assignment Writeup

Project_Machine_Learning

# Create a report describing how you built your model
1. read data  (pml-training.csv) and (pml-testing.csv)
2. check classes with unique(training$classe) [1] "A" "B" "C" "D" "E"
3. use complete.cases() to print a logical vector that indicates complete and missing rows (i.e. rows without NA).
and The data were initially inspected. A number of variables appeared to have missing variables e.g., max_roll_belt.
4. The na.strings argument is for substitution within the body of the file, that is, matching strings that should be replaced with NA.
5. Delete columns with all missing values.
6.delete the first 7 columns are not necessary for prediction with rf.
7. the dimensions of the new df
8. Data Slicing
Cross Validation
60% traning
40% testing
9. Random Forecast for prediction
10. Importance of variables
11. This graph shows the error vs. the number of trees. You can see how the error decreases as the number of trees increases.
12. confusionMatrix
13. predict final
