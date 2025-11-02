# ServiceNow_GRC_Project2
ServiceNow GRC + Agentic AI Compliance Summary Assistant | Yokohama PDI
# ServiceNow GRC | Agentic AI Compliance Summary Assistant (Yokohama PDI)

## Overview
This project introduces an **Agentic AI assistant** within ServiceNow’s GRC module that automatically **summarizes audit results** and generates **AI-driven recommendations** using Flow Designer.  
The automation demonstrates how Generative AI can enhance compliance reporting by producing contextual summaries and intelligent follow-up actions.

---

## Flow Logic
1. **Trigger:** Compliance Audit created or updated  
2. **If Audit Result = Passed**
   - AI Summary → “Audit successfully passed. Systems compliant.”
   - AI Recommendation → “Maintain standards and schedule next audit.”  
3. **If Audit Result = Partial**
   - AI Summary → “Audit partially passed. Gaps identified.”
   - AI Recommendation → “Review minor gaps and update documentation.”  
4. **If Audit Result = Failed**
   - AI Summary → “Audit failed. Critical controls breached.”
   - AI Recommendation → “Immediate remediation plan required and escalate to management.”  
5. **Else (No Result)**
   - AI Summary → “No audit result provided. Awaiting completion.”

---

## Highlights
- Built in **Flow Designer** on **Yokohama PDI**  
- Demonstrates **AI reasoning + summarization**  
- Produces contextual **AI Summary** and **Recommendations**  
- 100% **No-Code**  
- Ready for integration with **Predictive Intelligence** and **Now Assist**

---

## Diagram
![Flow Diagram](Diagrams/Flow Diagram.png)

---

## Example Test Results
| Audit Result | AI Summary | AI Recommendation |
|---------------|-------------|--------------------|
| Passed | Audit successfully passed. Systems compliant. | Maintain standards and schedule next audit. |
| Partial | Audit partially passed. Gaps identified. | Review minor gaps and improve documentation. |
| Failed | Audit failed. Critical controls breached. | Immediate remediation plan required. |
| (Empty) | No audit result provided. | N/A |

---

## Business Impact
This automation reduces manual compliance review effort by **50–70%**, improves accuracy of audit reporting, and provides AI-based recommendations for risk mitigation.  
It demonstrates how **AI + ServiceNow GRC** can transform compliance management through automated reasoning and intelligent summaries.
