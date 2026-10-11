# Week 3 Task 2: NLP - Text & Sentiment Classification

## Overview
This directory contains the Jupyter Notebook (`week_3_task_2_NLP.ipynb`) for Week 3 Task 2 of the EvolviX AI/ML Internship. The objective of this task is to perform sentiment classification on the IMDb movie reviews dataset by comparing a classical Machine Learning baseline with a Deep Learning Transformer model.

## Models Used
1. **Classical ML Approach:** TF-IDF Vectorizer + Logistic Regression.
2. **Deep Learning Approach:** Hugging Face Transformer pipeline using a fine-tuned model (`ahmed792002/Finetuning_Longformer_IMDb_movie_reviews_Classification`).

## Performance Comparison
Based on the testing phase in the notebook, here is how the two models compared:

* **Classical (TF-IDF) Model:** 
  * Accuracy: 0.71 (71%)
  * F1-Score: 0.72
* **Hugging Face Transformer:** 
  * Accuracy: 0.94 (94%)
  * F1-Score: 0.94

## Example Prediction
Here is an example of a sentiment prediction made by the Transformer model during inference:

> **📝 Review:** *"This movie was absolutely fantastic and I loved the acting!"*
> 
> **🎭 Sentiment:** 🟢 POSITIVE (Thumbs Up!)
> 
> **🎯 Confidence Score:** 99.90%

## Discussion: Classical vs. Transformer
While the classical TF-IDF model provided a solid baseline, it fundamentally relies on word frequencies and ignores word order, context, and complex sentence structures. Because of this, it can struggle with nuances like sarcasm or double negatives in reviews. 

On the other hand, the Hugging Face Transformer model significantly outperformed the classical approach (jumping from 71% to 94% accuracy). The transformer's self-attention mechanism allows it to understand the deep contextual meaning of the entire sentence, making it far superior at accurately classifying the true sentiment of complex movie reviews.
