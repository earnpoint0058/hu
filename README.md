# 0G Hackathon Quiz Answers (by GG)

---

## Phase 1 - Web

### 3 Basics (Unit 1 - Web3 Overview)
- True  
- Web 3.0  
- True  
- Bitcoin  
- True  

### Unit 2 - Introduction to Blockchain Technology
- False  
- False  
- False  
- False  
- True  
- False  

### Unit 3 - Wallet Principles and Security
- True  
- False  
- True  

### Unit 4 - Blockchain Application Scenarios
- False  
- Ethereum  
- False  
- True  
- False  

---

## Phase 2 - Ecosystem Overview

### Unit 1 - Understanding 0G
- Because it also supports other high-performance scenarios like DeFi and decentralized gaming  
- Redefine ownership, execution rights, and verification rights of AI models / Ensure transparency of model parameters and inference results / Enable AI services to be triggered and audited via smart contracts  

### Unit 2 - Exploring the Four Technical Pillars of 0G
- True  
- True  
- True  
- To improve efficiency by verifying only parts of data blocks  

### Unit 3 - Deploying Smart Contracts on 0G
- `forge --version`  
- 16601  
- Mint initial tokens to the contract creator during deployment  
- `-broadcast`  
- Query the contract address in the 0G block explorer  

---

## Phase 3 - Basic Solidity Syntax (Solidity 101)

### Unit 1 - Setup
- True  
- `pragma solidity ^0.8.20;`  
- `contract Example { }`  
- True  
- `int levels = 3;`  
- True  

### Unit 2 - Variable Type
- `uint num = 1;`  
- `int128 num = -200;`  
- False  
- `bool test = true;`  
- `bool example = d || e;`  
- `uint ownerBalance = wallet.balance;`  
- True  
- `address payable a = payable(0x5B38Da6a701c568545dCfcB03FcB875f56beddC4);`  
- True  

### Unit 3 - Function 1
- `function test() { }`  
- `function myFunction(uint temp, uint time) { }`  
- `function test() returns(bool) { }`  
- True  

### Unit 4 - Function 2
- `result = x * x;`  
- `result = subtract(j, i);`  
- `function myFunction() public { }`  
- True  
- private  
- False  
- False  
- `function myFunction() internal { }`  
- False  
- `function myFunction() external { }`  

### Unit 5 - Mapping
- `mapping(address => uint) pool;`  
- True  
- `uint => string`  
- `myMapping[50] = true;`  
- False  
- `bool checkFlags = flags[42];`  
- `delete balance[address(0x123)];`  

### Unit 6 - Classification
- `uint amount = 22;`  
- False  
- `uint num = 5;`  
- `function example() public pure {}`  
- True  
- `function books() public view returns (uint) {}`  
- True  

### Unit 7 - Wrap up
- `constructor(uint age) { }`  
- `require(x > 10);`  
- `address owner = msg.sender;`  
- False  

---

## Phase 3 - Basic Solidity Syntax (Solidity 102)

### Unit 1 - String
- `uint num = 66;`  
- True  
- string  
- False  
- `string.concat(a, b);`  

### Unit 2 - Data Location
- name  
- False  
- `string memory tempString = "Hello, Solidity";`  
- True  
- `function operate(string calldata myName) public {}`  
- True  

### Unit 3 - Struct
- ```solidity
  struct School {
      string name;
      uint256 num_Student;
      uint256 num_Teacher;
  }
