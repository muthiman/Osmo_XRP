## Proposal: Add `XRP.int3` to Alloyed XRP

### Overview

This proposal seeks to add **`XRP.int3`**—XRP bridged from XRP to Osmosis via the Bitfrost Bridge as a new constituent of **Alloyed XRP**. The proposal includes setting an **initial static cap of 20%** to limit exposure while adoption matures.

---

### Background: Alloyed XRP

**Alloyed XRP** is already established as the canonical XRP representation on Osmosis. It currently has a circulating supply of approximately **\$100k** on Osmosis. The asset is composed of multiple bridged variants of XRP, each with an individual cap to manage risk:

| Variant           | Origin                      | Cap |
| ----------------- | --------------------------- | --- |
| `XRP.axl`         | Axelar (Ethereum)           | 75% |
| `XRP.kava`        | IBC from Kava EVM           | 75% |
| `XRP.wh`          | Wormhole (Ethereum)         | 75% |
| `XRP.pica`        | Picasso (Solana)            | 40% |
| `XRP.inj`         | Injective Bridge (Ethereum) | 75% |
| `XRP.rt`          | Router Bridge               | 5%  |
| `XRP.e.op.axl`    | Axelar via Optimism         | 20% |
| `XRP.e.arb.axl`   | Axelar via Arbitrum         | 20% |
| `XRP.e.matic.axl` | Axelar via Polygon          | 20% |

---

### Proposed Addition

This proposal recommends including **`XRP.int3`** in the Alloyed XRP basket, allowing deposits via the Bitfrost bridge.

* **Initial Cap**: 20%
* **Initial Exposure**: \~\$200,000
* **Rationale**: The cap is set conservatively to mitigate risk associated with the deployment of a new bridging product. This limit can be adjusted via governance as the bridge gains usage and demonstrates stability.

---

### About Bitfrost

**Bitfrost** is the first interoperability solution offering a more efficient and transparent mechanism for cross-chain asset transfers for UTXOs and XRP. It enables **permissionless**, **secure**, and **cost-effective** bridging between Ethereum and the Cosmos ecosystem through the Cosmos Hub.

* **Learn more**: https://int3face.zone/ 

---

### Additional Resources

* **Alloyed Assets Blog Post**: [Read here](#)
* **Alloyed Dashboard**: [View statistics](#)

---

**Target On-Chain Governance Date**: **May 19, 2025**

