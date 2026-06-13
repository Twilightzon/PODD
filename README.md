# PODD: Pareto-Optimized Dual-Teacher Distillation for Fair Graph Learning under Distribution Shifts

This is the code for the paper "PODD: Pareto-Optimized Dual-Teacher Distillation for Fair Graph Learning under Distribution Shifts", which has been accepted at ECMLPKDD 2026. We are systematically organizing the relevant code for this work.


## 🛠️ Dependencies

* python>=3.7
* torch==2.0.1
* torch-geometric==2.3.1
* torch-scatter==2.1.1
* numpy==1.24.4
* scikit-learn==1.3.0


🧩 Plug-and-Play Framework PODD is designed as a model-agnostic, plug-and-play framework that can be seamlessly integrated with existing Fair GNNs (e.g., FairSIN, FairGB, NIFTY) or standard GNN backbones (e.g., GCN, GIN). It functions as a wrapper that enhances the base model's resistance against distribution shifts without requiring modifications to the model's internal architecture. When adapting PODD to other models, be sure to save the trained model first before entering our training phase.




## Running

The ```run.sh``` includes details to reproduce experimental results in the paper:

```
bash run.sh
```





















