---
uid: Microsoft.Quantum.Math.ContinuedFractionConvergentL
title: ContinuedFractionConvergentL function
ms.date: 02/21/2024 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: ContinuedFractionConvergentL
qsharp.summary: Finds the continued fraction convergent closest to `fraction`
with the denominator less or equal to `denominatorBound`
Using process similar to this: https://nrich.maths.org/1397
---

# ContinuedFractionConvergentL function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

```qsharp
function ContinuedFractionConvergentL(fraction : (BigInt, BigInt), denominatorBound : BigInt) : (BigInt, BigInt)
```

## Summary
Finds the continued fraction convergent closest to `fraction`
with the denominator less or equal to `denominatorBound`
Using process similar to this: https://nrich.maths.org/1397