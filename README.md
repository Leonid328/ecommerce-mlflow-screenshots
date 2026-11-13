# MLflow homework screenshots (ecommerce-start)

Live UI: Docker MLflow on kvm8, port **5002**.

- `01-runs.png` — experiment `ecommerce-purchase` (Task 1 + GridSearch)
- `02-registry.png` — model registry list: `ecommerce-purchase-clf` aliases `@champion` / `@challenger`
- `03-agent-tags.png` — agent tags: `promote_challenger`, F1 lift **6.01%** (>5%)
- `04-gridsearch.png` — nested Optuna `trial_0`…`trial_7`, `best_f1_score=0.8562`
- `05-confusion-matrix.png` — Task 1 confusion matrix (best baseline `lr=0.25`)

Code: https://github.com/Leonid328/ecommerce-mlflow-hw
