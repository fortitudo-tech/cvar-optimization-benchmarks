# CVaR optimization benchmark problems
This repository contains Conditional Value-at-Risk (CVaR) portfolio optimization benchmark
problems for fully general Monte Carlo distributions and derivatives portfolios.

The starting point is the [next-generation investment framework's market representation](https://youtu.be/4ESigySdGf8?si=yWYuP9te1K1RBU7j&t=46)
given by the matrix $R\in \mathbb{R}^{S\times I}$ and associated joint scenario probability
vectors $p,q\in \mathbb{R}^{S}$.

The [1_CVaROptBenchmarks notebook](https://github.com/fortitudo-tech/cvar-optimization-benchmarks/blob/main/1_CVaROptBenchmarks.ipynb)
illustrates how the benchmark problems can be solved using Fortitudo Technologies' Investment
Analysis module.

The [2_OptimizationExample notebook](https://github.com/fortitudo-tech/cvar-optimization-benchmarks/blob/main/2_OptimizationExample.ipynb)
shows how you can replicate the results using the [fortitudo.tech open-source Python package](https://github.com/fortitudo-tech/fortitudo.tech)
for the efficient frontier optimizations of long-only cash portfolios, which are the easiest problems to solve.

## Installation Instructions
It is recommended to install the code dependencies in a 
[conda environment](https://conda.io/projects/conda/en/latest/user-guide/concepts/environments.html):

    conda create -n cvar-optimization-benchmarks python
    pip install cvar-optimization-benchmarks

After this, you should be able to run the code in the [2_OptimizationExample notebook](https://github.com/fortitudo-tech/cvar-optimization-benchmarks/blob/main/2_OptimizationExample.ipynb).

## Portfolio Construction and Risk Management book
You can read much more about the [next-generation investment framework](https://antonvorobets.substack.com/p/anton-vorobets-next-generation-investment-framework)
in the [Portfolio Construction and Risk Management book](https://antonvorobets.substack.com/p/pcrm-book),
including a thorough description of CVaR optimization problems and
[Resampled Portfolio Stacking](https://antonvorobets.substack.com/p/resampled-portfolio-stacking).
