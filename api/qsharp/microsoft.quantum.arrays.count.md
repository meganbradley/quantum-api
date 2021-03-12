---
uid: Microsoft.Quantum.Arrays.Count
title: Count function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Count
qsharp.summary: >-
  Given an array and a predicate that is defined
  for the elements of the array, returns the number of elements
  an array that consists of those elements that satisfy the predicate.
---

# Count function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Given an array and a predicate that is defined

```qsharp
function Count<'T> (predicate : ('T -> Bool), array : 'T[]) : Int
```


## Input

### predicate : 'T -> [Bool](xref:microsoft.quantum.lang-ref.bool)

A function from `'T` to Boolean that is used to filter elements.


### array : 'T[]

An array of elements over `'T`.



## Output : [Int](xref:microsoft.quantum.lang-ref.int)

The number of elements in `array` that satisfy the predicate.

## Type Parameters

### 'T

The type of `array` elements.

## Example

The following code demonstrates the "Count" function.

## Remarks

The function is defined for generic types, i.e., whenever we have