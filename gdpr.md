# GDPR for Beginners 🇪🇺

> *"Privacy is not about having something to hide — it's about having something to protect."* — Anonymous

**GDPR** (General Data Protection Regulation) is the **EU's data privacy law** — the strongest privacy regulation in the world . It's not just about cybersecurity; it's about **fundamental human rights** in the digital age.

Think of it as the **rulebook for handling personal data** — who can collect it, why they can collect it, how they must protect it, and what happens when they fail. 🔐

---

## Are You In Scope? 🎯

**If you process personal data of people in the EU, you're in scope — regardless of where your company is based.**

```
┌─────────────────────────────────────────────────┐
│              GDPR SCOPE CHECK                   │
├─────────────────────────────────────────────────┤
│  1. PERSONAL DATA?  →  Any data about a person  │
│  2. EU DATA SUBJECT?→  Person in the EU         │
│  3. PROCESSING?     →  Collect, store, use      │
│                                                 │
│  ALL THREE = YOU'RE IN SCOPE ✅                 │
└─────────────────────────────────────────────────┘
```

### What Counts as Personal Data? 🪪

| Category | Examples |
|----------|----------|
| **Basic Identity** | Name, email, phone, address |
| **Online Identifiers** | IP address, cookies, device IDs |
| **Special Categories** 🔴 | Health, race, religion, biometrics, sexual orientation |
| **Financial** | Bank details, payment history |

> ⚠️ **Special categories** require **extra protection** — you need explicit consent or a specific legal basis.

### Who's Who? 👥

| Role | Definition | Example |
|------|------------|---------|
| **Data Subject** | The person whose data is processed | You, me, a customer |
| **Controller** | Decides **why** and **how** data is processed | Your company |
| **Processor** | Processes data **on behalf of** the controller | Cloud provider, payroll service |

> 💡 **Key rule:** Processors can only act on **documented instructions** from the controller .

---

## Individuals' Rights 🛡️

GDPR gives people **control over their data**. These are the rights you must uphold:

```
┌─────────────────────────────────────────────────┐
│              DATA SUBJECT RIGHTS                │
├─────────────────────────────────────────────────┤
│  📋 Right to be Informed     → Know how data is used │
│  👁️ Right of Access          → See what data you have │
│  ✏️ Right to Rectification   → Correct wrong data    │
│  🗑️ Right to Erasure         → "Right to be forgotten" │
│  📦 Right to Portability     → Move data to another provider │
│  🚫 Right to Object          → Stop processing       │
│  ⏸️ Right to Restrict        → Limit how data is used │
└─────────────────────────────────────────────────┘
```

> 📌 These rights must be fulfilled **free of charge** and **within one month** (extendable by two months for complex requests).

---

## Key Requirements 🔑

### 1. 📋 Lawful Basis for Processing
You can't just collect data because you want to. You need a **legal basis**:

| Basis | When It Applies |
|-------|-----------------|
| **Consent** ✅ | Clear, affirmative action — no pre-ticked boxes |
| **Contract** 📝 | Necessary to fulfill a contract |
| **Legal Obligation** ⚖️ | Required by law |
| **Vital Interests** 🚨 | Life-or-death situations |
| **Public Task** 🏛️ | Government functions |
| **Legitimate Interests** 💼 | Business need — balanced against rights |

### 2. 🚨 Data Breach Notification (The Clock is Ticking)

| Timeline | Action | Who |
|----------|--------|-----|
| **72 hours** ⏰ | Notify supervisory authority | Controller |
| **Without undue delay** 📢 | Notify affected individuals | Controller (if high risk) |

> ⚠️ **If the breach poses a high risk** to rights and freedoms, you must also inform the **data subjects** directly .

**What to include in breach notification:**
- Nature of the breach and categories affected
- Contact details of the DPO
- Likely consequences
- Measures taken or proposed 

### 3. 🔐 Security of Processing (Article 32)

You must implement **appropriate technical and organisational measures** :

| Measure | ISO 27001 Connection |
|---------|----------------------|
| **Pseudonymisation** | A.8.24 — Cryptography |
| **Encryption** | A.8.24 — Cryptography |
| **Confidentiality, Integrity, Availability** | CIA Triad — Clauses 4–10 |
| **Resilience** | A.5.29, A.5.30 — Business Continuity |
| **Regular testing** | A.8.8 — Vulnerability Management |
| **Access control** | A.5.15–A.5.18, A.8.2–A.8.5 |

### 4. 🏢 Data Protection Officer (DPO)
You must appoint a DPO if you:
- Are a **public authority**
- Process **large-scale** personal data
- Process **special categories** of data (health, biometrics, etc.) 

### 5. 📝 Data Protection Impact Assessment (DPIA)
Required when processing is **likely to result in high risk** to individuals' rights and freedoms .

### 6. 🌍 International Data Transfers
Transferring data outside the EU requires **safeguards**:
- Adequacy decision (EU Commission approved)
- Standard Contractual Clauses (SCCs)
- Binding Corporate Rules (BCRs)
- Certification mechanisms 

---

## 🔗 Control Connections: Mapping GDPR to ISO 27001

GDPR and ISO 27001 are **not competitors** — they're **allies**. GDPR sets the **legal requirement**; ISO 27001 provides the **management system** to achieve it .

### How the Connection Works

```
┌─────────────────────────────────────────────────────────────┐
│              GDPR REQUIREMENTS                              │
│                                                             │
│  Security of Processing ──────────────────────────────┐     │
│  Breach Notification  ─────────────────────────────────┤     │
│  Privacy by Design  ──────────────────────────────────┤     │
│  Data Subject Rights  ─────────────────────────────────┤     │
│  International Transfers  ─────────────────────────────┤     │
│                                                         │     │
│                    ▼         ▼         ▼                │     │
│              ┌─────────────────────────────────────┐    │     │
│              │       ISO 27001 CONTROLS            │    │     │
│              │  A.8.24  A.5.24  A.8.25  A.5.15...  │    │     │
│              └─────────────────────────────────────┘    │     │
└─────────────────────────────────────────────────────────────┘
```

### 📌 GDPR Art. 32 — Security of Processing → ISO 27001 A.8.24, A.5.15, A.8.13

| GDPR Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Pseudonymisation** | **A.8.24** — Use of cryptography |
| **Encryption** | **A.8.24** — Use of cryptography |
| **Confidentiality** | **A.5.15** — Access control |
| **Integrity** | **A.8.32** — Change management |
| **Availability** | **A.8.13** — Information backup |
| **Resilience** | **A.5.29** — Security during disruption |
| **Testing effectiveness** | **A.8.8** — Technical vulnerability management |

**Why this matters:** GDPR Art. 32 requires **risk-based security**. ISO 27001 Clause 6 (Risk Assessment) gives you the framework to determine what "appropriate" means .

**Examples of connection in practice:**
- You identify personal data risks → **Clause 6.1.2 — Risk Assessment**
- You implement encryption → **A.8.24**
- You restrict access → **A.5.15**
- You test backup restoration → **A.8.13**

---

### 📌 GDPR Art. 33/34 — Breach Notification → ISO 27001 A.5.24–A.5.28

| GDPR Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Detect and assess breach** | **A.5.25** — Assessment of events |
| **Respond to incident** | **A.5.26** — Incident response |
| **Notify authority (72h)** | **A.5.24** — Incident management planning |
| **Notify individuals** | **A.5.26** — Response procedures |
| **Document all breaches** | **A.5.28** — Evidence collection |
| **Learn and improve** | **A.5.27** — Post-incident review |

**Why this matters:** GDPR's **72-hour deadline** requires a mature incident response process. ISO 27001's incident controls (A.5.24–A.5.28) give you the *plan*; GDPR gives you the *deadline* .

**Examples of connection in practice:**
- You build an incident response plan → **A.5.24**
- You detect a breach via SIEM → **A.8.16**
- You notify the DPA within 72h → **A.5.26 + A.5.24**
- You review and improve after the breach → **A.5.27**

---

### 📌 GDPR Art. 25 — Privacy by Design → ISO 27001 A.8.25–A.8.28

| GDPR Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Data protection by design** | **A.8.25** — Secure development lifecycle |
| **Data protection by default** | **A.8.26** — Application security requirements |
| **Secure architecture** | **A.8.27** — Secure system architecture |
| **Secure coding** | **A.8.28** — Secure coding |
| **DPIA integration** | **Clause 6.1.2** — Risk assessment |

**Why this matters:** GDPR requires privacy safeguards to be **built into products and services from the earliest stage** . ISO 27001's secure development controls (A.8.25–A.8.28) give you the technical foundation .

**Examples of connection in practice:**
- You define security requirements for new apps → **A.8.26**
- You build privacy into the design → **A.8.25**
- You conduct a DPIA → **Clause 6.1.2**
- You test for vulnerabilities → **A.8.8**

---

### 📌 GDPR Art. 15–22 — Data Subject Rights → ISO 27001 A.5.34, A.5.15

| GDPR Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Right of Access (DSAR)** | **A.5.34** — Privacy and protection of PII |
| **Right to Erasure** | **A.5.34** — Privacy controls |
| **Right to Portability** | **A.5.34** — Privacy controls |
| **Access control for PII** | **A.5.15** — Access control policy |
| **Logging of PII access** | **A.8.15** — Logging |

**Why this matters:** GDPR rights must be **operationalized** — you need processes to find, export, and delete personal data on request. ISO 27001's privacy controls (A.5.34) and access controls (A.5.15) give you the structure .

**Examples of connection in practice:**
- You document where PII is stored → **A.5.34**
- You restrict who can access PII → **A.5.15**
- You log access to PII → **A.8.15**
- You fulfill a DSAR within 1 month → **A.5.34**

---

### 📌 GDPR Art. 28 — Processors → ISO 27001 A.5.19–A.5.22

| GDPR Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Due diligence on processors** | **A.5.19** — Supplier relationships |
| **Data processing agreements (DPA)** | **A.5.20** — Supplier agreements |
| **Supply chain security** | **A.5.21** — ICT supply chain |
| **Monitoring processors** | **A.5.22** — Supplier monitoring |
| **International transfers** | **A.5.20** — Contractual safeguards |

**Why this matters:** GDPR makes **you responsible** for your processors. ISO 27001's supplier controls (A.5.19–A.5.22) give you the **framework to manage that responsibility** .

**Examples of connection in practice:**
- You assess a new cloud provider → **A.5.19**
- You sign a DPA with security clauses → **A.5.20**
- You monitor provider compliance → **A.5.22**
- You verify international transfer safeguards → **A.5.20**

---

### 🧩 The Pattern: Every GDPR Requirement Connects

| GDPR Requirement | Primary ISO 27001 Connections |
|------------------|-------------------------------|
| **Lawful Basis** | Clauses 4–6 (Risk, Context, Legal Register) |
| **Security of Processing** | A.8.24, A.5.15, A.8.13, A.8.8 |
| **Breach Notification** | A.5.24–A.5.28, A.8.16 |
| **Privacy by Design** | A.8.25–A.8.28, Clause 6.1.2 |
| **Data Subject Rights** | A.5.34, A.5.15, A.8.15 |
| **Processor Management** | A.5.19–A.5.22 |
| **International Transfers** | A.5.20 (Contractual safeguards) |
| **DPO Appointment** | Clause 5.3 (Roles and responsibilities) |

> 💡 **The takeaway:** GDPR is the **legal obligation**. ISO 27001 is the **management system** that proves you're meeting it. ISO 27001 covers approximately **75% of GDPR's technical and organisational requirements** .

---

## GDPR vs NIS2 vs DORA — Quick Comparison ⚖️

| Aspect | GDPR 🇪🇺 | NIS2 🇪🇺 | DORA 🇪🇺 |
|--------|---------|---------|---------|
| **Type** | Regulation | Directive | Regulation |
| **Focus** | Personal data privacy | Critical sector cybersecurity | Financial sector resilience |
| **Scope** | Anyone processing EU data | 18 critical sectors | Financial entities |
| **Breach Reporting** | 72h to DPA | 24h/72h/1mo to CSIRT | 24h/72h/1mo to regulator |
| **Fines** | €20M or 4% turnover | €10M or 2% turnover | National law determines |
| **Individuals' Rights** | ✅ Yes | ❌ No | ❌ No |
| **Relationship** | Foundation | General cybersecurity | Finance-specific |

> 🤝 **Best practice:** Use ISO 27001 as your ISMS backbone, then map GDPR (and NIS2/DORA if applicable) requirements onto it. One system, multiple compliance wins .

---

## Curiosities for Cybersecurity Geeks 🤓

### 1. 🇪🇺 Born from 1995 Directive
GDPR replaced the **1995 Data Protection Directive**. The old rules were fragmented across 28 different national laws — GDPR unified them into **one EU-wide standard** .

### 2. 💰 The €20M Fine
GDPR fines can reach **€20 million or 4% of global annual turnover** — whichever is higher . This isn't a slap on the wrist; it's an existential threat for some companies.

### 3. 🌍 It Follows You Everywhere
GDPR applies to **non-EU companies** if they offer goods or services to EU individuals or monitor their behaviour. If you're a US company with EU customers, **you're in scope** .

### 4. 📦 The "Right to be Forgotten"
This isn't just about deleting data — it's about **propagating the deletion** across all systems, including backups and third parties. It's a **technical and legal challenge**.

### 5. 🕐 The 72-Hour Clock
GDPR gives you **72 hours** to notify the supervisory authority of a breach. NIS2 gives you **24 hours** for an early warning. The trend is clear: **faster reporting, more automation**.

### 6. 🎓 ISO 27001 Certification ≠ GDPR Compliance
You can be ISO 27001 certified and **still fail GDPR**. Why? GDPR requires specific **legal documentation** — lawful basis records, DPIAs, DPAs, consent mechanisms — that ISO 27001 doesn't mandate. But ISO 27001 gives you **75% of the technical foundation** .

---

## Quick Reference 📌

| Term | Meaning |
|------|---------|
| **GDPR** | General Data Protection Regulation |
| **Data Subject** | The person whose data is processed |
| **Controller** | Decides why and how data is processed |
| **Processor** | Processes data on behalf of controller |
| **DPO** | Data Protection Officer |
| **DPIA** | Data Protection Impact Assessment |
| **DSAR** | Data Subject Access Request |
| **PII** | Personally Identifiable Information |
| **DPA** | Data Processing Agreement |

---

## Study Questions 📝

1. What does GDPR stand for?
2. What are the three scope check criteria?
3. How many hours to notify a breach to the supervisory authority?
4. What is the difference between a controller and a processor?
5. Which ISO 27001 control maps to GDPR's security of processing requirement?
6. Can you be ISO 27001 certified and still fail GDPR?

<details>
<summary>👉 Click to reveal answers</summary>

1. General Data Protection Regulation
2. Personal data + EU data subject + Processing
3. 72 hours
4. Controller decides why/how; Processor acts on controller's instructions
5. A.8.24 — Cryptography (for encryption/pseudonymisation)
6. Yes — GDPR has specific legal documentation requirements ISO 27001 doesn't mandate

</details>

---

## Further Reading 📚

- 🔗 [GDPR Official Text — EUR-Lex](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- 🔗 [European Data Protection Board](https://edpb.europa.eu/)
- 🔗 [ISO/IEC 27001:2022 Official Page](https://www.iso.org/standard/27001)
- 🔗 [GDPR + ISO 27001 Mapping Guide](https://gdprlocal.com/strategic-synergy-optimising-gdpr-compliance-through-iso-270012022-controls/)

---

> 💬 *"GDPR doesn't ask if you respect privacy — it asks you to prove it, with documentation, on a deadline, with fines that make executives pay attention."* 🇪🇺🔐⚖️
