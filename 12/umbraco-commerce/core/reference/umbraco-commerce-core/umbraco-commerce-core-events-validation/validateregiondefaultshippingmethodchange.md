---
title: ValidateRegionDefaultShippingMethodChange
description: API reference for ValidateRegionDefaultShippingMethodChange in Umbraco Commerce
---
## ValidateRegionDefaultShippingMethodChange

```csharp
public class ValidateRegionDefaultShippingMethodChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateRegionDefaultShippingMethodChange

```csharp
public ValidateRegionDefaultShippingMethodChange(RegionReadOnly region, 
    ChangingValue<Guid?> shippingMethodId)
```


### Properties

#### Region

```csharp
public RegionReadOnly Region { get; }
```


---

#### ShippingMethodId

```csharp
public ChangingValue<Guid?> ShippingMethodId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->