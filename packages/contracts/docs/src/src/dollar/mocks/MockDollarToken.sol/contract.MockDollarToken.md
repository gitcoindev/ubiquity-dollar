# MockDollarToken
[Git Source](https://github.com/ubiquity/ubiquity-dollar/blob/fc55925e18af3f4cb5171ecd66ba4c48dc994260/src/dollar/mocks/MockDollarToken.sol)

**Inherits:**
ERC20


## Functions
### constructor


```solidity
constructor(uint256 initialSupply) ERC20("ubiquityDollar", "uAD");
```

### burn


```solidity
function burn(address account, uint256 amount) public;
```

### burnFrom


```solidity
function burnFrom(address account, uint256 amount) public;
```

### mint


```solidity
function mint(address account, uint256 amount) public;
```
