#### This is a KNN classifier implemented from scratch, which shows how a KNN classifier properly functions in order to get its output class.
#### I used the 'iris' dataset provided from Scikit-Learn to classify which iris species each data corresponds to.

## KNN (K-Nearest Neighbor)
- classification
- instance-base learning
  - learns the training examples by heart and then generalizes to new instances based on some similarity measure
  - builds the hypotheses from the training instances (builds a database of previous observations)

- Things you need
  1. Distance Metric
  - Euclidean
  - Manhattan
  2. K = # of neighbors to consult (parameter of the algorithm)
  - Time Complexity = O(n)
  3. Method for combining neighbors' outputs
  - Classification: Majority vote / Weighted majority vote
  - Regression: Average (real-values) / Weighted average
