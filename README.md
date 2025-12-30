# Bioinformatics Analysis of Blood Isolates of *Klebsiella pneumoniae* Using Kleborate​

**Aim**
To dentify and quantify the prevalence of the most common Klebsiella pneumoniae strains across a blood isolates dataset.​

**Bioinformatics Team Objectives**
* Standardize a rapid, reproducible pipeline for K.p analysis.​
* Produce consistent outputs: such as species ID, virulence score, AMR score..etc​
* Enable quick turnaround for infection control units and translational teams.
  ​
**Pipeline Overview​**
  1. FASTQ QC & Trimming >> FastQC+Trimmomatic
  2. Genome Assembly >> SPAdes​
  3. FastA QC Check >> Quast
  4. Prevalence of K. pneumoniae [Genotyping]​ >> Kleborate
  5. Visualizations & Reporting
     
**Assembly Metrics & Definitions**
1. *N50*: length at which 50% of the genome is contained in contigs of this length or longer.​
2. *L50*: minimum number of contigs whose length sum makes up half of the assembly
size.​
>> Example: N50 ≈ 200 kb, total length ~5.66 Mbp, L50 = 8

**To Read & Refrances**
1. https://github.com/klebgenomics/Kleborate
2. https://www.nature.com/articles/s41467-021-24448-3
3. https://kleborate.readthedocs.io/en/latest/
4. https://bio.tools/kleborate ​
