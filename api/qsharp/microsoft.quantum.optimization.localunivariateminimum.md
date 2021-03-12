---
uid: Microsoft.Quantum.Optimization.LocalUnivariateMinimum
title: LocalUnivariateMinimum function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Optimization
qsharp.name: LocalUnivariateMinimum
qsharp.summary: >-
  Returns some local minimum for a univariate function over a bounded interval,
  using a golden interval search.
---

# LocalUnivariateMinimum function

Namespace: [Microsoft.Quantum.Optimization](xref:Microsoft.Quantum.Optimization)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns some local minimum for a univariate function over a bounded interval,

```qsharp
function LocalUnivariateMinimum (fn : (Double -> Double), bounds : (Double, Double), tolerance : Double) : Microsoft.Quantum.Optimization.UnivariateOptimizationResult
```


## Input

### fn : [Double](xref:microsoft.quantum.lang-ref.double) -> [Double](xref:microsoft.quantum.lang-ref.double)

The univariate function to be minimized.


### bounds : ([Double](xref:microsoft.quantum.lang-ref.double),[Double](xref:microsoft.quantum.lang-ref.double))

The interval in which the local minimum is to be found.


### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

The accuracy in the function input to be tolerated.



## Output : [UnivariateOptimizationResult](xref:Microsoft.Quantum.Optimization.UnivariateOptimizationResult)

A local optima of the given function, located within the given bounds.