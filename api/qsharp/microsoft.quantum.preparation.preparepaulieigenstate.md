---
uid: Microsoft.Quantum.Preparation.PreparePauliEigenstate
title: PreparePauliEigenstate operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PreparePauliEigenstate
qsharp.summary: >-
  Prepares a qubit in the positive eigenstate of a given Pauli operator.
  If the identity operator is given, then the qubit is prepared in the maximally
  mixed state.
---

# PreparePauliEigenstate operation

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Prepares a qubit in the positive eigenstate of a given Pauli operator.

```qsharp
operation PreparePauliEigenstate (basis : Pauli, qubit : Qubit) : Unit
```


## Description

If the qubit was initially in the $\ket{0}$ state, this operation prepares the

## Input

### basis : [Pauli](xref:microsoft.quantum.lang-ref.pauli)

A Pauli operator $P$.


### qubit : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

A qubit to be prepared.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Example

To prepare a qubit in the $\ket{+}$ state: