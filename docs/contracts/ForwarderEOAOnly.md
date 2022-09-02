---
slug: /ForwarderEOAOnly
title: ForwarderEOAOnly
hide_title: true
displayed_sidebar: contracts
---

# ForwarderEOAOnly

## Methods

### execute

```solidity
function execute(MinimalForwarderEOAOnly.ForwardRequest req, bytes signature) external payable returns (bool, bytes)
```

#### Parameters

| Name      | Type                                   | Description |
| --------- | -------------------------------------- | ----------- |
| req       | MinimalForwarderEOAOnly.ForwardRequest | undefined   |
| signature | bytes                                  | undefined   |

#### Returns

| Name | Type  | Description |
| ---- | ----- | ----------- |
| \_0  | bool  | undefined   |
| \_1  | bytes | undefined   |

### getNonce

```solidity
function getNonce(address from) external view returns (uint256)
```

#### Parameters

| Name | Type    | Description |
| ---- | ------- | ----------- |
| from | address | undefined   |

#### Returns

| Name | Type    | Description |
| ---- | ------- | ----------- |
| \_0  | uint256 | undefined   |

### verify

```solidity
function verify(MinimalForwarderEOAOnly.ForwardRequest req, bytes signature) external view returns (bool)
```

#### Parameters

| Name      | Type                                   | Description |
| --------- | -------------------------------------- | ----------- |
| req       | MinimalForwarderEOAOnly.ForwardRequest | undefined   |
| signature | bytes                                  | undefined   |

#### Returns

| Name | Type | Description |
| ---- | ---- | ----------- |
| \_0  | bool | undefined   |