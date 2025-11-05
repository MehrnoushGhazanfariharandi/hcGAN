# A Hierarchical cGAN Architecture for Consistent Renewable Scenarios in Power System Planning
Code and data to replicate the results of the paper [A Hierarchical cGAN Architecture for Consistent Renewable Scenarios in Power System Planning].

## Abstract

Scenario generation plays a crucial role in the operation and planning of power systems with significant renewable
integration. In this work, we propose a data-driven hierarchical
conditional GAN (cGAN) framework for generating realistic
forecast and forecast error scenarios of wind power production. By conditioning the generation process on the forecast,
the proposed model directly learns the conditional forecasterror distribution. The method captures temporal variability
and spatial dependencies across multiple sites while maintaining
consistency between forecasts and their corresponding errors.
We also introduce regime labels derived from daily capacity
factors and use them as conditional inputs to enable controllable
scenario generation under specific operating conditions, such
as extreme wind events. Using real offshore wind timeseries
data, we demonstrate that our method reproduces key statistical
characteristics across different seasons and regimes. We show
that the generated scenarios provide realistic and reliable inputs
for power system operation and planning studies.
## Usage

Everything is implemented in [python](https://www.python.org/) (Version 3.11) and all results can be reproduced by running the code blocks in `OPT_results.ipynb` and `Scenario_gen.ipynb using the interactive [Jupyter environment with a python backend](). 
