# Name Recommendation System — ML-Driven Suggestive Modeling

> Intelligent name recommendation system leveraging machine learning and embedding techniques to generate personalized name suggestions based on user preferences.

---

## 🚀 Overview

This project implements a **name recommendation engine** using natural language processing and machine learning principles. Given a text prompt or preferences, the system generates meaningful and context-aware name suggestions — ideal for branding, product naming, character creation, or creative idea generation.

By combining **semantic understanding**, **vector embeddings**, and **similarity scoring**, this project demonstrates real-world ML applications beyond classification and regression.

---

## 📌 Problem Statement

Many applications require automated name suggestions that feel relevant and creative — from startups choosing brand names to authors selecting character names. Traditional keyword matching fails to capture semantic nuance. This system uses machine learning techniques to overcome that limitation.

---

## 🧠 ML Approach & Methodology

### 📊 Machine Learning Concepts Used

✔ **Text Preprocessing**
- Tokenization, cleaning, vectorization

✔ **Embedding-Based Similarity**
- Convert names and input prompts into embedding vectors
- Use cosine similarity to measure semantic closeness

✔ **Heuristic & Learned Ranking**
- Scores candidate names based on embedding distance
- Outputs ranked suggestions ordered by relevance

---

## 📈 How It Works

1. **User Prompt Input**  
   The user provides a description (e.g., “modern tech startup”, “fantasy character”).

2. **Embedding Generation**  
   Convert user input and candidate names into vector representations using embeddings.

3. **Similarity Scoring**  
   Compute similarity scores between the prompt and candidate vectors.

4. **Recommendation Output**  
   Return ranked name suggestions based on semantic relevance.

---

## 📁 Repo Structure

Name-Recommendation-system/
├── Notebooks/
│ └── Name_Recommendation_Model.ipynb
├── data/
│ └── name_datasets.csv
├── src/
│ └── recommender.py
├── README.md
└── requirements.txt

---


---

## 📊 Results & Evaluation

The system was evaluated using semantic similarity metrics:  
✔ Names produced are contextually aligned with user input  
✔ Comparable alternatives are grouped and ranked effectively  
✔ Demonstrates prototype-level performance for creative use cases

> *Note:* quantitative evaluation (e.g., user studies) can be added to further validate relevance scoring.

---

## 🧪 How to Run

```bash
# Clone the repository
git clone https://github.com/Dhruvsharma132/Name-Recommendation-system

# Install dependencies
pip install -r requirements.txt

# Open and run
jupyter notebook Notebooks/Name_Recommendation_Model.ipynb

---

💡 Key Skills Demonstrated

✔ Natural Language Processing (NLP)
✔ Embedding-based similarity modeling
✔ Feature extraction and vectorization
✔ ML system prototyping
✔ Problem framing for creative AI applications

---

📌 Why It Matters

This project illustrates how machine learning techniques — particularly embeddings and semantic similarity — can be used beyond standard supervised tasks. It highlights capabilities highly relevant to:

Recommendation engines

Generative AI systems

Semantic search applications

AI-driven creative tools

It bridges theory and practical impact, which is exactly what hiring managers look for in ML and data science candidates.

---

🔮 Future Enhancements

Enhancement ideas you can clearly articulate in interviews or portfolio updates:

✔ Integrate pretrained transformer embeddings (e.g., BERT, Sentence-Transformers)
✔ Add user preference learning using feedback loops
✔ Build an API with FastAPI or Flask for deployment
✔ Add a web UI for interactive name generation

---

📍 Author

Dhruv Sharma — Machine Learning Engineer | Data Scientist
Portfolio: https://github.com/Dhruvsharma132
LinkedIn: https://www.linkedin.com/in/dhruv-sharma-4791b723a/

## 📁 Repo Structure

