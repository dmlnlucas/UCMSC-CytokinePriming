# UC-MSC Cytokine Priming Analysis

This repository contains the analysis of transcriptomic data from human umbilical cord-derived mesenchymal stem cells (UC-MSCs) under two different priming conditions:

- **Cytokine-primed UC-MSCs** (IFN-γ + TNF-α + IL-1β) (GSE224190)
- **Single-primed UC-MSCs** (IFN-γ, TNF-α or IL-1β alone) (GSE129165)

The goal is to explore transcriptional changes and identify differentially expressed genes (DEGs), pathways, and biological processes associated with immunomodulatory and angiogenic enhancement. 
There is a special interest in membrane-associated DEGs, as the end goal is to create cell-derived nanoparticles.

## Repository Structure
├── data/ # Raw and preprocessed datasets

├── scripts/ # R script for analysis

├── results/ # Output figures and tables

├── README.md # This file

This code was written in the context of a Master's thesis at Hasselt University.

## Key findings

- Mixed cytokine priming changes the transcriptional status of a cell, mainly through upregulation of genes. All top 25 DEGs were upregulated in the primed condition.
- Membrane-associated immunmodulatory genes were almost entirely upregulated
- The mixed primed condition had a much larger amount of DEGs compared to the single primed, and a high overlap with single primed
- PCA analysis of all conditions further showed clear transcriptional similarities between TNF-a, IFN-g and the mixed conditions
- A linear regression fit of the logFC showed a significant synergistic effect of mixed cytokine priming compared to single-cytokine priming


## Contact

For questions or inquiries:
**Lucas Dumoulin** 

📧 dmlnlucas@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/lucasdumoulin/)  
🔗 [GitHub](https://github.com/dmlnlucas)
