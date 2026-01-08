# Domain 2 – Information Security Risk Management (20%)

### ISACA Domain Description (Paraphrased)
Information security risk management identifies, analyses, responds to, and monitors risks to ensure they remain within acceptable levels.

> **Exam mindset:** Risk management exists to **support business decisions**, not to eliminate all risk.

---

## Part A – Information Security Risk Assessment

**Risk Boundaries**
- Risk Appetite: Willingness to take risks
- Risk Tolerance: Acceptable variation
- Risk Capacity: Maximum berable risk

**Two Types of Risk**
- Inherent Risk - The risk in the absence of any controls. or mitigation efforts.
- Residual Risk - The level of risk remaining after controls have been applied.

**Risk Categories (types)**
- Strategic - Threats to the organisations ability to achieve strategic objective.
- Operational - Related to day-to-day operations. Failure of internal process, people or systems.
- Reputational - Erode client and stakeholder trust. May be from data breaches or unethical behaviour.
- Compliance - Non-compliance with laws, regulations, standards. Often result in fines and penalties.

ISACA context:
Risk events are specific occurrences that could negatively impact the confidentiality, integrity, or availability of information assets.

**Key points:**
- A risk event is what happens, not the cause.
- Must be clearly defined and business-relevant.
- Events link threats, vulnerabilities, and impact.
- Poorly defined events lead to poor decisions.
- Qualitative: high/medium/low.
- Quantitative: financial values and probabilities.
- Example:
“Unauthorised disclosure of customer data” is a risk event, not “malware infection”.

**More Risk Definitions**
- Systemic Risk - a catagory of tish that describes thrats to a system, market or economic segment. ie finance is susceptible to systemic risk.
- Obscure Risk - Risk that has not yet occured and is unlikely or difficult to fathom. A black swan event.

---

### 2A1 Emerging Risk and Threat Landscape

**ISACA context:**  
Threat modelling identifies potential threat sources and methods, while the threat landscape reflects current and emerging threats. Emerging risks and threats reflect changes in technology, business, and adversary behaviour.

**Key points:**
- Identify potential threats (technical, physical, operational). Examine vulnerabilities to identify weak points that could result in risk. Recognise assets including third parties that keep the business running.
- Threat landscape evolves constantly.
- Threats can be internal, external, accidental, or intentional.
- Intelligence improves awareness.
- Emerging risks involve uncertainty.
- Early identification enables proactive action.
- Focus on realistic and relevant threats.
- Threat vector vs attack surface - threat vector is a specific way to breach. attack surface is the system itself. The strong the defences the smaller the attack surface and fewer threat vectors.

**Memory hook:**  
> *Unknown risks become known risks through monitoring.*

**Example:**  
Ransomware targeting healthcare organisations becomes a key threat due to increased frequency and impact.
AI adoption introduces new privacy and security concerns.

---

### 2A2 Vulnerability and Control Deficiency Analysis

**ISACA context:**  
Vulnerability management identifies weaknesses that could be exploited by threats.

**Key points:**
- Vulnerabilities may be technical, procedural, or human.
- Control deficiencies increase likelihood or impact.
- Prioritisation is based on business impact.
- Identification does not equal risk acceptance.
- Governance focuses on process, not tools.

**Memory hook:**  
> *A vulnerability without impact is not a priority.*

**Example:**  
Lack of multi-factor authentication is a vulnerability that increases the likelihood of credential theft.

---

### 2A3 Risk Assessment and Analysis

**ISACA context:**  
Risk assessment evaluates likelihood and impact to prioritise risk treatment. Risk assessments should follow recognised concepts and standards to ensure consistency and credibility.

**Key points:**
- Risk = likelihood × impact.
- Scenarios combine threat, vulnerability, and impact.
- Can be qualitative or quantitative.
- Must be consistent and repeatable.
- Using a standard scoring matrix allows comparison of risks across departments.
- Supports decision-making and executive-level understanding.
- Helps prioritise risk treatment. Accept, mitigate, transfer or avoid.
- Quantitative - assigns a dollar value. Objective and uses formulars.
- Qualitative - uses a scoring system. Subjective usually low medium high heat map.

**Memory hook:**  
> *Impact usually outweighs likelihood on the exam.*

**Example:**  
A low-probability outage with high financial impact is prioritised.


---

## Part B – Information Security Risk Response

### 2B1 Risk Treatment / Risk Response Options

**ISACA context:**  
Defines how an organisation addresses identified risk.

**Key points:**
- Accept – within appetite.
- Mitigate – reduce risk. apply a control to minimise. 
- Transfer – shift risk to reduce probability or magnitude. ie 3rd party or insurance. 
- Avoid – eliminate activity. 
- Must align with appetite.
- Risk acceptance SHOULD NOT exceed risk appetite and MUST NOT exceed risk capacity.
- Business Impact Analysis (BIA) evaluates the potential impact of disruptions to business processes and information assets.
- Identifies critical processes. Determines RTO and RPO. Inputs into BCP and DR planning.
- Focuses on business consequences, not systems.
- Inherent risk shows raw exposure. Residual risk determines acceptance decisions. Residual risk must align with risk appetite.
- Controls reduce likelihood, impact, or both.

**Memory hook:**  
> *Avoidance removes risk; mitigation reduces it.*

**Example:**  
Insurance transfers financial impact but not operational disruption. An outage of online sales systems results in direct revenue loss and reputational damage.

---

### 2B2 Risk and Control Ownership

**ISACA context:**  
Controls can be preventive, detective, or corrective in nature. Clear ownership ensures accountability for risk decisions and control effectiveness.

**Key points:**
- Business owns risk.
- Risk owner is responsible for ensuring the risk is managed appropriately. typically senior exec, manager or director. They make decisions about risk response, allocate resources to manage, accept residual risk it it aligns to appetite, ongoing monitoring and reporting of risk. 
- Control owners usually the same person but custodian or steward of the control ensures operation. Ensure control is designed, documented and tested.
- Ownership supports escalation.
- Data Owner - Responsible for making decisions on how data is accessed, edited and used. Determine classification and are accountable for the risk.
- Data Custodian - Responsible for the day to day maintenance and config of the data. 
- Responsibility can be delegated but Accountability cannot be delegated away.
- Controls must be technically effective, cost effective and support business objectives. 
- Control Objectives. Preventive (firewalls, training), Detective (CCTV, log monitoring), Corrective (backup/restore)
- Control Categories. Technical (whitelisting, proxy), Administrative (policies or procedures), Physical (doors, etc)
- Control effectiveness and assurance. self assess, audits, vulnerability scans.

**Memory hook:**  
> *Risk ownership sits with those who benefit from the risk.*

**Example:**  
A business unit accepts residual risk after control implementation.

---

### 2B3 Risk Monitoring and Reporting

**ISACA context:**  
Ensures risks and controls remain effective and visible over time. Inherent risk exists before controls; residual risk remains after controls are applied.

**Key points:**
- Continuous or periodic monitoring.
- Metrics support insight. Reporting must suit the audience and enable informed decisions.

**Memory hook:**  
> *What isn’t monitored can’t be governed.*

**Example:**  
KRIs alert leadership to increasing threat activity.

**Risk register:** 
A risk register documents identified risks, their analysis, ownership, and treatment status.

**Key points:**
- Central source of risk information. Assigns ownership and accountability.
- Supports reporting and monitoring. Must be kept current.
- Information Security Manager is responsible for regular risk assessments, stakeholder communication and risk status reporting including open risks.
**Example:**
Each cyber risk includes a description, likelihood, impact, owner, and mitigation plan.

---

## Practice Exam Questions – Domain 2

### Question 1
What MOST influences the effectiveness of security controls?

**Answer:** Organizational culture.  
**Explanation:** Culture drives behaviour when controls fail.

---

### Question 2
What is the PRIMARY output of a risk assessment?

**Answer:** Prioritised risks to support decision-making.  
**Explanation:** Risk assessments inform action, not documentation.

---

### Question 3
Which risk response option eliminates risk entirely?

**Answer:** Risk avoidance.  
**Explanation:** Avoidance removes the activity creating the risk.

---

### Question 4
Why must risk reporting be tailored to its audience?

**Answer:** To enable effective decision-making.  
**Explanation:** Executives need summaries, not technical detail.

---

### Question 5
What is the PRIMARY purpose of a risk assessment?

**Answer:** To support informed business decisions.
**Explanation:** Risk assessments exist to enable decision-making, not to catalogue threats.

---

### Question 6
Which best describes a risk event?

**Answer:** A potential occurrence that negatively impacts business objectives.
**Explanation:** Risk events describe outcomes, not threats or vulnerabilities alone.

---

### Question 7
What is the MAIN output of a business impact analysis (BIA)?

**Answer:** Prioritised business processes and recovery requirements.
**Explanation:** BIAs identify what matters most and how quickly it must be restored.

---

### Question 8
What is the PRIMARY benefit of risk scenarios?

**Answer:** Improved consistency and clarity in risk evaluation.
**Explanation:** Scenarios help leadership understand and compare risks.

---

### Question 9
What does residual risk represent?

**Answer:** Risk remaining after controls are applied.
**Explanation:** This risk must be accepted, mitigated further, transferred, or avoided.

---

### Question 10
Which factor MOST influences risk prioritisation?

**Answer:** Business impact.
**Explanation:** ISACA prioritises impact over technical severity.
