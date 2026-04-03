# North-Face_NLP_Clustering

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Clustering-orange.svg)

This project applies **Unsupervised Machine Learning** and **Natural Language Processing (NLP)** to optimize the online product catalog of The North Face. 

By analyzing technical item descriptions, we identify hidden patterns to enhance user navigation and automate product suggestions.

## 🎯 Project Objectives
1.  **Product Clustering**: Grouping items with similar technical specifications using density-based spatial clustering.
2.  **Recommender System**: Building a functional tool to suggest 5 similar items based on a specific Product ID.
3.  **Topic Modeling (LSA)**: Extracting latent themes (e.g., waterproofing, thermal insulation, trail running) to challenge and improve existing catalog categories.

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **NLP**: SpaCy (using the `en_core_web_sm` model)
* **Machine Learning**: Scikit-Learn (TF-IDF Vectorization, DBSCAN, TruncatedSVD)
* **Visualization**: Matplotlib, WordCloud

## 🚀 Installation & Usage

1. **Clone the repository**:
```bash
git clone [https://github.com/YOUR_USERNAME/north-face-product-analysis.git](https://github.com/YOUR_USERNAME/north-face-product-analysis.git)
