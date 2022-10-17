#  Challenge 20: Joint Savings Smart Contract

This challenge builds a simple joint savings smart contract on the Ethereum network using Solidity. Inside the smart contract are functions to withdraw, deposit, and setAccounts in order to specify two user addresses that can be used to control the joint savings account.

---

## Technologies

This smart contract is written in solidity v0.5.0 and can be compiled and run on an ethereum development network.

---

## Installation Guide

You have a few options to get this code on your computer, two popular options are:

1. Download a ZIP of this repositories files 
[here](https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/archive/refs/heads/main.zip).

2. [Fork this respository](https://docs.github.com/en/get-started/quickstart/fork-a-repo "Fork a Repo - 
GitHub Docs") to your github account.

<p align="center">
<img src="https://github.com/Warp-9000/uw-fintech-2022-module01-challenge/blob/main/instructions/github-fork-button-screenshot.png?raw=true" 
alt="Fork UI on GitHub.com"
width="55%"/>
</p>

After forking the respository you can use `git clone 
your-username@domain.com:your-git-username/challenge-20-joint-savings-smart-contract.git` 
to download a copy of the forked respository to your computer.

Forking has the added benefit of enabling your to easily keep your copy of the 
application up-to-date should any changes or improvements be made in the future.

---

## Usage

***Please note:*** these usage instructions assume you are using an editor that can compile the solidity code and deploy the smart contract to an ethereum development network.

For example you could perform the following:

1. Load the code in `joint_savings.sol` in <a href="https://remix.ethereum.org">remix.ethereum.org</a>.
2. Compile the code using a `0.5.x` version compiler.
3. Deploy the smart contract on `Remix VM (London)`.

### Examples of the application running:

Using `setAccounts` to set the two accounts that own the contract:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%204.51.39%20PM%20-%20used%20setAccounts%20function.png?raw=true" 
alt="used setAccounts function" width="85%" />
</p>

Deposit 1 ether as wei to the contract:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%204.57.35%20PM%20-%20send%201%20ether%20as%20wei.png?raw=true" 
alt="depositing 1 ether as wei" width="85%" />
</p>

Deposit 10 ether as wei to the contract:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%204.59.13%20PM%20-%20send%2010%20ether%20as%20wei.png?raw=true" 
alt="depositing 1 ether as wei" width="85%" />
</p>

Deposit 5 ether to the contract:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%205.00.06%20PM%20-%20send%205%20ether.png?raw=true" 
alt="deposit 5 ether" width="85%" />
</p>

Withdraw 5 ether to `accountOne`:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%205.02.40%20PM%20-%20withdraw%205%20ether%20to%20accountOne.png?raw=true" 
alt="withdraw 5 ether to accountOne" width="85%" />
</p>

Withdraw 10 ether to `accountTwo`:
<p align="center">
<img src="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/blob/main/Execution_Results/Screen%20Shot%202022-10-16%20at%205.04.31%20PM%20-%20withdraw%2010%20ether%20to%20accountTwo.png?raw=true" 
alt="withdraw 10 ether to accountTwo" width="85%" />
</p>

---

## Contributors

Thanks!

<a href="https://github.com/warp-9000/challenge-20-joint-savings-smart-contract/graphs/contributors">
<img src="https://contrib.rocks/image?repo=warp-9000/challenge-20-joint-savings-smart-contract" />
</a>
