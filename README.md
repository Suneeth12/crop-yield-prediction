# 🌾 Predicting Crop Yield Using Decision Trees (ICISML 2026)

Official research code and exploratory data analysis for the peer-reviewed conference publication accepted at the **ICISML 2026 Conference**.

## 📄 Publication Details
- **Title**: Predicting Crop Yield Using Decision Trees
- **Venue**: International Conference on Information Security and Machine Learning (ICISML 2026)
- **Author**: Suneeth Reddy Peddamallu

## 🔬 Abstract & Methodology
Predicting crop yield is essential for food security and agricultural supply chain planning. This research analyzes an 8-year longitudinal agricultural dataset (2010–2018) across multi-regional agricultural zones:
1. **Data Preprocessing & Quality Engineering**: Cleaned agricultural records via missing value imputation, outlier detection, and robust label encoding.
2. **Exploratory Data Analysis & Feature Selection**: Conducted bivariate correlation analysis and mutual information scoring to isolate primary drivers of crop yield:
   - Crop variety & state classifications
   - Fertilizer usage (NPK ratios)
   - Annual precipitation / rainfall metrics
   - Soil surface temperatures
3. **Model Architecture & Evaluation**: Implemented and benchmarked Decision Tree Regressors and ensemble baselines, achieving:
   - **R² Score: 0.97**
   - **Mean Squared Error (MSE): 172,251**

## 📂 Repository Contents
- `researchpaper.ipynb`: End-to-end Jupyter Notebook containing dataset ingestion, statistical data visualizations, correlation heatmaps, feature engineering, and model cross-validation.
- `license.md`: Open-source MIT License.

## 🛠️ Tech Stack
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter

## 👤 Author
**Suneeth Reddy Peddamallu** — [GitHub](https://github.com/Suneeth12) • [Portfolio](https://suneeth.live) • [LinkedIn](https://linkedin.com/in/suneeth-reddy-peddamallu)
