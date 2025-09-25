# Affective Agent — Pre-Human-Trials Package (v4.1)

This repository hosts the **pilot-ready package** for running and validating an affective computing agent that integrates interoceptive signals (EDA, HR, Respiration) into predictive processing and global workspace dynamics.

## 🚀 Overview
The Affective Agent is designed for research and pilot validation. It provides a modular implementation for integrating synthetic and real physiological data into cognitive-affective architectures. The package supports ablation controls, signal ingestion, and automated quality checks.

## 📦 Contents
- ✅ Reference agent implementation with ablation controls  
- ✅ Synthetic physiology generator (baseline → stress → recovery)  
- ✅ Data ingestion (CSV adapter, event/marker aligner, self-report forms)  
- ✅ Quality control scripts and validation tools  
- ✅ Pilot-ready configuration (pre-human-trials)

## ⚡ Quickstart
1. Clone the repository:
   ```bash
   git clone https://github.com/Mark0340/affective-agent.git
   cd affective-agent
   ```

2. Unzip the essentials package (from Releases):
   ```bash
   unzip pretrial-essentials-v4_1.zip -d ./essentials
   ```

3. Run the reference agent:
   ```bash
   python run_agent.py --config essentials/config.yaml
   ```

## 📊 Validation Workflow
1. Generate synthetic physiology data.  
2. Run the agent with/without ablation controls.  
3. Align results with event markers and self-report forms.  
4. Review quality control metrics.

## 📂 Release Files
- [pretrial-essentials-v4_1.zip](https://github.com/Mark0340/affective-agent/releases/download/v4.1/pretrial-essentials-v4_1.zip)  
- [pretrial-essentials-v4_1.pdf](https://github.com/Mark0340/affective-agent/releases/download/v4.1/pretrial-essentials-v4_1.pdf)

## 📜 License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.

## 📖 Citation
If you use this work in research, please cite:

```
@software{affective_agent_v41,
  author = {Purvis, Mark},
  title = {Affective Agent — Pre-Human-Trials Package (v4.1)},
  year = {2025},
  url = {https://github.com/Mark0340/affective-agent}
}
```

---
For questions or contributions, please open an issue or pull request.
