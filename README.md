# Solidity API

## docgen_test

`this contract` docgen test.

_all function calls are currentlu implement without side effects_

### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

token transfer event.

| Name | Type | Description |
| ---- | ---- | ----------- |
| from | address | sender address |
| to | address | receiver address |
| value | uint256 | amount |

### constructor

```solidity
constructor(uint256 a1) public
```

create contract

| Name | Type | Description |
| ---- | ---- | ----------- |
| a1 | uint256 | test |

### transfer

```solidity
function transfer(address to, uint256 amount) public pure returns (bool)
```

token send

| Name | Type | Description |
| ---- | ---- | ----------- |
| to | address | receiver address |
| amount | uint256 | send value |

| Name | Type | Description |
| ---- | ---- | ----------- |
| [0] | bool | true or false. |

