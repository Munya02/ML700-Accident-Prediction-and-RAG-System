# README.txt

## Project Title

Machine Learning, Reinforcement Learning, and Retrieval-Augmented Generation (RAG) System Using South African Road Accident Data and Parliamentary Hansard Transcripts

---

## Project Description

This project consists of two main components:

### Component A

* Accident Severity Prediction using XGBoost
* Reinforcement Learning using Q-Learning for road safety decision-making

### Component B

* Data Preparation and Embedding Generation using Parliamentary Hansard Transcripts
* Transformer Fine-Tuning using DistilBERT for sentiment classification
* Retrieval-Augmented Generation (RAG) using FAISS and FLAN-T5 for policy-focused question answering

---

## Python Version

Python 3.12

---

## Dependencies

Install the required libraries using:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install xgboost
pip install torch
pip install transformers
pip install sentence-transformers
pip install faiss-cpu
pip install PyMuPDF
pip install accelerate
```

Or install all at once:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost torch transformers sentence-transformers faiss-cpu PyMuPDF accelerate
```

---

## Dataset Files Required

### Component A

* South Africa Road Accidents Dataset - 2017.xlsx

### Component B

Hansard Parliamentary Transcript PDFs:

* paliament 2022.pdf
* part 2 2022 paliament.pdf
* 2023 paliament.pdf
* 2023 part 2 paliament.pdf
* 2024_paliament.pdf
* 2024_part 2 paliamnet.pdf
* 2025_paliament.pdf
* part 2 2025 paliament.pdf

---

## Running the Notebook

1. Open Google Colab or Jupyter Notebook.
2. Upload all dataset files.
3. Open the notebook file.
4. Run all cells from top to bottom.
5. Wait for model training and evaluation to complete.
6. Review generated outputs, visualisations, evaluation metrics, and RAG responses.

---

## Notebook Structure

### Component A

1. Data Loading
2. Data Cleaning
3. Feature Encoding
4. Train/Test Split
5. XGBoost Training
6. Model Evaluation
7. Reinforcement Learning
8. Q-Learning Training
9. Policy Evaluation

### Component B

1. PDF Extraction
2. Text Cleaning
3. Tokenization
4. Embedding Generation
5. DistilBERT Fine-Tuning
6. Sentiment Classification Evaluation
7. FAISS Vector Database Creation
8. Retrieval-Augmented Generation
9. RAG Evaluation

---

## Expected Runtime

Approximate runtime in Google Colab:

| Task                   |     Estimated Time |
| ---------------------- | -----------------: |
| Data Preparation       |       5–10 minutes |
| XGBoost Training       | Less than 1 minute |
| Reinforcement Learning | Less than 1 minute |
| PDF Processing         |       5–10 minutes |
| Embedding Generation   |       5–15 minutes |
| DistilBERT Fine-Tuning |      10–20 minutes |
| RAG Setup and Testing  |       5–10 minutes |

Total Estimated Runtime:

20–45 minutes depending on hardware and internet speed.

---

## Hardware Requirements

Minimum:

* 8 GB RAM
* Dual-Core CPU

Recommended:

* Google Colab Runtime
* GPU acceleration (T4 or better)
* 12 GB RAM or higher

---

## Output Files

The notebook produces:

* Trained XGBoost Model
* Reinforcement Learning Q-Table
* DistilBERT Sentiment Classifier
* Semantic Embeddings
* FAISS Vector Index
* RAG Question Answering Outputs
* Evaluation Metrics
* Confusion Matrices
* Visualisations and Reports

---

## Author

Munyaradzi

Machine Learning 700 Assignment
