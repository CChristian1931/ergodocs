# Developers

This page should provides an entry-point to Ergo development. For a high-level introduction to Ergo please see the [protocol page](/dev/protocol). For a list of tools and services see [resources](dev/start/resources/) page.

## Getting Started

Apps in the Ergo ecosystem looks a bit like this. 

```mermaid
graph LR;
    A[Your APP & SDK] -->|HTTPS| B(Ergo Node)
    B -->|:9053| C[Ergo MainNet]
    B -->|:9052| D[Ergo TestNET]
    style C fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    style D fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
    linkStyle 0 stroke-width:2px,fill:none,stroke:grey;
    linkStyle 1 stroke-width:2px,fill:none,stroke:grey;
    linkStyle 2 stroke-width:2px,fill:none,stroke:grey;

```

Your application will communicate with the blockchain via a locally run instance of the Ergo Node. The Node provides an API that is used by your SDK logic to carry out operations on the blockchain. The on-chain code is ErgoScript, the off-chain code can be done in a programming langage of your choice. 

- [Set up a local Node on mainnet or testnet](/node/)

For your first interaction with the Ergo blockchain, [this video](https://www.youtube.com/watch?v=Md5s-XV6-Hs) takes you through the steps to programmatically create & submit a transaction. Alternatively, dive straight into ErgoScript or any of the other paths laid out below. 

Make sure to check out the [Resources page](dev/start/resources/) and [dev-tools tab on sigmaverse.io](https://sigmaverse.io/)

## Libraries

- [Back-end libraries (SDKs)](stack/back-end)
- [Front-end libraries](stack/front-end/)

## Languages

- [Start coding in JVM (Scala/Java)](/dev/stack/appkit/)
- [Start coding in Rust](/dev/Languages/rust)
- [Start coding in Python](/dev/Languages/python)
- [Start coding in JSON](/dev/stack/jde)
- [Start coding in ErgoScript](scs/ergoscript/)



## Tutorials


- [ErgoTutorials](https://www.youtube.com/channel/UCyOIxD7YSHN5QwLIulOWrew)
- [Kbit: Learning blockchains like Cardano and Ergo](https://www.youtube.com/watch?v=HDn49bToTMI)
- [Ergo 101 : Side tooling for building dApps on Ergo](https://dav009.medium.com/ergo-101-side-tooling-for-building-dapps-on-ergo-c71889d60826)

## Interactive

- [Interactive tutorials for javascript dApp development](https://play.dappstep.com/)


### Educational Courses

- DeCo (Decentralised Collaboration) teaches participants will learn about extended UTXO and boxes, registers, ErgoScript, designing simple systems, multi-transaction systems, and much more. Join the [DeCo Discord](https://discord.gg/PQPyFbKZ9z) for more information or watch their full courses on [youtube](https://www.youtube.com/channel/UCyOIxD7YSHN5QwLIulOWrew/playlists). 
- There are also planned [Educational Classes on Game Building and Design](https://medium.com/@lgmeister/the-future-of-ergogames-io-hosting-educational-classes-on-game-building-and-design-679afd2632d4) from [ErgoGames.io](https://ergogames.io)

### ERGOHACK

We host regular Hackathons on our Discord server. See [ergohack.io](https://ergohack.io/) for more information.





