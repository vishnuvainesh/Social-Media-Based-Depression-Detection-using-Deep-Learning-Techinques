# Social Media-Based Depression Detection using RoBERTa and DeBERTa

## Overview

This project focuses on detecting signs of depression from social media posts using state-of-the-art Transformer-based Natural Language Processing (NLP) models. The system analyzes textual content from social media and classifies whether a post indicates depressive behavior or not.

Two powerful pre-trained language models were fine-tuned and evaluated:

- RoBERTa (Robustly Optimized BERT Pretraining Approach)
- DeBERTa (Decoding-enhanced BERT with Disentangled Attention)

The project demonstrates the application of Deep Learning and NLP techniques in mental health analysis and text classification.

---

## Features

- Social media text preprocessing and cleaning
- Transformer-based text classification
- Fine-tuning of RoBERTa and DeBERTa models
- Performance evaluation using multiple metrics
- Confusion Matrix visualization
- Custom text prediction interface
- Experiment tracking using Weights & Biases (W&B)

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- RoBERTa
- DeBERTa
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Weights & Biases (W&B)
- Jupyter Notebook

---

## Dataset

The project utilizes the Mental Health Twitter Dataset containing social media posts labeled as:

- Depressed
- Not Depressed

The dataset was preprocessed before training to improve model performance.

---

## Project Workflow

### 1. Data Preprocessing

- Text cleaning
- Removing URLs
- Removing mentions (@username)
- Removing hashtags
- Handling missing values
- Normalizing text

### 2. Dataset Preparation

- Training Set (80%)
- Validation Set (10%)
- Testing Set (10%)

### 3. Model Fine-Tuning

#### RoBERTa
- Model: `roberta-base`
- Max Sequence Length: 128
- Epochs: 10
- Learning Rate: 2e-5

#### DeBERTa
- Model: `microsoft/deberta-base`
- Max Sequence Length: 128
- Epochs: 10
- Learning Rate: 2e-5

### 4. Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

### 5. Prediction

Users can input custom social media text and receive a prediction indicating whether the content is likely to express depressive behavior.

---

## Applications

- Mental Health Research
- Depression Detection
- Social Media Analytics
- Sentiment Analysis
- Healthcare AI Solutions
- NLP-based Text Classification

---

## Future Improvements

- Real-time social media monitoring
- Multi-language support
- Deployment using Streamlit or Flask
- Explainable AI integration
- Ensemble transformer models

---

## Results

Both RoBERTa and DeBERTa models successfully learned patterns from social media posts and demonstrated strong performance in depression classification tasks.

> Add your final Accuracy, Precision, Recall, and F1-Score values here.

---

## AI Assistance

This project was developed with the assistance of AI tools for:

- Code generation and optimization
- Debugging and troubleshooting
- Documentation preparation
- Model implementation guidance
- Workflow improvement suggestions

All generated content was reviewed, modified, tested, and validated before final implementation.

---

## Author

**Vishnupriyan V**

B.Tech Electronics and Computer Engineering (AI & Data Science)

Karunya Institute of Technology and Sciences

### Skills Demonstrated

- Deep Learning
- Natural Language Processing (NLP)
- Transformer Models
- RoBERTa
- DeBERTa
- PyTorch
- Hugging Face Transformers
- Machine Learning
- Data Analysis
- AI for Healthcare
