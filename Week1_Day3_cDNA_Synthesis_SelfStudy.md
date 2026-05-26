# Day 2 — cDNA Synthesis (Self-Study Notes)
**Date:** 01 May 2026  
**Type:** Self-directed conceptual study  
**Institution:** ICMR-NJIL&OMD, Agra

## Objective
Understand the molecular mechanism behind cDNA synthesis 
and how it connects to RT-PCR and downstream applications.

## Conceptual Summary

### What is cDNA?
cDNA (complementary DNA) is synthesised from mRNA using 
the enzyme **Reverse Transcriptase**. Unlike genomic DNA, 
cDNA contains only exon sequences — introns are absent 
because mRNA has already been spliced.

### Role of dNTPs
dNTPs (dATP, dTTP, dGTP, dCTP) are the DNA building 
blocks. PCR uses these to amplify and build new DNA 
strands from the cDNA template.

### Step-by-Step Mechanism

**Step 1 — First-strand synthesis:**  
Reverse Transcriptase binds mRNA using either an 
oligo(dT) primer (complementary to the poly-A tail) 
or random hexamers. It synthesises a complementary 
DNA strand, producing an RNA:cDNA hybrid.

**Step 2 — RNA strand nicking (RNase H activity):**  
RNase H introduces nicks in the RNA strand of the 
hybrid. This exposes 3'-OH groups that serve as 
priming sites for second-strand synthesis.

**Step 3 — Second-strand synthesis (DNA Pol I):**  
DNA Polymerase I uses its 5'→3' activity to replace 
the nicked RNA fragments with DNA, using the first 
cDNA strand as template.

**Step 4 — Ligation (DNA Ligase):**  
DNA Ligase seals the remaining nicks by catalysing 
the formation of phosphodiester bonds, producing 
double-stranded cDNA (ds cDNA).

## Key Enzymes Summary

| Enzyme | Function |
|---|---|
| Reverse Transcriptase | RNA → first-strand cDNA |
| RNase H | Nicks RNA in RNA:DNA hybrid |
| DNA Polymerase I | Replaces RNA nicks with DNA (5'→3') |
| DNA Ligase | Seals nicks; forms phosphodiester bonds |

## Connection to PhD Research
Understanding this mechanism is essential for designing 
accurate RT-qPCR experiments. In my proposed HsfA1 
study, primer specificity for individual wheat subgenomes 
(A, B, D) depends on cDNA derived exclusively from 
mRNA — making the exon-only nature of cDNA critically 
important for avoiding genomic DNA contamination.
