
Microsatellite genotype data for Atlantic Salmon (Salmo salar), Brown Trout (Salmo trutta), and two suspected hybrids of these two species, from the study "First documentation of a naturally produced Atlantic Salmon (Salmo salar) x Brown Trout (Salmo trutta) hybrid in a North American National Park". This file contains the final set of genotypes used to confirm hybrid status of one of the two suspected hybrid samples. Also included is a primer file containing sequence data for all loci included in downstream analyses. This file contains information needed to make primer input files for MEGASAT and SatAnalyzer. Finally, we have included a file that lists allele size and sequence differences between Atlantic Salmon and Brown Trout for each locus.


**Files and variables**

**File: Genepop_Panel46.txt**

Description: Genotypes for all samples examined, in genepop format.

Sample prefixes: CHE46 - confirmed hybrid parr, CHE47 - Brown Trout smolt with ambiguous phenotype, CLY - Atlantic Salmon sampled from Clyburn Brook, MAR - Brown Trout sampled from Margaree River


**File: primerfile.xlsx**

Sequence data for 46 microsatellite loci needed to construct primer input files in MEGASAT and SatAnalyzer/seq2sat. Note that some columns are only used for one program.

Locus: Locus names

Forward Primer (5'): Sequence of the forward primer

Reverse Primer (reverse complement of 3' primer): Sequence of the reverse primer, as it appears on the forward strand (so the reverse complement of the primer sequence that was ordered).

Forward Flanking Region: Sequence region between the microsatellite repeat array (MRA) and the forward primer. If there is no flanking region (i.e. the primer ends immediately before the beginning of the MRA) this cell is marked as 'X'.

Reverse Flanking Region: Sequence region between the MRA and the reverse primer. If there is no flanking region (i.e. the primer ends immediately before the beginning of the MRA) this cell is marked as 'X'.

Repeat Unit: Short sequence of nucleotide bases that are repeated inside the MRA

\# Repeats: Number of repeats in a reference sequence

MRA: Example sequence found inside the MRA taken from a reference sequence

Ratio: Ratio values used by MEGASAT to score genotypes, described in https://onlinelibrary.wiley.com/doi/10.1111/1755-0998.12561


**File: Microsat_Differences.xlsx**

File containing preliminary allele size ranges, heterozygosity, and mutation information for Atlantic Salmon and Brown Trout based on a small pilot dataset. Loci are grouped based on whether they have two or more differences between the two species, one difference between the two species, or no differences

Locus: Locus name

Allele Size AS: Range of allele sizes found in 13 Atlantic Salmon samples

Allele Size BT: Range of allele sizes found in 10 Brown Trout samples

Depth Ratio (AS/BT): Average number of reads in Atlantic Salmon samples divided by average number of reads in Brown Trout samples. Gives an idea of the relative amplification efficiency of the primers in each species

\# Alleles AS: Total number of different alleles found in 13 Atlantic Salmon samples

Observed Het AS: Observed heterozygosity at this locus in 13 Atlantic Salmon samples

\# Alleles BT: Total number of different alleles found in 10 Brown Trout samples

Observed Het BT: Observed heterozygosity at this locus in 10 Brown Trout samples

Mutations: Summary of non-repeat mutations found in Brown Trout alleles that were not present in Atlantic Salmon alleles

Mutation Region: The region (flanking or MRA) mutations were found in

Sequence Atlantic Salmon: The mutation region sequence found in Atlantic Salmon samples, with non-repeat mutations highlighted in red

Sequence Brown Trout: The mutation region sequence found in Brown Trout samples, with non-repeat mutations highlighted in red

