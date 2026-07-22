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
**Phase 8 – Research** 🚀 (12 skills)  
**Skills added so far**: **332** (2 Meta + 85 Engineering + 43 Document Production + 36 Product Management + 46 Design & UX + 24 Marketing & Growth + 24 Sales + 60 Finance + 12 Research)

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 🔬 Research (12 skills)

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 📐 | **research-design** | Study design, method choice, and research planning | [View](skills/research/research-design/) |
| 📚 | **literature-review** | Map existing knowledge and identify gaps | [View](skills/research/literature-review/) |
| 🖥️ | **desk-research** | Fast secondary research with source hygiene | [View](skills/research/desk-research/) |
| 💬 | **qualitative-research** | Depth methods for meaning, context, and motivation | [View](skills/research/qualitative-research/) |
| 📊 | **quantitative-research** | Measurement, sampling, and statistical care | [View](skills/research/quantitative-research/) |
| 📋 | **survey-design** | Reliable questionnaires and bias-aware structure | [View](skills/research/survey-design/) |
| 🎙️ | **interview-research** | Research interviews that elicit honest detail | [View](skills/research/interview-research/) |
| 🧩 | **research-synthesis** | Turn evidence into insights and recommendations | [View](skills/research/research-synthesis/) |
| 🏁 | **competitive-research** | Competitor product, pricing, and strategy intel | [View](skills/research/competitive-research/) |
| 📈 | **market-research** | Demand, segments, sizing, and buying dynamics | [View](skills/research/market-research/) |
| ⚖️ | **research-ethics** | Consent, privacy, harm minimization, honest reporting | [View](skills/research/research-ethics/) |
| 📝 | **research-reporting** | Clear, decision-ready research communication | [View](skills/research/research-reporting/) |

### 💰 Finance (60 skills)

<details>
<summary>Click to expand Finance catalog (60 skills)</summary>

Includes financial statements, modeling, FP&A, cash & treasury, valuation, unit economics, accounting & close, controls & risk, **retail & corporate credit risk monitoring**, fundraising, SaaS metrics, and more — see `skills/finance/`.

</details>

### 🤝 Sales (24) · 📈 Marketing & Growth (24) · 🎨 Design & UX (46) · 📦 Product Management (36) · 📄 Document Production (43) · ⚙️ Engineering (85)

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
│   ├── research/                # 12
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
- [x] Marketing & Growth · Sales · Finance (60)
- [x] Research pack (started – 12 core skills)
- [ ] Expand Research
- [ ] Customer Success, Compliance, HR, and remaining domains
- [ ] Curated skill packs + evaluation harness

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
