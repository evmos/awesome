# Awesome Evmos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Evmos is the one of the first [Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/)-based blockchains in the [Cosmos](https://cosmos.network/) ecosystem and enables developers to launch apps that run smart contracts across any number of EVM and Cosmos-based blockchains. It makes that process as simple and seamless as possible by allowing developers to continue creating apps in Solidity and Vyper like they’re accustomed to in the Ethereum ecosystem. Evmos opens a new frontier for blockchain applications, expanding the functionality of the EVM by enabling cross-chain applications that tap the liquidity and user bases of multiple blockchain ecosystems to provide more unified experiences.

> **The below Awesome list is a crowd-sourced list of projects building and supporting the Evmos ecosystem. This list is not an endorsement of any projects and everyone should always do your own research. Only notes in this indented format are official recommendations from the Evmos team.**

## Contributing

Please read the [Contributing guide](./CONTRIBUTING.md) to add your project or any other projects to the list. **Please make sure to add your project in alphabetical order within it's given section!**

## Contents

- [Resources](#resources)
  - [Documentation](#documentation)
  - [Other Ecosystem Maps](#other-ecosystem-maps)
  - [Evmos Community Telegram Groups](#evmos-community-telegram-groups)
- [Wallets](#wallets)
  - [Onramps and Exchanges](#onramps-and-exchanges)
- [Explorers](#explorers)
  - [EVM Explorers](#evm-explorers)
  - [Cosmos Explorers](#cosmos-explorers)
- [Infrastructure](#infrastructure)
  - [Indexers](#indexers)
  - [Oracles](#oracles)
  - [Validator and RPC Services](#Validator-and-RPC-Services)
- [Ecosystem](#ecosystem)
  - [dApps](#dapps)
    - [DeFi](#defi)
    - [NFTs](#nfts)
    - [DAOs](#daos)
  - [Launchpads, Incubators, Accelerators and Ecosystem Supporters](#launchpads,-incubators,-accelerators-and-ecosystem-supporters)
- [Dev Tools](#dev-tools)
- [Interoperability](#interoperability)
  - [IBC](#ibc)
  - [Bridges](#bridges)

## Resources

### [Documentation](https://evmos.dev)

### [Evmos Blog](https://evmos.blog)

### Other Ecosystem Resources

While this Awesome list is one great resource for tracking the growth of the ecosystem, other community members have created additional resources to learn more:

- [CoinGecko](https://www.coingecko.com/en/coins/evmos): World's largest independent cryptocurrency data aggregator.
- [CoinMarketCap](https://coinmarketcap.com/currencies/evmos/)
- [Commonwealth](https://commonwealth.im/evmos): Commonwealth is an all-in-one platform for on-chain communities to discuss, vote, and fund projects together. Never miss an on-chain event, proposal, or important discussion again.
- [Cros-nest Dashboard](https://chain-monitor.cros-nest.com/d/Cros-nest/block-chains?orgId=1&var-chain_id=evmos_9001-1&refresh=1m)
- [Defi Llama](https://defillama.com/chain/Evmos): Open and transparent DeFi TVL and analytics.
  - You can add your Evmos Project to the list by following [these instructions](https://docs.llama.fi/list-your-project/how-to-write-an-sdk-adapter) and replacing `bsc` with `evmos`.
- [Dex Screener](https://dexscreener.com/evmos)
- [Evmos Info](https://evmos.info/): Project discovery portal tracking all the latest projects on Evmos
- [Evmos Space](https://evmos.space/): Project discovery portal tracking all the latest projects on Evmos
- [Map of Zones](https://mapofzones.com/): Cosmos Ecosystem Explorer
- [Messari](https://messari.io/asset/evmos): Providing market intelligence that drives high-conviction participation in crypto.
- [Reddit](https://evmos.reddit.com)

### Evmos Community Telegram Groups

The only official Evmos telegram group is @EvmosOrg but there are many more unofficial group chats maintained by community members for special purposes or specific language groups.

- 🌍Global: [@Evmosorg](https://t.me/EvmosOrg) - Official
- 📣 Announcement: [@EvmosAnnouncements](https://t.me/EvmosAnnouncements)
- 🇷🇺Russian: [@evmos_ru](https://t.me/evmos_ru)
- 🇪🇸Spanish: [@Evmos_ESP](https://t.me/Evmos_ESP)
- 🇹🇷Turkish: [@evmos_tr](https://t.me/evmos_tr)
- 🇨🇳Chinese: [@evmos_zh](https://t.me/evmos_zh)
- 🇰🇷Korean: [@EvmosKorea](https://t.me/EvmosKorea)
- 🇧🇩Bengali: [@evmosBangladesh](https://t.me/EvmosBangladesh)
- 🇩🇪German: [@EvmosDE](https://t.me/EvmosDE)
- 🇮🇹Italia: [@EvmosITA](https://t.me/EvmosITA)
- 🇫🇷France: [@Evmos_Fra](https://t.me/Evmos_Fra)
- 🇻🇳Vietnamese: [@Evmos_VN](https://t.me/Evmos_VN)
- 🇮🇳India: [@EvmosIndia](https://t.me/EvmosIndia)
- 🇮🇩Indonesia: [@Evmos_ID](https://t.me/Evmos_ID)
- 🇮🇷Persian: [@Evmos_PR](https://t.me/Evmos_PR)
- 🇳🇬Nigeria: [@Evmos_NG](https://t.me/Evmos_NG)

## Wallets

- Evmos.me
  - [Website](https://evmos.me)
  - [Announcement](https://evmos.blog/featuring-evmos-me-an-all-in-one-evmos-portal-da0676f32f28)
- FoxWallet
  - [Website](https://foxwallet.com/en)
  - [Setup Guide](https://hc.foxwallet.com/docs/create-wallet)
  - [Audit](https://www.certik.com/projects/fox-wallet)
  - [Twitter](https://twitter.com/FoxWallet)
- Metamask
  - [Website](https://metamask.io/)
  - [Setup Guide](https://evmos.dev/guides/keys-wallets/metamask.html)
- Keplr
  - [Website](https://www.keplr.app/)
  - [Setup Guide](https://evmos.dev/guides/keys-wallets/keplr.html)

### Onramps and Exchanges

- 

## Explorers

Explorers are an important tool for users and developers alike to read and query the Evmos blockchain. Evmos allows for both Cosmos and EVM transactions and as such some explorers below support one or the other, while others support both for a unified experience.

### Mainnet Explorers

- [Official Evmos EVM Explorer](https://evm.evmos.org/)
- [Mintscan](https://mintscan.com/evmos/): Developed by the Cosmostation, the Mintscan explorer supports the most Cosmos chains available including Evmos. It currently only supports Cosmos transactions but EVM transactions are on the roadmap.
- [EvmoStats](https://evmostats.io/): Developed by DragonStake, the Evmostats dashboard offers historical and live data of network infrastructure such as validator bonded status, EVM transactions and governance proposals. 
- [Defier](https://defier.net/evmos/validators): The most detailed dashboard for tracking validators.

### Testnet Explorers

- [Official Evmos EVM Explorer](https://evm.evmos.dev/)
- [Mintscan](https://testnet.mintscan.io/evmos-testnet)
- [Big Dipper](https://testnet.evmos.bigdipper.live/)
- [EvmoStats](https://testnet.evmostats.io/)

## Infrastructure

Infrastructure plays an important role for developers to be able to build applications quickly. The following is a list of some of the infrastructure protocols available on Evmos

### Indexers

- The Graph:
  - [Twitter](https://twitter.com/graphprotocol)
  - Documentation
- Covalent: 
  - [Twitter](https://twitter.com/Covalent_HQ)
  - [Documentation](https://www.covalenthq.com/docs/networks/evmos/)
  - [Announcement](https://evmos.blog/bringing-evmos-developers-unparalleled-access-to-indexed-blockchain-data-with-covalent-94ad2cb8b0b1)
- Kyve
  - [Website](https://kyve.network)
  - [Twitter](https://twitter.com/KYVENetwork)
  - [Announcement](https://evmos.blog/decentralizing-blockchain-data-with-kyve-564acef3c806)

### Oracles

- Band Protocol
  - [Website](https://bandprotocol.com/)
  - [Documentation](https://docs.bandchain.org/band-standard-dataset/supported-blockchains.html)
- DIA
  - Website
  - Twitter
- Flux
  - [Website](https://www.fluxprotocol.org/)
  - [Documentation](https://docs.fluxprotocol.org/docs/getting-started/first-party-oracle/fpo-requesters#get-requesting)
- UMA
  - [Website](https://umaproject.org/)
  - [Twitter](https://twitter.com/umaprotocol)
  - [Announcement](https://evmos.blog/bringing-decentralized-oracles-to-evmos-with-uma-f554f8b0ad50)

### Validator and RPC Services
The following list includes companies that provide services to run Validators and highly available RPC endpoints for individuals in the ecosystem that don't want to or are unable to run these services themselves. Also included in this list are tools and services for infrastructure providers such as snapshot services.

> Official RPC Endpoints provided by the Evmos Foundation and Ecosystem Partners can be found [here](https://evmos.dev/api/connect.html).

- Akash Network
  - Website
  - Documentation
- Ankr
  - [Website](https://www.ankr.com/)
- AM Solutions services
  - [State sync, shrinked Data snap, RPC, API](https://www.theamsolutions.info/evmos-services)
- Blockdaemon
  - [Website](https://blockdaemon.com/)
  - [Ubiquity API Docs](ubiquity.docs.blockdaemon.com)
  - [Announcement](https://evmos.blog/blockdaemon-is-bringing-essential-blockchain-infrastructure-to-evmos-1ff54794c394)
- Chandra Station
  - [Website](https://www.chandrastation.com/)
  - [Twitter](https://twitter.com/chandrastation)
- Coinbase Cloud
  - [Website](https://www.coinbase.com/cloud)
  - [Twitter](https://twitter.com/CoinbaseCloud)
  - [Documentation]()
  - [Evmos Guide](https://www.coinbase.com/cloud/discover/protocol-guides/guide-to-evmos)
  - [Announcement](https://evmos.blog/bootstrapping-evmos-mainnet-launch-with-coinbase-cloud-b66e168f81a7)
- Figment
  - [Website](https://figment.io)
  - [Twitter](https://twitter.com/Figment_io)
  - [Announcement](https://evmos.blog/figment-is-supporting-crucial-blockchain-infrastructure-on-evmos-4df7408fe567)
- [Mercury Snapshots](https://mercury-nodes.net/evmos-snapshot/)
- [Notional Snapshots](https://snapshot.notional.ventures/evmos/)
- POKT
  - [Website](https://pokt.network)
  - [Twitter](https://twitter.com/POKTnetwork)
  - [Announcement](https://evmos.blog/pocket-network-joins-evmos-to-provide-builders-with-crucial-rpc-node-infrastructure-66616ea7c3ea)
- [Polkachu Snapshots](https://polkachu.com/tendermint_snapshots/evmos)
- [Stakingcare Snapshots](https://snapshots.stakingcare.com/evmos/)

### Auditors
Auditors are ciritical to ensuring a safe experience for users. The below Auditors have experience with EVM contracts, Cosmos SDK applications, or both.

- Halborn
  - [Website](https://halborn.com/)
- Verilog
  - [Website](https://www.verilog.solutions/)

## Ecosystem

### Dapps

#### DeFi

- 4T2: First Convex Fork on Evmos
  - App
  - [Twitter](https://twitter.com/4T2Finance)
  - [Medium](https://medium.com/@4T2)
  - [Discord](https://discord.gg/DBSCz4GjVa)
- Astroids Money: Algorithmic stable coin 
  - App
  - [Twitter](https://twitter.com/asteroidsmoney)
  - [Telegram](https://t.me/asteroidsmoney)
- Avelin Protocol: Decentralised OrderBook Exchange and Perps
  - App
  - [Twitter](https://twitter.com/AvelinProtocol)
- Basin Protocol: Liquid Staking for Evmos
  - App
  - [Twitter](https://twitter.com/basinprotocol)
  - [Discord](http://discord.gg/FHnYVWYZtz)
- Beanbag Fi: Stablecoin protocol
  - App
  - [Twitter](https://twitter.com/BeanbagFi)
- ClouDex: Dex on Evmos
  - App
  - [Twitter](https://twitter.com/EvmosCloudEx)
  - [Medium](https://medium.com/@CloudEx)
- Coslend: The Money Market of Cosmos Ecosystem
  - [App](https://coslend.com/)
  - [Twitter](https://twitter.com/coslend)
  - [Telegram](https://t.me/coslend)
- Cronus Finance: AMM Dex
  - [App](https://cronusfinance.xyz/)
  - [Twitter](https://twitter.com/CronusFinance)
  - [Medium](https://medium.com/@cronusfinance)
  - [Discord](http://discord.gg/cronusfinance)
- DForce: decentralized finance protocols covering assets, lending, and trading
  - [Announcement](https://medium.com/dforcenet/dforce-coming-to-evmos-soon-c8226afa80a0)
  - [App](https://dforce.network/)
  - [Twitter](https://twitter.com/dForcenet)
  - [Discord](https://discord.com/invite/c2PC8SM)
- Diffusion Finance: Evmos AMM based on Uniswap
  - [App](https://diffusion.fi/)
  - [Twitter](https://twitter.com/diffusion_fi)
  - [Medium](https://medium.com/@diffusion_fi)
  - [Telegram](https://t.co/zyhlPO5Ucy)
- Earnmos: Yield optimizer for interchain ecosystem
  - [App](earnmos.fi)
  - [Twitter](https://twitter.com/Earnmos1)
  - [Medium](https://medium.com/@market_55417)
- EvDoge: Community token
  - [Website](https://evdoge.space)
  - [Twitter](https://twitter.com/EvDogeCosmos)
  - [Discord](https://discord.gg/6emn3xcNCD)
- Evmos Galaxy: Lending and borrowing protocol
  - App
  - [Twitter](https://twitter.com/evmosgalaxy)
- Evmos Shiba: Community-centered meme token 
  - [Website](https://www.evmosshiba.com/)
  - [Twitter](https://twitter.com/EvmosShiba)
  - [Discord](https://discord.gg/xGwWYk5DGg)
- EvmoSwap: EvmoSwap is a AMM DEX on Evmos
  - [App](https://app.evmoswap.org/swap)
  - [Twitter](https://twitter.com/evmoswap)
  - [Discord](https://discord.gg/cEp53UXPw3)
- Expanding Space: NFT marketplace
  - App
  - [Twitter](https://twitter.com/expanding_space)
  - [Telegram](https://t.me/expandingspace)
  - [Discord](https://t.co/AHNcv2JVbh)
- Exswap: Defi Hub of Evmos
  - App
  - [Twitter](https://twitter.com/Exswapdotxyz)
  - [Telegram](https://t.me/Exswap)
  - [Discord](https://discord.gg/exswap)
  - [Medium](https://medium.com/@exswap.xyz)
- Fantastic Swap
  - App
  - [Twitter](https://twitter.com/Fantastic_Swap)
  - [Discord](http://discord.gg/tNW3fndAST)
- Frax: fractional-algorithmic stablecoin
  - [App](https://frax.finance/)
  - [Twitter](https://twitter.com/fraxfinance)
  - [Telegram](https://t.me/fraxfinance)
  - [Announcement](https://evmos.blog/frax-is-coming-to-evmos-61837abb2fa9)
- Kinesis Labs: Stablecoins on Cosmos
  - [App](https://kinesislabs.co/)
  - [Twitter](https://twitter.com/KinesisLabs)
  - [Telegram](https://t.me/KinesisLabsPublic)
  - [Discord](https://discord.gg/2RQtMZeGEF)
  - [Medium](https://medium.com/@kinesislabs)
- Midas Capital: Cross-chain permissionless lending pools
  - App
  - [Twitter](https://twitter.com/MidasCapitalxyz)
- Orimos Finance: The First Yearn Fork on Evmos
  - App
  - [Twitter](https://twitter.com/OrimosFinance)
- Perci Finance: The first Liquity fork on Evmos
  - App
  - [Twitter](https://twitter.com/PerciFinance)
  - [Discord](https://discord.gg/Fh8EwbUzPx)
- Photon Swap: AMM based on Uniswap
  - [App](https://photonswap.finance/#/swap)
  - [Twitter](https://twitter.com/photonswap_fi)
  - [Discord](https://discord.gg/JVYXYr6t8q)
- Pulsar Finance: Isolated Money Markets
  - [App](https://pulsarfinance.io/)
  - [Twitter](https://twitter.com/pulsarfinance_)
  - [Discord](https://discord.gg/Pw4RAVCR97)
- Quantum Swap:Decentralized exchange
  - [App](https://www.quantumswap.org/)
  - [Twitter](https://twitter.com/quantumswap_)
  - [Discord](http://quantumswap.org/discord)
- Revest: Financial NFTs
  - [App](https://revest.finance/)
  - [Twitter](https://twitter.com/RevestFinance)
  - [Telegram](https://t.me/revestfinance)
- Saddle Finance: AMM for swapping low-slippage pegged assets
  - [App](https://saddle.finance/#/)
  - [Twitter](https://twitter.com/saddlefinance)
  - [Discord](https://discord.gg/saddle)
- SpaceFi: SpaceFi is a cross-chain Web 3.0 platform with DEX, NFT, Starter and DAO on Evmos, Layer2 and Celo.
  - [App](https://t.co/Rqhb4bPnjP)
  - [Twitter](https://twitter.com/spacefi_io)
  - [Discord](https://discord.gg/WDtuwbYRXE)
- Thorus: All in one cross-chain #DeFi platform
  - [App](https://thorus.fi/)
  - [Twitter](https://twitter.com/ThorusFI)
  - [Discord](https://discord.gg/thorusfi)

#### NFTs & Gaming

- Cosmic Horizon: Elite Space Trading game built on Cosmos SDK
  - [Website](https://cosmic-horizon.com/)
  - [Twitter](https://twitter.com/CoHo_Cosmos)
  - [Discord](https://discord.gg/GTWQCMKvud)
- EVMHops: Evmos based P2E game
  - App
  - [Twitter](https://twitter.com/EvmHop)
  - [Medium](https://medium.com/@evmhops/evm-hop-a08ec1523041)
  - [Discord](https://discord.gg/evmhops)
- Evmos Explorers: 10k pfp Evmos explorers project 
  - [Website](https://evmosexplorers.com/)
  - [Twitter](https://twitter.com/evmosexplorers)
  - [Discord](https://discord.gg/wtsutGCguG)
- Evmos Punks:Punks on Evmos
  - [Website](https://ospunks.com/)   
  - [Twitter](https://twitter.com/EvmOSPunks)
  - [Discord](https://discord.com/invite/XjSN8k22ue)
- GamyFi: GamyFi platform is a fantasy sports platform and NFT marketplace
  - [App](https://gamyfi.org/home)
  - [Twitter](https://twitter.com/GamyFi_HQ)
  - [Telegram](https://t.me/GamyFi_ANN)
- Orbit Market: NFT Marketplace on Evmos. Built by OrbitalApes
  - [Website](https://www.orbitmarket.io/)
  - [Twitter](https://twitter.com/OrbitMarketOS)
  - [Discord](http://discord.gg/orbitalapes)
- Orbital Apes: Orbital Apes NFT & P2E game
  - [Website](https://www.orbitalapes.com/)
  - [Twitter](https://twitter.com/OrbitalApes)
  - [Discord](http://discord.gg/orbitalapes)
- Tofu NFT: NFT marketplace focused on GameFi and collectibles
  - [App](https://tofunft.com/evmos)
  - [Twitter](https://twitter.com/tofuNFT)
  - [Discord](https://discord.gg/3wFUTZmTm7)
- Treasureland: Treasureland is a cross-chain NFT platform
  - [App](https://treasureland.market/)
  - [Twitter](https://twitter.com/TreasurelandNFT)
  - [Discord](https://discord.gg/jjf7Uxm4rM)

#### DAOs

- 

### Launchpads, Incubators, Accelerators and Ecosystem Supporters

- DexPad: Multichain LaunchPad
  - [App](https://dexpad.io/)
  - [Twitter](https://twitter.com/dexpad)
  - [Discord](https://t.me/DexPad_IO)
- Layer2 Pad: Quadratic VC DAO and Public Goods Launchpad
  - [Website](https://l2pad.io/)
  - [Twitter](https://twitter.com/l2pad_io)
  - [Telegram](https://t.me/l2pad_comm)
- NovaDAO: Decentralized reserve currency
  - App
  - [Twitter](https://twitter.com/NovaDaoFinance)
  - [Discord](https://discord.gg/zbtRkB2Se9)
  - [Medium](https://medium.com/@Nova_DAO)

## Dev Tools

- Black IDE by Obsidian Labs
  - [App](https://eth.ide.black/local)
  - [Twitter](https://twitter.com/obsidian_labs)
  - [Github](https://github.com/ObsidianLabs/Black-IDE)
- Bulk Sender:  DAPP used to send tokens to many addresses in one transaction
  - [App](https://bulksender.app/)
  - [Telegram](https://t.me/bulksender)
- Gelato: Automate your smart contracts. Outsource your web3 DevOps needs and enjoy the perks of Ethereum's most reliable bot network at your fingertips.
  - [Website](https://www.gelato.network/)
  - [Twitter](https://twitter.com/gelatonetwork)
  - [Discord](https://discord.gg/ApbA39BKyJ)
- Gnosis Safe: A fully customizable trusted multisig.
  - [Testnet App](https://safe.evmos.dev/)
  - [Website](https://gnosis-safe.io/)
  - [Twitter](https://twitter.com/gnosisSafe)
- Multitransfer: Airdrop Tool
  - [App](https://multitransfer.org)
  - [Twitter](https://twitter.com/Multitransfer1)
  - [Telegram](https://t.me/mutitransfer)
- Restake App
  - [App](https://restake.app/evmos)
  - [Twitter](https://twitter.com/eco_stake)
  - [Discord](https://discord.gg/SAn2ZF3GJH)

## MISC

- Evmos Domains: Decentralized name service 
  - [App](https://evmos.domains/)
  - [Twitter](https://twitter.com/EvmosDomains)
  - [Discord](https://chat.evmos.domains/)
- EVMNS: Evmos Naming Service .evm
  - App
  - [Twitter](https://twitter.com/EvmnsOrg)
- Evmos Name Service
  - [App](https://evmosnameservice.com/)
  - [Twitter](https://twitter.com/EvmosNS)
  - [Telegram](https://t.me/evmosns)
- Wrapped Evmos (Official)
  - [Mainnet Verified Contract](https://evm.evmos.org/address/0xD4949664cD82660AaE99bEdc034a0deA8A0bd517/contracts)
  - [Testnet Verified Contract](https://evm.evmos.dev/address/0xcc491f589B45d4a3C679016195B3FB87D7848210)


## Interoperability

### IBC

- 

### Bridges
> The recommended bridge for Evmos users is the Nomad bridge which also leverages Connext for liquidity. While there are other bridges, Nomad and Connext offer an optimal balance between security and UX as well as bring value in other ways to the network. Of course, Evmos is a permissionless network allowing users and devs to choose their bridge provider on Evmos based on their differentiators: security, speed, fragmentation, etc. With that said, the team is focussed on simplifying bridging UX by closely collaborating with Nomad and Connext at launch to reduce fragmentation.

> **Any questions/issues you have about using bridging services please use their respective discord for. The Evmos team is not responsible for or able to help with customer service for bridge operations.**

- Nomad & Connext Bridge:
  - [Bridge Portal](https://app.nomad.xyz/)
  - Nomad Specifics
    - [Nomad Documentation](https://docs.nomad.xyz/)
    - [Official Nomad Representations](https://docs.nomad.xyz/bridge/domains.html)
    - [Nomad Ethereum Statistics](https://dune.com/0xroll/Nomad-Bridge-Ethereum)
    - [Nomad Discord](https://discord.gg/nomadxyz)
  - Connext Specifics
    - [Connext Documentation](https://docs.connext.network/)
    - [Connextscan](https://connextscan.io/evmos): View liquidity of Evmos on Connext.
    - [Connext Discord](https://discord.gg/connext)
