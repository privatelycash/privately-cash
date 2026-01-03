# privately-cash
"PrivatelyCash – Transfer SOL privately. Clean slate, zero trace. Privacy protocol on Solana using zero-knowledge proofs."
# PrivatelyCash

**PrivatelyCash – Transfer SOL Privately. Clean slate, zero trace.**  
NO CA. NO token. Just pure privacy.

Privacy protocol on **Solana** using zk-SNARKs + Merkle trees.  
Deposit SOL into shielded pool → Withdraw to fresh wallet with **zero on-chain link** to your old addresses.

**Status**: Development / Testnet (Mainnet coming soon)  
**Audits**: In progress (planned with top firms)

## Why PrivatelyCash?
- Breaks all traceability  
- Delivers truly clean funds  
- Simple, secure & non-custodial  
- Maximum privacy for your SOL

When you need your SOL to start **fresh & untraceable**.

## Features (Current & Planned)
- Private SOL transfers ✓  
- Private SPL tokens (soon)  
- Relayer support (optional, for IP privacy)  
- Private swaps (roadmap)

## Project Structure

anchor/         → Solana on-chain program (Rust + Anchor)
circuits/       → ZK circuits (Circom)
artifacts/      → Compiled proofs
audits/         → Security audit reports
scripts/        → Utilities & SDK helpers

## Quick Start (Dev)
```bash
# Prerequisites: Rust, Solana CLI ≥2.1, Anchor ≥0.32, Node ≥20, Circom ≥2.1

git clone https://github.com/YOUR_USERNAME/privatelycash.git
cd privatelycash/anchor
anchor build
anchor test

# Deploy to devnet (after config Anchor.toml)
anchor deploy --provider.cluster devnet

Security Note: After mainnet deploy → transfer upgrade authority to multisig immediately!Security & AuditsPrivacy projects are high-risk.
All code will be fully audited before mainnet.
Reports will be published here in /audits/.
Bug bounty planned post-audit.DisclaimerThis is experimental privacy technology.
Use at your own risk.
Not financial advice. Not for illicit activities.
We comply with applicable laws (OFAC-aware design).Contact & CommunityX/Twitter: @PrivatelyCash
  
Website: (coming soon – privately.cash or similar)

Contributions welcome! Open an issue or PR.

