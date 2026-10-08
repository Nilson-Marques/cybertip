# NIS2 for Beginners 🇪🇺

> *"Security is a shared responsibility — NIS2 makes it a legal one."* — Anonymous

**NIS2** is an **EU directive** covering critical sectors like energy, transport, and health. It's the upgraded version of the original NIS Directive — broader scope, stricter rules, and **personal accountability** for leadership. ⚡

Think of it as the **EU's baseline cybersecurity law** that forces critical organizations to move from "we should probably secure that" to "we must secure that, and here's the evidence." 🛡️

---

## Are You In Scope? 🎯

**If your organization operates in a critical sector and meets size thresholds, yes.**

```
┌─────────────────────────────────────────────────┐
│              NIS2 SCOPE CHECK                   │
├─────────────────────────────────────────────────┤
│  1. SECTOR?    →  Annex I or Annex II          │
│  2. SIZE?      →  Medium or Large enterprise   │
│  3. LOCATION?  →  Operating in the EU          │
│                                                 │
│  ALL THREE = YOU'RE IN SCOPE ✅                 │
└─────────────────────────────────────────────────┘
```

### The Two Annexes

| Annex I — High Criticality 🏦 | Annex II — Other Critical 📦 |
|-------------------------------|------------------------------|
| Energy (electricity, gas, oil, hydrogen) | Postal and courier services |
| Transport (air, rail, water, road) | Waste management |
| Banking and financial markets | Chemicals (production, distribution) |
| Health (hospitals, pharma, devices) | Food (production, processing, distribution) |
| Drinking water and wastewater | Manufacturing (medical devices, electronics, vehicles) |
| Digital infrastructure (cloud, data centers, DNS) | Digital providers (marketplaces, search, social) |
| ICT service management (B2B) | Research organizations |
| Public administration | |
| Space | |

### Size Thresholds 📏

| Entity Type | Employees | Turnover/Balance Sheet | Classification |
|-------------|-----------|------------------------|----------------|
| **Medium** | ≥ 50 | > €10M | Important |
| **Large** | > 250 | > €50M turnover + > €43M balance | Essential |

> ⚠️ **Exceptions:** Some entities are **automatically in scope** regardless of size — trust service providers, TLD registries, DNS providers, and public electronic communications providers .

---

## Key Measures (Article 21) 🔑

Article 21 defines **minimum cybersecurity risk management measures**. These are the **"what"** — not the "how." You decide the implementation; you must achieve the objective .

```
┌─────────────────────────────────────────────────┐
│         ARTICLE 21 — 10 CORE MEASURES           │
├─────────────────────────────────────────────────┤
│  (a) Risk analysis policies                     │
│  (b) Incident handling                          │
│  (c) Business continuity                        │
│  (d) Supply chain security                      │
│  (e) Secure acquisition & development           │
│  (f) Effectiveness assessment                   │
│  (g) Cyber hygiene & training                   │
│  (h) Cryptography policies                      │
│  (i) HR security, access control, asset mgmt    │
│  (j) MFA, secure communications                 │
└─────────────────────────────────────────────────┘
```

### 1. 📋 Risk Analysis Policies (Article 21a)
Documented policies for analyzing risks to your network and information systems. This is the **foundation** — everything else flows from here.

### 2. 🚨 Incident Handling (Article 21b)
Processes for detecting, responding to, and reporting incidents. NIS2 has **strict reporting timelines**:

| Timeline | Action | Who |
|----------|--------|-----|
| **24 hours** ⏰ | Early warning | CSIRT or competent authority |
| **72 hours** 📋 | Detailed incident notification | CSIRT or competent authority |
| **1 month** 📁 | Final report | CSIRT or competent authority |

> ⚠️ **Miss the deadline = fines.** Essential entities face up to **€10M or 2% of global turnover** .

### 3. 🔄 Business Continuity (Article 21c)
Backup management, disaster recovery, and crisis management. Your systems must **survive and recover** from disruption.

### 4. 🔗 Supply Chain Security (Article 21d)
Security requirements for your **direct suppliers and service providers**. You can't outsource your responsibility.

### 5. 💻 Secure Acquisition & Development (Article 21e)
Security in acquiring, developing, and maintaining network and information systems — including **vulnerability handling and disclosure**.

### 6. 📊 Effectiveness Assessment (Article 21f)
Policies and procedures to **measure whether your controls actually work**. Not just "we did it" — but "we proved it works."

### 7. 🧼 Cyber Hygiene & Training (Article 21g)
Basic security practices and **cybersecurity training** for staff. The human firewall.

### 8. 🔐 Cryptography Policies (Article 21h)
Policies for using encryption and cryptographic controls.

### 9. 👥 HR Security, Access Control, Asset Management (Article 21i)
People, permissions, and inventory. Who has access to what, and what assets do you have?

### 10. 📱 MFA & Secure Communications (Article 21j)
**Multi-factor authentication**, secure voice/video/text communications, and secure emergency communication systems.

---

## 🔗 Control Connections: Mapping Article 21 to ISO 27001

NIS2 Article 21 and ISO 27001 are **not competitors** — they're **allies**. NIS2 sets the **legal requirement**; ISO 27001 provides the **management system** to achieve it .

### How the Connection Works

```
┌─────────────────────────────────────────────────────────────┐
│              NIS2 ARTICLE 21 REQUIREMENTS                   │
│                                                             │
│  (a) Risk Analysis  ───────────────────────────────────┐    │
│  (b) Incident Handling  ───────────────────────────────┤    │
│  (c) Business Continuity  ─────────────────────────────┤    │
│  (d) Supply Chain  ────────────────────────────────────┤    │
│  (j) MFA & Comms  ─────────────────────────────────────┤    │
│                                                         │    │
│                    ▼         ▼         ▼                │    │
│              ┌─────────────────────────────────────┐    │    │
│              │       ISO 27001 CONTROLS            │    │    │
│              │  A.5.1  A.5.24  A.5.29  A.5.19 ...  │    │    │
│              └─────────────────────────────────────┘    │    │
└─────────────────────────────────────────────────────────────┘
```

### 📌 NIS2 (a) Risk Analysis → ISO 27001 Clauses 5, 6, 8

| NIS2 Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Information security policy** | **Clause 5.2** — Top management must establish policy |
| **Risk assessment process** | **Clause 6.1.2** — Define and apply risk assessment |
| **Risk treatment process** | **Clause 6.1.3** — Select and implement controls |
| **Operational risk assessment** | **Clause 8.2** — Perform assessments at planned intervals |
| **Policy for information security** | **A.5.1** — Documented policy approved by management |

**Why this matters:** NIS2 requires **board-approved** risk policies. ISO 27001 Clause 5 gives you the framework to make that happen — not just a document, but a living system .

**Examples of connection in practice:**
- You define risk appetite → this becomes your **ISMS scope** (Clause 4.3)
- You identify critical assets → this feeds your **risk assessment** (Clause 6.1.2)
- You implement controls → these are your **risk treatment decisions** (Clause 6.1.3)

---

### 📌 NIS2 (b) Incident Handling → ISO 27001 A.5.24–A.5.28

| NIS2 Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Incident management planning** | **A.5.24** — Roles, responsibilities, processes |
| **Event assessment** | **A.5.25** — Decide if an event is an incident |
| **Incident response** | **A.5.26** — Respond according to procedures |
| **Learning from incidents** | **A.5.27** — Post-incident review and improvement |
| **Evidence collection** | **A.5.28** — Preserve forensic evidence |
| **Event reporting** | **A.6.8** — Report security events |
| **Detection & monitoring** | **A.8.16** — Logs, SIEM, alerts |

**Why this matters:** NIS2's **24h/72h/1month** deadlines require a mature incident response process. ISO 27001's incident controls (A.5.24–A.5.28) give you the *plan*; NIS2 gives you the *deadline* .

**Examples of connection in practice:**
- You build an incident response plan → **A.5.24**
- You detect an anomaly via SIEM → **A.8.16**
- You report to the CSIRT in 24h → **A.5.26 + A.6.8**
- You review and improve after the incident → **A.5.27**

---

### 📌 NIS2 (c) Business Continuity → ISO 27001 A.5.29, A.5.30, A.8.13, A.8.14

| NIS2 Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **ICT readiness for continuity** | **A.5.30** — Plan for business continuity |
| **Security during disruption** | **A.5.29** — Maintain security during incidents |
| **Backup management** | **A.8.13** — Information backup |
| **Redundancy** | **A.8.14** — Redundant processing facilities |
| **Logging** | **A.8.15** — Logging for detection and recovery |

**Why this matters:** NIS2 requires that you **maintain services to critical sectors** even during major incidents. ISO 27001's continuity controls (A.5.29–A.5.30) give you the structure to plan, test, and improve .

**Examples of connection in practice:**
- You create a business continuity plan → **A.5.30**
- You implement redundant systems → **A.8.14**
- You test backup restoration → **A.8.13**
- You maintain security during recovery → **A.5.29**

---

### 📌 NIS2 (d) Supply Chain Security → ISO 27001 A.5.19–A.5.23

| NIS2 Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Supplier security** | **A.5.19** — Information security in supplier relationships |
| **Contract requirements** | **A.5.20** — Security clauses in supplier agreements |
| **ICT supply chain** | **A.5.21** — Manage security in the ICT supply chain |
| **Supplier monitoring** | **A.5.22** — Monitor, review, and change management |
| **Cloud services** | **A.5.23** — Lifecycle management for cloud services |

**Why this matters:** NIS2 makes **you responsible** for your vendors. ISO 27001's supplier controls (A.5.19–A.5.23) give you the **framework to manage that responsibility** — from due diligence to exit .

**Examples of connection in practice:**
- You assess a new cloud provider → **A.5.19**
- You sign a contract with security clauses → **A.5.20**
- You monitor the provider's security posture → **A.5.22 + A.5.23**
- You plan for contract termination → **A.5.19 exit strategy**

---

### 📌 NIS2 (j) MFA & Secure Communications → ISO 27001 A.5.14, A.8.3, A.8.24

| NIS2 Requirement | ISO 27001 Connection |
|------------------|----------------------|
| **Multi-factor authentication** | **A.8.3** — Information access restriction |
| **Secure communications** | **A.5.14** — Information transfer |
| **Cryptography policies** | **A.8.24** — Use of cryptography |
| **Access control** | **A.5.15** — Access control policy |

**Why this matters:** NIS2 explicitly requires **MFA** and **secure voice/video/text communications**. ISO 27001's access and cryptography controls (A.8.3, A.5.14, A.8.24) give you the technical foundation .

**Examples of connection in practice:**
- You enforce MFA for all users → **A.8.3**
- You encrypt email and messaging → **A.5.14 + A.8.24**
- You define access control policy → **A.5.15**

---

### 🧩 The Pattern: Every NIS2 Measure Connects

| NIS2 Article 21 Measure | Primary ISO 27001 Connections |
|-------------------------|-------------------------------|
| **(a) Risk Analysis** | Clauses 5.2, 6.1.2, 6.1.3, 8.2, 8.3, A.5.1 |
| **(b) Incident Handling** | A.5.24–A.5.28, A.6.8, A.8.16 |
| **(c) Business Continuity** | A.5.29, A.5.30, A.8.13, A.8.14, A.8.15 |
| **(d) Supply Chain Security** | A.5.19–A.5.23 |
| **(e) Secure Development** | A.8.8, A.8.19, A.8.25–A.8.32 |
| **(f) Effectiveness Assessment** | Clauses 9.1, 9.2, 9.3, A.5.35, A.5.36 |
| **(g) Cyber Hygiene & Training** | A.6.3, A.5, A.6, A.7, A.8 controls |
| **(h) Cryptography** | A.8.24 |
| **(i) HR, Access, Assets** | A.5, A.6, A.8 controls |
| **(j) MFA & Communications** | A.5.14, A.5.42, A.8.3, A.8.24 |

> 💡 **The takeaway:** NIS2 is the **legal obligation**. ISO 27001 is the **management system** that proves you're meeting it. One system, two compliance wins .

---

## NIS2 vs DORA — Quick Comparison ⚖️

| Aspect | NIS2 🇪🇺 | DORA 🇪🇺 |
|--------|---------|---------|
| **Type** | Directive (national law) | Regulation (direct EU law) |
| **Scope** | 18 critical sectors | Financial sector only |
| **Sectors** | Energy, transport, health, digital, etc. | Banks, insurers, investment firms |
| **Incident Reporting** | 24h / 72h / 1 month | 24h / 72h / 1 month |
| **Fines** | €10M or 2% (essential) | National law determines |
| **Relationship** | General framework | *Lex specialis* for finance |

> 🤝 **Best practice:** Use ISO 27001 as your ISMS backbone, then map NIS2 (and DORA if applicable) requirements onto it. One system, multiple compliance wins .

---

## Curiosities for Cybersecurity Geeks 🤓

### 1. 🇪🇺 Born from NIS1's Gaps
NIS2 replaces the original **NIS Directive (2016)**. NIS1 was criticized for being too vague, too narrow, and lacking enforcement. NIS2 fixed all three — broader scope, clearer requirements, **real fines** .

### 2. ⏰ The 24-Hour Clock is Brutal
Most regulations give weeks. NIS2 gives you **one day** for an early warning. This forced organizations to build **real-time detection and response** — not just quarterly reports .

### 3. 👔 Executives Are Personally Liable
NIS2 requires **management body approval** of cybersecurity measures and **personal accountability**. In some Member States, executives can be **disqualified** or face personal fines for non-compliance .

### 4. 📏 18 Sectors, Two Annexes
NIS2 covers **18 sectors** across two annexes. Annex I (high criticality) gets stricter oversight; Annex II (other critical) gets lighter supervision. But both face **the same Article 21 measures** .

### 5. 🔐 MFA Isn't Optional
NIS2 is one of the first EU regulations to **explicitly require** multi-factor authentication. No "we'll get to it eventually" — it's a legal requirement .

### 6. 🎓 ISO 27001 Certification ≠ NIS2 Compliance
You can be ISO 27001 certified and **still fail NIS2**. Why? NIS2 has **prescriptive timelines, mandatory MFA, and explicit supply chain requirements** that ISO 27001 doesn't enforce. But ISO 27001 gives you **80% of the foundation** .

---

## Quick Reference 📌

| Term | Meaning |
|------|---------|
| **NIS2** | Network and Information Security Directive 2 |
| **Essential Entity** | Large enterprise in Annex I — strictest oversight |
| **Important Entity** | Medium enterprise or Annex II — lighter oversight |
| **CSIRT** | Computer Security Incident Response Team |
| **Article 21** | 10 minimum cybersecurity measures |
| **Article 20** | Governance — board approval required |
| **MFA** | Multi-Factor Authentication — explicitly required |

---

## Study Questions 📝

1. What does NIS2 stand for?
2. What are the size thresholds for medium and large entities?
3. How many core measures are in Article 21?
4. What are the three incident reporting timelines?
5. Which ISO 27001 control maps to NIS2's incident handling requirement?
6. Can you be ISO 27001 certified and still fail NIS2?

<details>
<summary>👉 Click to reveal answers</summary>

1. Network and Information Security Directive 2
2. Medium: ≥50 employees or >€10M; Large: >250 employees or >€50M turnover + >€43M balance
3. 10 (a through j)
4. 24 hours (early warning), 72 hours (detailed), 1 month (final)
5. A.5.24 — Incident Management Planning
6. Yes — NIS2 has prescriptive requirements ISO 27001 doesn't enforce

</details>

---

## Further Reading 📚

- 🔗 [NIS2 Directive Official Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32022L2555)
- 🔗 [ENISA NIS2 Technical Guidance](https://www.enisa.europa.eu/publications/nis2-technical-implementation-guidance)
- 🔗 [BSI NIS2 to ISO 27001 Mapping Tool](https://www.bsigroup.com/globalassets/localfiles/fr-fr/iso-27001/nis-brochure/bsi-ce-nis2-mapping-tool-25-fr.pdf)

---

> 💬 *"NIS2 doesn't ask if you're secure — it asks you to prove it, on a deadline, with board-level accountability."* 🇪🇺⚡🛡️
