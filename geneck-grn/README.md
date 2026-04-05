# 🧬 Gene Regulatory Network (GRN) using GeNeCK

## 📌 Overview
This project focuses on constructing and analyzing a Gene Regulatory Network (GRN) using synthetic gene expression data. The network was inferred using the GLASSO (Graphical Lasso) algorithm in GeNeCK and further analyzed in Cytoscape.

---

## 🎯 Objective
- To generate gene expression data  
- To reconstruct a GRN using computational methods  
- To analyze network topology and identify key regulatory genes  

---

## 🛠 Tools & Technologies
- GeNeCK (GLASSO algorithm)  
- Cytoscape  
- Python (NumPy, Pandas)  

---

## 📊 Dataset
- Type: Synthetic gene expression data  
- Samples: 80  
- Genes: 40  

---

## 🔍 Methodology

### 1. Data Generation
- Generated gene expression dataset using Python  
- Used normal distribution (NumPy)  
- Saved dataset as CSV  

### 2. GRN Construction (GLASSO)
- Uploaded dataset to GeNeCK  
- Applied GLASSO (Graphical Lasso) algorithm  
- Inferred gene regulatory network based on partial correlations  

### 3. Network Visualization
- Imported network into Cytoscape  
- Applied layout for visualization  

### 4. Network Analysis
- Identified hub genes based on node degree  
- Calculated network properties:
  - Average degree  
  - Clustering coefficient  
  - Path length  
- Performed module detection using MCODE  

---

## 📈 Results

### 🔢 Network Statistics
- Number of nodes: 40  
- Number of edges: 345  
- Average degree: 17.25  
- Clustering coefficient: 0.458  
- Characteristic path length: 1.559  
- Network density: 0.442  

### 📸 Network Visualization
![GRN Network](your-image-name.png)

### 🧩 Module Detection (MCODE)
![MCODE Clusters](mcode-clusters.png)

- MCODE identified multiple clusters within the network  
- Each cluster represents highly interconnected gene groups  
- Indicates modular organization and coordinated gene regulation  

---

## 🧠 Conclusion
The GRN constructed using the GLASSO algorithm revealed a highly connected and structured network. The presence of hub genes and MCODE-detected clusters highlights the modular nature of gene regulation and underlying biological patterns.

---

## 🚀 Skills Gained
- GRN reconstruction using GLASSO  
- Network topology analysis  
- Cytoscape visualization  
- Module detection using MCODE  
