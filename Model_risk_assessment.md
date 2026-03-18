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

## 3. Model processes
- The model assumes that the data processing logic, feature selection, and underlying algorithms correctly identify, prioritize, and interpret relevant information for accurate risk assessment

## 4. Model Limitations

Despite the use of multiple data sources and validation mechanisms, the model has inherent limitations:

- The model may not be able to identify hidden or layered ownership structures, especially in jurisdictions with low transparency (e.g., offshore jurisdictions)
- The model may misinterpret or over-rely on adverse media, particularly when the context of the information is unclear, outdated, or influenced by external factors
- The model may not fully capture the outcome or materiality of past events (e.g., legal cases or regulatory actions), leading to incorrect risk interpretation
- The model depends on available data and may fail when critical information is missing, incomplete, or not publicly accessible
- The model may not adapt immediately to changes in regulations, policies, or emerging risk patterns
- The model may struggle to understand nuanced business contexts, especially in complex or evolving industries
- The model may generate explanations that are incomplete or not fully aligned with the actual reasoning process
- The model may not be able to detect intentional structuring or routing of transactions through intermediary jurisdictions (e.g., “U-turn” countries) designed to obscure exposure to high-risk or sanctioned regions
- The model may have limited ability to accurately interpret financial statements (e.g., annual accounts), particularly in assessing true profitability, financial health, or accounting nuances
- The model may not be able to fully trace the source of funds or detect complex layering patterns, increasing exposure to money laundering risks
- The model may fail to accurately identify or assess Politically Exposed Persons (PEPs) within complex ownership structures, including limitations in evaluating source of wealth (SoW) and source of funds (SoF)


These limitations highlight the importance of human oversight and validation in the decision-making process.

