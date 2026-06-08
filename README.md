# K-Means Clustering Algorithm From Scratch

A machine learning project that implements the K-Means Clustering algorithm from scratch using Python without relying on pre-built clustering libraries. The project demonstrates how unsupervised learning can be used to group similar data points and perform image color reduction.

<img src="color-reduction.gif" alt="drawing" width="600px"/>

## Project Overview

K-Means is one of the most widely used unsupervised machine learning algorithms. It partitions data into K clusters by iteratively assigning points to the nearest centroid and updating centroid positions until convergence.

This project implements the complete K-Means workflow from scratch and applies it to image color quantization (color reduction).

## Features

* K-Means Clustering implemented from scratch
* Random centroid initialization
* Distance-based cluster assignment
* Iterative centroid updates
* Convergence detection
* Image color reduction using clustering
* Visualization of clustering results

## Project Structure

```text
K-Means-Algorithm-From-Scratch/
│
├── K-means.ipynb          # Notebook with implementation and explanations
├── k-means.py             # Python implementation
├── image.jpg              # Sample image
├── color-reduction.gif    # Demonstration output
├── make_gif.py            # GIF generation script
├── images/                # Generated output images
└── README.md
```

## Technologies Used

* Python
* NumPy
* Matplotlib
* OpenCV (cv2)
* Scikit-learn (for comparison and utilities)

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move into the project directory:

```bash
cd K-Means-Algorithm-From-Scratch
```

Install dependencies:

```bash
pip install numpy matplotlib opencv-python scikit-learn
```

## Running the Project

Run the notebook:

```bash
jupyter notebook K-means.ipynb
```

Or execute the Python script:

```bash
python k-means.py
```

## How K-Means Works

1. Select K initial centroids.
2. Assign each data point to the nearest centroid.
3. Compute new centroids as the mean of assigned points.
4. Repeat steps 2 and 3 until centroids stop changing significantly.
5. Output the final clusters.

## Application: Image Color Reduction

The algorithm is applied to image compression by reducing the number of unique colors in an image.

Benefits:

* Reduced image size
* Simplified color palette
* Faster image processing

## Learning Outcomes

Through this project, I gained experience with:

* Unsupervised Machine Learning
* Clustering Algorithms
* Distance Metrics
* Numerical Computing with NumPy
* Data Visualization
* Image Processing Concepts
* Algorithm Implementation from Scratch

## Future Enhancements

* K-Means++ Initialization
* Elbow Method for Optimal K Selection
* Silhouette Score Evaluation
* Interactive Visualization
* Support for Custom Datasets

## Author

**Satheesh Rallapalle**

Machine Learning and Data Science Enthusiast

## License

This project is licensed under the MIT License.


