# Single-Cell
Notes and studies about single-cell analysis
## Vocabulary
* **Central dogma of molecular biology**

<p align="center">
  <img src="Central-Dogma-DNA-to-RNA-to-Protein.png" width="350" title="central dogma">
</p>

* A **tisuue** is a group of cells that have similar structure and function together as a unit. 
* **Transcription profiling:** Also known as **expression profiling**. It involves the quantification of gene expression of many genes in cells or tissue samples at the transcription (RNA) level.
* **Gene expression** is the process by which information from a gene is used in the synthesis of functional gene product that enables it to produce end products, protein or non-coding RNA, end ultimately phenotype, as final effect.
* **Tissue heterogeneity** refers to the fact that data generated with biological samples can be compromised by cells originating from other tissues or organs than the target tissue or organ of profiling. It can be caused by biological processes (such as immune cell infiltration), sample contamination, or mistakes in sample labelling.
*  **Read counts** are the total number of mRNAs from a gene that you sequenced.
*  **UMI (Unique Molecular Identifier) counts** are the total number of unique mRNAs for a gene that you captured.
*  **Demultiplexing** refers to the step in processing where you'd use the barcode information in order to know which sequences came from which samples after they had all be sequenced together.
*  In molecular biology, a **transcription factor (TF)** (or sequence-specific DNA-binding factor) is a protein that controls the rate of transcription of genetic information from DNA to messenger RNA, by binding to a specific DNA sequence.
*  A **doublet** is the case of two cells being lysed and sequenced within the same droplet.


## Notes
* Single-cell RNA-seq can asses the global state of all mRNA transcripts being expresses within a tissue with single-cell resolution, so with high content measures.
* Single-cell RNA-seq enables questions about tissue heterogeneity and how cells transition between different phsiological states.

* **Bulk vs Single-cell RNA sequencing**

 <p align="center">
  <img src="bulk_vs_SC.png" width="450" title="Bulk vs Single-Cell RNA sequencing">
</p>

* **Goals of scRNA-seq**
   - Measure the distribution of expression levels for each gene across a population of cells.
   - Measure transcriptional differences across and within groups of cells.
   - Resolve single-cell heterogeneity.
   
* **Overview of Single-cell RNA sequencing**

 <p align="center">
  <img src="scrna-process.png" width="650" title="Overview of Single-cell RNA sequencing">
</p>

* Unique molecular identifiers (UMIs) reduce amplification error

 <p align="center">
  <img src="umi-cellbarcode.png" width="450" title="umi and cell barcode">
</p>

* UMI counts compromise the gene by cell matrices for the analysis.

* Consideration for choosing scRNA-seq technology

 <p align="center">
  <img src="scRNA-seq-techs.png" width="450" title="comparison of scRNA-seq technologies">
</p>

* **Single cell RNA-seq analysis workflow**

 <p align="center">
  <img src="schematic-view-scRNA-seq-analysis.png" title="schematic-view-scRNA-seq-analysis">
</p>

## References
  1. UCLA QCBio Collaboratory - [Webinars on Youtube](https://www.youtube.com/watch?v=jwSPTgF9ESQ&t=1177s)
  2. https://en.wikipedia.org/wiki/Transcription_factor
  3. Luecken, M. D., & Theis, F. J. (2019). Current best practices in single‐cell RNA‐seq analysis: a tutorial. Molecular systems biology, 15(6), e8746.
