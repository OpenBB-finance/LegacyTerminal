---
title: norm
description: This page provides guidelines on using the 'norm' function to test whether
  particular data is normally distributed. It covers functionality and parameter description,
  and also includes histogram examples for a clear understanding.
keywords:
- data normalization
- data distribution
- histogram
- plot
- dataset
- data testing
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="econometrics /norm - Reference | OpenBB Terminal Docs" />

Test whether the used data is normally distributed.

### Usage

```python
norm -v {} [-p]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| column | The dataset.column you want to test normality for | None | False | None |
| plot | Whether you wish to plot a histogram to visually depict normality | False | True | None |

![histogram_adj_close_tsla](https://user-images.githubusercontent.com/46355364/155514663-90cb210a-002a-49fe-b7d3-29d9f2aeb5ac.png)

![histogram_returns_msft](https://user-images.githubusercontent.com/46355364/155514702-f46da473-b340-4d68-b31e-f96606c4ed00.png)

---
