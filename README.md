# 📚 Book Recommendation Engine using KNN

This project builds a book recommendation engine using the [Book-Crossing dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/), trained with **K-Nearest Neighbors**.

> ✅ Built in Google Colab using Python, Pandas, and Scikit-learn.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iSEeLCXGzklOnuWki_Sekq9U4K2Gq2Gl?usp=sharing)

---

## 🛠️ How It Works

- Filters users with ≥ 200 ratings and books with ≥ 100 ratings
- Creates a book-user matrix
- Trains a KNN model using cosine similarity
- Recommends 5 similar books given an input title

---

## 📦 Output Format

```python
get_recommends("Where the Heart Is (Oprah's Book Club (Paperback))")

[
  "Where the Heart Is (Oprah's Book Club (Paperback))",
  [
    ['Book A', 0.51],
    ['Book B', 0.52],
    ...
  ]
]
