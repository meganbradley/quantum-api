---
uid: Microsoft.Quantum.Arrays.Subarray
title: Subarray function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Subarray
qsharp.summary: >-
  Takes an array and a list of locations and
  produces a new array formed from the elements of the original
  array that match the given locations.
---

# Subarray function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Takes an array and a list of locations and

```qsharp
function Subarray<'T> (indices : Int[], array : 'T[]) : 'T[]
```


## Input

### indices : [Int](xref:microsoft.quantum.lang-ref.int)[]

A list of integers that is used to define the subarray.


### array : 'T[]

An array of elements over `'T`.



## Output : 'T[]

An array `out` of elements whose indices correspond to the subarray,

## Type Parameters

### 'T

The type of `array` elements.

## Remarks

The function is defined for generic types, i.e., whenever we have