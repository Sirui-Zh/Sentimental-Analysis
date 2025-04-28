# Sentiment Analysis - CS 3780/5780 Kaggle Competition

This repository contains my work for the "How Do You Feel?" sentiment analysis challenge on Kaggle, part of the CS 3780/5780 course.

## Competition Link
- [Kaggle Competition: How Do You Feel?](https://www.kaggle.com/competitions/cs-3780-5780-how-do-you-feel/submissions)

## Final Results
| Model | Public Score | Private Score |
|:---|:---|:---|
| BERT Fine-tuning | **0.76420** | **0.76960** |
| Logistic Regression Baseline | 0.65710 | 0.65300 |

🏅 **Final Ranking: 6th out of 126 participants**

---

## Files Included
- `Sentimental Analysis.ipynb`: Full training code for baseline logistic regression and fine-tuned BERT model.
- `bert_submission.csv`: Kaggle submission file generated from the BERT model.
- `logistic_regression_submission.csv`: Kaggle submission file generated from the logistic regression model.

---

## Model Summary
- **BERT Model**: 
  - Pretrained `bert-base-uncased`
  - Fine-tuned with cross-entropy loss
  - Max sequence length: 32
  - Batch size: 16
  - Learning rate: 2e-5
  - Achieved the best competition score

- **Baseline Logistic Regression**: 
  - TF-IDF vectorizer + simple logistic regression classifier.
  - Provided a reasonable baseline performance.

---

## Notes
- The BERT model significantly outperformed the traditional logistic regression approach.
- Fine-tuning and sequence length tuning were crucial for achieving a top-10 finish.
