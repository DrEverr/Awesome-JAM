# Awesome JAM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome JAM (Join-Accumulate Machine) resources, tools, examples, tutorials, and more

JAM is a blockchain technology created by Polkadot that provides a flexible framework for building decentralized services. This is your one-stop resource for everything related to JAM development.

## Contents

- [About JAM](#about-jam)
- [SDKs](#sdks)
- [Tools](#tools)
- [Examples & Demos](#examples--demos)
- [Documentation](#documentation)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Articles](#articles)
- [Community & Resources](#community--resources)
- [Contributing](#contributing)
- [License](#license)

## About JAM

The **Join-Accumulate Machine (JAM)** is a novel blockchain architecture developed by Polkadot that enables developers to create custom services with their own state transitions and execution logic. JAM provides a more flexible and efficient approach to building decentralized applications compared to traditional smart contract platforms.

**Key features:**
- **Flexible Service Model** - Define custom services with their own logic and state
- **High Performance** - Optimized for throughput and scalability
- **Interoperability** - Built-in support for cross-service communication

## SDKs

Software development kits for building JAM services in various languages.

- [Ajanta](https://github.com/Chainscore/ajanta) by [@Chainscore](https://github.com/Chainscore) - Python & C SDK for building and running services on JAM
- [Jade](https://github.com/spacejamapp/jade) by [@spacejamapp](https://github.com/spacejamapp) - Community SDK for Rust Services
- [jam-sdk](https://hackmd.io/@polkadot/jamsdk) by [@paritytech](https://github.com/paritytech) - Official SDK for creating JAM Services in Rust
- [jamc3](https://github.com/DrEverr/jamc3.c3l) by [@DrEverr](https://github.com/DrEverr) - SDK for creating JAM Services in C3
- [JamBrains service-sdk](https://github.com/JamBrains/service-sdk) by [@JamBrains](https://github.com/JamBrains) - SDK for creating JAM Services in C
- [as-lan](https://github.com/tomusdrw/as-lan) by [@tomusdrw](https://github.com/tomusdrw) - AssemblyScript SDK for JAM Services

## Tools

Development tools, debuggers, playgrounds, and utilities for JAM development.

- [JAM Codec](https://codec.fluffylabs.dev/) by [@fluffylabs](https://github.com/FluffyLabs) - Online encoder/decoder for JAM objects
- [JAM Search](https://search.fluffylabs.dev/) by [@fluffylabs](https://github.com/FluffyLabs) - Search tool for JAM-related resources and documentation
- [JAM Service Playground](https://playground.jamcha.in/) by [@JamBrains](https://github.com/JamBrains) - Browser-based playground for coding JAM services in C using JamBrains SDK
- [JAM State Viewer](https://state.fluffylabs.dev/) by [@fluffylabs](https://github.com/FluffyLabs) - Tool for visualizing and exploring JAM state
- [JamCode.Fun](https://jamcode.fun/) by [@Chainscore](https://github.com/Chainscore) - Browser-based IDE for building JAM services in Python, C, and C++
- [JAMC3](https://github.com/DrEverr/JAMC3) by [@DrEverr](https://github.com/DrEverr) - Docker-based build tool that compiles C3 source code into `.jam` blobs for PolkaVM
- [jammin](https://github.com/FluffyLabs/jammin) by [@fluffylabs](https://github.com/FluffyLabs) - CLI toolbox for JAM service development, building, deployment, and testing ([docs](https://fluffylabs.dev/jammin/))
- [PVM Debugger](https://github.com/FluffyLabs/pvm-debugger) by [@fluffylabs](https://github.com/FluffyLabs) - JAM PVM code debugger for debugging PolkaVM bytecode

## Examples & Demos

Real-world examples and demonstration projects showcasing JAM services.

- [Jade Examples](https://github.com/spacejamapp/jade) by [@spacejamapp](https://github.com/spacejamapp) - Example services included in the Jade project
- [jam-examples](https://github.com/tomusdrw/jam-examples) by [@tomusdrw](https://github.com/tomusdrw) - Collection of JAM service examples and tutorials in Rust using JamSDK
- [JAMC3 Examples](https://github.com/DrEverr/JAMC3/tree/main/examples) by [@DrEverr](https://github.com/DrEverr) - Example JAM services written in C3
- [jammin-create](https://github.com/jammin-create) - Template repositories for JAM SDKs ([Ajanta](https://github.com/jammin-create/jammin-create-ajanta), [JAM SDK](https://github.com/jammin-create/jammin-create-jam-sdk), [Jade](https://github.com/jammin-create/jammin-create-jade), [JAM-Brains](https://github.com/jammin-create/jammin-create-jambrains), [aslan](https://github.com/jammin-create/jammin-create-aslan), [Undecided](https://github.com/jammin-create/jammin-create-undecided))

## Documentation

Official documentation, specifications, and technical references.

- [Gray Paper Reader](https://graypaper.fluffylabs.dev/) by [@fluffylabs](https://github.com/FluffyLabs) - Interactive reader for the JAM Gray Paper
- [JAM Gray Paper](https://graypaper.com/) - The official JAM specification by Dr. Gavin Wood
- [JAM SDK Documentation](https://hackmd.io/@polkadot/jamsdk) - Documentation for the official Rust SDK

## Tutorials

Step-by-step guides and learning resources.

- [JAM Services Tutorial](https://github.com/paritytech/jam_public/tree/main/services_tutorial) - A tutorial introducing JAM Service development, with the gradual construction of an example service and instructions to interact with it
- [jam-examples](https://github.com/tomusdrw/jam-examples) - Includes tutorial-style examples for learning JAM service development
- [Pala Labs JAM Content Map](https://palalabs.notion.site/) by [@pala_labs](https://x.com/pala_labs) - Comprehensive educational resources including JAM Tour lecture archives, thematic shorts, interviews, and documentary

## Videos

Conference talks, tutorials, and educational video content.

- [PBA Bali 2025 Module 6 - How to JAM](https://www.youtube.com/watch?v=x-i30v1N3hY) - Tutorial on building with JAM
- [PBA Bali 2025 Module 6 - JAM Services](https://www.youtube.com/watch?v=2bzVvoywPfs) - Deep dive into JAM Services
- [PBA Bali 2025 Module 6 - JAM - Gavin Wood - The PBA Lecture](https://www.youtube.com/watch?v=XANhw95qOss) - Gavin Wood's JAM lecture at Polkadot Blockchain Academy
- [PBA Bali 2025 Module 6 - JAM Core VM](https://www.youtube.com/watch?v=z2dyFVURlRI) - JAM Core Virtual Machine explained
- [Yes, It Runs DOOM! Running Retro Games on the JAM Blockchain](https://www.youtube.com/watch?v=riyYJo-CKWE) - Demo of running DOOM on JAM

## Articles

Blog posts, technical write-ups, and articles about JAM.

### Technical Deep Dives

- [A Technical Overview of Polkadot's JAM Protocol](https://www.gate.com/learn/articles/a-technical-overview-of-polkadots-jam-protocol/62037) - Detailed technical analysis of the JAM protocol
- [Demystifying JAM, Polkadot's game-changer](https://www.parity.io/blog/JAM-demystified-explainer) by Parity Technologies - Comprehensive technical explainer about JAM
- [Why Polkadot's JAM is a Game-Changer for Blockchain Scalability](https://hackernoon.com/why-polkadots-jam-is-a-game-changer-for-blockchain-scalability) - HackerNoon article on JAM's scalability innovations

### Educational & Explainers

- [Blockchain 101: JAM](https://medium.com/@francomangone18/blockchain-101-jam-2d64de1cab1d) by Frank Mangone - Beginner-friendly introduction to JAM
- [Polkadot JAM Explained. Simply!](https://polkadotters.medium.com/polkadot-jam-explained-simply-825ec8b24607) by Polkadotters - Simple explanation of JAM concepts
- [What is JAM and What Does This Mean for Polkadot?](https://medium.com/dragonstake/what-is-jam-and-what-does-this-mean-for-polkadot-399647c360d6) by DragonStake - Overview of JAM's impact on Polkadot
- [What is JAM?](https://medium.com/@Luuuuu/what-is-jam-d9a3911cc807) by Just_Luuuu - Introduction to JAM technology

### Vision & Analysis

- [From Polkadot to Jam: Gavin Wood's Vision for Infinitely Scalable Blockchain Infrastructure](https://medium.com/@vjgaur/from-polkadot-to-jam-gavin-woods-vision-for-infinitely-scalable-blockchain-infrastructure-e625e29e8b29) by Vijay Gaur - Long-term vision for JAM
- [How Polkadot 2.0 and JAM Transform Web3](https://medium.com/@stakeflow/how-polkadot-2-0-and-jam-transform-web3-56d9ce17804c) by Stakeflow (July 2025) - JAM's role in Polkadot 2.0
- [JAM: Why Join-Accumulate Machine Is a Paradigm Shift for Web3 and AI Governance](https://medium.com/@buildwithbhavya/jam-why-join-accumulate-machine-is-a-paradigm-shift-for-web3-and-ai-governance-d3203769f0bd) by Bhavya Batra (May 2025) - Analysis of JAM's impact on Web3 and AI
- [The Story of A.I. Agents and JAM](https://medium.com/@dwulf69/the-story-of-a-i-agents-and-jam-join-accumulate-machine-66a60a269aa7) by dwulf - Exploring AI agents on JAM

### Use Cases & Applications

- [Acala JAMVerse: The Next Chapter](https://medium.com/acalanetwork/acala-jamverse-the-next-chapter-86f7f50514b1) by Travis Wilkerson (Aug 2025) - Building JAM-native dApps
- [JAM and JAM Grid: A New Era of Web3 Cloud Computing on Polkadot](https://www.panewslab.com/en/articledetails/5t3eun03.html) - JAM Grid cloud computing platform
- [Transforming Blockchain Scalability: Gavin Wood's Journey from Polkadot to JAM!](https://medium.com/@htxofficial/transforming-blockchain-scalability-gavin-woods-journey-from-polkadot-to-jam-406fa7bc194b) by htxofficial - Evolution from Polkadot to JAM

### Events & News

- [Gavin Wood Signals Next Steps For Polkadot's Revolutionary JAM Protocol At Sub0 Reset](https://hackernoon.com/gavin-wood-signals-next-steps-for-polkadots-revolutionary-jam-protocol-at-sub0-reset) - HackerNoon coverage of Sub0 Reset (Nov 2024)
- [JAM Tour Hangzhou Wraps Up: Gavin Wood Delves into Decentralized Supercomputing](https://medium.com/@OneBlockplus/jam-tour-hangzhou-wraps-up-gavin-wood-delves-into-decentralized-supercomputing-025904d55083) by OneBlock+ (March 2025) - JAM Tour Hangzhou coverage
- [JAM Tour Hong Kong: Gavin Wood on Polkadot's Supercomputing Future](https://medium.com/@OneBlockplus/jam-tour-hong-kong-gavin-wood-on-polkadots-supercomputing-future-eca59022a5f7) by OneBlock+ (Feb 2025) - JAM Tour Hong Kong coverage

### Developer Resources

- [ATTENTION: DEVELOPERS! Discover the $50 Million JAM Implementer's Prize](https://www.scytale.digital/blog-posts/attention-developers-discover-the-50-million-jam-implementers-prize-and-access-a-supercomputer-playground) by Scytale Digital - Information about JAM implementation prizes

## Community & Resources

Connect with the JAM community and find additional resources.

- [Decentralized JAM Competition](https://jam.web3.foundation/) - Web3 Foundation's initiative offering 10M DOT and 100K KSM for JAM client implementations
- [JAM Conformance](https://github.com/davxy/jam-conformance/) - JAM Prize M1 conformance tests, traces, and fuzzer reports
- [JAM Discord](https://discord.gg/amVfGfXu) - Join the JAM community Discord server
- [JAM Gray Paper](https://graypaper.com/) - Official JAM specification and white paper
- [JAM Test Vectors](https://github.com/davxy/jam-test-vectors) - Codec and STF test vectors for JAM implementations
- [Polkadot](https://polkadot.network/) - The ecosystem behind JAM

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

In short:

1. Fork the repository and create a branch
2. Add your resource to the appropriate section using the format: `- [Name](url) by [@user](profile) - Description`
3. Ensure alphabetical ordering within the section
4. Submit a pull request with working links and a clear description

## License

This repository is licensed under the [MIT License](LICENSE). Individual resources may have their own licenses - please check each resource for specific licensing information.

---

**Note**: This is a community-maintained list. If you know of awesome JAM resources, please contribute!
