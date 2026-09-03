# USOIL 1m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_029_418_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 1m OHLCV commodities historical data** — ultra high-quality 1m OHLCV for **WTI Crude Oil**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **WTI Crude Oil** (Commodities)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **6,029,418** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `USOIL_1m.csv` (55,440 rows, `2026-07-07` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **6,029,418** `1m` rows, **11 timeframes**, `2008-09-10` -> `2026-09-02`.

## Download sample

**[USOIL_1m.csv](https://github.com/getdata-finance/usoil-1m-ohlcv-commodities-historical-data/blob/main/USOIL_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-1m-ohlcv-commodities-historical-data/main/USOIL_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **6,029,418** |
| Period | `2026-07-07` -> `2026-09-02` | `2008-09-10` -> `2026-09-02` |
| File | `USOIL_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`USOIL_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T18:46:00+00:00 | 70.379 | 70.528 | 70.367 | 70.514 | 115 |
| 2026-07-07T18:47:00+00:00 | 70.514 | 70.657 | 70.499 | 70.637 | 158 |
| 2026-07-07T18:48:00+00:00 | 70.637 | 70.868 | 70.637 | 70.842 | 429 |
| 2026-07-07T18:49:00+00:00 | 70.842 | 71.069 | 70.817 | 70.842 | 567 |
| 2026-07-07T18:50:00+00:00 | 70.842 | 70.884 | 70.758 | 70.872 | 219 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 91.417 | 91.454 | 91.362 | 91.412 | 146 |
| 2026-09-02T01:57:00+00:00 | 91.412 | 91.469 | 91.387 | 91.433 | 179 |
| 2026-09-02T01:58:00+00:00 | 91.433 | 91.433 | 91.293 | 91.317 | 154 |
| 2026-09-02T01:59:00+00:00 | 91.317 | 91.343 | 91.242 | 91.298 | 156 |
| 2026-09-02T02:00:00+00:00 | 91.298 | 91.298 | 91.258 | 91.287 | 72 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full USOIL archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**
