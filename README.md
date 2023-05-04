<img src="./assets/huff.png">

# awesome-huff

## What the heck is Huff?

Huff is a low-level programming language designed for developing highly optimized smart contracts that run on the Ethereum Virtual Machine (EVM). Huff does not hide the inner workings of the EVM. Instead, Huff exposes its programming stack and provides useful tools like constants and macros.

Initially developed by the [Aztec Protocol](https://github.com/AztecProtocol) team, Huff was created to write [Weierstrudel](https://github.com/AztecProtocol/weierstrudel), an on-chain elliptical curve arithmetic library that requires incredibly optimized code which neither Solidity nor Yul could provide. [Huff](https://github.com/huff-language/huffc) was later rewritten by [Jet Jadeja](https://twitter.com/JetJadeja) in Typescript, and finally [it has been rewritten in Rust](https://github.com/huff-language/huff-rs) as `huff-rs` which is the version we use today.

Huff can be used to write highly-efficient smart contracts for use in production, or it can serve as a way for beginners to learn more about the EVM.

## Join the movement on Twitter
 - Follow [@huff_language](https://twitter.com/huff_language) to keep up with the latest news and announcements - notifications on, anon!
 - Follow [the Aztec Protocol team](https://twitter.com/aztecnetwork), the original creators of Huff.
 - Follow [Jet Jadeja](https://twitter.com/JetJadeja) The young prince of the Huff empire.
 - And a few other Huff chads: [@vex_0x](https://twitter.com/vex_0x), [@refcells](https://twitter.com/refcells), [@Maddiaa0](https://twitter.com/Maddiaa0), [@d1ll0nk](https://twitter.com/d1ll0nk), [@jtriley](https://twitter.com/jtriley_eth), [@0xKaden](https://twitter.com/0xKaden), [@merkleplant_eth](https://twitter.com/merkleplant_eth), [@real_philogy](https://twitter.com/real_philogy), [DeGatchi](https://twitter.com/DeGatchi), [@exp_table](https://twitter.com/exp_table), [@big_tech_sux](https://twitter.com/big_tech_sux)

## Drop a gm in the Discord
 - Huff is still young, but it already has a thriving community. People on the [Huff discord](https://discord.gg/xabvMWDpEf) are helpful, friendly, and chill.

## Start here
- [Huff landing page](https://huff.sh/) The landing page for all things Huff. Here you can
 find links to [Github](https://github.com/huff-language), [Twitter](https://twitter.com/huff_language), and [huff-docs](https://docs.huff.sh/).
- [The Huff Docs](https://docs.huff.sh/) ➸ START HERE ➸ Here you'll find installation guides, reference, tutorials and everything you need to know about Huff. What are you waiting for, anon?
- [Huff GitHub List](https://github.com/stars/pcaversaccio/lists/huff-language) A curated Github list of Huff language resources, libraries, tools, and more by [@pcaversaccio](https://twitter.com/pcaversaccio).

## Official huff-language Github repo
This is your main GH org for all things Huff: https://github.com/huff-language.
 - [huff-rs](https://github.com/huff-language/huff-rs) You'll be installing this, the new compiler built in Rust, developed by the community and recently released to the public.  After installing `huffc` it's time to start hacking! Write your first Huff function, anon. Start with something simple like adding two numbers.  See the tutorials in the docs.
 - [huff-project-template](https://github.com/huff-language/huff-project-template/) A template for bootstrapping new Huff projects. Includes Foundry `HuffDeployer`.
 - [vscode-huff](https://github.com/huff-language/vscode-huff) A VSCode extension for Huff with syntax highlighting.  Also available from within your VSCode in the Extensions Marketplace.
 - [huff-examples](https://github.com/huff-language/huff-examples) Currently has wip versions of ERC20 and ERC721.
 - [huff-breakage](https://github.com/huff-language/huff-breakage) 💎***HIDDEN GEM***💎 A repo containing incorrect, breaking, and footgunned Huff contracts. You'll learn a lot about Huff by reading what not to do in this excellent resource by [@refcells](https://twitter.com/refcells).
 - [huff-debug](https://github.com/huff-language/huff-debug) An easy hevm debug integration for hardhat-huff projects.
 - [foundry-huff](https://github.com/huff-language/foundry-huff) Foundry support for Huff.  Includes HuffDeployer to compile and test Huff contracts.
 - [hardhat-huff](https://github.com/huff-language/hardhat-huff) Huff support for Hardhat.

## Huff tooling
 - [Bytepeep](https://github.com/kadenzipfel/bytepeep) Bytepeep is a minimal bytecode peephole optimizer by [@0xKaden](https://twitter.com/0xKaden).
 - [Murph](https://github.com/iFrostizz/murph) Transpile EVM bytecode into Huff.
 - [vim-huff](https://github.com/marktoda/vim-huff) Huff syntax highlighting for vim
 - [hufflime](https://github.com/nguyenphuminh/hufflime) A Sublime Text package for Huff syntax highlighting.

## Huff articles
 - [Testing and deploying Huff contracts](https://mirror.xyz/0xF314e9Cc3D5F382669eeB01d31f421aF931b9eBB/H9-kta5z47jO-_Fg9Hv93D6xHcPCFgvfxCIQ26zI5hk) How to write tests and deploy your Huff contracts by [0xasp_](https://twitter.com/0xasp_).
 - [Which Smart Contract Language Is Right for Me?](https://blog.chain.link/solidity-vs-vyper/) A comparison of EVM languages benchmarked against Huff.  Written by some gigachads.
 - [Entering the Huff Ecosystem](https://merkleplant.xyz/posts/entering-the-huff-ecosystem) A deep dive into [TSOwnable-huff](https://github.com/byterocket/TSOwnabe-Huff) by the author, [@merkleplant_eth](https://twitter.com/merkleplant_eth).
 - [Huff vs Yul for EVM Smart Contracts](https://medium.com/@jtriley15/huff-vs-yul-for-evm-smart-contracts-620d1d618197) A well written and informative introduction to Huff by [@jtriley](https://twitter.com/jtriley_eth)
 - [Huff Challenge #1](https://mirror.xyz/seshanth.eth/8ZhSSQD3wRizdRXoseRPuk8lIjO0kpcvAym8KWm-WMM) A walkthrough and solution for the [first official Huff challenge](https://twitter.com/huff_language/status/1559658361469095936) by [@seshanth_](https://twitter.com/seshanth_).
 - [Huff Challenge #2](https://seshanth.xyz/huff-challenge-2) A walkthrough and solution for the [second official Huff challenge](https://twitter.com/huff_language/status/1560016429096677377) by [@seshanth_](https://twitter.com/seshanth_).
 - [From Zero to Nowhere](https://medium.com/aztec-protocol/from-zero-to-nowhere-smart-contract-programming-in-huff-1-2-ba2b6de7fa83) An informative, 4 part series and deep dive into Huff written by the [team that developed Huff](https://github.com/AztecProtocol).

## Huff videos
 - [EVM Through HUFF: Devtooligan](https://www.youtube.com/watch?v=Rfaabjj7n9k) Demo of Huff including a walk through of SimpleStore.huff and a bytecode optimization challenge produced by [@SpearbitDAO](https://twitter.com/SpearbitDAO).
 - [Devs Do Something #9 - Vex on Huff](https://www.youtube.com/watch?v=pOxRk6mbbFg) Interview with [@vex_0x](https://twitter.com/vex_0x), one of the core contributors to [huff-rs](https://github.com/huff-language/huff-rs). Lots of great discussion around the history and core concepts of Huff.
 - [Huff Basics - OpenZeppelin](https://forum.openzeppelin.com/t/huff-basics-video-introduction-to-huff-programming-language/2384) A 2020 introduction to Huff by OpenZeppelin.  This discusses the original version of Huff created by [Aztec](https://github.com/AztecProtocol).

 ## Advanced EVM articles
 - [EVM Deep Dives: The Path to Shadowy Super](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy) A great series by [@noxx3xxon](https://twitter.com/noxx3xxon) with a very deep dive into the evm.
 - [DeGatchi articles](https://degatchi.com/articles) Lots of alpha from [DeGatchi](https://twitter.com/DeGatchi), check out [Reversing The EVM: Raw Calldata](https://degatchi.com/articles/reading-raw-evm-calldata) and [A Low-Level Guide To Solidity's Storage Management](https://degatchi.com/articles/low_level_guide_to_soliditys_storage_management).
 - [Jean Cavalerra - All About...](https://jeancvllr.medium.com/) Jean goes super deep on a lot of topics - must read for anyone serious about low-level EVM.

## Projects using Huff in the wild
 - [HyVM](https://github.com/oguimbal/HyVM) Run arbitrary code on the EVM, part of [nested.fi](https://nested.fi/).
 - [Weierstrudel](https://github.com/AztecProtocol/weierstrudel) This is the project that Huff was written for (written for the original version of Huff) and is used by the [Aztec Protocol](https://github.com/AztecProtocol).

## Huff projects you can learn from and contribute to
 - [huffmate](https://github.com/pentagonxyz/huffmate) A library of modern, hyper-optimized, and secure Huff contracts. Currently the gold standard of Huff libraries.
 - [8-bit-array](https://github.com/h00p30/8bitArray) An implementation of an array in huff. It can store up to 32 8-bit values in a single storage slot.
 - [TSOwnable-huff](https://github.com/byterocket/TSOwnabe-Huff) An Ownable Implementation using Two-Step Transfer Pattern written by [@merkleplant_eth](https://twitter.com/merkleplant_eth).
 - [huffbound](https://github.com/PraneshASP/huffbound) A Soulbound token contract implementation using Huff by [0xasp_](https://twitter.com/0xasp_).
 - [huff-clones](https://github.com/clabby/huff-clones) Rewrite of clones-with-immutable-args in Huff.
 - [erc721h](https://github.com/Philogy/erc721h) Gas optimized version of ERC721A in Huff.
 - [huff-ethernaut-magic-number](https://github.com/minaminao/huff-ethernaut-magic-number) Ethernaut MagicNumber Solver.
 - [huff-goo-issuance](https://github.com/PraneshASP/huff-goo-issuance) GOO(Gradual Ownership Optimization) issuance implementation using Huff by [0xasp_](https://twitter.com/0xasp_).
 - [huff-safe](https://github.com/rodrigoherrerai/huff-safe) Safe multi-sig rewritten in huff.
 - [grim-reaper](https://github.com/massun-onibakuchi/grim-reaper) Gas optimized liquidation bot for Aave V3 in Huff.
 - [huff-learning](https://github.com/manasbir/huff-learning/tree/main/contracts) Some math and other functions implemented in Huff.
 - [huff-math](https://github.com/PraneshASP/huff-math) 👷🚧 Implementation of basic math operations using Huff by [0xasp_](https://twitter.com/0xasp_).
 - [huff-merkle](https://github.com/benleim/huff-merkle) Merkle distributor written in Huff.
 - [proxies](https://github.com/wolflo/proxies.huff) A few Ethereum delegate-call proxies written in raw bytecode via Huff.
 - [quicksort-huff](https://github.com/kyledewy/quicksort-huff) DsSort implemented in Huff.
 - [huff-snark-verifier](https://github.com/whitenois3/huff-snark-verifier) Generate an optimized Groth16 SNARK verification smart contract for use on EVM-based blockchains.
 - [huff-tools](https://github.com/kadenzipfel/huff-tools) A WIP set of tools for use with the huff language. Contains useful SafeMath functions by [@0xKaden](https://twitter.com/0xKaden).
 - [huff-vrgda](https://github.com/cheethas/huff-vrgda) Huff Implementation of VRGDAs.
 - [meth-weth](https://github.com/philogy/meth-weth) 👷🚧 WETH implementation in Huff by [philogy](https://twitter.com/real_philogy).
 - [doppelganger](https://github.com/emo-eth/doppelganger) Huff smart contracts for deploying arbitrary bytecode to deterministic CREATE2 addresses.
 - [hufflove](https://github.com/takez0o/hufflove) Rewrite of commonly used contracts by [@takez0_o](https://twitter.com/takez0_o).
 - [huff-binarySearch](https://github.com/0xsYcamore/huff_BinarySearch) Binary Search implemented in Huff.
 - [huff-single-byte-dispatcher](https://github.com/merklefruit/huff-single-byte-dispatcher) A jumptable-based function dispatcher in Huff by [@merklefruit](https://twitter.com/merklefruit).
 - [Damn-Vulnerable-DeFi-V3-CTF](https://github.com/0xJCN/Damn-Vulnerable-DeFi-V3-CTF) Damn Vulnerable DeFi solutions with Huff.
 - [Ethernaut-CTF](https://github.com/0xJCN/Ethernaut-CTF) Ethernaut solutions with Huff.
 - [Yul2Huff](https://yul2huff.vercel.app) Simple tool to convert Yul expressions to Huff.

## We heard you like ERC20 implementations
 - [huffmate ERC20](https://github.com/pentagonxyz/huffmate/blob/ab/erc20/src/tokens/ERC20.huff) This is the current gold standard of Huff ERC20
(includes EIP-2612 Permit) and passing all [Solmate](https://github.com/transmissions11/solmate) tests.
 - [erc20-huff](https://github.com/Dev-Doggo/erc20-huff) An ERC20 with Foundry tests.
 - [huff-pg](https://github.com/AdvaithD/huff-pg) An ERC20 implementation with SafeMath.
 - [huff-examples-ERC20](https://github.com/huff-language/huff-examples/tree/main/erc20) Currently has wip versions of ERC20 and ERC721.
 - [Solmate ERC20](https://github.com/devtooligan/huffhuffpass/blob/main/src/ERC20.huff) ERC20 implemented on Huff fully complete with all functionality

 ## Know your roots, anon
  - [AztecProtocol/huff](https://github.com/AztecProtocol/huff#why-is-it-called-huff) This is the original version of Huff, developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.
  - [Weierstrudel](https://github.com/AztecProtocol/weierstrudel) This is the project that Huff was written for.  Good luck with that math, anon.
  - [Oliver](https://github.com/AztecProtocol/Oliver) An elliptic curve point multiplication on the Baby-JubJub curve also developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.
  - [huffc](https://github.com/huff-language/huffc) The  [Jet Jadeja](https://twitter.com/JetJadeja) rewrite in Typescript that was deprecated on 4-Jul-2022.

## EVM opcodes
 - [evm.codes WITH HUFF PLAYGROUND](https://evm-codes-6zqgbc9nl-smlxl.vercel.app/playground?unit=Wei&codeType=Huff) **check it out!** This is a fork of evm.codes with Huff language support in the playground. Prototype, practice, and learn Huff with real time feedback and interactive debugger.
 - [evm.codes](https://www.evm.codes/) The ultimate resource for evm opcodes.  The playground will soon have Huff support!
 - [evm-puzzles](https://github.com/fvictorio/evm-puzzles) 10 puzzles to get you thinking like an evm.
 - [more-evm-puzzles](https://github.com/daltyboy11/more-evm-puzzles) 10 more puzzles!

 ## Huff honorable mentions
  - [0xleastw00d mentions Huff on Andy Li podcast](https://youtu.be/92ztf8OhZ6I?t=1888)
  - https://www.alchemy.com/dapps/huff-vm
  - https://www.devpill.me/docs/smart-contract-development/specialized-languages/#huff
  - https://golden.com/wiki/Huff-R9YXP8
  - https://tokeninsight.com/en/news/evm-programming-language-huff-officially-released

