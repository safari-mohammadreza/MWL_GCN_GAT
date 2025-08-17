# EEG-GCN-GAT — Mental Workload Classification from EEG Connectivity

**Turn EEG into graphs. Let the network learn which connections matter.**  
This repo contains the code and tools to classify mental workload (low vs. high) by converting directed effective connectivity (dDTF) into graphs and training a hybrid **GCN → GAT → GCN** model.

---

## Why this is interesting
- Uses **directed** effective connectivity (dDTF) to preserve information flow between EEG channels.  
- Hybrid architecture with **graph attention** + **dual pooling** (mean + max) for robust representations.  
- Includes **Optuna** hyperparameter search, a systematic **ablation study**, and **GNNExplainer**-based interpretability.  
- Strong reported performance on STEW (best config): **Accuracy 90.10% · Precision 87.47% · Recall 93.60% · F1 90.43%**.

---
