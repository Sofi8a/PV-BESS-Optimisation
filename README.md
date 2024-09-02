# PV BESS Optimisation Model
A deterministic optimisation model to advise on the most optimum PV and Battery technology type, capacity configuration,
and dispatch strategy.
Optimisation is performed based on:
- Electricity prices.
- Energy demand.
- Solar irradiance and ambient air temperature.
- Building's features (available rooftop area, battery room volume, etc.)
- Technology's technical and financial performance.
- Operational limits (SOC limit, electricity import/export limit)

NOTE:
Installation of GUROBI optimizer is required to run the code. Alternatively, the cell in Step-9 should be changed to "model.solve()"
to select PuLP default solver (takes longer to solve).
