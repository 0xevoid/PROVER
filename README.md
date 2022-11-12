<p style="font-size:14px" align="center">
<a href="https://m.do.co/c/2cea00d4f9bble" target="_blank">Deploy your VPS using our referral link to get 100$ free bonus for 60 days <img src="https://user-images.githubusercontent.com/50621007/183284313-adf81164-6db4-4284-9ea0-bcb841936350.png" width="30"/></a>
</p>

<p align="center">
  <img height="175" height="auto" src="https://user-images.githubusercontent.com/38981255/185994172-0b4e4ea8-f81a-48db-8020-9be619f485b7.png">
</p>

<p style="font-size:150px" align="center"> TUTORIAL ALEO PROVER TESTNET INCENTIVIZED

> TESTNET 3 INCENTIVES We have 25 million Aleo credits for developers, hackers, experts and validators during Testnet3. How can I get a prize?
- Developer:
Can earn prizes for writing, spreading, and running the program.
- Hacker:
Can earn rewards by identifying bugs in our protocol.
- Prover:
can generate PoSW evidence and gain imbalance.
- Validators:
Can participate in block and context production as part of AleoBFT and earn rewards from the protocol

## Hardware requirements

Here are the **minimum** requirements for running Aleo nodes:

| Component | Minimum Requirements |
|----------|---------------------|
|CPU|16-core (Preferably 32-core)|
|RAM|16GB memory (preferably 32GB)|
|Storage|500 GB HDD|

## Overview
**snarkOS** is a decentralized operating system for private applications. It forms the backbone of [ Aleo ](https://aleo.org/) and
allows the app to verify and save status in a publicly verifiable manner.

## Auto Install
```
wget -O prover.sh https://raw.githubusercontent.com/0xevoid/PROVER/main/prover.sh && chmod +x prover.sh && ./prover.sh
```

> **NOTE: Let the installation complete and don't forget to backup all your data that appears, after the automatic installation**

# Run Prover

```
cd snarkOS
screen -R prover
```

```
./run-prover.sh
```

- Enter the Private Key that you have backed up before and leave it until it's finished.
- `ctrl A D` to save the screen so that it runs on your PC background
- If you want to return to the running screen, use the command `screen -Rd prover`

## Uninstall

**Use If You Want To Delete Node Data**


```
rustup self uninstall
rm -rf prover.sh
rm -rf snarkOS
```
