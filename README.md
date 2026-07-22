# Agent Skills Collection

**A comprehensive, production-ready collection of high-quality Agent Skills** for Claude, Codex, Cursor, Gemini CLI, and other AI coding agents.

Built following the [Anthropic Agent Skills standard](https://github.com/anthropics/skills) with best practices from leading open collections.

> **Goal**: 500+ modular, battle-tested skills organized by domain, with strong verification steps, clear triggering descriptions, and progressive disclosure.

## Current Status

| Phase | Domain | Skills |
|-------|--------|--------|
| 1 | Engineering & Software Development | 85 ✅ |
| 2 | Document Production | 43 ✅ |
| 3 | Product Management | 36 ✅ |
| 4 | Design & UX | 46 ✅ |
| 5 | Marketing & Growth | 24 ✅ |
| 6 | Sales | 24 ✅ |
| 7 | Finance | 60 ✅ |
| 8 | Research | 24 ✅ |
| 9 | Compliance | 24 ✅ |
| 10 | Customer Success | 24 ✅ |
| 11 | **HR** | **30 ✅** |
| | **Meta** | **2** |
| | **Total** | **422** |

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 👥 HR (30 skills)

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🎯 | **talent-acquisition** | Attract, assess, and hire with quality and fairness | [View](skills/hr/talent-acquisition/) |
| 🏗️ | **job-architecture** | Families, levels, and role profiles | [View](skills/hr/job-architecture/) |
| 🎙️ | **interviewing** | Structured interviews and evidence-based selection | [View](skills/hr/interviewing/) |
| 🚀 | **onboarding-hr** | New-hire ramp, belonging, and early retention | [View](skills/hr/onboarding-hr/) |
| 📊 | **performance-management** | Expectations, reviews, calibration, fairness | [View](skills/hr/performance-management/) |
| 🎯 | **goal-setting-and-okrs-hr** | Aligned, usable goal/OKR systems | [View](skills/hr/goal-setting-and-okrs-hr/) |
| 💬 | **feedback-and-coaching** | Manager feedback skill and coaching cadence | [View](skills/hr/feedback-and-coaching/) |
| 📚 | **learning-and-development** | Capability building tied to strategy | [View](skills/hr/learning-and-development/) |
| 👑 | **succession-planning** | Critical roles, benches, readiness | [View](skills/hr/succession-planning/) |
| 💰 | **compensation-design** | Pay bands, variable pay, equity structures | [View](skills/hr/compensation-design/) |
| 🏥 | **benefits-strategy** | Benefits portfolio and perceived value | [View](skills/hr/benefits-strategy/) |
| 📈 | **workforce-planning** | Supply, demand, skills, and capacity | [View](skills/hr/workforce-planning/) |
| ⚖️ | **employee-relations** | Fair handling of conflicts and concerns | [View](skills/hr/employee-relations/) |
| 💙 | **employee-engagement** | Surveys, drivers, and action follow-through | [View](skills/hr/employee-engagement/) |
| 🌈 | **diversity-equity-inclusion** | Evidence-based DEI in process and outcomes | [View](skills/hr/diversity-equity-inclusion/) |
| 🏛️ | **culture-and-values** | Values as lived behaviors and systems | [View](skills/hr/culture-and-values/) |
| 📄 | **hr-policies** | Clear, usable, consistent people policies | [View](skills/hr/hr-policies/) |
| 🔍 | **workplace-investigations** | Fair, documented misconduct fact-finding | [View](skills/hr/workplace-investigations/) |
| 🚪 | **offboarding** | Secure, respectful, learning-oriented exits | [View](skills/hr/offboarding/) |
| 🔄 | **internal-mobility** | Internal moves, marketplaces, talent reuse | [View](skills/hr/internal-mobility/) |
| 📉 | **hr-analytics** | People metrics and responsible workforce insight | [View](skills/hr/hr-analytics/) |
| 🖥️ | **hr-systems** | HRIS/ATS/LMS selection and operation | [View](skills/hr/hr-systems/) |
| ⚖️ | **labor-compliance-basics** | Employment law literacy and escalation | [View](skills/hr/labor-compliance-basics/) |
| 🧭 | **manager-enablement** | Tools and skill for people leaders | [View](skills/hr/manager-enablement/) |
| 🎁 | **total-rewards** | Integrated pay, benefits, growth, experience | [View](skills/hr/total-rewards/) |
| 📣 | **employer-branding** | Authentic attraction narrative | [View](skills/hr/employer-branding/) |
| 🔀 | **change-management-hr** | People-side adoption of org change | [View](skills/hr/change-management-hr/) |
| 🧘 | **wellbeing-and-burnout** | Work design and support against burnout | [View](skills/hr/wellbeing-and-burnout/) |
| 🗂️ | **org-design-basics** | Structure, spans, layers, accountabilities | [View](skills/hr/org-design-basics/) |
| 🤝 | **hrbp-partnership** | Strategic HR business partnering | [View](skills/hr/hrbp-partnership/) |

### Other domains

Customer Success (24) · Compliance (24) · Research (24) · Finance (60) · Sales (24) · Marketing & Growth (24) · Design & UX (46) · Product Management (36) · Document Production (43) · Engineering (85) — full catalogs under `skills/`.

---

## Repository Structure

```
agent-skills-collection/
├── README.md
├── LICENSE
├── skills/
│   ├── meta/                 # 2
│   ├── engineering/          # 85
│   ├── document-production/  # 43
│   ├── product-management/   # 36
│   ├── design-ux/            # 46
│   ├── marketing-growth/     # 24
│   ├── sales/                # 24
│   ├── finance/              # 60
│   ├── research/             # 24
│   ├── compliance/           # 24
│   ├── customer-success/     # 24
│   ├── hr/                   # 30
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
- [x] Customer Success · **HR (30)** ✅
- [ ] Remaining domains toward 500+
- [ ] Curated skill packs + evaluation harness

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
