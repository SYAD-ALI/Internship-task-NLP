# 🧠 NLP Preprocessing Engine (Advanced)

## 📌 Overview

This project is part of my Data Science Internship (February 2026).
The goal is to build a robust NLP preprocessing pipeline that can clean and process real-world messy text data.

The system handles noise such as emojis, URLs, repeated characters, and inconsistent formatting.

---

## 🎯 Features

* Convert text to lowercase
* Remove numbers and special characters
* Remove URLs and email patterns
* Handle repeated characters (e.g., "soooo" → "so")
* Remove extra spaces
* Tokenization
* Remove short words (with exceptions like "no", "not")
* Token analytics (count, unique, average length)
* Frequency analysis using Counter
* Full pipeline implementation
* Error handling (empty input, emojis, numbers)

---

## 🛠️ Technologies Used

* Python
* Regular Expressions (re)
* Collections (Counter)
* Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```
NLP_TASK/
│── NLP_TASK.ipynb
│── README.md
```

---

## 🚀 How to Run

1. Open the notebook in Jupyter or Google Colab
2. Run all cells step by step
3. View preprocessing results and analysis

---

## 📊 Sample Input

```
"I absolutely looooved this product 😍😍"
```

## 📊 Sample Output

```
Tokens: ['absolutely', 'loved', 'this', 'product']
Cleaned Sentence: absolutely loved this product
```

---

## 📈 Output Includes

* Cleaned tokens
* Cleaned sentences
* Token statistics
* Frequency analysis

---

## ⚠️ Note

* This project is created for internship learning purposes
* Code is written in a simple and understandable way

---

## 👤 Author

**Name:** Syad Ali
**Internship ID:** IN126055102

---

## ✅ Conclusion

This project demonstrates how raw text data can be cleaned and transformed into structured format suitable for NLP models.
