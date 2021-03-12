---
uid: Microsoft.Quantum.Random.CategoricalDistribution
title: CategoricalDistribution function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Random
qsharp.name: CategoricalDistribution
qsharp.summary: >-
  Returns a discrete categorical distribution, in which the probability
  for each of a finite list of given outcomes is explicitly specified.
---

# CategoricalDistribution function

Namespace: [Microsoft.Quantum.Random](xref:Microsoft.Quantum.Random)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Returns a discrete categorical distribution, in which the probability

```qsharp
function CategoricalDistribution (probs : Double[]) : Microsoft.Quantum.Random.DiscreteDistribution
```


## Input

### probs : [Double](xref:microsoft.quantum.lang-ref.double)[]

The probabilities for each outcome from the categorical distribution.



## Output : [DiscreteDistribution](xref:Microsoft.Quantum.Random.DiscreteDistribution)

The index `i` with probability `probs[i] / sum`, where `sum` is the sum

## Example

The following Q# code will display 0 with probability 30% and 1 with