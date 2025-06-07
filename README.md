# Cancer-Computational-Biology-Notes-And-Code_Review-And-Read-Ahead_2025

weekend/extra reviewing/studying
papers, code, notes on sequencing, SVs, databases, pipelines

# Solid tumors
<< a table of some sorts here >>

# Papers
tags: `#immunesignatures` `#rnaseq`
- [ ] [2020 - RNA Immune Signatures from Pan-Cancer Analysis Are Prognostic for High-Grade Serous Ovarian Cancer and Other Female Cancers](https://www.mdpi.com/2072-6694/12/3/620) `#immunesignatures` `#rnaseq`

# Definitions
* __Subclonal__ "In cancer, subclones are __distinct subpopulations of cells within a tumor__ that have different genetic and/or epigenetic characteristics, originating from a common ancestral cell. These subclones can develop through the accumulation of mutations and other changes as cancer cells evolve and adapt to their environment. Understanding subclones is crucial because they can influence tumor behavior, treatment response, and resistance."

* __Clonal Hematopoiesis (CH)__ "Clonal hematopoiesis (CH) happens when a cell called a hematopoietic stem cell, which can develop into different types of blood cells, starts making cells with the same genetic mutation. These blood cells have a different genetic pattern than the rest of your blood cells." [source](https://www.mskcc.org/cancer-care/types/leukemias/risk-factors/clonal-hematopoiesis-ch)

<!-- words that come up that i mostly know to define/look into **soon** like over the weekends?? making a dictionary for myself for the future -->

# 1. Mutation Types and Genomic Alterations

* Truncating mutation
* Frameshift mutations
* Missense
* Splice mutations/alteration
* In-frame deletion
* Inframe indel
* Amplification
* Deep deletion
* Rearrangement
* Fusion
* Tandem duplication
* Novel (splicing) event
* Cryptic (splicing) event
* Homdels

# 2. Functional Impact Assessment

* Functional effect (mutation does or does not have functional effect)
* Gain of function
* Loss of function (Does the gene tolerate loss of function mutation)
* Deleterious
* Protein stabilization
* Misregulation
* Ubiquitinated
* Driver alteration
* Exon skipping

# 3. Gene and Protein Classification

* Tumor suppressor
* Oncogene
* Oncoprotein
* Context dependent tumor suppressor activity
* Copy number driven genes
* Wild type allele
* Canonical marker genes of tumors
* Specific examples: TP53, MYC, CDKN2Ap14ARF, CDKN2Ap16INK4A

# 4. Experimental Methods and (Clinical) Validation

* ChIP-seq for validation when RNA-seq doesn't give enough information
* RNA-seq to see if alteration was expressed
* Model system in cell line (overexpress the function and mutant)
* Validating expression
* Knockout gene
* Candidate testing
* Long read sequencing (to validate fusions)

# 5. Clinical and Phenotypic Analysis

* Clinical phenotype
* Phenotypic difference
* Survival curve/survival analysis
* Histology
* Primary site
* Actionable targets/actionable mutations
* Cancer types: Sarcoma, Colorectal cancer (CRC)

# 6. Genomic Analysis Concepts

* Allelic expression (what is the other allele doing)
* LOH (Loss of Heterozygosity)
* HETLOSS
* CNLOH
* Clonal vs subclonal
* Biallelic
* MSI (Microsatellite Instability)
* TMB (Tumor Mutational Burden)
* Immune deconvolution
* Recurrent alteration
* Isoform
* Overexpression positivity

# 7. Cancer-centric Databases and Resources

* COSMIC
* OncoKB
* TCGA (associate with phenotype, additional cohorts)
* dbSNP
* gnomAD

# 8. Cancer Biology and Tumor Properties

* Canonical pathway
* Tumor microenvironment
* Cellular plasticity
* Tumor heterogeneity
* Resistance to apoptosis
* Immune evasion
* "It was a clonal event"

# 9. Data Interpretation and Analysis Patterns

* Mutually exclusive vs co-occurring patterns
* Misannotated mutation
* Lowly expressed genes are super variable
* N-terminal path
* Locus
* Basic scientist vs. clinician (perspectives)
* p.X_splice format at MSKCC

# Etc
* [2008 - On the Process of Becoming a Great Scientist](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0040033)

# Books (I'm Reading)
* `#BOC` - [The Biology of Cancer](https://wwnorton.com/books/9780393887655)
* `#GITC` - [Genomics in the Cloud](https://www.oreilly.com/library/view/genomics-in-the/9781491975183/)
* `#SEAG` - [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/)

<!--
# Things I've learned so far
* There's probably no such thing as a "dumb" or "simple" question in cancer, because cancer is so complicated, it turns out the answer is complicated anyway
* Cursing over bad data is completely okay 😂
* If IGV is being super slow during screen-sharing on Zoom, turning your camera off makes IGV run fast again

# Remote work hacks
* Literally taking a shower before work or during lunch is the best thing ever ... just makes everything better the whole day
* Nose canceling headphones because someone is always getting their lawn mowed in the morning/afternoon etc. every day
* BenQ ScreenBar Halo is the best table lamp ever
-->
