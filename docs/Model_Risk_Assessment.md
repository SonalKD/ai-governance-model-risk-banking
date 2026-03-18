# Model Risk Assessment

## Overview
This section focuses on risks specifically related to the design, development, and performance of the AI model used for customer risk profiling.

---

## 1. Model Assumptions Risk
The model may rely on assumptions about customer behavior, country risk, or business activity that may not always hold true in real-world scenarios.

---

## 2. Data Risk
The model depends heavily on input data such as country, industry, and ownership structure. Poor quality, incomplete, or outdated data can negatively impact model performance.

---

## 3. Model Accuracy Risk
The model may produce incorrect risk scores (false positives or false negatives), leading to poor decision-making.

---

## 4. Model Drift Risk
Over time, patterns in customer behavior or risk environments may change, causing the model to become less accurate.

---

## 5. Explainability Risk
If the model cannot clearly explain how it arrived at a risk score, it may not be suitable for use in a regulated environment.

---

## 6. Bias Risk
The model may unintentionally favor or disadvantage certain customer groups based on country, business type, or other factors.

---

## 7. Overfitting / Underfitting Risk
The model may perform well on training data but fail in real-world scenarios (overfitting), or may be too simplistic and miss important patterns (underfitting).

---

## 8. Dependency Risk
The business may become too dependent on the model, reducing human judgment and critical thinking.

---

## 9. Validation Risk
If the model is not properly tested and validated before deployment, it may introduce significant risk into the system.

---


### 10. Limited Forward-Looking Capability

The model relies on historical and current data and may not capture future customer intentions, such as planned business expansion or changes in activities. This may result in incomplete or inaccurate risk assessment.

---


### 11. External Data Dependency Risk

The model depends on external data sources such as sanctions lists and country risk classifications. If these sources are not updated regularly, the model may fail to identify high-risk jurisdictions or sanctioned entities.

---

### 12. Data Completeness Risk

The model may not have access to all relevant customer information, such as accounts held across different systems or institutions. Incomplete data can lead to inaccurate risk scoring.

---

### 13. Data Freshness Risk

Customer information such as business activities (e.g., updates in KvK records) may change over time. If the model does not receive timely updates, it may base its assessment on outdated information.


## Summary
These model-specific risks highlight the need for proper validation, monitoring, and governance controls to ensure the model remains reliable and fit for purpose.
