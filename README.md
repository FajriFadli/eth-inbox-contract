# eth-inbox-contract
A smart contract used for storing and calling messages to/from Ethereum blockchain.

To deploy your own instance of this contract, you'll need to have [Node.js](https://nodejs.org/en/) installed, an Ethereum wallet, and an [Infura](https://infura.io/) account.

Clone this repo and type `npm install` inside the repo's folder to install all the dependencies it'll need, then paste in your wallet mnemonic and Infura endpoint into the [mnemonic.txt](secrets/mnemonicDummy.txt) and [endpoint.txt](secrets/endpointDummy.txt) respectively.

Then use the command `node deploy.js` to deploy your smart contract into the Ethereum blockchain.
