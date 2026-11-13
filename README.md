# MLflow homework screenshots (ecommerce-start)

Живой UI: Docker MLflow на kvm8, порт **5002**.

- `01-runs.png` — эксперимент `ecommerce-purchase` (Task 1 + GridSearch)
- `02-registry.png` / `03-agent-tags.png` — v4 `@champion` + `@challenger`, `agent_decision=promote_challenger`, lift **6.01%** (>5%)
- `04-gridsearch.png` — nested Optuna `trial_0…7`, `best_f1_score=0.8562`
- `05-confusion-matrix.png` — confusion matrix Task 1 (лучший baseline `lr=0.25`)

Код: https://github.com/Leonid328/ecommerce-mlflow-hw
