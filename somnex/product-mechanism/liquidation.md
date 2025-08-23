# Liquidation

### Liquidation

Somnex applies risk parameters per market to protect traders and liquidity providers.

### Key definitions

* Initial Margin Requirement (IMR): IMR = IMF × position\_notional.
* Initial Margin Fraction (IMF): % set per market/asset class.
* Maintenance Margin Requirement (MMR): MMR = MMF × position\_notional.
* Maintenance Margin Fraction (MMF): % set per market/asset class.
* Equity Value: unrealized PnL + unrealized fees (funding, borrow, open/close, liquidation) + collateral value.
* Collateral Value: Σ(collateral amounts × price × LTV).

### Liquidation condition

A position becomes eligible for liquidation when Equity Value ≤ MMR. The platform may partially or fully reduce the position to restore margin health.

### Fees affecting equity

* Trading fee (fixed): small % of notional on open/close.
* Funding rate (dynamic): periodic transfer between longs and shorts to align perp price with spot.
* Borrow fee (dynamic): variable hourly fee driven by utilization. Formula: (assets\_borrowed / total\_assets\_in\_pool) × 0.01% per hour.

Example: If 40% of a pool is borrowed → 0.40 × 0.01% = 0.004% per hour (\~0.096% per 24h).
