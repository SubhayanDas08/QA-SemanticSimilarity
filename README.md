# QA-SemanticSimilarity
## 📂 Project Overview

This project focuses on semantic similarity scoring between questions and paragraphs using different methodologies. The dataset consists of train and test questions organized in two separate sheets.

## 🛠 Tech Stack

- **Programming Languages:** Python  
- **Libraries & Frameworks:** Sentence Transformers, Parrot, Levenshtein, Pandas, NumPy  
- **Similarity Metrics:** Cosine Similarity, Levenshtein Distance  
- **Tools:** Jupyter Notebook, Excel  

## 📊 Notebooks and Implementations

### 1. **v1_Semantic Sentence Matching - Cosine.ipynb**
- **Methodology:** Sentence Transformer for embedding generation, Cosine Similarity for similarity calculation.  
- **Accuracy:** 78%

### 2. **v2_Semantic Sentence Matching - Levenshtein.ipynb**
- **Methodology:** Custom embeddings using the Levenshtein library for similarity computation.  
- **Accuracy:** 43%

### 3. **v3_Semantic Sentence Matching - Cosine.ipynb**
- **Methodology:** Data augmentation using Parrot, Sentence Transformer for embeddings, and Cosine Similarity for similarity calculation.  
- **Accuracy:** 83%

### 4. **v1_Semantic Paragraph Similarity Scoring.ipynb**
- **Methodology:** Sentence Transformer for embedding generation and Cosine Similarity for pairwise paragraph similarity.

## 📁 Dataset

- The dataset is organized into two sheets:  
  - **Train Questions**  
  - **Test Questions**  

## 📦 Requirements

To run the `v1_Semantic Paragraph Similarity Scoring.ipynb`, install the required Parrot library:

```bash
pip install git+https://github.com/PrithivirajDamodaran/Parrot_Paraphraser.git
