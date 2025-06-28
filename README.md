# deep-data-squad-19: Cross-Lingual Intent Classification using BERT

**Mini Project by Team Data Miners**

## Live Demo

Try the multilingual intent classification demo here:  
-> [Hugging Face Spaces – IntentBert](https://huggingface.co/spaces/charikri/IntentBert#multilingual-intent-classification)

---

## Project Overview

Conversational AI systems—such as chatbots, virtual assistants, and automated customer support—must increasingly operate across languages. This project focuses on **Cross-Lingual Intent Classification** using **multilingual BERT (mBERT)** to classify user intents in multiple languages: **English, Spanish, French, and Hindi**.

We fine-tune a transformer-based model (BERT) to accurately detect user intent across language boundaries, making AI systems more inclusive and capable of seamless cross-cultural interaction.

---

## Objectives

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

## Dataset

This project leverages the **MASSIVE dataset** provided by Amazon Science:  
-> [Hugging Face – MASSIVE Dataset](https://huggingface.co/datasets/AmazonScience/massive)

MASSIVE is a multilingual dataset for NLU tasks and supports over 50 intents across 51 languages, making it an ideal resource for multilingual intent classification.

---

## Reports and Documentation

- [Final Report (PDF)](https://github.com/monikatyagiisc/deep-data-squad-19/blob/main/reports/Final_Report.pdf)  
- [Shared Spreadsheet – Team Documentation](https://indianinstituteofscience-my.sharepoint.com/:x:/g/personal/rgayathri_iisc_ac_in/ER1sFJFsbsFLj66COTgWDYoBy5lkDJKdJZZ77cQ8MIeHsg?e=UK7NUV&ovuser=6f15cd97-f6a7-41e3-b2c5-ad4193976476%2Cmonikatyagi%40iisc.ac.in&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiI1MC8yNTA2MDIwNjYxMiIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D)   
- Architecture diagram: `Documents/architecture.puml`  
- Training heatmap: `models/model_training_performance_heatmap.png`  
- Paper assets: `reports/DA-225o-Deep-Learning-Team-19/`

---

## Repository Structure

```
deep-data-squad-19/
├── code/
│   └── multilingual_intent_classification.ipynb          # Main notebook
├── data/                                                 # Multilingual datasets
│   ├── english.csv
│   ├── french.csv
│   ├── hindi.csv
│   ├── spanish.csv
│   └── README.md
├── documents/
│   └── architecture.puml                                 # UML architecture diagram
├── models/                                               # Saved model checkpoints & performance visuals
│   ├── mbart/
│   ├── model_training_performance_heatmap.png
│   └── README.md
├── reports/                                              # Evaluation reports and LaTeX paper
│   ├── Abstract.pdf
│   ├── Final_Report.pdf
│   └── DA-225o-Deep-Learning-Team-19/
│       ├── architecture.png
│       ├── f1_chart.png
│       ├── main.tex
│       ├── mybibfile.bib
│       └── Tuning.png
├── README.md                                             # Project documentation
└── requiremets.txt                                       # Python dependencies
```

## Installation

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

## Usage

Launch Jupyter Notebook and run the classification pipeline:

jupyter notebook multilingual_intent_classification.ipynb

The notebook includes steps for:
	•	Data loading and preprocessing
	•	Tokenization using mBERT
	•	Fine-tuning the model
	•	Evaluating across all supported languages

Ensure your dataset files (english.csv, spanish.csv, etc.) are placed inside the data/ folder.


## Evaluation Metrics

We use the following performance metrics to evaluate the model for each language:
	•	Accuracy
	•	Precision
	•	Recall
	•	F1-Score

This helps assess mBERT’s cross-lingual understanding and intent detection capability.


## Dependencies

The project uses the following libraries:
	•	transformers
	•	torch
	•	scikit-learn
	•	pandas
	•	numpy
	•	matplotlib

Full list in: requirements.txt


## Contributors
- **Abhishek Gupta** – abhishekgup1@iisc.ac.in  
- **Bharat Karthi R K** – barathkarth1@iisc.ac.in  
- **Gayathri Ramasubramanian** – rgayathri@iisc.ac.in  
- **Harikrishnan C** – charikrishna@iisc.ac.in  
- **Inderjit Singh Chauhan** – inderjits@iisc.ac.in  
- **Monika Tyagi** – monikatyagi@iisc.ac.in



## License

This project is for educational and academic use. For any external or commercial usage, please contact the authors.



## Acknowledgments

Special thanks to:
	•	Hugging Face for the transformers library
	•	BERT multilingual pre-trained models
	•	Jupyter & open-source community

