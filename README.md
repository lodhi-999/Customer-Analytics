This repository contains solutions for three key tasks related to customer analytics, recommendation systems, and clustering. The tasks are implemented using Python and include:

1. **Exploratory Data Analysis (EDA)** and Business Insights
2. **Lookalike Model**
3. **Customer Segmentation / Clustering**




## Task 1: Exploratory Data Analysis (EDA) and Business Insights

**EDA Code**:
   - Loaded and cleaned data from `Customers.csv`, `Products.csv`, and `Transactions.csv`.
   - Explored key metrics such as total spending, average purchase frequency, and product preferences.
2. **Insights**:
   - Identified top-performing customers and products.
   - Observed seasonality trends in purchases.
   - Highlighted customer segmentation opportunities based on spending patterns.
3. **Deliverables**:
   - A Jupyter Notebook/Python script containing the EDA codes.
   - A PDF report with business insights.




## Task 2: Lookalike Model

1. **Feature Engineering**:
   - Created customer profiles by aggregating transactional and product data.
   - Encoded product categories and calculated metrics such as total spending and purchase frequency.
2. **Similarity Calculation**:
   - Used **cosine similarity** to find lookalikes.
   - Standardized features to ensure equal contribution to similarity scores.
3. **Output**:
   - Generated `Gaurav_Lodhi_Lookalike.csv`, which maps each customer (`C0001`–`C0020`) to their top 3 similar customers along with similarity scores.
4. **Deliverables**:
   - A Jupyter Notebook/Python script codes of the model.
   - The `Gaurav_Lodhi_Lookalike.csv` file.



  
## Task 3: Customer Segmentation / Clustering

1. **Data Preparation**:
   - Aggregated transaction and profile data.
   - Standardized numerical features.
2. **Clustering Algorithm**:
   - Used **KMeans** to segment customers with cluster sizes ranging from 2 to 10.
   - Selected the best number of clusters based on the lowest Davies-Bouldin Index.
3. **Visualization**:
   - Created scatter plots to visualize clusters.
   - Highlighted key differences between clusters.
4. **Output**:
   - Printed the number of clusters, DB Index, and cluster centers to the console.
5. **Deliverables**:
   - A Jupyter Notebook/Python script containing the logic.
   - A report on clustering results.



  
