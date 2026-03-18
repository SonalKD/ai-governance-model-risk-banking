Skip to content
SonalKD
ai-governance-model-risk-banking
Repository navigation
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Files
Go to file
t
docs
README.md
ai-governance-model-risk-banking/docs
/
Risk_Assessment.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

No wrap
Editing Risk_Assessment.md file contents
Selection deleted
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
121
122
123
124
125
126
127
128
129
130
131
132
133
134
135
136
137
138
139
140
141
142
143
144
145
146
147
148
### 5. Regulatory and Compliance Risk

The use of AI in a banking environment is subject to evolving regulatory requirements and internal policies. Failure to align with these requirements may lead to compliance breaches.

Key concerns include:

- Continuous changes in regulatory frameworks, standards, and internal policies related to AI, model risk, and data usage
- Risk that the model may become outdated if it does not reflect the latest regulatory expectations or control requirements
- Lack of clarity on which regulatory standards, policies, or control frameworks were applied during model development
- Absence of proper documentation to demonstrate compliance with applicable standards
- Risk that outputs are generated based on outdated assumptions, rules, or regulatory interpretations
- Inadequate auditability if decisions, data sources, and applied controls are not clearly documented and traceable

To mitigate this risk, the model and associated governance framework should:
- Clearly document applicable standards, policies, and control requirements
- Maintain versioning of models and regulatory references
- Include disclaimers where applicable if certain standards may not be fully up to date
- Be periodically reviewed and updated to align with regulatory changes
- Ensure audit readiness through proper documentation, traceability, and evidence of controls

---

### 6. Model Drift and Monitoring Risk

Over time, the performance and reliability of the AI model may degrade due to changes in data patterns, customer behavior, or external risk environments.

Key concerns include:

- Model drift, where the model becomes less accurate as underlying data distributions change
- Lack of timely monitoring to detect performance degradation or unusual patterns
- Infrequent or inconsistent review cycles, especially for high-risk models
- Delayed identification of issues due to absence of automated alerts or monitoring mechanisms
- Changes in upstream data sources or systems impacting model inputs without proper visibility
- Lack of proper documentation of model updates, approvals, and changes

To mitigate this risk, the governance framework should include:

- Defined review cycles based on model risk level (e.g., high-risk models reviewed at least annually or more frequently if needed)
- Use of monitoring tools (e.g., governance platforms such as OneTrust or similar) to track model performance, alerts, and compliance status
- Continuous monitoring of key performance indicators and drift metrics
- Ability to trigger reviews or updates before scheduled review dates if significant changes are detected
- Proper documentation of all changes, approvals, and decisions related to the model lifecycle
- End-to-end data lineage visibility to track how data flows from source to model output, enabling easier identification of issues in case of data or system failures

---

### 7. Operational Risk

Operational risk arises when both the AI system and the human analyst fail to correctly assess customer risk, leading to incorrect decisions.

Key concerns include:

- Incorrect risk classification by the model, combined with failure of the analyst to identify or override the error
- Rejection of legitimate customers due to incorrect high-risk classification, leading to business loss and poor customer experience
- Onboarding or retention of high-risk or unacceptable customers due to incorrect low or medium risk classification, potentially resulting in regulatory penalties and reputational damage
- Lack of adequate training and awareness among analysts on how to interpret and challenge AI outputs
- Over-dependence on existing model logic without continuous improvement or adaptation to new risk patterns
- Failure to update or enhance the model as new features, data sources, or risk indicators become available

To mitigate this risk, the governance framework should ensure:

- Strong human-in-the-loop controls and escalation mechanisms
- Regular training and awareness programs for analysts
- Continuous model improvement and enhancement based on feedback and changing risk environments
- Clear documentation of decision-making processes and overrides
- Alignment between operational processes and model behavior to ensure consistency and reliability
---

## Summary
These risks highlight the importance of implementing strong governance controls, human oversight, and continuous monitoring when using AI in a banking environment.
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
New File at / · SonalKD/ai-governance-model-risk-banking 
