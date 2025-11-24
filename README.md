
---

# 🔍 Key Features in the Dataset

### **Clinical Features**
- **MMSE** (Mini-Mental State Examination): cognitive function  
- **CDR** (Clinical Dementia Rating): dementia severity  
- **nWBV** (Normalized Whole Brain Volume): MRI measure of brain tissue  
- **eTIV** (Estimated Total Intracranial Volume)  
- **ASF** (Atlas Scaling Factor)  

### **Demographic Features**
- Age  
- Gender  
- Education Level  
- Socioeconomic Status (SES)  

### **Diagnosis Labels**
- CN → Cognitively Normal  
- MCI → Mild Cognitive Impairment  
- AD → Alzheimer’s Disease  

---

# 🧠 Modeling Approach

### **1. Data Preprocessing**
- Handling missing values  
- Encoding categorical variables  
- Standardizing MRI-based features  
- Splitting into train/test sets  

### **2. Feature Engineering**
Possible engineered features:
- Brain-to-Intracranial Ratio  
- MMSE decline (if visit-based data used)  
- Age buckets  

### **3. Model Evaluation Metrics**
- Accuracy  
- ROC-AUC  
- Confusion matrix  
- Precision & Recall (important for AD detection)  

---

# 📊 Example Research Questions

1. **Does brain volume correlate with Alzheimer’s severity (CDR)?**  
2. **At what age does cognitive decline accelerate?**  
3. **Can MRI-based features predict early Alzheimer’s?**  
4. **How does MMSE vary by disease group?**  

---

# 👥 Project Team (Group 7)

- Vishal Sharma — Data Research Lead  
- Harjeet Kaur — Literature & Analysis  
- Om Patel — Data Engineering  
- Kirti Sharma — Visualization & Modeling  
- Krupa Patel — Documentation & Reporting  

---

# 🚀 Getting Started

### Clone the repository:
```bash
git clone https://github.com/<your-username>/global-aging-analysis.git
cd global-aging-analysis
