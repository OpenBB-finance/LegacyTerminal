---
title: info
description: This page provides information about a command 'info' that displays option
  data. It includes details about usage, parameters, and examples of how to use the
  command in a Python environment. The page is particularly useful for individuals
  interested in stock options data.
keywords:
- Info command
- Option data
- Python environment
- Stock options data
- Command usage
- Command parameters
- Command examples
- Implied volatility
- Historical volatility
- Put/Call Vol ratio
- Today's volume
- Open interest
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/options/info - Reference | OpenBB Terminal Docs" />

Display option data [Source: Barchart.com]

### Usage

```python
info
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 16, 09:09 (🦋) /stocks/options/ $ info
                Options Information
┏━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                       ┃                         ┃
┡━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━┩
│ Implied Volatility    │   31.27%  (  -3.04%)    │
├───────────────────────┼─────────────────────────┤
│ Historical Volatility │   54.71%                │
├───────────────────────┼─────────────────────────┤
│ IV Percentile         │   81%                   │
├───────────────────────┼─────────────────────────┤
│ IV Rank               │   37.04%                │
├───────────────────────┼─────────────────────────┤
│ IV High               │   53.44% on 02/03/22    │
├───────────────────────┼─────────────────────────┤
│ IV Low                │   18.22% on 08/27/21    │
├───────────────────────┼─────────────────────────┤
│ Put/Call Vol Ratio    │  0.85                   │
├───────────────────────┼─────────────────────────┤
│ Today's Volume        │  143,740                │
├───────────────────────┼─────────────────────────┤
│ Volume Avg (30-Day)   │  241,667                │
├───────────────────────┼─────────────────────────┤
│ Put/Call OI Ratio     │  0.98                   │
├───────────────────────┼─────────────────────────┤
│ Today's Open Interest │  582,975                │
├───────────────────────┼─────────────────────────┤
│ Open Int (30-Day)     │  721,047                │
└───────────────────────┴─────────────────────────┘
```
---
