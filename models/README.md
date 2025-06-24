## 🧠 Model Checkpoints

You can find the final fine-tuned multilingual intent classification model in our Hugging Face repository:

👉 **[Hugging Face – Model Checkpoints](https://huggingface.co/spaces/charikri/IntentBert/tree/main/model)**

This directory contains:
- Final fine-tuned model weights
- Tokenizer configuration
- Model configuration files (`config.json`, `pytorch_model.bin`, `tokenizer_config.json`, etc.)

These can be used to:
- Load the model for inference
- Reproduce results
- Deploy via Hugging Face Spaces or any API

To load the model in Python using 🤗 Transformers:

```python
from transformers import AutoModelForSequenceClassification, AutoTokenizer

model = AutoModelForSequenceClassification.from_pretrained("charikri/IntentBert")
tokenizer = AutoTokenizer.from_pretrained("charikri/IntentBert")