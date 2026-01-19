
# Identifying Clusters of African Nations Based on GDP Growth Trajectories

![Sunset_in_Africa](https://github.com/user-attachments/assets/cb561a7c-6f4f-424f-894f-17f74e219b58)

## What the project does

This project applies **unsupervised machine learning** specifically the **K-Means clustering algorithm** to analyze and group African nations based on their GDP growth patterns from **2000 to 2023**.

The analysis follows a standard data science pipeline:

* **Preprocessing:** Transposing data from wide to long format and scaling features using `StandardScaler` to ensure fair distance calculations.
* **Optimization:** Using the **Elbow Method** to determine that 3 clusters provide the most meaningful grouping.
* **Clustering:** Categorizing 34 African countries into distinct economic profiles.
* **Visualization:** Generating average GDP trend lines and comparative bar plots (displayed in billions of USD) to visualize the trajectory of each cluster.
* **Evaluation:** Validating the model's performance using Silhouette, Davies-Bouldin, and Calinski-Harabasz scores.

## Why the project is useful

Understanding economic trajectories is vital for regional development. This project is useful because:

* **Identifying Peers:** It helps policymakers see which countries share similar economic challenges and successes.
* **Economic Benchmarking:** It highlights major regional players (like Nigeria and South Africa) versus steadily growing smaller economies, allowing for better-targeted economic research.
* **Data-Driven Insights:** It moves beyond simple geographical grouping to group countries by their actual economic performance over two decades.

## How users can get started with the project

To replicate this analysis or explore the data, follow these steps:

### 1. Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install pandas matplotlib scikit-learn numpy

```

### 2. Dataset

Download the "GDP Growth of African Countries" dataset from [Kaggle](https://www.kaggle.com/datasets/stealthtechnologies/gdp-growth-of-african-countries).

### 3. Running the Analysis

1. Load your data into a DataFrame named `Africa`.
2. Filter the years to focus on the 2000–2023 period.
3. Run the clustering script to generate the Elbow Plot.
4. Set `optimal_k = 3` and execute the pipeline to generate the final cluster visualizations and membership tables.

## Where users can get help with the project

If you encounter issues or have questions regarding the methodology:

* **GitHub Issues:** [Insert your GitHub Link here]
* **Documentation:** Refer to the `scikit-learn` documentation for deeper insights into [K-Means](https://www.google.com/search?q=https://scikit-learn.org/stable/modules/clustering.html%23k-means) and [StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html).
* **Contact:** You can reach out to the maintainer via [Insert your Email or Portfolio Link].


Contributions are welcome! If you would like to add more countries, explore different timeframes, or test different clustering algorithms (like Hierarchical Clustering), feel free to fork this repository and submit a pull request.

