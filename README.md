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
**Phase 8 – Research** 🚀 (24 skills)  
**Skills added so far**: **344** (2 Meta + 85 Engineering + 43 Document Production + 36 Product Management + 46 Design & UX + 24 Marketing & Growth + 24 Sales + 60 Finance + 24 Research)

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 🔬 Research (24 skills)

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
| 👀 | **ethnographic-research** | Observational research in real contexts | [View](skills/research/ethnographic-research/) |
| 📔 | **diary-studies** | Longitudinal capture of experiences over time | [View](skills/research/diary-studies/) |
| 🧪 | **usability-research** | Task-based evaluation of whether designs work | [View](skills/research/usability-research/) |
| 📉 | **experiment-analysis** | Credible A/B and experiment readout | [View](skills/research/experiment-analysis/) |
| 📖 | **systematic-review** | Protocol-driven evidence aggregation | [View](skills/research/systematic-review/) |
| 🎯 | **jtbd-research** | Jobs-to-be-Done progress and switching research | [View](skills/research/jtbd-research/) |
| 🛰️ | **technology-scouting** | Emerging tech and vendor landscape evaluation | [View](skills/research/technology-scouting/) |
| 🗄️ | **secondary-data-analysis** | Insight from existing datasets and logs | [View](skills/research/secondary-data-analysis/) |
| ⚙️ | **research-ops** | Recruiting, repositories, and research enablement | [View](skills/research/research-ops/) |
| 👤 | **persona-evidence** | Evidence-grounded personas, not stereotypes | [View](skills/research/persona-evidence/) |
| 💡 | **concept-testing** | Early concept and messaging evaluation | [View](skills/research/concept-testing/) |
| 🌍 | **field-research** | On-site and in-context studies outside the lab | [View](skills/research/field-research/) |

### 💰 Finance (60) · 🤝 Sales (24) · 📈 Marketing & Growth (24) · 🎨 Design & UX (46) · 📦 Product Management (36) · 📄 Document Production (43) · ⚙️ Engineering (85)

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
- [x] Research pack (24 skills) ✅
- [ ] Customer Success, Compliance, HR, and remaining domains
- [ ] Curated skill packs + evaluation harness

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
