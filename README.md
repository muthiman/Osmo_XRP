## Proposal: Add `XRP.int3` to Alloyed XRP

### Overview

This proposal seeks to add **`XRP.int3`**—XRP bridged from XRP to Osmosis via the Bitfrost Bridge as a new constituent of **Alloyed XRP**. The proposal includes setting an **initial static cap of 100%**. The rationale for this 100% cap rather than the standard 20% is due to the unique nature of the current alloy , which is comprised of a single asset (XRP.core). This alloy has extremely low liquidity and in order for the pool to service general purpose, we require exceeding the total liquidity of the alloy.

---

### Background: Alloyed XRP

**Alloyed XRP** is already established as the canonical XRP representation on Osmosis. It currently has a circulating supply of approximately **\$140k** on Osmosis. The asset is composed of one bridged variant of XRP:

| Variant           | Origin                      | Supply |
| ----------------- | --------------------------- | --- |
| `XRP.core`        | Coreum                      | 100% |

---

### Proposed Addition

This proposal recommends including **`XRP.int3`** in the Alloyed XRP basket, allowing deposits via the Bitfrost bridge.

* **Initial Cap**: 100%
* **Initial Exposure**: \~\$200,000
* **Rationale**: The cap is set conservatively to mitigate risk associated with the deployment of a new bridging product. This limit can be adjusted via governance as the bridge gains usage and demonstrates stability.

---

### About Bitfrost

**Bitfrost** is a high-performance Layer-1 blockchain implementing a novel leaderless, dynamic Threshold Signature Scheme (TSS) for secure cross-chain asset transfers. Built using a modified Cosmos SDK with Proof-of-Authority consensus, Bitfrost establishes trust-minimised bridges between heterogeneous blockchain architectures, particularly focusing on unlocking UTXO-based assets and now **XRP** for broader ecosystem utility. Bitfrost is developing a **permissionless**, **secure**, and **cost-effective** asset bridge between XRP and the Cosmos ecosystem through the Cosmos Hub.

* **Learn more**: https://int3face.zone/ 

---

### Bitfrost's contributions to Osmosis so far

* Bitfrost is currently serving Osmosis with bridged Doge as **Doge.int3**. Doge.int3 comprises 100% of the doge alloy. This pool is one of the most active pools on Osmosis and has traded over $50M in volume.
* Morover, Bitfrost has contributed to the Toncoin alloy pool as Ton.int3, although this makes up only 0.6% of the alloy. 

---

### Additional Resources

* **Alloyed Assets Blog Post**: [Read here](#)
* **Alloyed Dashboard**: [View statistics](#)

---

**Target On-Chain Governance Date**: **May 19, 2025**

