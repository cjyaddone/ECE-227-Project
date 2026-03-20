# 📊 Network Analysis and Visualization

## 🔍 Overview

This project analyzes real-world networks across three domains: **scientific collaboration, social interaction, and organizational communication**. We study structural properties such as centrality, community structure, degree distributions, and shortest-path behavior, and compare them against classical and advanced synthetic graph models.

The goal is to understand how different network generation mechanisms shape observable graph properties and how various metrics reveal different notions of node importance.

---

## 👥 Team Members

* **Zihao Yang**
  Community detection, implementation, visualization, report writing

* **Jiayi Chen**
  Dataset preparation, centrality analysis, report writing

* **Junyi Wu**
  Community detection methods, subgraph sampling comparison

* **Qinpei Luo**
  Synthetic model comparison and analysis, report writing

* **Matthew Alegrado**
  Degree distribution analysis and model fitting, report writing

---

## ⚙️ Key Steps

### 1. Data Acquisition

* Collaboration network (Erdős + CA-GrQc)
* Facebook ego network
* Enron email network

### 2. Preprocessing

* Graph construction
* Subgraph sampling (random, random walk, snowball)
* Focus on giant component when needed

### 3. Centrality Analysis

* Degree, Betweenness, Closeness, Eigenvector
* Compare overlap of top 10% nodes
* Interpret different notions of importance

### 4. Community Detection

* Louvain
* Leiden (Modularity + CPM)
* Spectral Clustering
* SBM (GMM-based)

### 5. Degree Distribution Modeling

* Power Law
* Exponential
* Lognormal
* Truncated Power Law

### 6. Network Metrics

* Diameter
* Average shortest path
* Clustering coefficient
* Assortativity
* Rich-club effect

### 7. Synthetic Model Comparison

* ER, WS, BA
* SBM, LFR, Forest Fire
* Evaluate realism vs empirical networks

---

## 🌿 Branch Structure & Work Distribution

### 🔹 `main`

* Final report

### 🔹 `zihao-community`

* Community detection implementations

### 🔹 `jiayi-centrality`

* Centrality analysis
* Overlap metrics

### 🔹 `qinpei_synthetic_model_comparison`

* Synthetic graph generation 
* Model fitting and comparison

### 🔹 `matthew-degree-distribution`

* Degree distribution fitting
* Power law / lognormal / exponential analysis

---

## 📌 Key Insights

* Centrality measures capture different roles (hubs vs brokers)
* Collaboration networks show strong overlap of importance metrics
* Facebook exhibits strong community clustering
* Enron reflects organizational communication structure
* No single synthetic model fully captures real-world networks
* Forest Fire and LFR provide the closest approximations

---
