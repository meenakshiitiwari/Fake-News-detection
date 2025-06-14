# Fake-News-detection
This project aims to identify whether a given news article is real or fake using Natural Language Processing (NLP) techniques and machine learning models. It is a classification problem built with Python and trained on labeled datasets of real and fake news articles.

**Dataset**
The project uses two CSV files:
Fake.csv — Contains fake news articles.
True.csv — Contains real news articles.
Both datasets are publicly available and include the text of the articles along with metadata such as titles and publication dates.

**Project Pipeline**
1. Data Preparation
Loaded and merged real and fake datasets.
Labeled articles (0 for fake, 1 for real).
Shuffled and reset the index for a balanced dataset.

3. Data Preprocessing
Converted text to lowercase.
Removed punctuation, special characters, and stopwords.
Applied tokenization and lemmatization using NLTK.

5. Exploratory Data Analysis (EDA)
Analyzed article length by label.
Visualized data distributions to observe patterns between real and fake news articles.

7. Feature Extraction
Converted text data into numerical features using:
TF-IDF Vectorizer or CountVectorizer (based on your implementation).

9. Model Training
Trained classification models such as:
Logistic Regression
Naive Bayes

**Evaluated model performance using:**
Accuracy
Precision, Recall, F1-Score
Confusion Matrix

**Results**
The best-performing model achieved:
Accuracy: ~85% (Adjust based on your results)
Good separation of real and fake articles based on the feature space.
