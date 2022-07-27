# Hyperverse FastCamp
My repo where I learn how to use the Hyperverse by Decentology!

## How to create an open minting site using the Hyperverse for Ethereum

### Step 1: Get test ETH
- Open your Ethereum wallet of choice. Make sure to adjust your settings so that you are using the Rinkeby test network.

- Go to a faucet website, such as [Chainlink](https://faucets.chain.link/rinkeby), and send some test ETH to your wallet. The reason for this is because we will need it to be able to interact with the example app and test functions.

### Step 2: Set up the Hyperverse
- Clone Decentology's Hyperverse Monorepo. Visit the [Github page](https://github.com/decentology/hyperverse-mono) for system requirements and instructions.

- Once everything is set up and installed, use the terminal to change the directory to the erc721 app and enter the command `pnpm dev`. You can then run the app locally by using your browser to open [localhost:3000](http://localhost:3000/)

### Step 3: Test out the ERC-721 module
- Once the example app is up and running, connect your wallet with the test ETH to the app. If you're not familiar with web3 or using websites that handle cryptocurrency, connecting your wallet is akin to logging into a website or a browser such as Google. It's just a way for the website to identify you as the person interacting with the app. You will see a notification pop up instructing you to sign (authorize) the transaction. 

- The first thing to do is to create an instance. To make sure everything is working, under the heading "Token Factory Functions", click the button to create an instance. Sign the transaction notification. You can even view your transaction on [Etherscan](https://rinkeby.etherscan.io) under the Rinkeby test network to watch its progress and see when it's successful.

- In your code editor, navigate to the _app.tsx file (you should still be in the erc721 directory). On line 59 of that file, change the tenant ID to your wallet address. You can do this by going to the example app, clicking the button with your wallet address, and using the button to copy that address. Then, copy/paste into your code, replacing the address that's in there already. This will make sure that any interactions you use interact with your wallet address.

### Step 4: Customize!


