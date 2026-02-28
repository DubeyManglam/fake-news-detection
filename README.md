# 📰 Fake News Detection using Machine Learning

This repository contains code for a Machine Learning project focused on detecting fake news articles using Natural Language Processing (NLP) techniques. The project is built using Python and leverages libraries such as Pandas, NumPy, Matplotlib, NLTK, and Scikit-learn.

---

## 📌 Overview

Fake news has become a major issue in today's digital world, where misinformation spreads rapidly across media platforms. This project aims to build a machine learning model that automatically classifies news articles as **Fake** or **Real** based on textual content.

---

## 🛠 Libraries Used

- **pandas** – Data manipulation and analysis  
- **numpy** – Numerical computations and array operations  
- **matplotlib** – Data visualization  
- **seaborn** – Enhanced data visualization  
- **re** – Regular expressions for text preprocessing  
- **nltk** – Natural Language Processing (stopword removal, stemming, tokenization)  
- **scikit-learn (sklearn)**:
  - `TfidfTransformer` & `TfidfVectorizer` – Feature extraction using TF-IDF  
  - `train_test_split` – Dataset splitting  
  - `LogisticRegression` – Classification model  
  - `accuracy_score` – Model performance evaluation  

---

## 📂 Dataset

The dataset contains news articles labeled as **Fake** or **Real**.  
Features include:
- Title
- Text
- Metadata (if available)

---

## 🔎 Approach

### 1️⃣ Data Preprocessing
- Text cleaning (removing special characters, URLs)
- Tokenization
- Stopword removal
- Stemming
- Text normalization

### 2️⃣ Feature Engineering
- TF-IDF (Term Frequency – Inverse Document Frequency) vectorization

### 3️⃣ Model Training
- Dataset split into training and testing sets
- Logistic Regression model trained on training data

### 4️⃣ Model Evaluation
- Performance evaluated using accuracy score on test data

---

## 🔄 Project Workflow

1. **Data Loading** – Load dataset containing real and fake news articles  
2. **Data Preprocessing**
   - Text Cleaning
   - Tokenization
   - Stopword Removal
   - Stemming  
3. **Feature Extraction** – Convert text into numerical vectors using TF-IDF  
4. **Model Training** – Train Logistic Regression classifier  
5. **Model Evaluation** – Measure performance using accuracy metric  
6. **Deployment (Optional)** – Use trained model to predict new articles  

---

## 📁 Repository Structure

```
data/         -> Dataset files  
notebooks/    -> Jupyter notebooks for preprocessing, training & evaluation  
scripts/      -> Python utility scripts  
README.md     -> Project documentation  
```

---

## 🚀 Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/DubeyManglam/fake-news-detection.git
```

### 2️⃣ Navigate to the project directory
```bash
cd fake-news-detection
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the project
Open and execute the Jupyter notebooks inside the `notebooks/` directory.

---

## 🤝 Contribution

Feel free to:
- Open issues  
- Suggest improvements  
- Submit pull requests  

If you found this project useful, consider ⭐ starring the repository!

---

### 📌 Author
**Manglam Dubey**  
GitHub: https://github.com/DubeyManglam
