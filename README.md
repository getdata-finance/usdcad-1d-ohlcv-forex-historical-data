# USDCAD 1d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-7_724_rows-blue)](https://getdata.finance/datasets/usdcad) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdcad)

### -> [**Download the full USDCAD dataset on getdata.finance**](https://getdata.finance/datasets/usdcad)

**USDCAD 1d OHLCV forex historical data** — ultra high-quality 1d OHLCV for **US Dollar / Canadian Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **US Dollar / Canadian Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdcad) · **7,724** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `USDCAD_1d.csv` (732 rows, `2024-05-21` -> `2026-09-25`, 80.61 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdcad)** — **7,724** `1d` rows (full `1m`: 9,133,625), **11 timeframes**, `2001-11-28` -> `2026-09-25`.

## Download sample

**[USDCAD_1d.csv](https://github.com/getdata-finance/usdcad-1d-ohlcv-forex-historical-data/blob/main/USDCAD_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdcad-1d-ohlcv-forex-historical-data/main/USDCAD_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdcad-1d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdcad-1d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdcad-1d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdcad](https://getdata.finance/datasets/usdcad)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdcad))** |
|---|--:|---|
| Instrument | US Dollar / Canadian Dollar · Forex | US Dollar / Canadian Dollar · Forex |
| Timeframes | `1d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1d rows | 732 | **7,724** |
| Size | 80.61 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdcad) |
| Period | `2024-05-21` -> `2026-09-25` | `2001-11-28` -> `2026-09-25` |
| File | `USDCAD_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdcad) |
| Coverage report | — | [USDCAD coverage](https://getdata.finance/coverage/usdcad) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdcad)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/usdcad) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCAD_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-05-21T00:00:00+00:00 | 1.36116 | 1.36634 | 1.36026 | 1.36292 | 164893 |
| 2024-05-22T00:00:00+00:00 | 1.36292 | 1.36939 | 1.36116 | 1.36908 | 162561 |
| 2024-05-23T00:00:00+00:00 | 1.36908 | 1.37433 | 1.36566 | 1.37352 | 196451.59344 |
| 2024-05-24T00:00:00+00:00 | 1.37352 | 1.3741 | 1.36503 | 1.36641 | 146402 |
| 2024-05-26T00:00:00+00:00 | 1.36641 | 1.36743 | 1.36614 | 1.36735 | 3499.18368 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-21T00:00:00+00:00 | 1.39946 | 1.40391 | 1.39905 | 1.40335 | 137512 |
| 2026-09-22T00:00:00+00:00 | 1.40335 | 1.40842 | 1.40245 | 1.40659 | 191425 |
| 2026-09-23T00:00:00+00:00 | 1.40659 | 1.41098 | 1.4064 | 1.4104 | 192003 |
| 2026-09-24T00:00:00+00:00 | 1.4104 | 1.41497 | 1.40966 | 1.41474 | 196936 |
| 2026-09-25T00:00:00+00:00 | 1.41474 | 1.41544 | 1.41333 | 1.41378 | 152112 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCAD_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCAD_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('USDCAD_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1d')
print(pf.stats())
```

## Download full data

The complete **USDCAD** archive on **[getdata.finance](https://getdata.finance/datasets/usdcad)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **7,724** rows at `1d`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCAD dataset on getdata.finance](https://getdata.finance/datasets/usdcad)**

---
*GetData · USDCAD 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdcad)*
