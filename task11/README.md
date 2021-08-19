# TASK 11

### 1- A screenshot of the accounts you created

<img src="https://github.com/orhanors/nervos-hackhaton/blob/master/task11/ss1.jpg" />

### 2- A link to the Layer 1 address you funded on the Testnet Explorer

- <a href="https://explorer.nervos.org/aggron/address/ckt1qyqxyen6rf4727qxcxzfe6xhmanz4cmrp0xsg2ewye">Funded Account Address </a>

### 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/orhanors/nervos-hackhaton/blob/master/task11/ss2.png" />

### 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/orhanors/nervos-hackhaton/blob/master/task11/ss3.png" />

### 5- The transaction hash from the console output

- Write call transaction hash:

```bash
0xb017ce8cfdaa552b8c9f4490c77c98e69754ea194dffc62b0ebfd809d3c1f1f4
```
- Deposit transaction hash:

```bash
0xc78f7d6a601921c23de239a1b0138a22608c1d99445267096b9ba2335333ca40
```

### 6- The contract address that you called

```bash
0xec1706d0A6b351784cADF40E91aCA8a56cd6adad
```
### 7- The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "tipAmount",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "address payable",
          "name": "author",
          "type": "address"
        }
      ],
      "name": "PostCreated",
      "type": "event"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "tipAmount",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "address payable",
          "name": "author",
          "type": "address"
        }
      ],
      "name": "PostTipped",
      "type": "event"
    },
    {
      "inputs": [],
      "name": "name",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "postCount",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "posts",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "tipAmount",
          "type": "uint256"
        },
        {
          "internalType": "address payable",
          "name": "author",
          "type": "address"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "createPost",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_id",
          "type": "uint256"
        }
      ],
      "name": "tipPost",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    }
  ]
```

### 8- Your Tron address

```bash
TTWQNVabq4vA8ZLu8CMVEigRsswmY6NNzj
```





