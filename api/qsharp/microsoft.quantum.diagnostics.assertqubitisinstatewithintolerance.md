---
uid: Microsoft.Quantum.Diagnostics.AssertQubitIsInStateWithinTolerance
title: AssertQubitIsInStateWithinTolerance operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Diagnostics
qsharp.name: AssertQubitIsInStateWithinTolerance
qsharp.summary: >-
  Asserts that a qubit in the expected state.

  `expected` represents a complex vector, $\ket{\psi} = \begin{bmatrix}a & b\end{bmatrix}^{\mathrm{T}}$.
  The first element of the tuples representing each of $a$, $b$
  is the real part of the complex number, while the second one is the imaginary part.
  The last argument defines the tolerance with which assertion is made.
---

# AssertQubitIsInStateWithinTolerance operation

Namespace: [Microsoft.Quantum.Diagnostics](xref:Microsoft.Quantum.Diagnostics)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Asserts that a qubit in the expected state.

```qsharp
operation AssertQubitIsInStateWithinTolerance (expected : (Microsoft.Quantum.Math.Complex, Microsoft.Quantum.Math.Complex), register : Qubit, tolerance : Double) : Unit
```


## Input

### expected : ([Complex](xref:Microsoft.Quantum.Math.Complex),[Complex](xref:Microsoft.Quantum.Math.Complex))

Expected complex amplitudes for $\ket{0}$ and $\ket{1}$, respectively.


### register : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Qubit whose state is to be asserted. Note that this qubit is assumed to be separable


### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

Additive tolerance by which actual amplitudes are allowed to deviate from expected.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Example

```qsharp

## Remarks

The following Mathematica code can be used to verify expressions for mi, mx, my, mz: