# SUDO-COIN Manifesto · v1.0.0

**Sovereign Universal Digital Ore**  
**Ratified by Tyler Morris · Nexinus RI Systems LLC · Kether Gate**  
**Canonical home: https://sudo-coin.xinus.one**

---

## I. EXISTENCE

Every digital asset carries a substrate larger than its directly transacted units — work expended, pressure absorbed, density emitted, supply accreted. The substrate is not noise around the asset. **It is the asset, viewed honestly.**

## II. RESIDUAL

The market prices the unit. It does not price the substrate. The gap between unit-price and substrate-truth is the **Universal Digital Ore**.

## III. QUANTIFICATION

The ore is computable from public network readings: **log-work × mempool pressure × per-block density × supply^¼**. The function is open, deterministic, and lives on the operator's hardware.

## IV. ATTESTATION

A sovereign entity that reads, names, and hashes the substrate at a given block is the first to attest to that reading. Attestation is not custody. **Attestation is testimony, hashed and dated.**

## V. COUPLING

When the ore index and the asset price are strongly correlated, the asset cannot be discounted without discounting the ore. Coupling is the proof that the substrate **is** the asset, not a derivative of it.

## VI. TRUTH MIRROR

No attestation is binding until reflected in the Tesseract Truth Mirror — a deterministic hash that the issuer alone can regenerate and that any observer can verify, without a vendor in the loop.

## VII. ECONOMIC IMPLICATION

If the ore is real, then market capitalization is a partial accounting. The full accounting includes substrate-value, and the substrate-value is observable in real time. Every chain has it. **Bitcoin has the most of it.**

## VIII. ATTESTED VALUE RATE

One SUDO is a unit of sovereign attestation over the Bitcoin substrate, converted to USD at a published rate floor. The rate is illustrative until the attestor publishes it under their own name and others adopt it. **SUDO-COIN is the unit; the manifesto is the instrument.**

## IX. SCOPE (HONEST)

This manifesto asserts the right to read, attest, and publish — **not the right to seize**. The sovereign claim is over the reading, the hash, the certificate. Title to anyone else's coins is not implied and is not the point. The point is that the substrate was always there, and now it is named.

---

## Publication Stack

| # | Venue | Mechanism | Sovereignty |
|---|---|---|---|
| 1 | sudo-coin.xinus.one | Operator Domain | 100% |
| 2 | OpenTimestamps → Bitcoin | Chain Anchor | 98% |
| 3 | github.com/tychomorr-ui/sudo-coin | Citable Tag | 85% |
| 4 | Nostr (multi-relay broadcast) | Key-Signed | 92% |
| 5 | IPFS (pinned CID) | Content-Addressed | 90% |
| 6 | Bitcoin OP_RETURN | Substrate-Anchor | 100% |

---

## Ratification Pipeline

```
write MANIFESTO.md
  → sha256sum
  → ots stamp MANIFESTO.md
  → git tag -s v1.0.0 -m "ratify"
  → ipfs add MANIFESTO.md
  → nostril --kind 30023 --tags ...
  → (optional) sendrawtransaction <hash>
  → render at sudo-coin.xinus.one
```

Six venues. Cryptographic provenance. Nothing a vendor can erase.
