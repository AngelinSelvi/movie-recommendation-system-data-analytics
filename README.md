# 🎬 Movie Recommendation System – Collaborative Filtering with Python

This project implements a **movie recommendation system** using **collaborative filtering techniques**. It suggests similar movies based on user preferences using **k-Nearest Neighbors (k-NN)** with **cosine similarity**. The project demonstrates how machine learning can personalize content recommendations using real-world datasets.

---

## 📌 Project Details

- **Project Title**: Movie Recommendation System  
- **Submitted By**: A. Angelin Selvi  
- **Course**: Data Science with Python  
- **Institution**: FIIT Training Institute  
- **Date**: January 2025  

---

## 📁 Datasets Used

- **movies.csv** – Contains movie ID, title, and genres (`9742 rows`)
- **ratings.csv** – Contains user IDs, movie ratings, and timestamps (`100,836 rows`)

> 📊 Datasets sourced from **Kaggle** and loaded using `pandas`

---

## 🔧 Methodology

1. **Data Preprocessing**
   - Merged movies and ratings datasets
   - Created a pivot table: users as rows, movies as columns
   - Handled missing values

2. **Data Filtering**
   - Retained movies with >10 ratings and users who rated >50 movies

3. **Model**
   - Used **k-NN algorithm** with **cosine similarity** to find movie similarities
   - Calculated recommendations based on a given movie input

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `scipy`

---

## 🚀 Features

- Recommend movies similar to a given movie title
- Handles sparse datasets (~73% sparse)
- Uses collaborative filtering without needing user login or profile

---

## 🧪 Sample Result

> 🎥 Input: `"Iron Man"`  
> 🎯 Output Recommendations:
- Guardians of the Galaxy (2014)
- The Dark Knight (2008)
- Up (2009)
- Captain America: The First Avenger (2011)

---

## 📄 Files Included

- `Movie Recommendation System.pdf` – Full report with explanation and results
- (Optional) `recommendation_system.ipynb` – Python notebook for actual code
- `README.md` – This documentation file

---

## 🔍 Learnings

- Practical implementation of collaborative filtering
- Handling large sparse datasets using Scipy CSR matrix
- Model building using `k-NN` with Scikit-learn

---

## 📌 Future Scope

- Improve model with hybrid recommendation (collaborative + content-based)
- Add a web interface using Flask or Streamlit
- Include user profiles or watch history for personalized results

---

## 📬 Contact

- LinkedIn: [www.linkedin.com/in/datawithangelin] 
- GitHub: [https://github.com/AngelinSelvi]
