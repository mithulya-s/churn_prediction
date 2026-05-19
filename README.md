# 📊 Customer Churn Prediction

> **Predicting customer churn with machine learning** — Identify at-risk customers and drive retention strategies with data-driven insights.

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=for-the-badge&logo=tensorflow)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 🎯 Project Overview

This project develops and compares **machine learning models** to predict customer churn in the telecommunications industry. By analyzing customer behavior patterns and service usage, we identify which customers are at risk of leaving, enabling proactive retention efforts.

### 📌 Key Details

| Aspect | Details |
|--------|---------|
| **Dataset** | Telco Customer Churn Dataset |
| **Samples** | 7,043 customers |
| **Task** | Binary Classification (Churn / No Churn) |
| **Models** | Decision Tree, Neural Network |
| **Data Split** | 80% Training, 20% Testing |
| **Format** | Jupyter Notebooks |

---

## 🏗️ Architecture

### Two Predictive Models

#### 1️⃣ **Decision Tree Classifier**
- Interpretable rule-based model
- Shows feature importance and decision paths
- Fast training and inference
- Excellent for business stakeholders to understand decisions

#### 2️⃣ **Neural Network (Deep Learning)**
- Multi-layer perceptron architecture
- Captures complex non-linear patterns
- Uses TensorFlow/Keras framework
- Optimized for capturing intricate customer behavior relationships

### 🔄 Model Comparison
Both models are trained on the same dataset and evaluated side-by-side to understand the trade-offs between **interpretability** and **predictive power**.

---

## 🧠 Machine Learning Pipeline

```
┌─────────────────────────────────────────────────────────────┐
│  1. DATA LOADING & EXPLORATION                              │
│     • Load Telco dataset                                    │
│     • Exploratory Data Analysis (EDA)                       │
│     • Statistical summaries & visualizations                │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  2. DATA PREPROCESSING                                      │
│     • Handle missing values                                 │
│     • Encode categorical features                           │
│     • Scale numerical features                              │
│     • Feature engineering & selection                       │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  3. MODEL DEVELOPMENT                                       │
│     • Decision Tree: Training & tuning                      │
│     • Neural Network: Architecture design & training        │
│     • Hyperparameter optimization                           │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  4. MODEL EVALUATION                                        │
│     • Classification metrics (Precision, Recall, F1)        │
│     • Confusion matrices & ROC curves                       │
│     • Feature importance analysis                           │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  5. INSIGHTS & RECOMMENDATIONS                              │
│     • Model comparison & selection                          │
│     • Business insights on churn drivers                    │
│     • Actionable retention strategies                       │
└─────────────────────────────────────────────────────────────┘
```

---

## 📚 Notebooks Included

### 🔹 **ML_Coursework.ipynb** (Primary)
Complete end-to-end machine learning workflow:
- Data loading and comprehensive EDA
- Feature engineering and preprocessing
- Decision Tree model development
- Neural Network implementation
- Model evaluation and comparison
- Visualizations and insights

### 🔹 **Churn_Prediction_Refined.ipynb** (Refined)
Optimized version with enhancements:
- Streamlined preprocessing pipeline
- Hyperparameter tuning
- Advanced feature importance analysis
- Refined model architectures
- Detailed performance comparisons

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.8+** | Programming language |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical computing |
| **Scikit-learn** | Machine learning algorithms |
| **TensorFlow/Keras** | Deep learning framework |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualizations |
| **Jupyter** | Interactive notebook environment |

---

## 📊 What You'll Learn

✅ **Data Science Fundamentals**
- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- Data preprocessing and normalization

✅ **Machine Learning Techniques**
- Decision Tree classification
- Neural Network design and training
- Model hyperparameter tuning

✅ **Model Evaluation**
- Classification metrics (Precision, Recall, F1-Score)
- Confusion matrices and ROC-AUC curves
- Feature importance interpretation

✅ **Business Intelligence**
- Identifying key churn drivers
- Creating actionable insights
- Developing retention strategies

---

## 💼 Business Applications

This churn prediction model can help:

🎯 **Identify At-Risk Customers** - Flag customers likely to churn before they leave  
📞 **Target Retention Campaigns** - Focus efforts on high-value customers at risk  
💰 **Reduce Revenue Loss** - Proactive intervention to minimize customer attrition  
📈 **Improve Customer Lifetime Value** - Develop data-driven loyalty programs  
🔍 **Understand Churn Drivers** - Discover key factors influencing customer decisions  

---

## 📁 File Structure

```
churn_prediction/
├── ML_Coursework.ipynb              # Primary notebook (complete workflow)
├── Churn_Prediction_Refined.ipynb   # Refined notebook (optimized version)
└── README.md                         # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn jupyter
```

### Running the Notebooks
1. Clone the repository
2. Navigate to the project directory
3. Launch Jupyter Notebook
4. Open either `ML_Coursework.ipynb` or `Churn_Prediction_Refined.ipynb`
5. Run cells sequentially to execute the analysis

---

## 🔍 Key Features Analyzed

The model analyzes customer features including:
- **Demographics** - Age, gender, location
- **Service Usage** - Internet type, phone service, data consumption
- **Contract Details** - Contract length, billing method, tenure
- **Financial Metrics** - Monthly charges, total charges, discounts
- **Interactions** - Support tickets, technical issues reported

---

## 📈 Model Insights

### Decision Tree Advantages
✓ Highly interpretable - Easy to explain to stakeholders  
✓ Shows decision rules - Understand "why" a customer will churn  
✓ Fast predictions - Real-time scoring possible  
✓ Handles non-linear relationships naturally  

### Neural Network Advantages
✓ Superior pattern recognition - Captures complex customer behaviors  
✓ Better generalization - Handles diverse customer segments  
✓ Flexible architecture - Can be extended with additional layers  
✓ Strong performance on large datasets  

---

## 🎓 Learning Outcomes

By exploring this project, you'll understand:
- End-to-end machine learning workflow
- Data preprocessing and feature engineering
- Building and training supervised learning models
- Model evaluation and comparison
- Translating ML predictions into business value

---

## 📝 Notes

- The project focuses on **model development and comparison**
- Results are evaluated on a held-out test set for unbiased assessment
- Both notebooks document the complete analysis process
- Extensive visualizations aid in understanding model behavior
- Code is well-commented for educational purposes

---

## 🤝 Contributing

This is a coursework/portfolio project. For improvements or suggestions:
- Feel free to open issues
- Submit pull requests with enhancements
- Share insights on model improvements

---

## 📄 License

This project is open source and available for educational purposes.

---

<div align="center">

### 🚀 Ready to Dive In?
Start with **ML_Coursework.ipynb** for the complete journey through customer churn prediction!

**Questions?** Open an issue or reach out!

⭐ If you found this helpful, please consider giving it a star!

</div>

---

**Last Updated:** February 2026  
**Language:** Python 3.8+  
**Format:** Jupyter Notebooks  
**Status:** Active & Maintained
