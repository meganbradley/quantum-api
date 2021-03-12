---
uid: Microsoft.Quantum.MachineLearning.NMisclassifications
title: NMisclassifications function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.MachineLearning
qsharp.name: NMisclassifications
qsharp.summary: >-
  Given a set of inferred labels and a set of correct labels, returns
  the number of indices at which each set of labels differ.
---

# NMisclassifications function

Namespace: [Microsoft.Quantum.MachineLearning](xref:Microsoft.Quantum.MachineLearning)

Package: [Microsoft.Quantum.MachineLearning](https://nuget.org/packages/Microsoft.Quantum.MachineLearning)


Given a set of inferred labels and a set of correct labels, returns

```qsharp
function NMisclassifications (proposed : Int[], actual : Int[]) : Int
```


## Input

### proposed : [Int](xref:microsoft.quantum.lang-ref.int)[]




### actual : [Int](xref:microsoft.quantum.lang-ref.int)[]





## Output : [Int](xref:microsoft.quantum.lang-ref.int)

The number of indices `idx` such that

## Example

```qsharp