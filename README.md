Iris Dataset - K-Nearest Neighbors (KNN) Classification
This project demonstrates how to build and evaluate a K-Nearest Neighbors (KNN) classifier using the classic Iris dataset. 
The task includes normalization, hyperparameter tuning (K values), model evaluation, and decision boundary visualization.
🔍 Tasks Performed
 1. Normalize Features
Used StandardScaler to standardize the numeric features.
Label encoded the Species column for classification.

2. Train a K-Nearest Neighbors Classifier
Used KNeighborsClassifier from sklearn.neighbors.
Trained model with varying values of K (1 to 10).

3. Experiment with Different K Values
Evaluated K from 1 to 10.
Recorded accuracy for each K.
Chose optimal K (e.g., K=3) based on test accuracy.

4. Evaluate Model
Used accuracy_score for final accuracy.
Generated confusion_matrix and plotted it using ConfusionMatrixDisplay.

5. Visualize Decision Boundaries
Selected 2 features (PetalLengthCm and PetalWidthCm) to visualize decision boundaries in 2D.
Used meshgrid and contour plots to show regions classified by KNN.

📊 Key Libraries Used
pandas, numpy
matplotlib, seaborn
sklearn.preprocessing, sklearn.model_selection, sklearn.neighbors, sklearn.metrics

