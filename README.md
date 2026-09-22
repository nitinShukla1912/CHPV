# Chandipura virus outbreak 2026 genomic surveillance in Gujarat, India

This repository contains a Nextstrain dataset developed to explore the genomic epidemiology of Chandipura virus (CHPV), with a focus on viruses detected during the 2026 acute encephalitis syndrome (AES) outbreak in Gujarat, India.

The interactive Nextstrain build allows researchers to examine the phylogenetic relationships, temporal distribution, geographic distribution, and genomic variation of CHPV sequences in the context of previously reported viruses.

## Interactive Nextstrain build

The dataset can be explored through Nextstrain Community:

**https://nextstrain.org/community/nitinShukla1912/CHPV**

The visualization provides an interactive view of:

- phylogenetic relationships among CHPV genomes
- viruses detected during the 2026 outbreak
- comparison with previously reported CHPV genomes
- sampling dates and geographic locations
- nucleotide and amino-acid changes
- genomic divergence among circulating viruses

## Background

Chandipura virus is a negative-sense single-stranded RNA virus belonging to the family *Rhabdoviridae* and genus *Vesiculovirus*. CHPV is associated with acute encephalitis syndrome, particularly among children, and has caused several outbreaks in India.

Major outbreaks have previously been reported during 2003–2004, followed by a large outbreak in Gujarat in 2024. CHPV was again detected among AES cases during 2026.

This project was developed to place the 2026 CHPV genomes within the broader genomic context of previously reported CHPV sequences and to examine whether the viruses detected during the current outbreak show evidence of continued circulation and genomic diversification.

## Study focus

The current analysis primarily focuses on CHPV genomes generated from clinical AES cases detected during the 2026 outbreak.

The genomic analysis includes comparison with previously reported CHPV genomes, including the 2024 outbreak sequence: `PQ185534.2` and the reference genome: `NC_020805.1`

The analysis is intended to help investigate:

1. the phylogenetic placement of the 2026 CHPV genomes;
2. their relationship with viruses reported during previous outbreaks;
3. genomic diversity within the 2026 outbreak;
4. nucleotide and amino-acid substitutions present in circulating viruses; and
5. the geographic and temporal distribution of detected CHPV genomes.

## Dataset

The Nextstrain visualization is generated from CHPV genome sequences together with associated metadata.

The current dataset includes genomes from the 2026 AES outbreak and selected publicly available CHPV sequences representing previous outbreaks and historical circulation.

Metadata used in the build include:

- sample identifier
- collection date
- year
- district
- state
- country
- patient age
- patient sex
- genomic lineage or phylogenetic grouping where applicable

## Genomic analysis

The analysis includes multiple complementary approaches.

### Pairwise SNP analysis

Pairwise single-nucleotide polymorphism distances were calculated using `snp-dists`.

This analysis was used to compare the 2026 CHPV genomes with previously reported viruses, including the 2024 outbreak genome `PQ185534.2`.

The SNP analysis provides a quantitative measure of genomic divergence between sequences but should be interpreted together with phylogenetic relationships, genome completeness, and sequence quality.

### Mutation analysis

High-confidence nucleotide variants were identified from reference-based sequencing data.

Mutations were evaluated relative to the CHPV reference genome `NC_020805.1`.

The analysis includes:

- synonymous substitutions
- nonsynonymous substitutions
- non-coding mutations
- amino-acid changes in the N, P, M, G, and L proteins

High-frequency mutations can also be examined to identify substitutions shared across most 2026 outbreak genomes.

## CHPV genome organization

The approximately 11 kb CHPV genome contains five major protein-coding genes:

| Gene | Protein |
|------|---------|
| N | Nucleocapsid protein |
| P | Phosphoprotein |
| M | Matrix protein |
| G | Glycoprotein |
| L | Large RNA-dependent RNA polymerase protein |

The genome also contains 5′ and 3′ untranslated regions.

## Repository structure

The repository is organized as follows:

```text
CHPV/
├── README.md
└── auspice/
    └── CHPV.json
