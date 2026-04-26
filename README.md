# STA 631 Portfolio – Cliff S. K. Mutegi

**Course:** Statistical Modeling I (Winter 2026)  
**Instructor:** Dr. John Appiah-Kubi  
**Student:** Cliff S. K. Mutegi (G02486017)  
**Final Portfolio Submission**

---

## Purpose of This Portfolio

This repository contains a comprehensive, professional response to the constructive feedback received on my group project. After carefully reviewing Dr. Appiah-Kubi’s comments, I made substantial revisions that demonstrate:

- Deeper understanding of model selection and justification
- Rigorous diagnostic checking (including assumption testing for LDA/QDA)
- Stronger, more policy-relevant interpretation of results
- Transparent responsiveness to feedback

This enhanced portfolio demonstrates the full scope of work completed for STA 631 and my commitment to rigorous statistical practice.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Classification_project_revised.Rmd` | Complete revised group project with all requested improvements |
| `Classification_project_revised.pdf` | Polished PDF of the revised project |
| `demonstration_code.Rmd` | Full R Markdown demonstrating all five required model types |
| `demonstration_code.html` | Knitted HTML version of the demonstration code |
| `Reflection_Document_Cliff_Mutegi.pdf` | Detailed reflection with five “Show and Tell” entries |
| `Self_Evaluation_Letter_Cliff_Mutegi.pdf` | Cover-letter format self-evaluation |
| `index.html` | Professional portfolio website (view at GitHub Pages) |

---

## How Feedback Was Addressed

### 1. Binary outcome was “somewhat blunt”
**Solution:** Added new subsection 2.1.1 with clear justification (small cell size in “D_or_lower”) + multinomial logistic sensitivity analysis. Predictor rankings remained consistent, validating the binary approach while acknowledging its limitations.

### 2. Limited depth on model selection & justification
**Solution:** Created dedicated section 3.3 “Model Selection Rationale” explaining why logistic, lasso, LDA, and QDA were deliberately chosen and how they complement one another.

### 3. Limited deeper checking (LDA/QDA assumptions, robust validation)
**Solution:** Added subsection 4.3.1 containing:
- Box’s M test for equal covariance assumption
- Q-Q plots of linear discriminants
- Repeated 5-fold CV (5 repeats) showing <1.2% accuracy variation
- Calibration curves for logistic and lasso models

### 4. Lasso justification was thin
**Solution:** Expanded discussion to emphasize:
- Stability across CV folds (>90% of folds retained core predictors)
- Automatic shrinkage of correlated survey items
- Superior policy interpretability for school administrators and parents

---

## Key Metrics from Revised Project

- **Best Model:** Lasso Logistic Regression (88.6% accuracy, 0.812 ROC-AUC)
- **Strongest Predictors:** Volunteering at school, attending general meetings, female sex, graduate parental education
- **Class Imbalance Handled:** Stratified sampling + ROC-AUC tuning + repeated CV
- **New Diagnostics Added:** Box’s M test (p < 0.001), repeated CV stability, calibration analysis

---

## Why This Portfolio Deserves Recognition

- **Responsiveness:** Every single point in the feedback was addressed with concrete additions.
- **Statistical Growth:** Moved from basic metrics to proper assumption checking and robustness analysis.
- **Professional Communication:** Clear model justification and stakeholder-relevant interpretation.
- **Iterative Improvement:** Transparent before/after comparison showing genuine development as a data scientist.

---

## How to View the Portfolio Website

The professional website will be available at `https://cliffmutegi.github.io/sta631-portfolio`

---

## Contact

**Cliff S. K. Mutegi**  
mutegic@mail.gvsu.edu  
(616) 264-7075  
Grand Valley State University  
MS Data Science and Analytics Program

---

*Thank you, Dr. Appiah-Kubi, for your detailed and constructive feedback. I hope this revised portfolio demonstrates both my technical growth and my commitment to rigorous, responsible statistical practice.*
