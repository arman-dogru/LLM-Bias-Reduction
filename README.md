# CSI5137 - Final Project: Bias in Machine Learning Software - GitHub Repository

## **Project Title**
**Bias in Machine Learning Software: Why? How? What to Do? Using LLMs**

## **Contributors**
- **Patrick Loranger**  
  Student ID: 300112374  
  Email: plora079@uottawa.ca  

- **Arman Dogru**  
  Student ID: 300168151  
  Email: adogr056@uottawa.ca  

- **Manav Isrrani**  
  Student ID: 300161398  
  Email: misrr103@uottawa.ca  

### **Course Information**
- **Course:** CSI5137 - Applications of NLP and ML in Software Engineering  
- **Instructor:** Professor Mehrdad Sabetzadeh ([m.sabetzadeh@uottawa.ca](mailto:m.sabetzadeh@uottawa.ca))  
- **Submission Date:** Monday, December 23, 2024  

---

## **Abstract**
This repository accompanies our research on identifying, understanding, and mitigating bias in machine learning models using novel approaches, including **Large Language Models (LLMs)** and a reimagined version of the **Fair-SMOTE algorithm**. Our work explores the effectiveness of LLMs in reducing biases without the need for traditional data augmentation techniques like SMOTE, while maintaining high model performance across datasets.

---

## **Repository Structure**
The repository is organized into the following sections:

### **Notebooks**
1. **Datasets with LLM Classifiers**  
   - Analysis with and without SMOTE for six datasets.  
   - **Notebook Count:** 12 (2 variations for each dataset).  

2. **Traditional Classifiers**  
   - Comparison of traditional machine learning models (e.g., Random Forest, SVM) with and without SMOTE.  
   - **Notebook Count:** 2 (with and without SMOTE).

### **Datasets**
- Adult Census Income
- German Credit
- Default Credit
- Bank Marketing
- MEPS-15
- MEPS-16

### **Results**
- Comparative performance metrics across datasets:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1 Score**
  - **Fairness Metrics** (e.g., Demographic Parity, Equal Opportunity).

### **Scripts**
- Preprocessing pipeline for data cleaning and encoding.
- SMOTE implementation for synthetic data generation.
- Training and evaluation scripts for both traditional classifiers and LLM-based models.

---

## **Instructions**
### **Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

### **Execution on Kaggle**
All notebooks were executed using Kaggle's cloud environment to leverage its computational resources. Follow the steps below to run the notebooks on Kaggle:
1. Navigate to [Kaggle](https://www.kaggle.com/) and create an account if you don’t already have one.
2. Upload the repository as a Kaggle dataset or individual notebooks into a Kaggle kernel.
3. Select a Kaggle runtime environment with sufficient computational resources (e.g., GPU or TPU for LLM-based notebooks).
4. Run each notebook and review the outputs directly within the Kaggle interface.

---

## **Findings**
1. **LLM Classification**: Demonstrated comparable or superior performance to traditional classifiers, often without requiring SMOTE.
2. **Fairness Evaluation**: LLMs effectively mitigated bias while maintaining high accuracy, F1 scores, and other performance metrics.
3. **Traditional Classifiers**: SMOTE improved fairness but introduced variability in other metrics, emphasizing the trade-offs inherent in traditional approaches.

---

## **Acknowledgments**
We extend our gratitude to **Professor Mehrdad Sabetzadeh** for his guidance and support throughout this project.  

For further inquiries, please contact any of the contributors listed above.  
