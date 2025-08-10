# Large Language Models in Bioinformatics: A Survey

> This is a summary of the paper "Large Language Models in Bioinformatics: A Survey" published in the Findings of the Association for Computational Linguistics: ACL 2025. It provides a systematic review of recent advancements in the application of LLMs to bioinformatics.

**Paper Link:** 🔗 [https://aclanthology.org/2025.findings-acl.184/](https://aclanthology.org/2025.findings-acl.184/)

---

## 📜 Abstract

Large Language Models (LLMs) are revolutionizing bioinformatics, enabling advanced analysis of DNA, RNA, proteins, and single-cell data. This survey provides a systematic review of recent advancements, focusing on genomic sequence modeling, RNA structure prediction, protein function inference, and single-cell transcriptomics. Meanwhile, the paper also discusses several key challenges, including data scarcity, computational complexity, and cross-omics integration, and explores future directions such as multimodal learning, hybrid AI models, and clinical applications. By offering a comprehensive perspective, this paper underscores the transformative potential of LLMs in driving innovations in bioinformatics and precision medicine.

## 🚀 Table of Models

This table provides a comprehensive overview of representative LLMs in bioinformatics, systematically categorized by model architecture, dataset, task, and application domain. **Some Models/Methods are provided here, and more details can be found in the original text** 🔗 [https://aclanthology.org/2025.findings-acl.184/](https://aclanthology.org/2025.findings-acl.184/).

| Model | Author & Time | Venue | Type | Datasets | Task Focus |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **DNABERT** | Ji et al. (2021) | Bioinformatics | Encoder-only | ENCODE | Predicts genomic functions using DNA sequences |
| **AlphaFold2** | Jumper et al. (2021) | Nature | — | PDB, BFD, etc | Predicts protein 3D structures from sequences |
| **RoseTTAFold** | Baek et al. (2021) | Science | Encoder-Decoder | PDB, etc | Predicts protein structures and interactions efficiently |
| **Enformer** | Avsec et al. (2021) | Nat. Methods | Encoder-only | UCSC Genome Browser, etc | Predicts gene expression from DNA sequences |
| **ESM-1b** | Rives et al. (2021) | PNAS | Encoder-only | UniParc | Predicts protein structure and function |
| **MSA Transformer** | Rao et al. (2021) | PMLR | Encoder-only | UniRef50 | Predicts protein structures using multiple sequence alignments |
| **Fold2Seq** | Cao et al. (2021) | PMLR | Encoder-Decoder | CATH 4.2 | Designs protein sequences from 3D folds |
| **ProGPT2** | Ferruz et al. (2022) | Nat. Commun. | Decoder-only | Uniref50 | Generates novel protein sequences with natural-like properties |
| **scBERT** | Yang et al. (2022) | Nat. Mach. Intell. | Encoder-only | Panglao | Annotates cell types from single-cell RNA-seq data |
| **ProteinBERT** | Brandes et al. (2022) | Bioinformatics | Encoder-only | UniProtKB and UniRef90 | Predicts protein functions from sequences |
| **ProtTrans** | Elnaggar et al. (2021) | IEEE PAMI | Encoder-only | UniRef and BFD | Predicts protein functions and structures |
| **ProGen** | Madani et al. (2023) | Nat. Biotechnol. | Decoder-only | UniprotKB, etc | Generates functional protein sequences across families |
| **ESMFold** | Lin et al. (2023) | Science | Encoder-Decoder | UniRef50 | Predicts protein structures from single sequences |
| **Geneformer** | Theodoris et al. (2023) | Nature | Encoder-Decoder | GEO, SRA, HCA, etc | Predicts gene networks from single-cell data |
| **HyenaDNA** | Nguyen et al. (2023) | NeurIPS | Decoder-only | Human reference genome | Models long-range DNA interactions at single-nucleotide resolution |
| **Uni-RNA** | Wang et al. (2023b) | bioRxiv | Encoder-only | RNAcentral, etc | Predicts RNA structures, functions, and properties |
| **ProGen2** | Nijkamp et al. (2023) | Cell Syst. | Decoder-only | UniProtKB and BFD | Generates functional protein sequences across families |
| **xTrimoPGLM** | Chen et al. (2025) | Nat. Methods | Encoder-Decoder | Uniref90 and ColabFoldDB | Predicts and designs protein sequences and structures |
| **RNA-MSM** | Zhang et al. (2024) | Nucleic Acids Res. | Encoder-only | RNAcmap | Predicts RNA structures using evolutionary information |
| **TFBert** | Luo et al. (2023) | Interdiscip. Sci. | Encoder-only | 690 ChIP-seq | Predicts transcription factor binding sites |
| **DNAGPT** | Zhang et al. (2023) | arXiv | Decoder-only | GRCh38 | Generates and analyzes DNA sequences |
| **GROVER** | Sanabria et al. (2024) | Nat. Mach. Intell. | Encoder-only | GRCh37 | Predicts DNA functions from sequence context |
| **megaDNA** | Shao and Yan (2024) | Nat. Commun. | Decoder-only | NCBI GenBank | Generates and analyzes functional genomes |
| **Nucleotide Transformer** | Dalla-Torre et al. (2024)| Nat. Methods | Encoder-only | GRCh38 | Predicts molecular phenotypes from DNA sequences |
| **RNAErnie** | Wang et al. (2024) | Nat. Mach. Intell. | Encoder-only | RNAcentral | Predicts RNA functions and structures |
| **RhoFold+** | Shen et al. (2024) | Nat. Methods | Encoder-only | RNAcentral | Predicts RNA 3D structures from sequences |
| **GPTCelltype** | Hou and Ji (2024) | Nat. Methods | Decoder-only | figshare, Zenodo, GEO, etc. | Automates cell type annotation using GPT-4 |
| **Evo** | Nguyen et al. (2024) | Science | Decoder-only | OpenGenome | Predicts and designs DNA, RNA, proteins |
| **scFoundation** | Hao et al. (2024a) | Nat. Methods | Encoder-Decoder | HCA, Single Cell Portal, GEO, etc | Predicts and analyzes single-cell transcriptomics data |
| **scGPT** | Cui et al. (2024) | Nat. Methods | Encoder-Decoder | CELLxGENE | Predicts and analyzes single-cell omics data |
| **AlphaFold3** | Abramson et al. (2024) | Nature | — | PDB | Predicts biomolecular structures and interactions accurately |
| **DNABERT2** | Zhou et al. (2023) | ICLR | Encoder-only | Human and multi-species genome | Predicts genomic functions across species efficiently |
| **ESM-DBP** | Zeng et al. (2024) | Nat. Commun. | Encoder-only | UniProtKB | Predicts DNA-binding proteins and residues accurately |
| **RoseTTAFold All-Atom**| Krishna et al. (2024) | Science | Encoder-Decoder | PDB, etc | Predicts and designs biomolecular structures |
| **ProstT5** | Heinzinger et al. (2024)| NAR Genom. Bioinform. | Encoder-Decoder | AFDB | Translates protein sequences to 3D structures |
| **EpiGePT** | Gao et al. (2024) | Genome Biol. | Encoder-only | ENCODE | Predicts context-specific epigenomic signals and interactions |
| **RiNALMo** | Penic et al. (2024) | arXiv | Encoder-only | RNAcentral | Predicts RNA structures and functions |
| **ENBED** | Malusare et al. (2024) | Bioinform. adv. | Encoder-Decoder | NCBI-Genome | Analyzes DNA sequences with byte-level precision |
| **GPN-MSA** | Benegas et al. (2025) | Nat. Biotechnol. | Encoder-only | multiz MSA, etc | Predicts genome-wide variant effects efficiently |
| **ESM-3** | Hayes et al. (2025) | Science | Encoder-Decoder | UniRef | Predicts and designs proteins with multi-modal inputs |

---

## 🎯 Key Application Domains

### 🧬 DNA and Genomics
LLMs are enhancing the analysis of DNA sequences, predicting mutation impacts, identifying regulatory elements, and generating functional gene sequences.
- **Models:** `DNABERT`, `DNABERT-2`, `GeneBERT`, `GROVER`, `MegaDNA`, `Nucleotide Transformer`, `Evo`, `Enformer`, `TFBert`, `DNAGPT`, `EpiGePT`, `GPN-MSA`, `ENBED`.

### 🦠 RNA
LLMs are applied to predict the complex secondary and tertiary structures of RNA, which are crucial for their function. They also help in understanding RNA functions and interactions.
- **Models:** `Uni-RNA`, `RhoFold+`, `NuFold`, `RNA-MSM`, `RNAErnie`, `RiNALMo`, `BioLLMNet`, `RNA-GPT`, `RNA-DCGen`.

### 🔬 Proteins
This is a major area where LLMs predict protein 3D structures, infer functions, and assist in the de novo design and engineering of novel proteins.
- **Models:** `AlphaFold2`, `RoseTTAFold`, `ESM-1b`, `ProteinBERT`, `ProtTrans`, `AlphaFold3`, `ESM-DBP`, `RoseTTAFold All-Atom`, `ProstT5`, `Fold2Seq`, `ProGPT2`, `ProGen`, `ProGen2`, `ESM-3`, `xTrimoPGLM`.

### 📊 Single-Cell (scRNA) Analysis
LLMs process vast single-cell datasets to automate cell type annotation, analyze gene expression, and understand cellular processes like disease progression.
- **Models:** `scBERT`, `Geneformer`, `GPTCelltype`, `scFoundation`, `scGPT`.

---

## 🚧 Challenges and Future Directions

### Key Challenges
*   **Data Scarcity, Quality, and Bias:** High-quality, annotated biological data is limited, leading to potential model biases.
*   **Computational Complexity:** Training and running state-of-the-art models require massive computational resources, limiting accessibility.
*   **Multimodal Integration:** Biological systems are complex. Current models often focus on a single data type (e.g., only DNA), missing the interactions between different molecular layers.

### Future Directions
*   **Hybrid AI Models:** Integrate LLMs with graph neural networks (GNNs) and knowledge graphs to improve biological reasoning.
*   **Multimodal Learning:** Develop models that can process DNA, RNA, protein, and epigenetic data simultaneously for a more holistic understanding.
*   **Clinical Applications:** Bridge the gap between research and real-world applications by focusing on model validation, regulatory compliance, and ethical considerations.

---

## ©️ Citation

If you find this summary or the original paper useful in your research, please consider citing:

```bibtex
@inproceedings{wang-etal-2025-large-language,
    title = "Large Language Models in Bioinformatics: A Survey",
    author = "Wang, Zhenyu  and
      Wang, Zikang  and
      Jiang, Jiyue  and
      Chen, Pengan  and
      Shi, Xiangyu  and
      Li, Yu",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-acl.184/",
    doi = "10.18653/v1/2025.findings-acl.184",
    pages = "3602--3615",
    ISBN = "979-8-89176-256-5",
    abstract = "Large Language Models (LLMs) are revolutionizing bioinformatics, enabling advanced analysis of DNA, RNA, proteins, and single-cell data. This survey provides a systematic review of recent advancements, focusing on genomic sequence modeling, RNA structure prediction, protein function inference, and single-cell transcriptomics. Meanwhile, we also discuss several key challenges, including data scarcity, computational complexity, and cross-omics integration, and explore future directions such as multimodal learning, hybrid AI models, and clinical applications. By offering a comprehensive perspective, this paper underscores the transformative potential of LLMs in driving innovations in bioinformatics and precision medicine."
}
