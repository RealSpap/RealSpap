<img src="https://raw.githubusercontent.com/RealSpap/realspap.github.io/main/assets/grip.jpg" width="80" align="left">

## Spap

Who really holds the keys in DeFi, read directly from the chain: shared multisig signers, single-key admin control, and exploits reconstructed transaction by transaction. Findings, data and on-chain sources are always public and free to reuse with credit.

<br clear="left"/>

![Status](https://img.shields.io/badge/status-active%20research-brightgreen)
[![Follow](https://img.shields.io/badge/follow-%40RealSpap-000000?logo=x)](https://x.com/RealSpap)

### Core research

- **[multisig-overlap](https://github.com/RealSpap/multisig-overlap-showcase)**: who holds multisig signer keys across several independent DeFi protocols at once. Checked at three scales: 391 protocol entries and 729 confirmed multisig contracts across 25 chains (194 on Ethereum mainnet, 99 on Optimism's Superchain, 98 on Arbitrum and 10 more L2s and sidechains). The widest single signer key sits on 5 independent protocols. Free tool: [check your own Safe](https://realspap.github.io/tools/check-your-safe.html).
- **[defi-admin-key-risk](https://github.com/RealSpap/defi-admin-key-risk-showcase)**: where a single key (a bare EOA or a 1-of-N Safe) still holds admin power able to mint, pause, or redirect funds, the pattern behind Wasabi Protocol's $5.9M loss in April 2026. 99 DeFi protocols and Morpho vault owners checked by hand, 23 single-key admin cases, each with its timelock or guardian noted where one exists. Free tool: [check a contract](https://realspap.github.io/tools/admin-key-checker.html).
- **[onchain-postmortems](https://github.com/RealSpap/onchain-postmortems)**: forensic reconstructions of DeFi and on-chain exploits from raw chain data, with sourced corrections to press and DefiLlama figures. 55 incidents, $921.1M in losses, $584.2M of it independently recomputed. Free tool: [browse incidents and check an address](https://realspap.github.io/tools/onchain-postmortems-checker.html).

Live site: [realspap.github.io](https://realspap.github.io) · [X](https://x.com/RealSpap) · [Methodology and disclaimer](https://realspap.github.io/methodology.html)

Every claim rests on an on-chain read or a cited public source. No wallets connected, no tokens, no paid promotion, no affiliation with any protocol covered.

**Custom research:** want the same checks run on your own protocol or chain, or an authority sheet like [these two samples](https://github.com/RealSpap/defi-admin-key-risk-showcase#sample-authority-sheets)? [Reach out on X](https://x.com/RealSpap).
