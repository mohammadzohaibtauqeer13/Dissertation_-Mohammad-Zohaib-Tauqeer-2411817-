README - LLMs for Heart Disease Prediction Using Tokenized ECG Data
Mohammad Zohaib Tauqeer – 2411817 

  ------------------------------------------------------------
  📘 PROJECT OVERVIEW
  ------------------------------------------------------------
  This project predicts the Big Five Personality Traits
  (Openness, Conscientiousness, Extraversion, Agreeableness,
  Neuroticism) using machine learning and deep learning
  models. It was developed as part of a Master’s dissertation.

  The notebook FINAL_DISSERTATION.ipynb contains the
  end‑to‑end workflow: - Data loading and preprocessing -
  Model training (Logistic Regression, Random Forest, XGBoost,
  LSTM) - Evaluation using ML metrics - Explainability using
  SHAP and LIME - Result visualisation and comparison
  ------------------------------------------------------------

📁 PROJECT STRUCTURE

FINAL_DISSERTATION_ Mohammad Zohaib Tauqeer – 2411817.ipynb – Full pipeline notebook data/ – Persona‑Chat +
Wikipedia processed datasets models/ – Trained models results/ –
Metrics/plots (confusion matrices, ROC curves, SHAP outputs)

  ------------------------------------------------------------
  📄 FEATURES
  ------------------------------------------------------------
  1. Dataset Preparation - Persona‑Chat dataset (Zhang et
  al.) - Wikipedia text data - Cleaning, tokenisation,
  splitting - Big Five scoring and labelling

  2. Models Implemented Traditional ML: - Logistic
  Regression - Random Forest - XGBoost

  Deep Learning: - LSTM neural network

  3. Training & Tuning - TF‑IDF vectorisation for ML models -
  Embeddings + padded sequences for LSTM - Grid search /
  manual tuning - Early stopping

  4. Evaluation Metrics - Accuracy, Precision, Recall,
  F1‑Score - ROC‑AUC - Confusion Matrix

  5. Explainability - SHAP value explanations for feature
  contributions - LIME text explanations
  ------------------------------------------------------------

📊 OUTPUTS GENERATED

The notebook produces: - Accuracy/F1 comparisons - ROC curves - SHAP
summary plots - LIME explanations - LSTM training curves - Model
comparison tables

  ------------------------------------------------------------
  🛠 TECHNOLOGIES USED
  ------------------------------------------------------------
  Python 3 NumPy, Pandas Scikit-learn TensorFlow / Keras
  XGBoost Matplotlib SHAP, LIME SpaCy / NLTK

  ------------------------------------------------------------

🚀 HOW TO RUN

▶ Environment Setup
1. Create a Python 3 environment
2. Install required libraries:
   pip install -r requirements.txt

▶ Data Setup
3. If using PTB-XL ECG data:
   - Upload ptb-xl.zip to Google Drive
   - Run the extraction code block in Colab to prepare data

▶ Model Execution
4. Open FINAL_DISSERTATION.ipynb
5. Execute each section in order:
   - Data loading & preprocessing
   - Model training (ML + LSTM)
   - Evaluation & explainability
   - Results export

Results will be saved in the results/ folder.


  ---------------
  📚 REFERENCES
  ---------------

Zhang et al., Persona‑Chat Dataset Hochreiter & Schmidhuber (1997) –
LSTM Big Five Personality Theory Literature
