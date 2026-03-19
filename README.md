# AI Governance & Model Risk Framework for CDD

A practical project demonstrating how AI Governance and Model Risk principles can be applied to AI-assisted Customer Due Diligence (CDD) in banking.

## Overview

This project presents an AI Governance & Model Risk framework for an AI-assisted Customer Due Diligence (CDD) use case in banking.

The goal is to demonstrate how AI models can be governed, monitored, and validated in a regulated financial environment.

## Key Areas Covered

- Model assumptions and limitations  
- Data quality and validation checks  
- Bias and fairness considerations  
- Explainability and transparency  
- Regulatory and compliance risks  
- Model monitoring and drift  
- Operational risks and human oversight  

## Why this project

As financial institutions adopt AI in risk assessment, it becomes critical to ensure that models are transparent, explainable, and compliant with regulatory expectations.

This project connects real-world FEC/CDD experience with AI Governance and Model Risk principles.

# ai-governance-model-risk-banking
AI Governance & Model Risk Framework for an AI-assisted CDD Risk Profiling banking use case

## Model Governance & Controls

To ensure the AI model is used responsibly in a banking environment, the following governance controls are required:

### 1. Data Governance

- Ensure high-quality, complete, and validated input data, with periodic data quality checks in place
- Clearly define data ownership, with data owners responsible for maintaining data accuracy, completeness, and timeliness
- Provide training and awareness to data owners on how data is used within the model and how changes may impact model outputs
- Perform regular checks for missing, inconsistent, or outdated data, and ensure proper resolution processes are in place
- Monitor data sources for reliability and ensure alignment across internal systems, customer-provided data, and external sources




### 2. Model Validation

- Perform independent validation before deployment by a separate function (e.g., model validation team or second-line risk), ensuring that validation is not solely dependent on the analyst
- Clearly define roles and responsibilities for validation, including reviewers, validators, and approval authorities
- Conduct back-testing of model outputs against historical cases to assess accuracy and consistency of risk classifications
- Ensure validation includes both business and technical perspectives (e.g., business analysts, testers, and risk teams)
- Perform periodic reviews of model performance, including reassessment of assumptions, inputs, and outputs
- Utilize governance tools (e.g., model inventory or tracking tools such as OneTrust or similar) to track model lifecycle, review timelines, and changes
- Ensure all validation activities, findings, and approvals are properly documented for audit and regulatory purposes


### 3. Explainability

- Model decisions should be explainable to analysts, auditors, and stakeholders, with clear reasoning on how conclusions are derived and which data sources are used
- Ensure transparency in data processing, including how raw data is transformed into model inputs, with proper documentation of data lineage and ownership
- Maintain clear documentation of key input factors (features) that influence model outcomes, enabling validation and challenge by analysts
- Ensure that only relevant and necessary data is used for decision-making, avoiding unnecessary exposure of sensitive or confidential information
- Provide appropriate access to relevant stakeholders (e.g., auditors, risk teams) to review model logic, data sources, and decision pathways
- Ensure explanations are consistent, traceable, and aligned with actual model behavior, avoiding misleading or incomplete justifications





### 4. Human Oversight

- The model should be used as a decision-support tool and not as a fully automated decision-maker; final risk classification must remain under human responsibility
- Analysts should review all model outputs, with a risk-based approach where higher-risk or complex cases (e.g., high-risk or potentially unacceptable clients) receive enhanced scrutiny
- The model may assist in automating specific components (e.g., business profile, ownership structure, initial SoW/SoF indicators), but conclusions must be validated by analysts and, where applicable, quality control functions
- Human review should focus on identifying inconsistencies, contextual gaps, or potential misinterpretation by the model
- Establish a clear escalation process for cases where model outputs are uncertain, inconsistent, or potentially inaccurate
- Ensure that identified issues are fed back into the model governance process, enabling continuous improvement, recalibration, or updates to the model
- Maintain proper documentation of human interventions, overrides, and escalation decisions for audit and accountability purposes


### 5. Monitoring & Drift Detection

- Implement continuous monitoring of model outputs, inputs, and data processing stages to ensure transparency across the full data lifecycle
- Establish clear traceability across data flow (input → transformation → output), enabling identification of issues at each stage (e.g., data input errors, processing errors, or model logic issues)
- Detect changes in model behavior over time (model drift), including shifts in input data patterns, customer profiles, or external risk indicators
- Utilize governance and monitoring tools (e.g., model tracking or inventory systems) to track model performance, review cycles, and changes
- Ensure proper training and awareness for users and data owners to effectively use monitoring tools and interpret outputs
- Perform periodic recalibration and review of the model, not only based on performance degradation but also due to:
  - Regulatory changes (e.g., EU AI Act updates)
  - Internal policy or standard changes
  - System or data pipeline updates
  - Emerging risk patterns or business changes
- Maintain documentation of monitoring activities, identified issues, and remediation actions for audit and governance purposes




### 6. Regulatory Compliance

- Ensure alignment with applicable regulatory frameworks, including the EU AI Act, GDPR, and relevant banking regulations
- Establish regular engagement with compliance and legal functions (e.g., periodic reviews, workshops) to stay updated on regulatory changes and interpretations
- Implement a structured process to track regulatory updates, including:
  - Identification and assessment of new requirements
  - Defined timelines for implementation
  - Approval workflows before changes are deployed
- Maintain transparency on whether model outputs are based on current or previous regulatory standards, including the use of appropriate disclaimers where required
- Ensure all changes driven by regulatory updates are documented, approved, and traceable
- Maintain comprehensive documentation covering:
  - Data sources and ownership
  - Model logic and assumptions
  - Validation and approval records
  - Monitoring and review activities
- Clearly document any temporary exceptions or missing elements (e.g., unavailable documents), including:
  - Approval from compliance or relevant authority
  - Defined remediation actions and timelines
  - Alerts or follow-ups to ensure completion
- Ensure all documentation is audit-ready, with clear traceability, accountability, and evidence of decision-making



## Author

Sonal Dongare  
FEC Analyst | AI Governance & Model Risk (in transition)
