# Visualize Plastid Genome Structure
## Circular Chloroplast Genome Map of Citrus sinensis

*Course:* Cell and Molecular Biology Laboratory  
*Student:* Zenas Charis C. Deguit  
*Course/Section:* B  
*Scientific Name:* Citrus sinensis (L.) Osbeck  
*Common Name:* Sweet Orange  
*Family:* Rutaceae  
*NCBI Accession:* NC_008334.1  
*Genome Length:* 160,129 bp  
*Database:* NCBI RefSeq  
*Visualization Software:* OrganellarGenomeDRAW (OGDRAW)

---

## 1. Introduction

Plastid genomes contain genetic information essential for photosynthesis and other cellular processes. In many flowering plants, the chloroplast genome exhibits a quadripartite structure consisting of a Large Single-Copy (LSC) region, a Small Single-Copy (SSC) region, and two Inverted Repeat regions (IRa and IRb).

This activity focused on visualizing the complete chloroplast genome of Citrus sinensis using OrganellarGenomeDRAW (OGDRAW). The circular genome map was generated to examine its structural organization, gene distribution, transcriptional orientation, and GC content variation.

---

## 2. Objectives

The objectives of this activity were to:

1. Generate a circular plastid genome map using OGDRAW.
2. Identify the LSC, SSC, IRa, and IRb regions.
3. Examine the distribution and orientation of annotated genes.
4. Identify major protein-coding genes, tRNA genes, and rRNA genes.
5. Observe GC content variation across the chloroplast genome.
6. Interpret the structural features shown in the circular genome map.
7. Document the visualization procedure, results, and interpretations in GitHub.

---

## 3. Genome Information and Data Source

The complete annotated chloroplast genome of Citrus sinensis was obtained from the National Center for Biotechnology Information (NCBI) RefSeq database.

### Table 1. General Characteristics of the Chloroplast Genome

| Characteristic | Information |
|---|---|
| Scientific Name | Citrus sinensis (L.) Osbeck |
| Common Name | Sweet Orange |
| Family | Rutaceae |
| NCBI Accession | NC_008334.1 |
| Database Source | NCBI RefSeq |
| Genome Type | Complete Chloroplast Genome |
| Genome Length | 160,129 bp |
| GC Content | 38.48% |
| Genome Organization | Quadripartite |
| Visualization Software | OGDRAW |

*NCBI Genome Record:*  
https://www.ncbi.nlm.nih.gov/nuccore/NC_008334.1

*Original Annotated GenBank File:*  
[Download GenBank File](data/Citrus_sinensis_NC_008334.1.gb)

The same chloroplast genome used in the previous plastid genome characterization activity was retained for this visualization exercise.

---

## 4. OGDRAW Visualization Procedure

The circular chloroplast genome map was generated using OrganellarGenomeDRAW (OGDRAW), an online tool for visualizing annotated organellar genomes.

*OGDRAW Website:*  
https://chlorobox.mpimp-golm.mpg.de/OGDraw.html

### Procedure

1. Opened the OGDRAW website.
2. Selected Standard mode for genome visualization.
3. Uploaded the annotated GenBank file of Citrus sinensis (NC_008334.1).
4. Used a circular-topology working copy of the genome because the original GenBank LOCUS field was designated as linear.
5. Selected Circular as the genome map type.
6. Selected Plastid as the sequence source.
7. Enabled automatic detection of inverted-repeat regions.
8. Selected the major gene and feature categories.
9. Enabled the GC content graph.
10. Enabled transcription direction indicators and the full legend.
11. Enabled asterisk labels for intron-containing genes.
12. Selected PNG as the output format and superfine resolution.
13. Submitted the visualization job and downloaded the generated circular genome map.

The original GenBank file was preserved without modification. The working copy used for OGDRAW differed only in its topology metadata, allowing the genome to be displayed in circular form.

### Table 2. OGDRAW Visualization Settings

| Parameter | Selected Setting |
|---|---|
| Mode | Standard |
| Genome Map Type | Circular |
| Sequence Source | Plastid |
| Inverted Repeat Detection | Auto |
| Gene and Feature Categories | Enabled |
| GC Content Graph | Enabled |
| Direction of Transcription | Enabled |
| Full Legend | Enabled |
| Intron-Containing Gene Labels | Enabled |
| Output Format | PNG |
| Resolution | Superfine |

---

## 5. Circular Plastid Genome Map

### Figure 1. Circular Chloroplast Genome Map of Citrus sinensis

![Circular Plastid Genome Map of Citrus sinensis](figures/Citrus_sinensis_plastid_map.png)

*Figure 1. Circular Chloroplast Genome Map of _Citrus sinensis_ (NC_008334.1).* The map was generated using OrganellarGenomeDRAW (OGDRAW) and illustrates the organization of the 160,129-bp chloroplast genome. It shows the Large Single-Copy (LSC) region, Small Single-Copy (SSC) region, and two Inverted Repeat regions (IRa and IRb). Genes are color-coded according to their functional categories, and their positions indicate their distribution and orientation along the genome. The inner graph represents GC content variation, while the legend identifies the major gene groups.

---

## 6. Plastid Genome Structural Organization

The circular chloroplast genome map of Citrus sinensis shows the typical quadripartite organization found in many flowering plants.

### Table 3. Major Structural Regions

| Genome Region | Size (bp) |
|---|---:|
| Large Single-Copy (LSC) | 87,744 |
| Small Single-Copy (SSC) | 18,393 |
| Inverted Repeat A (IRa) | 26,996 |
| Inverted Repeat B (IRb) | 26,996 |
| *Total Genome Length* | *160,129* |

### Structural Interpretation

The LSC region occupies the largest portion of the circular genome map and is positioned toward the upper section of the figure. The SSC region is located at the lower portion, while the two inverted-repeat regions flank the SSC, with IRa on the lower-right side and IRb on the lower-left side.

The inverted repeats contain duplicated genes, including ribosomal RNA genes and several ribosomal protein genes. This arrangement is characteristic of many angiosperm chloroplast genomes and contributes to their conserved genomic organization.

---

## 7. Gene Distribution and Functional Organization

The circular plastid genome map displays several functional categories of annotated genes.

### Major Gene Groups

| Gene Group | Examples | Biological Function |
|---|---|---|
| Photosystem I | psaA, psaB | Photosynthetic electron transport |
| Photosystem II | psbA, psbB | Light-dependent reactions |
| ATP Synthase | atpA, atpB | ATP production |
| Cytochrome b6f | petA, petB | Electron transport between photosystems |
| Carbon Fixation | rbcL | Carbon dioxide fixation |
| RNA Polymerase | rpoA, rpoB | Plastid gene transcription |
| Ribosomal Proteins | rpl2, rps12 | Protein synthesis |
| Transfer RNA | trnH, trnK | Amino acid transport during translation |
| Ribosomal RNA | rrn16, rrn23 | Ribosome structure and function |
| Other Plastid Genes | matK, clpP | RNA processing and protein maintenance |

### Interpretation

The annotated genes are distributed throughout the chloroplast genome and are grouped according to their biological functions. Photosynthesis-related genes participate in the light-dependent reactions and carbon fixation, while other genes support transcription, translation, and protein maintenance.

The map also shows that genes occur on both DNA strands. Their orientations indicate the direction of transcription, demonstrating that genes can be transcribed in different directions along the circular genome.

---

## 8. GC Content Distribution

The OGDRAW map includes an inner GC content graph showing variation in nucleotide composition across the chloroplast genome.

The genome has an overall GC content of *38.48%*, as previously determined using Galaxy gfastats analysis.

### Interpretation

The GC content graph shows slight variations across different regions of the chloroplast genome rather than a completely uniform pattern. These differences reflect changes in the relative proportions of guanine and cytosine bases along the DNA sequence.

Although these variations are visible, the genome map alone does not establish their specific biological significance.

---

## 9. Overall Interpretation

The circular plastid genome map of Citrus sinensis provides a visual representation of its structural and functional organization. The genome consists of four major regions: the LSC, SSC, IRa, and IRb. These regions form the typical quadripartite structure characteristic of many flowering-plant chloroplast genomes.

The map also illustrates the distribution of protein-coding genes, transfer RNA genes, and ribosomal RNA genes. Several genes are duplicated within the inverted-repeat regions, while the direction of gene orientation indicates transcription from different DNA strands.

Furthermore, the GC content graph shows differences in nucleotide composition across the genome. Overall, the OGDRAW visualization makes it easier to understand the organization, distribution, and orientation of chloroplast genes compared with examining raw DNA sequences or lengthy annotation tables.

---

## 10. Laboratory Questions and Answers

All ten questions from Part E of the laboratory manual were answered using the circular genome map, corresponding GenBank annotations, and previously obtained genome information.

The answers include:

- Scientific name and accession number
- Complete plastid genome length
- LSC, SSC, IRa, and IRb regions
- Examples of genes in the LSC and SSC regions
- Duplicated genes in inverted-repeat regions
- Photosynthesis-related genes and functions
- Direction of transcription
- GC content variation
- Importance of graphical plastid genome visualization

*[View Complete Laboratory Questions and Answers](answers/Lab_plastid_genome_answers.md)*

---

## 11. Data and Figure Files

The following files are provided in this repository:

*Annotated GenBank File:*  
[data/Citrus_sinensis_NC_008334.1.gb](data/Citrus_sinensis_NC_008334.1.gb)

*Circular Plastid Genome Map:*  
[figures/Citrus_sinensis_plastid_map.png](figures/Citrus_sinensis_plastid_map.png)

*Laboratory Questions and Answers:*  
[answers/Lab_plastid_genome_answers.md](answers/Lab_plastid_genome_answers.md)

---

## 12. Reproducibility

This activity can be reproduced by obtaining the complete annotated chloroplast genome of Citrus sinensis from NCBI using accession NC_008334.1.

The GenBank file can be uploaded to OGDRAW using Standard mode. If the original file is interpreted as linear, its topology metadata can be changed to circular in a separate working copy while preserving the original sequence and annotations.

The circular genome option, automatic inverted-repeat detection, GC content graph, transcription direction, full legend, and intron-containing gene labels should be enabled. The final map can then be generated in PNG format and compared with the visualization documented in this repository.

---

## 13. Conclusion

The OGDRAW visualization successfully illustrated the circular chloroplast genome structure of Citrus sinensis, measuring 160,129 bp. The generated map displayed the typical quadripartite organization consisting of the LSC, SSC, and two inverted-repeat regions.

The map also revealed the distribution and orientation of genes involved in photosynthesis, transcription, translation, and other plastid functions. Duplicated genes within the inverted repeats and variations in GC content provided additional information about the structural organization of the plastome.

Overall, this activity demonstrated the usefulness of graphical genome visualization in understanding the organization and functional features of chloroplast DNA. OGDRAW provided a clear representation of genomic information that would be more difficult to interpret using only raw DNA sequences or GenBank annotation lists.

---

## 14. References

1. National Center for Biotechnology Information (NCBI). Citrus sinensis chloroplast, complete genome. RefSeq NC_008334.1.  
   https://www.ncbi.nlm.nih.gov/nuccore/NC_008334.1

2. Bausher, M. G., Singh, N. D., Lee, S. B., Jansen, R. K., & Daniell, H. (2006). The complete chloroplast genome sequence of Citrus sinensis (L.) Osbeck var 'Ridge Pineapple': Organization and phylogenetic relationships to other angiosperms. BMC Plant Biology, 6, 21.  
https://link.springer.com/article/10.1186/1471-2229-6-21

3. Greiner, S., Lehwark, P., & Bock, R. (2019). OrganellarGenomeDRAW (OGDRAW) version 1.3.1: Expanded toolkit for the graphical visualization of organellar genomes. Nucleic Acids Research, 47, W59–W64.

4. OrganellarGenomeDRAW (OGDRAW). CHLOROBOX, Max Planck Institute of Molecular Plant Physiology.  
   https://chlorobox.mpimp-golm.mpg.de/OGDraw.html
