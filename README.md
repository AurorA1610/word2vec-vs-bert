# Tweet Sentiment Analysis: A Comparison of Word2Vec and BERT Embeddings

This project compares two text representation techniques, Word2Vec and BERT, for sentiment classification of tweets. A simple neural network is trained on both embeddings, and their performance is evaluated.

## Objectives

- Using pretrained **Word2Vec** and **BERT** models for text embeddings
- Showing embeddings of some selected adjectives
- Finding top 5 most similar words using both models
- Using two 2-layer neural network classifiers:
  - Word2Vec-based tweet representation
  - BERT-based tweet representation
- Comparing performance of the classifiers based on F1-score

---

## Technologies Used

- Python
- Gensim (Word2Vec)
- Hugging Face Transformers (BERT)
- PyTorch
- Scikit-learn
- NumPy
- Pandas

---

## Result

- BERT produces richer sentence representations, leading to higher classification performance.
- BERT creates contextual embeddings. The same word has different representations depending on its sentence context.
- Unlike Word2Vec, BERT captures word order and relationships using attention mechanisms.
- BERT understands phrases like “not good” correctly. Word2Vec averaging loses such meaning.
