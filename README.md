# Hello World DApp on Ethereum Blockchain
[Online Demo using web3](http://sauravtom.com/hello-world-ethereum-blockchain/)


[Online Demo using ethers.js](http://sauravtom.com/hello-world-ethereum-blockchain/ethers-js/) 

[about ethers.js](https://docs.ethers.io/ethers.js/html/)
1. `git clone https://github.com/sauravtom/hello-world-ethereum-blockchain.git`

2. `cd hello-world-ethereum-blockchain`

3. Setup metamask for your browser using [this guide](https://medium.com/@followcoin/how-to-install-metamask-88cbdabc1d28)

4. Get some test ethers from the [roposten faucet](https://faucet.metamask.io/)

5. Make sure you're Metamask account is connected to the Roposten network
![alt text](https://raw.githubusercontent.com/sauravtom/hello-world-ethereum-blockchain/master/demo-images/1.png)

6. Copy the content of `Hello.sol` to [online Remix IDE.](http://remix.ethereum.org) Follow [this guide](https://media.readthedocs.org/pdf/remix/latest/remix.pdf) to learn more about Remix IDE

7. Inside remix, compile and deploy the smart contract to Roposten Network

⋅⋅⋅Compile the smart contract `Hello.sol` from the Compile tab ![alt text](https://raw.githubusercontent.com/sauravtom/hello-world-ethereum-blockchain/master/demo-images/5.png)

⋅⋅⋅Deploy the smart contract from the Run tab, after selecting the correct environment as shown ![alt text](https://raw.githubusercontent.com/sauravtom/hello-world-ethereum-blockchain/master/demo-images/2.png)

8. Copy the smart contract address to clipboard ![alt text](https://raw.githubusercontent.com/sauravtom/hello-world-ethereum-blockchain/master/demo-images/4.png)

9. Copy the smart contract abi json to clipboard ![alt text](https://raw.githubusercontent.com/sauravtom/hello-world-ethereum-blockchain/master/demo-images/3.png)

10. Paste the smart contract address and the abi json to the `index.js` file (Use https://jsonformatter.org/ to flatten the abi json object for code cleanliness)

9. Save your changes and start a local web server to serve the `index.html` file


using python


`python -m SimpleHTTPServer` 


or node


`npm install http-server -g`


`http-server`

