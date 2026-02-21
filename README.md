# Awesome Algorand [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<div align="center">
<a href="https://github.com/awesome-algorand/awesome-algorand"><img src="https://dweb.link/ipfs/QmfTGB4EFu1FypcZEWWgs3jCmFw75MrqezVV7oQbnbQPyQ" /></a>
</div>
<br/>
<div align="center">
⚡ A curated list of awesome resources related to the <a href='https://www.algorand.co/'>Algorand</a> Blockchain.
<br />
<br />
Algorand is an open-source, proof of stake Blockchain and smart contract computing platform.
</div>

<p align="center">
    <img  src="https://api.visitorbadge.io/api/visitors?path=aorumbayev%2Fawesome-algorand&countColor=%23000000&style=flat" />
    <a target="_blank" href="https://awesomealgo.com"><img src="https://img.shields.io/badge/url-website-black.svg" /></a>
    <a target="_blank" href="https://github.com/awesome-algorand/awesome-algorand"><img src="https://img.shields.io/badge/url-repository-black.svg" /></a>
    <br />
    <a target="_blank" href="https://rss.com/podcasts/the-awesomealgo-podcast"><img src="https://img.shields.io/badge/podcast-rss-black.svg?color=gold" /></a>
    <a target="_blank" href="https://coinmarketcap.com/currencies/algorand/"><img src="https://img.shields.io/badge/coinmarketcap-price-black.svg?color=teal" /></a>
    <a target="_blank" href="https://github.com/awesome-algorand/awesome-algorand"><img src="https://img.shields.io/github/stars/awesome-algorand/awesome-algorand?color=teal" /></a>
    <a target="_blank" href="https://github.com/awesome-algorand/awesome-algorand/network/members"><img src="https://img.shields.io/github/forks/awesome-algorand/awesome-algorand?color=gold" /></a>
</p>

## Contents

* [Core Resources](#core-resources)
  * [Official Resources](#official-resources)
  * [AlgoKit](#algokit)
  * [AlgoKit Templates](#algokit-templates)
* [Learning Resources](#learning-resources)
  * [Crash Courses](#crash-courses)
  * [General courses](#general-courses)
  * [Tutorials](#tutorials)
  * [Community Resources](#community-resources)
  * [Projects](#projects)
  * [AlgoKit Community Templates](#algokit-community-templates)
* [Development & Tools](#development--tools)
  * [Language SDKs & Tools](#language-sdks--tools)
  * [Smart Contract Development](#smart-contract-development)
  * [CLI](#cli)
  * [IDEs](#ides)
  * [Testing & Debugging](#testing--debugging)
  * [Deployment & Environment](#deployment--environment)
* [Wallets & Asset Interaction](#wallets--asset-interaction)
  * [Wallet Providers](#wallet-providers)
  * [Wallet Development](#wallet-development)
  * [Blockchain Explorers](#blockchain-explorers)
  * [Portfolio Trackers](#portfolio-trackers)
  * [Name Services](#name-services)
* [Infrastructure & Ecosystem Services](#infrastructure--ecosystem-services)
  * [Nodes & Consensus Participation](#nodes--consensus-participation)
  * [Blockchain Bridges](#blockchain-bridges)
  * [Oracles](#oracles)
  * [Security Auditing Services](#security-auditing-services)
  * [Metrics and Analytics Services](#metrics-and-analytics-services)
* [SSI, DID and Verifiable Credentials](#ssi-did-and-verifiable-credentials)
* [AI and Machine Learning](#ai-and-machine-learning)
* [Application Platforms & Examples](#application-platforms--examples)
  * [DeFi Platforms](#defi-platforms)
  * [NFT Marketplaces](#nft-marketplaces)
  * [Prediction Markets](#prediction-markets)
  * [Subscription Management](#subscription-management)
  * [Decentralized voting](#decentralized-voting)
* [Standards](#standards)
  * [Algorand Request for Comments](#algorand-request-for-comments)

## Core Resources

### Official Resources

> Official resources for Algorand.

* [Algorand](https://algorandtechnologies.com/) - Official website.
* [Algorand Foundation](https://algorand.foundation/) - Official website of the Foundation.
* [Algorand FAQ](https://algorand.foundation/faq) - FAQ maintained by the Algorand Foundation.
* [Algorand Governance](https://governance.algorand.foundation/) - Official website of Algorand Governance program.
* [Algorand Developer Portal](https://dev.algorand.co/) - Official Algorand developer portal.
* [Algorand Protocol Specs](https://github.com/algorandfoundation/specs) ⭐ 73 | 🐛 22 | 🌐 TeX | 📅 2026-02-05 - Protocol-level specification documents for the Algorand platform.
* [Algorand Discord](https://discord.com/invite/YgPTCVk) - Official Algorand Discord server.

### AlgoKit

> AlgoKit is the official one-stop shop tool for developers building on the Algorand network. Maintained by the Algorand Foundation.

* [algokit-cli](https://github.com/algorandfoundation/algokit-cli) ⭐ 191 | 🐛 28 | 🌐 Python | 📅 2026-02-05 - The Algorand AlgoKit CLI is the one-stop shop tool for developers building on the Algorand network.
* [puya](https://github.com/algorandfoundation/puya) ⭐ 96 | 🐛 23 | 🌐 Python | 📅 2026-02-21 - An official Python to TEAL compiler that allows you to write code to execute on the Algorand Virtual Machine (AVM) with Python syntax.
* [algokit-utils-ts](https://github.com/algorandfoundation/algokit-utils-ts) ⭐ 25 | 🐛 26 | 🌐 TypeScript | 📅 2026-02-20 - Algorand AlgoKit Utils for TypeScript.
* [algokit-utils-py](https://github.com/algorandfoundation/algokit-utils-py) ⭐ 19 | 🐛 15 | 🌐 Python | 📅 2026-02-20 - Algorand AlgoKit Utils for Python.
* [puya-ts](https://github.com/algorandfoundation/puya-ts) ⭐ 16 | 🐛 16 | 🌐 TypeScript | 📅 2026-02-20 - An official TypeScript to TEAL compiler frontend, leveraging the core puya compiler, allows you to write code to execute on the Algorand Virtual Machine (AVM) with TypeScript syntax.
* [algokit-core](https://github.com/algorandfoundation/algokit-core) ⭐ 15 | 🐛 38 | 🌐 Rust | 📅 2026-02-21 - Multi-language core primitives (Rust + FFI bindings) powering higher-level AlgoKit tooling (crypto, encoding, protocol logic).
* [algokit-avm-vscode-debugger](https://github.com/algorandfoundation/algokit-avm-vscode-debugger) ⭐ 13 | 🐛 11 | 🌐 TypeScript | 📅 2026-01-26 - VSCode extension for line‑by‑line debugging of Algorand Python, TypeScript, TealScript and raw TEAL smart contracts via AVM traces.
* [algorand-python-testing](https://github.com/algorandfoundation/algorand-python-testing) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2026-01-23 - A Python library for unit testing Algorand Python smart contracts without the need to interact with the Algorand Blockchain.
* [algokit-client-generator-ts](https://github.com/algorandfoundation/algokit-client-generator-ts) ⭐ 5 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-09 - Algorand AlgoKit Typed Client Generator for TypeScript.
* [algorand-TypeScript-testing](https://github.com/algorandfoundation/algorand-TypeScript-testing) ⭐ 4 | 🐛 5 | 🌐 TypeScript | 📅 2026-02-17 - A TypeScript library for unit testing Algorand smart contracts without the need to interact with the Algorand Blockchain.
* [algokit-client-generator-py](https://github.com/algorandfoundation/algokit-client-generator-py) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2026-01-26 - Algorand AlgoKit Typed Client Generator for Python.
* [algokit-lora](https://lora.algokit.io/mainnet) - Visual local network explorer & app builder for testing Algorand applications (deploy contracts, inspect state, craft transactions).
* [AlgoKit Docs](https://dev.algorand.co/algokit/algokit-intro/) - Official Algorand AlgoKit documentation.

### AlgoKit Templates

> AlgoKit templates are a set of starter and production-ready baseline templates for developing and deploying Algorand applications. They are designed to be used as a starting point for developers to quickly bootstrap their projects and focus on the business logic of their applications. Refer to [Creating AlgoKit Templates](https://github.com/algorandfoundation/algokit-cli/blob/main/docs/tutorials/algokit-template.md) ⭐ 191 | 🐛 28 | 🌐 Python | 📅 2026-02-05 for a general guide on how to create your own AlgoKit templates.

* [algokit-python-template](https://github.com/algorandfoundation/algokit-python-template) ⭐ 10 | 🐛 11 | 🌐 Jinja | 📅 2025-12-30 - Official AlgoKit's Algorand Python template provides a production-ready baseline for developing and deploying smart contracts in Python.
* [algokit-fullstack-template](https://github.com/algorandfoundation/algokit-fullstack-template) ⭐ 10 | 🐛 2 | 🌐 Jinja | 📅 2025-12-23 - Official AlgoKit fullstack template provides a production-ready baseline for developing and deploying fullstack applications with Algorand dependencies integrated. Also serves as a reference for template builders on how to combine standalone algokit templates under one full stack template project.
* [algokit-TypeScript-template](https://github.com/algorandfoundation/algokit-TypeScript-template) ⭐ 4 | 🐛 5 | 🌐 Jinja | 📅 2026-02-10 - Official AlgoKit's Algorand TypeScript template provides a production-ready baseline for developing and deploying smart contracts in TypeScript.
* [algokit-react-frontend-template](https://github.com/algorandfoundation/algokit-react-frontend-template) ⭐ 4 | 🐛 1 | 🌐 Jinja | 📅 2026-02-03 - Official AlgoKit React frontend template provides a production-ready baseline for developing and deploying React frontend applications with Algorand dependencies integrated. Also serves as a reference for template builders on implementing standalone algokit frontend templates.

## Learning Resources

> List of learning resources for Algorand. Includes courses, tutorials, and other resources.

### Crash Courses

* [Algorand School](https://github.com/cusma/algorand-school) ⭐ 81 | 🐛 1 | 📅 2023-10-25 - Crash course slide deck.
* [Zero to Hero Blockchain Algorand](https://github.com/VKappaKV/Zero-To-Hero-blockchain-Algorand) ⭐ 14 | 🐛 0 | 📅 2025-08-18 - Curated learning path for Algorand developers.
* [Zero to Hero PyTeal](https://www.youtube.com/playlist?list=PLwRyHoehE435ttTjvFZA-DyqHYIYc26K_) - PyTeal crash course video lectures.
* [Algorand, efficient self-sustaining Blockchain](https://prismic-io.s3.amazonaws.com/algorandfoundationv2/d5407f96-8e7d-4465-9656-2abb558850a9_Proof+of+Stake+Blockchain+Efficiency+Framework.pdf) - Proof of Stake Blockchain Efficiency Framework.
* [Algorand Efficiency](https://www.youtube.com/watch?v=e8s8Ui8vDaY) - Understanding Algorand's working principles and its efficiency.
* [Introduction to AVM and Applications](https://www.youtube.com/watch?v=fTAPLiPcj28) - Introduction to the Algorand Virtual Machine architecture and Algorand Smart Contracts (aka Applications).
* [Introduction to PyTeal](https://www.youtube.com/watch?v=zXDqJHK_Bqs) - Walkthrough of PyTeal, the Python framework for developing Algorand smart contracts (with [@matteojug](https://twitter.com/matteojug)).
* [PyTeal ABI Smart Contracts](https://www.youtube.com/watch?v=USLcyfVD_ws) - Using PyTeal to develop *ABI-compliant* Smart Contracts on Algorand. Final live coding section (with [@deanste](https://twitter.com/_deanste)).
* [Beaker](https://www.youtube.com/watch?v=031VvOxvuxY) - Framework for Algorand Smart Contract development, client and testing based on PyTeal. Live coding session (with [@HGKimChris](https://twitter.com/HGKimChris)).
* [Dissecting Algorand](https://medium.com/coinmonks/dissecting-algorand-e962f48f8c72) - Introduction Algorand and an analysis on Algorand's inner workings.

### General courses

> Please note these are intended for absolute beginners interested in foundational knowledge relatable to all Blockchain systems. Building a theoretical understanding of the domain of Blockchain protocols is an important prerequisite that can significantly amplify your learning about Algorand technology.

* [Foundations of Blockchains](https://www.youtube.com/watch?v=KNJGPI0fuFA\&list=PLEGCF-WLh2RLOHv_xUGLqRts_9JxrckiA) - A video course by Tim Roughgarden a Professor of Computer Science at Columbia University highlighting the fundamental principles, concepts and properties of Blockchain protocols.

### Tutorials

* [Lending pool using Reach](https://developer.algorand.org/tutorials/building-a-lending-pool-using-reach/) - Tutorial on how to build a lending pool using the Reach language.
* [Creating a License Manager Contract](https://developer.algorand.org/tutorials/creating-a-license-manager-contract-utilizing-pyteal-and-inner-transactions/) - Tutorial on utilizing PyTEAL and Inner Transactions.
* [Stateless session management with the Pera wallet](https://developer.algorand.org/tutorials/stateless-session-management-with-the-pera-wallet/) - Pera Wallet connection example with Next.js and Redux.
* [AlgoMinter](https://developer.algorand.org/tutorials/algominter-a-web-app-for-minting-assets-using-python-algosigner-and-anvil-platform/) - Build your web app for minting assets using Python, AlgoSigner, and Anvil Platform.
* [Getting Started with Django, Python, and Algorand](https://developer.algorand.org/solutions/getting-started-with-python-algorand-sdk-and-django/) - Tutorial from algorand developer portal.
* [MultiSig with Algorand for Co-operative Groups](https://developer.algorand.org/tutorials/decentralised-co-operative-unions-algorand-multisignature-account/) - Decentralised co-operative unions with Algorand Multisignature Account.
* [Adding Notes to Transactions](https://developer.algorand.org/tutorials/v2-read-and-write-transaction-note-field-python/) - Read and Write to the Transaction Note Field with Python.
* [Create Assets with a Stateful Smart Contract](https://developer.algorand.org/solutions/using-stateful-smart-contract-to-create-algorand-standard-asset/) - Using Stateful Smart Contract To Create Algorand Standard Asset.
* [Artificial Intelligence on Algorand](https://developer.algorand.org/solutions/artificial-intelligence-on-algorand/) - Tutorial on using machine learning to predict the transaction volume of the USDC stablecoin on the Algorand Blockchain.

### Community Resources

> The following contains sections related to open source projects, utilities, and news resources.

### Projects

> A list of open source projects, blogs, websites that are built on top of Algorand.

* [staketaxcsv](https://github.com/hodgerpodger/staketaxcsv) ⭐ 269 | 🐛 11 | 🌐 Python | 📅 2026-02-13 - Python backend for [stake.tax](https://stake.tax) that generates taxable transactions CSVs for Algorand and other Blockchains.
* [Auction Demo](https://github.com/algorand/auction-demo) ⚠️ Archived - On-chain NFT auction using smart contracts.
* [Pipeline-UI](https://github.com/headline-design/pipeline-ui) ⭐ 30 | 🐛 3 | 🌐 HTML | 📅 2022-06-22 - A React.js based component library for rapid deployment of Algorand Dapps.
* [AlgoWorld-Contracts](https://github.com/algoworldNFT/algoworld-contracts) ⭐ 28 | 🐛 10 | 🌐 Python | 📅 2026-02-04 - Collection of all smart contracts used by AlgoWorld, written in PyTeal.
* [algonim](https://github.com/cusma/algonim) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2021-08-04 - First Algorand mini-puzzle-game. Written in Python+PyTEAL by [@cusma](https://twitter.com/cusma_b).
* [AlgoWorld-Swapper](https://github.com/algoworldNFT/algoworld-swapper) ⚠️ Archived - Free and trustless ASA swapper, powered by Algorand Smart Signatures.
* [WalletConnect Example DApp](https://github.com/algorand/walletconnect-example-dapp) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-29 - Algorand WalletConnect demo.
* [arc3.xyz](https://github.com/barnjamin/arc3.xyz) ⭐ 22 | 🐛 3 | 🌐 TypeScript | 📅 2022-10-12 - Dapp that can be used to mint ARC3 compliant NFTs.
* [QRCode Generator](https://github.com/emg110/algorand-qrcode) ⭐ 21 | 🐛 2 | 🌐 JavaScript | 📅 2024-09-09 - Uinversal QRCode generator module for Algorand ARC-26 URIs.
* [wen-tools](https://github.com/LoafPickleWW/wen-tools) ⭐ 21 | 🐛 1 | 🌐 TypeScript | 📅 2025-11-17 - Bulk operations tool for Algorand.
* [txnDuck](https://github.com/No-Cash-7970/txnDuck) ⭐ 19 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-30 - Transaction building tool for Algorand blockchain.
* [algorealm](https://github.com/algorealm/algorealm) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2023-01-05 - Claim the Crown and the Sceptre of Algorand Realm! Written in Python+PyTEAL by [@cusma](https://github.com/cusma).
* [algonoderewards](https://github.com/cryptomalgo/algonoderewards) ⭐ 18 | 🐛 10 | 🌐 TypeScript | 📅 2025-12-31 - Track and visualize Algorand node rewards using Nodely API.
* [Algorand Session Wallet](https://github.com/barnjamin/algorand-session-wallet) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2022-07-21 - Session wallet to allow persisted wallet connections across multiple wallets.
* [algovanity](https://algovanity.com/) - Algorand Vanity Address Generator from [Ripe](https://github.com/Ripe/algovanity) ⭐ 17 | 🐛 0 | 🌐 Svelte | 📅 2025-01-25.
* [Automated Prediction Market Maker on Algorand](https://github.com/dspytdao/Algo_AMM) ⭐ 17 | 🐛 5 | 🌐 Python | 📅 2024-07-22 - backend repository with project hosted at [algoAMM.com](https://algoamm.com).
* [lazylora](https://github.com/aorumbayev/lazylora) ⭐ 13 | 🐛 2 | 🌐 Rust | 📅 2026-02-09 - Terminal UI for exploring Algorand blockchain.
* [TinyBar App](https://github.com/aorumbayev/tinybar) ⭐ 12 | 🐛 8 | 🌐 Python | 📅 2026-02-04 - A tiny macOS menu bar app for tracking ASA prices from TinyMan.
* [minter](https://github.com/algofishexe/minter) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2022-03-24 - Bulk mint Algorand NFTs following the ARC-69 community standard. Written in Node.js by [@fish.exe](https://twitter.com/AlgofishExe).
* [galvanity](https://github.com/shmutalov/galvanity) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2021-09-23 - Go-based Algorand vanity address generator.
* [genpyteal](https://github.com/runvnc/genpyteal) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2022-09-27 - Generate PyTeal from (mostly) normal Python.
* [AlgoPing](https://github.com/aorumbayev/algoping) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-12-15 - A tiny cron job that issues a [tweet](https://twitter.com/algoping) if public Algorand Nodes (AlgoExplorer, AlgoNode and etc) are not healthy.
* [AlgoDepo](https://github.com/dspytdao/AlgoDepo) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2023-01-30 - Single Deposit App Algorand.
* [AlgoDeposit](https://github.com/dspytdao/AlgoDeposit) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-04-22 - AMM Pool App Algorand.
* [xGov-Guru](https://github.com/SilentRhetoric/xGov-Guru) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-10 - Tool to browse xGov voting data and proposals.
* [algorealm-ui](https://github.com/algorealm/algorealm-ui) ⭐ 3 | 🐛 13 | 🌐 TypeScript | 📅 2026-02-20 - A web CLI Emulator version of algorealm cli game by @aorumbayev.
* [AgorHash](https://github.com/bafio89/agorhash) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-19 - Public, permissionless, decentralized and uncensorable free speech protocol.
* [algofractals](https://github.com/aorumbayev/algofractals) ⚠️ Archived - Mint randomly generated mandelbrot fractals with embedded ARC69 tags. (Archived on Dec 31, 2023)
* [algorewards](https://algorewards.github.io/) - Free and unofficial Algorand governance reward calculator. Hosted on GitHub Pages.
* [STOI](https://stoi.org/) - Song ownership gone decentralized via microDAOs.
* [AlgoTables](https://algotables.github.io/) - A suite of tools designed to aid everyday hodlers of ALGO who participate in the Algorand ecosystem.

### AlgoKit Community Templates

> AlgoKit community templates are a set of starter and production-ready baseline templates for developing and deploying Algorand applications created by the projects and individuals in the Algorand community.

* [algokit-goracle-template](https://github.com/GoracleNetwork/algokit_default_template) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2023-06-09 - Algokit community template for quick starting a smart contract project interacting with goracle.
* [algokit-subtopia-template](https://github.com/subtopia-algo/algokit-subtopia-template) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2023-12-05 - Algokit community template for quick starting a dapp frontend project interacting with Subtopia platform.
* [algokit-tealish-template](https://github.com/aorumbayev/algokit-tealish-template) ⭐ 0 | 🐛 0 | 🌐 Jinja | 📅 2023-05-17 - AlgoKit community template for quick starting a smart contract project with tealish and algojig.

## Development & Tools

> Awesome client libraries, tools, and community utilities for development.

### Language SDKs & Tools

> Awesome client libraries, tools, and community utilities sorted by the language of implementation.

#### C/C++

* [vertices-algorand-sdk](https://github.com/vertices-network/c-vertices-sdk) ⭐ 11 | 🐛 1 | 🌐 C | 📅 2021-11-18 - The Vertices SDK provides developers with easy device access to interact with Blockchains.
* [unreal-algorand-sdk](https://github.com/Wisdom-Labs/Algorand-Unreal-Engine-SDK) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2023-09-08 - Official Unreal Engine plugin for Algorand Blockchain Platform.
* [cplusplus-algorand-sdk](https://github.com/Wisdom-Labs/Algorand-CPlusPlus-SDK) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2022-12-14 - Algorand C++ SDK: This repo is providing C++ sdk on algorand chain.

#### Dart

* [dart-algorand-sdk](https://pub.dev/packages/algorand_dart) - Dart Algorand SDK.

#### Go

* [go-algorand](https://github.com/algorand/go-algorand) ⭐ 1,426 | 🐛 273 | 🌐 Go | 📅 2026-02-21 - Algorand's official implementation in Go.
* [go-algorand-sdk](https://github.com/algorand/go-algorand-sdk) ⭐ 189 | 🐛 13 | 🌐 Go | 📅 2026-02-20 - The Algorand Golang SDK.
* [conduit](https://github.com/algorand/conduit) ⭐ 43 | 🐛 17 | 🌐 Go | 📅 2026-02-18 - Algorand's data pipeline framework.

#### PHP

* [algorand-php](https://github.com/RootSoft/algorand-php) ⭐ 43 | 🐛 5 | 🌐 PHP | 📅 2022-10-07 - Algorand PHP SDK created by [@RootSoft](https://github.com/RootSoft).
* [php-algorand-sdk](https://github.com/ffsolutions/php-algorand-sdk) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2023-08-23 - Algorand PHP SDK created by [@ffsolutions](https://github.com/ffsolutions).

#### Python

* [py-algorand-sdk](https://github.com/algorand/py-algorand-sdk) ⭐ 277 | 🐛 11 | 🌐 Python | 📅 2026-02-20 - The Algorand Python SDK.
* [tinyman-py-sdk](https://github.com/tinymanorg/tinyman-py-sdk) ⭐ 117 | 🐛 8 | 🌐 Python | 📅 2026-02-09 - Tinyman Python SDK.
* [smart-asa](https://github.com/algorandlabs/smart-asa) ⭐ 31 | 🐛 8 | 🌐 Python | 📅 2024-03-20 - Smart ASA PyTeal reference implementation based on ARC-20.

#### JavaScript & TypeScript

* [js-algorand-sdk](https://github.com/algorand/js-algorand-sdk) ⭐ 297 | 🐛 66 | 🌐 TypeScript | 📅 2026-02-20 - The Algorand JavaScript SDK & Examples.
* [algo-builder](https://github.com/scale-it/algo-builder) ⭐ 128 | 🐛 15 | 🌐 TypeScript | 📅 2023-07-18 - Framework to automate development of Algorand Assets and Smart Contracts.
* [perawallet-connect](https://github.com/perawallet/connect) ⭐ 71 | 🐛 14 | 🌐 TypeScript | 📅 2026-02-20 - JavaScript SDK for integrating Pera Wallet to web applications.
* [algo-builder-templates](https://github.com/scale-it/algo-builder-templates) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2022-10-06 - Dapps templates for Algo Builder.
* [algonaut.js](https://github.com/thencc/algonautjs) ⭐ 10 | 🐛 28 | 🌐 TypeScript | 📅 2024-07-02 - An easier Algo sdk for front-end dapps (TypeScript).
* [defly-connect](https://github.com/blockshake-io/defly-connect) ⭐ 10 | 🐛 3 | 🌐 TypeScript | 📅 2025-01-09 - JavaScript SDK for integrating Defly Wallet to web applications.
* [subtopia-js](https://github.com/subtopia-algo/subtopia-js) ⭐ 10 | 🐛 6 | 🌐 TypeScript | 📅 2026-02-19 - Subtopia JavaScript SDK providing convenient interfaces to interact with Subtopia platform.
* [solid-algo-wallets](https://github.com/SilentRhetoric/solid-algo-wallets) ⚠️ Archived - SolidJS wallet integration library for Algorand.

#### Java

* [java-algorand-sdk](https://github.com/algorand/java-algorand-sdk) ⭐ 72 | 🐛 22 | 🌐 Java | 📅 2026-02-20 - The Algorand Java SDK.

#### .NET

* [dotnet-algorand-sdk](https://github.com/RileyGe/dotnet-algorand-sdk) ⭐ 41 | 🐛 5 | 🌐 C# | 📅 2023-05-24 - Algorand .NET SDK created by [@RileyGe](https://github.com/RileyGe).
* [unity-algorand-sdk](https://github.com/CareBoo/unity-algorand-sdk) ⭐ 31 | 🐛 0 | 🌐 C# | 📅 2025-06-28 - An Algorand SDK for Unity. Use the Algorand Blockchain in your video game.
* [dotnet-alogrand-sdk (2)](https://github.com/FrankSzendzielarz/dotnet-algorand-sdk) ⭐ 29 | 🐛 5 | 🌐 C# | 📅 2024-05-19 - Algorand .NET SDK maintained by [@FrankSzendzielarz](https://github.com/FrankSzendzielarz).
* [dotnet-yieldly-sdk](https://github.com/geoffodonnell/dotnet-yieldly-sdk) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2023-01-08 - Yieldly .NET SDK.
* [dotnet-tinyman-sdk](https://github.com/geoffodonnell/dotnet-tinyman-sdk) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2023-05-13 - Tinyman .NET SDK.
* [powershell-algorand-module](https://github.com/geoffodonnell/powershell-algorand-module) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-03-30 - Algorand PowerShell Module.
* [unity-algorand-sdk-based-on-net-sdk](https://github.com/Vytek/AlgorandUnitySDK) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2021-11-10 - Quick and dirty Unity SDK based on .NET Algorand SDK by RileyGe.

#### Rust

* [rust-algorand-sdk](https://github.com/manuelmauro/algonaut) ⭐ 69 | 🐛 28 | 🌐 Rust | 📅 2024-07-29 - Rust Algorand SDK.

#### Swift

* [algorand-wallet](https://github.com/algorand/algorand-wallet) ⚠️ Archived - Algorand wallet official implementation in Swift.
* [swift-algorand-sdk](https://github.com/Jesulonimi21/Swift-Algorand-Sdk) ⭐ 24 | 🐛 10 | 🌐 Swift | 📅 2024-09-29 - A Swift SDK for interacting with the Algorand Blockchain.

#### Ruby

* [TEALrb](https://github.com/joe-p/TEALrb) ⚠️ Archived - A Ruby DSL for writing Algorand smart contracts. (Archived on Jan 22, 2023)

### Smart Contract Development

#### Languages & Compilers

* [pyteal](https://github.com/algorand/pyteal) ⭐ 294 | 🐛 60 | 🌐 Python | 📅 2025-10-14 - Algorand Smart Contracts in Python.
* [TEALScript](https://github.com/algorand-devrel/TEALScript) ⭐ 53 | 🐛 35 | 🌐 TypeScript | 📅 2025-12-17 - Enables Algorand smart contract development with native TypeScript syntax, tooling, and IDE support.
* [tealang](https://github.com/pzbitskiy/tealang) ⭐ 37 | 🐛 2 | 🌐 Go | 📅 2022-04-16 - A high level language for Algorand ASC1 and TEAL.
* [algoml](https://github.com/petitnau/algoml) ⭐ 24 | 🐛 0 | 🌐 OCaml | 📅 2022-06-14 - A domain-specific language for specifying Algorand smart contracts, which compiles into TEAL scripts.
* [aqua-compiler](https://github.com/optio-labs/aqua-compiler) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2022-07-27 - An expressive high level language for the Algorand block chain that compiles to TEAL code.
* [reach](https://docs.reach.sh) - A domain-specific language for building cross chain decentralized applications (DApps).
* [tealish](https://tealish.tinyman.org) - Readable Algorand VM language enabling procedural-style TEAL focused on clarity.

#### Frameworks & Utilities

* [beaker](https://github.com/algorandfoundation/beaker) ⭐ 96 | 🐛 20 | 🌐 Python | 📅 2024-10-22 - Pythonic smart contract framework (PyTEAL DSL wrappers, client + testing utilities). (Canonical repo)
* [pyteal-utils](https://github.com/algorand/pyteal-utils) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2023-04-07 - PyTEAL utilities library.
* [avm-semantics](https://github.com/runtimeverification/avm-semantics) ⭐ 15 | 🐛 11 | 🌐 Python | 📅 2025-10-01 - Algorand Virtual Machine and TEAL Semantics in K framework. Aids with testing and formal verification of smart contracts.
* [d-asa](https://github.com/cusma/d-asa) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-02-20 - Debt Algorand Standard Application providing reference implementations and interfaces for tokenizing debt instruments (bonds, loans, commercial papers) that conform to ACTUS standards.

### CLI

* [AlgoRun](https://github.com/algorandfoundation/algorun) ⭐ 30 | 🐛 5 | 🌐 Python | 📅 2023-06-30 - Simple CLI utility for setting up and starting an Algorand MainNet participation node.

### IDEs

> Awesome client libraries, tools, community plugins and integrations for IDEs.

#### vim

* [vim-algorand-teal](https://github.com/aldur/vim-algorand-teal) ⭐ 6 | 🐛 0 | 🌐 Vim Script | 📅 2023-05-31 - Minimalistic syntax highlight for Algorand's TEAL Smart Contract language to vim.

#### IntelliJ

* [algoDEA](https://algodea-docs.bloxbean.com/) - Algorand IntelliJ Plugin.

#### VSCode

* [optio-labs/teal-debugger-extension](https://github.com/optio-labs/teal-debugger-extension) ⭐ 14 | 🐛 2 | 🌐 TypeScript | 📅 2022-07-05 - Debug teal with minimal AVM configuration inside VSCode.
* [Obsidian Labs/vscode-algorand](https://github.com/ObsidianLabs/vscode-algorand) ⭐ 13 | 🐛 12 | 🌐 TypeScript | 📅 2023-01-16 - Algorand VS Code Extension.

#### Visual Studio

* [Algorand Visual Studio Extension](https://github.com/FrankSzendzielarz/AlgorandVisualStudio) ⭐ 19 | 🐛 24 | 🌐 C# | 📅 2024-08-09 - Visual Studio extensions for C# TEAL compilation and Algorand Smart Contract development.

### Testing & Debugging

* [tealer](https://github.com/crytic/tealer) ⭐ 63 | 🐛 42 | 🌐 Python | 📅 2024-02-08 - Static TEAL analyser with a set of vulnerability detectors for quick contracts reviews.
* [graviton](https://github.com/algorand/graviton) ⭐ 18 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-02-20 - Algorand's TEAL blackbox testing toolkit.
* [algojig](https://github.com/Hipo/algojig) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2025-05-15 - A tool for testing Algorand smart contracts.
* [tealinspector](https://github.com/Hipo/tealinspector) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2022-11-17 - Quick and easy TEAL code debugging by Hipo labs.
* [irulan](https://irulan.dev/) - Web app for deploying + testing smart contracts ([open source! + PRs welcome](https://github.com/thencc/irulan) ⭐ 4 | 🐛 21 | 🌐 Vue | 📅 2023-06-22).
* [algokit-avm-debugger](https://github.com/algorandfoundation/algokit-avm-debugger) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-26 - Standalone AVM Debug Adapter Protocol implementation powering advanced contract debugging tooling.

### Deployment & Environment

* [Algorand Sandbox](https://github.com/algorand/sandbox) ⭐ 242 | 🐛 11 | 🌐 Shell | 📅 2025-10-24 - Fast way to create and configure an Algorand development environment.
* [Algorand Sandbox Dev](https://github.com/MakerXStudio/algorand-sandbox-dev) ⚠️ Archived - Docker Hub image for faster local development and CI/CD usage. (Archived on Jan 2, 2024)
* [Official Algod Container](https://hub.docker.com/r/algorand/algod) - Algod Docker Hub image from Algorand Inc.
* [Official Conduit Container](https://hub.docker.com/r/algorand/conduit) - Conduit Docker Hub image from Algorand Inc.

## Wallets & Asset Interaction

### Wallet Providers

> List of wallet providers for Algorand. Please note that this list is not exhaustive and is not an endorsement of any wallet provider.
> ⚠️ Given the [attacks](https://twitter.com/myalgo_/status/1632862464244162560) on MyAlgo wallet users, related sdk has been excluded from the list.

* [Liquid Auth](https://github.com/algorandfoundation/liquid-auth) ⭐ 32 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-26 - Self-hosted service to bind passkeys to crypto keypairs plus P2P signaling for secure peer connections.
* [Kibisis](https://github.com/kibis-is/web-extension) ⭐ 18 | 🐛 13 | 🌐 TypeScript | 📅 2025-08-10 - Open source Algorand wallet web extension built in React and TypeScript.
* [Pera Wallet](https://github.com/perawallet) - Secure, open source and community driven wallet for both mobile and desktop devices. Maintained by the team behind official Algorand Wallet.
* [Method Wallet](https://methodwallet.app/) - Algorand Wallet you'll love.
* [Defly Wallet](https://defly.app/) - Defly is an Algorand wallet with great suit of integrated DeFi features.
* [Exodus](https://www.exodus.com/) - Multi-cryptocurrency wallet with Algorand support.
* [A-Wallet](https://a-wallet.net/) - AWallet is an open source, HTML only, corporate friendly, and secure Algorand wallet.

### Wallet Development

* [use-wallet](https://github.com/txnlab/use-wallet) ⭐ 101 | 🐛 11 | 🌐 TypeScript | 📅 2026-02-20 - React hooks for using Algorand compatible wallets with web applications. Developed by [txnlab](https://www.txnlab.dev/).
* [use-wallet-js](https://github.com/TxnLab/use-wallet-js) ⚠️ Archived - TypeScript library for integrating Algorand wallets into decentralized applications.
* [rsagg](https://github.com/dragmz/rsagg) ⭐ 8 | 🐛 3 | 🌐 C | 📅 2025-08-27 - A Rust library for GPU accelerated Algorand 'vanity' address generation.

### Blockchain Explorers

> List of Blockchain explorers for Algorand. Used to view transactions, accounts, assets, etc.

* [Allo](https://allo.info) - Unified Algorand explorer covering all networks by Nodely.
* [Pera Explorer](https://explorer.perawallet.app/) - Algorand Accounts, Standard Asset (ASA) explorer built by [Pera Wallet](https://perawallet.app/)
* [Algorand Ballet](https://akaalias.github.io/algorand-ballet/) - Algorand accounts' 2D graphs.
* [Algorand Multiverse](https://algo3d.live/) - Algorand accounts' 3D graphs.
* [AlgoSurf](https://algo.surf/) - Algorand Network Explorer (supports LocalNet in `localhost`).

### Portfolio Trackers

> List of portfolio trackers for Algorand. Aids in tracking the value of your assets.

* [CompX](https://app.compx.io/dashboard) - Track or search assets, rewards, yield farming, transactions, and NFTs on the Algorand Blockchain anywhere and anytime. Formerly Algogator.Finance.
* [ASA Stats](https://www.asastats.com/) - One-stop portfolio tracker used to summarize Algorand asset valuations from up to five wallet addresses.

### Name Services

> A list of name services that allow for human-readable addresses.

* [NFDomains](https://nf.domains/) - Algorand name service and marketplace for Non-Fungible Domains (NFDs) — unique, readable aliases for wallet addresses.

## Infrastructure & Ecosystem Services

### Nodes & Consensus Participation

* [nodekit](https://github.com/algorandfoundation/nodekit) ⭐ 57 | 🐛 11 | 🌐 Go | 📅 2025-12-09 - Terminal user interface for running and managing Algorand nodes locally.
* [reti](https://github.com/algorandfoundation/reti) ⭐ 40 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-03 - Contracts, Node Daemon, and UI for Algorand 'The Reti' consensus incentives, enabling decentralized staking pools to broaden participation and enhance network security.
* [Algorand Node UI](https://github.com/algorand/node-ui) ⭐ 27 | 🐛 6 | 🌐 Go | 📅 2023-07-07 - Terminal UI for remote Algorand node management.
* [AlloCTRL](https://github.com/AlgoNode/alloctrl) ⭐ 15 | 🐛 3 | 🌐 Svelte | 📅 2023-07-28 - A simple, open source, dashboard to help managing your node and participation keys safely, from your local machine.
* [Algorand - The Undocumented Docs](https://github.com/AlgoChads/algorand-undoc-docs) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-05 - Dev Notes for Archival Node, Indexer Setup (and more).
* [Nodely](https://nodely.io) - Free Node/Indexer APIs, Node running FAQ, Node/Indexer daily snapshots.
* [SubQuery](https://subquery.network) - Open, fast, flexible, and decentralised cross-chain data indexer for Algorand ([getting started guide](https://academy.subquery.network/quickstart/quickstart_chains/algorand.html)).

### Blockchain Bridges

> This provides a list of bridges that allow for cross-chain transfers of assets between Algorand and other Blockchains.

* [Algomint](https://algomint.io/) - Centralized BTC and ETH bridge to Algorand.
* [Messina](https://messina.one/) - The ALGO — ETH two-way Messina.one's Bridge will open the doors for interoperability between Ethereum and ERC-20 tokens with Algorand.

### Oracles

> A list of oracle solutions that allow for smart contracts to interact with the real world.

* [Gora](https://www.gora.io/) - Decentralized oracle networks that connect the Algorand Blockchain with the real world.

### Security Auditing Services

> This section is not aimed to promote any of the companies below, please do your due diligence when researching on options available for audits. Instead, the following is simply aimed to highlight an expanding variety of companies offering smart contract audits for Algorand ecosystem.

* [algorand-ecosystem-audits](https://github.com/blockshake-io/algorand-ecosystem-audits) ⭐ 5 | 🐛 0 | 📅 2022-12-31 - A growing collection of audit reports in the Algorand ecosystem maintained by [blockshake-io](https://blockshake.io).
* [Vantage Point Blockchain](https://www.vantagepoint.sg/contact-us) - Smart contract audits, crypto wallet audit and other penetration testing services in Algorand ecosystem with clients such as Folks.Finance, Pera, Algorand Foundation, Deflex (Defly/Alammex), GARD, Venue.One and others. Reports are signed by velocity.vantagepoint.algo and published at <https://github.com/vantagepointreports/releases> ⭐ 3 | 🐛 0 | 📅 2023-06-19.
* [Tenset Security](https://github.com/tenset-security/audits) ⭐ 3 | 🐛 0 | 📅 2024-06-14 - Comprising a team of Web3 Security Researchers, Tenset Security is dedicated to leaving no stone unturned in their pursuit of security excellence. They have a [proven track record of success](https://twitter.com/algoworld_nft/status/1691891473166279042) in discovering high-severity vulnerabilities specifically within Algorand projects, emphasizing their expertise and commitment to the Algorand ecosystem.
* [Certik](https://www.certik.com/ecosystems/algorand) - Web3 security suite: smart contract audits plus analytics (Skynet, SkyTrace) for Algorand projects.
* [UlamLabs](https://www.ulam.io/software-services/smart-contract-audits) - A Blockchain lab based in Poland, offering auditing services for Algorand smart contracts.
* [Runtime Verification](https://runtimeverification.com/smartcontract) - Smart contract analysis and verification by the team who audited platforms like Algofi, FolksFinance, Yieldly and other prominent DeFi platforms in the ecosystem.
* [Immunebytes](https://www.immunebytes.com) - Secure your Algorand Smart Contract with credible security auditing solutions.
* [KudelskiSecurity](https://kudelskisecurity.com) - Move your Blockchain project securely and successfully into production or onto mainnet. Company can help you assess, design, customize, deploy and manage Blockchain and digital ledger technology systems so you can confidently leverage security as a powerful differentiator in this dynamic market.

### Metrics and Analytics Services

> Metrics and analytics services for Algorand.

* [Algorand MainNet metrics](https://metrics.algorand.org/) - Dashboard that measures the current scale, security, decentralization, and adoption of the open-source Algorand protocol.
* [Metrika](https://app.metrika.co/dashboard/algorand/) - Algorand network performance and account monitor.
* [Allo Metrics](https://metrics.allo.info/) - Algorand MainNet in numbers.

## SSI, DID and Verifiable Credentials

> A list of W3C decentralized identifiers, verifiable credentials and Self sovereign identity service projects.

* [GoPlausible](https://goplausible.com) - Provides [PLAUSIBLE protocol](https://github.com/GoPlausible), A W3C DIDs, Verifiable Credentials and Utility NFTs protocol built on Algorand, as well as [ThisDID](https://thisdid.com) Universal W3C DID/URI resolver.

## AI and Machine Learning

> A list of AI, ML and Data Science projects that leverage Algorand.

* [algorand-mcp](https://github.com/GoPlausible/algorand-mcp) ⭐ 40 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-20 - Algorand Model Context Protocol (Server & Client) by GoPlausible.
* [algorand-agent-skills](https://github.com/algorand-devrel/algorand-agent-skills) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-02-12 - Canonical collection of Agent Skills for AI-assisted development on Algorand by Algorand DevRel.
* [VibeKit](https://github.com/gabrielkuettel/vibekit) ⭐ 17 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-12 - CLI + MCP server that gives AI coding assistants the skills and tools to build on Algorand.
* [algorand-remote-mcp](https://github.com/GoPlausible/algorand-remote-mcp) ⭐ 15 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-10 - Algorand remote SSE MCP Server Cloudflare Worker.
* [arcontextify](https://github.com/aorumbayev/arcontextify) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-06-18 - Algorand ARC-56 to MCP server converter.
* [CorvidAgent](https://github.com/CorvidLabs/corvid-agent) ⭐ 3 | 🐛 19 | 🌐 TypeScript | 📅 2026-02-21 - AI agent orchestration platform with on-chain messaging, persistent memory, and autonomous scheduling via Algorand.
* [AlgoChat](https://github.com/CorvidLabs/ts-algochat) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-07 - Encrypted on-chain messaging protocol for Algorand, enabling AI agent-to-agent communication via transaction notes.
* [Algorand-GPT](https://chatgpt.com/g/g-izA6hnC93-algorand-gpt) - An Algorand Assistant Expert with access to all Algorand documentation and chain data built on OpenAI's ChatGPT platform by GoPlausible.
* [DID-GPT](https://chatgpt.com/g/g-rOCQculZQ-did-gpt) - A W3C DID resolver assistant built on OpenAI's ChatGPT platform by GoPlausible.

## Application Platforms & Examples

### DeFi Platforms

> Awesome DeFi platforms and protocols on Algorand. Please note that this list is not aimed to promote any specific project, but rather to provide a comprehensive overview of the ecosystem. Do your own research before investing or using any of the projects listed here.

* [Folks-Finance/algorand-js-sdk](https://github.com/Folks-Finance/folks-finance-js-sdk) ⭐ 41 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-15 - Official Folks Finance Algorand Protocol SDK.
* [folks-router](https://github.com/Folks-Finance/folks-router) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-09 - Efficient swap routing SDK on Algorand by Folks Finance.
* [Tinyman](https://tinyman.org/) - A decentralized trading protocol, AMM and platform.
* [Pact](https://www.pact.fi/) - Decentralised Automated Market Maker (AMM) built on the Algorand protocol.
* [Lofty.ai](https://www.lofty.ai/) - Tokenized real estate investing platform.
* [Folks.finance](https://folks.finance/) - Decentralized capital markets protocol.
* [Cometa.farm](https://cometa.farm/) - Decentralized liquidity-as-a-service.
* [aramid.finance](https://www.aramid.finance/) - A Decentralized Cross-Chain Protocol supporitng Algorand, Polygon, Ethereum and other EVM chains.
* [stabilitas.finance](https://stabilitas.finance/) - Stable and secure digital assets for various purposes such as purchases, remittances and as a store of value.
* [vestige.fi](https://vestige.fi/) - A decentralized ecosystem of tools primary used as a tool to track and trend Algorand Standard Assets and Liquidity Pools across the ecosystem. The platform also provides a decentralized swap and a launchpad platform.

### NFT Marketplaces

> Awesome NFT marketplaces and galleries on Algorand.

* [Rand Gallery](https://www.randgallery.com/) - Algorand Standard Asset (ASA) explorer and marketplace developed by [Chris Antaki](https://github.com/ChrisAntaki).
* [AlgoGems](https://algogems.io/) - Algorand Standard Asset (ASA) markeplace and trading platform for NFT collectors.
* [AlgoMart](https://github.com/deptagency/algomart) ⚠️ Archived - Opensource NFT marketplace whitelabel solution.
* [Flatter](https://www.flatternft.com/) - NFT art and collectible marketplace.

### Prediction Markets

> Awesome prediction markets and trading platforms on Algorand.

* [Alpha Arcade](https://www.alphaarcade.com/) - Prediction market platform on Algorand.

### Subscription Management

> Awesome subscription management platforms on Algorand. Please note that this list is not aimed to promote any specific project, but rather to provide a comprehensive overview of the ecosystem. Do your own research before investing or using any of the projects listed here.

* [Subtopia](https://subtopia.io/) - Decentralized subscription management platform for dApp creators and platform on Algorand. Manage and own your subscription infrastructure, setup flexible plans, discounts and get paid in Algo or any ASA token. Created by @aorumbayev.

### Decentralized voting

> Tools for on-chain voting powered by Algorand

* [vote-coin-demo](https://github.com/scholtz/vote-coin-demo) ⭐ 601 | 🐛 0 | 🌐 Vue | 📅 2025-09-08 - Decentralized message standard for on-chain voting on Algorand developed by @scholtz.
* [nft\_voting\_tool](https://github.com/algorandfoundation/nft_voting_tool) ⭐ 6 | 🐛 2 | 🌐 TypeScript | 📅 2025-11-19 - Official voting tool by Algorand Foundation. The repository contains a voting tool that allows for creation and facilitation of immutable, tamperproof voting using the Algorand Blockchain.

## Standards

### Algorand Request for Comments

> Standards and specs defined in *finalized* ARCs.
> The list of all the ARCs can be found [here](https://arc.algorand.foundation).

* [ARC3](https://github.com/algorandfoundation/ARCs/blob/main/ARCs/arc-0003.md) ⭐ 139 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - Official Algorand Standard Asset Parameters Conventions for Fungible and Non-Fungible Tokens.
* [ARC4](https://github.com/algorandfoundation/ARCs/blob/main/ARCs/arc-0004.md) ⭐ 139 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - Application Binary Interface.
* [ARC32](https://github.com/algorandfoundation/ARCs/blob/main/ARCs/arc-0032.md) ⭐ 139 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - Application Specification.
* [ARC56](https://github.com/algorandfoundation/ARCs/blob/main/ARCs/arc-0056.md) ⭐ 139 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - Extended and improved Application Specification.
* [ARC69](https://github.com/algorandfoundation/ARCs/blob/main/ARCs/arc-0069.md) ⭐ 139 | 🐛 26 | 🌐 Python | 📅 2026-02-17 - One of several Algorand Standard Asset Parameters Conventions.

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/awesome-algorand/awesome-algorand/blob/main/contributing.md) ⭐ 214 | 🐛 4 | 📅 2026-02-09 first.

Special thanks to everyone who forked or starred the repository ❤️

[![Stargazers repo roster for @awesome-algorand/awesome-algorand](https://reporoster.com/stars/dark/awesome-algorand/awesome-algorand)](https://github.com/awesome-algorand/awesome-algorand/stargazers) ⭐ 214 | 🐛 4 | 📅 2026-02-09

[![Forkers repo roster for @awesome-algorand/awesome-algorand](https://reporoster.com/forks/dark/awesome-algorand/awesome-algorand)](https://github.com/awesome-algorand/awesome-algorand/network/members) ⭐ 214 | 🐛 4 | 📅 2026-02-09
