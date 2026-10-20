# Dominique Martel

**AI-native builder: I ship production web3 and security systems with AI agents · Accounting background · Québec, remote**

I don't write code by hand. I design, specify, review, test and operate systems built with AI agents (Claude Code), and I ship them to production. Everything below is live, on mainnet, with real customers or real payments.

I came to this from accounting (over ten years as an accounting technician), which is why my products have working billing, revenue reporting and fee logic from day one, and why I read a protocol's economics as carefully as its code.

I work in French and English, from Québec, fully remote. I'm looking for a small web3 or security team that needs someone who turns a problem into a running system and then keeps it running, not someone to pass a whiteboard coding test.

Full portfolio: **[sentinelleai.app/about](https://sentinelleai.app/about)**

## What I've built and operate

| Project | What it is | Proof |
|---|---|---|
| **Sentinelleai** | Detection and response platform for small businesses and web3 teams: hosts and ransomware, web apps, software supply chain, smart contracts. Contract verification on eight on-chain ecosystems with a multi-model AI panel, findings proved by replaying exploits on a fork. Live Stripe billing, 2FA, tamper-evident evidence ledger, ~280 test scripts in CI. Built and operated solo. | [sentinelleai.app](https://sentinelleai.app) |
| **On-chain circuit breaker / Auto-pause** | Pause-only watchdog over 20 EVM chains: owner, module routes and bytecode read through a quorum of RPC endpoints; `pause()` sent on a confirmed takeover, never unpause. Armed in production since August 2026. | part of Sentinelleai |
| **Magneta Contract Risk** | Paid API that AI agents call without an account: deterministic risk report for any contract on 20 chains, $0.02 per call in USDC over HTTP 402 (x402, Coinbase facilitator) on Base mainnet. Also an MCP server in the official MCP registry. | [x402.magneta.finance](https://x402.magneta.finance) · [source](https://github.com/Bosacks/magneta-risk-x402) |
| **Magneta Finance** | Token launcher, DEX and token explorer, same contract suite on 20 EVM mainnets. Native-currency fee logic, multisig-controlled upgrades, self-hosted subgraph and RPC proxy, three Next.js apps on one dedicated server. | [magneta.finance](https://magneta.finance) · [app](https://app.magneta.finance) · [scope](https://scope.magneta.finance) |
| **Security program** | Twenty-plus internal audit rounds (static analysis, multi-model review, economic analysis, fuzzing, mutation testing); every finding fixed on testnet first and promoted, or documented as accepted. Secret rotation calendar, Dependabot triage on every commit, SBOM and config-drift checks in CI. | across all of the above |

## How I work

- Specify precisely, let agents build, verify everything myself: compile, test, read the diff, check on-chain state before anything reaches production.
- Testnet first, then promotion; one production change at a time, verified (HTTP 200, on-chain read) before the next.
- Every report an agent gives me is checked, not trusted.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/dominique-martel-134a5a16) · [Medium](https://medium.com/@bosacks_25667) · [X @sentinelleai](https://x.com/sentinelleai)
