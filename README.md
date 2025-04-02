# 🧪 AI-Based Drug Toxicity Prediction Using Tox21 Dataset

This project implements an end-to-end machine learning pipeline for **drug toxicity prediction** using the **Tox21 dataset**. The workflow leverages cheminformatics tools like **RDKit**, machine learning via **scikit-learn**, and deep learning utilities from **DeepChem** to process molecular SMILES strings and predict toxicity.

## 📁 Dataset

- **Source:** [Tox21 Challenge Dataset](https://tripod.nih.gov/tox21/challenge/)
- **Format:** CSV
- **Fields:** SMILES strings + toxicity labels for various biological targets

---

## 🔬 Key Features

- 🧬 Converts **SMILES** strings to RDKit molecule objects
- 🔍 Extracts **Morgan Fingerprints (ECFP)** for molecular representation
- 🤖 Trains a **Random Forest Classifier** to predict toxicity
- 📈 Evaluates model with accuracy and classification report
- 🧠 Visualizes predicted **toxic vs non-toxic** compounds using pie charts
- 🧪 Displays sample molecule structures with toxicity labels

---

## Example Output
**Accuracy**: e.g., Model Accuracy: 84.65%; 
**Visualization**:
Pie Chart
Top Toxic Compounds:

Molecular Formula	Toxicity Probability
C12H14ClN3O2S - 0.97;
C9H11NO2 - 0.91

## 🧠 Tools & Libraries Used
  **RDKit** – Molecular processing; 
  **DeepChem** – Cheminformatics utilities;
  **scikit-learn** – Machine Learning;
  **Matplotlib** – Visualization;
  **Pandas** – Data Handling;

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/28Srushti/tox21-toxicity-prediction.git
cd tox21-toxicity-prediction


