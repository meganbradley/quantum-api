---
uid: Microsoft.Quantum.Random.DrawCategorical
title: DrawCategorical operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Random
qsharp.name: DrawCategorical
qsharp.summary: >-
  Draws a random sample from a categorical distribution specified by a
  list of probablities.
---

# DrawCategorical operation

Namespace: [Microsoft.Quantum.Random](xref:Microsoft.Quantum.Random)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Draws a random sample from a categorical distribution specified by a

```qsharp
operation DrawCategorical (probs : Double[]) : Int
```


## Description

The probability of selecting a specific index is proportional to the value

## Input

### probs : [Double](xref:microsoft.quantum.lang-ref.double)[]

An array of floating-point numbers proportional to the probability of



## Output : [Int](xref:microsoft.quantum.lang-ref.int)

An integer $i$ with probability $\Pr(i) = p_i / \sum_i p_i$, where $p_i$

## See Also

- [Microsoft.Quantum.Random.CategoricalDistribution](xref:Microsoft.Quantum.Random.CategoricalDistribution)