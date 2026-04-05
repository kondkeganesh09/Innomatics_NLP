🧠 NLP Token Classification using BERT
POS Tagging & Chunking

This project demonstrates fine-tuning a transformer model using BERT (bert-base-uncased) for token classification tasks, including:
Part-of-Speech (POS) Tagging
Chunking (Phrase Detection)

The implementation is built using Hugging Face Transformers and PyTorch, focusing on real-world NLP pipeline design.

📌 Project Overview

Token classification assigns a label to each word in a sentence.

🔹 POS Tagging

Identifies grammatical roles:

NNP → Proper Noun
VBD → Verb (Past Tense)
IN → Preposition
🔹 Chunking

Identifies phrase structure:

B-NP → Beginning of Noun Phrase
I-NP → Inside Noun Phrase
B-VP → Verb Phrase
B-PP → Prepositional Phrase
⚙️ Tech Stack
Python
Hugging Face Transformers
PyTorch
Datasets Library
🔄 Pipeline

Raw Text → Tokenization → Label Alignment → BERT Model → Training → Evaluation → Inference

🧪 Model Details
Model: bert-base-uncased
Task: Token Classification
Dataset: CoNLL-style dataset
Training Epochs: 3
Evaluation Metric: Accuracy

📊 Results
Achieved ~97% accuracy on POS tagging
Model learned meaningful token-level patterns
Minor errors observed due to contextual limitations

🔍 Sample Output
Input
Elon Musk founded Tesla in California

POS Output

Elon → NNP
Musk → NNP
founded → VBD
Tesla → NNP
in → IN
California → NNP

Chunking Output

Elon → B-NP
Musk → I-NP
founded → B-VP
Tesla → B-NP
in → B-PP
California → B-NP

⚠️ Challenges Faced
Dataset loading issues due to updated libraries
Handling subword tokenization in BERT
Label alignment for token classification
Debugging inconsistent inference outputs

💡 Key Learnings
Importance of preprocessing in NLP pipelines
How transformer models handle sequence labeling
Real-world implementation of token classification
Evaluation and debugging of ML models

🙌 Acknowledgement

This project was completed as part of my learning journey with Innomatics Research Labs.

👨‍💻 Author
Ganesh
