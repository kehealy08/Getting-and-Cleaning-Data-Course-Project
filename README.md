
# "Getting and Cleaning Data" Course Project

This is the "Getting and Cleaning Data" course project. The run_analysis.R file contains a code that does the following:

1. Downloads and unzips the data file (if not already existing in working directory)
2. Loads the activity and feature labels 
3. Extracts only the wanted features  with "mean" or "sd" in the label
4. Loads the training data, keeping only columns with wanted features
5. Load the training activity, and subject datasets 
6. Merges the training data, activity, and subject datasets
7. Loads the test data, keeping only columns with wanted features
8. Load the test activity, and subject datasets
9. Merges the test data, activity, and subject datasets
10. Merges the test and training datasets together
11. Converts activity and subject columns into factors
12. Output a tidy dataset (tidy.txt) with mean value of each variable for each subject and each activity
>>>>>>> 4d750407437d23688cb6a8aca7aa80b2462400bc
