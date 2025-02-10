# 🎵 Optimizing Spotify Song Investments Through Analytics  

## 🚀 Project Overview  
This project leverages **predictive modeling, exploratory data analysis (EDA), feature engineering, and business intelligence** to maximize return on investment (ROI) in the music industry. By accurately predicting hit songs, we reduce missed opportunities and optimize investments in new music releases.  

We built and evaluated multiple predictive models (**Logistic Regression, Decision Trees, KNN, Neural Networks**) to classify songs as potential hits. Our best-performing **Neural Network model achieved a 99% ROI**, identifying high-potential songs that generated **$241M in revenue from a $120M investment**, significantly improving investment efficiency.  

## 📂 Project Structure  
The project consists of multiple Jupyter Notebook files worked on by different team members:  

- **`df.csv`** - The dataset used for model training.  
- **`df_cleaned.csv`** - The cleaned dataset used for model training.  
- **`Project+_data_cleaning_and_NN.ipynb`** - Contains data preprocessing, feature engineering, and neural network implementation.  
- **`Project_decision_tree.ipynb`** - Includes Decision Tree modeling and evaluation.  
- **`Team2_Presentation.pptx`** - Final presentation summarizing insights, model performance, and recommendations.  

## 📊 Key Insights  
### 🔍 Data Analysis & Feature Engineering  
- **Merging Datasets:** Unified multiple datasets to enhance predictive power.  
- **Feature Engineering:** Created new variables and performed correlation analysis.  
- **Outlier Handling:** Standardized distributions and removed inconsistencies.  

### 🔥 Model Performance Comparison  
| Model | Accuracy | Precision | Recall | ROI Impact |
|--------|---------|----------|--------|------------|
| Decision Tree | Moderate | High | Moderate | Good |
| KNN | High for unpopular songs | Perfect | Low for hits | Poor |
| Neural Networks | **Best Performance** | **Optimized** | **High Recall** | **99% ROI** |

### 🎯 Business Recommendations  
- **Spotify should adopt the Neural Network model** for its superior recall and ROI.  
- **Investment strategy:** Prioritize songs with high predicted hit potential while accepting some false positives.  
- **Enhance marketing strategies** by leveraging data-driven insights to support new music promotions.  
