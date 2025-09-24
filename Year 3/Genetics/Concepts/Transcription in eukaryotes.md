---
tags:
  - concept
aliases:
  - Eukaryotic Transcription Regulation
  - TF Regulation
---

### Definition
> Eukaryotic transcription regulation is the complex process by which cells control the expression of genes, primarily through the action of [[Transcription factors]] binding to [[Cis-acting elements]] on DNA.

### Context & Significance
The regulation of transcription in eukaryotes is significantly more complex than in bacteria. This complexity allows for the sophisticated gene expression programs necessary for multicellular life, including cell differentiation, development, and responses to the environment. It involves a larger variety of regulatory DNA sequences and protein factors, including those that package DNA into [[Chromatin]]. A core principle is **[[Combinatorial control]]**, where specific outcomes are achieved by using different combinations of a limited number of protein factors.

---

### Core Components & Principles

#### 1. Protein Factors (Trans-acting)
- **[[Transcription factors]] (TFs):** Proteins that bind to specific DNA sequences to modulate transcription. They exhibit **[[Modularity]]**, meaning their functional domains can act independently. Key domains include:
    - **[[DNA-binding domain]]:** Recognises and binds to specific DNA sequences.
	    - This domain allows the transcription factor to specifically recognize and bind to DNA enhancer elements. For example, [[Gal4]] has a DNA-binding domain that allows it to bind to upstream activation sequence (UAS) elements.
    - **[[Activation domain]] / [[Repression domain]]:** Recruits other proteins to activate or repress transcription.
	    - This domain interacts with other components of the transcription machinery to either **turn on (activate)** or **turn off (repress)** transcription. For instance, [[C-EBP]] (CCAAT/enhancer-binding protein) has an activation domain that interacts with other components to activate transcription, while other transcription factors have repression domains.
    - **[[Dimerization domain]]:** Allows TFs to form homodimers or heterodimers, increasing regulatory complexity and binding specificity.
	    - This facilitates the formation of **homodimers** (binding between two identical transcription factors) or **heterodimers** (binding between different family members). [[Gal4]], for example, binds as a homodimer to its binding sites.
    - **[[Ligand-binding Domain]]:** Binds small molecules like hormones or vitamins, often triggering a conformational change that activates the TF.
	    - This domain can bind a ligand, such as a hormone or vitamin, which changes the transcription factor's structure and activates it. An example is the Estrogen receptor, which binds estrogen.
- **[[coregulators]]:** Proteins that do not bind DNA themselves but are recruited by TFs to modulate transcription.
    - **[[Coactivators]]:** Increase transcription, for example by bridging TFs to [[RNA polymerase II]] or by modifying [[Chromatin Structure]] (e.g., histone acetyltransferases).
    - **[[Corepressors]]:** Decrease transcription.
- **[[general transcription factors]] (GTFs):** Proteins required at all promoters to initiate transcription by recruiting RNA Polymerase II.

#### 2. DNA Sequences (Cis-acting)
- **[[Promoters|Promoter]]:** The DNA region where transcription is initiated.
    - **Core Promoter:** Surrounds the transcription start site and is bound by GTFs.
- **[[Enhancers|Enhancer]] / [[silencer]]:** Regulatory DNA sequences that increase or decrease transcription, respectively. They can be located close to the promoter (proximal) or at a considerable distance (distal) and are bound by specific TFs.

---

### Model Systems & Examples

#### 1. The [[Yeast GAL system]]
A classic model for induced gene expression in response to an environmental signal (galactose).
- **Key Genes:** `GAL1, GAL2, GAL7, GAL10` (metabolic genes).
- **Key Regulators:**
    - **[[Gal4]]:** A TF (activator) that constitutively binds to an enhancer element called the **[[Upstream Activation Sequence (UAS)]]**.
    - **[[Gal80]]:** A corepressor that binds to Gal4's activation domain, inhibiting it.
    - **[[Gal3]]:** A sensor protein that, upon binding galactose, sequesters Gal80, freeing Gal4 to activate transcription.
- **Mechanism:**
    - **No Galactose:** Gal80 is bound to Gal4, transcription is OFF.
    - **Galactose Present:** Gal3 binds galactose, then binds Gal80, releasing it from Gal4. Gal4's activation domain is now exposed, and transcription is ON.
![[Pasted image 20250728112133.png]]
#### 2. [[Yeast mating-type switching]]
Demonstrates the principle of **[[Combinatorial control]]** where a few TFs generate different cell types.
- **Master Locus:** The **[[MAT locus]]** determines cell type (`a`, `α`, or `a/α` diploid).
- **Key Regulator:** **[[MCM1]]** is a TF present in all cell types.
- **Logic:**
    - **In `a` cells:** MCM1 alone activates `a`-specific genes.
    - **In `α` cells:** MCM1 combines with **[[alpha1 protein]]** (an activator) to turn ON `α`-specific genes. MCM1 also combines with **[[alpha2 protein]]** (a repressor) to turn OFF `a`-specific genes.
    - **In `a/α` diploid cells:** The **[[alpha2 protein]]** still represses `a`-specific genes with MCM1. Additionally, the **[[a1 protein]]** (from the `MATa` allele) binds to the **[[alpha2 protein]]**, and this new complex represses haploid-specific genes, including the `alpha1` gene itself.

---

### Connections
- **Parent Topics:** [[gene regulation]], [[Molecular Biology]]
- **Related Concepts:** [[Chromatin Remodeling]], [[Epigenetics]], [[Signal Transduction]], [[Notes on Developmental Genetics]]
- **Techniques:** [[ChIP-seq]] (to identify TF binding sites), [[Reporter assay]] (to measure enhancer activity).