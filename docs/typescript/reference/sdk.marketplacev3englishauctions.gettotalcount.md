---
slug: /reference/sdk.marketplacev3englishauctions.gettotalcount
title: MarketplaceV3EnglishAuctions.getTotalCount() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# MarketplaceV3EnglishAuctions.getTotalCount() method

Get the total number of english auctions

## Example

```javascript
const totalAuctions = await contract.englishAuctions.getTotalCount();
```

**Signature:**

```typescript
getTotalCount(): Promise<BigNumber>;
```

**Returns:**

Promise&lt;BigNumber&gt;

Returns the total number of auctions created.