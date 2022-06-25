# awesome-huff
A curated list of resources for Huff language.

```
                              ,....,
                            ,::::::<
                           ,::/^\"``.
                          ,::/, `   e`.
                         ,::; |        '.
                         ,::|  \___,-.  c)
                         ;::|     \   '-'
                         ;::|      \
                         ;::|   _.=`\
                         `;:|.=` _.=`\
                           '|_.=`   __\
                           `\_..==`` /
                            .'.___.-'.
                           /          \
                          ('--......--')
                          /'--......--'\
                          `"--......--"`        _              ___    ___
                                               | |            / __)  / __)
 _____ _ _ _ _____  ___  ___  ____  _____ _____| |__  _   _ _| |__ _| |__
(____ | | | | ___ |/___)/ _ \|    \| ___ (_____)  _ \| | | (_   __|_   __)
/ ___ | | | | ____|___ | |_| | | | | ____|     | | | | |_| | | |    | |
\_____|\___/|_____|___/ \___/|_|_|_|_____)     |_| |_|____/  |_|    |_|

```
*ascii art credit: Joan Stark (jgs)

Huff is a low-level programming language designed for developing highly optimized smart contracts that run on the Ethereum Virtual Machine (EVM). Huff does not hide the inner workings of the EVM. Instead, Huff exposes its programming stack to the developer for manual manipulation.

Initially developed by the [Aztec Protocol](https://github.com/AztecProtocol) team, Huff was created to write [Weierstrudel](https://github.com/AztecProtocol/weierstrudel), an on-chain elliptical curve arithmetic library that requires incredibly optimized code which neither Solidity nor Yul could provide.

[Huff](https://github.com/huff-language/huffc) was later rewritten by [Jet Jadeja](https://twitter.com/JetJadeja) in Typescript, and is [currently being rewritten again in Rust](https://github.com/huff-language/huff-rs).

Huff can be used to write highly-efficient smart contracts for use in production, or it can serve as a way for beginners to learn more about the EVM.


## Say gm in the Discord
 - Huff is still young, but it already has a thriving community. Everyone on the [Huff discord](https://discord.gg/W5Cff3Kh) is super helpful and friendly.

## Join the movement on Twitter
 - Follow [@huff_language](https://twitter.com/huff_language) to keep up with the latest news and announcments -- turn those notifications on, anon!
 - Follow [the Aztec Protocol team](https://twitter.com/aztecnetwork), the original creators of Huff.
 - Follow [Jet Jadeja](https://twitter.com/JetJadeja) The young prince of the Huff empire, aka "Sensei".
 - And a few other Huff chads: [@asnared](https://twitter.com/asnared), [@big_tech_sux](https://twitter.com/big_tech_sux), [@d1ll0nk](https://twitter.com/d1ll0nk), [@exp_table](https://twitter.com/exp_table), [@jtriley](https://twitter.com/jtriley_eth), [@merkleplant_eth](https://twitter.com/merkleplant_eth) [@sw0nt](https://twitter.com/sw0nt)

## Official huff-language Github repo
This is your main GH org for all things Huff: https://github.com/huff-language.

- [huffc](https://github.com/huff-language/huffc) ➸ START HERE ➸  This is the stable version currently in use. It is an npm package that can be installed with:
```bash
yarn global add huffc
```
 - Install `huffc` with the above command and start hacking.  Write your first Huff function, anon. Start with something simple like adding two numbers.
 - [vscode-huff](https://github.com/huff-language/vscode-huff) A VSCode extension for Huff with syntax highlighting.  Also available from within your VSCode in the Extensions Marketplace.
 - [foundry-huff](https://github.com/huff-language/foundry-huff) A Foundry template to compile and test Huff contracts.
 - [huff-examples](https://github.com/huff-language/huff-examples) Currently has wip versions of ERC20 and ERC721.
 - [huff-rs](https://github.com/huff-language/huff-rs) THE FUTURE OF HUFF. There is a grass-roots community effort to rewrite Huff in Rust. Will you help us work out the bugs, anon?
 - [huff-project-template](https://github.com/huff-language/huff-project-template/) A template for bootstrapping new Huff projects.  Includes Foundry `HuffDeployer`.
 - [huff-debug](https://github.com/huff-language/huff-debug) An easy hevm debug integration for hardhat-huff projects.
 - [hardhat-huff](https://github.com/huff-language/hardhat-huff) Huff support for Hardhat.
 - [huff-docs](https://github.com/huff-language/huff-docs) 🚧 Currently under constructions, this is the future home of Huff documentation. Will you write some docs, anon?
 - [huff-web](https://github.com/huff-language/huff-web) 🚧 The future landing page for all things Huff Language. Please consider contributing your VuePress skills anon.

## Huff articles
 - [Huff vs Yul for EVM Smart Contracts](https://medium.com/@jtriley15/huff-vs-yul-for-evm-smart-contracts-620d1d618197) A well written and informative introduction to Huff by [@jtriley](https://twitter.com/jtriley_eth)
 - [From Zero to Nowhere](https://medium.com/aztec-protocol/from-zero-to-nowhere-smart-contract-programming-in-huff-1-2-ba2b6de7fa83) An informative, 4 part series and deep dive into Huff written by the [team that developed Huff](https://github.com/AztecProtocol).

## Huff projects you can learn from and contribute to
 - [TSOwnable-huff](https://github.com/byterocket/TSOwnabe-Huff) An Ownable Implementation using Two-Step Transfer Pattern
 - [huff-learning](https://github.com/manasbir/huff-learning/tree/main/contracts) Some math and other functions implemented in Huff.
 - [huff-tools](https://github.com/kadenzipfel/huff-tools) A WIP set of tools for use with the huff language. Contains useful SafeMath functions.
 - [8-bit-array](https://github.com/h00p30/8bitArray) An implementation of an array in huff. It can store up to 32 8-bit values in a single storage slot.
 - [proxies](https://github.com/wolflo/proxies.huff) A few Ethereum delegate-call proxies written in raw bytecode via Huff.
 - [huff-pg](https://github.com/AdvaithD/huff-pg) An ERC20 implementation with SafeMath.

 ## Know your roots, anon
  - [AztecProtocol/huff](https://github.com/AztecProtocol/huff#why-is-it-called-huff) - This is the original version of Huff, developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.
  - [Weierstrudel](https://github.com/AztecProtocol/weierstrudel) This is the project that Huff was written for.  Good luck with that math, anon.
  - [Oliver](https://github.com/AztecProtocol/Oliver) An elliptic curve point multiplication on the Baby-JubJub curve also developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.

## EVM Opcodes
 - [evm-puzzles](https://github.com/fvictorio/evm-puzzles) 10 puzzles to get you thinking like an evm.
 - [more-evm-puzzles](https://github.com/daltyboy11/more-evm-puzzles) 10 more puzzles!
 - [evm.codes](https://www.evm.codes/) The ultimiate resource for evm opcodes.  The playground will soon have Huff support!
 - [EVM Deep Dives: The Path to Shadowy Super](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy) A great series by [@noxx3xxon](https://twitter.com/noxx3xxon) with a very deep dive into the evm.
