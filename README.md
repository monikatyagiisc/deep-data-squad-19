# 🧠 deep-data-squad-19: Cross-Lingual Intent Classification using BERT

**Mini Project by Team Data Miners**

## 📌 Project Overview

Conversational AI systems—such as chatbots, virtual assistants, and automated customer support—must increasingly operate across languages. This project focuses on **Cross-Lingual Intent Classification** using **multilingual BERT (mBERT)** to classify user intents in multiple languages: **English, Spanish, French, and Hindi**.

We fine-tune a transformer-based model (BERT) to accurately detect user intent across language boundaries, making AI systems more inclusive and capable of seamless cross-cultural interaction.

---

## 🎯 Objectives

- Classify user intents using pre-trained **mBERT**.
- Address challenges like:
  - Language diversity
  - Data sparsity
  - Domain-specific vocabulary
- Evaluate multilingual performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## 📂 Repository Structure

```
deep-data-squad-19/
│
├── code/                                    
│   ├── multilingual_intent_classification.ipynb # Main notebook
├── requirements.txt                         	 # Python dependencies
├── data/                                        # Folder for multilingual datasets
│   ├── english.csv
│   ├── spanish.csv
│   ├── french.csv
│   └── hindi.csv
├── reports/								    # Folder for evaluation reports
├── models/        								# Folder for saved model checkpoints
│   └── mbart_model.pth                          # Fine-tuned mBERT model
└── README.md                                   # Project documentation
```
---

## 🔧 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/deep-data-squad-19.git
cd deep-data-squad-19
```


2.	Create a virtual environment and install dependencies:
•	On Linux/macOS:
	```bash
	python -m venv venv
	source venv/bin/activate  
	```
    •	On Windows use 
	```bash
	venv\Scripts\activate
	```
3.	Install required dependencies:
	```bash
	pip install -r requirements.txt
	```

---

## 🚀 Usage

Launch Jupyter Notebook and run the classification pipeline:

jupyter notebook multilingual_intent_classification.ipynb

The notebook includes steps for:
	•	Data loading and preprocessing
	•	Tokenization using mBERT
	•	Fine-tuning the model
	•	Evaluating across all supported languages

Ensure your dataset files (english.csv, spanish.csv, etc.) are placed inside the data/ folder.


## 📊 Evaluation Metrics

We use the following performance metrics to evaluate the model for each language:
	•	✅ Accuracy
	•	📍 Precision
	•	🔁 Recall
	•	🏅 F1-Score

This helps assess mBERT’s cross-lingual understanding and intent detection capability.


## 🧪 Dependencies

The project uses the following libraries:
	•	transformers
	•	torch
	•	scikit-learn
	•	pandas
	•	numpy
	•	matplotlib

Full list in: requirements.txt


## 🤝 Contributors
	•	Abhishek Gupta
	•	Bharat Karthi R K
    •	Gayathri ramasubramaniyam
	•	Harikrishnan C
    •	Indrerjit Singh Chahuan
	•	Monika Tyagi



## 📜 License

This project is for educational and academic use. For any external or commercial usage, please contact the authors.



## 🌐 Acknowledgments

Special thanks to:
	•	Hugging Face 🤗 for the transformers library
	•	BERT multilingual pre-trained models
	•	Jupyter & open-source community

