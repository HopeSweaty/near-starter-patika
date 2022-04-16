# `near-sdk-as` Starter Kit for Patika Bootcamp
Switch branch to which you want to deploy your contract.
## Setup
First you need to clone the this repository:

```bash
git clone https://github.com/HopeSweaty/near-starter-patika.git
```

Then you need to install the dependencies:

```bash
cd near-starter-patika
yarn
```

Build contract:

```bash
yarn build:relase
```

Deploy contract:

```bash
near deploy --accountId "yourtestnetusername" --wasmFile build/release/simple.wasm
```

Test contract:

```bash
near view "yourtestnetusername" helloWorld '{"names": ["<Your Name>", "<Friend Name>"]}'
```

### Forked from starter--near-sdk-as 