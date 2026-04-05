# 🧬 Gene Regulatory Network (GRN) using GeNeCK

## 📌 Overview
This project focuses on constructing and analyzing a Gene Regulatory Network (GRN) using synthetic gene expression data. The network was inferred using GeNeCK and further analyzed in Cytoscape.

---

## 🎯 Objective
- To generate gene expression data  
- To reconstruct a GRN using computational methods  
- To analyze network topology and identify key regulatory genes  

---

## 🛠 Tools & Technologies
- GeNeCK  
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
- Saved data in CSV format  

### 2. GRN Construction
- Uploaded dataset to GeNeCK  
- Applied GRN reconstruction algorithm  
- Generated interaction network  

### 3. Network Visualization
- Imported network into Cytoscape  
- Applied layout for visualization  

### 4. Network Analysis
- Identified hub genes based on connectivity  
- Computed network statistics  
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
- Identified 5 clusters/modules in the network  
- Modules indicate groups of highly interconnected genes  
- Suggests functional grouping and regulatory patterns  

---

## 🧠 Conclusion
The GRN analysis revealed a highly connected network with significant clustering. The presence of hub genes and multiple modules indicates coordinated gene regulation and structured network organization.

---

## 🚀 Skills Gained
- Gene regulatory network construction  
- Network topology analysis  
- Cytoscape visualization  
- Module detection using MCODE  
