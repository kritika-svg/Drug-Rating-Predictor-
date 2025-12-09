# 📘 Drugs, Side Effects & Medical Conditions — Analytics Report

A data analytics project exploring **2,931 drug entries** from *Drugs.com* using **Python, Pandas, NumPy, and Scikit-Learn**.  
Includes full data cleaning, EDA, feature engineering, and safety analysis.

---

## 🔍 Overview

The dataset contains:

- Drug info (name, generic, class)
- Medical conditions
- Side effects (text)
- Ratings & reviews
- Pregnancy category & CSA schedule
- Alcohol interaction

**Final dataset after cleaning: 0 missing values**

---

## 🧹 Data Cleaning Highlights

- Filled missing text with `"Unknown"`
- Converted numeric fields to proper types
- Normalized activity values (0–1 scale)
- Encoded alcohol interaction & pregnancy category
- Removed inconsistent columns
- Label-encoded all categorical fields

---

## 📊 Key EDA Findings

- **Top conditions:** Pain, Flu, Acne, Hypertension  
- **Common side effects:** Hives, difficulty breathing, itching  
- **Dominant drug classes:** Respiratory, dermatology, antihistamines  
- **Safety:** 1,500+ drugs show alcohol interaction; Category X/D frequent in critical drug classes  

---

## 🧠 Feature Engineering

- Label Encoding  
- StandardScaler  
- Boolean flags for major side effects & drug classes  
- Parsed text into structured features  
- Exported cleaned dataset for ML pipelines  

**Suitable for:**  
Classification, Clustering, Recommendation Systems, Association Rule Mining

---

## 📝 Insights

- More user reviews → higher ratings  
- Allergic reactions dominate reported side effects  
- Respiratory & skin treatments are the most common drug categories  
- High-risk safety categories spread across many therapeutic classes  

---

## 🏁 Conclusion

A fully cleaned, transformed, and **ML-ready pharmaceutical dataset**, enabling:  
✔ Healthcare analytics  
✔ Drug safety analysis  
✔ Predictive modeling  
✔ Clinical decision support  

---
