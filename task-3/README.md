https://gitcoin.co/issue/nervosnetwork/grants/3/100026208

A screenshot of the console output immediately after you have successfully issued a smart contract call.
![Screenshot of the call](https://github.com/arnaudatcomet/nervos/blob/main/task-3/smart-contract-call.png)

he transaction hash from the console output (in text format).:
0xe56fd0601a26d9199d32d8d0133c19eb62a46eb04e6801d83211301c4343b0cd

The contract address that you called (in text format).:
0xE59dd17c01102ad9e840294036283540c00D7467

The ABI for contract you made a call on (in text format).:
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
  }]
  ```