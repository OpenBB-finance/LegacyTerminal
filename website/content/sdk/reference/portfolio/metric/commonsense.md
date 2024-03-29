---
title: commonsense
description: This documentation page includes details on how to get the commonsense
  ratio for a portfolio within the OpenBB-framework using Python. It explains the
  use of the PortfolioEngine class and provides examples using the openbb.portfolio.load
  and openbb.portfolio.metric.commonsense functions.
keywords:
- commonsense ratio
- PortfolioEngine
- openbb.portfolio.load
- openbb.portfolio.metric.commonsense
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="portfolio.metric.commonsense - Reference | OpenBB SDK Docs" />

Get common sense ratio

Source Code: [[link](https://github.com/OpenBB-finance/OpenBBTerminal/tree/main/openbb_terminal/portfolio/portfolio_model.py#L1448)]

```python
openbb.portfolio.metric.commonsense(portfolio_engine: portfolio_engine.PortfolioEngine)
```

---

## Parameters

| Name | Type | Description | Default | Optional |
| ---- | ---- | ----------- | ------- | -------- |
| portfolio_engine | PortfolioEngine | PortfolioEngine class instance, this will hold transactions and perform calculations.<br/>Use `portfolio.load` to create a PortfolioEngine. | None | False |


---

## Returns

| Type | Description |
| ---- | ----------- |
| pd.DataFrame | DataFrame of the portfolios and the benchmarks common sense ratio during different time periods |
---

## Examples

```python
from openbb_terminal.sdk import openbb
p = openbb.portfolio.load("openbb_terminal/miscellaneous/portfolio_examples/holdings/example.csv")
output = openbb.portfolio.metric.commonsense(p)
```

---
