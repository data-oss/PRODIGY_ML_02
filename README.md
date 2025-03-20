# Mall Customer Segmentation Model

## Overview
Customer segmentation is a key strategy in marketing and business analytics. This project applies **machine learning clustering techniques** to segment mall customers based on their demographic and spending behavior. The goal is to help businesses tailor marketing strategies, improve customer experience, and increase sales.

## Problem Statement
Shopping malls collect vast amounts of customer data, including age, gender, income, and spending behavior. However, without proper analysis, this data remains underutilized. This project aims to segment customers into meaningful groups, enabling businesses to:
- Personalize marketing campaigns
- Improve customer engagement
- Optimize store layouts and promotions

## Features
- **Data preprocessing**: Handling missing values, encoding categorical variables
- **Exploratory Data Analysis (EDA)**: Understanding customer distribution through visualizations
- **Clustering algorithms**: K-Means, Hierarchical Clustering, and DBSCAN
- **Dimensionality reduction**: PCA for visualization of clusters
- **Model evaluation**: Silhouette score and Elbow method
- **Visualization of customer groups**: Scatter plots, heatmaps, and bar charts

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/mall-customer-segmentation.git
   cd mall-customer-segmentation
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Dataset
The dataset contains the following features:
- **Customer ID**: Unique identifier for each customer
- **Gender**: Male or Female
- **Age**: Customer’s age
- **Annual Income (k$)**: Customer’s yearly income in thousand dollars
- **Spending Score (1-100)**: A score assigned by the mall based on customer behavior

The dataset should be placed in the `data/` directory before running the model.

## Usage
1. Run the Jupyter Notebook to explore the dataset and train the model:
   ```sh
   jupyter notebook model_train_Mallcustomer.ipynb
   ```
2. Modify the notebook or script as needed for custom segmentation analysis.
3. Use the trained model to analyze new customer data and predict segment classifications.

## Methodology
1. **Data Preprocessing**
   - Handle missing values (if any)
   - Encode categorical variables
   - Normalize numerical features

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots to analyze income, age, and spending score
   - Correlation matrix to identify key relationships

3. **Clustering Techniques**
   - **K-Means Clustering**: Used to segment customers into K groups based on similarity
   - **Hierarchical Clustering**: Alternative clustering technique to validate K-Means results
   - **DBSCAN**: Density-based clustering to detect noise and outliers

4. **Model Evaluation**
   - **Elbow Method**: Determines optimal K value for K-Means
   - **Silhouette Score**: Measures cluster quality
   - **Visual Validation**: Scatter plots of clusters

5. **Interpretation of Results**
   - Define cluster characteristics (e.g., High spenders, Budget shoppers, Young professionals)
   - Business recommendations based on segmentation

## Results
The segmentation model effectively identifies distinct customer groups, helping businesses:
- Target high-spending customers with exclusive deals
- Offer personalized recommendations based on spending habits
- Improve product placement and store layout based on demographic preferences

## Future Improvements
- Integrate **deep learning** for more advanced segmentation
- Apply **predictive analytics** to forecast customer lifetime value
- Extend the dataset with **real-time customer behavior tracking**

## Contributing
Contributions are welcome! If you have suggestions for improvement, feel free to fork the repository, create a branch, and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Author
**Dua Zahra**  
GitHub: 
https://github.com/data-oss

---

