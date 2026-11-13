# MLflow homework screenshots (ecommerce-start)

Живой UI: Docker `ghcr.io/mlflow/mlflow:v3.12.0` на kvm8, порт **5002**.

- `01-runs.png` — эксперимент `ecommerce-purchase`: `gb_lr0.05`, `gb_lr0.1` (champion), `gb_lr0.2`, parent `GridSearch`
- `02-registry.png` — Model Registry `ecommerce-purchase-clf`
- `03-agent-tags.png` — теги агента: `keep_champion`, F1 0.8428 → 0.8696, lift 3.17% < 5%
- `04-gridsearch.png` — nested Optuna: child runs `trial_0`…`trial_7`, `best_f1_score=0.8696`
- `05-confusion-matrix.png` — confusion matrix лучшего run Task 1 (`lr=0.1`)
- `05b-cm-lr0.05.png`, `05c-cm-lr0.2.png` — остальные матрицы Task 1

Код: https://github.com/Leonid328/ecommerce-mlflow-hw
