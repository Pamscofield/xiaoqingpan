---
title: dsRNA structure
summary: dsRNA
date: 2025-06-24

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [****](https://en.wikipedia.org/wiki/Double-stranded_RNA#/media/File:Double-stranded_RNA.gif)'

authors:
  - admin

tags:
  - double-stranded RNA
  - double-stranded DNA
  - A-form
---

## What is dsRNA

[Wikipedia](https://en.wikipedia.org/wiki/Double-stranded_RNA)
Double-stranded RNA (dsRNA) is RNA with two complementary strands found in cells. It is similar to DNA but with the replacement of thymine by uracil and the adding of one oxygen atom. Despite the structural similarities, much less is known about dsRNA [^1].

## Why is dsRNA important
They form the genetic material of some viruses (double-stranded RNA viruses). dsRNA, such as viral RNA or siRNA, can trigger **RNA interference** in eukaryotes, as well as **interferon response** in vertebrates. In eukaryotes, dsRNA plays a role in the activation of the innate immune system against viral infections [^1].

## dsRNA structure [^2]
**A-dsRNA**
[Structure](structure.png)
From left to right: A-form DNA, B-form DNA, Z-form DNA. Image created by Richard Wheeler

| dsRNA | dsDNA |
| --- | --- |
| A-form helix | B-form helix |
| narrow major groove \n wide minor groove | wide major groove \n narrow minor groove |
| major groove for protein bindng | minor groove for protein binding |
| usually sequence specific | usually sequence independent and through RNA backbone, often recognized by ribose 2′-OH (2′-hydroxyl)  |
| short, less stable | long, stable |
| recognized by immune system through TLR9 | recognized by intracellular receptors like RIG-I and MDA5, TLR3 | 

*dsRNA is characterized by a small major groove.*

**Z-RNA [^3]**
[Z-RNA](Z-RNA.jpg)
In a paper published in the May 13th, 2021 issue of PLOS Genetics, a Z-RNA nanoswitch that regulates interferon immune responses is described. The switch, less than 5 nanometer in length, is based on sequences, called flipons, that change outcomes by altering their three dimensional conformation. The Z-RNA nanoswitch flips from the shorter right-handed A-RNA helix ("on") to the longer left-handed Z-RNA helix ("off"). The flip ends immune responses against self RNAs, but not against viruses. Surprisingly, the Z-RNA nanoswitch sequence is encoded by "junk DNA." The Z-RNA nanoswitch is used by some cancers to silence anti-tumor immune responses. In other cases, a malfunction of the Z-RNA nanoswitch causes inflammatory disease.


## dsRNA sensors [^4]
**he RIG-I like receptors**
In humans, RIG-I like receptors are: RIG-I, MDA5, and LGP2 (encoded by *RIGI*, *IFIH1*, and *DHX58*). Binding of either RIG-I or MDA5 to dsRNA drives the induction of IFN signaling through the activation of MAVS. 
RIG-I recognizes blunt dsRNA (no hangover) with 5' di- or triphosphate (rare and often on viral dsRNA) which allows self and non-self discrimination. 
MDA5 is length-dependent but no discrimination of self or non-self dsRNA. But this is often prevented by ADAR A-to-I RNA editing endogenous dsRNA.
While LGP2 lacks the N-terminal caspase activations and recruiment domain (CARDs) and cannot directly induce signaling. 

**PKR**
PKR is encoded by *EIF2AK2*, it binds to dsRNA via two dsRNA-binding domains. Sequence non-specific, often >30 bp. The primary substrate of PKR is the translation initiation factor eIF2α (encoded by EIF2S1). PKR's primary function is to inhibit protein synthesis by phosphorylation the eukaryotic initiation factor eIF2α, thus prevent viral replication. 

## What happens to endogenous dsRNA in the nucleus
### ADAR [^5]
**ADAR1**
Mutations in ADAR1 cause the interferonopathy Aicardi-Goutières syndrome (**AGS**). 
Two isoforms, p150 and p110 (differet promoters). p150 is responsible for the suppresion of dsRNA sensing by MDA5 and PKR. Both isoforms are induced to some extent by IFN signaling. p110 is responsible for most nuclear A-to-I RNA editing. But keep in mind that both isoforms of ADAR1 can shuttle to the nucleus and carry out editing.
The ZBD in ADAR1 negatively regulates ZBP1, another human protein with ZBD, which can trigger inflammatory responses.

**ADAR2**
ADAR2 is encoded by *ADARB1*. Largely expressed in the brain, and essential in mice (meaning that knocking out of ADAR2, mice die). -> Because in mice, ADAR2 edites *GRIA* mRNA, which encodes an AMPA glutamate receptor. CAG -> CIG // Gln -> Arg this is the only known essential recoding event in mice. 

**ADAR3**
Encoded by *ADARB2*. Unlike ADAR1 and ADAR2, ADAR3 has no catalytic activity and has the ability to bind **single-stranded RNA**. ADAR3 expression is largely confined to the brain, where it is involved in learning and memory. Recent work has revealed a role for ADAR3 in glioblastoma where it regulates A-to-I editing by ADAR1, MAVS protein expression, and NF-kB signaling. 

| p110 | p150 |
| nuclear | cytoplasm |
| introns | 3'UTR -> more likely to encounter MDA5 and PKR|
| one Z-DNA binding doman (ZBD): Z-beta | Z-alpha and Z-beta -> autoinflammatory diseases |



| ADAR1 | ADAR2 |
| --- | --- |
| frequently in repetitive regions | all regions |
| *Alu* | Q/R site in the GluR-B, pre-mRNA |
| more dependent on the presence of N7 in the edited base | can be influenced by the presence of loops and mismatches in the RNA structure |
| can bind to Z-RNA | - |

## A-to-I editing and suppression of innate immunity
- ADAR1-p150 suppresses MDA5 activation through A-to-I editing
- ADAR suppresses PKR which is editing-independent

## Export of dsRNA out of the nucleus

**Reference**:
[^1]: https://en.wikipedia.org/wiki/Double-stranded_RNA
[^2]: Hur S. Double-Stranded RNA Sensors and Modulators in Innate Immunity. Annu Rev Immunol. 2019 Apr 26;37:349-375. doi: 10.1146/annurev-immunol-042718-041356. Epub 2019 Jan 23. PMID: 30673536; PMCID: PMC7136661.
[^3]: https://medicalxpress.com/news/2021-05-z-rna-nanoswitch-encoded-junk-dna.html
[^4]: Cottrell, Kyle A. et al. The competitive landscape of the dsRNA world. Molecular Cell, Volume 84, Issue 1, 107 - 119
[^5]: Zambrano-Mila, M.S., Witzenberger, M., Rosenwasser, Z. et al. Dissecting the basis for differential substrate specificity of ADAR1 and ADAR2. Nat Commun 14, 8212 (2023). https://doi.org/10.1038/s41467-023-43633-0