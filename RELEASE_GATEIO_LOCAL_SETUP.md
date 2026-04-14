# Gate.io Local Setup

This release packages a verified local Gate.io dry-run setup for this repository.

## Included

- Gate.io spot dry-run example config
- Separate webserver config for download and backtest pages
- README quick usage notes in English and Turkish
- Dedicated local setup documentation page
- Release notes page in docs

## Verified flow

1. Start the trade UI on `8080`
2. Start the download/backtest UI on `8081`
3. Download `BTC/USDT` and `ETH/USDT` `5m` candles
4. Run backtesting with `SampleStrategy`

## Reference backtest

- Exchange: `gateio`
- Trading mode: `spot`
- Pairs: `BTC/USDT`, `ETH/USDT`
- Timeframe: `5m`
- Timerange: `20260407-20260414`
- Starting balance: `1000 USDT`
- Final balance: `1002.398 USDT`
- Total profit: `2.398 USDT`
- Total trades: `8`

## Notes

- `user_data/config.json` is intentionally ignored and is not part of the repository.
- Replace placeholder secrets in the example config files before use.