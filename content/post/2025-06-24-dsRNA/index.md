---
title: dsRNA structure
summary: dsRNA
date: 2025-06-25

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

## dsRNA sensors [^3]
### The RIG-I like receptors
In humans, RIG-I like receptors are: RIG-I, MDA5, and LGP2 (encoded by *RIGI*, *IFIH1*, and *DHX58*). Binding of either RIG-I or MDA5 to dsRNA drives the induction of IFN signaling through the activation of MAVS. 
RIG-I recognizes blunt dsRNA (no hangover) with 5' di- or triphosphate (rare) which allows self and non-self discrimination. 
MDA5 is length-dependent but no discrimination of self or non-self dsRNA. But this is often prevented by ADAR A-to-I RNA editing endogenous dsRNA.
While LGP2 lacks the N-terminal caspase activations and recruiment domain (CARDs) and cannot directly induce signaling. 

### PKR
PKR is encoded by *EIF2AK2*, it binds to dsRNA via two dsRNA-binding domains. Sequence non-specific, often >30 bp. The primary substrate of PKR is the translation initiation factor eIF2α (encoded by EIF2S1). PKR's primary function is to inhibit protein synthesis by phosphorylation the eukaryotic initiation factor eIF2α, thus prevent viral replication. 



**Reference**:
[^1]: https://en.wikipedia.org/wiki/Double-stranded_RNA
[^2]: Hur S. Double-Stranded RNA Sensors and Modulators in Innate Immunity. Annu Rev Immunol. 2019 Apr 26;37:349-375. doi: 10.1146/annurev-immunol-042718-041356. Epub 2019 Jan 23. PMID: 30673536; PMCID: PMC7136661.
[^3]: Cottrell, Kyle A. et al. The competitive landscape of the dsRNA world. Molecular Cell, Volume 84, Issue 1, 107 - 119