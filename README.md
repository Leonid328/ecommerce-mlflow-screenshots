# MLflow homework screenshots (ecommerce-start)

Скриншоты прогонов на kvm8, MLflow: http://168.231.116.71:5000

- `01-runs.png` — Task 1–2: runs эксперимента `ecommerce-purchase` (learning_rate, accuracy, F1)
- `02-registry.png` — Model Registry `ecommerce-purchase-clf`: v1 `@champion`, v2 `@challenger`
- `03-agent-tags.png` — Task 3: теги агента (`agent_decision=keep_champion`, lift 1.92% < 5%)

Код: отдельный репозиторий с `src/train.py`, `src/tune.py`, `src/promote_agent.py`.
