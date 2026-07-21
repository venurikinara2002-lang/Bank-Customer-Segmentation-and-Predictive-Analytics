# Bank Customer Segmentation and Predictive Analytics

<div align="center">
  <img src="banner.png" alt="Bank Customer Segmentation Banner" width="100%">
</div>

## 📌 Project Overview
This project performs an end-to-end data analysis and machine learning pipeline on a real-world Portuguese bank dataset. The primary goals are to understand customer behaviors through Exploratory Data Analysis (EDA) and clustering, and to build robust predictive models capable of forecasting future customer interactions or identifying key target segments. The dataset features significant class imbalance, which is addressed using SMOTE.

## 📂 Repository Structure

The project workflow is divided across several Jupyter Notebooks and presentation slides:

- **`Data_Preprocessing.ipynb`**: Handles data cleaning, missing value imputation, feature engineering, and preparation of the dataset for analysis and modeling.
- **`Cluster and EDA.ipynb`**: Contains extensive Exploratory Data Analysis (EDA) along with customer segmentation/clustering techniques to discover distinct customer profiles.
- **`FAMD.ipynb`**: Performs Factor Analysis of Mixed Data (FAMD) to reduce dimensionality while handling both categorical and numerical variables simultaneously.
- **`SMOTE_with_model (1).ipynb`**: Implements predictive machine learning models, utilizing Synthetic Minority Over-sampling Technique (SMOTE) to effectively balance the class distribution and improve model reliability.
- **`Bank EDA slides.pdf`**: Presentation slides summarizing the initial Exploratory Data Analysis insights.
- **`Bank Advance Analysis slides.pdf`**: Presentation slides detailing the advanced analytics, modeling results, and final business recommendations.
- **`train.csv` / `archive.zip`**: The dataset used for the project.

## 🛠️ Tech Stack & Techniques
- **Programming Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-Learn (Classification, Clustering)
- **Advanced Techniques**: SMOTE (Class Imbalance), FAMD (Dimensionality Reduction)

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/venurikinara2002-lang/Bank-Customer-Segmentation-and-Predictive-Analytics.git
   ```
2. Ensure you have Jupyter Notebook installed along with the necessary Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn prince
   ```
   *(Note: The `prince` library is commonly used for FAMD in Python).*
3. Extract `archive.zip` if needed, to access the full datasets.
4. Open the notebooks in sequential order (Preprocessing -> EDA -> FAMD -> Modeling) using Jupyter:
   ```bash
   jupyter notebook
   ```

## 🤝 Contributions
Feel free to open issues or submit pull requests for any improvements or bug fixes.
