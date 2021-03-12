---
uid: Microsoft.Quantum.Canon.ApplyIfElseRC
title: ApplyIfElseRC operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyIfElseRC
qsharp.summary: >-
  Applies one of two controllable operations, depending on the value of a
  classical result.
---

# ApplyIfElseRC operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Applies one of two controllable operations, depending on the value of a

```qsharp
operation ApplyIfElseRC<'T, 'U> (result : Result, (zeroOp : ('T => Unit is Ctl), zeroInput : 'T), (oneOp : ('U => Unit is Ctl), oneInput : 'U)) : Unit is Ctl
```


## Description

Given a result `result`, applies the operation `zeroOp` with `zeroInput` as

## Input

### result : __invalid<Result>__

The measurement result used to determine if `zeroOp` or `oneOp` is


### zeroOp : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Ctl

The controllable operation to be applied when `result == Zero`.


### zeroInput : 'T

The input to be provided to `zeroOp` when `result == Zero`.


### oneOp : 'U => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Ctl

The controllable operation to be applied when `result == One`.


### oneInput : 'U

The input to be provided to `oneOp` when `result == One`.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Type Parameters

### 'T

The input type of the operation `zeroOp` to be conditionally applied.
### 'U

The input type of the operation `oneOp` to be conditionally applied.

## See Also

- [Microsoft.Quantum.Canon.ApplyIfZero](xref:Microsoft.Quantum.Canon.ApplyIfZero)
- [Microsoft.Quantum.Canon.ApplyIfOne](xref:Microsoft.Quantum.Canon.ApplyIfOne)
- [Microsoft.Quantum.Canon.ApplyIfElseRC](xref:Microsoft.Quantum.Canon.ApplyIfElseRC)
- [Microsoft.Quantum.Canon.ApplyIfElseRA](xref:Microsoft.Quantum.Canon.ApplyIfElseRA)
- [Microsoft.Quantum.Canon.ApplyIfElseRCA](xref:Microsoft.Quantum.Canon.ApplyIfElseRCA)