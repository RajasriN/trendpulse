# TrendPulse Part 3: Exploratory Data Analysis (EDA) & Visualization

This module represents **Part 3** of the TrendPulse project, focusing on Exploratory Data Analysis (EDA) and professional data visualization across multi-region YouTube trending datasets (US, GB, and IN).

## 📂 Directory Contents

* **`TrendPulse_Part3.ipynb`**: The main Jupyter Notebook containing data merging, feature engineering (engagement scores, log transformations), and visualization logic.
* **`log_views_distribution.png`**: Distribution plot highlighting data skewness in view counts using a logarithmic scale (`log1p`).
* **`engagement_correlation_heatmap.png`**: Correlation matrix showing the linear relationships between views, likes, comment counts, and computed engagement scores.
* **`top_categories_engagement.png`**: Bar chart highlighting the top 10 video categories ranked by average engagement score.
* **`engagement_by_country_boxplot.png`**: Cross-market comparison displaying engagement score distributions across the US, Great Britain, and India.

---

## 📊 Key Visualizations & Insights

1. **Log-View Distribution:** Addresses the heavy right-skewness of raw view counts, normalizing metrics for better statistical evaluation.
2. **Correlation Heatmap:** Demonstrates strong positive correlations between user interactions (likes and comments) and total view counts.
3. **Category Performance:** Identifies which content genres consistently drive higher audience engagement across regions.
4. **Cross-Market Analysis:** Highlights behavioral differences and median engagement levels across the US, GB, and IN markets.

---

## 🚀 How to Run

1. Open the repository in **Google Colab** or your local Jupyter environment.
2. Ensure your cleaned datasets are available in the project directories.
3. Run the cells sequentially in `TrendPulse_Part3.ipynb` to execute the data processing pipeline, generate high-resolution (300 DPI) charts, and save them automatically to the workspace.
