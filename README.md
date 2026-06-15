# Supermarket Price Direction Prediction

This project predicts UK supermarket price direction using price-history-only features.

## Setup

Create the Conda environment:

```bash
conda env create -f environment.yml
conda activate supermarket-price-direction
```

After the environment is created, export a pinned lock file:

```bash
conda env export --no-builds > environment.lock.yml
```

## Project structure

```text
data/
  raw/
  interim/
  processed/
notebooks/
src/
tests/
figures/
results/
```

## Run order

1. Repository and environment setup
2. Fresh clone environment check
3. Data audit
4. Data cleaning
5. Feature engineering
6. Persistence baseline
7. Logistic Regression, Decision Tree, Random Forest, XGBoost
8. Imbalance comparison
9. Evaluation and TreeSHAP interpretation

## Licence

Apache-2.0.
