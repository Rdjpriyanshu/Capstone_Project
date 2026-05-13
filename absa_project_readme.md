# Aspect-Based Sentiment Analysis (ABSA) using RoBERTa

## Overview
This project implements an **Aspect-Based Sentiment Analysis (ABSA)** system using the **RoBERTa transformer model**. The model classifies sentiments into different categories such as positive, negative, and neutral for aspect-level text analysis.

The notebook includes:
- Data preprocessing
- Model training using RoBERTa
- Evaluation metrics and visualizations
- Confusion matrix generation
- Interactive Gradio interface for predictions

---

# Features
- Transformer-based sentiment classification using RoBERTa
- GPU support with PyTorch
- Class balancing using weighted loss
- Model evaluation using:
  - Accuracy
  - F1 Score
  - Classification Report
- Visualization of model performance
- Interactive web interface using Gradio

---

# Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Pandas & NumPy
- Matplotlib
- Gradio
- spaCy

---

# Project Structure
```bash
├── Absa_Improved.ipynb     # Main notebook
├── dataset/                # Dataset files
├── model/                  # Saved trained model
├── outputs/                # Graphs and reports
└── README.md               # Project documentation
```

---

# Installation
Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Install dependencies:

```bash
pip install torch transformers accelerate scikit-learn pandas numpy matplotlib gradio spacy
```

Download spaCy model:

```bash
python -m spacy download en_core_web_sm
```

---

# Running the Project
Open the Jupyter notebook:

```bash
jupyter notebook Absa_Improved.ipynb
```

Run all cells step by step for:
1. Data preprocessing
2. Model training
3. Evaluation
4. Visualization
5. Gradio deployment

---

# Model Training
The project uses:
- **RoBERTaForSequenceClassification**
- **AdamW Optimizer**
- **Linear Learning Rate Scheduler**
- **Weighted Loss for Imbalanced Data**

---

# Evaluation Metrics
The model performance is evaluated using:

- Accuracy Score
- F1 Score
- Precision & Recall
- Confusion Matrix
- Classification Report

---

# Gradio Interface
An interactive Gradio UI is included to test sentiment predictions in real time.

Example:

```python
predict_sentiment("The food quality was amazing but service was slow")
```

---

# Sample Output
- Positive Sentiment
- Negative Sentiment
- Neutral Sentiment

---

# Future Improvements
- Multi-aspect sentiment extraction
- Deployment using Streamlit or Flask
- Hyperparameter tuning
- Support for multilingual sentiment analysis
- Real-time API integration

---

# Author
**Priyanshu Yadav**
- Data Science Engineer
- Android Developer

---

# License
This project is for educational and research purposes.

