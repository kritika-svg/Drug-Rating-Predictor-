📘 Drugs, Side Effects & Medical Conditions — Analytics Report

A data analytics project exploring 2,931 drug entries from Drugs.com using Python, Pandas, NumPy, and Scikit-Learn.
Includes full cleaning, EDA, feature engineering, and safety analysis.

🔍 Overview

The dataset contains:

Drug info (name, generic, class)

Medical conditions

Side effects (text)

Ratings & reviews

Pregnancy category, CSA schedule

Alcohol interaction

Final dataset after cleaning: 0 missing values

🧹 Data Cleaning Highlights

Filled missing text with "Unknown"

Converted numeric fields

Normalized activity values (0–1 scale)

Encoded alcohol interaction, pregnancy category

Removed inconsistent columns

Label-encoded all categories

📊 Key EDA Findings

Top conditions: Pain, Flu, Acne, Hypertension

Common side effects: Hives, difficulty breathing, itching

Dominant drug classes: Respiratory, dermatology, antihistamines

Safety: 1,500+ drugs show alcohol interaction; Category X/D common in critical treatments

🧠 Feature Engineering

Label Encoding

StandardScaler

Boolean flags for major side effects & classes

Cleaned structured dataset exported for ML

Suitable for: Classification, Clustering, Recommendations, Rule Mining.

📝 Insights

More reviews → higher ratings

Allergic reactions dominate side effects

Respiratory & skin treatments most common

High-risk drugs spread across many classes

🏁 Conclusion

A fully cleaned, transformed, and ML-ready pharmaceutical dataset enabling healthcare insights, safety analysis, and predictive modeling.
