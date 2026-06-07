# Assignment-08-Clustering-and-Dimensionality-Reduction
Implementation of KMeans and Hierarchical Clustering algorithms on the Iris dataset using Python and Scikit-Learn, including data preprocessing, cluster visualization, and performance analysis.

## Objective

The objective of this assignment is to understand and apply clustering techniques on a real-world dataset using unsupervised machine learning algorithms.

This project uses the Iris dataset from Scikit-Learn and implements:

- KMeans Clustering
- Hierarchical Clustering
- Cluster Visualization

---

## Dataset

The Iris dataset is a well-known dataset containing measurements of iris flowers.

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Since clustering is an unsupervised learning task, the species (target) column is not used during model training.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- SciPy
- Jupyter Notebook

---

## Project Structure


---

## Loading and Preprocessing

1. Load the Iris dataset from Scikit-Learn.
2. Convert the dataset into a Pandas DataFrame.
3. Remove the target/species column.
4. Use only numerical features for clustering.

---

## KMeans Clustering

### How It Works

KMeans divides data into K clusters by:

1. Initializing K centroids.
2. Assigning points to the nearest centroid.
3. Updating centroid positions.
4. Repeating until convergence.

### Why KMeans?

- Efficient for numerical datasets.
- Works well on the Iris dataset.
- Easy to visualize and interpret.

---

## Hierarchical Clustering

### How It Works

Hierarchical clustering builds clusters step-by-step by merging the closest clusters until the desired number of groups is reached.

### Why Hierarchical Clustering?

- Does not require random initialization.
- Produces a dendrogram for cluster analysis.
- Suitable for small datasets like Iris.

---

## Visualizations

The project includes:

- KMeans Cluster Plot
- Hierarchical Cluster Plot
- Dendrogram

These visualizations help understand the grouping of Iris flower samples.

---

## Results

Both KMeans and Hierarchical Clustering successfully identify natural groupings within the Iris dataset.

KMeans provides fast and efficient clustering, while Hierarchical Clustering offers additional insights through the dendrogram structure.

---

## Author

Thwoyyiba Nasreen c

