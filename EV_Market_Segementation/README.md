# Electric Vehicle Market Segmentation

## Overview
This project focuses on segmenting customers in the electric vehicle market based on their vehicle type, battery type, charging type, and battery capacity. The objective is to optimize product features and target specific customer segments to enhance market competitiveness and customer satisfaction.

## Project Structure
- `evdata.csv`: Dataset containing information about electric vehicles, including vehicle type, battery type, charging type, and battery capacity.
- `EV_Market_Segmentation.ipynb`: Jupyter Notebook containing the code for data exploration, segmentation, profiling, and target segment selection.
- `README.md`: This file, providing an overview of the project.

## Code
The `EV_Market_Segmentation.ipynb` notebook includes the following sections:
1. Data Exploration: Loading and examining the dataset to understand its structure and basic statistics.
2. Feature Engineering and Preprocessing: Selecting relevant features for segmentation and preprocessing the data by encoding categorical variables and normalizing numerical features.
3. Dimensionality Reduction: Using Principal Component Analysis (PCA) to reduce the dimensionality of the feature set.
4. Clustering: Employing K-means clustering algorithm to segment the customers based on the reduced feature set.
5. Segment Profiling: Analyzing and profiling each segment to understand the characteristics and preferences of different customer groups.
6. Target Segment Selection: Identifying the target segment based on predefined criteria, such as the segment with the highest average battery capacity.

## Requirements
The project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- matplotlib

## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the `EV_Market_Segmentation.ipynb` notebook to execute the code and perform customer segmentation and target segment selection.
4. Modify the code or criteria according to your specific requirements.