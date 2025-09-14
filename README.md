<div align="center">

# Customer Churn Prediction & Analytics Platform

End-to-end churn risk intelligence: data → ML prediction → actionable BI dashboards.

<br/>
<img src="Customer Churn Dashboard.png" alt="Churn Dashboard" width="420" />
<img src="Customer Risk Analysis.png" alt="Risk Dashboard" width="420" />

</div>

---

## Executive Summary
Customer churn impacts revenue durability. This project delivers a clear analytical foundation and interactive Power BI dashboards that segment churn risk and surface actionable retention insights. The current scope focuses on data readiness, risk framing, and stakeholder visualization—designed for fast extension into a full ML pipeline.

---
## ✅ Highlights
- Interactive Power BI dashboards (churn overview + risk analysis) showcasing churn trend, retention cohorts, and risk segmentation.
- Risk banding framework (Critical / High / Medium / Low) aligned to actionable follow‑up windows.
- Clean separation between current delivered assets and clearly scoped next build steps.
- Practitioner-oriented structure that can be extended into a reproducible ML pipeline without refactoring.

---
## Problem Statement
Churned customers require replacement through costly acquisition. Early identification of accounts trending toward churn enables targeted retention actions that improve lifetime value and reduce leakage.

---
## Objectives (Current Scope)
| Area | Objective |
|------|-----------|
| Data | Provide a unified customer foundation for churn segmentation |
| Analytics | Surface churn trend and retention cohorts clearly |
| Risk | Classify customers into actionable probability-aligned bands |
| Stakeholder Value | Enable leadership & success teams to prioritize follow‑ups |

---
## 🗂 Dataset
Source file: `02 Customer Churn-Dataset.xlsx`

Representative fields:
- Customer identifiers & tenure metrics
- Subscription & contract attributes
- Billing (monthly / total charges)
- Engagement & support interaction indicators
- Churn status flag

These feed risk segmentation and dashboard aggregation.

---
## High-Level Flow (Planned Extension)
Data (Excel) → Transformation → (Future) Model Training → Scoring Output → Dashboards

---
## Risk Banding Framework
| Probability | Band | Action Focus |
|-------------|------|-------------|
| ≥ 0.75 | Critical | Immediate retention intervention |
| 0.50–0.75 | High | Incentive / offer sequencing |
| 0.30–0.50 | Medium | Nurture & monitor |
| < 0.30 | Low | Standard lifecycle engagement |

---
## 📊 Dashboards
Included: `Customer Churn Dashboard.pbix`, `Customer Risk Analysis Dashboard.pbix` (+ PNG previews above).

Showcased views:
- Churn trend and retention
- Cohort dynamics
- Risk distribution
- Segmentation & drill‑through

---
## Future ML Extension
Next layer adds: model training (baseline → ensemble), probability calibration, explainability exports, and drift monitoring.


---
Planned (next milestone) will introduce `data/`, `src/`, `artifacts/`, and `reports/` directories as the modeling layer is added.

---
## Next Increment (Planned)
Add minimal Python pipeline (ingestion, feature builder, baseline model) + scored output feeding dashboard refresh.

---
## Future Evaluation Artifacts
ROC / PR curves · Lift chart · Calibration plot · SHAP drivers · Drift summary


---
## 🗺 Upcoming Enhancements
- Add requirements file & environment definition
- Commit ingestion + feature engineering modules
- Baseline model & risk scoring export
- SHAP driver integration in dashboard

---
##  Design Principles
- Practical first: deliver dashboards & risk framing before automation.
- Extend not rewrite: structure supports adding ML incrementally.
- Action orientation: risk bands map directly to retention motions.
- Transparency: clear separation of shipped vs upcoming.

---
## 🤝 Contributing
Future contributions: modular pipeline stages, evaluation rigor, explainability exports.

---
