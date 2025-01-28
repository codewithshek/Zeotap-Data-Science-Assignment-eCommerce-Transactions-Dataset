## PROJECT -- 01

> Exploratory Data Analysis (EDA) on Customer Data

This project involves performing Exploratory Data Analysis (EDA) on customer, product, and transaction datasets to derive meaningful insights. The analysis focuses on understanding customer demographics, transaction patterns, and product popularity. Key visualizations include customer distribution by region, signup trends over time, and sales analysis by product category. The insights gathered will help inform marketing strategies and improve customer engagement.


## PROJECT -- 02

> Lookalike Model Development

This project entails building a Lookalike Model that recommends similar customers based on their profiles and transaction history. The model merges customer demographic data with transaction records to create comprehensive profiles. Using cosine similarity, the model identifies the top three lookalikes for each of the first twenty customers (C0001 - C0020), providing valuable insights for targeted marketing efforts.


## PROJECT -- 03

> Customer Segmentation Using Clustering Techniques

This project focuses on customer segmentation through clustering techniques using both customer profile information and transaction data. The K-Means clustering algorithm is employed to identify distinct customer segments based on spending behavior and transaction frequency. Key metrics such as the Davies-Bouldin Index and silhouette scores are calculated to evaluate cluster quality, providing insights into customer behavior that can guide marketing strategies.


## Directory Structure

```

github.com/codewithshek/zeotap-data-science-assignment-ecommerce-transactions-dataset/
    ├── Customer_Segmentation_Results.csv
    ├── Customers.csv
    ├── Products.csv
    ├── Transactions.csv
    ├── Task-1/
    │   ├── Task-1_EDA.ipynb
    │   └── .ipynb_checkpoints/
    │       └── Task-1_EDA-checkpoint.ipynb
    ├── Task-2/
    │   ├── Lookalike.csv
    │   ├── Task-2_Lookalike.ipynb
    │   └── .ipynb_checkpoints/
    │       ├── Lookalike-checkpoint.csv
    │       └── Task-2_Lookalike-checkpoint.ipynb
    └── Task-3/
        ├── Task-3_Clustering.ipynb
        └── .ipynb_checkpoints/
            └── Task-3_Clustering-checkpoint.ipynb
```

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/codewithshek/Zeotap-Data-Science-Assignment-eCommerce-Transactions-Dataset.git
cd Zeotap-Data-Science-Assignment-eCommerce-Transactions-Dataset/
```

## Usage

Each project folder contains a Jupyter Notebook for analysis and relevant reports in PDF format. You can run the notebooks locally using Jupyter Lab or Jupyter Notebook:

```bash
jupyter notebook Project-1/Task-1_EDA.ipynb
jupyter notebook Project-2/Task-2_Lookalike.ipynb
jupyter notebook Project-3/Task-3_Clustering.ipynb
```

This will allow you to explore the code and visualizations interactively.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.
