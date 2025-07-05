# 🧠 Question Answering System with BERT

This project implements a Question Answering (QA) pipeline using **BERT** (Bidirectional Encoder Representations from Transformers), a powerful pre-trained transformer model. The goal is to accurately extract answers from a given passage based on user queries.

---

## 📌 Project Overview

Using Hugging Face's Transformers library, this system leverages a fine-tuned BERT model to perform extractive question answering. It is applied to a domain-specific use case — answering questions based on **medical-related text**, such as clinical notes.

---

## 💡 Key Features

- Utilizes a pre-trained **BERT QA model** (`bert-large-uncased-whole-word-masking-finetuned-squad`)
- Accepts custom input passages and questions
- Extracts and returns the most probable answer span
- Clean and modular pipeline for easy experimentation

---

## 📁 Dataset / Input

The system can be applied to any paragraph of text. In this project, sample questions are derived from passages related to the **medical domain** for contextual testing.

---

## 🛠️ Requirements

- Python 3.6+
- Transformers (`pip install transformers`)
- PyTorch or TensorFlow (compatible with Hugging Face models)
- Jupyter Notebook (for running the demo)

---

## 🚀 How to Run

1. Clone the repository
2. Install the required libraries
3. Open the `Question_Answering_BERT.ipynb` notebook
4. Run through the cells to load the model and test it on custom passages and questions

---

## 📊 Future Improvements

- Expand to multi-passage retrieval for open-domain QA
- Include confidence scores and multiple answer suggestions
- Add a user interface (e.g., Streamlit or Flask web app)

---

## 🧪 Example Use Case

> **Passage:** _"...The patient was diagnosed with type 2 diabetes and started on metformin..."_  
> **Question:** _"What medication was prescribed?"_  
> **Answer:** _"metformin"_

---

## 📜 License

This project is for educational and non-commercial use. Refer to the original BERT license under [Google Research](https://github.com/google-research/bert).

---

Feel free to contribute or customize it to other domains like legal, finance, or education!
