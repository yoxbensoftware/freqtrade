# Release Notes: Gate.io Local Setup

This repository snapshot adds a reproducible local setup for Gate.io dry-run usage.

## Included changes

- Added a local Gate.io dry-run example config.
- Added a separate webserver example config for download and backtest pages.
- Added a dedicated setup guide for local usage.
- Added concise README usage notes in English and Turkish.
- Verified download and backtest flow with `SampleStrategy` on `BTC/USDT` and `ETH/USDT`.

## Verified workflow

1. Start trade UI on `8080`.
2. Start standalone webserver UI on `8081`.
3. Download `5m` data.
4. Run backtesting for `SampleStrategy`.

## Reference backtest run

- Exchange: `gateio`
- Trading mode: `spot`
- Pairs: `BTC/USDT`, `ETH/USDT`
- Timeframe: `5m`
- Timerange: `20260407-20260414`
- Starting balance: `1000 USDT`
- Final balance: `1002.398 USDT`
- Total trades: `8`