---
date: 2023-02-28
pub-on: 2020-09-11
project: joe-studts-1
oneline-summary: Usign IPM to help scaling from lab-to-manufacture during IEX. 
tags: paper
---
[[|PDF]]

## Terminology
- SDM: Scale down models
- HMW: High molecular weight species, which usually considered as impurities.
- SMA: Steric mass action model for IEX


## Problems
When scaling up from scale down models (SDM) to manufacturing, single parameter (column inner diameter) affects multiple downstream processes. 

Using SMA modeling (One model to describe both scales without doing expansive recalibration) to simulate the scaling can helps to improve traditional SDM workflow (SDM -> Scale up -> Recalibrate). 

## Methods
IPM on SDM, change inner diameter parameter in the model to manufacturing scale. Examine how well IPM works by comparing differences between predicted and observed CQAs and KPIs. 

Step 1: Get acceptance criteria based on historical runs +/- 3SD in large-scale
Step 2: 

## Results

![[Pasted image 20230228104142.png]]

## After-thoughts
- The scaling issue is somewhat justified by this study
- If IPM can inform small-to-large, then it could do the same in large-to-small. In the scenario where more information is needed (some problem occur in the manufacturing process with some unknown cause, experimentation on large-scale is costly), diagnosis in small scale with mechanistic model could help??