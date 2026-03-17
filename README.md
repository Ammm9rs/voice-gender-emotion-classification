# Voice-gender-emotion-classification
ML models to classify **gender** and **emotion** from voice recordings.

## Results
| Model | Accuracy |
|-------|----------|
| Linear SVM | 97.41% |
| Logistic Regression | 97.16% |
| Gaussian Naive Bayes | 89.08% |
| Bernoulli Naive Bayes | 86.43% |

## Tech Stack
Python, scikit-learn, pandas, librosa, matplotlib

## Dataset
- Gender: 3168 voice samples (Kaggle)
- Emotion: 2452 audio files, 4 emotions

## Key Decisions
- Used Stratified K-Fold CV to handle sorted dataset bias
- sklearn Pipeline to prevent data leakage
