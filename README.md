# Gender & Emotion Classification using voice

ML models to classify **gender** and **emotion** from voice recordings.

## Gender Recognition Results
| Model | Accuracy |
|-------|----------|
| Linear SVM | 97.41% |
| Logistic Regression | 97.16% |
| Gaussian Naive Bayes | 89.08% |
| Bernoulli Naive Bayes | 86.43% |

## Emotion Recognition Results
| Model | Accuracy |
|-------|----------|
| Random Forest | 91.9% |
| Decision Tree | 87.9% |
| SVM | 63.6% |

## Tech Stack
Python, scikit-learn, librosa, pandas, matplotlib, seaborn

## Key Improvements Over Original
- Fixed sorted dataset bias using Stratified K-Fold
- Prevented data leakage using sklearn Pipeline
- Added fearful emotion class (5 vs 4 emotions)
- Improved emotion accuracy from 76% to 91.9%
