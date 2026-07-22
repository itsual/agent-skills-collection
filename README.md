# Agent Skills Collection

**A comprehensive, production-ready collection of high-quality Agent Skills** for Claude, Codex, Cursor, Gemini CLI, and other AI coding agents.

Built following the [Anthropic Agent Skills standard](https://github.com/anthropics/skills) with best practices from leading open collections.

> **Goal**: 500+ modular, battle-tested skills organized by domain, with strong verification steps, clear triggering descriptions, and progressive disclosure.

## Current Status

**Phase 1 – Engineering & Software Development** ✅ (85 skills)  
**Phase 2 – Document Production** ✅ (43 skills)  
**Phase 3 – Product Management** ✅ (36 skills)  
**Phase 4 – Design & UX** ✅ (46 skills)  
**Phase 5 – Marketing & Growth** ✅ (24 skills)  
**Phase 6 – Sales** ✅ (24 skills)  
**Phase 7 – Finance** ✅ (60 skills)  
**Phase 8 – Research** ✅ (24 skills)  
**Phase 9 – Compliance** 🚀 (24 skills)  
**Skills added so far**: **368** (2 Meta + 85 Engineering + 43 Document Production + 36 Product Management + 46 Design & UX + 24 Marketing & Growth + 24 Sales + 60 Finance + 24 Research + 24 Compliance)

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 🛡️ Compliance (24 skills)

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 📜 | **regulatory-compliance** | Map obligations to controls, owners, and evidence | [View](skills/compliance/regulatory-compliance/) |
| 📄 | **policy-management** | Policy lifecycle — create, approve, communicate, maintain | [View](skills/compliance/policy-management/) |
| 🎯 | **compliance-risk-assessment** | Rank compliance risk and prioritize remediation | [View](skills/compliance/compliance-risk-assessment/) |
| 🔒 | **data-privacy-compliance** | Lawful processing, rights, retention, transfers | [View](skills/compliance/data-privacy-compliance/) |
| 🏦 | **aml-kyc-basics** | CDD/EDD, monitoring, suspicious activity escalation | [View](skills/compliance/aml-kyc-basics/) |
| 🔐 | **information-security-compliance** | Security controls mapped to compliance evidence | [View](skills/compliance/information-security-compliance/) |
| 📊 | **sox-and-financial-controls** | ICFR/SOX-style control design, testing, deficiencies | [View](skills/compliance/sox-and-financial-controls/) |
| 🔍 | **compliance-monitoring** | Testing programs that verify controls in practice | [View](skills/compliance/compliance-monitoring/) |
| 🤝 | **third-party-risk-compliance** | Vendor diligence, contracts, and ongoing oversight | [View](skills/compliance/third-party-risk-compliance/) |
| 📡 | **regulatory-change-management** | Horizon scan, impact, implement before effective dates | [View](skills/compliance/regulatory-change-management/) |
| 🎓 | **compliance-training** | Role-relevant training that changes behavior | [View](skills/compliance/compliance-training/) |
| ⚖️ | **ethics-and-conduct** | Code of conduct, speak-up, conflicts of interest | [View](skills/compliance/ethics-and-conduct/) |
| 🚫 | **sanctions-screening** | List screening, alert handling, and escalation | [View](skills/compliance/sanctions-screening/) |
| 🧠 | **model-risk-governance** | Model inventory, validation, monitoring, challenge | [View](skills/compliance/model-risk-governance/) |
| 🛡️ | **consumer-protection-compliance** | Fair treatment, disclosures, responsible marketing | [View](skills/compliance/consumer-protection-compliance/) |
| 📁 | **records-management** | Retention, holds, findability, and disposition | [View](skills/compliance/records-management/) |
| 📋 | **regulatory-exam-management** | Exam prep, requests, fieldwork, remediation | [View](skills/compliance/regulatory-exam-management/) |
| 🤖 | **ai-model-compliance** | AI decision governance, fairness, oversight | [View](skills/compliance/ai-model-compliance/) |
| 🚨 | **incident-breach-notification** | Breach assessment and regulatory notification clocks | [View](skills/compliance/incident-breach-notification/) |
| 📨 | **complaints-handling** | Regulated complaints logging, resolution, themes | [View](skills/compliance/complaints-handling/) |
| ⚠️ | **conduct-risk** | Customer harm, incentives, and culture-driven risk | [View](skills/compliance/conduct-risk/) |
| 📑 | **licensing-and-permissions** | Authorization perimeter and conditions tracking | [View](skills/compliance/licensing-and-permissions/) |
| 🏗️ | **operational-resilience-compliance** | Critical services, impact tolerances, scenario tests | [View](skills/compliance/operational-resilience-compliance/) |
| 📢 | **whistleblowing-investigations** | Speak-up investigations with fairness and non-retaliation | [View](skills/compliance/whistleblowing-investigations/) |

### 🔬 Research (24) · 💰 Finance (60) · 🤝 Sales (24) · 📈 Marketing & Growth (24) · 🎨 Design & UX (46) · 📦 Product Management (36) · 📄 Document Production (43) · ⚙️ Engineering (85)

Full catalogs under the respective `skills/` directories.

---

## Repository Structure

```
agent-skills-collection/
├── README.md
├── LICENSE
├── skills/
│   ├── meta/                    # 2
│   ├── engineering/             # 85
│   ├── document-production/     # 43
│   ├── product-management/      # 36
│   ├── design-ux/               # 46
│   ├── marketing-growth/        # 24
│   ├── sales/                   # 24
│   ├── finance/                 # 60
│   ├── research/                # 24
│   ├── compliance/              # 24
│   └── ...
└── packs/
```

## How to Use

```bash
git clone https://github.com/itsual/agent-skills-collection.git
# Copy desired skills into ~/.claude/skills/ (or equivalent)
```

## Roadmap

- [x] Engineering · Document Production · Product Management · Design & UX
- [x] Marketing & Growth · Sales · Finance (60) · Research (24)
- [x] Compliance pack (24 skills) ✅
- [ ] Customer Success, HR, and remaining domains
- [ ] Curated skill packs + evaluation harness

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
