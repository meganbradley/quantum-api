---
uid: Microsoft.Quantum.Arithmetic.IncrementByInteger
title: IncrementByInteger operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: IncrementByInteger
qsharp.summary: >-
  Increments an unsigned quantum register by a classical integer,
  using phase rotations.
---

# IncrementByInteger operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Increments an unsigned quantum register by a classical integer,

```qsharp
operation IncrementByInteger (increment : Int, target : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit is Adj + Ctl
```


## Description

Suppose that `target` encodes an unsigned integer $x$ in a little-endian

## Input

### increment : [Int](xref:microsoft.quantum.lang-ref.int)

The integer by which the `target` is incremented by.


### target : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A quantum register encoding an unsigned integer using little-endian



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
