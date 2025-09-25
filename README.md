# Affective Agent Prototype  
**Author:** Mark Purvis  

This is the first working prototype that links interoception, prediction error, and a global workspace into a testable model of **emotion & consciousness**.  

---

## 📦 What’s Inside
- **src/** → core source code (`affective_agent.py`)  
- **scripts/** → simulation scripts (threat, recovery, control comparison)  
- **tests/** → simple tests to validate model behavior  
- **paper/** → draft write-up with theory, design, and results  
- **figures/** → plots of valence/arousal from simulations  
- **affective_agent_whitepaper.pdf** → full whitepaper with results + diagrams  

---

## 🚀 Quickstart
1. Clone or download this repository  
2. Run a simulation:  
   ```bash
   python scripts/simulate.pypytest
## Final Validation Summary
- ✅ Complexity metrics show rich internal dynamics (entropy > 2.5).
- ✅ Perturbations yield correct causal signs (EDA ↑ → arousal ↑, valence ↓).
- ✅ Ablations confirm all components contribute.
- ✅ Baselines weaker than full model.
- ✅ Robust to realistic noise and latency.

See detailed CSVs in `experiments/` and `results/`.
