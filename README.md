# Affective Agent — Pre-Human-Trials Package (v4.1)

This repository contains the **pilot-ready package** for running and validating an affective computing agent that integrates interoceptive signals (EDA, HR, Respiration) into predictive processing and global workspace dynamics.

The package includes:
- ✅ Reference agent implementation with ablation controls  
- ✅ Synthetic physiology generator (baseline → stress → recovery)  
- ✅ Data ingestion (CSV adapter, event/marker aligner, self-report forms)  
- ✅ Quality control (clipping, NaN repair, flatline detection)  
- ✅ Metrics: Shannon entropy, Lempel-Ziv complexity, Active Information Storage (AIS), HRV (RMSSD)  
- ✅ Validation workflows (baseline, ablations, noise sweeps)  
- ✅ Self-report & events augmentation (correlations, segment deltas, CIs & permutation tests)  
- ✅ Reporting in Markdown (`docs/validation_summary.md`), machine-readable CSV (`docs/summary.csv`), and consolidated PDF (`docs/affective-agent_pilot_report.pdf`)  
- ✅ Operator runbook, preregistration outline, and consent template  

---

## 🚀 Quick Start

### 1. Setup
```bash
git clone https://github.com/Mark0340/affective-agent.git
cd affective-agent

python -m venv .venv
source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
pip install -U pip
pip install -e .
