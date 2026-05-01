# PEPITA: A Forward Learning Algorithm

## Motivation

The backpropagation algorithm, despite its success in training artificial neural networks,
is fundamentally at odds with the way biological neural systems operate. Real neurons
learn through local updates and feedback driven by temporal dynamics, not global error
signals or synchronized weight updates. Forward learning algorithms aim to mimic these
biologically inspired processes, offering a more natural and adaptive approach to training
artificial networks. One such algorithm is discussed in detail in this report.

## Introduction

The PEPITA algorithm (Present the Error to Perturb the Input To modulate the Activity) is a forward-learning approach that uses top-down feedback connections, aiming
to address the limitations of backpropagation in biological plausibility. Instead,
PEPITA sends feedback signals from later layers (higher up in the hierarchy) back to
earlier layers, helping them make corrections during learning.

- Please refer to the ECEN_689_GRP7_REPORT.pdf file in the repo for more information on results and analysis. Thank you for your time. 




