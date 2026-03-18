# Model Risk Assessment

## 1. Model Overview

The AI model is designed to support Customer Due Diligence (CDD) by assisting analysts in risk profiling of customers.

The model uses a combination of structured and unstructured data to generate a risk classification (Low, Medium, High).

This includes:

- Customer-provided information (e.g., annual reports, financial statements, ownership structures, identification documents, and business activity details)
- Ownership and registration data, validated against official sources (e.g., KvK or equivalent registries)
- Jurisdictional risk indicators, including exposure to high-risk or low-transparency regions (e.g., offshore jurisdictions)
- External data sources such as news articles, public records, and adverse media
- Internal banking systems (e.g., customer data platforms such as Siebel)

The model considers consistency, traceability, and validity of the data across these sources when generating outputs.

___


The model also provides explanations to support its outputs, referencing relevant and verifiable data sources where available, enabling analysts to understand the reasoning behind the risk classification..

__

The final decision remains with the human analyst, with the AI acting as a support tool.


## 2. Model Inputs

The model relies on multiple data sources to generate risk assessments, including:

- Customer identification data (name, country, business activity)

- Ownership structure and Ultimate Beneficial Owner (UBO) information

- Jurisdictional risk indicators (e.g., high-risk countries)

- External data sources such as news articles, sanctions lists, and public records

- Internal bank systems (e.g., customer data platforms such as Siebel)

The quality, completeness, and accuracy of these inputs directly impact the reliability of the model output.


