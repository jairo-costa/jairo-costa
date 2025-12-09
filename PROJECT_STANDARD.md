# 🧭 Project Standard — Jairo Costa (ML/AI Portfolio)
### Version 1.0 — Established After Project 06

This document defines the official methodology, structure, and communication standards for all ML/AI projects developed in my portfolio.  
It ensures consistency, clarity, and professional-level documentation across every repository.

---

# 1. Corporate Email (Project Brief from Manager)

Each project starts with a corporate-style email from my simulated manager, Mariana.

### Required structure:
- Clear subject  
- Business context  
- Motivation for the project  
- Minimum technical scope  
- Expected deliverables (EDA, baselines, models, metrics, visuals)  
- Interpretation requirements  
- Professional signature  

**Purpose:** simulate realistic business scenarios and expectations.

---

# 2. Internal Message (Repository Kickoff)

A structured message opening the project inside the GitHub Chat:

### Must include:
- Official project name  
- Objective  
- Business summary  
- Repository structure  
- Workflow (study notebook → mentored reasoning → final notebook)  
- File organization rules  

---

# 3. Official Repository Structure

All projects must follow this exact folder layout:

project-xx-name/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── study-version.ipynb
│ └── final-version.ipynb
│
├── src/ # optional
│
├── README.md
├── requirements.txt


### Rules:
- Only processed data goes into `data/processed/`.
- Study and final notebooks are always separated.
- `src/` is optional and used only when modularization makes sense.

---

# 4. README Structure (Standard)

Every project README must contain:

1. **Overview**  
2. **Context & Problem Definition**  
3. **PPI — Preliminary Problem Identification**  
4. **Dataset Description**  
5. **Methodology**  
6. **Repository Structure**  
7. **Models Tested**  
8. **Results**  
9. **Business Interpretation**  
10. **Next Steps**

### README must be written in English.

---

# 5. Study Notebook (study-version.ipynb)

A pedagogical notebook that documents the full reasoning process.

### Contains:
- Header  
- PPI  
- Imports  
- Dataset loading  
- Full EDA  
- Feature engineering  
- Exploratory tests  
- Debugging, corrections, hypotheses  
- Explanations in PT/EN  
- Human thinking, mistakes, restarts, insights  

**This notebook is intentionally imperfect — it documents learning.**

---

# 6. Guided Mentorship Stage (Core of the Method)

Before implementing models, a set of conceptual questions must be answered:

### Examples:
- *What do you expect the model to struggle with, and why?*  
- *If you remove lags, what real-world behavior disappears?*  
- *What does a jagged time-series plot imply about trend vs. seasonality?*  
- *Which features matter and why?*  
- *Which baseline is appropriate for this problem?*  

**Purpose:**  
Develop reasoning before code, reinforce ML intuition, and simulate senior oversight.

---

# 7. Final Notebook (final-version.ipynb)

Produced only after study + mentorship.

### Requirements:
- Clean  
- Structured  
- Professional  
- English only  
- No failed attempts  
- Only final decisions  
- Clear business-oriented interpretation  

---

# 8. Publication Workflow (LinkedIn)

Each project generates up to four posts:

### Monday — Kickoff  
Corporate email + context.

### Wednesday — Process & Mentorship  
Debugging, failures, reasoning, insights.

### Thursday — Lessons Learned  
Short reflections, technical maturity.

### Friday — Final Delivery  
Models, metrics, plots, repo link.

### Sunday — Sidequest (optional)  
Personal reflections, meta-learning.

---

# 9. Technical Identity (Jairo’s Signature)

All projects must express:

- Structured reasoning  
- Strong documentation  
- Analytical clarity  
- Business understanding  
- Clean repos  
- Professional storytelling  
- Simulation of real corporate environments  
- Growth mindset with transparent mistakes  

---

# 10. Startup Prompt for Every New Project

Every new chat must start with:

> **“This is my official Project Standard (Version 1.0). Use this standard in every step of Project 07 (and future projects): corporate email → internal message → repo structure → README → study notebook → mentorship → final notebook.”**

This guarantees continuity and prevents divergence from the methodology.

---

**End of Version 1.0**
