## ai_evaluation_assessment

# Automarker Evaluation Project

This project evaluates the performance of a BERT-based writing automarker against human-assigned scores for English language learners. It was developed as part of an interview assessment for evaluating automated scoring systems in high-stakes contexts like visa or university entrance exams.

## 📁 Project Structure

- evaluation_set.csv – Dataset containing both automarker and human scores
- train_dev_set.csv – Training/development data (no automarker predictions)
- score_mappings.csv – Mapping from raw scores to CEFR levels and pass/fail outcomes
- AI_EVAL.ipynb – Main analysis notebook
- README.md – Project overview and setup instructions

## 🔍 Evaluation Steps

1. Raw Score Accuracy  
   - Metrics: RMSE, MAE, R²  
   - Visual: Scatter plot comparing automarker vs. human scores

2. CEFR Classification Accuracy  
   - Metrics: Precision, Recall, F1-score, Confusion Matrix  
   - Focus: Alignment of CEFR level predictions with human ratings

3. Pass/Fail Binary Classification  
   - Metrics: Accuracy, Precision, Recall, F1-score  
   - Visual: Confusion matrix for binary decisions

4. Confidence Calibration  
   - Examines how well the automarker's confidence score reflects actual correctness  
   - Visual: Calibration curve (confidence bins vs. CEFR agreement)

## 🧪 How to Run

1. Clone the repository:
   - git clone https://github.com/kabirolawore/ai_eval_assessmt.git
   - cd ai_eval_assessmt
   - run
