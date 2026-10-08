# EU AI Act for Beginners 🇪🇺

> *"AI is neither good nor evil, but it is a powerful tool — and power needs guardrails."* — Anonymous

**The EU AI Act** (Regulation (EU) 2024/1689) is the **world's first comprehensive AI law** . It's not just about cybersecurity or privacy — it's about ensuring AI is **safe, trustworthy, and respects fundamental rights** .

Think of it as the **rulebook for AI** — who can build it, what it can do, and how it must behave. 🛡️🤖

---

## Are You In Scope? 🎯

**If you provide or deploy AI systems in the EU market, you're in scope — regardless of where your company is based** .

```
┌─────────────────────────────────────────────────┐
│              EU AI ACT SCOPE CHECK              │
├─────────────────────────────────────────────────┤
│  1. AI SYSTEM?   →  Any AI that infers outputs  │
│  2. EU MARKET?   →  Offered or used in the EU   │
│  3. YOUR ROLE?   →  Provider or Deployer        │
│                                                 │
│  ALL THREE = YOU'RE IN SCOPE ✅                 │
└─────────────────────────────────────────────────┘
```

### Who's Who? 👥

| Role | Definition | Example |
|------|------------|---------|
| **Provider** | Develops AI and places it on the market under their name | Company building an AI recruitment tool  |
| **Deployer** | Uses AI developed by others in a professional capacity | Hospital using AI diagnostic tools  |
| **Authorised Representative** | EU-based representative for non-EU providers | Required for non-EU companies  |

> 💡 **Key rule:** If a deployer **significantly modifies** an AI system, they become a **provider** and inherit all provider obligations .

---

## The Risk-Based Approach 🎯

The AI Act uses a **risk pyramid**. The higher the risk, the stricter the rules .

```
┌─────────────────────────────────────────────────┐
│              AI ACT RISK PYRAMID                │
├─────────────────────────────────────────────────┤
│  🔴 UNACCEPTABLE  →  BANNED COMPLETELY          │
│                                                 │
│  🟠 HIGH-RISK     →  STRICT REQUIREMENTS        │
│                                                 │
│  🟡 LIMITED-RISK  →  TRANSPARENCY OBLIGATIONS   │
│                                                 │
│  🟢 MINIMAL RISK  →  NO OBLIGATIONS (~85%)      │
└─────────────────────────────────────────────────┘
```

### 🔴 Tier 1: Unacceptable Risk — Prohibited (Article 5)

**Banned outright from the EU market.** These AI practices violate fundamental rights .

| Banned Practice | Why It's Banned |
|-----------------|-----------------|
| **Subliminal manipulation** | Distorts behaviour without user awareness  |
| **Exploiting vulnerabilities** | Targets age, disability, socioeconomic situation  |
| **Social scoring** | Classifies people based on behaviour, affecting opportunities  |
| **Predictive policing** | Profiles individuals for criminal activity  |
| **Untargeted facial scraping** | Building databases from internet/CCTV images  |
| **Workplace/school emotion AI** | Reading emotions (except medical/safety)  |
| **Biometric categorisation** | Inferring race, religion, sexual orientation  |
| **Real-time remote biometric ID** | Law enforcement in public spaces (limited exceptions)  |

> ⏰ **Prohibitions effective:** 2 February 2025 

---

### 🟠 Tier 2: High-Risk AI (Articles 6–27)

**Significant risks to health, safety, or fundamental rights.** Heavy compliance requirements .

**Two classification tracks:**

| Track | What It Covers | Deadline |
|-------|----------------|----------|
| **Track A** | AI as safety component in regulated products (medical devices, vehicles, toys) | 2 August 2028  |
| **Track B** | AI in 8 sensitive areas (Annex III) | 2 December 2027  |

**Annex III High-Risk Areas:**

| Area | Examples |
|------|----------|
| **Biometrics** | Remote identification, emotion recognition |
| **Critical Infrastructure** | Energy, water, transport systems |
| **Education** | Admissions, grading, exam monitoring |
| **Employment** | Recruitment, performance evaluation, termination |
| **Essential Services** | Credit scoring, welfare eligibility, emergency triage |
| **Law Enforcement** | Profiling, evidence evaluation, recidivism risk |
| **Migration/Border** | Asylum processing, document verification |
| **Justice/Democracy** | Judicial research, election influence |

**Provider Obligations for High-Risk AI** :

| Requirement | What You Must Do |
|-------------|------------------|
| **Risk Management (Art. 9)** | Continuous, lifecycle-spanning risk identification and mitigation |
| **Data Governance (Art. 10)** | Training data must be relevant, representative, bias-checked |
| **Technical Documentation (Art. 11)** | Comprehensive docs, retained 10 years |
| **Automatic Logging (Art. 12)** | Event logs enabling traceability |
| **Transparency (Art. 13)** | Clear info to deployers on capabilities and limitations |
| **Human Oversight (Art. 14)** | Humans can understand, monitor, override, halt the system |
| **Accuracy & Cybersecurity (Art. 15)** | Declared metrics; resilience to adversarial attacks |
| **Quality Management (Art. 17)** | Lifecycle-spanning documented quality processes |
| **Conformity Assessment (Art. 43)** | Self-assessment for most; third-party audit for biometrics |

---

### 🟡 Tier 3: Limited Risk — Transparency (Article 50)

**Light obligations. Mainly disclosure** .

| AI System | Obligation |
|-----------|------------|
| **Chatbots** | Must inform users they're talking to AI |
| **Deepfakes** | Must label content as AI-generated |
| **Emotion Recognition** | Must disclose its use |
| **Biometric Categorisation** | Must disclose its use |
| **Synthetic Content** | Must mark outputs as machine-readable AI-generated |

> ⏰ **Transparency effective:** 2 August 2026 

---

### 🟢 Tier 4: Minimal Risk — No Obligations

**~85% of AI systems fall here.** Spam filters, AI in video games, basic recommendation engines .

No compliance requirements. Free to use.

---

## Special Category: General-Purpose AI (GPAI)

**GPAI models** (like large language models) have **dedicated rules** because they can be integrated into many downstream systems .

```
┌─────────────────────────────────────────────────┐
│              GPAI MODEL OBLIGATIONS             │
├─────────────────────────────────────────────────┤
│  📄 Technical documentation                     │
│  📢 Transparency to downstream providers         │
│  📚 Copyright compliance policies               │
│  🌐 Public disclosure of training data summaries│
│  👤 Authorised representative (non-EU)          │
└─────────────────────────────────────────────────┘
```

**Systemic Risk GPAI:** Models trained with **>10²⁵ FLOPs** are presumed to have systemic risk .

**Enhanced obligations for systemic-risk GPAI:**
- Model evaluations and adversarial testing
- Systemic risk identification and mitigation
- Serious incident reporting
- Cybersecurity safeguards

> ⏰ **GPAI obligations effective:** 2 August 2025 

---

## 🔗 Control Connections: Mapping EU AI Act to ISO 27001 & ISO 42001

The AI Act and ISO standards are **not competitors** — they're **allies**. The AI Act sets the **legal requirement**; ISO 27001 and **ISO/IEC 42001** provide the **management systems** to achieve it .

### How the Connection Works

```
┌─────────────────────────────────────────────────────────────┐
│              EU AI ACT REQUIREMENTS                         │
│                                                             │
│  Risk Management  ─────────────────────────────────────┐    │
│  Data Governance  ─────────────────────────────────────┤    │
│  Technical Docs  ──────────────────────────────────────┤    │
│  Human Oversight  ─────────────────────────────────────┤    │
│  Cybersecurity  ───────────────────────────────────────┤    │
│                                                         │    │
│                    ▼         ▼         ▼                │    │
│              ┌─────────────────────────────────────┐    │    │
│              │    ISO 27001 + ISO 42001 CONTROLS   │    │    │
│              │  A.8.24  A.5.15  A.8.25  Clause 6...│    │    │
│              └─────────────────────────────────────┘    │    │
└─────────────────────────────────────────────────────────────┘
```

### 📌 AI Act Art. 9 — Risk Management → ISO 27001 Clause 6

| AI Act Requirement | ISO 27001 Connection |
|--------------------|----------------------|
| **Risk identification** | **Clause 6.1.2** — Risk assessment |
| **Risk evaluation** | **Clause 6.1.2** — Analyse and evaluate risks |
| **Risk treatment** | **Clause 6.1.3** — Select and implement controls |
| **Continuous risk management** | **Clause 8.2** — Operational risk assessments |

**Why this matters:** The AI Act requires **continuous risk management** across the AI lifecycle. ISO 27001's risk framework gives you the structure to do it systematically .

**Examples of connection in practice:**
- You identify AI risks → **Clause 6.1.2**
- You select controls → **Clause 6.1.3**
- You monitor risks continuously → **Clause 8.2**

---

### 📌 AI Act Art. 10 — Data Governance → ISO 27001 A.5.34, A.8.24

| AI Act Requirement | ISO 27001 Connection |
|--------------------|----------------------|
| **Training data quality** | **A.5.34** — Privacy and protection of PII |
| **Bias examination** | **Clause 6.1.2** — Risk assessment (bias as risk) |
| **Data relevance** | **A.5.34** — Data quality controls |
| **Data security** | **A.8.24** — Cryptography for data protection |

**Why this matters:** The AI Act requires **representative, error-free, bias-checked training data** . ISO 27001's privacy and data controls give you the foundation for data governance .

**Examples of connection in practice:**
- You document data sources → **A.5.34**
- You assess bias risks → **Clause 6.1.2**
- You encrypt training data → **A.8.24**

---

### 📌 AI Act Art. 15 — Cybersecurity → ISO 27001 A.8.8, A.8.16, A.8.25

| AI Act Requirement | ISO 27001 Connection |
|--------------------|----------------------|
| **Resilience to attacks** | **A.8.8** — Technical vulnerability management |
| **Adversarial robustness** | **A.8.25** — Secure development lifecycle |
| **Incident detection** | **A.8.16** — Monitoring activities |
| **Model poisoning protection** | **A.8.25** — Secure development |
| **Data poisoning protection** | **A.5.34** — Data quality controls |

**Why this matters:** AI systems face **AI-specific threats** — data poisoning, model poisoning, adversarial examples . ISO 27001's security controls provide the foundation, but AI-specific extensions are needed .

**Examples of connection in practice:**
- You test for adversarial attacks → **A.8.8**
- You monitor model behaviour → **A.8.16**
- You secure the model lifecycle → **A.8.25**

---

### 📌 AI Act Art. 14 — Human Oversight → ISO 27001 Clause 5, A.5.15

| AI Act Requirement | ISO 27001 Connection |
|--------------------|----------------------|
| **Human oversight design** | **Clause 5** — Leadership and governance |
| **Override capability** | **A.5.15** — Access control (who can override) |
| **Monitoring by humans** | **A.8.16** — Monitoring activities |
| **Accountability** | **Clause 5.3** — Roles and responsibilities |

**Why this matters:** The AI Act requires **meaningful human oversight** — not just a checkbox . ISO 27001's governance and access controls give you the structure to enforce it.

**Examples of connection in practice:**
- You define who can override AI → **A.5.15**
- You establish oversight roles → **Clause 5.3**
- You monitor human-AI interaction → **A.8.16**

---

### 🧩 The Pattern: Every AI Act Requirement Connects

| AI Act Requirement | Primary ISO 27001 Connections |
|--------------------|-------------------------------|
| **Risk Management (Art. 9)** | Clauses 6.1.2, 6.1.3, 8.2 |
| **Data Governance (Art. 10)** | A.5.34, A.8.24 |
| **Technical Documentation (Art. 11)** | Clause 7.5 — Documented information |
| **Logging (Art. 12)** | A.8.15 — Logging |
| **Transparency (Art. 13)** | A.5.34 — Privacy controls |
| **Human Oversight (Art. 14)** | Clause 5, A.5.15, A.8.16 |
| **Cybersecurity (Art. 15)** | A.8.8, A.8.16, A.8.25 |
| **Quality Management (Art. 17)** | Clause 9, 10 — Performance & Improvement |

> 💡 **The takeaway:** The AI Act is the **legal obligation**. ISO 27001 + **ISO/IEC 42001** (AI Management System) are the **management systems** that prove you're meeting it .

---

## AI Act vs GDPR vs NIS2 — Quick Comparison ⚖️

| Aspect | EU AI Act 🇪🇺 | GDPR 🇪🇺 | NIS2 🇪🇺 |
|--------|--------------|---------|---------|
| **Type** | Regulation | Regulation | Directive |
| **Focus** | AI safety & rights | Personal data privacy | Critical sector cybersecurity |
| **Scope** | AI providers & deployers | Anyone processing EU data | 18 critical sectors |
| **Risk Approach** | 4-tier pyramid | Principles-based | Entity classification |
| **Fines** | €35M or 7% turnover | €20M or 4% turnover | €10M or 2% turnover |
| **Timeline** | Progressive (2025-2028) | Immediate (2018) | National implementation |

> 🤝 **Best practice:** Use ISO 27001 as your ISMS backbone, add **ISO 42001** for AI governance, then map AI Act (and GDPR/NIS2 if applicable) requirements onto it. One system, multiple compliance wins .

---

## Curiosities for Cybersecurity Geeks 🤓

### 1. 🌍 First of Its Kind
The EU AI Act is the **first comprehensive AI law in the world**. It can set a **global standard** for AI regulation, similar to how GDPR influenced privacy laws worldwide .

### 2. 💰 The €35M Fine
AI Act fines can reach **€35 million or 7% of global annual turnover** — the **highest** among EU digital regulations .

### 3. 📊 85% Unregulated
When the AI Act was proposed, it was estimated that **85% of AI systems** would fall into the minimal-risk category — no obligations .

### 4. ⏰ The Timeline Shuffle
High-risk AI obligations were originally set for **2 August 2026**. The "AI Omnibus" pushed them to **2 December 2027** (Annex III) and **2 August 2028** (Annex I) .

### 5. 🤖 GPAI = The New Frontier
**General-Purpose AI** models (like LLMs) have **dedicated rules** — because they can be integrated into countless downstream systems, creating **systemic risk** .

### 6. 🎓 ISO 27001 Certification ≠ AI Act Compliance
You can be ISO 27001 certified and **still fail the AI Act**. Why? The AI Act has **AI-specific requirements** — training data governance, human oversight design, adversarial testing — that ISO 27001 doesn't mandate. But **ISO/IEC 42001** bridges that gap .

---

## Quick Reference 📌

| Term | Meaning |
|------|---------|
| **EU AI Act** | Regulation (EU) 2024/1689 |
| **Provider** | Develops and places AI on the market |
| **Deployer** | Uses AI in professional capacity |
| **GPAI** | General-Purpose AI model |
| **Systemic Risk** | Risk from high-impact GPAI capabilities |
| **Annex III** | List of high-risk AI use cases |
| **Conformity Assessment** | Process to demonstrate compliance |
| **AI Omnibus** | 2026 amendments streamlining AI Act rules |

---

## Study Questions 📝

1. What does the EU AI Act regulate?
2. What are the four risk tiers?
3. What is the difference between a provider and a deployer?
4. What are the three main high-risk AI areas?
5. Which ISO standard complements ISO 27001 for AI governance?
6. Can you be ISO 27001 certified and still fail the AI Act?

<details>
<summary>👉 Click to reveal answers</summary>

1. AI systems placed on or used in the EU market
2. Unacceptable (banned), High-Risk, Limited-Risk, Minimal-Risk
3. Provider develops AI; Deployer uses AI developed by others
4. Biometrics, Critical Infrastructure, Education, Employment, Essential Services, Law Enforcement, Migration, Justice (any 3)
5. ISO/IEC 42001 — AI Management System
6. Yes — AI Act has AI-specific requirements ISO 27001 doesn't mandate

</details>

---

## Further Reading 📚

- 🔗 [EU AI Act Official Page](https://artificialintelligenceact.eu/)
- 🔗 [AI Act Service Desk — European Commission](https://ai-act-service-desk.ec.europa.eu/)
- 🔗 [ISO/IEC 42001 — AI Management System](https://www.iso.org/standard/81230.html)
- 🔗 [ISO/IEC 27001:2022 Official Page](https://www.iso.org/standard/27001)

---

> 💬 *"The EU AI Act doesn't ask if your AI is smart — it asks if it's safe, transparent, and respects human dignity. That's a higher bar."* 🇪🇺🤖⚖️
