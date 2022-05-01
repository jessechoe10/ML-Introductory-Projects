I experimented with different features and I learned that Quarter 2 and Quarter 3 grades had the highest accuracy rate in terms of my linear regression model.

Here is the output for Quarter 2 vs Quarter 3 grades.

`y = 1.11 x + -1.41` <- This represents the line of best fit with both coefficients rounded to two decimal places.
`Accuracy:  85%` <- This represents the corresponding accuracy. The highest accuracy of all three datasets. The train/test split was around 15%.

`y = 0.95 x + 0.32` <- This represents the line of best fit with both coefficients rounded to two decimal places.
`Accuracy:  77%` <- This represents the corresponding accuracy. The highest accuracy of all three datasets. The train/test split was around 20%.

`y = 1.06 x + -1.10` <- This represents the line of best fit with both coefficients rounded to two decimal places.
`Accuracy:  70%` <- This represents the corresponding accuracy. The highest accuracy of all three datasets. The train/test split was around 20%.

I decided to use the first line of best fit to predict fourth quarter grades (final grades). You can find the predicted final grades in the `q4preds.csv` file.

Dataset: https://www.kaggle.com/datasets/impapan/student-performance-data-set
