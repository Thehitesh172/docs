---
slug: /reference/sdk.contractfunctionsfromabi
title: ContractFunctionsFromAbi type
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# ContractFunctionsFromAbi type

**Signature:**

```typescript
export type ContractFunctionsFromAbi<TAbi extends Abi> = {
  [TFunctionName in TAbiFunctionNames<TAbi>]: ExtractFunctionType<
    TAbi,
    TFunctionName
  >;
};
```

**References:** [TAbiFunctionNames](./sdk.tabifunctionnames.md), [ExtractFunctionType](./sdk.extractfunctiontype.md)