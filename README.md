# Machine Learning Projects

This repository is a structured learning space for implementing machine learning projects while studying core algorithmic concepts.

## Learning Objectives

- Reinforce theoretical machine learning knowledge through hands-on practice
- Build intuition for data preprocessing, model training, and evaluation
- Compare different algorithms across classification and regression problems
- Document experiments and learning progress in a clean, reproducible way

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Projects Overview

| Algorithm | Project | Task Type | Status |
| --- | --- | --- | --- |
| Decision Tree | [Titanic Survival Prediction](./01-decision-tree/titanic-survival/) | Binary Classification | Planned |

## Repository Structure

```text
machine-learning-projects/
├── 01-decision-tree/
│   ├── titanic-survival/
│   │   ├── data/
│   │   ├── notebooks/
│   │   ├── README.md
│   │   └── requirements.txt
│   └── README.md
├── .gitignore
├── README.md
└── LICENSE
```

## Getting Started

1. Clone the repository.
2. Create a local virtual environment:
   ```bash
   python3 -m venv .venv
   ```
3. Activate it on macOS/Linux:
   ```bash
   source .venv/bin/activate
   ```
4. Install dependencies for the Titanic project:
   ```bash
   pip install -r 01-decision-tree/titanic-survival/requirements.txt
   ```
5. In VS Code, select the `.venv` interpreter and choose the corresponding Jupyter kernel when working with notebooks.

New projects will be added progressively as the learning journey expands to additional algorithms and topics.
