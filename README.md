# Hyperverse FastCamp
My repo where I learn how to use the Hyperverse by Decentology!

## How to create an open minting site using the Hyperverse for Ethereum

### Step 1: Get test ETH
- Open your Ethereum wallet of choice. Make sure to adjust your settings so that you are using the Rinkeby test network.

- Go to a faucet website, such as [Chainlink](https://faucets.chain.link/rinkeby), and send some test ETH to your wallet. The reason for this is because we will need it to be able to interact with module.

### Step 2: Set up Hyperverse
- Go to [eth.hyperverse.dev](https://eth.hyperverse.dev/) and choose the ERC-721 module. Click the button in the top right corner of the app to connect your wallet with the test ETH to the module. If you're not familiar with web3 or using websites that handle cryptocurrency, connecting your wallet is akin to logging into a website or a browser such as Google. It's just a way for the website to identify you as the person interacting with the app. You will see a notification pop up instructing you to sign (authorize) the transaction.

- Open your code editor or terminal, and navigate to the directory you want to store your app in.

- Clone the Next.js boilerplate code into that directory by entering the command `git clone https://github.com/decentology/erc721-nextjs-boilerplate` into the terminal.

- Change the directory so that you're in the erc721-nextjs-boilerplate folder. Run the command `npm i` to install the needed dependencies for the module.

- Navigate to your _app.tsx file. Within the MyApp function, change the tenantId to the wallet address you used to connect to the module. This will make sure that any functions from the module you use interacts with your wallet address.

- Enter the command `npm dev` into the terminal. You will then be able to see the app locally on [localhost:3000](http://localhost:3000/). You are now connected to the Hyperverse!

### Step 3: Customize!

- Any aesthetic changes you want to make can be achieved by adjusting the code in the index.tsx file (in the pages folder) or the Home.module.css file (in the styles folder).

- Additionally, you can customize the functionality of your app by checking out the Dashboard and Code tabs of the ERC-721 module on [eth.hyperverse.dev](https://eth.hyperverse.dev/). There you can see the code snippets and demos via Storybook for functions that allow you to get the balance of accounts, whitelist wallet address for minting, create an NFT collection, you name it!


