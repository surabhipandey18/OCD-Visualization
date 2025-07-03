# 🧠 OCD Patient Demographic and Clinical Data Analysis

This project explores static visualizations from a dataset of patients diagnosed with Obsessive-Compulsive Disorder (OCD). The aim is to uncover patterns in demographics, clinical profiles, and psychiatric comorbidities using descriptive statistics and classic Python plotting libraries.

---

## 🗃️ Dataset Columns

The dataset contains the following fields:

- `Patient ID`
- `Age`
- `Gender`
- `Ethnicity`
- `Marital Status`
- `Education Level`
- `OCD Diagnosis Date`
- `Duration of Symptoms (months)`
- `Previous Diagnoses`
- `Family History of OCD`
- `Obsession Type`
- `Compulsion Type`
- `Y-BOCS Score (Obsessions)`
- `Y-BOCS Score (Compulsions)`
- `Depression Diagnosis`
- `Anxiety Diagnosis`
- `Medications`

---

## 📊 Visualizations Created

- **Demographic Distributions**
  - Age histogram
  - Gender and Ethnicity bar charts
  - Marital and Education status breakdowns

- **Clinical Features**
  - Symptom duration histograms
  - Obsession & compulsion type frequency plots
  - Y-BOCS score distributions (Obsessions and Compulsions)

- **Psychiatric Comorbidities**
  - Depression and anxiety diagnosis frequencies
  - Combinations of previous diagnoses (if applicable)

---

## 🌐 Y-BOCS Self-Assessment Website

To complement the clinical data analysis, a standalone HTML-based **Y-BOCS Self-Assessment Tool** has been developed.

🔹 **Purpose:**  
The site allows individuals to self-report and calculate their OCD severity using the Yale–Brown Obsessive Compulsive Scale (Y-BOCS). It is for educational purposes only and does not replace professional diagnosis.

🔹 **Features:**
- Clinical-style landing page with call-to-action
- 10-question Y-BOCS form (obsessions + compulsions)
- Explanatory help text for each question
- Result shown with severity level
- Recent scores stored locally in browser
- “Consult a Doctor” CTA and disclaimer
- Responsive design (mobile-friendly)

🔹 **Tech Stack:**  
Pure HTML + CSS + JavaScript (no frameworks). Fully client-side, privacy-friendly.

You can open https://ocd-visualization.vercel.app/ in any browser.

---

## 🧰 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

This project focuses on local, private analysis for learning and insight generation.


## 🔍 Goal

To better understand how OCD presents across different patient profiles and how it coexists with other psychiatric factors using clean, interpretable visualizations.

---
