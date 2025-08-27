Which model performed better and why?

The Random Forest model usually performs slightly better than Logistic Regression (around 96–98% vs. 93–96%). This happens because Random Forest is an ensemble method that combines many decision trees, making it better at capturing complex patterns in pixel values. Random forest also performs better on non-linear pixel patterns thus there is higher accuracy as compared to logistic regression.

What do accuracy and confusion matrix mean?

Accuracy: Out of all digit images tested, what fraction were classified correctly. Example: 0.96 means 96 out of 100 images are predicted correctly.

Confusion matrix: A table that shows how often each digit was predicted correctly, and where the model confused one digit with another. For example, if the model predicts some “9”s as “4”s, that shows up in the matrix.

Interesting observations about the dataset:

In small 8×8 pixel images, certain digits can be difficult to distinguish due to their shapes. For example: 1 vs. 7 can appear similar in some cases. Overlapping strokes in 4 vs. 9 can lead to confusion. Despite their low resolution, both models achieve high accuracy, showing that even simple ML models can recognize handwriting effectively.
