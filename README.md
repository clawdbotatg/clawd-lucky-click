# 🎰 Lucky Click

A CLAWD token gambling game on Base. Pay 10,000 CLAWD per click — 1 in 10 chance to win 90,000 CLAWD.

**🔴 This entire project — contract, frontend, deployment — was built by an AI agent (LeftClaw 🦞). It has NOT been audited or reviewed by a human developer. Play at your own risk. There are probably bugs.**

## How It Works

1. **Click** — Pay 10,000 CLAWD. Your secret is committed on-chain.
2. **Check** — After 1 block, your secret is mixed with the blockhash. 1 in 10 chance to win.
3. **Claim** — If you won, reveal on-chain to collect 90,000 CLAWD. If you lost, no action needed.

Uses commit-reveal so neither the player nor the blockchain can predict the outcome at bet time.

- **House edge:** 10%
- **Contract:** [`0xc0520e84C4362bC0075f190e987417742d0D6814`](https://basescan.org/address/0xc0520e84C4362bC0075f190e987417742d0D6814) on Base
- **Token:** [$CLAWD](https://basescan.org/token/0x9f86dB9fc6f7c9408e8Fda3Ff8ce4e78ac7a6b07) on Base
- **Live:** [luckyclick.clawdbotatg.eth.link](https://luckyclick.clawdbotatg.eth.link)

## ⚠️ Disclaimer

This is unaudited, experimental software written by an AI. The smart contract has not been reviewed by any human. Do not bet more than you're willing to lose. The house must be funded with CLAWD to pay winners — if the house runs dry, new bets will revert.

## Built With

- [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2) (Foundry + Next.js)
- Deployed to IPFS via [BuidlGuidl](https://buidlguidl.com/)
- ENS subdomain: `luckyclick.clawdbotatg.eth`

## Development

```bash
git clone https://github.com/clawdbotatg/clawd-lucky-click.git
cd clawd-lucky-click
yarn install
yarn start
```

Built by LeftClaw 🦞 — the builder claw of [clawdbotatg.eth](https://clawdbotatg.eth.link)
