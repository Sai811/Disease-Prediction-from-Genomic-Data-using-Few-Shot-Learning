🧬 Disease Prediction from Genomic Data using Few-Shot Learning

This project explores the use of few-shot learning to predict diseases based on genomic sequences, addressing the challenge of limited labeled data in bioinformatics. By applying models like Prototypical Networks and Siamese Networks, we enable disease classification with high accuracy using only a few training examples per class.

📊 Dataset

The dataset (Genomicdata2.csv) consists of DNA sequences labeled by disease class. Each row represents a DNA sequence encoded using k-mer frequency features, transforming raw nucleotide sequences into a numerical format suitable for machine learning.
	•	Samples: ~1000 DNA sequences
	•	Features: k-mer frequency vectors (length depends on k value used)
	•	Classes: Multiple disease categories
	•	Preprocessing: Includes cleaning, encoding (k-mers), and normalization

🤖 Model Overview
	•	Few-Shot Learning Framework: Designed for N-way K-shot classification
	•	Models Implemented:
	•	Prototypical Networks
	•	Siamese Networks
	•	Loss Functions: Contrastive loss, prototypical loss
	•	Training: Meta-learning strategy using episodic training

📈 Results
	•	Evaluated using accuracy, precision, recall, and F1-score
	•	Visualizations include confusion matrices and embedding plots
	•	Demonstrates robust generalization with limited training data

🛠 Tech Stack
	•	Python (NumPy, Pandas, scikit-learn)
	•	PyTorch / TensorFlow (for model training)
	•	Jupyter Notebook (code and visualization)

🎯 Applications
	•	Personalized medicine
	•	Rare disease detection
	•	Genomic diagnostics
