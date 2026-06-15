# 🗂️ genor-orchestrator-dashboard

**DEPRECATED — consolidated into [genor-orchestrator-plugin](https://github.com/GenorTG/genor-orchestrator-plugin)**

This was originally split into a separate "skill" repo by mistake. The dashboard
is a UI sidecar for the plugin, not a standalone skill. Everything now lives in
the plugin repo:

| What | Where |
|------|-------|
| Dashboard web app | `genor-orchestrator-plugin/dashboard/` |
| Server | `genor-orchestrator-plugin/dashboard/server.py` |
| PM2 | Runs `serve.sh` from plugin repo |

Kept for history. Will be removed.
