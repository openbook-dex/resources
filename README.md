# resources

Resources for the Openbook, a community driven fork of the old Serum V3 program.

Discord: https://discord.gg/pX3n5Sercb
Twitter: https://twitter.com/openbookdex 

## Project Background (article)

- https://twitter.com/m_schneider/status/1591636082890006529

## Projects supporting

- Jupiter
- Switchboard
- Mango
- Drift
- Raydium
- Prism
- CellFi
- Dual Finance
- Dexlab
- Solend
- Solape
- Step Finance
- Lanatools
- TabTrader

## Program

- [source](https://github.com/blockworks-foundation/serum-dex)
- mainnet `srmqPvymJeFKQ4zGQed1GFppgkRHL9kaELCbyksJtPX`
- devnet `EoTcMgcDRTJVZDMZWBoU6rhYHZfkNTVEAfz3uUJRcYGj`

## Create new market

- [Serum Explorer](https://serumexplorer.xyz)
- [Raydium (Create Market)](https://raydium.io/create-market/)

## Front-ends / GUIs

- [Solape](https://dex.solape.io)
- [Dexlab](https://openbook.dexlab.space)
- [Jupiter](https://jup.ag/)
- [Prism](https://prism.ag/)
- [Forked Serum UI](https://openbook.lionfi.sh/#/market/8BnEgHoWFysVcuFFX7QztDmzuH8r5ZFvyP3sYwn1XTh6)
- [Lanatools](https://lanatools.com/lanadex)
- [WOOF DEX](https://dex.woofsolana.world)
- [TabTrader](https://tabtrader.com)

## Cranks

- [mango](https://github.com/blockworks-foundation/mango-client-v3)

```
$ ENDPOINT_URL="https://api.mainnet-beta.solana.com" KEYPAIR="[0,0,0,…]" ts-node src/scripts/serumCranks.ts
```

## Data

- [openserum.io](https://openserum.io)
- [serum-vial](https://github.com/tardis-dev/serum-vial)
  `wss://vial.mngo.cloud/v1/ws`
- [birdeye.so](https://birdeye.so)
- Dynamic markets.json: https://cache.prism.ag/openbook.json
- Dynamic markets.json (OpenSerum): https://openserum.io/api/serum/markets.json
- Dynamic markets.json (OpenSerum), 24hr minimum volume: (https://openserum.io/api/serum/markets.json?min24hVolume=1000)

## Client Libraries

- Serum-TS (Typescript): [Serum-TS](https://github.com/project-serum/serum-ts)
- PySerum (Python): [PySerum](https://github.com/serum-community/pyserum)
- Solnet.Serum (C#): [Solnet.Serum](https://github.com/bmresearch/Solnet.Serum)
- SolanaJ-Programs (Java):
  [SolanaJ-Programs](https://github.com/skynetcap/solanaj-programs/tree/master/serum)

## FAQ

Same code as Serum v3? 
- Yes, On a newly deployed program ID, deployed by a multi-sig.

Why fork Serum Code?
- FTX had access to it and funds could be stolen by the "hacker", forked program with multisig control on [Realms](https://app.realms.today/dao/OPENBOOK)

Token?
- Still using SRM token for simplicity, more details soon.

Whats the connection with Serum team/protocol?
- Forked off the Serum codebase as FTX controls the authority, transitioned to an ecosystem realms multisig. Currently using SRM token but might transition off it.

Hiring?
- No, its a DAO, join our Discord. 

Raising?
- Doubt so but stay tuned.

Airdrop?
- No
