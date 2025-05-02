# 🧠 Burnout Risk Classifier — Predicting Burnout from Behavioral Patterns

> **Detect burnout before it happens. Predict responsibly.**

This project uses machine learning to build a behavioral-based classifier capable of **detecting early signs of burnout risk** from daily routine data — including sleep hours, workload, screen time, and social interaction.

In an era driven by productivity and hyperconnectivity, building systems that can prevent mental collapse isn't just technical work — it's a human need.

---

## 🚀 Project Highlights

- ✅ **Simulated dataset with realistic behavioral logic**
- 📊 **Exploratory analysis focused on mental health features**
- 🛠️ Missing data imputation guided by visual evidence (`boxplot`, `histplot`)
- ⚖️ **Modeling with a focus on recall**, ideal for preventive screening
- 🧬 **Comparison of class imbalance strategies:**
  - Baseline model
  - `class_weight='balanced'`
  - `SMOTE` (synthetic oversampling)
- 📈 Final comparison table for model performance
- 💡 Priority on **interpretability and sensitivity**

---

## 💡 Why this project matters

Burnout is not a technical bug — it's a silent public health issue.  
A good predictive model shouldn't just optimize accuracy — it should also minimize risk.  
In this project, we deliberately maximize **recall for the minority class (burnout cases)**, accepting a drop in precision.  
Because in mental health, **it's better to raise a false alarm than to miss someone at risk.**

---

## 📁 Project Structure

```bash
burnout-risk-classifier/
├── BurnoutRadar_Notebook.ipynb   # Main notebook with all project steps
├── Burnout_Dataset.csv           # Simulated dataset (with missing values)
├── README.md                     # This file
