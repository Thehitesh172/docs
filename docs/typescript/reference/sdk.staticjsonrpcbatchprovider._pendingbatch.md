---
slug: /reference/sdk.staticjsonrpcbatchprovider._pendingbatch
title: StaticJsonRpcBatchProvider.\_pendingBatch property
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# StaticJsonRpcBatchProvider.\_pendingBatch property

**Signature:**

```typescript
_pendingBatch: Array<{
  request: {
    method: string;
    params: Array<any>;
    id: number;
    jsonrpc: "2.0";
  };
  resolve: (result: any) => void;
  reject: (error: Error) => void;
}> | null;
```