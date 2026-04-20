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

4.  [RNA-RNA Interaction Prediction](#rna-rna-interaction-prediction)

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
| **2025 Bioinformatics**| **DeepRSMA: a cross-fusion-based deep learning method for RNA–small molecule binding affinity prediction**| [Paper](https://doi.org/10.1093/bioinformatics/btae678) |
| **2025 Nucleic Acids Research**| **RNAincoder: a deep learning-based encoder for RNA and RNA-associated interaction**| [Paper](https://doi.org/10.1093/nar/gkad404) |
| **2021 Nature**| **Highly Accurate Protein Structure Prediction with AlphaFold**| [Paper](https://www.nature.com/articles/s41586-021-03819-2) |
| **2015 Nature**| **Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning**| [Paper](https://www.nature.com/articles/nbt.3300) |

</details>


## A Task-Oriented View of Intermolecular RNA Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

### 2.1 Interaction types: RNA-RNA, RNA-protein, RNA-small molecule
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is a useful chapter-opening reference because it explicitly treats RNA–protein, RNA–small molecule, and RNA–RNA prediction within one sequence-only framework. |
| **2022 Brief. Bioinform.** | **Protein-RNA interaction prediction with deep learning: structure matters** | [Paper](https://academic.oup.com/bib/article/23/1/bbab540/6470965) | A focused review of protein–RNA interaction prediction that helps define the RNA–protein branch of the chapter and distinguishes site and preference prediction settings. |
| **2024 Brief. Bioinform.** | **A Hitchhiker's guide to RNA–RNA structure and interaction prediction tools** | [Paper](https://academic.oup.com/bib/article/25/1/bbad421/7457347) | A broad review of RNA–RNA structure and interaction prediction that is well suited for defining the RNA–RNA branch of the task space. |
| **2025 Drug Discov. Today** | **Artificial intelligence for RNA–ligand interaction prediction: advances and prospects** | [Paper](https://www.sciencedirect.com/science/article/pii/S1359644625000790) | A comprehensive review of RNA–ligand prediction that helps define the RNA–small molecule branch, including site prediction, affinity prediction, docking, and screening. |
| **2022 Nucleic Acids Res.** | **RNAInter v4.0: RNA interactome repository with redefined confidence scoring system and improved accessibility** | [Paper](https://academic.oup.com/nar/article/50/D1/D326/6414580) | **RNAInter** is useful here because it makes explicit that a single repository may contain multiple RNA-centered interaction types under different evidence and confidence schemes. |
| **2023 Nucleic Acids Res.** | **NPInter v5.0: ncRNA interaction database in a new era** | [Paper](https://academic.oup.com/nar/article/51/D1/D232/6827104) | **NPInter** is a key database reference for emphasizing that RNA-centered “interaction” spans several partner modalities and does not correspond to one single prediction problem. |

### 2.2 Prediction granularities: pair, site, profile, affinity, structure, screening
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is a useful representative of pair-level interaction prediction, where the output is whether an RNA-partner pair is likely to interact. |
| **2025 J. Mol. Biol.** | **Identifying RNA-small Molecule Binding Sites Using Geometric Deep Learning with Language Models** | [Paper](https://www.sciencedirect.com/science/article/pii/S0022283625000762) | **RNABind** is a representative binding-site prediction paper, where the model outputs local RNA regions or nucleotides likely to bind small molecules. |
| **2025 Nucleic Acids Res.** | **Base-resolution binding profile prediction of proteins on RNAs with deep learning** | [Paper](https://academic.oup.com/nar/article/53/14/gkaf748/8223173) | **iDeepB** represents profile-style prediction, where the output is a base-resolution binding landscape rather than a single binary label. |
| **2024 Brief. Bioinform.** | **Reliable method for predicting the binding affinity of RNA-small molecule interactions using machine learning** | [Paper](https://academic.oup.com/bib/article/25/2/bbae002/7584787) | This paper is a clear example of affinity regression, where the goal is to predict quantitative binding strength instead of interaction existence alone. |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | This benchmark is useful for illustrating structure-level or duplex-level prediction, where the output concerns intermolecular base pairing rather than pair classification. |
| **2024 Nat. Methods** | **Accurate RNA 3D structure prediction using a language model-based deep learning approach** | [Paper](https://www.nature.com/articles/s41592-024-02487-0) | **RhoFold+** represents structure generation, where the output is a 3D structural hypothesis rather than a scalar interaction score. |
| **2025 Nat. Commun.** | **RNAmigos2: accelerated structure-based RNA virtual screening with deep graph learning** | [Paper](https://www.nature.com/articles/s41467-025-57852-0) | **RNAmigos2** is a screening-oriented model in which the output is a ranking over compounds, making it a useful reference for virtual screening as a distinct prediction granularity. |

### 2.3 Supervision semantics: physical interaction, functional association, proxy signal
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 Nucleic Acids Res.** | **RNAInter v4.0: RNA interactome repository with redefined confidence scoring system and improved accessibility** | [Paper](https://academic.oup.com/nar/article/50/D1/D326/6414580) | **RNAInter** is a key reference for showing that “interaction” labels may arise from very different evidence types and confidence levels. |
| **2023 Nucleic Acids Res.** | **NPInter v5.0: ncRNA interaction database in a new era** | [Paper](https://academic.oup.com/nar/article/51/D1/D232/6827104) | **NPInter** is especially useful for emphasizing that many datasets mix direct physical interactions with broader association-style annotations. |
| **2023 Brief. Bioinform.** | **A systematic benchmark of machine learning methods for protein-RNA interaction prediction** | [Paper](https://academic.oup.com/bib/article/24/5/bbad307/7252289) | This benchmark makes clear that many protein–RNA models are trained on heterogeneous CLIP-derived signals, so supervision often reflects experimental proxy readouts rather than direct physical binding alone. |
| **2024 Comput. Struct. Biotechnol. J.** | **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools** | [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | This review is useful for contrasting direct sequence/structure-based prediction with proxy-signal-driven models trained on high-throughput datasets. |
| **2025 Commun. Biol.** | **PaRPI predicts RNA-Protein interactions from cross-protocol and cross-batch RNA-binding protein datasets** | [Paper](https://www.nature.com/articles/s42003-025-08807-0) | **PaRPI** is directly relevant to supervision semantics because it explicitly addresses protocol- and batch-dependent binding signals as a source of supervision inconsistency. |
| **2025 Patterns** | **A deep learning model for characterizing protein-RNA interactions from sequences at single-base resolution** | [Paper](https://www.sciencedirect.com/science/article/pii/S2666389924003222) | **Reformer** is a useful example of proxy-signal supervision because it learns from eCLIP-style binding profiles, where the target is an experimental signal landscape rather than a pure binary physical interaction label. |

### 2.4 A conceptual map linking task, representation, and evaluation
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Mach. Intell.** | **Generalized biological foundation model with unified nucleic acid and protein language** | [Paper](https://www.nature.com/articles/s42256-025-01044-4) | **LucaOne** is a strong reference for linking task diversity to shared biological representation learning across RNA, DNA, and proteins. |
| **2025 Nat. Commun.** | **Benchmarking pre-trained genomic language models for RNA sequence-related predictive applications** | [Paper](https://www.nature.com/articles/s41467-025-66899-y) | This benchmark is highly relevant for showing that representation choice, task formulation, and evaluation setting are tightly coupled in RNA prediction. |
| **2026 Brief. Bioinform.** | **Zero-shot benchmarking of RNA language models in structural, functional and evolutionary learning** | [Paper](https://academic.oup.com/bib/article/27/2/bbag098/8509095) | This paper provides a compact bridge from task taxonomy to representation analysis by comparing how RNA language models behave across structurally and functionally distinct tasks. |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is a good transition paper because it naturally connects partner modality, backbone representation, and downstream task heads within one conceptual framework. |
| **2025 Nat. Commun.** | **Data splitting to avoid information leakage with DataSAIL** | [Paper](https://www.nature.com/articles/s41467-025-58606-8) | **DataSAIL** is helpful for the evaluation side of the conceptual map, because it makes clear that task definition and representation cannot be separated from split strategy and generalization assessment. |

</details>


## RNA-Small Molecule Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

### 2026
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2026 Nat. Biotechnol.** | **Predicting small molecule–RNA interactions without RNA tertiary structures** | [Paper](https://www.nature.com/articles/s41587-025-02942-z) | **SMRTnet** predicts small molecule–RNA interactions without requiring RNA tertiary structures, enabling scalable screening for RNA-targeted discovery. |
| **2026 Brief. Bioinform.** | **CoBRA: compound binding site prediction using RNA language model** | [Paper](https://academic.oup.com/bib/article/27/1/bbaf713/8419945) | **CoBRA** uses an RNA language model for RNA–compound binding-site prediction and is designed to work without explicit tertiary-structure input. |
| **2026 J. Chem. Inf. Model.** | **DeepMIF: A Multiview Interactive Fusion-Based Deep Learning Method for RNA–Small Molecule Binding Affinity Prediction** | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c02946) | **DeepMIF** focuses on RNA–small molecule binding affinity prediction through multiview interactive fusion of RNA and ligand representations. |
| **2026 J. Cheminform.** | **DeepRNA-DTI: a deep learning approach for RNA-compound interaction prediction with binding site interpretability** | [Paper](https://link.springer.com/article/10.1186/s13321-025-01132-y) | **DeepRNA-DTI** is a sequence-based deep learning framework for RNA–compound interaction prediction with interpretable binding-site outputs. |


### 2025
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Comput. Sci.** | **What’s so hard about RNA-targeting drug discovery?** | [Paper](https://www.nature.com/articles/s43588-025-00853-2) | A commentary discussing major bottlenecks in RNA-targeting drug discovery, including limited data, evaluation challenges, and generalization issues. |
| **2025 J. Mol. Biol.** | **Identifying RNA-small Molecule Binding Sites Using Geometric Deep Learning with Language Models** | [Paper](https://www.sciencedirect.com/science/article/pii/S0022283625000762) | **RNABind** combines geometric deep learning with RNA language-model embeddings for RNA–small molecule binding-site prediction. |
| **2025 Brief. Bioinform.** | **MVRBind: multi-view learning for RNA-small molecule binding site prediction** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf489/8260790) | **MVRBind** integrates multiple structural views to improve RNA–small molecule binding-site prediction accuracy. |
| **2025 Nat. Comput. Sci.** | **RNA–ligand interaction scoring via data perturbation and augmentation modeling** | [Paper](https://www.nature.com/articles/s43588-025-00820-x) | **RNAsmol** improves RNA–ligand interaction scoring through data perturbation and augmentation to address data scarcity. |
| **2025 J. Chem. Inf. Model.** | **GATRsite: RNA–Ligand Binding Site Prediction Using Graph Attention Convolution Network and Pre-trained RNA Language Model** | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c00605) | **GATRsite** combines graph attention with a pretrained RNA language model for RNA–ligand binding-site prediction. |
| **2025 Brief. Bioinform.** | **DistRMI: a deep distance-aware neural network for explainable RNA loop motif-small molecule interaction prediction** | [Paper](https://academic.oup.com/bib/article/26/6/bbaf660/8375362) | **DistRMI** targets RNA loop motif–small molecule interaction prediction with distance-aware modeling and interpretability. |



### 2024
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024 Nature Communications** | **sChemNET: a deep learning framework for predicting small molecules targeting microRNA function** | [Paper](https://www.nature.com/articles/s41467-024-49813-w) |
| **2024 JBHI**| **MultiModRLBP: A Deep Learning Approach for Multi-Modal RNA-Small Molecule Ligand Binding Sites Prediction**| [Paper](https://ieeexplore.ieee.org/abstract/document/10530045) |
| **2024 Bioinformatics**| **DeepRSMA: a cross-fusion-based deep learning method for RNA–small molecule binding affinity prediction**| [Paper](https://doi.org/10.1093/bioinformatics/btae678) |
| **2024 JCTC**| **SPRank─A Knowledge-Based Scoring Function for RNA-Ligand Pose Prediction and Virtual Screening**| [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.4c00681) |
| **2024 Bioinformatics** | **DeepRSMA: a cross-fusion-based deep learning method for RNA-small molecule binding affinity prediction** | [Paper](https://academic.oup.com/bioinformatics/article/40/12/btae678/7900291) | **DeepRSMA** uses cross-fusion and cross-attention to model fine-grained RNA and ligand features for binding-affinity prediction. |
| **2024 Brief. Bioinform.** | **Reliable method for predicting the binding affinity of RNA-small molecule interactions using machine learning** | [Paper](https://academic.oup.com/bib/article/25/2/bbae002/7584787) | A machine-learning framework for RNA–small molecule binding-affinity prediction, with an emphasis on robustness across RNA subtypes. |
| **2024 Nat. Commun.** | **Identifying small-molecules binding sites in RNA conformational ensembles with SHAMAN** | [Paper](https://www.nature.com/articles/s41467-024-49638-7) | **SHAMAN** identifies small-molecule binding sites from RNA conformational ensembles, highlighting the role of RNA dynamics in ligand recognition. |
| **2024 J. Chem. Inf. Model.** | **A Machine Learning Method for RNA–Small Molecule Binding Preference Prediction** | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c01324) | A machine-learning method for RNA–small molecule binding-preference prediction at the RNA–ligand pair level. |



### 2023 
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2023 Brief. Bioinform.** | **RLBind: a deep learning method to predict RNA–ligand binding sites** | [Paper](https://academic.oup.com/bib/article/24/1/bbac486/6832814) | **RLBind** is a deep learning approach for RNA–ligand binding-site prediction using global sequence/structure features and local nucleotide context. |
| **2023 Brief. Bioinform.** | **Structural interaction fingerprints and machine learning for predicting and explaining binding of small molecule ligands to RNA** | [Paper](https://academic.oup.com/bib/article/24/4/bbad187/7171416) | This study uses structural interaction fingerprints and machine learning to predict and explain RNA–small molecule binding. |



### 2022 and Earlier 
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 Nature Reviews Drug Discovery**| **Targeting RNA structures with small molecules**| [Paper](https://www.nature.com/articles/s41573-022-00521-4) | review |
| **2022 NeurIPS workshop**| **Predicting Ligand-RNA Binding Using E3-Equivariant Network and Pretraining**| [Paper](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.mlsb.io/papers_2022/Predicting_Ligand_RNA_Binding_Using_E3_Equivariant_Network_and_Pretraining.pdf) | |
| **2021 Bioinformatics**| **Recognition of small molecule–RNA binding sites using RNA sequence and structure**| [Paper](https://academic.oup.com/bioinformatics/article/37/1/36/6069564) |
| **2018 Nature Reviews Drug Discovery**| **Principles for targeting RNA with drug-like small molecules**| [Paper](https://www.nature.com/articles/nrd.2018.93) | review |
| **2022 J. Cheminform.** | **Machine learning approaches to optimize small-molecule inhibitors for RNA targeting** | [Paper](https://link.springer.com/article/10.1186/s13321-022-00583-x) | A machine-learning study on optimizing RNA-targeting small-molecule inhibitors, relevant to RNA–small molecule screening and design. |
| **2022 MLSB Workshop** | **Predicting Ligand–RNA Binding Using E3-Equivariant Network and Pretraining** | [Paper](https://www.mlsb.io/papers_2022/Predicting_Ligand_RNA_Binding_Using_E3_Equivariant_Network_and_Pretraining.pdf) | A workshop paper that applies E3-equivariant modeling and pretraining to ligand–RNA binding prediction. |



</details>



## RNA-Protein Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

### 2026 
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2026 bioRxiv**| **Augmented prediction of multi-species protein–RNA interactions using evolutionary conservation of RNA-binding proteins**| [Paper](https://www.biorxiv.org/content/10.1101/2025.09.27.678913v2.abstract) | |
| **2026 arXiv**| **ZeroFold: Protein-RNA Binding Affinity Predictions from Pre-Structural Embeddings**| [Paper](https://arxiv.org/abs/2603.23583) | |

### 2025
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Communications Biology**| **RNA-protein interaction prediction using network-guided deep learning**| [Paper](https://www.nature.com/articles/s42003-025-07694-9)  | |
| **2025 Interdiscip Sci Comput Life Sci**| **NPI-HGNN: A Heterogeneous Graph Neural Network-Based Approach for Predicting ncRNA-Protein Interactions**| [Paper](https://link.springer.com/article/10.1007/s12539-025-00689-4#citeas)  | |
| **2025 TNNLS**| **RPI-GGCN: Prediction of RNA–Protein Interaction Based on Interpretability Gated Graph Convolution Neural Network and Co-Regularized Variational Autoencoders**| [Paper](https://ieeexplore.ieee.org/abstract/document/10520920) | |
| **2025 Communications Biology**| **PRA-Pred: Structure-based prediction of protein-RNA binding affinity**| [Paper](https://www.nature.com/articles/s42003-025-07694-9) | |
| **2025 BIB**| **Graph-RPI: predicting RNA–protein interactions via graph autoencoder and self-supervised learning strategies**| [Paper](https://doi.org/10.1093/bib/bbaf292) | |
| **2025 Communications Biology**| **PaRPI predicts RNA-Protein interactions from cross-protocol and cross-batch RNA-binding protein datasets**| [Paper](https://www.nature.com/articles/s42003-025-08807-0) | |
| **2025 JCIM**| **Transfer Learning for Predicting ncRNA-Protein Interactions**| [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.5c00914) | |
| **2025 PLOS One**| **RPIPLM: Prediction of ncRNA-protein interaction by post-training a dual-tower pretrained biological model with supervised contrastive learning**| [Paper](https://doi.org/10.1371/journal.pone.0329174) | |
| **2025 JCIM**| **SeqMG-RPI: A Sequence-Based Framework Integrating Multi-Scale RNA Features and Protein Graphs for RNA-Protein Interaction Prediction**| [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.5c00176) | |
| **2025 Patterns**| **A deep learning model for characterizing protein-RNA interactions from sequences at single-base resolution**| [Paper](https://www.cell.com/patterns/fulltext/S2666-3899(24)00322-2) | |
| **2025 NAR**| **Base-resolution binding profile prediction of proteins on RNAs with deep learning**| [Paper](https://doi.org/10.1093/nar/gkaf748) | |


### 2024
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024 Computational and Structural Biotechnology Journal**| **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools**| [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | review |
| **2024 NAR**| **Prediction of protein-RNA interactions from single-cell transcriptomic data**| [Paper](https://doi.org/10.1093/nar/gkae076) | |
| **2024 IJBM**| **PRA-Pred: Structure-based prediction of protein-RNA binding affinity**| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141813024002939) | |


### 2023
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2023 Computers in Biology and Medicine**| **MHAM-NPI: Predicting ncRNA-protein interactions based on multi-head attention mechanism**| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S001048252300608X) |  || 
| **2023 BIB**| **A systematic benchmark of machine learning methods for protein–RNA interaction prediction**| [Paper](https://doi.org/10.1093/bib/bbad307) | |
| **2023 Computational and Structural Biotechnology Journal**| **ncRPI-LGAT: Prediction of ncRNA-protein interactions with line graph attention network framework**| [Paper](https://www.sciencedirect.com/science/article/pii/S2001037023001241) | |

### 2022 and Earlier
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 BIB**| **Predicting potential interactions between lncRNAs and proteins via combined graph auto-encoder methods**| [Paper](https://doi.org/10.1093/bib/bbac527) | ||
| **2022 Bioinformatics Advances**| **Prediction of RNA–protein interactions using a nucleotide language model**| [Paper](https://doi.org/10.1093/bioadv/vbac023) | |
| **2021 BIB**| **DeepDISOBind: accurate prediction of RNA-, DNA- and protein-binding intrinsically disordered residues with deep multi-task learning**| [Paper](https://doi.org/10.1093/bib/bbab521) | |
| **2021 BIB**| **Protein–RNA interaction prediction with deep learning: structure matters**| [Paper](https://doi.org/10.1093/bib/bbab540) | |
| **2020 Cell**| **How RNA-Binding Proteins Interact with RNA: Molecules and Mechanisms**| [Paper](https://www.cell.com/molecular-cell/fulltext/S1097-2765(20)30159-3) | review |
| **2020 NAR**| **DeepCLIP: predicting the effect of mutations on protein–RNA binding with deep learning**| [Paper](https://doi.org/10.1093/nar/gkaa530) | |
| **2019 Nature Methods**| **Methods to study RNA–protein interactions**| [Paper](https://www.nature.com/articles/s41592-019-0330-1) | review |
| **2019 NC**| **A deep learning framework to predict binding preference of RNA constituents on protein surface**| [Paper](https://www.nature.com/articles/s41467-019-12920-0) | |


## RNA-RNA Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

### 2026
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2026 Nat. Commun.** | **The role of low-complexity repeats in RNA–RNA interactions and a deep learning framework for duplex prediction** | [Paper](https://www.nature.com/articles/s41467-026-68356-w) | **RIME** links large-scale RRI data analysis with a language-model-based predictor for RNA–RNA duplex prediction, highlighting the importance of low-complexity repeats. |
| **2026 Bioinformatics** | **DeepLMI: Deep Feature Mining with a Globally Enhanced Graph Convolutional Network for Robust lncRNA–miRNA Interaction Prediction** | [Paper](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btag145/8541986) | **DeepLMI** combines deep feature mining with a globally enhanced GCN to improve robustness in lncRNA–miRNA interaction prediction. |
| **2026 Front. Artif. Intell.** | **Computational understanding of non-coding RNA pairwise interactions** | [Paper](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2026.1749205/full) | **CUPID** predicts ncRNA–ncRNA interactions directly from primary sequences using a deep learning framework oriented toward pairwise ncRNA interaction discovery. |
| **2026 Bioinform. Adv.** | **MiRInter-Trans: a Transformer-Based Framework for microRNA Interaction Prediction** | [Paper](https://academic.oup.com/bioinformaticsadvances/advance-article/doi/10.1093/bioadv/vbag073/8512506) | **MiRInter-Trans** uses RNA foundation-model embeddings and a Transformer-style pipeline to predict miRNA interactions from sequence alone across multiple RNA-partner types. |
| **2026 J. Chem. Inf. Model.** | **HetGAT-LMI: Interpretable Heterogeneous Graph Attention Method for Predicting lncRNA-miRNA Interactions** | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c02664) | **HetGAT-LMI** builds an interpretable heterogeneous graph attention model for lncRNA–miRNA interaction prediction and emphasizes graph-level explainability. |

### 2025
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is a unified sequence-only framework that predicts RNA interactions with proteins, small molecules, and other RNAs using pretrained biological language models. |
| **2025 Brief. Bioinform.** | **Introducing TEC-LncMir for prediction of lncRNA-miRNA interactions through deep learning of RNA sequences** | [Paper](https://academic.oup.com/bib/article/26/1/bbaf046/8006248) | **TEC-LncMir** treats lncRNA and miRNA sequences as language-like inputs and combines Transformer encoders with CNNs for sequence-driven interaction prediction. |
| **2025 Brief. Bioinform.** | **Enhancing LncRNA-miRNA interaction prediction with multimodal contrastive representation learning** | [Paper](https://academic.oup.com/bib/article/26/3/bbaf281/8164224) | **MCRLMI** integrates multi-source similarity information and sequence encodings through multimodal contrastive learning for improved lncRNA–miRNA interaction prediction. |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | This study benchmarks 23 methods for base-pair prediction in RNA–RNA interactions and highlights the strong zero-shot performance of deep-learning-based approaches. |
| **2025 Int. J. Biol. Macromol.** | **LncRNA-miRNA interaction prediction based on multi-source heterogeneous graph neural network and multi-level attention mechanism** | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141813025061690) | **LMI-MM** integrates multi-source heterogeneous networks, sequence-derived attributes, and multi-level attention for lncRNA–miRNA interaction prediction. |
| **2025 Int. J. Biol. Macromol.** | **A rapid prediction model for MiRNA-LncRNA interactions utilizing multi-view projection fusion and random parallel matrix factorization** | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0141813025059598) | **MVPFDPC** emphasizes fast and accurate miRNA–lncRNA interaction prediction through multi-view projection fusion and matrix-factorization-style modeling. |

### 2024
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024 Brief. Bioinform.** | **A Hitchhiker's guide to RNA–RNA structure and interaction prediction tools** | [Paper](https://academic.oup.com/bib/article/25/1/bbad421/7457347) | A broad review of RNA–RNA structure and interaction prediction tools, covering thermodynamics-based and comparative approaches as well as practical tool selection. |
| **2024 Methods Mol. Biol.** | **How to do RNA-RNA Interaction Prediction? A Use-Case Driven Handbook Using IntaRNA** | [Paper](https://link.springer.com/chapter/10.1007/978-1-0716-3519-3_9) | A practical handbook for applying **IntaRNA** to different RNA–RNA interaction prediction scenarios, with emphasis on accessibility-based prediction strategies. |
| **2024 Comput. Struct. Biotechnol. J.** | **A heterogeneous information network learning model with neighborhood-level structural representation for predicting lncRNA-miRNA interactions** | [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024002265) | **HINLMI** integrates heterogeneous biological knowledge and neighborhood-level structural representation learning for lncRNA–miRNA interaction prediction. |
| **2024 J. Cell. Mol. Med.** | **LncRNA–miRNA interactions prediction based on meta-path similarity and Gaussian kernel similarity** | [Paper](https://onlinelibrary.wiley.com/doi/full/10.1111/jcmm.18590) | **MPGK-LMI** combines meta-path similarity, Gaussian kernel similarity, and graph attention to model lncRNA–miRNA interactions more effectively. |

### 2023
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2023 IEEE/ACM Trans. Comput. Biol. Bioinform.** | **A Survey of Computational Methods and Databases for lncRNA-MiRNA Interaction Prediction** | [Paper](https://doi.org/10.1109/TCBB.2023.3264254) | A focused survey of computational methods, databases, and evaluation strategies for lncRNA–miRNA interaction prediction. |
| **2023 Methods Mol. Biol.** | **Web Services for RNA-RNA Interaction Prediction** | [Paper](https://link.springer.com/protocol/10.1007/978-1-0716-2768-6_11) | A review of web services for RNA–RNA interaction prediction, including general-purpose tools, class-specific tools, and RNA-design-oriented services. |
| **2023 BMC Bioinformatics** | **GKLOMLI: a link prediction model for inferring miRNA–lncRNA interactions by using Gaussian kernel-based method on network profile and linear optimization algorithm** | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05309-w) | **GKLOMLI** formulates miRNA–lncRNA interaction discovery as a link-prediction problem using Gaussian-kernel similarity and linear optimization. |
| **2023 Interdiscip. Sci. Comput. Life Sci.** | **PmliHFM: Predicting Plant miRNA-lncRNA Interactions with Hybrid Feature Mining Network** | [Paper](https://pubmed.ncbi.nlm.nih.gov/36223068/) | **PmliHFM** is a plant-focused predictor that uses hybrid feature mining to capture interaction-relevant patterns from miRNA and lncRNA sequences. |
| **2023 IEEE Trans. Nanobiosci.** | **Predicting Plant miRNA-lncRNA Interactions via a Deep Learning Method** | [Paper](https://pubmed.ncbi.nlm.nih.gov/37167036/) | **PmlIPM** is a deep learning framework for plant miRNA–lncRNA interaction prediction, designed for species-specific RNA regulatory analysis. |

### 2022
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 Symmetry** | **Recent Deep Learning Methodology Development for RNA–RNA Interaction Prediction** | [Paper](https://www.mdpi.com/2073-8994/14/7/1302) | A review of recent deep learning methodology for RNA–RNA interaction prediction, with particular attention to miRNA–mRNA and lncRNA–miRNA tasks. |
| **2022 Brief. Bioinform.** | **ncRNAInter: a novel strategy based on graph neural network to discover interactions between lncRNA and miRNA** | [Paper](https://academic.oup.com/bib/article/23/6/bbac411/6770397) | **ncRNAInter** uses graph neural networks and a comprehensive RNA representation strategy to identify lncRNA–miRNA interactions. |
| **2022 Brief. Bioinform.** | **Predicting the potential human lncRNA–miRNA interactions based on graph convolution network with conditional random field** | [Paper](https://academic.oup.com/bib/article/23/6/bbac463/6775599) | **GCNCRF** combines graph convolution with conditional random fields to model human lncRNA–miRNA interaction networks. |
| **2022 IEEE/ACM Trans. Comput. Biol. Bioinform.** | **MD-MLI: Prediction of miRNA–lncRNA Interaction by Using Multiple Features and Hierarchical Deep Learning** | [Paper](https://www.computer.org/csdl/journal/tb/2022/03/09246277/1olDhDAvx5u) | **MD-MLI** uses hierarchical deep learning and multiple feature sources to improve miRNA–lncRNA interaction prediction. |
| **2022 Interdiscip. Sci. Comput. Life Sci.** | **BoT-Net: a lightweight bag of tricks-based neural network for efficient LncRNA-miRNA interaction prediction** | [Paper](https://link.springer.com/article/10.1007/s12539-022-00535-x) | **BoT-Net** is a lightweight sequence-based model that focuses on informative subsequences to improve efficiency and generalization in lncRNA–miRNA interaction prediction. |

</details>


## Datasets, Benchmarks, and Evaluation Pitfalls

### Data Resources Across Tasks

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

#### Sequence / family resources
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2026 Nucleic Acids Res.** | **RNAcentral in 2026: genes and literature integration** | [Paper](https://academic.oup.com/nar/article/54/D1/D303/8382359) | A major integrative resource for RNA sequences, genes, and literature links across RNA classes, useful as a general entry point for sequence-centric tasks. |
| **2025 Nucleic Acids Res.** | **Rfam 15: RNA families database in 2025** | [Paper](https://academic.oup.com/nar/article/53/D1/D258/7889252) | A core family-level resource for curated RNA families, consensus secondary structures, and alignments, widely used in homology-aware benchmarking. |

#### Structure resources
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2011 Nucleic Acids Res.** | **PRIDB: a protein-RNA interface database** | [Paper](https://pubmed.ncbi.nlm.nih.gov/21071426/) | **PRIDB** provides curated protein–RNA interface annotations and is particularly useful for residue-level and binding-site prediction tasks. |
| **2014 Nucleic Acids Res.** | **The Nucleic Acid Database: new features and capabilities** | [Paper](https://academic.oup.com/nar/article/42/D1/D114/1070039) | **NDB** is a foundational nucleic-acid structural resource that supports RNA and RNA-complex structure analysis beyond general-purpose structural repositories. |

#### Task-specific interaction resources
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 Nucleic Acids Res.** | **RNAInter v4.0: RNA interactome repository with redefined confidence scoring system and improved accessibility** | [Paper](https://academic.oup.com/nar/article/50/D1/D326/6414580) | **RNAInter** is a comprehensive interaction repository spanning RNA–RNA, RNA–protein, RNA–small molecule, and related interaction types with explicit confidence annotations. |
| **2023 Nucleic Acids Res.** | **NPInter v5.0: ncRNA interaction database in a new era** | [Paper](https://academic.oup.com/nar/article/51/D1/D232/6827104) | **NPInter** is a major ncRNA interaction database covering broad functional and physical interaction annotations across many RNA-centered tasks. |
| **2023 J. Mol. Biol.** | **R-SIM: A Database of Binding Affinities for RNA-small Molecule Interactions** | [Paper](https://www.sciencedirect.com/science/article/pii/S002228362200540X) | **R-SIM** focuses on quantitative RNA–small molecule binding affinities and is especially relevant for regression and affinity-prediction benchmarks. |
| **2022 ACS Chem. Biol.** | **R-BIND 2.0: An Updated Database of Bioactive RNA-Targeting Small Molecules and Associated RNA Secondary Structures** | [Paper](https://pubs.acs.org/doi/10.1021/acschembio.2c00224) | **R-BIND 2.0** organizes bioactive RNA-targeting ligands together with associated RNA structural context and is useful for RNA-ligand discovery studies. |

#### Benchmark-oriented resource papers
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024 J. Mol. Biol.** | **RNA3DB: A structurally-dissimilar dataset split for training and benchmarking deep learning models of RNA structure prediction** | [Paper](https://www.sciencedirect.com/science/article/pii/S0022283624001475) | **RNA3DB** emphasizes structure-dissimilar splits, making it a benchmark-oriented resource for studying leakage-aware evaluation and out-of-distribution generalization. |

</details>

### Evaluation Metrics Across Prediction Settings

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

#### Classification metrics
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2015 PLoS One** | **The Precision-Recall Plot Is More Informative than the ROC Plot When Evaluating Binary Classifiers on Imbalanced Datasets** | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0118432) | A classic reference showing why PR curves and AUPRC are often more informative than ROC curves under strong class imbalance. |

#### Regression metrics
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2024 Brief. Bioinform.** | **Reliable method for predicting the binding affinity of RNA-small molecule interactions using machine learning** | [Paper](https://academic.oup.com/bib/article/25/2/bbae002/7584787) | A representative RNA–small molecule affinity-prediction study that reports common regression metrics and discusses robustness across RNA subtypes. |
| **2024 Int. J. Biol. Macromol.** | **PRA-Pred: Structure-based prediction of protein-RNA binding affinity** | [Paper](https://www.sciencedirect.com/science/article/pii/S0141813024002939) | **PRA-Pred** exemplifies structure-based protein–RNA affinity prediction and is useful when discussing regression settings in interaction modeling. |

#### Structure-level metrics
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2016 PLoS One** | **DockQ: A Quality Measure for Protein-Protein Docking Models** | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0161879) | **DockQ** is a widely used continuous structure-quality metric that can inform RNA-complex evaluation by analogy to docking-style assessment. |
| **2005 Proteins** | **Assessing predictions of protein-protein interactions: the CAPRI experiment** | [Paper](https://pubmed.ncbi.nlm.nih.gov/15659362/) | The **CAPRI** framework established influential structure-level evaluation criteria such as interface- and RMSD-based assessment. |

#### Virtual screening metrics
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2007 J. Chem. Inf. Model.** | **Evaluating Virtual Screening Methods: Good and Bad Metrics for the "Early Recognition" Problem** | [Paper](https://pubs.acs.org/doi/10.1021/ci600426e) | A classic paper on virtual-screening evaluation, particularly important for early-recognition metrics such as enrichment-oriented assessment. |
| **2009 BMC Bioinformatics** | **A statistical framework to evaluate virtual screening** | [Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC2722655/) | A statistical treatment of virtual-screening metrics that is often cited when discussing robust evaluation beyond single-score summaries. |

#### RNA-specific evaluation / benchmark papers
| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | A dedicated benchmark study for RNA–RNA base-pair prediction that highlights task-specific metric design and the importance of strict evaluation. |

</details>

### Splitting Strategies and the Generalization Problem

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Commun.** | **Data splitting to avoid information leakage with DataSAIL** | [Paper](https://www.nature.com/articles/s41467-025-58606-8) | **DataSAIL** directly addresses data leakage caused by naive splitting and motivates similarity-aware train/test partitioning. |
| **2024 J. Mol. Biol.** | **RNA3DB: A structurally-dissimilar dataset split for training and benchmarking deep learning models of RNA structure prediction** | [Paper](https://www.sciencedirect.com/science/article/pii/S0022283624001475) | **RNA3DB** shows how structurally dissimilar splits provide a more realistic picture of model generalization than random splits. |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | This benchmark explicitly studies stricter evaluation settings and is useful when arguing that random splits can overestimate RNA–RNA prediction performance. |
| **2024 Comput. Struct. Biotechnol. J.** | **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools** | [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | A cross-example benchmark that better reflects practical generalization than single-dataset random-split evaluation alone. |
| **2023 Brief. Bioinform.** | **A systematic benchmark of machine learning methods for protein-RNA interaction prediction** | [Paper](https://academic.oup.com/bib/article/24/5/bbad307/7252289) | A systematic benchmark study that helps illustrate how model performance changes under more realistic and harder generalization settings. |

</details>

### Negative Sampling and Label Quality

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 BMC Biol.** | **Negative sampling strategies impact the prediction of scale-free biomolecular network interactions with machine learning** | [Paper](https://link.springer.com/article/10.1186/s12915-025-02231-w) | A highly relevant study showing that benchmark conclusions can be dominated by the negative-sampling protocol in biomolecular interaction prediction. |
| **2022 Brief. Bioinform.** | **Positive-unlabeled learning in bioinformatics and computational biology: a brief review** | [Paper](https://academic.oup.com/bib/article/23/1/bbab461/6415313) | A concise review explaining why many biological interaction tasks are better viewed as positive-unlabeled problems rather than standard binary classification. |
| **2023 Inf. Sci.** | **SURE: Screening unlabeled samples for reliable negative samples based on reinforcement learning** | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025523001226) | **SURE** provides a representative strategy for identifying reliable negatives from unlabeled data, which is directly relevant to label-quality discussions. |

</details>

### Methodological Blind Spots Across RNA Interaction Prediction

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2022 Brief. Bioinform.** | **Protein-RNA interaction prediction with deep learning: structure matters** | [Paper](https://academic.oup.com/bib/article/23/1/bbab540/6470965) | A broad review emphasizing structural information, dataset limitations, and unresolved methodological challenges in protein–RNA prediction. |
| **2024 Brief. Bioinform.** | **A Hitchhiker's guide to RNA-RNA structure and interaction prediction tools** | [Paper](https://academic.oup.com/bib/article/25/1/bbad421/7457347) | A comprehensive review of RNA–RNA prediction tools that is especially useful for discussing thermodynamics, accessibility, and methodological boundaries. |
| **2022 WIREs Comput. Mol. Sci.** | **RNA-ligand molecular docking: advances and challenges** | [Paper](https://wires.onlinelibrary.wiley.com/doi/10.1002/wcms.1571) | A strong reference for blind spots related to static structures, insufficient flexibility modeling, and incomplete treatment of thermodynamics and kinetics. |
| **2025 Drug Discov. Today** | **Artificial intelligence for RNA-ligand interaction prediction: advances and prospects** | [Paper](https://www.sciencedirect.com/science/article/pii/S1359644625000790) | A review of current AI approaches for RNA–ligand prediction that highlights data scarcity, poor cross-domain transfer, and the lack of unified benchmarks. |
| **2025 Nat. Comput. Sci.** | **What’s so hard about RNA-targeting drug discovery?** | [Paper](https://www.nature.com/articles/s43588-025-00853-2) | A concise perspective on why RNA-targeting discovery remains difficult, particularly from the standpoint of data, evaluation, and generalization. |
| **2025 Commun. Biol.** | **RNA-protein interaction prediction using network-guided deep learning** | [Paper](https://www.nature.com/articles/s42003-025-07694-9) | A representative recent model paper that is useful for discussing the gap between benchmark performance and true generalization to unseen molecules. |
| **2026 Int. J. Mol. Sci.** | **Sequence-Based Models for RNA–Protein Interactions: Imputation Might Be Insufficient for Novel Signal Prediction in eCLIP Data** | [Paper](https://pubmed.ncbi.nlm.nih.gov/41683618/) | This paper directly highlights limited extrapolation and weak novel-signal generalization in sequence-based RNA–protein models. |

</details>

### Recommended Best Practices

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Commun.** | **Data splitting to avoid information leakage with DataSAIL** | [Paper](https://www.nature.com/articles/s41467-025-58606-8) | A key reference supporting the recommendation to prioritize leakage-aware and similarity-aware split strategies. |
| **2015 PLoS One** | **The Precision-Recall Plot Is More Informative than the ROC Plot When Evaluating Binary Classifiers on Imbalanced Datasets** | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0118432) | A foundational reference supporting the recommendation to report PR-based metrics under strong class imbalance. |
| **2025 BMC Biol.** | **Negative sampling strategies impact the prediction of scale-free biomolecular network interactions with machine learning** | [Paper](https://link.springer.com/article/10.1186/s12915-025-02231-w) | Supports the recommendation to document negative-sampling schemes explicitly and avoid overinterpreting results driven by sampling artifacts. |
| **2022 Brief. Bioinform.** | **Positive-unlabeled learning in bioinformatics and computational biology: a brief review** | [Paper](https://academic.oup.com/bib/article/23/1/bbab461/6415313) | Supports treating many interaction datasets as partially labeled rather than fully observed binary ground truth. |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | Supports the recommendation to evaluate under stricter and task-faithful benchmark settings instead of relying only on optimistic random splits. |
| **2024 Comput. Struct. Biotechnol. J.** | **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools** | [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | Supports the recommendation to include external case studies or broader cross-example validation when possible. |
| **2022 Nucleic Acids Res.** | **RNAInter v4.0: RNA interactome repository with redefined confidence scoring system and improved accessibility** | [Paper](https://academic.oup.com/nar/article/50/D1/D326/6414580) | Supports the recommendation to state label provenance clearly and distinguish among interaction definitions across databases. |
| **2023 Nucleic Acids Res.** | **NPInter v5.0: ncRNA interaction database in a new era** | [Paper](https://academic.oup.com/nar/article/51/D1/D232/6827104) | Supports the recommendation to distinguish physical interaction prediction from broader association-style prediction tasks. |

</details>


## Unified RNA Models

> Representative references organized into three broad categories.

## 1. Unified Trends

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Mach. Intell.** | **Generalized biological foundation model with unified nucleic acid and protein language** | [Paper](https://www.nature.com/articles/s42256-025-01044-4) | **LucaOne** is an important early example of unified biological sequence modeling across nucleic acids and proteins, supporting the idea of shared pretrained backbones. |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is a clear RNA-centric unification attempt, using one framework to support RNA–protein, RNA–small molecule, and RNA–RNA interaction prediction. |
| **2024 Nature** | **Accurate structure prediction of biomolecular interactions with AlphaFold 3** | [Paper](https://www.nature.com/articles/s41586-024-07487-w) | **AlphaFold 3** demonstrates that a single biomolecular architecture can jointly model proteins, nucleic acids, ligands, ions, and modified residues. |
| **2025 Nat. Commun.** | **RiNALMo: general-purpose RNA language models can generalize well on structure prediction tasks** | [Paper](https://www.nature.com/articles/s41467-025-60872-5) | **RiNALMo** supports the trend toward general-purpose RNA backbones that transfer across multiple structure-related downstream tasks. |
| **2025 Nat. Commun.** | **ERNIE-RNA: an RNA language model with structure-enhanced representations** | [Paper](https://www.nature.com/articles/s41467-025-64972-0) | **ERNIE-RNA** integrates structural priors into RNA language modeling and is highly relevant to unified RNA representation learning. |
| **2026 Nat. Methods** | **Orthrus: toward evolutionary and functional RNA foundation models** | [Paper](https://www.nature.com/articles/s41592-026-03064-3) | **Orthrus** represents a newer stage of RNA foundation modeling aimed at jointly capturing evolutionary and functional RNA signals. |
| **2026 RNA Biol.** | **AI foundation models for RNA biology** | [Paper](https://www.tandfonline.com/doi/full/10.1080/15476286.2026.2650517) | This review summarizes how RNA foundation models are starting to function as general backbones for diverse RNA biology tasks. |

</details>

## 2. Main Barriers

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2026 Brief. Bioinform.** | **Zero-shot benchmarking of RNA language models in structural, functional and evolutionary learning** | [Paper](https://academic.oup.com/bib/article/27/2/bbag098/8509095) | This benchmark shows that current RNA language models still have uneven strengths across structural, functional, and evolutionary tasks, limiting true unification. |
| **2025 Nat. Commun.** | **Benchmarking pre-trained genomic language models for RNA sequence-related predictive applications** | [Paper](https://www.nature.com/articles/s41467-025-66899-y) | This study highlights the persistence of heterogeneous task definitions and inconsistent downstream supervision in RNA-related prediction. |
| **2025 Nat. Commun.** | **Benchmarking all-atom biomolecular structure prediction with FoldBench** | [Paper](https://www.nature.com/articles/s41467-025-67127-3) | **FoldBench** shows that nucleic acids remain especially challenging for all-atom prediction, underscoring RNA structural uncertainty and flexibility. |
| **2024 Comput. Struct. Biotechnol. J.** | **RNA-protein interaction prediction without high-throughput data: An overview and benchmark of in silico tools** | [Paper](https://www.sciencedirect.com/science/article/pii/S2001037024003866) | This benchmark is useful for discussing fragmented evaluation standards, inconsistent inputs, and varying output definitions in RNA–protein prediction. |
| **2025 Bioinformatics** | **Benchmarking the methods for predicting base pairs in RNA-RNA interactions** | [Paper](https://academic.oup.com/bioinformatics/article/41/6/btaf289/8125807) | This paper directly illustrates the fragmentation of RNA–RNA benchmarks and how stricter evaluation can change the ranking of methods. |
| **2022 WIREs Comput. Mol. Sci.** | **RNA-ligand molecular docking: advances and challenges** | [Paper](https://wires.onlinelibrary.wiley.com/doi/10.1002/wcms.1571) | This review is a key reference for discussing static-structure assumptions, insufficient treatment of flexibility, and incomplete thermodynamic and kinetic modeling. |
| **2025 Nat. Comput. Sci.** | **What’s so hard about RNA-targeting drug discovery?** | [Paper](https://www.nature.com/articles/s43588-025-00853-2) | This perspective captures major translational bottlenecks such as sparse data, unstable supervision, and the lack of standardized benchmarks. |
| **2025 Curr. Opin. Struct. Biol.** | **Foundation models of protein sequences: A brief overview** | [Paper](https://www.sciencedirect.com/science/article/pii/S0959440X25000223) | This review is useful for contrast, showing how protein modeling already has a more mature and coherent foundation-model ecosystem than RNA. |
| **2025 Curr. Opin. Struct. Biol.** | **Are protein language models the new universal key?** | [Paper](https://www.sciencedirect.com/science/article/pii/S0959440X25000156) | This paper helps explain the gap between RNA and protein fields by showing how protein language models have become broadly reusable across tasks. |

</details>

## 3. Future Directions

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Mach. Intell.** | **Generalized biological foundation model with unified nucleic acid and protein language** | [Paper](https://www.nature.com/articles/s42256-025-01044-4) | **LucaOne** is a useful reference when arguing for shared pretrained backbones as the foundation of unified RNA interaction architectures. |
| **2025 Nat. Commun.** | **ERNIE-RNA: an RNA language model with structure-enhanced representations** | [Paper](https://www.nature.com/articles/s41467-025-64972-0) | **ERNIE-RNA** supports the view that unified RNA models should combine sequence learning with explicit structure-aware inductive bias. |
| **2024 Nat. Mach. Intell.** | **An interpretable RNA foundation model for exploring functional RNA motifs in plants** | [Paper](https://www.nature.com/articles/s42256-024-00946-z) | **PlantRNA-FM** is relevant for the blueprint because it connects foundation modeling with interpretability and motif-level mechanistic insight. |
| **2025 Brief. Bioinform.** | **BioLLMNet: enhancing RNA-interaction prediction with a specialized cross-LLM transformation network** | [Paper](https://academic.oup.com/bib/article/26/5/bbaf549/8303308) | **BioLLMNet** is especially useful for motivating partner-modality fusion and multi-head RNA interaction prediction within one architecture. |
| **2026 Nat. Biotechnol.** | **Predicting small molecule–RNA interactions without RNA tertiary structures** | [Paper](https://www.nature.com/articles/s41587-025-02942-z) | **SMRTnet** supports the idea that future unified models should remain useful even when high-quality RNA tertiary structures are unavailable. |
| **2024 Nat. Methods** | **Accurate RNA 3D structure prediction using a language model-based deep learning approach** | [Paper](https://www.nature.com/articles/s41592-024-02487-0) | **RhoFold+** is an important reference for structure-generation heads in unified RNA pipelines. |
| **2025 Nat. Comput. Sci.** | **RNA–ligand interaction scoring via data perturbation and augmentation modeling** | [Paper](https://www.nature.com/articles/s43588-025-00820-x) | **RNAsmol** is highly relevant for task-specific heads such as ranking and scoring in unified RNA-targeted screening workflows. |
| **2024 Nat. Commun.** | **Identifying small-molecules binding sites in RNA conformational ensembles with SHAMAN** | [Paper](https://www.nature.com/articles/s41467-024-49638-7) | **SHAMAN** is a strong reference for dynamic and ensemble-aware modeling, an important direction for future unified RNA frameworks. |
| **2026 RNA Biol.** | **AI foundation models for RNA biology** | [Paper](https://www.tandfonline.com/doi/full/10.1080/15476286.2026.2650517) | This review is useful for summarizing future directions such as larger RNA foundation models, multimodal supervision, interpretability, and design-oriented applications. |

</details>


