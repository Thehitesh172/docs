---
slug: /reference/sdk.erc20.claimto
title: Erc20.claimTo() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# Erc20.claimTo() method

Claim a certain amount of tokens to a specific Wallet

## Example

```javascript
const address = "{{wallet_address}}"; // address of the wallet you want to claim the NFTs
const quantity = 42.69; // how many tokens you want to claim

const tx = await contract.erc20.claim(address, quantity);
const receipt = tx.receipt; // the transaction receipt
```

**Signature:**

```typescript
claimTo(destinationAddress: string, amount: Amount, options?: ClaimOptions): Promise<TransactionResult>;
```

## Parameters

| Parameter          | Type                                  | Description                              |
| ------------------ | ------------------------------------- | ---------------------------------------- |
| destinationAddress | string                                | Address you want to send the token to    |
| amount             | [Amount](./sdk.amount.md)             | Quantity of the tokens you want to claim |
| options            | [ClaimOptions](./sdk.claimoptions.md) | <i>(Optional)</i>                        |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

- The transaction receipt

## Remarks

Let the specified wallet claim Tokens.