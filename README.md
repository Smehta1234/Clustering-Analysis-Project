# Clustering Analysis Project

This project demonstrates the application of three clustering algorithms (K-Means, Hierarchical Clustering, and Mean-Shift) on the Iris dataset from the UCI Machine Learning Repository. The goal is to compare the performance of these algorithms under different preprocessing techniques and evaluate their clustering efficiency using metrics and visualizations.

## Features
- Implementation of three clustering techniques:
  - **K-Means Clustering**
  - **Hierarchical Clustering**
  - **Mean-Shift Clustering**
- Preprocessing options:
  - **Normalization** using StandardScaler
  - **Dimensionality Reduction** using PCA
- Evaluation metrics for clustering performance:
  - **Silhouette Score**
  - **Calinski-Harabasz Index**
  - **Davies-Bouldin Index**
- Visualizations for:
  - Individual clustering results
  - Combined comparisons of clustering methods

## Dataset
The Iris dataset from the UCI Machine Learning Repository is used in this project. It contains 150 samples with four features (sepal length, sepal width, petal length, petal width) and one target label (species).

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```bash
   python clustering_analysis.py
   ```
2. Explore the output visualizations and results.

## Project Workflow
1. **Data Loading**:
   The Iris dataset is loaded directly from its URL.
2. **Preprocessing**:
   - Normalization is applied to scale the data.
   - PCA is optionally applied to reduce the dimensionality to two components.
3. **Clustering**:
   - Each of the three clustering algorithms is applied.
   - Performance metrics are calculated for each configuration.
4. **Visualization**:
   - Clustering results are visualized in 2D scatter plots.
   - Comparative visualizations for all clustering methods are provided.

## Evaluation Metrics
- **Silhouette Score**: Measures how similar a sample is to its cluster compared to other clusters.
- **Calinski-Harabasz Index**: Higher values indicate well-defined clusters.
- **Davies-Bouldin Index**: Lower values indicate better clustering.

## Examples
### Individual Clustering Results
Visualizations of the clusters formed by each algorithm are displayed with:
- Preprocessing configurations (Normalization, PCA).
- Cluster count (where applicable).

### Combined Visualization
A side-by-side comparison of clustering methods using Normalization and PCA.

![Example Visualization](example_visualization.png)

## Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Results
The clustering results are saved as visualizations, and metrics are printed to the console for each algorithm and preprocessing configuration. The project demonstrates how preprocessing affects clustering performance and highlights differences between algorithms.

## Conclusion
This project serves as a comprehensive analysis and comparison of clustering algorithms, showcasing their strengths and weaknesses under various preprocessing scenarios. It can be adapted to other datasets for further exploration.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for the Iris dataset.
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html) for the implementation of clustering algorithms.

