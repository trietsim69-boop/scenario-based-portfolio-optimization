# Scenario-Based Portfolio Optimization for University Strategy

A consulting-style decision analytics project for strategic decision-making under uncertainty. The project evaluates alternative strategic actions for Aalto University’s long-term teaching and learning strategy using scenario planning, multi-attribute utility analysis, swing weighting, and constrained portfolio optimization.

## Project overview

The goal of this project was to recommend a robust strategic action portfolio under uncertain future conditions. Instead of assuming one fixed future, the model evaluates actions across three alternative scenarios:

1. **Competitive Global Campus**
2. **Always-Learning Society**
3. **Human-First University**

The final recommendation is based on expected utility, implementation feasibility, and robustness across sensitivity cases.

## Methods used

- Scenario planning
- Rank-Order Centroid scenario probability elicitation
- Multi-attribute utility analysis
- Value functions
- Swing weighting
- Constrained portfolio optimization
- Sensitivity analysis
- SWOT analysis
- Client-facing decision recommendation

## Decision problem

The model evaluates seven strategic action proposals across eight attributes, including learning outcomes, progression, learner experience, accessibility, assessment integrity, strategic autonomy, employability, and reputation.

The optimization model selects the best portfolio subject to:

- Budget constraint
- Implementation capacity constraint
- Portfolio size constraint
- Dependency constraint
- Balance constraint
- Time constraint

## Key recommendation

The base-case model recommends a four-action portfolio:

- Elite Mentor Network / Smart Work-Study
- Aalto-Controlled Core Infrastructure
- Aalto-Certified Micro-Credentials
- Pedagogical Training for Staff

The recommended portfolio achieved an expected utility of **2.462**, using **€4.9M** of budget, six implementation-capacity points, and 5.2 years of implementation time. The report also found that the recommendation was robust to changes in scenario probabilities but more sensitive to implementation constraints. 

## Repository structure

```text
.
├── README.md
├── report/
│   └── decision_analytics_report.pdf
└── model/
    └── portfolio_model.xlsx
