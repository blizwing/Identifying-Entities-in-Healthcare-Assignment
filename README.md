# Identifying Entities in Healthcare Data

This project focuses on Named Entity Recognition (NER) in healthcare data using syntactic processing techniques with SpaCy. The dataset consists of tokenized sentences with medical terms, and the goal is to preprocess the data and apply NLP models to identify and label relevant entities.

## 🚀 Project Objectives

- Parse healthcare-related text data.
- Preprocess tokenized sentences where each word appears on a new line.
- Restore original sentence structure from raw input format.
- Apply SpaCy-based Named Entity Recognition (NER).
- Evaluate and visualize NER outputs.

## 🔧 Tools & Libraries

- Python
- SpaCy
- Pandas
- Matplotlib
- Seaborn

## 📁 Dataset Format

The input data is structured as:
- One word per line for each sentence.
- Empty lines separating two sentences.
- Labels follow the same token-per-line format.

Example:
```
Patient
was
given
aspirin

Medication
was
prescribed
```
## 🔄 Steps Performed

1. **Environment Setup**: Installed and imported necessary NLP libraries and models.
2. **Data Preprocessing**: Parsed line-wise token format and reconstructed sentence-level data.
3. **NER Model Loading**: Loaded a SpaCy model and disabled unnecessary pipeline components to improve performance.
4. **Entity Recognition**: Applied NER to extract medical entities.
5. **Evaluation**: Visualized and validated model output.

## 📊 Results

The model successfully identified common healthcare entities such as diseases, medications, and procedures from tokenized input data. Results were visualized for analysis.

## 🧠 Future Improvements

- Train a domain-specific NER model with custom annotations.
- Incorporate contextual embeddings (e.g., BERT-based models).
- Extend support for multilingual medical records.

## 📌 Author

Pratham Mhatre

---

