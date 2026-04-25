# AI-Powered Paraphrasing Tool 🤖

An intelligent text transformation system built with Python and Transformer-based deep learning models. This tool preserves the original meaning of a text while improving clarity and ensuring high originality through structural rewriting.

## 🚀 Key Features
* **Core Engine:** Powered by the `T5-Base` model fine-tuned on the PAWS dataset for high-quality paraphrasing.
* **Semantic Preservation:** Uses BERT-based embeddings (`all-MiniLM-L6-v2`) to ensure context remains unchanged.
* **Originality Check:** Automated ROUGE-L scoring to measure lexical diversity and prevent repetition.
* **Fluency Layer:** Integrated with `LanguageTool` for real-time grammar and spelling correction.
* **GPU Optimized:** Designed for high-speed inference on Google Colab (T4 GPU).

## 🛠️ Technology Stack
* **Language:** Python 3.12
* **Deep Learning:** Hugging Face Transformers, PyTorch
* **Evaluation:** Scikit-Learn, Rouge-Score
* **Grammar & NLP:** LanguageTool, Sentence-Transformers

## 📊 Performance Evaluation
The tool has been evaluated against multiple test cases to ensure it meets academic and professional standards for accuracy and originality.

| Metric | Target Range | Result (Avg) |
| :--- | :--- | :--- |
| **Semantic Similarity** | > 0.85 | **0.95** |
| **ROUGE-L (Originality)** | 0.4 - 0.7 | **0.62** |
| **Grammar Pass Rate** | 100% | **98%+** |

### Visualization
The chart below shows the "Sweet Spot" achieved by the tool: High semantic similarity (Accuracy) with controlled overlap (Originality).

![Performance Metrics](image_4da43a.png)

## 📋 Installation & Usage

### Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/ai-paraphraser.git](https://github.com/your-username/ai-paraphraser.git)
   cd ai-paraphraser


