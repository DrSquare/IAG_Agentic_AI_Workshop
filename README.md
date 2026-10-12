# IAG Agentic AI Workshop

Materials for the workshop **"Define, Design, Build Agents in Copilot Cowork"**. The repo has the slide deck, sample business documents to run agents against, and example skills that show how to package organisational know-how for an agent.

The demo uses a fictional general insurer, **Harbourline**.

## Contents

| Path | What it is |
|---|---|
| `Define, Design, Build Agents in Copilot Cowork_vF.pdf` | Workshop slide deck |
| `06 OneDrive - Demo files/` | Sample inputs for the demos |
| `08 OneDrive - Documents-Cowork-skills/` | Example Cowork skills (`SKILL.md` files) |

### Demo files

- `annual-report.pdf`: insurer annual report, used for KPI extraction and analysis
- `board-paper.pdf`: draft Board paper, used for review against the Board paper standard
- `business-case-model.xlsx`: business case financial model that goes with the Board paper

### Skills

Each skill is a folder containing a `SKILL.md` with YAML frontmatter (`name`, `description`) and the instructions the agent follows.

| Skill | Purpose |
|---|---|
| `board-paper-standard` | Review, critique or draft Board papers and business cases against Harbourline's standard |
| `competitor-profile` | Profile competitors, brokers, reinsurers or vendors under fixed, comparable headings |
| `insurance-kpis` | Standard definitions for general insurance KPIs (GWP, NIR, COR, ITR, claims ratios, capital) |
| `stakeholder-brief` | One-page pre-meeting brief on a key stakeholder, plus commitments tracking |
| `strategic-radar` | Weekly ELT scan of market, competitor, technology, regulatory and internal signals |

## Using the skills

1. Copy a skill folder into the location your agent platform reads skills from (for example, the Cowork skills folder in OneDrive).
2. Ask a question that matches the skill's `description`, for example "Review this board paper" or "Extract the KPIs from the annual report".
3. The agent loads the skill and follows its instructions.

Adapt the skills to your organisation by editing the references to SharePoint locations, owners, priorities and definitions.

## Disclaimer

Harbourline, the people it names and all figures are fictional and exist only for training.
