# ERC20 SmartContract

## Creating Smart Contract

1. Remix Ethereum
1. On deploy tab select the "Injected Web3" which integrates with Ropsten network
1. The Smart Contract account it displayed on the "Deploy" tab. 


## Sample Running Smart Contract

Deployed Contract
1. ERC20.sol: ipfs://QmejdqNJpxrRweqo9rLZEKBkU14TP64aDeQ1PmyNWyrQgn
1. https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v4.0.0/contracts/token/ERC20/ERC20.sol: ipfs://QmXGhsAPeemtVQ8ip5CsParvX3sgpMm4Lq8EccS3YaTtwA
1. metadata.json: ipfs://QmZyBwDhNeKzFPFxTVAEi4Z49L6oNcrwp3gGF9nYJH8HdL

Sample Running Address: 0xC44bf84C7d877A286b179Af92C400aA16CaEC251

Gas Estimator (1GAS = 1GWEI): https://br.beincrypto.com/converter/gas-to-usd?amount=1


# Run and Simulate Contract through Remix IDE
Remix is an online ide to create a solidity smart contract. It also has the feature to compile run, deploy and simulate smart contracts.

1. Open Remix IDE.
1. Select environment Solidity
1. Go to File Explorer Tab and create a file Lottery.sol
1. Get the Contract Code
1. Go to Solidity Compiler Tab and Select
1. Compiler Version to 0.8.10
1. Language as Solidity
1. EVM as Compiler Default
1. Now click Compile ERC20.sol
1. You can enable auto-compile by check the checkbox Auto Compile
1. Go to Deploy And Run Transaction Tab and Deploy the contract in local EVM
1. Your contract functionality will be available in Deploy And Run Tracsaction tab, under the Deployed Contract section

# Deploy the contract to Rinkeby Network through Remix Ide
Testnets provide developers a place to kick the smart contract and test before the real assets being involved. These Testnets behave very much like the main-net and does not require actual money(ether). Here we are going to try Rinkeby Testnet.

1. Make sure you run the Lottery contract using previous section instructions
1. Open Metamask, put the password and make sure, you are connected to the Rinkeby network.
1. Go to Deployed And Run Transaction tab and select
1. Environment is Injected Web3
1. As account, your Metamask wallet address should be selected
1. Make sure you have enough ether in your wallet to deploy the contract
1. Now click Deploy. This will deploy your contract to the Rinkeby network.
1. In the Remix IDE, check Log Section and grab the Transaction Hash and store it.
1. Go to Ether Scan and search for the Transaction Hash. You will get the Deployed Contract Address. Also, this Contract Address will be required further.