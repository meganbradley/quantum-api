---
uid: Microsoft.Quantum.Intrinsic.M
title: M operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Intrinsic
qsharp.name: M
qsharp.summary: >-
  Performs a measurement of a single qubit in the
  Pauli $Z$ basis.
---

# M operation

Namespace: [Microsoft.Quantum.Intrinsic](xref:Microsoft.Quantum.Intrinsic)

Package: [Microsoft.Quantum.QSharp.Core](https://nuget.org/packages/Microsoft.Quantum.QSharp.Core)


Performs a measurement of a single qubit in the

```qsharp
operation M (qubit : Qubit) : Result
```


## Description

The output result is given by

## Input

### qubit : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Qubit to be measured.



## Output : __invalid<Result>__

`Zero` if the $+1$ eigenvalue is observed, and `One` if

## Remarks

Equivalent to: