---
uid: Microsoft.Quantum.Math.ExpModL
title: ExpModL function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: ExpModL
qsharp.summary: >-
  Returns an integer raised to a given power, with respect to a given
  modulus.
---

# ExpModL function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns an integer raised to a given power, with respect to a given

```qsharp
function ExpModL (expBase : BigInt, power : BigInt, modulus : BigInt) : BigInt
```


## Description

Let us denote expBase by $x$, power by $p$ and modulus by $N$.

## Input

### expBase : [BigInt](xref:microsoft.quantum.lang-ref.bigint)




### power : [BigInt](xref:microsoft.quantum.lang-ref.bigint)




### modulus : [BigInt](xref:microsoft.quantum.lang-ref.bigint)





## Output : [BigInt](xref:microsoft.quantum.lang-ref.bigint)



## Remarks

Takes time proportional to the number of bits in `power`, not the `power` itself.