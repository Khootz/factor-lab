# 2026-10-05 — Night versus the trading day

## Takeaway

The return sits in the night. Buying at the close and selling at the next open beat buying at the open and selling at the close, in the last year, the last ten years, and since 2005. Both halves of the long windows agree.

No transaction fee is included. These numbers are the price change only.

## What was tested

- Night: buy the close, sell the next open, cash while the market is open.
- Day: buy the open, sell the close, cash overnight.
- Hold: own the close the whole time.
- Names: the Wind daily book, forward-adjusted, through 2026-09-30. Index levels and VIX are left out. A name counts in a window only if it covers that window.
- The book in the chart is an equal mix, reset every day. The median name is the fairer summary. SPY is the plain reference.

Two bad prints were removed: one impossible bar in 3533-TW on 9 June 2009, and a missed 4-for-1 split in the SoftBank ADR on 8 January 2026. Dividends sit in the night, because the prices are adjusted for them.

## Typical name

Yearly return, no transaction fee. The night beat the day on 38 of 51 names last year, 38 of 44 over ten years, and 32 of 37 since 2005.

| Window | Night | Day | Holding |
|---|---:|---:|---:|
| Last year | +20.6% | −7.0% | +14.7% |
| Last ten years | +18.5% | −2.4% | +15.9% |
| Since 2005 | +20.6% | −1.0% | +13.6% |

## SPY alone

No transaction fee.

| Window | Night | Day | Holding |
|---|---:|---:|---:|
| Last year | +18.6% | −1.7% | +16.6% |
| Last ten years | +12.1% | +2.8% | +15.3% |
| Since 2005 | +9.2% | +1.6% | +10.9% |

## Equal mix of the names

Reset every day, so this climbs faster than a typical name. It is this list, not the market. No transaction fee.

| Window | Night | Day | Holding | Worst fall, night | Worst fall, holding |
|---|---:|---:|---:|---:|---:|
| Last year | +50.4% | −15.8% | +25.3% | −7.9% | −10.5% |
| Last ten years | +29.9% | −2.7% | +25.7% | −29.2% | −29.9% |
| Since 2005 | +27.3% | −1.2% | +24.9% | −32.5% | −53.9% |

The night was positive in both halves of the ten-year window and in both halves since 2005. The day was negative in both.

Over the ten years the day earned the return for six names: 0005-HK, 0939-HK, 0941-HK, 1398-HK, AAPL, and SFTBY.

## Charts

![Growth of one dollar, no transaction fee](overnight-day-2026-10-05.png)

![Each name, last ten years, no transaction fee](overnight-day-by-name-2026-10-05.png)

The test that produced these numbers lives in the Joywin desk at `technical/smc/overnight.py`. This file is only the record.
