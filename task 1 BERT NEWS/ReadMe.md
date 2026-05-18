# 🧠 News Topic Classifier Using BERT
Objective

Build a transformer-based NLP model to classify news headlines into categories like World, Sports, Business, and Technology using BERT.

---

Dataset

* AG News Dataset (from Hugging Face)
* 4 classes of news topics

---

Workflow

Data Preprocessing

* Loaded dataset using `datasets` library
* Cleaned and structured text data

Tokenization

* Used `bert-base-uncased` tokenizer
* Applied padding and truncation
* Generated input IDs and attention masks

Model Training

* Fine-tuned pre-trained BERT model
* Used Hugging Face `Trainer` API
* Loss function: CrossEntropyLoss

Evaluation

* Accuracy
* F1-Score

---
Deployment

* Built interactive UI using Streamlit / Gradio
* Users can input custom news text
* Model predicts category instantly

---

Tech Stack

* Python
* Hugging Face Transformers
* PyTorch
* Scikit-learn
* Streamlit / Gradio

---

Skills Learned

* NLP using Transformers
* Transfer Learning
* Text Classification
* Model Deployment

---

How to Run

```bash
pip install transformers datasets torch scikit-learn streamlit
python train.py
streamlit run app.py
```

---

Output

* Classified news category
* Model evaluation metrics

---
