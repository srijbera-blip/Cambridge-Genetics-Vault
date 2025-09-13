---
tags:
  - concept
aliases:
  - Chromatin Immunoprecipitation followed by sequencing
---
allows researchers to identify the genome-wide locations DNA binding proteins and specific histone modifications

### purpose and principle
ChIP-seq devised to identify all the binding sites of a protein in a sequenced genome
used to map histone modifications and other events that occur at gene promoters and [[Enhancers]], indicating their activity or regulatory state
helps to catalog protein-DNA interactions in normal and diseased cells providing insights into gene function

### methodology/process
several steps:
- cross-linking
	- cells treated with chemicals like formaldehyde (1%) of disuccinimidyl glutarate (DSG) to covalently link proteins to the DNA they are bound to --> preserves protein-dna interactions throughout the following steps
- chromatin fragmentation
	- cross linked chromatin broken into small pieces. achieved by
		- digestion with MNase( micococcal nuclease) to an average size of 1-2kb
		- sonication, particularly for studies of SWI/SNF complex subunits ,which may involve dual cross linking (DSG then formaldehyde) before fragmentation
- immunoprecipitation (IP)
	- a specific antibody recognises protein of interest (e.g. a regulatory protein or a specific histone modification) is added to capture and purify these complexes
- Cross-linking reversal and DNA purification
	- cross links between proteins and dna are reversed usually by overnight incubation and the DNA in extracted and purified using minelute pcr purification kits. the purified dna is quantified before library preparation
- **Sequencing Library Preparation:** The purified ChIP DNA is used to prepare sequencing libraries. This typically involves using kits compatible with next-generation sequencing platforms
- **Next-Generation Sequencing:** The DNA fragments are then subjected to high-throughput DNA sequencing, such as **Illumina sequencing**
- **Data Analysis:** The raw sequencing reads from ChIP-seq experiments undergo rigorous computational analysis
- **Alignment:** Reads are aligned to a reference genome (e.g., mm9 or mm10 for mouse) using tools like Bowtie or bowtie2
- **Filtering:** Alignments are filtered to remove spurious signals, duplicate reads, and low-quality data
- **Peak Calling:** Specialized software (e.g., MACS2) is used to **identify "peaks" of enrichment**, which correspond to the genomic regions where the protein of interest or histone modification is present
- **Normalization:** Signal values are normalized across samples to account for variations in sequencing depth and pull-down effi
- **Downstream Analysis:** This can include
	- Classification of identified regions as promoters or enhancers based on their proximity to transcription start sites (TSS) and other histone marks (e.g., H3K4me3)
	- Correlation of ChIP-seq signals with changes in gene expression (e.g., using RNA-seq data)
	- Identification of super-enhancers
	- Transcription factor motif enrichment analysis to predict co-factors
	- Gene ontology (GO) enrichment analysis to understand associated biological pathways


### application and findings
**Applications and Findings from Sources:**

• **SWI/SNF Complex Studies:** ChIP-seq has been extensively used to study mammalian SWI/SNF chromatin remodeling complexes.

    ◦ ChIP-seq for H3K27ac in mouse embryonic fibroblasts (MEFs) showed that SWI/SNF subunit inactivation (e.g., Smarca4 or Smarcb1 loss) led to a **marked reduction in H3K27ac levels at many enhancers**, but not at promoters

.

    ◦ ChIP-seq for core SWI/SNF subunits (SMARCC1 and SMARCA4) revealed that **SWI/SNF is bound at the vast majority of enhancers** in wild-type cells. Loss of Smarcb1 significantly reduced SWI/SNF binding, particularly at enhancers, which correlated with the loss of H3K27ac

.

    ◦ ChIP-seq data, combined with RNA-seq, showed a **significant correlation between loss of H3K27ac at enhancers and reduced expression of nearest genes**, with downregulated genes often associated with development and differentiation pathways

.

    ◦ In a different study, MLF2-V5 ChIP-seq was performed to assess MLF2 binding to chromatin, and it **did not detect MLF2 bound to chromatin** across the genome, suggesting MLF2's role is upstream of SWI/SNF chromatin binding

.

• **Histone Modification Mapping:** ChIP has been used to identify histone modifications at specific gene promoters, such as the IFN-β gene, showing that these modifications occur prior to transcription initiation

.

• **Protein-DNA Interaction Mapping:** ChIP-seq is crucial for cataloging protein-DNA interactions in normal and diseased cells

.

• **Nucleosome Distribution:** ChIP (specifically, ChIP-seq) allows for the determination of the genome-wide distribution of nucleosomes

.

In summary, ChIP-seq is an essential high-throughput genomic technique that provides detailed, genome-wide maps of protein-DNA interactions and specific histone modifications, offering crucial insights into gene regulation and chromatin dynamics.

