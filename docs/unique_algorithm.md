# Unique Prototype Algorithm

## Algorithm

**MahdaviEvidenceMlOptimizationRepairLoop** (`P069-Mahdavi-MlOptimization`)

## Professor Alignment

- Professor: Mehrdad Mahdavi
- Research area: ML optimization, federated learning, learning theory
- Focus terms: ML optimization, federated learning, learning theory

## Core Mechanism

This prototype prioritizes efficient training configurations under metric, runtime, and calibration tradeoffs.

## Decision Rule

Rank seed cases by optimization-specific priority score with Mahdavi-aligned focus term 'ML optimization'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `optimization` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Mehrdad Mahdavi's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
