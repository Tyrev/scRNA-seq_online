### Introduction to scRNA-seq

1. There are many challenges associated with scRNA-seq analysis. Which of the following is **NOT** an issue we encounter?
    - i. scRNA-seq generates large volumes of data 
    - i. Low depth of sequencing will produce zero counts for many genes that are actually expressed in the cell
    - i. **Transcripts can be over-represented in the library due to PCR artifacts**
    - i. Temporal changes can cause biological variability
    - i. Batch effects can cause technical variability

 
### Raw data to count matrix

1. Which of the following statements is **NOT TRUE** about the 3' end sequencing protocols for single cell RNA-seq"?
    - Cheaper per cell cost
    - Larger number of cells sequenced allow for better identity of cell populations
    - **Ideal for detection of isoform-level differences in expression**
    - More accurate quantification due to use UMIs

1. **True**/False. Two reads with the same sample index, cellular barcode and UMI should be counted as a single read.

1. True/**False**. Using single cell RNA-seq we are assaying so many cells per sample, so there is no need to have biological replicates.

1. Which of the following steps are **NOT** involved in creating a cell x gene count matrix?
    - Filtering out unknown cellular barcodes
    - Demultiplexing the samples
    - Mapping/pseudo-mapping to transcriptome
    - **Compute quality metrics for each individual sample**
    - Collapsing UMIs and quantification of reads

