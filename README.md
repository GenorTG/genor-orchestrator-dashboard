# Genor's Orchestration Skill

[![ClawHub](https://img.shields.io/badge/ClawHub-genor--orchestrator-blue)](https://clawhub.com/packages/genor-orchestrator)
[![License: MIT-0](https://img.shields.io/badge/License-MIT--0-brightgreen)](LICENSE)

**Companion for [Genor's Orchestrator Plugin](https://github.com/GenorTG/genor-orchestrator-plugin).** Provides the dashboard web UI, coding workflow reference, and operational scripts.

---

## Components

**Dashboard** (PM2 on port 8766): Model CRUD, routing config, session viewer, project management.

**Scripts**: auto-populate-models.py, check-models.sh, check-prices.sh, init-project.sh, test-model.sh.

**SKILL.md**: Codified coding workflow (6 phases), model routing decision tables, sub-agent protocol, tool fallback chains.

---

## Install

```bash
# Via ClawHub
clawhub install genor-orchestrator

# Or from source (skill/ subdirectory of plugin repo)
clawhub install ./path/to/skill/
```

Then start the dashboard:
```bash
pm2 start dashboard/server.py --name orchestration-dashboard --interpreter python3 -- 8766
```

---

## License

MIT-0
