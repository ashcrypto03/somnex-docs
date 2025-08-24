# Swap Aggregator

### Swap Aggregator

Somnex SpotX is a smart swap aggregator that searches liquidity across the Somnia ecosystem and executes the best total price (price + slippage + gas). It combines Somnex V2/V3, QuickSwap, Somnia Exchange, and other venues via real‑time smart routing.

<figure><img src="../.gitbook/assets/image (5).png" alt="SpotX — Swap Aggregator UI"><figcaption></figcaption></figure>

_SpotX — Swap Aggregator UI_

### How it works

* Indexes pools across supported DEXs and Somnex pools.
* Simulates candidate paths and splits your order to minimize total cost.
* Displays route badges: Best Price • Smart Route • Across all DEXes.
* Minimizes slippage and gas while maximizing execution probability.

### How to use

1. Open [Somnex](https://somnex.xyz/) → SpotX and connect your wallet.
2. In the Pay field, choose the token and enter the amount.
3. In the To field, choose the token you want to receive.
4. Review the route preview, minimum received, slippage tolerance, and estimated gas.
5. Click Approve (first time) then Swap → Confirm in wallet.

### Tips

* If a route fails, slightly increase slippage tolerance or try a smaller size.
* Use stable pairs for lower slippage; volatile pairs may require higher tolerance.
* Verify token contracts to avoid imposters.

### Fees

Swap fee: TBD by venue. Network gas applies. The aggregator chooses the best combination of venue fees + gas to minimize your all‑in cost.

### Troubleshooting

* Insufficient liquidity: reduce size or try a different token path.
* Insufficient allowance: click Approve and confirm in your wallet.
* Price updated: re‑quote appears when market moves; review and accept.
