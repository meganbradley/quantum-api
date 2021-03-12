---
uid: Microsoft.Quantum.Arithmetic.MultiplyAndAddByModularInteger
title: MultiplyAndAddByModularInteger operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: MultiplyAndAddByModularInteger
qsharp.summary: Performs a modular multiply-and-add by integer constants on a qubit register.
---

# MultiplyAndAddByModularInteger operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Performs a modular multiply-and-add by integer constants on a qubit register.

```qsharp
operation MultiplyAndAddByModularInteger (constMultiplier : Int, modulus : Int, multiplier : Microsoft.Quantum.Arithmetic.LittleEndian, summand : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit is Adj + Ctl
```


## Description

Implements the map

## Input

### constMultiplier : [Int](xref:microsoft.quantum.lang-ref.int)

An integer $a$ to be added to each basis state label.


### modulus : [Int](xref:microsoft.quantum.lang-ref.int)

The modulus $N$ which addition and multiplication is taken with respect to.


### multiplier : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A quantum register representing an unsigned integer whose value is to


### summand : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A quantum register representing an unsigned integer to use as the target



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

- For the circuit diagram and explanation see Figure 6 on [Page 7

## See Also

- [Microsoft.Quantum.Arithmetic.MultiplyAndAddPhaseByModularInteger](xref:Microsoft.Quantum.Arithmetic.MultiplyAndAddPhaseByModularInteger)