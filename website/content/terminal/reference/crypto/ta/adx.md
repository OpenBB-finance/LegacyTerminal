---
title: adx
description: This page provides detailed instructions on using the ADX, a Welles Wilder
  style moving average of the Directional Movement Index. It includes usage examples
  and parameter specifications.
keywords:
- ADX
- Welles Wilder
- Directional Movement Index
- DX
- trend strength
- parameters
- n_length
- n_scalar
- n_drift
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/ta/adx - Reference | OpenBB Terminal Docs" />

The ADX is a Welles Wilder style moving average of the Directional Movement Index (DX). The values range from 0 to 100, but rarely get above 60. To interpret the ADX, consider a high number to be a strong trend, and a low number, a weak trend.

### Usage

```python
adx [-l N_LENGTH] [-s N_SCALAR] [-d N_DRIFT]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| n_length | length | 14 | True | range(1, 100) |
| n_scalar | scalar | 100 | True | None |
| n_drift | drift | 1 | True | range(1, 100) |

![adx](https://user-images.githubusercontent.com/46355364/154309667-c67f6078-822f-452d-9853-ffffa9172670.png)

---
