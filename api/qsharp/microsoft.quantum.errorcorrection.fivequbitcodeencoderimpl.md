---
uid: Microsoft.Quantum.ErrorCorrection.FiveQubitCodeEncoderImpl
title: FiveQubitCodeEncoderImpl operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.ErrorCorrection
qsharp.name: FiveQubitCodeEncoderImpl
qsharp.summary: Private operation used to implement both the 5 qubit encoder and decoder.
---

# FiveQubitCodeEncoderImpl operation

Namespace: [Microsoft.Quantum.ErrorCorrection](xref:Microsoft.Quantum.ErrorCorrection)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Private operation used to implement both the 5 qubit encoder and decoder.

```qsharp
operation FiveQubitCodeEncoderImpl (data : Qubit[], scratch : Qubit[]) : Unit is Adj
```


## Input

### data : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

an array holding 1 qubit which is the input qubit.


### scratch : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

an array holding 4 qubits which add redundancy.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

The particular encoder chosen was taken from the paper V. Kliuchnikov and D. Maslov, "Optimization of Clifford Circuits,"