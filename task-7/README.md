# Task 7

1. Screenshots or video of your application running on Godwoken.

#1 Deploy smart contract
![](https://github.com/arnaudatcomet/nervos/blob/main/task-7/1-deploy.png)

#2 Read initial value of the smart contract saving
![](https://github.com/arnaudatcomet/nervos/blob/main/task-7/2-read.png)

#3 Add deposit to savings
![](https://github.com/arnaudatcomet/nervos/blob/main/task-7/3-add.png)

#4 Read the new deposit amount
![](https://github.com/arnaudatcomet/nervos/blob/main/task-7/4-read-new.png)

2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.
https://github.com/arnaudatcomet/nervos/blob/main/task-7/dApp

3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)
Deployed contract address
```
    0x2FD56Bf6778AEf05aDfBDD7760DcAB8EA76C17a6
```
Deployed contract tx hash
```
    0x0451c21175c469b88c787c1d52eb18afdcaf177dbfede9cb47a55a60b71d4dc1
```
ABI
```
    [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "add",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```