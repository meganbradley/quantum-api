---
uid: Qdk.Std.Arrays.FlatMapped
title: FlatMapped function
ms.date: 11/01/2024
ms.topic: managed-reference
qsharp.kind: function
qsharp.package: __Std__
qsharp.namespace: Std.Arrays
qsharp.name: FlatMapped
qsharp.summary: "Given an array and a function that maps an array element to some output array, returns the concatenated output arrays for each array element."
---

# FlatMapped function

Fully qualified name: Std.Arrays.FlatMapped

```qsharp
function FlatMapped<'TInput, 'TOutput>(mapper : ('TInput -> 'TOutput[]), array : 'TInput[]) : 'TOutput[]
```

## Summary
Given an array and a function that maps an array element to some output
array, returns the concatenated output arrays for each array element.

## Type Parameters
### 'TInput
The type of `array` elements.
### 'TOutput
The `mapper` function returns arrays of this type.

## Input
### mapper
A function from `'TInput` to `'TOutput[]` that is used to map array elements.
### array
An array of elements.

## Output
An array of `'TOutput[]` which is the concatenation of all arrays generated by
the mapping function.

## Example
The following code creates an array with each element of the input array repeated twice.
```qsharp
let repeatedPairs = FlatMapped(x -> Repeated(x, 2), [1, 2, 3]);
// repeatedPairs is [1, 1, 2, 2, 3, 3].
```