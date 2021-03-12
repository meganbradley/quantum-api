---
uid: Microsoft.Quantum.Canon.BoundCA
title: BoundCA function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: BoundCA
qsharp.summary: >-
  Given an array of operations acting on a single input,
  produces a new operation that
  performs each given operation in sequence.
  The modifier `CA` indicates that all operations in the array are adjointable
  and controllable.
---

# BoundCA function

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Given an array of operations acting on a single input,

```qsharp
function BoundCA<'T> (operations : ('T => Unit is Adj + Ctl)[]) : ('T => Unit is Adj + Ctl)
```


## Input

### operations : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Adj + Ctl[]

A sequence of operations to be performed on a given input.



## Output : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Adj + Ctl

A new operation that performs each given operation in sequence

## Type Parameters

### 'T

The target on which each of the operations in the array act.

## Example

The following are equivalent:

## See Also

- [Microsoft.Quantum.Canon.Bound](xref:Microsoft.Quantum.Canon.Bound)