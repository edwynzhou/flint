# Flint (trimmed)

This repository has been trimmed to only include the ML forecaster and RL agent components.

Remaining structure:

- `services/backend/model/forecaster` — forecaster code and export scripts
- `services/backend/model/run_agent` — RL (PPO) training/eval pipelines
- `services/backend/model/agents` — agent wrappers
- `services/backend/model/trade_env` — environment and utilities
- `services/backend/model/data` — CSV data and extraction scripts
- `services/backend/model/README_model.md` — model examples and commands

Quick start:

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Export forecasts (example):

```bash
python -m backend.model.forecaster.export_forecast --contract H --start-ts "2025-09-15T07:00:00Z" --align next
```

3. Run agent eval report (example):

```bash
python -m backend.model.run_agent.run_eval_report --contract H --start-ts "2025-09-15T07:00:00Z" --align next
```

If you want a full backup of the remaining model folder, there's a ZIP in the repository root named `model_backup.zip`.
