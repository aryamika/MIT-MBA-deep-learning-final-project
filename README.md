# Detecting Fake Job Postings with Deep Learning

Welcome to our GitHub repository! Here, we've documented our journey tackling the critical issue of fake job postings using machine learning and deep learning techniques. We created models that accurately identify genuine job ads, scam postings, and deceptive "ghost jobs."

## Why It Matters
Fake job postings negatively affect job seekers and employers alike:
- **Scam postings:** Trick applicants into financial fraud or identity theft.
- **Ghost jobs:** Companies post these without intending to hire, misleading applicants and creating frustration.

Our goal was to build automated systems that make the job market safer and more transparent.

## What We Set Out to Do
- Develop machine learning models (Logistic Regression and BERT) to detect fake job ads.
- Understand the key features that distinguish real postings from fraudulent ones.
- Address challenges like class imbalance and evaluate the models' performance.
- Consider trade-offs between model complexity and practical real-world use.

## How We Did It
- **Data Collection:** We leveraged Kaggle datasets with examples of both scam and ghost job postings.
- **Data Preparation:** Combined and cleaned datasets, removed duplicates, and applied NLP methods including Bag-of-Words and BERT tokenization.
- **Baseline Model:** We first tested a logistic regression model as a baseline to establish performance benchmarks.
- **Advanced Model:** Next, we fine-tuned a BERT transformer model for deeper, context-sensitive analysis.

## Our Results

| Metric              | Logistic Regression | BERT Transformer |
|---------------------|---------------------|------------------|
| **Accuracy**        | 98.12%              | **98.34%**       |
| **Precision**       | 98.63%              | **98.87%**       |
| **Recall**          | 96.78%              | **97.08%**       |
| **F1-Score**        | 97.70%              | **97.96%**       |
| **ROC-AUC**         | 99.24%              | **99.67%**       |

Our BERT model outperformed the baseline, significantly reducing misclassification and improving overall detection accuracy.

## Lessons We Learned
- Dataset balancing was crucial for our models' success.
- BERT's ability to understand context greatly improved performance.
- Real-world application depends on balancing model complexity and computational efficiency.

## What's Next
- Further optimizing BERT through hyperparameter tuning.
- Exploring simpler, faster models for more efficient deployment.
- Validating our models on external, unseen datasets.

## Contributors
This project was a collaborative effort—I worked alongside three classmates:
- Radhika Anbazhagan
- Clemence Couteau
- Reid Silverhart

## Explore Further
- [Google Colab Notebook](https://colab.research.g
