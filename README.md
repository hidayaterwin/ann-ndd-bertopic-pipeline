# ann-ndd-bertopic-pipeline

This repository contains the Jupyter Notebook used for the topic modeling component of our scientometric analysis:  
**“Artificial Neural Networks in Image-Based Neurodevelopmental Disorder Research: A Scientometric and Topic Modeling Review (2004–2024)”**

## 📂 Contents

- `BERTopic_V2.ipynb` — The full topic modeling pipeline implemented in Python.
- **Data** — Not included for privacy reasons. See the Data Availability statement in our paper for details.

## 🧩 Methodology

This notebook reproduces the topic modeling workflow described in the Methods section of our paper.  
Key steps include:
- Text preprocessing with SpaCy (lemmatization, stopword removal)
- Sentence embeddings using the `all-MiniLM-L6-v2` model (Sentence-Transformers)
- Dimensionality reduction with UMAP
- Clustering with HDBSCAN
- Topic modeling with BERTopic
- Class-based TF-IDF scoring for interpretable keywords
- Topic probabilities estimation

## 🗃️ Dependencies

The pipeline uses the following Python libraries:
- BERTopic
- Sentence-Transformers
- SpaCy
- UMAP-learn
- HDBSCAN
- scikit-learn
- Matplotlib / Plotly (for visualization)

All packages were used in their stable versions as of the paper’s final submission.

## ⚙️ How to run

You can open and run the notebook in:
- **Google Colab** (recommended for easy setup)
- **Jupyter Notebook** (locally, if you have the dependencies installed)

⚡ For Google Colab:
1. Upload your own cleaned dataset matching the structure described in our paper.
2. Adjust the file path in the notebook if needed.
3. Run each cell step by step.

## 🔒 Data Availability

Due to licensing and privacy considerations, the cleaned dataset used in this study is not included in this repository. Please refer to the *Data Availability* section of the paper for more information.

## 📜 Citation

If you use this code for academic purposes, please cite our paper:
> *[Your paper citation here, e.g., DOI or preprint link]*

---

