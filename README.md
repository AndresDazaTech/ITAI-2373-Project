#BBC News Categorization Analysis
##📌 Overview
This project analyzes the BBC News Dataset using a comprehensive NLP pipeline to classify news articles into predefined categories: business, tech, politics, sport, and entertainment. The goal is to automate categorization for improved media monitoring, trend identification, and decision-making.

##📂 Dataset Details

Source: BBC News Dataset
Categories: Business, Tech, Politics, Sport, Entertainment
Training Set: 1,490 records
Testing Set: 735 records
Preprocessing:

Tokenization
Stop-word removal
TF-IDF feature extraction




##⚙️ Models Evaluated

Naive Bayes: Simple probabilistic classifier for text.
Logistic Regression: Effective for high-dimensional text data.
Support Vector Machine (SVM): Requires careful tuning; less effective for this dataset.


##📊 Performance Metrics





























ModelTest AccuracyCV MeanCV StdNaive Bayes0.72150.47400.0594Logistic Regression0.71480.75670.0313SVM0.35570.35740.0193
✅ Logistic Regression proved most robust and consistent.

🔍 Key Challenges

Integration of diverse NLP libraries
Handling complex data structures (TF-IDF, sentiment scores, entity lists)
Ethical considerations: bias, privacy, misinformation


##🚀 Future Directions

Implement Topic Modeling (LDA)
Explore Transformers & BERT
Investigate causal text analysis
Enhance collaboration through code reviews and communication


##✅ Conclusion
This project demonstrates the practical application of machine learning for text classification. It emphasizes technical rigor, ethical responsibility, and the potential for advanced NLP techniques to improve performance.

##👥 Authors
Andres Daza & Taki Bouberi
ITAI 2373 – Final Project
Professor: Anna Rachapudi
