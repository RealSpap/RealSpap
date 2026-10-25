Contact: [contact@realspap.com](mailto:contact@realspap.com)

<img src="https://raw.githubusercontent.com/RealSpap/realspap.github.io/main/assets/grip.jpg" width="80" align="left">

## RealSpap

Who can change a DeFi contract, how fast, and what we could not read. On-chain research and a public authority oracle (testnet). Replay commands included.

Findings, data and on-chain sources are public. Licence per repository: CC BY 4.0 for the data and text of the three showcases, MIT for code and for onchain-postmortems.

<br clear="left"/>

![Status](https://img.shields.io/badge/status-active%20research-brightgreen)
[![Follow](https://img.shields.io/badge/follow-%40RealSpap-000000?logo=x)](https://x.com/RealSpap)

### Core research

- **[multisig-overlap](https://github.com/RealSpap/multisig-overlap-showcase)**: who holds multisig signer keys across several independent DeFi protocols at once. Checked at three scales: <!--chiffre:multisig.entrees_total-->411<!--/chiffre--> protocol entries and <!--chiffre:multisig.contrats_total-->749<!--/chiffre--> confirmed multisig contracts across 25 chains (<!--chiffre:multisig.mainnet-->214<!--/chiffre--> on Ethereum mainnet, 99 on Optimism's Superchain, 98 on Arbitrum and 10 more L2s and sidechains). The widest single signer key sits on 5 independent protocols. Free tool: [check your own Safe](https://realspap.github.io/tools/check-your-safe.html).
- **[defi-admin-key-risk](https://github.com/RealSpap/defi-admin-key-risk-showcase)**: where a single key (a bare EOA or a 1-of-N Safe) still holds admin power able to mint, pause, or redirect funds. <!--chiffre:defi.verifies-->108<!--/chiffre--> DeFi protocols and lending-vault owners checked by hand, <!--chiffre:defi.cas-->30<!--/chiffre--> single-key admin cases, each with its timelock or guardian noted where one exists. Free tool: [check a contract](https://realspap.github.io/tools/admin-key-checker.html).
- **[onchain-postmortems](https://github.com/RealSpap/onchain-postmortems)**: forensic reconstructions of DeFi and on-chain exploits from raw chain data (all but one, whose chain was rolled back past the attack), with sourced corrections to press and aggregator figures. 64 incidents, $926.0M in losses, $589.1M of it independently recomputed. Free tool: [browse incidents and check an address](https://realspap.github.io/tools/onchain-postmortems-checker.html).
- **[authority-risk-oracle](https://github.com/RealSpap/authority-risk-oracle-showcase)** (testnet): for each contract it watches, who can change it, how fast, and what stands in the way (a key, a multisig, a timelock), published as a score any contract can read. Testnet: the oracle contracts sit on testnets, the contracts they score are real deployments. Replay commands, no key needed: [three commands](https://github.com/RealSpap/authority-risk-oracle-showcase#three-commands). Live readings: [the oracle page](https://realspap.github.io/oracle/).

Live site: [realspap.github.io](https://realspap.github.io) · [X](https://x.com/RealSpap) · [Methodology and disclaimer](https://realspap.github.io/methodology.html)

Every claim rests on an on-chain read or a cited public source. No wallets connected, no tokens, no paid promotion, no affiliation with any protocol covered.

**Custom research:** want the same checks run on your own protocol or chain, or an authority sheet like [these two samples](https://github.com/RealSpap/defi-admin-key-risk-showcase#sample-authority-sheets)? Write to [contact@realspap.com](mailto:contact@realspap.com) or [reach out on X](https://x.com/RealSpap).
