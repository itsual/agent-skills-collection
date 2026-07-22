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
**Phase 9 – Compliance** ✅ (24 skills)  
**Phase 10 – Customer Success** 🚀 (12 skills)  
**Skills added so far**: **380** (2 Meta + 85 Engineering + 43 Document Production + 36 Product Management + 46 Design & UX + 24 Marketing & Growth + 24 Sales + 60 Finance + 24 Research + 24 Compliance + 12 Customer Success)

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 💙 Customer Success (12 skills)

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🎯 | **cs-strategy** | Segmentation, coverage model, and CS outcomes | [View](skills/customer-success/cs-strategy/) |
| 🚀 | **onboarding-success** | Time-to-value and first-90-days success | [View](skills/customer-success/onboarding-success/) |
| 💚 | **customer-health-scores** | Actionable health models and risk bands | [View](skills/customer-success/customer-health-scores/) |
| 🔄 | **renewal-management** | Managed renewals with value evidence and risk plays | [View](skills/customer-success/renewal-management/) |
| 📈 | **expansion-playbooks** | Adoption-led upsell and cross-sell plays | [View](skills/customer-success/expansion-playbooks/) |
| 🛡️ | **churn-prevention** | Risk detection, save plays, root-cause learning | [View](skills/customer-success/churn-prevention/) |
| 📊 | **qbr-and-ebis** | Outcome-focused business reviews | [View](skills/customer-success/qbr-and-ebis/) |
| ⭐ | **customer-advocacy** | References, stories, and advocate programs | [View](skills/customer-success/customer-advocacy/) |
| 📋 | **success-planning** | Joint success plans with goals and owners | [View](skills/customer-success/success-planning/) |
| 🔗 | **support-to-success-handoff** | Clean Support ↔ CS ownership and context | [View](skills/customer-success/support-to-success-handoff/) |
| 📉 | **cs-metrics** | NRR, GRR, adoption, and leading indicators | [View](skills/customer-success/cs-metrics/) |
| 🗣️ | **voice-of-customer** | Structured VoC capture and routing to product | [View](skills/customer-success/voice-of-customer/) |

### 🛡️ Compliance (24) · 🔬 Research (24) · 💰 Finance (60) · 🤝 Sales (24) · 📈 Marketing & Growth (24) · 🎨 Design & UX (46) · 📦 Product Management (36) · 📄 Document Production (43) · ⚙️ Engineering (85)

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
│   ├── customer-success/        # 12
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
- [x] Marketing & Growth · Sales · Finance · Research · Compliance
- [x] Customer Success pack (started – 12 core skills)
- [ ] Expand Customer Success
- [ ] HR and remaining domains
- [ ] Curated skill packs + evaluation harness

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
