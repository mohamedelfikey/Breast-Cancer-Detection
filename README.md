# Breast Cancer Detection System

This project focuses on building a **Breast Cancer Detection System** using various machine learning algorithms to classify tumors as malignant or benign. The performance of each model has been evaluated, and comparisons were drawn based on **recall metrics**.

---

## Project Overview
Breast cancer is one of the most prevalent types of cancer, and early detection plays a crucial role in effective treatment. This project uses machine learning models trained on breast cancer datasets to predict tumor status. The project also evaluates and compares the accuracy and recall for different models to identify the best-performing approach.

---

## Technologies Used
- **Python**: Programming language
- **Libraries**: 
  - Scikit-learn
  - NumPy
  - Pandas
  - Matplotlib / Seaborn (for visualization)
- **Jupyter Notebook / Colab**: For development and experimentation

---

## Dataset
The dataset used in this project is the **Breast Cancer Wisconsin Dataset** available from the UCI Machine Learning Repository or other sources. The dataset consists of:
- **Features**: Various cell characteristics
- **Target Labels**: 0 (Benign), 1 (Malignant)

---

## Models Implemented
The following machine learning models were implemented, and their performance was evaluated based on the **recall metric**:

| **Model**                      | **Recall for 0 (Benign)** | **Recall for 1 (Malignant)** |
|--------------------------------|---------------------------|------------------------------|
| Logistic Regression            | 96%                       | 98%                          |
| Decision Tree Classifier       | 92%                       | 92%                          |
| Random Forest Classifier       | 97%                       | 98%                          |
| K Neighbors Classifier         | 96%                       | 98%                          |
| Support Vector Machine (SVM)   | 96%                       | 99%                          |
| Gaussian Naive Bayes (GaussianNB)| 96%                    | 93%                          |

---

## Key Findings
1. **Support Vector Machine (SVM)** achieved the highest recall for malignant tumors (99%).
2. **Random Forest Classifier** demonstrated excellent results for both benign and malignant classes (97%-98%).
3. Recall was prioritized in this project because accurately identifying malignant cases is critical for early diagnosis.

---

## Results
The project highlights the importance of recall in detecting malignant tumors to minimize false negatives. Support Vector Machine emerged as the best-performing model.

---

## Future Improvements
- Integration of deep learning models like CNNs.
- Building a web-based interface for real-time predictions.
- Testing the system on larger datasets.

---


## Author
- **Mohamed Ahmed** - [LinkedIn](https://www.linkedin.com/in/mohamed-elfikey/) | [GitHub](https://github.com/mohamedelfikey)

