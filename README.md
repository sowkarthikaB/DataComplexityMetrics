## Technologies
Python
Scikit-learn
NumPy
Pandas

## Steps
1. Load dataset
2. Compute data complexity measures
3. Calculate Adjacency Matrix
4. Create MST using Prim's
5. Find edges connecting two different classes in MST
6. Make the data points of each class along with its 2-NN as base model
7. use rbf-SVM on each subproblem (Train multiple SVM models)
8. Use weighted approach to predict the final class (Dynamically select ensemble)
