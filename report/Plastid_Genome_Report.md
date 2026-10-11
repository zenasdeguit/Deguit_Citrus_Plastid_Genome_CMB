# Characterization of the Plastid Genome of Citrus sinensis

**Course:** Cell and Molecular Biology Laboratory  
**Genus:** *Citrus*  
**Selected Species:** *Citrus sinensis* (Sweet Orange)  
**Family:** Rutaceae  
**NCBI Accession:** NC_008334.1  
**Database:** NCBI RefSeq  
**Analysis Platform:** Galaxy (gfastats)

---

## 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Citrus sinensis* (L.) Osbeck, commonly known as sweet orange, belonging to the family Rutaceae. Its complete chloroplast genome was retrieved from the NCBI RefSeq database under accession NC_008334.1. The genome consists of 160,129 base pairs (bp), with a GC content of 38.48%, as confirmed through Galaxy gfastats analysis.

| Information | Result |
|---|---|
| Scientific name | *Citrus sinensis* (L.) Osbeck |
| Common name | Sweet orange |
| Family | Rutaceae |
| NCBI accession | NC_008334.1 |
| Database source | NCBI RefSeq |
| Complete genome size | 160,129 bp |
| GC content | 38.48% |

**NCBI Source:** https://www.ncbi.nlm.nih.gov/nuccore/NC_008334.1

---

## 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI RefSeq record identifies NC_008334.1 as the complete chloroplast genome of *Citrus sinensis*. Its annotation specifies the chloroplast as the source organelle and describes the sequence as full-length. Galaxy gfastats analysis confirmed that the genome consists of one continuous sequence measuring 160,129 bp, with no reported assembly gaps. Furthermore, the GenBank annotation contains numerous chloroplast genes associated with photosynthesis, transcription, translation, and other essential functions, demonstrating that the sequence represents a complete plastid genome rather than an individual barcode marker or genome fragment.

---

## 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

The *Citrus sinensis* chloroplast genome exhibits the typical quadripartite organization found in many flowering plants. It consists of a Large Single-Copy (LSC) region, a Small Single-Copy (SSC) region, and two Inverted Repeat regions (IRa and IRb). The inverted repeats separate the two single-copy regions and contain duplicated genes, including ribosomal RNA genes.

### Table 1. Organization of the Citrus sinensis Chloroplast Genome

| Region | Size (bp) |
|---|---:|
| Large Single-Copy (LSC) | 87,744 |
| Small Single-Copy (SSC) | 18,393 |
| Inverted Repeat A (IRa) | 26,996 |
| Inverted Repeat B (IRb) | 26,996 |
| **Total Genome Length** | **160,129** |

The genome follows the LSC–IR–SSC–IR arrangement, which is characteristic of many angiosperm chloroplast genomes. Although the NCBI LOCUS field represents the reference sequence as linear, the biological plastome is conventionally organized as a circular DNA molecule.

---

## 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The published *Citrus sinensis* chloroplast genome study identified 133 genes, including 89 protein-coding genes, four distinct ribosomal RNA genes, and 30 distinct transfer RNA genes. Some genes are duplicated within the inverted-repeat regions, resulting in additional gene copies.

### Table 2. Published Chloroplast Gene Content

| Gene Category | Number |
|---|---:|
| Total genes, including duplicated copies | 133 |
| Protein-coding genes, including duplicated copies | 89 |
| Distinct tRNA genes | 30 |
| Distinct rRNA genes | 4 |
| Genes containing introns | 17 |

The reported categories use different counting conventions, particularly for duplicated genes. Therefore, they should not be added together to calculate the total number of genes.

The current GenBank annotation contains 140 gene feature entries, which differs from the published gene inventory because of annotation and counting conventions.

The original study also reported an rpl22 copy in the IRb region containing premature stop codons, suggesting loss of normal protein-coding function. However, this sequence is not explicitly annotated as a pseudogene in the current GenBank record.

Genes located within the inverted-repeat regions may occur in two copies because the chloroplast genome contains two corresponding IR regions. This duplication explains why certain genes, including ribosomal RNA genes, appear more than once in the genome.

---

## 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

The *Citrus sinensis* chloroplast genome contains protein-coding genes involved in photosynthesis, carbon fixation, ATP production, transcription, translation, and other cellular processes.

### Table 3. Selected Plastid Protein-Coding Genes and Their Functions

| Gene | Functional Group | Biological Function |
|---|---|---|
| psaA | Photosystem I | Encodes a core protein involved in photosynthetic electron transport. |
| psbA | Photosystem II | Encodes the D1 reaction-center protein involved in light-dependent electron transport. |
| atpA | ATP synthase | Encodes a subunit involved in ATP production during photophosphorylation. |
| petA | Cytochrome b6f complex | Encodes cytochrome f, which participates in photosynthetic electron transport. |
| rbcL | Carbon fixation | Encodes the large subunit of RuBisCO, which catalyzes carbon dioxide fixation. |
| rpoA | RNA polymerase | Encodes a subunit of plastid RNA polymerase involved in transcription. |
| rpl2 | Ribosomal protein | Encodes a component of the large ribosomal subunit. |
| rps12 | Ribosomal protein | Encodes a component of the small ribosomal subunit. |
| matK | RNA processing | Encodes a maturase associated with intron splicing. |
| clpP | Protein maintenance | Encodes a protease subunit involved in protein degradation. |

**Interpretation:**

These genes demonstrate the diverse functions supported by the chloroplast genome. Photosystem genes and the cytochrome b6f complex participate in light-dependent electron transport, while ATP synthase contributes to energy production. The rbcL gene is important for carbon fixation, whereas RNA polymerase and ribosomal protein genes support gene expression. Other genes, such as matK and clpP, contribute to RNA processing and protein maintenance.

---

## 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

The chloroplast genome of *Citrus sinensis* contains ribosomal RNA (rRNA) and transfer RNA (tRNA) genes that are essential for protein synthesis. The rRNA genes contribute to the structure and function of plastid ribosomes, while tRNA genes encode molecules that deliver amino acids during translation.

### Table 4. Ribosomal RNA Genes

| rRNA Gene | Function |
|---|---|
| 16S rRNA | Forms part of the small ribosomal subunit. |
| 23S rRNA | Forms part of the large ribosomal subunit and participates in peptide bond formation. |
| 4.5S rRNA | Contributes to the structure and function of the large ribosomal subunit. |
| 5S rRNA | Provides structural support to the large ribosomal subunit. |

These four rRNA types are duplicated within the inverted-repeat regions, resulting in eight rRNA feature entries in the GenBank annotation.

### Table 5. Examples of Transfer RNA Genes

| tRNA Gene | Function |
|---|---|
| trnH-GUG | Encodes tRNA for histidine. |
| trnK-UUU | Encodes tRNA for lysine. |
| trnL-UAA | Encodes tRNA for leucine. |
| trnM-CAU | Encodes tRNA for methionine. |
| trnF-GAA | Encodes tRNA for phenylalanine. |

### Table 6. Examples of Intron-Containing Genes

| Gene | Number of Introns | Main Function |
|---|---:|---|
| atpF | 1 | ATP synthase subunit involved in ATP production. |
| rpoC1 | 1 | Plastid RNA polymerase subunit involved in transcription. |
| rps16 | 1 | Ribosomal protein involved in translation. |
| ndhA | 1 | Component of the chloroplast NDH complex. |
| ycf3 | 2 | Participates in Photosystem I assembly. |
| clpP | 2 | Protease subunit involved in protein maintenance. |
| rps12 | 2 | Ribosomal protein gene undergoing trans-splicing. |

**Interpretation:**

The presence of rRNA and tRNA genes demonstrates that chloroplasts possess part of the molecular machinery needed for protein synthesis. Several protein-coding genes also contain introns that must be removed during RNA processing. The rps12 gene is particularly notable because it undergoes trans-splicing, in which RNA segments originating from separate genomic locations are joined to produce a functional transcript.

---

## 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

The *Citrus sinensis* chloroplast genome contains several notable features involving gene duplications, gene loss, and structural changes.

**Gene Duplications**

The chloroplast genome contains two inverted-repeat regions that include duplicated genes, particularly ribosomal RNA genes and several ribosomal protein genes. The original study also reported an expansion of the inverted repeats that duplicated the rps19 gene and the first 84 amino acids of rpl22.

**Gene Loss**

The original study reported the absence of the infA gene, which normally encodes translation initiation factor 1 in some other chloroplast genomes. This represents a difference in gene content compared with plastid genomes that retain infA.

**Pseudogene-Related Feature**

The published study identified an rpl22 copy in the IRb region containing a nonsense mutation that resulted in nine premature stop codons. This suggests that the duplicated sequence has lost normal protein-coding function. However, the current GenBank annotation does not explicitly classify this feature as a pseudogene.

**Repeats and Other Features**

Bausher et al. (2006) identified 29 direct and inverted repeats of at least 30 bp with sequence identity of at least 90%. The study also reported six putative RNA-editing sites, including sites associated with petL, psbH, ycf2, and ndhA.

No major genome rearrangement was reported for this reference plastome compared with the typical angiosperm chloroplast genome organization.

**Interpretation:**

These findings demonstrate that although the *Citrus sinensis* chloroplast genome maintains a generally conserved organization, it also contains evolutionary changes. Gene duplications, the absence of infA, and the unusual rpl22 sequence illustrate how plastid genomes can undergo structural and functional modifications over time.

---

## 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The *Citrus sinensis* chloroplast genome has a GC content of **38.48%**, as determined using the gfastats tool in Galaxy.

### Table 7. Genome Base Composition

| Nucleotide | Number of Bases |
|---|---:|
| Adenine (A) | 48,780 |
| Cytosine (C) | 31,405 |
| Guanine (G) | 30,216 |
| Thymine (T) | 49,728 |
| **Total** | **160,129** |

The GC content indicates that guanine and cytosine account for 38.48% of the genome, while adenine and thymine account for approximately 61.52%. This shows that the chloroplast genome has an AT-rich nucleotide composition.

**First Notable Observation: Complete and Continuous Genome Sequence**

Galaxy gfastats analysis identified one scaffold and one contig, both measuring 160,129 bp, with no reported assembly gaps. The scaffold and contig N50 values were equal to the total genome length. These results are consistent with the complete chloroplast genome sequence obtained from NCBI.

**Second Notable Observation: Quadripartite Genome Organization**

The annotated chloroplast genome contains a Large Single-Copy region of 87,744 bp, a Small Single-Copy region of 18,393 bp, and two Inverted Repeat regions of 26,996 bp each. This organization is characteristic of many flowering-plant chloroplast genomes. The inverted-repeat regions contain duplicated genes, contributing to the structural organization of the plastome.

---

## 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

Plastid and mitochondrial genomes are both organellar genomes found in plant cells. Although they share several characteristics, they differ in their biological functions, genome organization, gene content, and evolutionary patterns.

### Similarities

1. Both plastids and mitochondria contain their own DNA, separate from the nuclear genome.
2. Both originated from bacterial ancestors through endosymbiosis.
3. Both genomes contain genes encoding proteins, transfer RNAs, and ribosomal RNAs.
4. Both are generally inherited uniparentally in flowering plants, most commonly through the maternal lineage.
5. Both can exist in multiple copies within a cell, and their DNA is organized into nucleoids.
6. Both require nuclear-encoded proteins for many aspects of their replication, gene expression, and maintenance.
7. Both genomes can undergo mutations, recombination, and evolutionary changes.

### Differences

1. Plastid genomes are located in plastids, whereas mitochondrial genomes are located in mitochondria.
2. Plastid genomes primarily encode components involved in photosynthesis and plastid gene expression, while mitochondrial genomes primarily encode components involved in cellular respiration and mitochondrial gene expression.
3. Chloroplast genomes of many flowering plants have a conserved quadripartite organization, whereas plant mitochondrial genomes frequently display more complex and variable structures.
4. Plastid genomes are generally smaller than mitochondrial genomes in flowering plants.
5. Plastid genomes contain photosystem, ATP synthase, and carbon-fixation genes, whereas mitochondrial genomes contain genes associated with respiratory electron transport and oxidative phosphorylation.
6. Plant mitochondrial genomes generally undergo more extensive structural rearrangements, while chloroplast genomes are often more structurally conserved.
7. In many flowering plants, mitochondrial protein-coding sequences have lower nucleotide substitution rates than plastid genes, despite mitochondrial genomes often showing greater structural variation.

**Interpretation:**

Plastid and mitochondrial genomes share an evolutionary origin through endosymbiosis and retain genetic systems that support essential cellular functions. However, they have become specialized for different metabolic processes. Their contrasting genome structures and evolutionary patterns make them useful for different types of genetic, evolutionary, and phylogenetic studies.

---

## 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

Plastid genomes are valuable in molecular biology, evolutionary biology, plant systematics, and conservation genetics because they provide relatively compact and informative genetic sequences. Their organization and inheritance patterns offer several advantages compared with the much larger nuclear genome.

### Advantages of Plastid Genomes

1. **Smaller genome size:** Plastid genomes are generally much smaller than nuclear genomes, making them easier and less expensive to sequence and analyze.

2. **Relatively conserved structure:** Many flowering-plant plastid genomes share a similar organization, allowing comparisons among related species.

3. **High copy number:** Plastid DNA is often present in multiple copies per cell, which can facilitate DNA recovery and sequencing.

4. **Useful for phylogenetic analysis:** Conserved genes and variable regions can help reconstruct evolutionary relationships among plant species.

5. **Useful for species identification:** Plastid markers such as rbcL and matK are widely used in plant DNA barcoding.

6. **Useful for phylogeography:** Plastid haplotypes can help investigate the geographic distribution and historical movement of maternal lineages in many flowering plants.

7. **Reduced sexual recombination:** Plastid genomes generally undergo less recombination through sexual reproduction than nuclear chromosomes, making many plastid haplotypes easier to trace across generations.

8. **Multiple genetic markers:** A complete plastid genome provides more sequence information than an individual barcode gene.

9. **Useful for conservation genetics:** Plastid sequences can help identify evolutionary lineages and investigate population history.

10. **Useful for comparative genomics:** Differences in gene content, inverted-repeat boundaries, and genome structure can provide information about plastid genome evolution.

11. **Useful for studying photosynthesis:** Plastid genomes encode proteins involved in photosynthetic electron transport, ATP production, and carbon fixation.

12. **Simpler inheritance patterns:** Predominantly uniparental inheritance can simplify some evolutionary analyses compared with biparentally inherited nuclear chromosomes.

13. **Avoidance of nuclear sex-chromosome complexity:** In species with nuclear sex chromosomes, plastid DNA generally follows a separate cytoplasmic inheritance pattern rather than the inheritance of nuclear sex-linked chromosomes.

### Limitations of Plastid Genomes

1. **Limited genetic information:** Plastid genomes represent only a small portion of the total genetic information of a plant.

2. **Incomplete representation of species history:** Plastid genomes often trace only one parental lineage and may not reflect the evolutionary history of the entire species.

3. **Limited resolution among closely related organisms:** Conserved plastid regions may contain insufficient variation to distinguish recently diverged species.

4. **Cannot directly explain most nuclear traits:** Many developmental, reproductive, and physiological characteristics are controlled primarily by nuclear genes.

5. **Cannot adequately investigate nuclear sex-linked inheritance:** Traits associated with nuclear sex chromosomes generally require nuclear genomic analysis.

6. **Limited information about hybridization:** Because plastid genomes are often inherited from one parent, they may not reveal the full genetic contribution of both parents.

7. **Exceptions to inheritance patterns:** Maternal inheritance is common but not universal. Paternal or biparental plastid inheritance can occur in some plant lineages.

8. **Potential discordance with nuclear phylogenies:** Hybridization, introgression, and incomplete lineage sorting can produce differences between plastid and nuclear evolutionary histories.

9. **Possible analytical complications:** Transfers of plastid DNA into the nuclear genome may complicate sequence identification if nuclear plastid sequences are mistaken for genuine plastid DNA.

10. **Restricted functional scope:** Plastid genome data alone cannot fully explain traits involving nuclear, mitochondrial, and environmental interactions.

### Example Research Question Suitable for Plastid Genome Data

**How are different Citrus species evolutionarily related based on their complete chloroplast genome sequences?**

Plastid genome data would be useful because conserved genes and variable genomic regions can be compared to reconstruct evolutionary relationships among Citrus species. This approach may reveal relationships among plastid lineages and provide information about their evolutionary history.

### Example Research Question More Suitable for Nuclear Genome Data

**Which nuclear genes control fruit sweetness and acidity in Citrus sinensis?**

Nuclear genome analysis would be more appropriate because fruit sweetness and acidity involve complex metabolic and regulatory pathways influenced by multiple nuclear genes. Genome-wide association studies and nuclear gene-expression analyses could help identify genetic factors contributing to these traits.

**Interpretation:**

Plastid genomes are useful for studying plant evolution, species identification, phylogenetic relationships, and the genetic basis of plastid functions. Their relatively small size and conserved organization make them practical for comparative molecular studies. However, their predominantly uniparental inheritance and limited gene content mean that nuclear genomic information is often necessary to obtain a more complete understanding of plant biology.

---

## Plastid vs. Mitochondrial Genome Comparison

### Table 8. Comparison of Plastid and Mitochondrial Genomes in Plants

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Located in plastids, including chloroplasts. | Located in mitochondria. |
| Main biological functions | Encodes components involved in photosynthesis, carbon fixation, and plastid gene expression. | Encodes components involved in cellular respiration, oxidative phosphorylation, and mitochondrial gene expression. |
| Typical genome organization | Often has a conserved quadripartite LSC–IR–SSC–IR organization in flowering plants. | Highly variable; may contain recombining circular, linear, or branched DNA forms. |
| Relative genome size | Usually smaller; Citrus sinensis has a 160,129-bp chloroplast genome. | Often larger in flowering plants, commonly hundreds of thousands to over a million base pairs, although sizes vary greatly. |
| Gene content | Contains photosystem, ATP synthase, carbon-fixation, ribosomal protein, rRNA, and tRNA genes. | Contains respiratory-chain, ATP synthase, ribosomal protein, rRNA, and tRNA genes, with substantial variation among lineages. |
| Copy number | Usually multiple plastid genome copies per cell; varies by tissue and developmental stage. | Usually multiple mitochondrial DNA copies per cell; varies by tissue and developmental stage. |
| Inheritance | Usually maternal in flowering plants, with exceptions. | Usually maternal in flowering plants, with exceptions. |
| Recombination / structural change | Generally more structurally conserved, although rearrangements and recombination can occur. | Frequently undergoes recombination-mediated rearrangements and structural changes. |
| Mutation / substitution pattern | Often has higher nucleotide substitution rates than plant mitochondrial genes, although rates vary by lineage. | Usually has relatively low nucleotide substitution rates in flowering plants despite extensive structural variation. |
| Common research applications | Plant identification, DNA barcoding, phylogenetics, phylogeography, comparative genomics, and photosynthesis studies. | Mitochondrial evolution, cytoplasmic male sterility, respiration, organellar inheritance, and comparative genomics. |

**Note:** The plastid information includes observations from the selected *Citrus sinensis* chloroplast genome. The mitochondrial characteristics summarize general patterns reported for land plants, particularly flowering plants, rather than measurements from a *Citrus sinensis* mitochondrial genome.

---

## Conclusion

The characterization of the *Citrus sinensis* chloroplast genome provided information about its sequence composition, genome organization, annotated genes, and biological functions. The complete plastid genome measured 160,129 bp and had a GC content of 38.48%, as confirmed through Galaxy gfastats analysis. The genome exhibited the typical quadripartite organization consisting of a Large Single-Copy region, a Small Single-Copy region, and two Inverted Repeat regions.

The annotated genome contained genes involved in photosynthesis, ATP production, carbon fixation, transcription, translation, and RNA processing. Additional features, including intron-containing genes, duplicated sequences, the absence of infA, and the unusual rpl22 copy, provided insight into plastid genome evolution.

Comparison with mitochondrial and nuclear genomes highlighted the distinctive organization, inheritance, and research applications of plastid DNA. Overall, the activity demonstrated how public genomic databases, annotated sequence records, and bioinformatics tools can be used to characterize a chloroplast genome and understand its biological and evolutionary significance.

---

## References

1. Bausher, M. G., Singh, N. D., Lee, S. B., Jansen, R. K., & Daniell, H. (2006). The complete chloroplast genome sequence of Citrus sinensis (L.) Osbeck var 'Ridge Pineapple': Organization and phylogenetic relationships to other angiosperms. *BMC Plant Biology, 6*, 21.  
  https://link.springer.com/article/10.1186/1471-2229-6-21

2. National Center for Biotechnology Information. (n.d.). *Citrus sinensis* chloroplast, complete genome (NC_008334.1). NCBI RefSeq.  
   https://www.ncbi.nlm.nih.gov/nuccore/NC_008334.1

3. Rose, R. J. (2019). Sustaining life: Maintaining chloroplasts and mitochondria and their genomes in plants. *Plants, 8*(9), 333.  
   https://www.mdpi.com/2223-7747/8/9/333

4. Smith, D. R., & Keeling, P. J. (2015). Mitochondrial and plastid genome architecture: Reoccurring themes, but significant differences at the extremes. *Proceedings of the National Academy of Sciences, 112*(33), 10177–10184.  
   https://pmc.ncbi.nlm.nih.gov/articles/PMC4547224/

5. Gualberto, J. M., & Newton, K. J. (2017). Plant mitochondrial genomes: Dynamics and mechanisms of mutation. *Annual Review of Plant Biology, 68*, 225–252.  
 https://www.annualreviews.org/content/journals/10.1146/annurev-arplant-043015-112232

6. Birky, C. W., Jr. (2001). The inheritance of genes in mitochondria and chloroplasts: Laws, mechanisms, and models. *Annual Review of Genetics, 35*, 125–148.  
 https://www.annualreviews.org/content/journals/10.1146/annurev.genet.35.102401.090231

7. Galaxy Project. (n.d.). Galaxy Main.  
   https://usegalaxy.org/

8. Galaxy Training Network. (n.d.). Galaxy training materials.  
   https://training.galaxyproject.org/
