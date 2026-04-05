🚀 Token Classification using BERT (NER)
 
📌 Overview
This project demonstrates fine-tuning a transformer model for **Token Classification** using BERT.

The model is trained to identify named entities such as:
- 👤 Person (PER)
- 🏢 Organization (ORG)
- 📍 Location (LOC)

## 🧠 Objective
To build a system that assigns labels to each token in a sentence using transformer-based architecture.
## 🛠️ Tech Stack
- Python
- Hugging Face Transformers
- PyTorch
- Datasets Library
- SeqEval
## 📊 Dataset
- WikiANN (NER Dataset)
- Used due to compatibility with latest Hugging Face API

 ⚙️ Pipeline
Raw Text → Tokenization → Label Alignment → Model Training → Evaluation → Inference

 🔥 Model Used
- BERT (bert-base-uncased)

📈 Evaluation Metrics
- Precision
- Recall
- F1 Score

🧪 Sample Output

Input:
Elon Musk founded Tesla in California

Output:
| Word        | Entity Type | Confidence |
|------------|------------|-----------|
| Elon        | Person (PER) | 0.95 |
| Musk        | Person (PER) | 0.96 |
| Tesla       | Organization (ORG) | 0.99 |
| California  | Location (LOC) | 0.98 |
-
⚠️ Challenges Faced
- Token-label alignment with subwords
- Dataset compatibility issues (deprecated datasets)
- Debugging static vs dynamic outputs
- Balancing training time and accuracy

💡 Key Learnings
- How BERT performs token classification
- Handling real-world NLP issues
- Importance of data size and epochs
- Debugging ML pipelines

🚀 Future Improvements
- Deploy using FastAPI / Streamlit


## 👨‍💻 Author
Ganesh
