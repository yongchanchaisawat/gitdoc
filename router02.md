# Router02

## Code

[`PancakeRouter01.sol`](https://github.com/BBT-DeFi/BBT-Swap/blob/main/periphery/contracts/PancakeRouter01.sol)

## Address

BBTswapRouter02 is deployed at ~~0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D~~  on the Bitkub smart chain mainnet, and Bitkub smart chain testnets. It was built from commit 25925.

## Read-Only Functions

### factory

```javascript
function factory() external pure returns (address);
```

 Returns ~~**factory address.\(link edit\)**~~

### WETH

```javascript
function WETH() external pure returns (address);
```

### quote

See ~~**quote.**~~

### getAmountOut

See getAmountOut.

### getAmountIn

~~See getAmountIn.~~

### getAmountsOut

```javascript
function getAmountsOut(uint amountIn, address[] calldata path) external view returns (uint[] memory amounts);
```

See getAomuntsOut.

### getAmountsIn

```javascript
function getAmountsIn(uint amountOut, address[] calldata path) external view returns (uint[] memory amounts);
```

See getAmountsIn

## State-Changing Functions

### addLiquidity

