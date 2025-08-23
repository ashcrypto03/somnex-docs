# Terminology

### Terminology

Aggregator: Router that searches across multiple DEXs/pools to execute swaps at the best total cost (price + slippage + gas).

AMM: Automated Market Maker; smart-contract pool that prices trades algorithmically using token reserves.

V2 Pool (Volatile): Full-range AMM suitable for volatile/meme assets.

V3 Pool (Concentrated): Liquidity deployed within chosen price ranges for higher capital efficiency and fee capture.

Perp (Perpetual Contract): Derivative without expiry; uses funding rate to anchor to spot.

SPLP: Perp Pool LP; single-sided USDC liquidity provider for perps; earns protocol fees.

Funding Rate: Periodic payment between longs and shorts to keep perp price close to spot.

Borrow Fee: Hourly fee for borrowing assets; (assets\_borrowed / total\_assets\_in\_pool) × 0.01% per hour.

Smart Routing: Algorithm that splits orders across venues/paths to minimize total cost.

Slippage: Difference between expected and executed price due to depth/volatility.

IMR / IMF: Initial Margin Requirement / Fraction; equity required to open/increase a position.

MMR / MMF: Maintenance Margin Requirement / Fraction; equity required to keep a position open.

Equity Value: Unrealized PnL + unrealized fees + collateral value.

Collateral Value: Sum of collateral assets × price × LTV.

Bonding Curve: Price-of-token follows a deterministic curve as tokens are bought/sold during launch.

Referral Rebate/Discount: Fee share to referrer and discount to invitee based on tier.
