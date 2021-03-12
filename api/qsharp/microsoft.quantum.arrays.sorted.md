---
uid: Microsoft.Quantum.Arrays.Sorted
title: Sorted function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Sorted
qsharp.summary: >-
  Given an array, returns the elements of that array sorted by a given
  comparison function.
---

# Sorted function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Given an array, returns the elements of that array sorted by a given

```qsharp
function Sorted<'T> (comparison : (('T, 'T) -> Bool), array : 'T[]) : 'T[]
```


## Input

### comparison : ('T,'T) -> [Bool](xref:microsoft.quantum.lang-ref.bool)

A function that compares two elements such that `a` is considered to


### array : 'T[]

The array to be sorted.



## Output : 'T[]



## Type Parameters

### 'T

The type of each element of `array`.

## Example

The following snippet sorts an array of integers to occur in ascending

## Remarks

The function `comparison` is assumed to be transitive, such that