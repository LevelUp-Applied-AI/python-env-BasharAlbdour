[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rZxQuJoV)
# AI.SPIRE Pre-Work — Python Toolchain

This repository is your workspace for Pre-Work Days 3–5.

| Day | PR | Topic |
|-----|-----|-------|
| 3 | PR-2 | Python venv Bootstrap + Sanity Script |
| 4 | PR-3 | Notebook vs Script: Same Output Two Ways |
| 5 | PR-4 | Compute & Debug Evidence Pack |

## Setup

Install Python 3.11 from [python.org](https://python.org), then:

```bash
python -m venv .venv
source .venv/bin/activate        # macOS / Linux
# source .venv/Scripts/activate  # Windows (Git Bash)
python -m pip install --upgrade pip
python -m pip install -r requirements-prework.txt
```

## Submitting PRs

1. Create a branch named for the PR task (e.g., `pr-02-python-env`)
2. Complete the work
3. Push the branch and open a PR from your branch to `main`
4. Submit the PR URL in TalentLMS

when to use each:
1- we should use a jupyter notebook when we want to experiment a code and see the output immediately espeically when we are required
to explore data depending on execution order and memory, the notebook helps me to debug easily and understand each operation 
in an interactive way .
2-we use python script when we need a clean and well organized code that runs from start to finish , we use it also when I already know
what the output will be , so the script feels more suitable for final solution . 

