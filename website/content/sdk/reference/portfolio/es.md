---
title: es
description: Learn how to use the openbb.portfolio.es function to calculate the portfolio
  expected shortfall. It allows the use of different distributions and custom percentiles.
keywords:
- openbb.portfolio.es
- Portfolio expected shortfall
- PortfolioEngine class
- Calculations on portfolio
- Portfolio distributions
- Portfolio percentiles
- openbb.portfolio.load
- Portfolio examples
- Python portfolio calculations
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="portfolio.es - Reference | OpenBB SDK Docs" />

Get portfolio expected shortfall

Source Code: [[link](https://github.com/OpenBB-finance/OpenBBTerminal/tree/main/openbb_terminal/portfolio/portfolio_model.py#L1797)]

```python
openbb.portfolio.es(portfolio_engine: portfolio_engine.PortfolioEngine, use_mean: bool = False, distribution: str = "normal", percentile: float = 99.9)
```

---

## Parameters

| Name | Type | Description | Default | Optional |
| ---- | ---- | ----------- | ------- | -------- |
| portfolio_engine | PortfolioEngine | PortfolioEngine class instance, this will hold transactions and perform calculations.<br/>Use `portfolio.load` to create a PortfolioEngine. | None | False |
| use_mean |  | if one should use the data mean return | False | True |
| distribution | str | choose distribution to use: logistic, laplace, normal | normal | True |
| percentile | float | es percentile (%) | 99.9 | True |


---

## Returns

| Type | Description |
| ---- | ----------- |
| pd.DataFrame | DataFrame with portfolio expected shortfall |
---

## Examples

```python
from openbb_terminal.sdk import openbb
p = openbb.portfolio.load("openbb_terminal/miscellaneous/portfolio_examples/holdings/example.csv")
output = openbb.portfolio.es(p)
```

---
