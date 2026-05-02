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
This project includes a full set of business and technical deliverables:

- 📊 **Technical Memo**  
  Concise summary of modeling approach, evaluation, and business recommendations  
  👉 [View PDF](./technical%20memo.pdf)

- 📈 **Model Evaluation Slides**  
  Compares model performance, error behavior, and selection rationale  
  👉 [Download Slides](./Should%20We%20Upgrade%20Our%20Claim%20Severity%20Model%20A%20Data-Driven%20Evaluation.pptx)

- 🔍 **Fraud Investigation Slides**  
  Demonstrates how model outputs translate into real investigation decisions  
  👉 [Download Slides](./Should%20We%20Investigate%20This%20Claim.pptx)

- 📉 **Threshold Optimization Slides**  
  Shows cost trade-offs and how the optimal fraud threshold was selected  
  👉 [Download Slides](./Are%20We%20Using%20the%20Right%20Fraud%20Threshold.pptx)

- 📄 **Full Analysis Report / Code Output**  
  Detailed analysis, modeling workflow, and results documentation  
  👉 [View PDF](./Fraud%20detection%20cost%20optimization%20code.pdf)
---

## Tools

- R (tidyverse, ggplot2)  
- Statistical Modeling  
- Decision Analysis  
- Quarto  

---

More details available in the project files.
