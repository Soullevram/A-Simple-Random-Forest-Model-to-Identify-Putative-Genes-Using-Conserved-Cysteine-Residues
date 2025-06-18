# A-Simple-Random-Forest-Model-to-Identify-Putative-Genes-Using-Conserved-Cysteine-Residues

## The Background
For genes under strong balancing selection (i.e. systems in which heterozygotes are favoured), hyper variability of gene sequences tend to occur. These genes also tend to be short (less than 100 amino acid residues). This can make identifying and annotating these regions incredibly difficult. That said, there are often conserved residues without which, the proteins don't function.

## The Data
The data contained 11 fasta files.

## The Problem
The fasta files provided represent a region of a genome approximately 20kbp in length. This region has been demonstrated to be under strong balancing selection. Somewhere within this region there is a short, protein coding gene (less than 150 amino acid residues). It is characterized by eight conserved cysteine residues. The aim is to identify putative regions within the sequences which may represent the gene of interest.
