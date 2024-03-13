# Fashion MNIST Cluster Analysis

The Jupyter notebook contains code for analyzing the Fashion MNIST dataset using various dimensionality reduction techniques and clustering algorithms.

## Dataset Description
The Fashion MNIST dataset consists of 70,000 grayscale images of fashion items across 10 categories. Each image is 28x28 pixels.

## Usage
1. Download the Jupyter notebook file `Fashion MNIST Cluster Analysis.ipynb`.
2. Ensure you have the required dependencies installed (`numpy`, `matplotlib`, `scikit-learn`, etc.).
3. Download the Fashion MNIST dataset from Kaggle (https://www.kaggle.com/datasets/zalando-research/fashionmnist) or download `Dataset.zip`, unzip it and place it in the same directory as the notebook.
4. Open the notebook in Jupyter and execute each cell sequentially.

## Notebook Sections
- **Data Loading and Preprocessing**: Loads and preprocesses the Fashion MNIST dataset, splits it into training, validation, and test sets.
- **PCA Analysis**: Identifies the number of components needed to preserve 95% of the variance and visualizes the effect of PCA on image representations.
- **Dimensionality Reduction Visualization**: Generates scatter plots for PCA, t-SNE, LLE, and MDS to visualize high-dimensional data in 2D space.
- **Clustering Analysis**: Clusters images using K-Means and Gaussian Mixture Model after dimensionality reduction and visualizes the clusters to identify similar clothing items.

## Conclusion
The notebook provides insights into the structure of the Fashion MNIST dataset, demonstrating the effectiveness of dimensionality reduction techniques and clustering algorithms for understanding and organizing image data.

Feel free to explore the notebook and experiment with different parameters to further analyze the dataset. If you have any questions or suggestions, please reach out.
