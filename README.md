# ERC20 Token w/ Crowdsale (Initial Token Offering) Smart Contracts

## Description of repository

**NodeJS & TruffleSuite Project for writing smart contracts on binance smart chain in Solidity programming language for the Ethereum Virtual Machine. This is the code for an ERC20 Token && Crowdsale Smart contracts based on OpenZeppelin Contract Library.**

### How to run this project

- Open your bash terminal and set up your project directory by cloning the repo and installing dependencies needed.

```bash
git clone 'this-github-repo-url'
cd 'repo/root/directory'
npm install
```

- Change the values inside of `truffle-config.js` && `./migrations/2_deploy.js` to match your desired specified parameters. Consider revising your own version of this to include additional crowdsale methods by including additional OpenZeppelin Contract components such as; emissions or distribution controls.

- When you are ready to compile & deploy, run the commands below to do so.

```bash
truffle compile
truffle deploy --network bscTestnet #Use desired network from truffle-config.js
```

**_If you run into any issues, feel free to send me an email or join my Telegram channel where I try to help as many as I can, when I can. Thank you and don't forget to check out my YouTube @hashguide & website TheCryptoist.com & most of all, don't forget to share to the next person so we can further out reach!_**
