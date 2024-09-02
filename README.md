### PV BESS Optimisation Model (Deterministic_Op_Model.ipynb)
A deterministic optimisation model to advise on the most optimum PV and Battery technology type, capacity configuration,
and dispatch strategy.
Optimisation is performed based on:
- Electricity prices.
- Energy demand.
- Solar irradiance and ambient air temperature.
- Building's features (available rooftop area, battery room volume, etc.)
- Technology's technical and financial performance.
- Operational limits (SOC limit, electricity import/export limit)

### Uncertainty Analysis with MCS (Uncertainty_MCS.ipynb)
An uncertainty analysis on annual electricity price increase and its influence on the optimised solution.

NOTES:
- Installation of GUROBI optimizer is required to run the code. Alternatively, the cell in Step-9 should be changed to "model.solve()"
to select PuLP default solver (takes longer to solve).

