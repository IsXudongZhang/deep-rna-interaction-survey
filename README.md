# RNA Interaction Literature Survey

This repository serves as a literature survey and reference library for **RNA-related molecular interactions**, accompanying an ongoing review of methods and studies on RNA interactions with **proteins, small molecules, and other biomolecular modalities**. It is designed to organize representative papers by topic, covering **RNA representation methods, structural modeling, benchmark datasets, evaluation strategies, and interaction prediction tasks**, and to provide a structured entry point for understanding the broader landscape of **RNA interaction research and RNA-targeted discovery**.

---

## 📚 Contents
1.  [Biomolecular Representation Learning](#molecular-representation-learning)
    - [RNA Language Model](#rna-language-model)
    - [RNA 2D Representation](#rna-2d-representation)
    - [RNA 3D Representation](#rna-3d-representation)
    - [Small Molecule and Protein Representation](#small-molecule-and-protein-representation)

2.  [RNA-Small Molecule Interaction Prediction](#rna-small-molecule-interaction-prediction)

3.  [RNA-Protein Interaction Prediction](#rna-protein-interaction-prediction)



---



## Molecular Representation Learning

### RNA Language Model
<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nature Communications** | **ERNIE-RNA: an RNA language model with structure-enhanced representations** | [Paper](https://www.nature.com/articles/s41467-025-64972-0) |
| **2025 arXiv** | **A Comparative Review of RNA Language Models** | [Paper](https://arxiv.org/pdf/2505.09087) | review \ preprint |
| **2025 Communications Biology** | **BiRNA-BERT allows efficient RNA language modeling with adaptive tokenization** | [Paper](https://www.nature.com/articles/s42003-025-08982-0) |
| **2024 Nature Communications** | **RNA language models predict mutations that improve RNA function** | [Paper](https://www.nature.com/articles/s41467-024-54812-y#Sec2) |
| **2025 Nature Communications** | **RiNALMo: general-purpose RNA language models can generalize well on structure prediction tasks** | [Paper](https://www.nature.com/articles/s41467-025-60872-5) |
| **2024 NeurIPS Proceedings** | **BEACON: Benchmark for Comprehensive RNA Tasks and Language Models** | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/a8ea503d91320fcfe12cba61c8a6d285-Paper-Datasets_and_Benchmarks_Track.pdf) |
| **2024 oxford academic** | **Multiple sequence alignment-based RNA language model and its application to structural inference** | [Paper](https://doi.org/10.1093/nar/gkad1031) |
| **2022 arXiv**| **Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions**| [Paper](https://arxiv.org/abs/2204.00300) | RNA-FM|
| **2023 bioRXiv**| **UNI-RNA: UNIVERSAL PRE-TRAINED MODELS REVOLUTIONIZE RNA RESEARCH**| [Paper](https://www.biorxiv.org/content/10.1101/2023.07.11.548588v1.full) |
| **2024 BIB**| **Self-supervised learning on millions of primary RNA sequences from 72 vertebrates improves sequence-based RNA splicing prediction**| [Paper](https://academic.oup.com/bib/article/25/3/bbae163/7644137) |
| **2024 Nature Machine Intelligence**|  **Multi-purpose RNA language modelling with motif-aware pretraining and type-guided fine-tuning** | [Paper](https://www.nature.com/articles/s42256-024-00836-4) |
| **2018 Bioinformatics**|  **Convolutional neural networks for classification of alignments of non-coding RNA sequences** | [Paper](https://doi.org/10.1093/bioinformatics/bty228) |
| **2025 科学技术与工程**|  **基于四元数的 RNA 特征提取方法.** | [Paper](http://dx.doi.org/10.12404/j.issn.1671-1815.2408787) |
| **2025 Bioinformatics**|  **From nucleotides to numbers: a comprehensive review of RNA feature extraction methods for computational modelling** | [Paper](https://doi.org/10.1093/bib/bbaf701) |  review |
| **2023 bioRxiv** | **Multiple sequence-alignment-based RNA language model and its application to structural inference** | [Paper](https://www.biorxiv.org/content/10.1101/2023.03.15.532863v1) | 基于多序列比对(MSA)的模型，引入进化保守性信息提升结构预测精度。 |
| **2024 bioRxiv** | **DGRNA: a long-context RNA foundation model with bidirectional attention Mamba2** | [Paper](https://www.biorxiv.org/content/10.1101/2024.10.31.621427v1) | 采用Mamba 架构替代 Transformer，解决了超长 RNA 序列处理的计算瓶颈。 |
</details>


### RNA 2D Representation
<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2011** | **ViennaRNA Package 2.0** | [Paper](https://link.springer.com/article/10.1186/1748-7188-6-26) |
| **2022 Nucleic Acids Research** | **UFold: fast and accurate RNA secondary structure prediction with deep learning** | [Paper](https://academic.oup.com/nar/article/50/3/e14/6430845) |
| **2005 JACS** | **RNA Structure Analysis at Single Nucleotide Resolution by Selective 2‘-Hydroxyl Acylation and Primer Extension (SHAPE)** | [Paper](https://pubs.acs.org/doi/10.1021/ja043822v) |
| **2015 Nature** | **Structural imprints in vivo decode RNA regulatory mechanisms** | [Paper](https://www.nature.com/articles/nature14263) | icSHAPE |
| **2022 Nucleic Acids Research** | **UFold: fast and accurate RNA secondary structure prediction with deep learning**|[Paper](https://academic.oup.com/nar/article/50/3/e14/6430845)|
| **2014 Nature**| **Genome-wide probing of RNA structure reveals active unfolding of mRNA structures in vivo**| [Paper](https://www.nature.com/articles/nature12894) |
| **2020 Bioinformatics**| **Graph neural representational learning of RNA secondary structures for predicting RNA-protein interactions**| [Paper](https://academic.oup.com/bioinformatics/article/36/Supplement_1/i276/5870515) |
| **2025 Nature Communications** | **Deep generalizable prediction of RNA secondary structure via base pair motif energy** | [Paper](https://www.nature.com/articles/s41467-025-60048-1) | 引入碱基对基元能量模型，显著提升了深度学习模型在未知 RNA 家族上的泛化预测能力。 |
| **2024 Communications Biology** | **Accurate prediction of RNA secondary structure including pseudoknots through solving minimum-cost flow with learned potential** | [Paper](https://www.nature.com/articles/s42003-024-05952-w) | 利用最小费用流算法与学习势能函数，实现了包含假结（Pseudoknots）的高精度二级结构预测。 |

</details>

### RNA 3D Representation

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024** | **Advances in the field of RNA 3D structure prediction and modeling, with purely theoretical approaches, 和 with the use of experimental data** | [Paper](https://www.cell.com/structure/fulltext/S0969-2126(24)00332-0) | review |
| **2021 Nucleic Acids Research**|  **RCSB Protein Data Bank: powerful new tools for exploring 3D structures of biological macromolecules for basic and applied research and education in fundamental biology, biomedicine, biotechnology, bioengineering and energy sciences** |[Paper](https://academic.oup.com/nar/article/49/D1/D437/5992282)| dataset |
| **2021 Science**| **Geometric deep learning of RNA structure**|[Paper](https://www.science.org/doi/10.1126/science.abe5650)|
| **2024**| **gRNAde: Geometric Deep Learning for 3D RNA inverse design**|[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11142113/)|
| **2023 ncs** | **Evaluating native-like structures of RNA-protein complexes through the deep learning method**|[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9958188/)|
| **2021 NIPS** | **ATOM3D: Tasks On Molecules in Three Dimensions** | [Paper](https://arxiv.org/abs/2012.04035)|
| **2021 Nature Method** | **Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning** | [Paper](https://www.nature.com/articles/s41592-019-0666-6)|
| **2025** | **The prediction of RNA-small-molecule ligand binding affinity based on geometric deep learning** |[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1476927125000271)|
| **2025** | **The prediction of RNA-small molecule binding sites in RNA structures based on geometric deep learning**|[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141813025038607)|

</details>


### Small Molecule and Protein Representation

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | 标题 | Links | Description |
| :--- | :--- | :--- | :--- |
| **1988** | **SMILES, a chemical language and information system. 1. Introduction to methodology and encoding rules** | [Paper](https://pubs.acs.org/doi/abs/10.1021/ci00057a005) |
| **2010 JCIM**| **Extended-Connectivity Fingerprints**| [Paper](https://pubs.acs.org/doi/10.1021/ci100050t) |
| **2020 arXiv** | **ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction**| [Paper](https://arxiv.org/abs/2010.09885) |
| **2020 arXiv** | **Molecular representation learning with language models and domain-relevant auxiliary tasks**| [Paper](https://arxiv.org/abs/2011.13230) |
| **2025 Nature Biotechnology**| **Predicting small molecule–RNA interactions without RNA tertiary structures**| [Paper](https://www.nature.com/articles/s41587-025-02942-z) |
| **2023 Science**| **Evolutionary-scale prediction of atomic-level protein structure with a language model**| [Paper](https://www.science.org/doi/10.1126/science.ade2574) |
| **2025 Science**| **Simulating 500 million years of evolution with a language model**| [Paper](https://www.science.org/doi/10.1126/science.ads0018) |
| **2022 TPAMI**| **ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning**| [Paper](https://ieeexplore.ieee.org/document/9477085) | Arichtecture|
| **2024 NAR**| **EquiPNAS: improved protein–nucleic acid binding site prediction using protein-language-model-informed equivariant deep graph neural networks**| [Paper](https://academic.oup.com/nar/article/52/5/e27/7590918) |
| **2025 Communications Biology**| **RNA-protein interaction prediction using network-guided deep learning**| [Paper](https://www.nature.com/articles/s42003-025-07694-9) |
| **2025 Cell Systems**| **ProtRNA: A protein-derived RNA language model by cross-modality transfer learning**| [Paper](https://www.cell.com/cell-systems/abstract/S2405-4712(25)00204-2) |
| **2025 Biorxiv**| **RESM: Capturing sequence and structure encoding of RNAs by mapped transfer learning from ESM (evolutionary scale modeling) protein language model**| [Paper](https://doi.org/10.1101/2025.08.09.669469) |
| **2024 MDPI**| **Advances in the Application of Protein Language Modeling for Nucleic Acid Protein Binding Site Prediction**| [Paper](https://www.mdpi.com/2073-4425/15/8/1090) |
| **2024 Biorxiv**| **Bridging biomolecular modalities for knowledge transfer in bio-language models**| [Paper](https://doi.org/10.1101/2024.10.15.618385) |
| **2025 Journal of Chemical Theory and Computation**| **Advances and Challenges in Machine Learning for RNA-Small Molecule Interaction Modeling: Review**| [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.5c00973) |  review  |
| **2026 Nature Biotechnology**| **Predicting small molecule–RNA interactions without RNA tertiary structures**| [Paper](https://www.nature.com/articles/s41587-025-02942-z) |
| **2025 Briefings in Bioinformatics**| **Reliable method for predicting the binding affinity of RNA-small molecule interactions using machine learning**| [Paper](https://doi.org/10.1093/bib/bbae002) |
| **2025 Bioinformatics**| **DeepRSMA: a cross-fusion-based deep learning method for RNA–small molecule binding affinity prediction**| [Paper](https://doi.org/10.1093/bioinformatics/btae678) |
| **2025 Nucleic Acids Research**| **RNAincoder: a deep learning-based encoder for RNA and RNA-associated interaction**| [Paper](https://doi.org/10.1093/nar/gkad404) |
| **2021 Nature**| **Highly Accurate Protein Structure Prediction with AlphaFold**| [Paper](https://www.nature.com/articles/s41586-021-03819-2) |
| **2015 Nature**| **Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning**| [Paper](https://www.nature.com/articles/nbt.3300) |

</details>


## RNA-Small Molecule Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2021 Bioinformatics**| **Recognition of small molecule–RNA binding sites using RNA sequence and structure**| [Paper](https://academic.oup.com/bioinformatics/article/37/1/36/6069564) |
| **2023 BIB**| **RLBind: a deep learning method to predict RNA–ligand binding sites**| [Paper](https://academic.oup.com/bib/article/24/1/bbac486/6832814) |
| **2022 Nature Reviews Drug Discovery**| **Targeting RNA structures with small molecules**| [Paper](https://www.nature.com/articles/s41573-022-00521-4) | review |
| **2018 Nature Reviews Drug Discovery**| **Principles for targeting RNA with drug-like small molecules**| [Paper](https://www.nature.com/articles/nrd.2018.93) | review |
| **2025 NCS**| **What’s so hard about RNA-targeting drug discovery?**| [Paper](https://www.nature.com/articles/s43588-025-00853-2) |
| **2025 JMB**| **Identifying RNA-small Molecule Binding Sites Using Geometric Deep Learning with Language Models**| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0022283625000762) | benchmark |
| **2025 Briefings in Bioinformatics** | **MVRBind: multi-view learning for RNA-small molecule binding site prediction** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf489/8260790) | MVRBind：采用多视图学习框架整合多维特征，专门用于高精度预测 RNA 上的小分子结合位点。 |
| **2025 Nature Computational Science** | **RNA–ligand interaction scoring via data perturbation and augmentation modeling** | [Paper](https://www.nature.com/articles/s43588-025-00820-x) | (RNAsmol) 通过数据扰动与增强建模优化亲和力打分，系统性解决了小分子-RNA 交互数据稀缺的问题。 |
| **2024 Nature Communications** | **sChemNET: a deep learning framework for predicting small molecules targeting microRNA function** | [Paper](https://www.nature.com/articles/s41467-024-49813-w) |
</details>



## RNA-Protein Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2020 Cell**| **How RNA-Binding Proteins Interact with RNA: Molecules and Mechanisms**| [Paper](https://www.cell.com/molecular-cell/fulltext/S1097-2765(20)30159-3) | review |
| **2019 Nature Methods**| **Methods to study RNA–protein interactions**| [Paper](https://www.nature.com/articles/s41592-019-0330-1) | review |
| **2025 Communications Biology**| **RNA-protein interaction prediction using network-guided deep learning**| [Paper](https://www.nature.com/articles/s42003-025-07694-9)  | |
| **2025 Interdiscip Sci Comput Life Sci**| **NPI-HGNN: A Heterogeneous Graph Neural Network-Based Approach for Predicting ncRNA-Protein Interactions**| [Paper](https://link.springer.com/article/10.1007/s12539-025-00689-4#citeas)  | |
| **2022 BIB**| **Predicting potential interactions between lncRNAs and proteins via combined graph auto-encoder methods**| [Paper](https://doi.org/10.1093/bib/bbac527) | ||
| **2023 Computers in Biology and Medicine**| **MHAM-NPI: Predicting ncRNA-protein interactions based on multi-head attention mechanism**| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S001048252300608X) |  || 
| **2024 Computational and Structural Biotechnology Journal**| **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools**| [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | review |
| **2025 TNNLS**| **RPI-GGCN: Prediction of RNA–Protein Interaction Based on Interpretability Gated Graph Convolution Neural Network and Co-Regularized Variational Autoencoders**| [Paper](https://ieeexplore.ieee.org/abstract/document/10520920) | |
| **2019 NC**| **A deep learning framework to predict binding preference of RNA constituents on protein surface**| [Paper](https://www.nature.com/articles/s41467-019-12920-0) | |
| **2020 NAR**| **DeepCLIP: predicting the effect of mutations on protein–RNA binding with deep learning**| [Paper](https://doi.org/10.1093/nar/gkaa530) | |
| **2021 BIB**| **Protein–RNA interaction prediction with deep learning: structure matters**| [Paper](https://doi.org/10.1093/bib/bbab540) | |
| **2022 Bioinformatics Advances**| **Prediction of RNA–protein interactions using a nucleotide language model**| [Paper](https://doi.org/10.1093/bioadv/vbac023) | |
| **2021 BIB**| **DeepDISOBind: accurate prediction of RNA-, DNA- and protein-binding intrinsically disordered residues with deep multi-task learning**| [Paper](https://doi.org/10.1093/bib/bbab521) | |


</details>