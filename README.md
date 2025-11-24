
---
	
#  Key Features in the Dataset

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

#  Modeling Approach

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

#  Getting Started

### Clone the repository:
```bash
git clone (https://github.com/ompatel3457-cell/global-aging-analysis.git)
cd global-aging-analysis
