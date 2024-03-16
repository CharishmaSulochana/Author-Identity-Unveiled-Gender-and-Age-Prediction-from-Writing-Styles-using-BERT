# Author-Identity-Unveiled-Gender-and-Age-Prediction-from-Writing-Styles-using-BERT

# Problem Statement:
Author profiling is a challenging task involving the categorization of authors into age groups and genders based on textual data. The primary aim is to develop accurate machine learning models that can predict the age group and gender of authors, enabling marketers to tailor campaigns for specific demographics effectively.

# Abstract :
Project focuses on author profiling: predicting age group and gender from textual data. Objective is to Categorize age groups into predefined ranges and determine binary gender labels.

# Dataset:
The dataset is sourced from Zenodo.org, originating from the PAN13 project. It consists of 100,000 documents in XML format, with three columns: Gender, Age Group, and Content. Data preprocessing involves removing numbers and HTML tags to prepare the dataset for analysis.

# Methodology:
The project employs a methodology centered around data preprocessing, exploratory data analysis, model building, and evaluation metrics. Text vectorization techniques such as TF-IDF and Count Vectorizer are utilized alongside machine learning algorithms. BERT embeddings are highlighted for their ability to capture contextual information effectively. Evaluation is conducted using metrics such as F1 scores to assess model performance for both age group and gender prediction.

# Conclusion:
This work significantly advances understanding author identification based on input text.
Choice of vectorization method and model greatly impacts performance.
AdaBoost with TF-IDF is the most precise model for age group prediction (F1 score: 0.58).
K-neighbours with TF-IDF is optimal for gender prediction (F1 score: 0.58).
BERT embeddings are notably effective, especially in complex models like Naive Bayes, SVM, Random Forest, Decision Tree, and AdaBoost.
Logistic Regression consistently performs well across vectorization methods.
Integration of BERT, capable of bi-directional understanding, surpasses traditional ML methods, showcasing practical applications in marketing strategy customization and combating fake news by author identification.

# Future Work:
Opportunities exist for further exploration and improvement in this field.
Incorporating more advanced natural language processing (NLP) methods and deeper learning architectures beyond BERT could enhance understanding of intricate authorship details.
The project lays the groundwork for future endeavors aimed at refining and expanding our comprehension of author writing styles.
