# Text_Summarization
This project implements a **Text Summarization** system that extracts key information from lengthy articles, blogs, and news reports. It includes **extractive summarization** using spaCy and **abstractive summarization** using Hugging Face's transformer models like BERT and GPT. The model is fine-tuned to improve the quality of generated summaries and is evaluated using metrics such as ROUGE scores.
# Dataset:
The project utilizes the **CNN/Daily Mail Dataset**, a large-scale dataset containing news articles and corresponding human-written summaries, commonly used for training and evaluating text summarization models.
## Steps:
- **Extractive Summarization:** Identifies and extracts important sentences from the text using NLP techniques.
- **Abstractive Summarization:** Generates human-like summaries using pre-trained deep learning models.
- **Fine-tuning:** Enhances the performance of pre-trained models for improved summarization quality.
- **Evaluation:** Assesses model performance using ROUGE scores.
# Dependencies:
- spacy==3.8.2
- transformers==4.36.2
- torch==2.1.2
- datasets==2.16.1
- nltk==3.8.1
- rouge-score==0.1.2
- numpy==2.2.1
- pandas==2.2.3
- matplotlib==3.10.0
- joblib==1.4.2
