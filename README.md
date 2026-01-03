## Methodology

This project evaluates emotion classification performance across traditional feature-based representations and modern pre-trained language models under a unified experimental framework.

---

### TF-IDF Based Models
TF-IDF representations were used to capture word importance based on term frequency and inverse document frequency. These experiments focus on understanding how sparse, frequency-based features perform on emotion classification tasks.

- Experiments were conducted on both **balanced** and **unbalanced** versions of the dataset
- Highlights the impact of class imbalance on performance
- Serves as a strong traditional baseline for comparison

---

### FastText-Based Models
FastText-based experiments leverage dense word embeddings that capture semantic and subword-level information.

- Implemented on both **balanced** and **unbalanced** datasets
- Captures richer semantic relationships than TF-IDF
- Provides a middle ground between classical feature-based approaches and deep contextual models
- Computationally efficient while improving representation quality

---

### Pre-Trained Deep Learning Models
Transformer-based pre-trained language models were fine-tuned to capture contextual and semantic nuances in emotional text.

**Models used**:
- DistilBERT  
- MobileBERT  

These models utilize contextual embeddings learned from large-scale corpora, enabling improved generalization and deeper understanding of complex emotion expressions in text.

---

