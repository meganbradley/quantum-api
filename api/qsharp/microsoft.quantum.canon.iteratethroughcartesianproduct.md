---
uid: Microsoft.Quantum.Canon.IterateThroughCartesianProduct
title: IterateThroughCartesianProduct operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: IterateThroughCartesianProduct
qsharp.summary: >-
  Applies an operation for each index in the Cartesian product of several
  ranges.
---

# IterateThroughCartesianProduct operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Applies an operation for each index in the Cartesian product of several

```qsharp
operation IterateThroughCartesianProduct (bounds : Int[], op : (Int[] => Unit)) : Unit
```


## Description

Iteratively applies an operation for each element of the Cartesian product

## Input

### bounds : [Int](xref:microsoft.quantum.lang-ref.int)[]

An array specifying the ranges to be iterated over, with each range


### op : [Int](xref:microsoft.quantum.lang-ref.int)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) 

An operation to be called for each element of the given Cartesian product.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Example

Given an operation `op`, the following two snippets are equivalent:

## See Also

- [Microsoft.Quantum.Canon.IterateThroughCartesianPower](xref:Microsoft.Quantum.Canon.IterateThroughCartesianPower)