# 🚀 20-Minute AI: Fast NLP with Hugging Face

A streamlined Python implementation for high-impact NLP tasks. This project demonstrates how to deploy **Sentiment Analysis**, **Text Summarization**, and **Named Entity Recognition (NER)** using Hugging Face Transformers Pipelines.

![](img/Gemini_Generated_Image_q8iai9q8iai9q8ia.png)

## 🌟 Features
- **Plug-and-Play:** Uses `pipeline` abstractions for SOTA performance with zero configuration.
- **Multi-Task:** Three core NLP solutions in a single script.
- **Lightweight:** Designed to run on standard hardware without requiring heavy GPU clusters.

## 🛠️ Installation

Clone the repo and install the dependencies:

```bash
git clone [https://github.com/your-username/20-minute-ai.git](https://github.com/your-username/20-minute-ai.git)
cd 20-minute-ai
pip install transformers torch pandas
```

## 🚀 Quick Start

Run the core script to see the three NLP tasks in action:

```python
from transformers import pipeline

# 1. Sentiment Analysis
sentiment = pipeline("sentiment-analysis")
print(sentiment("This project is incredibly easy to set up!"))

# 2. Summarization
summarizer = pipeline("summarization")
print(summarizer("Your long text here...", max_length=50))

# 3. Named Entity Recognition
ner = pipeline("ner", aggregation_strategy="simple")
print(ner("Google is headquartered in Mountain View, California."))
```

## 📚 References

[Hugging Face Transformers Documentation](https://huggingface.co/learn/llm-course/chapter1/3)

## 📝 License

MIT





