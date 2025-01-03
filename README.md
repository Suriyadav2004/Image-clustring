# Image Clustering and Segmentation with Python

This project showcases various image clustering and segmentation techniques using Python. The techniques demonstrated are:

1. **K-Means Clustering**
2. **MeanShift Clustering**
3. **DBSCAN Clustering**
4. **Gaussian Mixture Model (GMM)**
5. **Watershed Segmentation**
6. **Agglomerative Clustering**

## Requirements

To run the code, ensure you have the following libraries installed:

```bash
pip install opencv-python scikit-learn matplotlib
## Description
This project applies different clustering and segmentation methods to images, including:

## K-Means Clustering
Used to partition an image into clusters based on pixel similarity.

## MeanShift Clustering
A clustering approach that does not require specifying the number of clusters in advance.

## DBSCAN Clustering
A density-based clustering technique that can identify clusters of varying shapes and sizes.

## Gaussian Mixture Model (GMM)
A probabilistic model that assumes all data points are generated from a mixture of several Gaussian distributions.

## Watershed Segmentation
A method used for detecting boundaries between different regions in an image.

## Agglomerative Clustering
A hierarchical clustering technique that builds clusters by merging smaller clusters.

## How to Use
Clone the repository to your local machine.

## Install the required libraries using the provided pip install command.

Run the scripts for each clustering and segmentation technique. Each script loads an image, applies the respective method, and displays the original and processed images side by side.

## Example
The repository includes example scripts for each technique. Below is a brief description of each script:

kmeans_clustering.py: Demonstrates K-Means clustering.

meanshift_clustering.py: Demonstrates MeanShift clustering.

dbscan_clustering.py: Demonstrates DBSCAN clustering.

gmm_clustering.py: Demonstrates Gaussian Mixture Model clustering.

watershed_segmentation.py: Demonstrates Watershed segmentation.

agglomerative_clustering.py: Demonstrates Agglomerative clustering.

## Results
Each script generates visual output displaying the original image alongside the clustered/segmented image. This allows for a clear comparison of the effectiveness of each method.

## Contributing
Feel free to submit issues, fork the repository, and send pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
