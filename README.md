# DS3100 Final Project Guide

📅 **Due Date:** Tuesday, April 29, 2025 at 5:00pm

---

## 📌 Overview

In this comprehensive end-of-semester project, you'll collaborate in groups to apply your data science skills and communicate findings to a technical audience. You'll choose a topic and dataset, conduct a regression-based analysis, and present your insights in a short PDF or HTML report generated from an RMarkdown script.

Your report should include:

- Introduction
- Data overview
- Exploratory analysis results
- Key insights
- Implications or recommendations
- A short paragraph explaining each member’s contributions

---

## 🧠 General Guidance

- **Long ≠ better** – Be informative but concise.
- **Keep it clean** – Show only relevant output (skip `head()`, `str()`, or `summary()`).
- **Make it readable** – Ensure figures are appropriately sized and everything fits on the page.
- **Collaborate effectively** – Divide and conquer, but document who did what.
- **Ask for help** – Consult instructors/TAs if needed.

---

## 🔄 Workflow

### 1. Group Formation & Topic Selection

- Groups are assigned randomly.
- Pick a topic relevant to the course and interesting to your group.
- Choose one or more relevant datasets (merging is optional).

### 2. Select a Dataset

- Avoid using the same dataset from previous assignments.
- The dataset should require cleaning and transformation.
- Ensure it's suitable for:
  - Linear/logistic regression
  - Training-testing, cross-validation, or bootstrapping
  - PCA, clustering, network analysis, or text analysis

---

## 📄 Report Content

### ✅ Discuss the Data

- Where did the dataset come from?
- What was its original purpose?
- What's your purpose for using it?

### ✅ Consider Variables of Interest

- Only analyze relevant variables
- Preserve the original dataset by storing cleaned versions in new objects
- Describe variable types (binary, continuous, filter, score-related)

### ✅ Develop a Research Question

- You may have multiple questions
- Use course methods to guide your inquiry

### ✅ Wrangle the Data

- Transform and format as needed (wide/long, standardize, categorize)
- Keep data tidy
- Perform wrangling throughout the analysis process

### ✅ Visualize by Outcome

- **Binary outcome**: Bar charts, box plots
- **Continuous outcome**: Scatterplots, density plots

### ✅ Model the Data

- Choose suitable regression models
- Check assumptions
- Try alternative models or control variable sets
- Evaluate generalizability (split/cross-validation/bootstrapping)
- Interpret results (effect sizes, R², RMSE, etc.)

### ✅ Discuss Findings

- Summarize all results
- Relate back to research questions
- Note limitations:
  - Sample size
  - Sampling method
- Suggest future directions

---

## ✅ Final Checklist

Make sure your submission includes:

1. **✔️ 25+ lines** of code cleaning and wrangling the data
2. **✔️ 5+ descriptive** visualizations/tables
3. **✔️ Dataset inspection** and quality description
4. **✔️ 3+ regression models** with interpretation and assumptions checked
5. **✔️ 2+ advanced methods** (e.g., generalizability, PCA, clustering, networks, or text)
6. **✔️ A single**:
   - Code script
   - PDF or HTML report
   - All relevant datasets

> 🔁 Every student must upload the same content to Brightspace for grading.

---


