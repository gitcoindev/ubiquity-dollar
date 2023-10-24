# CreditClockFacet
[Git Source](https://github.com/ubiquity/ubiquity-dollar/blob/8e774eecb089180805d9583f0e7776529582e747/src/dollar/facets/CreditClockFacet.sol)

**Inherits:**
[Modifiers](/src/dollar/libraries/LibAppStorage.sol/contract.Modifiers.md)

CreditClock Facet


## Functions
### setManager

Updates the manager address


```solidity
function setManager(address _manager) external onlyAdmin;
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`_manager`|`address`|New manager address|


### getManager

Returns the manager address


```solidity
function getManager() external view returns (address);
```
**Returns**

|Name|Type|Description|
|----|----|-----------|
|`<none>`|`address`|Manager address|


### setRatePerBlock

Sets rate to apply from this block onward


```solidity
function setRatePerBlock(bytes16 _ratePerBlock) external onlyAdmin;
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`_ratePerBlock`|`bytes16`|ABDKMathQuad new rate per block to apply from this block onward|


### getRate


```solidity
function getRate(uint256 blockNumber) external view;
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`blockNumber`|`uint256`|Block number to get the rate for. 0 for current block.|


