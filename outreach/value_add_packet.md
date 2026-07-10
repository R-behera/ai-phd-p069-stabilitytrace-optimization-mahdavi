# Professor Outreach Value-Add Packet

## Bottom Line

This repository is currently a **research proposal and execution scaffold**, not a completed result. Use it to show Professor Mahdavi that you understand the research area and can contribute a concrete, reproducible artifact.

## Target Professor

- **Professor:** Mehrdad Mahdavi
- **University:** Penn State
- **Program:** CSE PhD
- **Research area from CSV:** ML optimization, federated learning, learning theory
- **Representative paper from CSV:** Online Convex Optimization with Long Term Constraints; 2012; JMLR
- **Scholar link:** https://scholar.google.com/scholar?q=Online+Convex+Optimization+with+Long+Term+Constraints

## Proposed Value Add

Build **a controlled training-dynamics study connecting optimization choices to reliability and efficiency** focused on **ML optimization**.

### What You Can Contribute

- Run compact, reproducible training experiments under a fixed compute budget.
- Measure stability, calibration, and distribution shift rather than only final accuracy.
- Produce diagnostics that explain when an optimization method is worth its complexity.

## Concrete Starter Project

Implement a small benchmark matrix across optimizer/schedule/model-size choices and track robustness, calibration, and seed variance.

## 30/60/90-Day Plan

### First 30 Days

- Re-read 3-5 recent lab papers and write a one-page problem framing memo.
- Build the first dataset or evaluation slice with documented source provenance.
- Reproduce one credible baseline and record exact commands.
- Create a failure bank with at least 20 concrete examples.

### Days 31-60

- Add the proposed method or evaluation contribution.
- Run ablations that isolate the contribution from data scale and model-size effects.
- Add robustness, temporal, domain-shift, or subgroup tests where relevant.
- Write interim results as a short lab-note style report.

### Days 61-90

- Expand the benchmark to 50-100 examples or the equivalent for the domain.
- Run statistical checks, seed variance checks, and cost/runtime analysis.
- Convert results into a paper-style technical report.
- Package the repo so another student can reproduce the main table.

## Deliverables To Offer The Professor

- Locked compute-budget experiment configs.
- Training dynamics plots and final result tables.
- Seed-stability and calibration analysis.
- A recommendation memo for which method to scale up.

## Skills This Demonstrates

ML systems experimentation, optimization diagnostics, statistical reporting, efficient training.

## Honest Outreach Framing

Do **not** claim this is finished. The honest claim is:

> I prepared a concrete research scaffold aligned with your work and would like to turn it into a reproducible contribution if it matches your lab's current priorities.

## Sharing Note

This GitHub repository is public. Before emailing, verify the professor's current work, personalize the email, and be ready to explain exactly what is implemented versus planned.
