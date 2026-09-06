# fantom_trading_bot_2

**Classification: ARCHIVED** (historical sketch). Not an ACTIVE dependency.

Governance: [ADL-Governance](https://github.com/beyond-repair/ADL-Governance)

## What this repository is

A 2023-era Python sketch (`fantom 19.py`) describing strategy *names* (trend, breakout, swing, scalp) plus placeholder functions. Helpers return constants (`0.0`, `True`, `False`). There is no exchange client, no tests, no CI, and no measured PnL.

## What this repository is not

- Not a live trading system.
- Not a validated strategy.
- Not a security-reviewed MEV implementation.
- Enumerated names `FrontRunning` and `SandwichBot` are **unimplemented stubs**. They are not product features and must not be treated as operational capability.

## Successor cluster (not proven ports)

Related names in the portfolio (no automatic SUPERSEDES claim this cycle):

- `fantom-smart-contracts-first-bot`
- `ftmA.I.bot`
- `FortiTrade_Multi-Strategy`

Canonical product trading stack is **not** asserted here. BlockSwarm remains the on-chain SAGF owner per governance.

## Claims

| Claim | Level |
|-------|-------|
| File exists and parses as incomplete Python | empirical (tree) |
| Strategies execute or profit | **unsupported** |
| Safe to run against funds | **false** |
