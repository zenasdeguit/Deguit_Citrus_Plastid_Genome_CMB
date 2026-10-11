# Plastid Genome Characterization of Citrus sinensis

## 1. General Genome Information

The complete chloroplast genome of *Citrus sinensis* (sweet orange) was retrieved from NCBI RefSeq under accession NC_008334.1. The genome sequence was analyzed using the gfastats tool in Galaxy, while gene annotations were examined using the corresponding GenBank file.

### Table 1. General Characteristics of the Chloroplast Genome

| Characteristic | Result |
|---|---|
| Genus | *Citrus* |
| Species | *Citrus sinensis* |
| Common name | Sweet orange |
| Family | Rutaceae |
| Database | NCBI RefSeq |
| Accession/version | NC_008334.1 |
| Genome length | 160,129 bp |
| GC content | 38.48% |
| AT content | 61.52% |
| Genome organization | Quadripartite |
| Topology in GenBank LOCUS | Linear |
| Number of sequence records | 1 |
| Number of scaffolds | 1 |
| Number of contigs | 1 |
| Number of assembly gaps | 0 |
| Scaffold N50 | 160,129 bp |

**Interpretation:**

The chloroplast genome of *Citrus sinensis* consists of a single continuous sequence measuring 160,129 bp, with a GC content of 38.48%. Galaxy gfastats analysis identified one scaffold and one contig without reported assembly gaps. The genome contains more adenine and thymine bases than guanine and cytosine bases, indicating an AT-rich nucleotide composition.

Although the NCBI LOCUS field describes the reference sequence as linear, the published study describes the chloroplast genome using the typical quadripartite organization of flowering-plant plastomes.

---

## 2. Plastid Genome Organization

The *Citrus sinensis* chloroplast genome contains four major regions: the Large Single-Copy (LSC) region, Small Single-Copy (SSC) region, and two Inverted Repeat regions (IRa and IRb).

### Table 2. Chloroplast Genome Regions

| Genome Region | Size (bp) |
|---|---:|
| Large Single-Copy (LSC) | 87,744 |
| Small Single-Copy (SSC) | 18,393 |
| Inverted Repeat A (IRa) | 26,996 |
| Inverted Repeat B (IRb) | 26,996 |
| **Total Genome Length** | **160,129** |

**Interpretation:**

The *Citrus sinensis* chloroplast genome exhibits the typical LSC–IR–SSC–IR organization. The LSC region is the largest, followed by the two inverted-repeat regions and the SSC region. The inverted repeats contain duplicated genes, including ribosomal RNA genes, which contribute to the organization and gene content of the plastid genome.

The region sizes were obtained from the published chloroplast genome study by Bausher et al. (2006).

---

## 3. Annotated Gene Content

The original study reported 133 genes in the *Citrus sinensis* chloroplast genome, including protein-coding genes, tRNA genes, and rRNA genes.

### Table 3. Published Gene Inventory

| Gene Category | Reported Number |
|---|---:|
| Total annotated genes | 133 |
| Protein-coding genes | 89 |
| Distinct tRNA genes | 30 |
| Distinct rRNA genes | 4 |
| Genes containing introns | 17 |

**Annotation Note:**

The uploaded NCBI RefSeq GenBank file contains 140 `gene` feature entries, 87 CDS entries, 45 tRNA entries, and 8 rRNA entries. These are counts of the current annotation features rather than counts of unique genes.

The published study and current annotations use different gene-counting conventions. Duplicated genes and separately annotated RNA segments can affect the counts. Therefore, the published gene inventory and the current GenBank feature counts are reported separately.

---

## 4. Important Protein-Coding Genes

The chloroplast genome contains genes associated with photosynthesis, ATP production, gene expression, and other cellular processes.

### Table 4. Selected Protein-Coding Genes and Their Functions

| Gene | Functional Group | Biological Function |
|---|---|---|
| psaA | Photosystem I | Encodes a core reaction-center protein involved in photosynthetic electron transport. |
| psbA | Photosystem II | Encodes the D1 reaction-center protein involved in light-dependent electron transport. |
| atpA | ATP synthase | Encodes a subunit involved in ATP production during photophosphorylation. |
| petA | Cytochrome b6f complex | Encodes cytochrome f, which participates in electron transport between photosystems. |
| rbcL | Carbon fixation | Encodes the large subunit of RuBisCO, which catalyzes carbon dioxide fixation. |
| rpoA | RNA polymerase | Encodes a subunit of the plastid RNA polymerase involved in transcription. |
| rpl2 | Ribosomal protein | Encodes a protein component of the large ribosomal subunit. |
| rps12 | Ribosomal protein | Encodes a protein component of the small ribosomal subunit. |
| matK | RNA processing | Encodes a maturase associated with the splicing of group II introns. |
| clpP | Protein maintenance | Encodes a protease subunit involved in protein degradation. |
| ndhA | Electron transport | Encodes a component of the chloroplast NADH dehydrogenase-like complex. |

**Interpretation:**

The annotated protein-coding genes demonstrate that the *Citrus sinensis* chloroplast genome supports several essential cellular functions. Photosystem genes participate in light-dependent reactions, ATP synthase genes contribute to energy production, and rbcL is involved in carbon fixation. Other genes support transcription, translation, protein maintenance, and RNA processing within the chloroplast.

---

## 5. Ribosomal RNA and Transfer RNA Genes

The chloroplast genome contains genes encoding RNA molecules essential for protein synthesis.

### Ribosomal RNA Genes

Four distinct rRNA types are present:

1. 16S rRNA
2. 23S rRNA
3. 4.5S rRNA
4. 5S rRNA

These rRNAs form structural and functional components of plastid ribosomes. Each type is represented in both inverted-repeat regions, resulting in eight rRNA feature entries in the current GenBank annotation.

### Examples of Transfer RNA Genes

| tRNA Gene | Function |
|---|---|
| trnH-GUG | Encodes a tRNA for histidine. |
| trnK-UUU | Encodes a tRNA for lysine. |
| trnL-UAA | Encodes a tRNA for leucine. |
| trnM-CAU | Encodes a tRNA for methionine. |
| trnF-GAA | Encodes a tRNA for phenylalanine. |

**Interpretation:**

The tRNA and rRNA genes contribute to protein synthesis within chloroplasts. Transfer RNAs deliver amino acids during translation, while ribosomal RNAs form important components of plastid ribosomes. Together, these RNA molecules support the expression of chloroplast-encoded proteins.

---

## 6. Introns and RNA Processing

The *Citrus sinensis* chloroplast genome contains genes with introns, which must be removed from RNA transcripts during RNA processing.

### Table 5. Examples of Intron-Containing Genes

| Gene | Number of Introns |
|---|---:|
| atpF | 1 |
| rpoC1 | 1 |
| rps16 | 1 |
| ndhA | 1 |
| ndhB | 1 |
| petB | 1 |
| clpP | 2 |
| ycf3 | 2 |
| rps12 | 2 |

**Interpretation:**

Several chloroplast genes contain introns that require RNA splicing before functional gene products can be produced. The genes clpP, ycf3, and rps12 contain two introns, while several others contain one. The rps12 gene is particularly notable because its transcript undergoes trans-splicing, involving RNA segments encoded at separate genomic positions.

---

## 7. Pseudogenes, Duplications, and Other Notable Features

### Gene Duplications

The chloroplast genome contains duplicated genes within the inverted-repeat regions.

Examples include:

- rps19
- rpl2
- rpl23
- ycf2
- ndhB
- rps7
- rRNA genes

These duplicated regions contribute to the conserved organization of the chloroplast genome.

### Gene Loss

The original study reported the absence of the infA gene, which encodes a translation initiation factor in some other plant chloroplast genomes.

### Unusual rpl22 Feature

The published study identified an rpl22 copy in the IRb region containing premature stop codons. This indicates disruption of the normal protein-coding sequence and is consistent with loss of function.

However, the current GenBank annotation does not explicitly label this feature as a pseudogene.

**Interpretation:**

The chloroplast genome of *Citrus sinensis* contains notable structural and functional features, including gene duplications, intron-containing genes, and the reported absence of infA. The unusual rpl22 copy also demonstrates that duplicated genes may undergo sequence changes that affect their normal function.

---

## 8. Galaxy Sequence Statistics

The FASTA sequence of the complete chloroplast genome was uploaded to Galaxy and analyzed using gfastats.

**Galaxy History Name:** Plastid_Citrus_Deguit

**Tool Used:** gfastats

### Table 6. Galaxy gfastats Results

| Parameter | Result |
|---|---:|
| Number of scaffolds | 1 |
| Total scaffold length | 160,129 bp |
| Average scaffold length | 160,129 bp |
| Scaffold N50 | 160,129 bp |
| Number of contigs | 1 |
| Total contig length | 160,129 bp |
| Contig N50 | 160,129 bp |
| Number of gaps | 0 |
| Adenine (A) | 48,780 |
| Cytosine (C) | 31,405 |
| Guanine (G) | 30,216 |
| Thymine (T) | 49,728 |
| GC content | 38.48% |

**Interpretation:**

The gfastats analysis confirmed that the *Citrus sinensis* chloroplast genome consists of one continuous sequence measuring 160,129 bp. The absence of assembly gaps and the presence of a single contig are consistent with the complete genome record retrieved from NCBI. The GC content of 38.48% indicates that adenine and thymine are more abundant than guanine and cytosine.

---

## 9. Summary

The plastid genome characterization of *Citrus sinensis* revealed a complete chloroplast genome measuring 160,129 bp, with a GC content of 38.48%. Its organization consists of a large single-copy region, a small single-copy region, and two inverted repeats.

The genome contains genes involved in photosynthesis, ATP synthesis, carbon fixation, transcription, translation, and RNA processing. Several genes contain introns, while duplicated genes occur within the inverted-repeat regions.

Overall, the findings demonstrate the characteristic genome organization and functional gene content of a flowering-plant chloroplast genome. The combination of NCBI annotations, published genome information, and Galaxy sequence statistics provided a comprehensive characterization of the *Citrus sinensis* plastome.

---

## References

1. National Center for Biotechnology Information. *Citrus sinensis* chloroplast, complete genome. RefSeq NC_008334.1.  
   https://www.ncbi.nlm.nih.gov/nuccore/NC_008334.1

2. Bausher, M. G., Singh, N. D., Lee, S. B., Jansen, R. K., & Daniell, H. (2006). The complete chloroplast genome sequence of Citrus sinensis (L.) Osbeck var 'Ridge Pineapple': Organization and phylogenetic relationships to other angiosperms. *BMC Plant Biology, 6*, 21.  
  https://link.springer.com/article/10.1186/1471-2229-6-21

3. Galaxy Project. Galaxy Main.  
   https://usegalaxy.org/
