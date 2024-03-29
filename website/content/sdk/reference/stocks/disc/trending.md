---
title: trending
description: The Trending page provides a list of trending articles from OpenBB, it
  allows customization of the quantity of articles displayed with a default value
  set at 5.
keywords:
- Trending articles
- Source code
- Stocks discovery
- Article limit customization
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks.disc.trending - Reference | OpenBB SDK Docs" />

Returns a list of trending articles

Source Code: [[link](https://github.com/OpenBB-finance/OpenBBTerminal/tree/main/openbb_terminal/stocks/discovery/seeking_alpha_model.py#L100)]

```python
openbb.stocks.disc.trending(limit: int = 5)
```

---

## Parameters

| Name | Type | Description | Default | Optional |
| ---- | ---- | ----------- | ------- | -------- |
| limit | int | Number of articles | 5 | True |


---

## Returns

| Type | Description |
| ---- | ----------- |
| list | Trending articles list |
---
