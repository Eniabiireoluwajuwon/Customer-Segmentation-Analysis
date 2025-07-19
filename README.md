# Customer-Segmentation-Analysis
## Ove

This project focuses on the analysis of customer behaviour for an online retail dataset. The goal is to segment customers into distinct groups based on their purchasing patterns using machine learning algorithms. The analysis employs K-Means clustering and Principal Component Analysis (PCA) to identify customer segments, enabling targeted marketing, personalized recommendations, and efficient resource allocation.

## Problem Statement

In e-commerce, understanding the different types of customers is critical for designing effective marketing strategies and improving customer retention. This project addresses the challenge of identifying meaningful customer segments from transactional data, which can then be used to enhance customer engagement and drive business growth.

## Key Features

- **Customer Segmentation**: Group customers into segments based on their buying behaviour.
- **Exploratory Data Analysis (EDA)**: Visualize distributions, correlations, and interactions between customer features.
- **Clustering**: Use KMeans clustering to segment customers into 4 distinct groups.
- **Dimensionality Reduction**: Use PCA to reduce the feature set to 2 dimensions for easier visualisation of the segments.
- **Cluster Profiling**: Provide detailed descriptions of each cluster for strategic insights.

## Tools Used

- **Python**: Programming language for data manipulation and analysis.
- **Pandas**: Data manipulation and analysis library.
- **Matplotlib & Seaborn**: Libraries for data visualisation.
- **Scikit-Learn**: Machine learning library for KMeans clustering and PCA.
- **Jupyter Notebooks**: Used for running and documenting the analysis.

## Installation Instructions

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/oluwajuwoneniabiire/customer-segmentation-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd customer-segmentation-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    - If `requirements.txt` is not available, install the required libraries manually using `pip`:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```

## How to Use / Run the Project

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Launch the notebook and run all cells to execute the analysis and see the results.

3. The customer segments will be generated using KMeans clustering, and visualised using PCA for 2D representation.

## Directory Structure
customer-segmentation-analysis/
│
├── data/ # Folder containing the raw dataset
│ └── OnlineRetail.xlsx
│
├── notebooks/ # Jupyter notebooks for the analysis
│ └── customer_segmentation_analysis.ipynb
│
├── requirements.txt # List of required Python dependencies
│
└── README.md # Project documentation (this file)


## Results / Outputs

The analysis identifies four distinct customer segments based on their purchasing behaviours. The key findings include:

- **Cluster 0**: Dormant customers who have made only a few purchases in the past.
- **Cluster 1**: High-frequency, high-spending customers who engage with the platform regularly.
- **Cluster 2**: Mid-tier customers with moderate activity.
- **Cluster 3**: Very recent, high-value customers with frequent transactions.

These insights can be used to design targeted marketing campaigns, improve customer retention, and optimize resource allocation.

## Contributors

- **Eniabiire' Oluwajuwon**: Author and data analyst.
- **Contributors' Names** (if any): Additional contributors.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

