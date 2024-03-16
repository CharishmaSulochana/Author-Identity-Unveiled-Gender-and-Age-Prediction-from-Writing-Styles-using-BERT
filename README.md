# Author-Identity-Unveiled-Gender-and-Age-Prediction-from-Writing-Styles-using-BERT

# Problem Statement:
Author profiling is a challenging task involving the categorization of authors into age groups and genders based on textual data. The challenge addressed in this project revolves around author profiling, with the primary objective of predicting age group and gender based on textual data. Author profiling plays a crucial role in various domains, including marketing, forensic linguistics, and content moderation. By accurately categorizing authors into age groups and genders, businesses can tailor marketing campaigns to specific demographics, while forensic linguists can utilize author profiling techniques to identify authors of anonymous texts, aiding in criminal investigations. Additionally, in the realm of content moderation, author profiling can assist in detecting and combating fake news by attributing content to its real authors. However, despite its significance, author profiling remains a challenging task due to the diverse linguistic styles and writing patterns exhibited by authors across different demographics. This project aims to develop effective machine learning models that can accurately predict the age group and gender of authors from textual data, contributing to advancements in author profiling methodologies and their practical applications.

# Abstract:
Project focuses on author profiling: predicting age group and gender from textual data. Objective is to Categorize age groups into predefined ranges and determine binary gender labels.

# Dataset:
The dataset is sourced from Zenodo.org, originating from the PAN13 project. It consists of 100,000 documents in XML format, with three columns: Gender, Age Group, and Content. Data preprocessing involves removing numbers and HTML tags to prepare the dataset for analysis.

# Methodology:
The project employs a methodology centered around data preprocessing, exploratory data analysis, model building, and evaluation metrics. Text vectorization techniques such as TF-IDF and Count Vectorizer are utilized alongside machine learning algorithms. BERT embeddings are highlighted for their ability to capture contextual information effectively. Evaluation is conducted using metrics such as F1 scores to assess model performance for both age group and gender prediction.
# Python Libraries:
TensorFlow: An open-source machine learning framework developed by Google.
Scikit-learn: A machine learning library in Python that provides tools for data mining and analysis.
Pandas: A data manipulation and analysis library in Python.
NumPy: A fundamental package for scientific computing in Python, providing support for multi-dimensional arrays and matrices.
Transformers: An open-source library for natural language processing (NLP) tasks, including pre-trained models like BERT.
Regular Expressions: A tool for pattern matching and string manipulation in Python.
SimpleImputer: A function from Scikit-learn used for imputing missing values in datasets.
train_test_split: A function from Scikit-learn used to split datasets into training and testing sets for model evaluation.
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
