# Published-work
This repository documents my contributions to published work.


## Published work #1 (2024)

**Felgines, Rymen, Martins et al. (2024)** *Nature Communications*  
“CLSY docking to Pol IV requires a conserved domain critical for small RNA biogenesis and transposon silencing.”   
Paper: https://www.nature.com/articles/s41467-024-54268-0  
Public analysis repo: https://github.com/toddblev/Felgines_Rymen_Martins_2024

## What I did
For Supplementary Fig. 6, I produced the **merged siRNA-seq analysis** by integrating **three independent Arabidopsis smRNA-seq datasets**:
- **Two previously published datasets** (from Zhou et al. 2018 and Zhou et al. 2022; I generated the libraries for the 2022 study)
- **One new dataset** generated for the 2024 paper (I generated the libraries and performed the bioinformatic analysis)

I used the lab’s standard siRNA-seq processing workflow as a base and added custom steps to harmonize outputs across studies, enabling comparison in a single figure.

Note: The upstream project repository intentionally remains minimal and does not include the custom merge code I wrote for this cross-study integration.

## Data sources (public accessions)
The merged figure integrates data from these public series:
- **Zhou et al. 2018 (smRNA-seq)**: GEO **GSE99692**  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99692
- **Zhou et al. 2022 (smRNA-seq)**: GEO **GSE164601**  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE164601
- **Felgines, Rymen, Martins et al. 2024 (smRNA-seq)**: GEO **GSE278181**  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE278181

## How to cite
Please cite: Felgines, L., Rymen, B., Martins, L.M. et al. CLSY docking to Pol IV requires a conserved domain critical for small RNA biogenesis and transposon silencing. Nat Commun 15, 10298 (2024). https://doi.org/10.1038/s41467-024-54268-0

## Published work #2 (2025)

**Xu et al. (2025)** *Nature Cell Biology*  
“Transcription factors instruct DNA methylation patterns in plant reproductive tissues.”   
Paper: https://www.nature.com/articles/s41556-025-01808-5  
Public analysis repo: https://github.com/jlawlab/REM_INSTRUCTS_METHYLATION/tree/main/Extended_Data_Fig.2a_REM_phylogenetic_tree

## What I did
1. Phylogeny (Extended Data Fig. 2a):
I reconstructed a phylogeny for 46 Arabidopsis REM genes. This analysis uses two custom scripts:
- `LM_REM_phylogenetic_tree.bash` — sequence alignment + tree inference  
- `LM_Phylo_Tree_Visualization.r` — tree visualization

2. RNAseq (Fig. 3i):
RNA-seq data were generated from flower, ovule, and anther tissues. I used the lab’s standard RNA-seq processing workflow as a base and added custom steps (not deposited in the repo) to harmonize outputs across studies, enabling comparison in a single figure.

## Data sources (public accessions)
  **Xu et al. 2025**: GEO **GSE282200**  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282200

## How to cite
Please cite: Xu, G., Chen, Y., Martins, L.M. et al. Transcription factors instruct DNA methylation patterns in plant reproductive tissues. Nat Cell Biol 27, 2116–2127 (2025). https://doi.org/10.1038/s41556-025-01808-5

## Contact
**My unpublished work is private, but can be consulted upon request**

Laura M. Martins (lmmartinsw@gmail.com)

