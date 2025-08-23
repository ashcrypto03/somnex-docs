# Background

### Background

Somnex is the native, one-stop DeFi platform on Somnia—combining a best-price swap aggregator, perpetuals, a multi-strategy liquidity layer (V2, V3, and single-sided perp pools), and a one-click meme launchpad.

### Why Somnex exists

* DeFi is fragmented: users hop between apps for swaps, perps, and token launches.
* Fragmentation leads to worse execution, idle capital, and poor UX.
* Somnex unifies the core flows on a single, fast L1 (Somnia).

### Somnia foundation

Somnia is a high-performance, EVM-compatible Layer 1 with sub-second finality and a stated capability of 1,000,000+ TPS—built for real-time, fully on-chain apps (games, social, DeFi).

### High-level architecture

* SpotX Aggregator: indexes liquidity from Somnex V2/V3, QuickSwap, Somnia Exchange, etc., then performs smart routing for the best total execution (price + slippage + gas).
* Perpetuals: on-chain perps for 50+ markets with up to 50× leverage.
* Liquidity Layer: V2 (volatile AMM), V3 (concentrated ranges), and Perp Pools (SPLP: single-sided USDC).
* Meme Launchpad: one-click token creation (name/ticker/logo), bonding-curve sale, auto-listing on Somnex Swap.

![](<../.gitbook/assets/0 (1).jpeg>)

_Somnex Aggregator Flywheel_

![](<../.gitbook/assets/1 (2).png>)

_Somnex Perpetual Trade Flywheel_
