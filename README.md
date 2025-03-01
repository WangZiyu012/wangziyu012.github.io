# Welcome!

Hi I'm Ziyu Wang (王 梓瑜), currently a master student @University of Tokyo, School of Engineering. 

My current main research interest is foundation models in LLM, primarily focusing on improving the capabilities of Mamba in generative AI and sequence prediction.

# Education

## University of Tokyo (Japan)  
**Master of Engineering** (10/2023 – 9/2025)  

- **Affiliation:** School of Engineering, Dept. of System Innovation  
- **Research Field:** Machine Learning  

## Xi'an Jiaotong University (China)  
**Bachelor of Science** (10/2019 – 7/2023)  

- **Affiliation:** School of Mathematics and Statistics, Honor Science Program of Math  
- **Major:** Applied Math and Statistics  


# Experience

## 5/2022 – 7/2022  
Working with [**Dr. Jiangjun Peng**](https://scholar.google.co.jp/citations?user=3crYjMoAAAAJ) on Computer Vision.  

## 7/2022 – 1/2023  
Working with [**Dr. Qian Zhao**](https://scholar.google.co.jp/citations?hl=en&user=vM6yGTEAAAAJ) on Computer Vision.  

## 1/2023 – 7/2023  
Working with [**Prof. Deyu Meng**](https://scholar.google.co.jp/citations?hl=en&user=an6w-64AAAAJ) on LLM/Generative AI and Computer Vision.  

## 10/2023 – now  
Working with [**Prof. Watanabe Masataka**](https://x.com/watanabemasata?) on enhancing the Mamba model (foundational LLM model) and Graph Machine Learning.  

# LLM/Generative AI Projects

## [**Github Link1**](https://github.com/WangZiyu012/ORMamba)  
### **Project1: Order-Robust Mamba for Time Series Forecasting**  
**Key Words:** Mamba; Time Series Prediction; Foundational LLM model.  

We present ORMamba, an approach that eliminates channel-order bias in Mamba-based time series forecasting.  
By reversing channel orders, removing 1D convolutions, and introducing channel correlation modeling, it enhances channel-dependency learning.  
Experiments show its effectiveness in both standard and transfer learning scenarios.  

---

## [**Github Link2**](https://github.com/WangZiyu012/STUM)  
### **Project2: Mitigating RNN State Explosion for Long-Context Modeling**  
**Key Words:** Long-context; Foundational LLM Model.  

We identify state explosion in Mamba-2 RNNs for extended contexts, linking it to overparametrized states and overfitting.  
Empirical studies reveal linear thresholds for training length and exponential scaling of feasible context length.  
Our model shows near-perfect retrieval at very short tokens, demonstrating RNNs’ long-context potential.  

---

## [**Github Link3**](https://github.com/WangZiyu012/KAD)  
### **Project3: Unified Kolmogorov–Arnold and State-Space Framework for Robust Time Series Anomaly Detection**  
**Key Words:** Mamba, KAN, Anomaly Detection.  

We use Kolmogorov–Arnold enforcement for rapid physical consistency checks, attention for global insights, and MAMBA for local variation detection and distribution shift handling.  
The model's time-series-specific reconstructor efficiently isolates features, ensuring robust performance.  
Experiments show its superior anomaly detection across diverse multivariate datasets.  

# Computer Vision Projects

## [**Github Link4**](https://github.com/WangZiyu012/V2M)  
### **Project4: 2D State-Space Mamba for Efficient Image Representation**  
**Key Words:** Mamba, Representation Learning.  

We propose V2M, which extends Mamba’s state-space approach to 2D and preserves local structures while enabling parallel hardware efficiency.  
By processing tokens across both dimensions, it captures spatial locality while maintaining Mamba’s scalability.  
Experiments on ImageNet and downstream tasks validate V2M’s superior performance over existing visual backbones.  

---

## [**Github Link5**](https://github.com/WangZiyu012/SSMamba)  
### **Project5: Spectral-Spatial Mamba: Isometry-Invariant Graph Laplacian Traversal for Robust Point Cloud Analysis**  
**Key Words:** Mamba, Masked Autoencoders, 3D Point Clouds.  

We propose Spectral-Spatial Mamba, which employs a graph Laplacian-based traversal that preserves isometric invariance for point cloud data.  
Using a recursive partitioning strategy for segmentation and refined token restoration in the Masked Autoencoder, it outperforms baselines in classification, segmentation, and few-shot tasks, advancing both supervised and self-supervised learning.  

---

## [**Github Link6**](https://github.com/WangZiyu012/LLRM)  
### **Project6: Efficient Large-Scale 3D Reconstruction with Gaussian Splats from Long Image Sequences**  
**Key Words:** 3D Reconstruction.  

Our model generalizes 3D Gaussian splat reconstruction from extensive image sequences.  
Combining Mamba2 and classic Transformer blocks, it processes 32 high-resolution views in only 1.3 seconds.  
Token merging and Gaussian pruning ensure quality and efficiency.  
On large-scale benchmarks, it achieves near optimization-based results while being two orders of magnitude faster.  


# Graph Machine Learning Projects

## [**Github Link7**](https://github.com/WangZiyu012/CSSGT)  
### **Project7: Enhancing Graph Transformers with SNNs and Mutual Information**  
**Key Words:** Graph Neural Networks, Spiking Neural Networks, Transformers, Mutual Information  

We develop a model that merges Transformers’ power with Spiking Neural Network efficiency through MIGS for graph splitting and SDGA for spike-driven attention.  
Under a contrastive learning framework, it converges within two epochs and surpasses state-of-the-art models, maintaining low computational overhead across various datasets.  

**Remark:** Accepted by the ACM WWW conference (Ranked 1st in the field of Databases & Information Systems by [**Google Scholar**](https://scholar.google.com/citations?view_op=top_venues&hl=en&vq=eng_databasesinformationsystems)). To appear after May 2025.  

---

## [**Github Link8**](https://github.com/WangZiyu012/ACR)  
### **Project8: ACR: A General Framework for Graph-Level Learning**  
**Key Words:** Graph Neural Networks, Representation Learning.  

We propose an attention-based adaptive centrality readout function that extends beyond node-degree information and outperforms existing readout methods.  
It can also operate as a standalone framework without relying on GNNs. This flexibility empowers effective graph-level learning, capturing global properties and achieving state-of-the-art performance across diverse tasks.  

---

## [**Github Link9**](https://github.com/WangZiyu012/DyMamba)  
### **Project9: DyMamba: A State-Space Approach for Efficient Long-Term Modeling in Continuous-Time Dynamic Graphs**  
**Key Words:** Dynamic Graph, Mamba.  

We propose DyMamba, which encodes extended node interactions and temporal patterns via a two-stage state-space model.  
A node-level SSM captures historical sequences, while a time-level SSM highlights critical temporal information, enabling robust long-range dependency handling.  
Experiments confirm DyMamba’s superior accuracy and efficiency for large-scale continuous-time dynamic graphs.  

---

# Others  

## **Awards:**  
Program Chair and Reviewer of the ACM WWW conference (Ranked 1st in the field of Databases & Information Systems by [**Google Scholar**](https://scholar.google.com/citations?view_op=top_venues&hl=en&vq=eng_databasesinformationsystems)).  

## **Languages:**  
Chinese (Native), English (TOEIC 920 points), Japanese (JLPT N1).  

## **Programming Languages:**  
Python, Matlab, C++, C, Java, C#.  

## **Technologies:**  
AutoDL, AWS, PyTorch, PyG, HuggingFace, Pandas, NumPy.  

