---
uid: Microsoft.Quantum.Canon.AndLadder
title: AndLadder operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: AndLadder
qsharp.summary: Performs a controlled "AND ladder" on a register of target qubits.
---

# AndLadder operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Performs a controlled "AND ladder" on a register of target qubits.

```qsharp
operation AndLadder (ccnot : Microsoft.Quantum.Canon.CCNOTop, controls : Qubit[], targets : Qubit[]) : Unit is Adj
```


## Description

This operation applies a transformation described by the following

## Input

### ccnot : [CCNOTop](xref:Microsoft.Quantum.Canon.CCNOTop)

The CCNOT gate to use for the construction.


### controls : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A register of qubits to be used as controls for the and ladder.


### targets : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

The length of `targets` must be at least 1 and equal to the length



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

- Used as a part of <xref:microsoft.quantum.canon.applymulticontrolledc>

## References

- [ *Michael A. Nielsen , Isaac L. Chuang*,