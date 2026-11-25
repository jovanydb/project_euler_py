# Project Euler · Python

**Mathematical problem solving in Python 3.13, one Jupyter notebook at a time.**

[Browse notebooks](#notebook-index) · [Run locally](#run-locally) · [C++ companion](https://github.com/jovanydb/project_euler_cpp)

This ongoing collection explores number theory, combinatorics, and algorithmic reasoning through [Project Euler](https://projecteuler.net/) problems. Notebooks preserve individual approaches and experiments; some remain works in progress.

## Notebook index

Links identify notebooks present in this repository, not a certification that every solution is complete.

| Problem numbers | Notebooks |
| --- | --- |
| 1–5 | [1](problem_1.ipynb) · [2](problem_2.ipynb) · [3](problem_3.ipynb) · [4](problem_4.ipynb) · [5](problem_5.ipynb) |
| 6–10 | [6](problem_6.ipynb) · [7](problem_7.ipynb) · [8](problem_8.ipynb) · [9](problem_9.ipynb) · [10](problem_10.ipynb) |
| 11–18 | [11](problem_11.ipynb) · [12](problem_12.ipynb) · [13](problem_13.ipynb) · [15](problem_15.ipynb) · [16](problem_16.ipynb) · [17](problem_17.ipynb) · [18](problem_18.ipynb) |
| 20–30 | [20](problem_20.ipynb) · [25](problem_25.ipynb) · [30](problem_30.ipynb) |
| 40–80 | [40](problem_40.ipynb) · [48](problem_48.ipynb) · [80](problem_80.ipynb) |

## Run locally

```bash
git clone https://github.com/jovanydb/project_euler_py.git
cd project_euler_py
python -m venv .venv
```

Activate with `source .venv/bin/activate` on macOS/Linux or `.\.venv\Scripts\Activate.ps1` in Windows PowerShell. Then install the notebook interface:

```bash
python -m pip install jupyterlab
python -m jupyterlab
```

Open a notebook and run its cells from top to bottom in a fresh kernel. Install any additional packages imported by the notebook you select. GitHub also renders notebooks for reading without a local setup.

## Suggested starting point

[Problem 1](problem_1.ipynb) introduces a compact `solve1()` function for summing multiples of 3 or 5 below 1,000. Continue through the index to explore other mathematical techniques.

## Reviewing a solution

For each notebook, check the problem bounds, explain the reasoning, and compare the result with independent small cases before relying on it. Restarting the kernel helps reveal hidden cell-order dependencies. Timing comparisons should state the input size and environment.

## Project direction

Continue documenting mathematical explanations, distinguish drafts from completed solutions, and add complexity notes where they help compare approaches.
