# Automating-Risk-Evaluation
The aim was to build a model capable of classifying AI systems according to the EU AI Act’s risk tiers, while also providing LIME explanations and contextual legal references to support compliance.

## 🔍 Features

- Supports legal document ingestion and risk categorization.
- Uses fine-tuned transformer models for legal text analysis.
- Includes LIME interpretability for model decisions.

## 🛠 Technologies Used

- Python (Jupyter Notebook)
- Google Colab
- Transformers (joelniklaus/legal-xlm-roberta-base)
- LIME for interpretability
- Scikit-learn, Pandas, Numpy
- Google Drive for file access

## 🚀 Getting Started

To run this project, follow the steps below:

### Step 1: Download the Repository

⚠️ **Note for GitHub Users**

If GitHub shows an "Invalid Notebook" error, don't worry — this does **not** affect functionality in Google Colab. The issue is caused by widget metadata (`metadata.widgets.state`) missing from the notebook file, which can break GitHub rendering but not actual usage.

✅ You can still open and run the notebook perfectly in Google Colab.

### Step 2: Upload to Google Drive

1. Upload the entire folder to your Google Drive.
2. Ensure all .ipynb files and supporting datasets are in one folder.

### Step 3: Open in Google Colab

1. Go to Google Colab.
2. Click on File > Open notebook > Google Drive.
3. Locate the uploaded notebook (e.g., Automate_Risk_Classification.ipynb) and open it.

### Step 4: Run the Notebook

Follow the notebook cells sequentially to load models, preprocess documents, classify risks and interpret results.

## 📁 File Structure

 - Automate_Risk_Classification.ipynb: Main notebook for classification and evaluation.
 - EU_AI_Act_Dataset/: Example legal and company policy documents.
