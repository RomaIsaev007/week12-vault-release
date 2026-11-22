# Week 12 — Final Verification Checklist (Devnet)

- **Wallet:** `EUpX3WNe7Uv3YP1nya2h2bBo6sRJCMVdDcsFhLc6fESQ`
- **Token:** `romaisaev` (`ROMA`, Token-2022)
- **Mint:** `5mYLe...XU9az`
- **Create & Metadata Tx:** `3YgVN...yUiFz`
- **Transfer Tx:** `2jTDf...jgZeg`

## Checks
- [x] Vault PDA seed uses `["vault", authority]`
- [x] `amount > 0` validation on `deposit` and `withdraw`
- [x] Balance guard (`total_deposited >= amount`) and checked math
- [x] No private keys or seed phrases in repository
