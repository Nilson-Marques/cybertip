# DORA Explained Simply 🇪🇺

> *"Resilience is not about avoiding the storm — it's about being able to operate through it."* — Anonymous

**DORA** (Digital Operational Resilience Act) is an **EU regulation** for the financial sector. It's the digital sibling of ISO 27001 — but with **legal teeth**, **mandatory timelines**, and **no opt-out**. 🏦

Think of it as the **operational resilience rulebook** that forces banks, insurers, and their tech providers to survive, respond, and recover from cyber incidents — not just plan for them. ⚡

---

## Who It Applies To 🎯

- 🏦 **Banks** and credit institutions
- 🛡️ **Insurers** and reinsurers
- 📈 **Investment firms** and trading venues
- 💳 **Payment providers** and crypto-asset service providers
- ☁️ **ICT third-party providers** (cloud, SaaS, data centers) — *yes, they're in scope too*

> 😰 Without DORA: *"We had a breach... we'll figure it out."*
> 😎 With DORA: *"We reported in 24 hours, contained in 72 hours, and filed the final report in 30 days."*

---

## Key Requirements 🔑

```
┌─────────────────────────────────────────────────┐
│              DORA — 5 PILLARS                   │
├──────────────┬──────────────┬──────────┬────────┤
│ ICT RISK     │ INCIDENT     │ RESILIENCE│ THIRD │
│ MANAGEMENT   │ REPORTING    │ TESTING   │ PARTY │
│   🛡️        │   🚨         │  🧪       │ 🤝    │
├──────────────┼──────────────┼──────────┼────────┤
│ Governance   │ 24h alert    │ Scenario │ Due    │
│ Frameworks   │ 72h report   │ Testing  │ Dilig. │
│ Controls     │ 1mo final    │ TLPT     │ Exit   │
└──────────────┴──────────────┴──────────┴────────┘
```

### 1. 🛡️ ICT Risk Management
A documented, board-approved framework for identifying, protecting, detecting, responding, and recovering from ICT risks.

### 2. 🚨 Incident Reporting (The Clock is Ticking)
| Timeline | What You Must Do |
|----------|------------------|
| **24 hours** ⏰ | Initial notification of a major incident |
| **72 hours** 📋 | Detailed incident report |
| **1 month** 📁 | Final root cause analysis and remediation report |

> ⚠️ **Miss the deadline = regulatory penalty.** No "we're still investigating" excuses.

### 3. 🧪 Resilience Testing
Regular testing of your digital defenses — from vulnerability scans to full **Threat-Led Penetration Testing (TLPT)** for significant entities.

### 4. 🤝 Third-Party Risk Management
You're responsible for your **ICT vendors**. Contracts must include:
- Service level descriptions
- Security requirements
- Audit rights
- **Exit strategies** (no vendor lock-in allowed)

### 5. 🌐 Information Sharing
Voluntary sharing of cyber threat intelligence between financial entities to strengthen collective defense.

---

## 🔗 Control Connections: Mapping DORA to ISO 27001

DORA and ISO 27001 are **not competitors** — they're **allies**. DORA sets the *legal requirement*; ISO 27001 provides the *management system* to achieve it.

### How the Connection Works

```
┌─────────────────────────────────────────────────────────────┐
│              DORA REQUIREMENTS                              │
│                                                             │
│  ICT Risk Mgmt  ──────────────────────────────────────┐     │
│  Incident Reporting  ──────────────────────────────────┤     │
│  Resilience Testing  ──────────────────────────────────┤     │
│  Third-Party Risk  ────────────────────────────────────┤     │
│                                                         │     │
│                    ▼         ▼         ▼                │     │
│              ┌─────────────────────────────────────┐    │     │
│              │       ISO 27001 CONTROLS            │    │     │
│              │  A.5.7  A.5.23  A.8.16  A.5.24 ...  │    │     │
│              └─────────────────────────────────────┘    │     │
└─────────────────────────────────────────────────────────────┘
```

### 📌 DORA — ICT Risk Management → ISO 27001 Clauses 4–6

| DORA Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Governance & framework** | **Clause 5 — Leadership** — top management must approve and support the ISMS |
| **Risk identification** | **Clause 6.1.2 — Risk Assessment** — identify assets, threats, vulnerabilities |
| **Risk treatment** | **Clause 6.1.3 — Risk Treatment** — select controls from Annex A |
| **Documentation** | **Clause 7.5 — Documented Information** — everything must be recorded |

**Why this matters:** DORA requires a **board-level approved framework**. ISO 27001 Clause 5 gives you the structure to make that happen — not just a policy PDF, but a living management system.

**Examples of connection in practice:**
- You define an ICT risk appetite → this becomes your **ISMS scope** (Clause 4.3)
- You identify critical business functions → this feeds your **risk assessment** (Clause 6.1.2)
- You implement controls → these are your **risk treatment decisions** (Clause 6.1.3)

---

### 📌 DORA — Incident Reporting → ISO 27001 A.5.24 & Clause 9

| DORA Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Incident management plan** | **A.5.24 — Incident Management Planning** — documented roles, comms, escalation |
| **Detection & monitoring** | **A.8.16 — Monitoring Activities** — logs, SIEM, alerts |
| **Reporting timelines** | **Clause 9.1.1 — Monitoring & Measurement** — track and measure performance |
| **Post-incident review** | **Clause 10 — Improvement** — corrective actions and lessons learned |

**Why this matters:** DORA's **24h/72h/1month** deadlines require you to have a **mature incident response process**. ISO 27001's A.5.24 gives you the *plan*; DORA gives you the *deadline*.

**Examples of connection in practice:**
- You build an incident response plan → **A.5.24**
- You detect an anomaly via SIEM → **A.8.16**
- You report to the regulator in 24h → **Clause 9.1.1** (measurement of response time)
- You review and improve after the incident → **Clause 10**

---

### 📌 DORA — Resilience Testing → ISO 27001 A.8.8 & Clause 9

| DORA Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Vulnerability management** | **A.8.8 — Management of Technical Vulnerabilities** — scan, assess, patch |
| **Testing programs** | **Clause 9.1.1 — Monitoring & Measurement** — evaluate security effectiveness |
| **Threat-Led Pen Testing (TLPT)** | **A.8.29 — Security Testing in Development** + **A.8.16** monitoring |
| **Continuous improvement** | **Clause 10 — Improvement** — act on test findings |

**Why this matters:** DORA requires **evidence of resilience**, not just claims. ISO 27001's testing controls (A.8.8, A.8.29) give you the technical foundation, while Clause 9 provides the measurement framework.

**Examples of connection in practice:**
- You run quarterly vulnerability scans → **A.8.8**
- You perform TLPT on critical systems → **A.8.29 + A.8.16**
- You track remediation time → **Clause 9.1.1**
- You update controls based on findings → **Clause 10**

---

### 📌 DORA — Third-Party Risk → ISO 27001 A.5.19 & A.5.23

| DORA Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Due diligence** | **A.5.19 — Information Security in Supplier Relationships** — assess vendor security |
| **Contract requirements** | **A.5.20 — Addressing Security in Supplier Agreements** — legal clauses |
| **Cloud services** | **A.5.23 — Cloud Security** — lifecycle management |
| **Exit strategies** | **A.5.19 + A.5.23** — termination and data return |
| **Continuous monitoring** | **Clause 9.1.1 — Monitoring & Measurement** — vendor performance tracking |

**Why this matters:** DORA makes **you responsible** for your vendors. ISO 27001's supplier controls (A.5.19–A.5.23) give you the **framework to manage that responsibility** — from due diligence to exit.

**Examples of connection in practice:**
- You assess a new cloud provider → **A.5.19**
- You sign a contract with security clauses → **A.5.20**
- You monitor the provider's security posture → **A.5.23 + Clause 9.1.1**
- You plan for contract termination → **A.5.19 exit strategy**

---

### 🧩 The Pattern: Every DORA Pillar Connects

| DORA Pillar | Primary ISO 27001 Connections |
|-------------|-------------------------------|
| **ICT Risk Management** | Clauses 4–6, A.5.7, A.8.16 |
| **Incident Reporting** | A.5.24, A.8.16, Clause 9.1.1, Clause 10 |
| **Resilience Testing** | A.8.8, A.8.29, Clause 9.1.1, Clause 10 |
| **Third-Party Risk** | A.5.19, A.5.20, A.5.23, Clause 9.1.1 |
| **Information Sharing** | A.5.7 — Threat Intelligence |

> 💡 **The takeaway:** DORA is the **legal obligation**. ISO 27001 is the **management system** that proves you're meeting it. Together, they're a powerhouse.

---

## DORA vs ISO 27001 — Quick Comparison ⚖️

| Aspect | DORA 🇪🇺 | ISO 27001 🌍 |
|--------|---------|--------------|
| **Type** | Regulation (law) | Standard (voluntary) |
| **Scope** | EU financial sector | Any organization |
| **Enforcement** | Regulators, fines | Certification bodies |
| **Incident Timelines** | 24h / 72h / 1 month | Not prescribed |
| **Testing** | Mandatory TLPT | Risk-based |
| **Third-Party** | Contractual requirements | Supplier controls |
| **Certification** | No | Yes |

> 🤝 **Best practice:** Use ISO 27001 as your ISMS backbone, then map DORA requirements onto it. One system, two compliance wins.

---

## Curiosities for Cybersecurity Geeks 🤓

### 1. 🇪🇺 Born from Financial Fragility
DORA was created after major ICT outages and cyberattacks exposed how **interconnected** and **fragile** the EU financial system had become. It came into force in **January 2023** and applies from **January 2025**.

### 2. ⏰ The 24-Hour Clock is Brutal
Most regulations give weeks. DORA gives you **one day** to report a major incident. This forced banks to build **real-time detection and response** — not just quarterly reports.

### 3. ☁️ Cloud Providers Are In Scope
For the first time, **Big Tech cloud providers** (AWS, Azure, Google Cloud) can be directly overseen by EU regulators as **critical ICT third-party providers**. This was unthinkable a decade ago.

### 4. 🧪 TLPT Isn't Optional
**Threat-Led Penetration Testing** (TLPT) is mandatory for significant entities. It's not a checkbox — it's a **red team exercise** against live production systems, with regulators watching.

### 5. 🎓 ISO 27001 Certification ≠ DORA Compliance
You can be ISO 27001 certified and **still fail DORA**. Why? DORA has **prescriptive timelines, mandatory testing, and contractual requirements** that ISO 27001 doesn't enforce.

---

## Quick Reference 📌

| Term | Meaning |
|------|---------|
| **DORA** | Digital Operational Resilience Act |
| **ICT** | Information and Communication Technology |
| **TLPT** | Threat-Led Penetration Testing |
| **ICT Third-Party** | Cloud, SaaS, data center providers |
| **Major Incident** | Significant disruption requiring regulatory report |
| **Exit Strategy** | Plan for terminating vendor contracts safely |

---

## Study Questions 📝

1. What does DORA stand for?
2. What are the three incident reporting timelines?
3. Which ISO 27001 control maps to DORA's incident management requirement?
4. What is TLPT and who must perform it?
5. Can you be ISO 27001 certified and still fail DORA?

<details>
<summary>👉 Click to reveal answers</summary>

1. Digital Operational Resilience Act
2. 24 hours (initial), 72 hours (detailed), 1 month (final)
3. A.5.24 — Incident Management Planning
4. Threat-Led Penetration Testing; significant financial entities
5. Yes — DORA has prescriptive requirements ISO 27001 doesn't enforce

</details>

---

## Further Reading 📚

- 🔗 [DORA Official EU Page](https://www.digital-operational-resilience-act.com/)
- 🔗 [EBA DORA Resources](https://www.eba.europa.eu/)
- 🔗 [ISO/IEC 27001:2022 Official Page](https://www.iso.org/standard/27001)

---

> 💬 *"DORA doesn't ask if you're resilient — it asks you to prove it, on a deadline, with evidence."* 🇪🇺⚡🛡️
