# A-pipeline-for-markers-selection-using-Restriction-site-Associated-DNA-sequencing-RAD-Seq
Master_thesis Project  

{Abstract}

The discovery and assessment of genetic variants for Next Generation Sequencing (NGS), including Restriction site Associated DNA sequencing (RAD-Seq), is an important task in bioinformatics and comparative genetics. The genetic variants can be single-nucleotide polymorphisms (SNPs), insertions and deletions (Indels) when compared to a reference genome. Usually, the short reads are aligned to a reference genome at first using NGS alignment software such as the Burrows- Wheeler Aligner (BWA). The alignment is usually stored into a BAM file, a binary format of standard SAM (Sequence Alignment/Map) protocol. Then analysis software, such as Genome analysis Toolkit (GATK) or SAMTools, together with scripts written in R programming language, could provide an efficient solution for calling variants.  

In this project, we focused on RAD-Seq-based marker selection for {Arabidopsis thaliana}. RAD-Seq consists short reads, which do not cover the whole reference genome. In order to obtain four call-sets of SNPs as output in Variant Call Format (VCF), SNPs have been called by using GATK or SAMTools. Then, VCF files have been visualized by using Integrative Genomics Viewer (IGV) software. We found that the visualization of SNPs and Indels is very helpful and provides us with valuable insights on marker selection. We found that applying Chi-Square test for all target genotypes, such as homozygous reference 0/0, heterozygous variants 0/1 and homozygous variants 1/1, to test Hardy-Weinberg Equilibrium (HWE) to reduce false positive rate significantly. We showed that our pipeline is efficient in RAD-Seq-based marker selection.

{Keywords:} NGS, RAD-Seq, discovery calling variants, {Arabidopsis thaliana} TAIR10, GATK, SAMTools, Chi-Square test, P-HWE, reliable SNPs.
