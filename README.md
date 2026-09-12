# GER30 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-77_438_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 1h OHLCV index historical data** — ultra high-quality 1h OHLCV for **DAX 40 (GER30)**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **77,438** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `GER30_1h.csv` (2,589 rows, `2026-03-12` -> `2026-09-11`, 239.98 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **77,438** `1h` rows (full `1m`: 2,329,742), **11 timeframes**, `2008-09-10` -> `2026-09-11`.

## Download sample

**[GER30_1h.csv](https://github.com/getdata-finance/ger30-1h-ohlcv-index-historical-data/blob/main/GER30_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-1h-ohlcv-index-historical-data/main/GER30_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-1h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-1h-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-1h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 2,589 | **77,438** |
| Size | 239.98 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Period | `2026-03-12` -> `2026-09-11` | `2008-09-10` -> `2026-09-11` |
| File | `GER30_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/ger30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T03:00:00+00:00 | 23251.29 | 23272.31 | 23205.31 | 23245.55 | 3887 |
| 2026-03-12T04:00:00+00:00 | 23245.55 | 23283.05 | 23234.3 | 23259.05 | 1901 |
| 2026-03-12T05:00:00+00:00 | 23259.05 | 23324.04 | 23255.29 | 23315.55 | 3676 |
| 2026-03-12T06:00:00+00:00 | 23315.55 | 23370.04 | 23295.29 | 23353.55 | 2449 |
| 2026-03-12T07:00:00+00:00 | 23353.55 | 23454.55 | 23344.55 | 23445.54 | 7737 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T15:00:00+00:00 | 25516.99 | 25587.5 | 25511.99 | 25547.01 | 11877 |
| 2026-09-11T16:00:00+00:00 | 25547.01 | 25569.15 | 25533.64 | 25562.64 | 7098 |
| 2026-09-11T17:00:00+00:00 | 25562.64 | 25582.66 | 25560.14 | 25562.66 | 4258 |
| 2026-09-11T18:00:00+00:00 | 25562.66 | 25570.66 | 25541.64 | 25545.65 | 4532 |
| 2026-09-11T19:00:00+00:00 | 25545.65 | 25558.15 | 25540.64 | 25553.89 | 2792 |

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

df = pd.read_csv('GER30_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GER30_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **77,438** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30)*
