# Capacitated Lot Sizing Problem (CLSP)

In this repository, a multi-period production planning problem with capacity constraints is modeled and solved.

## Problem Description
The problem considers a single-product production system over a finite planning horizon with:
- Limited production capacity
- Limited inventory capacity
- Fixed setup cost
- Variable production cost
- Inventory holding cost
- Known deterministic demand

The objective is to minimize the total cost while satisfying all demands and ending with zero inventory.

## Solution Approaches
The problem is solved using two independent methods:
1. **Dynamic Programming (DP)** – solved stage by stage and presented with value tables.
2. **Mixed Integer Linear Programming (MILP)** – implemented and solved using **Pyomo** and **GLPK**.

Both approaches lead to the same optimal production plan and total cost, validating the correctness of the solution.

## Contents
- Mathematical formulation of the CLSP
- Step-by-step Dynamic Programming solution
- MILP formulation and validation
- Final optimal production plan and cost

## Tools
- LaTeX (XeLaTeX, xepersian)
- Pyomo
- GLPK

