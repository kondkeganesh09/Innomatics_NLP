📊 BERT Fine-Tuning for Sentiment Analysis

## 📌 Overview
This project focuses on fine-tuning a pre-trained BERT model for text classification using the IMDB Movie Reviews dataset. The goal is to understand how different fine-tuning strategies affect model performance.
 🎯 Objective
- Learn BERT fine-tuning
- Perform text preprocessing and tokenization
- Train and evaluate a classification model
- Compare different training approaches

🛠️ Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Google Colab

🔄 Workflow
Raw Data → Preprocessing → Tokenization → Model Training → Evaluation → Comparison

⚙️ Experiments

🔹 Experiment 1: Full Fine-Tuning
- Trained all layers of BERT
- Achieved highest performance
🔹 Experiment 2: Freeze All Layers
- Only classifier layer was trained
- Faster training but lower accuracy
🔹 Experiment 3: Fine-Tune Last 2 Layers
- Only last few layers were trained
- Balanced performance and speed

📊 Results

| Experiment | Accuracy | F1 Score |
|-----------|--------|--------|
| Full Fine-Tuning | 83.1% | 83.3% |
| Freeze All Layers | 51.1% | 59.3% |
| Last 2 Layers | 76.7% | 75.3% |

📌 Key Learnings
- Fine-tuning improves model performance significantly
- Freezing layers reduces training time but impacts accuracy
- BERT captures contextual meaning better than traditional methods

🚀 Future Improvements
- Try DistilBERT or RoBERTa
- Use learning rate scheduler
- Apply early stopping

📷 Output
Confusion matrices and evaluation metrics are included in the notebook.
📎 Conclusion
This project helped in understanding how BERT works in real-world NLP tasks and how different training strategies impact results.

---

⭐ If you found this project useful, feel free to star the repository!
