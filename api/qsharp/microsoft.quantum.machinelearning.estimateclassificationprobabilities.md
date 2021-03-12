---
uid: Microsoft.Quantum.MachineLearning.EstimateClassificationProbabilities
title: EstimateClassificationProbabilities operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.MachineLearning
qsharp.name: EstimateClassificationProbabilities
qsharp.summary: >-
  Given a set of samples and a sequential classifier, estimates the
  classification probability for those samples by repeatedly measuring
  the output of the classifier on each sample.
---

# EstimateClassificationProbabilities operation

Namespace: [Microsoft.Quantum.MachineLearning](xref:Microsoft.Quantum.MachineLearning)

Package: [Microsoft.Quantum.MachineLearning](https://nuget.org/packages/Microsoft.Quantum.MachineLearning)


Given a set of samples and a sequential classifier, estimates the

```qsharp
operation EstimateClassificationProbabilities (tolerance : Double, model : Microsoft.Quantum.MachineLearning.SequentialModel, samples : Double[][], nMeasurements : Int) : Double[]
```


## Input

### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

The tolerance to allow in encoding the sample into a state preparation


### model : [SequentialModel](xref:Microsoft.Quantum.MachineLearning.SequentialModel)

The sequential model to be used to estimate the classification


### samples : [Double](xref:microsoft.quantum.lang-ref.double)[][]

An array of feature vectors for each sample to be classified.


### nMeasurements : [Int](xref:microsoft.quantum.lang-ref.int)

The number of measurements to use in estimating the classification



## Output : [Double](xref:microsoft.quantum.lang-ref.double)[]

An array of estimates of the classification probability for each given