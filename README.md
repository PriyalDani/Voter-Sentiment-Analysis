# Leveraging Big Data in Voter Sentiment Analysis

## Overview
This project explores the use of big data technologies and advanced machine learning models to analyze voter sentiment from Reddit data. By decoding millions of digital conversations, it provides insights into public opinion and behavior, empowering policymakers, campaign teams, and researchers to make informed decisions.

---

## Objectives
1. Analyze voter sentiment during elections using Reddit data.
2. Utilize advanced machine learning models (BERT, Naïve Bayes) for sentiment classification.
3. Address challenges like unstructured data processing, class imbalance, and real-time sentiment shifts.

---

## Methodology
### Data Collection:
- Collected election-related posts and comments from Reddit using **PRAW (Python Reddit API Wrapper)**.
- Focused on election-specific subreddits for relevance.

### Data Storage:
- Used **HDFS (Hadoop Distributed File System)** for scalable and fault-tolerant data storage.

### Sentiment Analysis:
- Applied **Naïve Bayes** for initial classification and **Complement Naïve Bayes** to address class imbalance.
- Fine-tuned **BERT (Bidirectional Encoder Representations from Transformers)** for enhanced accuracy and contextual understanding.

### Tools and Technologies:
- **Programming**: Python, PRAW, NLTK, TensorFlow, Scikit-learn
- **Data Storage**: HDFS
- **Libraries**: Pandas, TfidfVectorizer, SelectKBest
- **Models**: Naïve Bayes, Complement Naïve Bayes, BERT

---

## Results
- **Sentiment Distribution**:
  - Neutral: 46.6%
  - Negative: 33.7%
  - Positive: 19.6%
- **Model Accuracy**:
  - Complement Naïve Bayes: 32.81%
  - BERT: 29.69%

---

## Impact
This project highlights the complexities of voter sentiment, revealing polarization and public opinion trends. The insights enable stakeholders to craft better strategies for engaging voters and addressing public concerns.

---

## Team Members
- Priyal Dani
- Utsav Parekh
- Asmita Singh
- Simran Singh

## References
1. [Hadoop: The Definitive Guide](https://www.oreilly.com/library/view/hadoop-the-definitive/9781449311520/)
2. [Sentiment Analysis with BERT](https://doi.org/10.1186/s40537-023-00781-w)
