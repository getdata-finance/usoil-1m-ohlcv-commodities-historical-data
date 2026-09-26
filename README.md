# USOIL 1m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_053_800_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 1m OHLCV commodities historical data** — ultra high-quality 1m OHLCV for **WTI Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **WTI Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **6,053,800** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `USOIL_1m.csv` (179,290 rows, `2026-03-26` -> `2026-09-25`, 11.38 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **6,053,800** `1m` rows (full `1m`: 5,981,180), **11 timeframes**, `2008-09-10` -> `2026-09-25`.

## Download sample

**[USOIL_1m.csv](https://github.com/getdata-finance/usoil-1m-ohlcv-commodities-historical-data/blob/main/USOIL_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-1m-ohlcv-commodities-historical-data/main/USOIL_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/usoil-1m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usoil-1m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/usoil-1m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usoil](https://getdata.finance/datasets/usoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 179,290 | **6,053,800** |
| Size | 11.38 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Period | `2026-03-26` -> `2026-09-25` | `2008-09-10` -> `2026-09-25` |
| File | `USOIL_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/usoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:28:00+00:00 | 91.332 | 91.333 | 91.283 | 91.288 | 47 |
| 2026-03-26T02:29:00+00:00 | 91.288 | 91.358 | 91.288 | 91.358 | 62 |
| 2026-03-26T02:30:00+00:00 | 91.358 | 91.368 | 91.308 | 91.363 | 73 |
| 2026-03-26T02:31:00+00:00 | 91.363 | 91.473 | 91.363 | 91.473 | 128 |
| 2026-03-26T02:32:00+00:00 | 91.473 | 91.479 | 91.422 | 91.462 | 150 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T20:40:00+00:00 | 92.677 | 92.682 | 92.592 | 92.592 | 55 |
| 2026-09-25T20:41:00+00:00 | 92.592 | 92.599 | 92.567 | 92.569 | 65 |
| 2026-09-25T20:42:00+00:00 | 92.569 | 92.589 | 92.548 | 92.563 | 64 |
| 2026-09-25T20:43:00+00:00 | 92.563 | 92.563 | 92.527 | 92.539 | 34 |
| 2026-09-25T20:44:00+00:00 | 92.539 | 92.539 | 92.473 | 92.492 | 60 |

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

df = pd.read_csv('USOIL_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USOIL_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USOIL_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[getdata.finance](https://getdata.finance/datasets/usoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **6,053,800** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**

---
*GetData · USOIL 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usoil)*
