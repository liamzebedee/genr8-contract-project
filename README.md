Template project for the [GENR8 Hackathon](https://genr8.codes). This automatically connects to our private blockchain. 

Built with [Embark framework](https://embark.status.im/).

## Setup
```
git clone https://github.com/liamzebedee/genr8-contract-project
cd genr8-contract-project
yarn
```

## Develop
Write some Solidity contracts in `contracts/`. 

Test them by running 

```
$(yarn bin)/embark run --nodashboard
```

## Deploy
To deploy contract to our blockchain:

```
$(yarn bin)/embark run --nodashboard genr8
```