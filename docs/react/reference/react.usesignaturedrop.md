---
slug: /reference/react.usesignaturedrop
title: useSignatureDrop
hide_title: true
displayed_sidebar: react
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# useSignatureDrop

> Warning: This API is now obsolete.
>
> This hook is deprecated and will be removed in a future major version. You should use instead.
>
> ```diff
> - const signatureDrop = useSignatureDrop("0x1234...");
> + const signatureDrop = useContract("0x1234...", "signature-drop").contract;
> ```

Hook for getting an instance of an `SignatureDrop` contract. This contract is meant to interface with ERC721 compliant NFTs that can be lazily minted.

## Example

```javascript
import { useContract } from '@thirdweb-dev/react'

export default function Component() {
  const { contract } = useContract("<YOUR-CONTRACT-ADDRESS>", "signature-drop")

  // Now you can use the Signature drop contract in the rest of the component

  // For example, this function will let the connected wallet claim a new NFT
  async function claim(quantity) {
    await contract.claim(quantity)
  }

  ...
}
```

**Signature:**

```typescript
export declare function useSignatureDrop(
  contractAddress?: RequiredParam<string>,
): import("@thirdweb-dev/sdk").SignatureDrop | undefined;
```

## Parameters

| Parameter       | Type                                                    | Description                                                                              |
| --------------- | ------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| contractAddress | [RequiredParam](./react.requiredparam.md)&lt;string&gt; | <i>(Optional)</i> the address of the NFT Drop contract, found in your thirdweb dashboard |

**Returns:**

import("@thirdweb-dev/sdk").SignatureDrop \| undefined