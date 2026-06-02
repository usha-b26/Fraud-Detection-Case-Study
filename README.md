# Financial Fraud Detection Case Study: Risk Modeling & Cost-Benefit Optimization

An end-to-end data analytics case study evaluating fraudulent financial transactions. This repository demonstrates data cleaning, risk classification, model performance validation using a confusion matrix, and a final business-centric cost-benefit framework to maximize operational savings.

## Project Deliverables
* 📊 **Data Sheets (`/Data`):** Complete processing pipeline from raw transaction logging to baseline stats, category-specific risk modeling, and a financial matrix.
* 🗂️ **Executive Presentation (`/Presentation`):** A high-level deck summarizing technical insights and strategic business recommendations for stakeholders.

---

## Analytical Workflow Breakdown

### 1. Baseline Statistics
Establishes the historical foundation of the transaction pool, isolating the systemic occurrence of fraud (Fraud Rate) to benchmark performance improvements.

### 2. Risk Stratification by Category
Segments transaction flags across different behavioral and merchant categories. This isolates high-variance categories to optimize rules engines for risk detection.

### 3. Model Evaluation (Confusion Matrix)
Quantifies predictive accuracy by mapping model outputs into standard performance segments:
* **True Positives (TP) & True Negatives (TN):** Correctly classified risk.
* **False Positives (FP):** Clear transactions flagged as fraud (causing customer friction).
* **False Negatives (FN):** Missed fraud instances (causing direct financial leakage).

### 4. Cost-Benefit Optimization
Translates statistical model outputs directly into bottom-line fiscal impact. It balances the operational overhead of investigating False Positives against the catastrophic cost of unmitigated False Negatives to locate the optimal financial equilibrium.

---

## Data Schema & Architecture Reference

The data underlying this case study spans across 5 foundational matrices:

| Sheet/File Resource | Focus Area | Key Data Attributes Evaluated |
| :--- | :--- | :--- |
| `1_Raw_Data_&_Calculations` | Primary Processing | Unique Transaction Identifiers, Amounts, Flags, True Classes. |
| `2_Baseline_Stats` | Descriptive Overviews | Global Transaction Volumes, Absolute Fraud Baselines, Percentages. |
| `3_Risk_By_Category` | Segmentation Analysis | Vertical Risk Densities, Relative Risk Multipliers. |
| `4_Confusion_Matrix` | Model Performance | True Positives, False Positives, False Negatives, Precision, Recall. |
| `5_Cost_Benefit` | Business Value (ROI) | Fraud Losses Saved, Investigation Overheads, Net System Savings. |

---

## Key Strategic Takeaways

* **Precision-Recall Tradeoff:** Fine-tuning detection thresholds to decrease False Negatives dramatically drops total fraud losses, but requires scaling operations to handle the resulting bump in False Positives.
* **Fiscal Optimization:** The optimal point of the model is found not just where accuracy is highest, but where the **Total Cost (Operational Overhead + Uncaught Fraud Loss)** is lowest.

## Technical Frameworks Demonstrated
* Descriptive & Inferential Statistics
* Classification Model Performance Metrics (Confusion Matrices)
* Business Intelligence & Financial Forecasting Models
* Data Visualization & Presentation Delivery

## License
This case study portfolio is open-source and available under the MIT License.
