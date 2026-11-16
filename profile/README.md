# Prismaport

Non-custodial stablecoin payments. A merchant gets a payment link or an API call; the payer sends
USDC or another accepted stablecoin to a deposit address made for that one payment; the funds go
on-chain, in the same transaction that settles them, to the merchant's own wallets, minus a fee
that the contracts cap. Prismaport never holds the money and cannot redirect it.

[prismaport.com](https://prismaport.com)

## Repositories

| Repository | What | Status |
|---|---|---|
| [prismaport-contracts-evm-v1](https://github.com/prismaport/prismaport-contracts-evm-v1) | The EVM contracts: deposit addresses, the fee and split rules, the signed-authorization gateway | Live on Base, source verified |
| [prismaport-contracts-solana-v1](https://github.com/prismaport/prismaport-contracts-solana-v1) | The Solana program: PDA deposit addresses with the same fee and split rules | Release candidate, on devnet; not yet on mainnet |

The application code (checkout, dashboard, API) is coming to this organization later.

## Security

Report a vulnerability privately through the affected repository's **Security** tab ("Report a
vulnerability"). See [SECURITY.md](https://github.com/prismaport/.github/blob/main/SECURITY.md).
