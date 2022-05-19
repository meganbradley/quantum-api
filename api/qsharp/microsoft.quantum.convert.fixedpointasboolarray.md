---
uid: Microsoft.Quantum.Convert.FixedPointAsBoolArray
title: FixedPointAsBoolArray function
ms.date: 5/19/2022 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Convert
qsharp.name: FixedPointAsBoolArray
qsharp.summary: Computes fixed-point approximation for a double and returns it as `Bool` array.
---

# FixedPointAsBoolArray function

Namespace: [Microsoft.Quantum.Convert](xref:Microsoft.Quantum.Convert)

Package: [Microsoft.Quantum.Numerics](https://nuget.org/packages/Microsoft.Quantum.Numerics)


Computes fixed-point approximation for a double and returns it as `Bool` array.

```qsharp
function FixedPointAsBoolArray (integerBits : Int, fractionalBits : Int, value : Double) : Bool[]
```


## Input

### integerBits : [Int](xref:microsoft.quantum.qsharp.valueliterals#int-literals)

Assumed number of integer bits (including the sign bit).


### fractionalBits : [Int](xref:microsoft.quantum.qsharp.valueliterals#int-literals)

Assumed number of fractional bits.


### value : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

Value to be approximated.



## Output : [Bool](xref:microsoft.quantum.qsharp.valueliterals#bool-literals)[]



## Example

Note that the first element in the Boolean array is the least-significant bit.