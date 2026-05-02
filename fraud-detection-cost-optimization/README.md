# Fraud Detection & Cost Optimization

## Business Problem

Insurance companies must decide which claims to investigate for fraud. Investigating too many claims increases operational costs, while missing fraudulent claims leads to significant financial loss.

The goal of this project is to evaluate predictive models and optimize investigation thresholds to minimize total cost.

---

## Approach

- Evaluated claim severity models using cross-validated MAE  
- Assessed model uncertainty using confidence intervals  
- Derived decision thresholds based on cost trade-offs  
- Simulated outcomes across thresholds using real claim data  

---

## Key Results

- Selected best-performing model based on cross-validation and confidence intervals  
- Derived a **10% investigation threshold** using cost assumptions  
- Identified a **5% optimal threshold** using real outcomes  
- Reduced cost by approximately **$23.5K per 1,000 claims**

---

## 📂 Project Deliverables
This project includes a technical memo, presentation slides, and supporting analysis:

- 📊 [Technical Memo](./technical%20memo.pdf)
- 📈 [Model Evaluation Slides](./Should%20We%20Upgrade%20Our%20Claim%20Severity%20Model%20A%20Data-Driven%20Evaluation.pptx)
- 🔍 [Fraud Investigation Slides](./Should%20We%20Investigate%20This%20Claim.pptx)
- 📄 [Full Analysis Report](./Fraud%20detection%20cost%20optimization.pdf)

---

## Tools

- R (tidyverse, ggplot2)  
- Statistical Modeling  
- Decision Analysis  
- Quarto  

---

More details available in the project files.
