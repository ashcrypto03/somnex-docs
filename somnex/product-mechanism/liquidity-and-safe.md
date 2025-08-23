# Liquidity and Safe

### Liquidity and Safe

### Liquidity architecture

* Aggregator routing taps Somnex V2/V3, QuickSwap, Somnia Exchange, and others for best execution.
* AMM liquidity via V2 (full-range) and V3 (concentrated ranges).
* Perp liquidity (SPLP) is single-sided USDC; utilization drives borrow fees.

### Safety considerations

* Single-sided SPLP avoids impermanent loss but returns vary with market conditions.
* V3 management risk: narrow ranges can idle liquidity; maintain ranges proactively.
* Perps risk: liquidation if equity < MMR; funding/borrow fees influence PnL.
