
# 📄 Multi-Document-Summarizer-using-Transfer-Learning

Welcome to the **Multi-Document-Summarizer-using-Transfer-Learning** project! This repository contains an implementation of a generative model using transfer learning to summarize multiple documents. The summarizer is based on the `t5-small` model from Hugging Face's Transformers library.

## 📖 Introduction

Summarizing multiple documents into a concise and coherent summary is a challenging task, especially with the vast amount of information available today. This project leverages transfer learning with the T5 model to efficiently summarize multiple documents, making it easier to extract key information.

## ✨ Features

- **Generative Model**: Utilizes the `t5-small` model to generate summaries.
- **Transfer Learning**: Fine-tunes the model on the `multi_news` dataset for better summarization performance.
- **Efficient Summarization**: Capable of processing and summarizing multiple documents in a single run.

## 🧠 Model and Dataset

- **Model**: `t5-small` from Hugging Face's Transformers library, fine-tuned for summarization tasks.
- **Dataset**: The model is trained and evaluated on the `multi_news` dataset, which contains news articles and their summaries.

## 🛠️ Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yajasarora/Multi-Document-Summarizer-using-Transfer-Learning.git
   cd Multi-Document-Summarizer-using-Transfer-Learning
   ```

2. **Install the required dependencies**:
   Ensure you have Python 3.x installed. Then, install the necessary packages:
   ```bash
   pip install datasets transformers accelerate
   ```

3. **Run the Jupyter Notebook**:
   Open the Jupyter Notebook `main.ipynb` to explore the summarization process:
   ```bash
   jupyter notebook main.ipynb
   ```

## 🚀 Usage

- **Load Dataset**: The project uses the `multi_news` dataset. It is automatically loaded and split into training and testing sets.
- **Tokenization**: The documents are tokenized using the `AutoTokenizer` from the T5 model.
- **Training**: The model is fine-tuned using the `Seq2SeqTrainer` for efficient summarization.
- **Summarization**: After training, the model can summarize multiple documents, providing concise and coherent summaries.

## 📈 Results

The project outputs summaries for the input documents, which can be further evaluated for coherence and relevance. Training and evaluation results are stored in the `./results` directory.

## 🤝 Contributions

Contributions to this project are welcome! If you have ideas for improving the model or adding new features, feel free to fork the repository and submit a pull request.

## 📬 Contact

For any questions or feedback, feel free to reach out via GitHub Issues or contact me directly.

---

Transform how you process information with our Multi-Document-Summarizer-using-Transfer-Learning! 📄
