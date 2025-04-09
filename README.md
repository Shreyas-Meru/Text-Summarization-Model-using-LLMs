# 🧠 Text Summarization Model using LLMs

This repository contains a Jupyter Notebook implementation of a **Text Summarization Model** using Large Language Models (LLMs). The project demonstrates how to leverage the capabilities of transformer-based language models to generate concise and informative summaries from long texts.

## 🚀 Features

- Extractive & abstractive summarization
- Integration with Hugging Face Transformers
- Summarization using pre-trained model `t5-base`
- Simple and readable code in a single Jupyter Notebook
- Custom text input for interactive testing

## 📁 File

- `Text_Summarization_Model_using_LLMs.ipynb`: Main notebook demonstrating the full workflow from loading a model to summarizing input text.

## 🛠️ Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/Shreyas-Meru/Text-Summarization-Model-using-LLMs.git
   cd Text-Summarization-Model-using-LLMs
   ```

2. Install dependencies:
   ```bash
   pip install transformers
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Text_Summarization_Model_using_LLMs.ipynb
   ```

## 💡 Working

The model uses Hugging Face’s `transformers` library to load pre-trained LLMs for summarizing long texts.

### 🔤 Example

**Input Text:**
```
The rapid advancement of artificial intelligence has sparked both excitement and concern among experts, as it promises to revolutionize industries while raising ethical and societal questions.
```

**Generated Summary (Abstractive):**
```
Summary: the rapid advancement of artificial intelligence has sparked both excitement and concern among experts. artificial intelligence promises to revolutionize industries.
```

You can modify the input text within the notebook and see live results.

## 🔗 Reference

This project was inspired by the tutorial published on *The Clever Programmer* blog:  
👉 [Text Summarization Model using LLMs – The Clever Programmer](https://thecleverprogrammer.com/2024/10/07/text-summarization-model-using-llms/)
