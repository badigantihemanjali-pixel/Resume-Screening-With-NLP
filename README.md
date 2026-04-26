
A machine learning and NLP-based project that automates the **resume screening** process by matching resumes with job descriptions and ranking them based on similarity.  
This project uses **TF-IDF**, **ML models**, and **BERT embeddings** to evaluate the relevance of resumes for given job descriptions.

---

## 🚀 Features
- Preprocess resumes and job descriptions using **NLP techniques**.  
- Extract features using **TF-IDF** and **BERT embeddings**.  
- Train multiple machine learning models (**Logistic Regression, Random Forest, XGBoost, LightGBM, Gradient Boosting**) for classification.  
- Compare model performance and select the best-performing model.  
- Visualize evaluation metrics (accuracy, F1-score, confusion matrix).  
- Rank resumes based on their relevance to the given job description.  

---

## 📂 Project Workflow
### Step 1 – Data Collection  
Upload datasets:
- `resume_job_matching_dataset.csv` (Resumes + Job Descriptions).  
- Pre-trained BERT embeddings (if using transformer-based models).  

### Step 2 – Data Preprocessing  
- Tokenization, stopword removal, lemmatization.  
- Text normalization (lowercasing, punctuation removal).  

### Step 3 – Feature Extraction  
- **TF-IDF vectorization** for classical ML models.  
- **BERT embeddings** for semantic understanding.  

### Step 4 – Model Training  
- Logistic Regression  
- Random Forest  
- XGBoost  
- LightGBM  
- Gradient Boosting  

### Step 5 – Model Evaluation  
- Compare models using accuracy, F1-score, precision, recall.  
- Select the **best model** for prediction.  

### Step 6 – Resume Ranking  
- Predict scores for resumes against a given job description.  
- Rank resumes by predicted relevance.  

### Step 7 – Visualization  
- Accuracy comparison graph for all models.  
- Confusion matrix for the best model.  

### Step 8 – Final Deployment
- Deploy as a **Streamlit Web App** or on **Hugging Face Spaces**.  

---

## ⚙️ Installation & Setup

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>

2. Install dependencies:
   pip install -r requirements.txt

3. Run in Jupyter Notebook or Google Colab.

---

🔮 Future Improvements

Integrate deep learning models (BERT, RoBERTa, DistilBERT).

Build a Streamlit app for interactive resume uploads.

Deploy model as a REST API with FastAPI/Docker.

Improve ranking algorithm with semantic similarity scoring.   

---

## 👨‍💻 Author

Developed by **Badiganti  Hemanjali**

GitHub: https://github.com/badigantihemanjali-pixel

LinkedIn: https://www.linkedin.com/in/hemanjali-badiganti-0a3bb3266
