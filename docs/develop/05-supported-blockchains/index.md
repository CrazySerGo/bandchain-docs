# Supported Blockchains

:::caution

- We recommend experimenting with using our solution on a test network first before proceeding to mainnet.
- Please ONLY use the proxy contract as in the case that the base contract is updated, the proxy contract will always
  point to the correct base contract and show the most updated price feeds.

:::

Currently, our `StdReferenceProxy` smart contracts are available on the following networks:

## Testnets

| Blockchain        |                                                                          `StdReferenceProxy` Contract Address                                                                          |
| ----------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Astar (Shibuya)   |                            [0x2Bf9a731f9A56C59DeB4DF1369286A3E69F5b418](https://blockscout.com/shibuya/address/0x2Bf9a731f9A56C59DeB4DF1369286A3E69F5b418)                             |
| Avalanche (Fuji)  |                             [0xD0b2234eB9431e850a814bCdcBCB18C1093F986B](https://testnet.snowtrace.io/address/0xD0b2234eB9431e850a814bCdcBCB18C1093F986B)                              |
| Bitgert           |                        [0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68](https://testnet-explorer.brisescan.com/address/0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68)                         |
| BitTorrent Chain  |                             [0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68](https://testnet.bttcscan.com/address/0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68)                              |
| Boba              |                      [0xe8e974b6b294AC1f5031AC54B968E8afFb7306Cb](https://blockexplorer.rinkeby.boba.network/address/0xe8e974b6b294AC1f5031AC54B968E8afFb7306Cb)                       |
| Celo (Alfajores)  |                     [0x660cBc25F0cFD31F0Bdcaa43525f0bACC6DB2ABc](https://alfajores-blockscout.celo-testnet.org/address/0x660cBc25F0cFD31F0Bdcaa43525f0bACC6DB2ABc)                     |
| CLV               |                           [0xD0b2234eB9431e850a814bCdcBCB18C1093F986B](https://clover-testnet.subscan.io/account/0xD0b2234eB9431e850a814bCdcBCB18C1093F986B)                           |
| Cronos            |                             [0xD0b2234eB9431e850a814bCdcBCB18C1093F986B](https://testnet.cronoscan.com/address/0xD0b2234eB9431e850a814bCdcBCB18C1093F986B)                             |
| Findora           |                       [0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68](https://testnet-anvil.evm.findorascan.io/address/0x8c064bCf7C0DA3B3b090BAbFE8f3323534D84d68)                        |
| Godwoken          |                             [0x0c2362c9a0586dd7295549c65a4a5e3afe10a88a](https://v1.betanet.gwscan.com/address/0x0c2362c9a0586dd7295549c65a4a5e3afe10a88a)                             |
| Harmony           |                               [0xD0b2234eB9431e850a814bCdcBCB18C1093F986B](https://explorer.pops.one/address/0xd0b2234eb9431e850a814bcdcbcb18c1093f986b)                               |
| Icon (Berlin)     |                        [cxd2bac764a0277efb9a6861fa991be4e5a46f16a2](https://berlin.tracker.solidwallet.io/contract/cxd2bac764a0277efb9a6861fa991be4e5a46f16a2)                         |
| Icon (Lisbon)     |                        [cx734512ad03efdcedb69e0526415a7ce21340e0db](https://lisbon.tracker.solidwallet.io/contract/cx734512ad03efdcedb69e0526415a7ce21340e0db)                         |
| Meter             |                          [0xe1bCC505f2Bdd02C9480C924856f5080834A3897](https://scan-warringstakes.meter.io/address/0xe1bCC505f2Bdd02C9480C924856f5080834A3897)                          |
| Oasis (Emerald)   |                      [0x61704EFB8b8120c03C210cAC5f5193BF8c80852a](https://testnet.explorer.emerald.oasis.dev/address/0x61704EFB8b8120c03C210cAC5f5193BF8c80852a)                       |
| Oasis (Sapphire)  |                      [0x0c2362c9A0586Dd7295549C65a4A5e3aFE10a88A](https://testnet.explorer.sapphire.oasis.dev/address/0x0c2362c9A0586Dd7295549C65a4A5e3aFE10a88A)                      |
| OKC               |                          [0xb6256DCb23CEE06eDa2408E73945963606fdddd7](https://www.oklink.com/en/okc-test/address/0xb6256DCb23CEE06eDa2408E73945963606fdddd7)                           |
| Osmosis           | [osmo1j8jnej8k5he7h27qzr4v999xgsd0q43n9ny8phtx9aj6w82ruwgslcp77p](https://testnet.mintscan.io/osmosis-testnet/account/osmo1j8jnej8k5he7h27qzr4v999xgsd0q43n9ny8phtx9aj6w82ruwgslcp77p) |
| PlatON            |                          [0xb6256DCb23CEE06eDa2408E73945963606fdddd7](https://devnet2scan.platon.network/address/0xb6256DCb23CEE06eDa2408E73945963606fdddd7)                           |
| Secret (Pulsar-2) |                 [secret14swdnnllsfvtnvwmtvnvcj2zu0njsl9cdkk5xp](https://secretnodes.com/secret/chains/pulsar-2/accounts/secret14swdnnllsfvtnvwmtvnvcj2zu0njsl9cdkk5xp)                 |

## Mainnets

| Blockchain       |                                                          `StdReferenceProxy` Contract Address                                                          |
| ---------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------: |
| Astar (Astar)    |             [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://blockscout.com/astar/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)              |
| Astar (Shiden)   |               [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://shiden.subscan.io/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)               |
| Avalanche        |                 [0x75B01902D9297fD381bcF3B155a8cEAC78F5A35E](https://snowtrace.io/address/0x75B01902D9297fD381bcF3B155a8cEAC78F5A35E)                  |
| BitTorrent Chain |                 [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://bttcscan.com/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                  |
| BNB              |                  [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://bscscan.com/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                  |
| Celo             |               [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://explorer.celo.org/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)               |
| CLV              |                  [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://clvscan.com/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                  |
| Cronos           |                 [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://cronoscan.com/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                 |
| Ethereum         |                 [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://etherscan.io/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                  |
| Fantom           |                  [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://ftmscan.com/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)                  |
| Godwoken         |                 [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://v1.gwscan.com/account/0xda7a001b254cd22e46d3eab04d937489c93174c3)                 |
| Icon (Java)      |            [cxe647e0af68a4661566f5e9861ad4ac854de808a2](https://tracker.icon.community/contract/cxe647e0af68a4661566f5e9861ad4ac854de808a2)            |
| Meter            |                 [0x861C20f77f194EEa4f86e0d39069D789265A3A82](https://scan.meter.io/address/0x861C20f77f194EEa4f86e0d39069D789265A3A82)                 |
| Moonriver        |             [0x75B01902D9297fD381bcF3B155a8cEAC78F5A35E](https://moonriver.moonscan.io/address/0x75B01902D9297fD381bcF3B155a8cEAC78F5A35E)             |
| Oasis (Emerald)  |          [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://explorer.emerald.oasis.dev/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)           |
| OKC              |              [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://www.oklink.com/oec/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)               |
| Optimism         |            [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://optimistic.etherscan.io/address/0xDA7a001b254CD22e46d3eAB04d937489c93174C3)            |
| PlatON           |              [0xDA7a001b254CD22e46d3eAB04d937489c93174C3](https://scan.platon.network/address/0xda7a001b254cd22e46d3eab04d937489c93174c3)              |
| Secret 4         | [secret1ezamax2vrhjpy92fnujlpwfj2dpredaafss47k](https://secretnodes.com/secret/chains/secret-4/accounts/secret1ezamax2vrhjpy92fnujlpwfj2dpredaafss47k) |
