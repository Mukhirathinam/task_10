# Task 10 - KNN: Handwritten Digit Classification

## Objective
Classify handwritten digits using the K-Nearest Neighbors algorithm and identify the optimal value of K.

## Dataset
Scikit-learn Digits Dataset (load_digits)

## Tools Used
- Python
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Loaded the digits dataset and verified shapes of features and labels.
2. Visualized sample digit images to confirm labels.
3. Split dataset into training and testing sets.
4. Applied StandardScaler because KNN is distance-based.
5. Trained KNN model with multiple K values (3,5,7,9).
6. Plotted Accuracy vs K graph to select the best K.
7. Generated confusion matrix to analyze misclassifications.
8. Displayed sample predictions with digit images.

## Deliverables
- Notebook / Python script
- Accuracy vs K plot
- Confusion matrix image

## Conclusion
KNN achieved high accuracy for digit classification. Feature scaling and choosing the optimal K value significantly improved performance.
