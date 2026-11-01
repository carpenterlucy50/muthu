# `submission/` — Deliverables Packaging

This directory contains packaged ZIP deliverables according to the submission specification on Page 14 of the Capstone Brief.

## Submission ZIP Structure
The deliverable archive packages all required files for reproducible evaluation:
- `README.md` (Explaining setup, run command, and public GitHub URL: https://github.com/pearllakhsmi786/VoiceOps-2026-Project)
- `.env.example` (Template with no API keys or secrets)
- `requirements.txt` (Pinned project dependencies)
- `run.py` (Unified CLI entrypoint accepting `--input-dir` and `--output-dir`)
- `src/` (Complete source code)
- `tests/` (Automated test suite)
- `evaluation/` (Evaluation benchmark drivers)
- `report.pdf` (Max 4-page technical report)
- `demo_instructions.md` (2-minute live demo script)
- `sample_outputs/` (Sample batch audio results and benchmark dashboards)

## Strict Hygiene Checks
Per Capstone Brief Page 14:
- Virtual environments (`.venv/`, `venv/`) are excluded.
- Secret credentials (`.env`, live API keys) are strictly excluded.
- Raw dataset copies are excluded to keep file size within limits.
