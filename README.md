# 🎓 Explainable AI for Job Placement Prediction  
### Using CatBoost, SHAP, SMOTE, Scaling, and Advanced ML Techniques

This project builds an **Explainable AI (XAI)** system to predict whether a student will be **placed** or **not placed** based on academic, technical, and employability-related features.  
The model focuses on **interpretability**, helping placement teams understand *why* a prediction was made.

---

# 🧠 **Technologies Used**
- 🐱 **CatBoost Classifier** – handles categorical + numerical data natively  
- 🔍 **SHAP Explainability** – provides human-interpretable AI decisions  
- ⚖️ **SMOTE Oversampling** – solves class imbalance  
- 🔧 **Feature Engineering** – scaling, log-transform, encoding  
- 📊 **Evaluation Tools** – accuracy, confusion matrix  
- 📚 **Python Libraries** – scikit-learn, pandas, numpy, seaborn, matplotlib  
- 🔮 **TabPFN (optional)** – transformer-based probabilistic classifier  

---
# 📁 Dataset Information

The dataset contains **7,225 student records** with **11 features**.

### 📄 Columns in Dataset

| Column | Description |
|--------|-------------|
| **CGPA** | Cumulative Grade Point Average (0–10) |
| **Internships** | Number of internships completed |
| **Projects** | Number of academic/technical projects |
| **Workshops/Certifications** | Number of workshops/certifications completed |
| **AptitudeTestScore** | Aptitude exam score (0–100) |
| **SoftSkillsRating** | Soft skills rating (0–5) |
| **ExtracurricularActivities** | Yes/No participation |
| **PlacementTraining** | Yes/No training program |
| **SSC_Marks** | Class 10 percentage |
| **HSC_Marks** | Class 12 percentage |
| **PlacementStatus** | Target variable → Placed / NotPlaced |

# 🧾 🔟 Results Summary

- CatBoost achieved high accuracy

- SHAP provided full transparency

- SMOTE balanced the training dataset

- Feature engineering improved model stability

- The system predicts student placement with explainability suitable for:

- College placement cells

- HR analytics teams

- Student counselors

- ML explainability case studies
