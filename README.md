# Sentimental-Analysis-of-User-feedback-VADER-Lexicon-vs-distilbert-vs-RoBERTa-vs-Ensemble-Approach-

## Overview
This project compares different sentiment analysis models to evaluate user feedback. We analyze sentiment using the following approaches:

- **VADER Lexicon** (Rule-based sentiment analysis)
- **DistilBERT** (A lightweight transformer-based model)
- **RoBERTa** (A robustly optimized BERT model)
- **Ensemble Approach** (Combining multiple models for better accuracy)

## Objective
The goal of this project is to determine which model performs best in analyzing user feedback and to explore how an ensemble approach can enhance sentiment prediction.

## Dataset
- https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset

## Methodology
1. **Preprocessing**: Not done as our main focus is classification of the user feedback into positive / negative/ neutral sentiment (sentimental analysis)
2. **Applying Sentiment Models**:
   - VADER for rule-based sentiment analysis.
   - DistilBERT and RoBERTa for deep learning-based sentiment classification.
   - An ensemble method combining these models.
3. **Evaluation Metrics**:
   - Accuracy

4. **Comparison**: Analyzing how many user feedbacks we could classify properly matching with given ideal output in the dataset.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **NLTK** (VADER implementation)
- **Hugging Face Transformers** (DistilBERT, RoBERTa)
- **PyTorch** (Deep learning framework)

## Results & Findings
- VADER Lexicon: 85 were classified correctly out of 96 responses.
- distilbert: 95 were classified correctly out of 96 responses.
- RoBERTa: All were classified correctly out of 96 responses.
- Ensemble approach: All of them classified correctly out of 96 responses.

## Future Work
- Fine-tuning transformer models for better accuracy.
- Expanding dataset diversity.
- Real-time sentiment tracking for feedback streams.
- (please refer to https://github.com/greekyogurt9/Sentimental-Analysis-of-User-feedback-Training-and-Fine-Tuning-model-)

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

---

### Author
Ankita B.

For any queries, reach out via GitHub issues or email.

