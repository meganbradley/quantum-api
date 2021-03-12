---
uid: Microsoft.Quantum.Arrays.Interleaved
title: Interleaved function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Interleaved
qsharp.summary: Interleaves two arrays of (almost) same size.
---

# Interleaved function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Interleaves two arrays of (almost) same size.

```qsharp
function Interleaved<'T> (first : 'T[], second : 'T[]) : 'T[]
```


## Description

This function returns the interleaving of two arrays, starting

## Input

### first : 'T[]

The first array to be interleaved.


### second : 'T[]

The second array to be interleaved.



## Output : 'T[]

Interleaved array

## Type Parameters

### 'T

The type of each element of `first` and `second`.

## Example

```qsharp