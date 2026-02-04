# 🧠 Brain Scan Image Segmentation using Unsupervised Learning

This project explores unsupervised image segmentation on brain scan images using Python. It demonstrates how raw medical imaging data can be transformed, analyzed, and segmented using K-Means clustering, bridging image processing and machine learning fundamentals.

The work emphasizes data preparation, feature transformation, clustering, and visual interpretation—skills directly relevant to data science and machine learning roles.

## 📌 Project overview

Load and process brain scan images (including DICOM format)

Convert image data into numerical features suitable for ML

Apply K-Means clustering for image segmentation

Visualize clustered regions to interpret intensity-based patterns

Demonstrate an end-to-end analytical workflow on non-tabular data

This project focuses on methodology and reasoning, not medical diagnosis.

## 🛠 Tools & technologies

-> Python

-> NumPy – numerical computation and reshaping

-> Matplotlib – visual analysis and results interpretation

-> Pillow (PIL) – image handling

-> pydicom – medical image ingestion

-> Scikit-learn – K-Means clustering

## 📂 Repository structure
Brain_Scanning.ipynb   # End-to-end analysis and modeling notebook
README.md              # Project documentation

## ⚙️ Environment setup
pip install numpy matplotlib scikit-learn pillow pydicom

## 🔍 Methodology

Data ingestion

Brain scan images loaded from image/DICOM formats

Converted into NumPy arrays for numerical analysis

Exploratory visualization

Intensity distributions and raw scans visualized

Enables qualitative inspection before modeling

Feature preparation

Image reshaped into pixel-level feature vectors

Data structured for unsupervised learning algorithms

Unsupervised modeling

K-Means clustering applied to segment image regions

Cluster assignments mapped back to spatial structure

Result interpretation

Segmented images visualized

Patterns analyzed based on pixel intensity and structure

## 📊 Results

Clear separation of image regions based on intensity

Visual demonstration of how clustering can uncover structure in image data

Practical example of applying ML techniques beyond traditional tabular datasets

## 🤖 This project highlights:

Unsupervised learning workflow

Algorithm selection and clustering behavior

High-dimensional data handling

Mapping model outputs back to real-world representations

Relevant for roles involving ML fundamentals, modeling pipelines, and algorithmic thinking.

## ⚠️ Disclaimer

This project is for educational and analytical purposes only.
It is not intended for clinical or diagnostic use.

## 🚀 Possible extensions

Compare K-Means with Gaussian Mixture Models or DBSCAN

Apply image normalization and noise reduction

Extend to supervised segmentation with CNNs

Scale analysis to larger MRI datasets

## 🧠 Why this project matters

Medical imaging is a real-world domain where data is messy, high-dimensional, and visual. This project demonstrates the ability to reason about such data, choose appropriate algorithms, and communicate results clearly—skills that translate directly to industry data science and ML roles.
