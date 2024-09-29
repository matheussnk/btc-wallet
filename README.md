<h1>
Creating and Using a Cryptocurrency Wallet
</h1>


Repository documenting a **Binance - Blockchain Developer with Solidity** project challenge: building a bitcoin wallet generator, importing it into specific software and executing bitcoin send and receive transactions. 

   
## Objectives 

Work on developing a wallet generator and carry out bitcoin transactions. Project carried out for the course **“Blockchain Specialist Training”**, on the [Digital Innovation One] platform (https://www.dio.me/), under the guidance of Professor Cassiano Peres. 



## Tech 

[![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=30A3DC)]() 
![Static Badge](https://img.shields.io/badge/Electrum%20Bitcoin%20Wallet%20-%20blue?logo=blockchain) 
![Static Badge](https://img.shields.io/badge/Bitcoin%20Faucet%20Generator%20-%20black?logo=bitcoin) 
<br>
## Project
<table>
  <thead>
    <tr align=“left”>
      <th>No</th>
      <th>Steps</th>
    </tr>
  </thead>
  <tbody align=“left”>
    <tr>
      <td>01</td>
      <td>Code Development in VS Code</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Transition to Electrum Bitcoin Wallet</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Making Test Bitcoin Transactions</td>  
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

______________

## Stage 1: Code development in VS Code 

The start of our project is marked by the use of VS Code, an integrated development environment, to develop the code in JavaScript. This is the basis of our Bitcoin wallet generator. 

To support our development, we proceeded to download essential dependencies: 

- **bip39**: For generating wallet seeds, which are sets of words used to retrieve or create wallets. 

- **bip32**: Provides functionalities necessary for wallet generation, including the creation of HD (Hierarchical Deterministic) wallets that allow for a more secure and systematic organization of keys. 

- **bitcoinjs-lib**: A comprehensive library that makes it easier to handle Bitcoin operations, including creating addresses and transactions. 

With these tools in hand, we followed a series of steps to build the wallet generator code: 

1. Import the dependencies. 

2. Define the Bitcoin network to be used. 

3. Establish the structure for HD wallets. 

4. Generate a mnemonic as a seed. 

5. Create the root of the HD wallet. 

6. Generate an account with private and public keys. 

7. Create the Bitcoin address. 

8. Display the wallet data: address, private key and seed.

______________
 
## Step 2: Transition to the Electrum Bitcoin Wallet 

To carry out the test Bitcoin transactions, we chose **[Electrum Bitcoin Wallet](https://electrum.org/)** as our transaction platform. After downloading and installing the software on the local machine, we enabled *testnet* mode, to simulate transactions without the use of real bitcoins, providing a secure environment for testing. 

Once Electrum is ready, we proceed to **import the private key previously generated in VS Code**. This key is the link to our personalized wallet, now called “dio-wallet-testnet” within Electrum. This process gives Electrum the ability to access and manage the test bitcoins that our wallet will move.  

So, with the private key duly imported, our Electrum wallet is operational, ready to start sending and receiving test bitcoins. 

______________

## Step 3: Making Test Bitcoin Transactions 

With our wallet ready in Electrum and the private key imported, we move on to the final stage of our project: carrying out bitcoin sending and receiving transactions on the testnet. 
______________


In this way, we completed the project challenge. Our goal was to build a bitcoin wallet generator from scratch, import this wallet into specialized software and, finally, execute bitcoin sending and receiving transactions on the testnet. 

It is important to note that the project was developed using the version of node@16.15.0.

As the version is old, I chose to use nvm to install the packages
