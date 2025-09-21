
# 🎬 Movie Recommender System

A **content-based movie recommender system** built with Python. It uses **TF-IDF** and **BERT embeddings** to recommend movies and TV shows based on genres, cast, director, and description from the Netflix dataset.

---


## ⚙️ Features

* **Exploratory Data Analysis (EDA):**

  * Movies vs TV Shows count
  * Top genres, directors, and countries
  * Trends over time
* **Preprocessing & Feature Engineering:**

  * Handle missing values
  * Normalize and clean text features
  * Create combined "content feature" (genres + cast + director + description)
* **Recommendation System:**

  * **TF-IDF + Cosine Similarity**
  * **BERT Embeddings + Cosine Similarity** (semantic search)
  * Support for **title-based** and **free-text query-based** recommendations
* **Interactive App (Optional):**

  * Built with Flask/Streamlit to try recommendations in browser

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Create virtual environment and install requirements:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Mac/Linux

   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook for experiments:

   ```bash
   jupyter notebook
   ```
4. (Optional) Run the app:

   ```bash
   streamlit run app.py
   ```

---

## 📊 Dataset

* Source: [Netflix Movies and TV Shows dataset (Kaggle)](https://www.kaggle.com/shivamb/netflix-shows)
* Contains attributes:

  * `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genres), `description`

---

## 💡 Future Improvements

* Hybrid model combining **content-based + collaborative filtering**
* Better embeddings with **Sentence-BERT / OpenAI embeddings**
* Deploy as a full web app with a search interface
* Add user ratings & personalization

---

## 📌 Example Recommendations

**Query:** *Stranger Things*
**Top Recommendations:**

1. Beyond Stranger Things
2. Prank Encounters
3. Anjaan: Special Crimes Unit
4. Safe Haven
5. Eli

---

## 👨‍💻 Author

**Utkarsha Gupta**
🎓 Electronics, Communication & Information Technology Engineering Student
💡 Interested in ML/AI, Data Analysis, IoT, and Software Development

---
