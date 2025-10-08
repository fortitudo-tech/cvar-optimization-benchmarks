# CVaR optimization benchmark problems
This repository contains Conditional Value-at-Risk (CVaR) portfolio optimization benchmark problems for fully general Monte Carlo distributions and derivatives portfolios.

The starting point is the [next-generation investment framework's market representation](https://youtu.be/4ESigySdGf8?si=yWYuP9te1K1RBU7j&t=46) given by the matrix $R\in \mathbb{R}^{S\times I}$ and associated joint scenario probability vectors $p,q\in \mathbb{R}^{S}$.

The [CVaROptBenchmarks notebook](https://github.com/fortitudo-tech/cvar-optimization-benchmarks/blob/main/CVaROptBenchmarks.ipynb) illustrates how the benchmark problems can be solved using Fortitudo Technologies' Investment Analysis module, while the [OptimizationExample notebook](https://github.com/fortitudo-tech/cvar-optimization-benchmarks/blob/main/OptimizationExample.ipynb) shows how you can replicate the results using the [fortitudo.tech open-source Python package](https://github.com/fortitudo-tech/fortitudo.tech) for the efficient frontier optimizations of long-only cash portfolios, which are the easiest problems to solve.

You can read much more about the next-generation investment framework in the [Portfolio Construction and Risk Management book](https://antonvorobets.substack.com/p/pcrm-book).