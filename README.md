# Explainable Multi-Agent Reinforcement Learning for Autonomous Cyber Defense

This repository contains the source code, environment implementation, and experimental results for the research project: **"Explainable Multi-Agent Reinforcement Learning for Autonomous Cyber Defense: A POSG Framework with SHAP-Driven Policy Interpretation"**.

## Repository Structure

- `Explainable Multi-Agent Reinforcement Learning for Autonomous Cyber Defense.ipynb`: The main research notebook containing:
  - Environment implementation (`CyberSecEnv`).
  - Stable-Baselines3 wrappers.
  - Training loops and self-play logic.
  - SHAP-based policy interpretation cells.
- `Manuscript Research Logs-Outputs-Plots/`: Comprehensive logs, metrics, and visualization plots generated during the experimental phases, including ablation studies.

## Setup & Installation

To run the experiments locally, ensure you have Python installed and install the required dependencies:

```bash
pip install gymnasium==1.0.0 stable-baselines3 shimmy shap numpy torch matplotlib seaborn
```

## How to Use

1.  Open the Jupyter Notebook: `Explainable Multi-Agent Reinforcement Learning for Autonomous Cyber Defense.ipynb`.
2.  Follow the cells sequentially to:
    - Define the POSG environment.
    - Initialize the training protocol.
    - Run evaluations against heuristic and RL baselines.
    - Generate SHAP plots for policy interpretation.
