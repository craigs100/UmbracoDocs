---
title: DiscountService
description: API reference for DiscountService in Umbraco Commerce
---
## DiscountService

```csharp
public class DiscountService : ServiceBase<DiscountService>, 
    ICachedEntityService<DiscountReadOnly>, IDiscountService
```

**Inheritance**

* class [ServiceBase&lt;TSelf&gt;](servicebase-1.md)
* interface [ICachedEntityService&lt;TEntityType&gt;](icachedentityservice-1.md)
* interface [IDiscountService](idiscountservice.md)

**Namespace**
* [Umbraco.Commerce.Core.Services](README.md)

### Constructors

#### DiscountService

```csharp
public DiscountService(IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, 
    ILogger<DiscountService> logger, ICacheAccessor cacheAccessor, 
    DiscountRuleProviderCollection discountRuleProviders, 
    DiscountRewardProviderCollection discountRewardProviders)
```


### Methods

#### DeleteDiscount (1 of 2)

```csharp
public void DeleteDiscount(Guid id)
```

---

#### DeleteDiscount (2 of 2)

```csharp
public void DeleteDiscount(Discount entity)
```


---

#### DiscountCodeExists

```csharp
public bool DiscountCodeExists(Guid storeId, string code)
```


---

#### DiscountExists

```csharp
public bool DiscountExists(Guid storeId, string alias)
```


---

#### GetActiveDiscounts

```csharp
public IEnumerable<DiscountReadOnly> GetActiveDiscounts(Guid storeId)
```


---

#### GetDiscount (1 of 2)

```csharp
public DiscountReadOnly GetDiscount(Guid id)
```

---

#### GetDiscount (2 of 2)

```csharp
public DiscountReadOnly GetDiscount(Guid storeId, string alias)
```


---

#### GetDiscountByCode

```csharp
public DiscountReadOnly GetDiscountByCode(Guid storeId, string code)
```


---

#### GetDiscountRewardProviderDefinitions

```csharp
public IEnumerable<DiscountRewardProviderDefinition> GetDiscountRewardProviderDefinitions()
```


---

#### GetDiscountRewardProviderScaffold

```csharp
public DiscountRewardProviderScaffold GetDiscountRewardProviderScaffold(string alias)
```


---

#### GetDiscountRuleProviderDefinitions

```csharp
public IEnumerable<DiscountRuleProviderDefinition> GetDiscountRuleProviderDefinitions()
```


---

#### GetDiscountRuleProviderScaffold

```csharp
public DiscountRuleProviderScaffold GetDiscountRuleProviderScaffold(string alias)
```


---

#### GetDiscounts (1 of 2)

```csharp
public IEnumerable<DiscountReadOnly> GetDiscounts(Guid storeId)
```

---

#### GetDiscounts (2 of 2)

```csharp
public IEnumerable<DiscountReadOnly> GetDiscounts(Guid[] ids)
```


---

#### SaveDiscount

```csharp
public void SaveDiscount(Discount entity)
```


---

#### SortDiscounts

```csharp
public void SortDiscounts(Guid[] sortedIds)
```


---

#### ValidateDiscountCode

```csharp
public bool ValidateDiscountCode(Guid storeId, string code)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->