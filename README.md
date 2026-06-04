# community_detection
Implementation and comparative study of community detection algorithms 
in complex networks.

This project implements and evaluates:
- Iterative Local Search (baseline/comparative method)
- K-Rank (state-of-the-art comparison)
- **MVEGC** (Multi-View Embedding Graph Compression) — our proposed framework

MVEGC combines multi-view node embeddings (Jaccard, Adamic-Adar, 
normalized adjacency), graph compression, spectral 
clustering, and modified label propagation.

## Team
Collaborative work by:
- Meryem Batoul KARIM
- Menatallahfadoua SLAMA
- Hiba GUERROUACHE
- Sabrina CHOUIKRAT
- Maria DJEBLAHI
- Meriem DJELLAL

## Contents
- `notebooks/` — Algorithm implementations
  - Baseline methods (Iterative Local Search, K-Rank)
  - MVEGC: Our proposed framework
  - Hyperparameter tuning and comparisons to state-of-the-art
- `reports/` — Full research report with methodology and results

