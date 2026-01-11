# Fraudchain-
FraudChain++ is an end-to-end Anti-Money Laundering (AML) framework built on Graph Neural Networks (GNNs) for detecting illicit activity in Bitcoin transaction networks. The project combines graph-based learning, explainable AI, and real-time streaming systems to enable regulator-aligned, production-ready fraud detection.
The system integrates **graph learning, explainable AI, and streaming systems** to detect illicit financial behavior in a regulator-aligned, production-ready manner.

---



## 📌 Table of Contents
- Motivation
- Problem Statement
- Key Features
- Modeling Approach
- Explainability & Compliance
- Streaming & Monitoring
- Evaluation Strategy
- Tech Stack
- Results & Outcomes
- Team & Contribution
- Future Work
- License

---

## 🎯 Motivation
Financial crime on blockchain networks is **highly relational, dynamic, and adaptive**.  
Traditional rule-based AML systems:
- Fail to capture hidden transaction relationships
- Break under evolving fraud strategies
- Offer limited interpretability for regulators

**FraudChain++** addresses these gaps by modeling blockchain data as **temporal graphs** and applying **Graph Neural Networks** with **explainable decision pipelines**.

---

## ❓ Problem Statement
Given a continuous stream of blockchain transactions:
- Identify potentially illicit wallets and transaction patterns
- Generalize to **future, unseen fraud behavior**
- Provide **transparent, auditable explanations**
- Support **real-time scoring and alerting**

---

## ✨ Key Features

### 🔗 Graph-Based Transaction Modeling
- Wallets as nodes, transactions as directed edges  
- Temporal graph construction preserving transaction order  

### 🧠 Advanced GNN Architectures
- **GraphSAGE** – scalable neighborhood aggregation  
- **GCN** – spectral graph convolution  
- **GAT** – attention-based message passing  

### 🕒 Temporal Generalization
- Time-based train/validation/test splits  
- Prevents data leakage common in AML datasets  
- Simulates real-world deployment scenarios  

### 📊 Explainability & Compliance
- Node-level and subgraph-level explanations  
- Regulator-friendly, auditable model decisions  

### ⚡ Real-Time Streaming System
- Online transaction scoring  
- Alert generation and risk threshold calibration  
- Concept drift monitoring for evolving fraud patterns  


## 🧪 Modeling Approach
- Bitcoin transactions modeled as temporal graphs  
- Node and edge feature engineering  
- Multiple GNN architectures evaluated under identical temporal constraints  
- Model selection based on **generalization, robustness, and stability**  

---

## 🔍 Explainability & Compliance
FraudChain++ integrates explainable AI techniques to ensure **trust, transparency, and regulatory alignment**:

- **GNNExplainer**
  - Identifies influential nodes, edges, and subgraphs
  - Produces local explanations per prediction

- **GraphSHAP**
  - Shapley-value based attribution for graph components
  - Quantifies structural and feature-level contributions

These explanations enable auditors and investigators to trace **why a transaction or wallet was flagged**.

---

## 📡 Streaming & Monitoring
The online inference system supports:
- Real-time transaction ingestion
- Continuous risk scoring
- Alert prioritization
- Concept drift detection to identify performance degradation

This allows AML enforcement to move from **batch analysis** to **continuous monitoring**.

---

## 📈 Evaluation Strategy
- Time-aware evaluation aligned with production deployment  
- Metrics focused on:
  - Precision under severe class imbalance
  - False-positive minimization
  - Stability across temporal windows  

---

## 🛠 Tech Stack

**Machine Learning & Graphs**
- PyTorch
- PyTorch Geometric
- GraphSAGE, GCN, GAT
- GNNExplainer, GraphSHAP

**Streaming & Systems**
- Real-time inference pipeline
- Alerting and monitoring services

**Domain**
- Blockchain analytics
- Anti-Money Laundering (AML)
- Financial crime detection



---

## 🏆 Results & Outcomes
- Robust detection of illicit transaction subgraphs  
- Strong generalization to future transaction windows  
- Transparent, compliance-ready predictions  
- Scalable architecture suitable for real-time AML deployment  

---

## 👥 Team & Contribution
**Role:** Project Lead  
**Location:** Pune, India  
**Duration:** Jul 2025 – Dec 2025  

- Led a 4-member team  
- Designed the GNN-based AML framework  
- Built explainability and compliance pipelines  
- Architected real-time scoring, alerting, and drift monitoring  

---

## 🔮 Future Work
- Multi-chain AML (Ethereum, Layer-2s)
- Cross-graph fraud ring detection
- Active learning with investigator feedback
- Integration with regulatory reporting systems

---

## 📜 License
This project is released under the **MIT License**.
