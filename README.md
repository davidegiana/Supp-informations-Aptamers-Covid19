# Supplementary Code and Data for article: Sequence optimization of a DNA aptamer inhibiting COVID-19 infection guided by analysis of secondary structure distribution
This repository contains the supplementary code and data of the following article :

[UNDER REVIEW]

# Summary of the uploaded data:
```
Permutations_SSD_Calculation.ipynd  #Jupyter Notebook containing the script used to generate all permutations of a DNA sequence given the starting sequence, first nucleotide to mutate and last nucleotide to mutate and S_pm calculations.
Sequence_Table.csv ->               #Table containg all the sequences used in the article
Pipeline_output/                     #Folder containing intermediate results of the pipeline 
    │── subopt                      # Nupack suboptimal structures
    │── barriers                    # Barriers strucure selection
    │── Nuclust_output              # Nuclust structure selection
    │── bpRNA_input                 # bpRNA input files generated from both Barriers and Nuclust output
    │── bpRNA_output                # bpRNA output
    └── alignment.csv               # sequence-structure alignment table
```
# Citations

NUPACK

* [M.E. Fornace, N.J. Porubsky, and N.A. Pierce (2020). A unified dynamic programming framework for the analysis of interacting nucleic acid strands: enhanced models, scalability, and speed. ACS Synth Biol, 9:2665-2678, 2020.](https://pubs.acs.org/doi/10.1021/acssynbio.9b00523)
* [R. M. Dirks, J. S. Bois, J. M. Schaeffer, E. Winfree, and N. A. Pierce. Thermodynamic analysis of interacting nucleic acid strands. SIAM Rev, 49:65-88, 2007.](https://epubs.siam.org/doi/10.1137/060651100)
