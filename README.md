# BBC News Categorization Analysis

## 📌 Overview
This project analyzes the BBC News Dataset using a comprehensive NLP pipeline to classify news articles into predefined categories. The primary goal is to automate categorization for improved media monitoring, trend identification, and strategic decision-making.

## 📂 Dataset Details
*   **Source:** BBC News Dataset
*   **Target Categories:**
    *   Business
    *   Tech
    *   Politics
    *   Sport
    *   Entertainment
*   **Data Split:**
    *   Training Set: 1,490 records
    *   Testing Set: 735 records
*   **Preprocessing Pipeline:**
    1.  Tokenization
    2.  Stop-word removal
    3.  TF-IDF feature extraction

## ⚙️ Models Evaluated
We evaluated three distinct machine learning models for this classification task:

1.  **Naive Bayes:** A simple probabilistic classifier tailored for text data.
2.  **Logistic Regression:** A linear model effective for high-dimensional text data.
3.  **Support Vector Machine (SVM):** A complex classifier (found to be less effective for this specific dataset configuration).

## 📊 Performance Metrics

| Model | Test Accuracy | CV Mean | CV Std |
| :--- | :---: | :---: | :---: |
| **Naive Bayes** | 0.7215 | 0.4740 | 0.0594 |
| **Logistic Regression** | **0.7148** | **0.7567** | **0.0313** |
| **SVM** | 0.3557 | 0.3574 | 0.0193 |

> **Conclusion:** ✅ **Logistic Regression** proved to be the most robust and consistent model based on Cross-Validation (CV) scores.

## 🔍 Key Challenges
*   **Library Integration:** Managing dependencies across diverse NLP libraries.
*   **Data Structures:** Handling complex structures such as TF-IDF vectors, sentiment scores, and entity lists.
*   **Ethics:** Addressing potential bias, privacy concerns, and the spread of misinformation in automated news sorting.

## 🚀 Future Directions
- [ ] **Topic Modeling:** Implement Latent Dirichlet Allocation (LDA).
- [ ] **Deep Learning:** Explore Transformers & BERT embeddings.
- [ ] **Causal Analysis:** Investigate causal relationships within the text.
- [ ] **Process:** Enhance collaboration through rigorous code reviews.

## ✅ Conclusion
This project demonstrates the practical application of machine learning for text classification. It emphasizes technical rigor, ethical responsibility, and the potential for advanced NLP techniques to further improve performance.

---

### 👥 Authors
**Andres Daza & Taki Bouberi**
*ITAI 2373 – Final Project*
*Professor: Anna Rachapudi*
