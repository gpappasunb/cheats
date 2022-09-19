# Navi cheats for bioinformatics

Collection of command line cheat sheets formatted for [navi: An interactive cheatsheet tool for the command-line](https://github.com/denisidoro/navi)

To [import](https://github.com/denisidoro/navi#cheatsheet-repositories) these into navi use:

    navi repo add https://github.com/gpappasunb/cheats 

To check where it was installed in your computer:

    navi info cheats-path

# Using navi

You have to search navi sheets using the following queries:

    navi -q bioinfo 
    navi --query bioinfo
    navi -q blast 
    navi -q fasta 
    navi --query gff 





## What are the commands available?

This is a partial list of the available cheats given the bioinformatics program categories:

### blast

* Execute blast against a database of choice

### fasta

Requirements: [SeqKit - Ultrafast FASTA/Q kit](https://bioinf.shenwei.me/seqkit/)

* Fasta from a subset of ids
* Subset a fasta by IDs in a file
* Fasta subsequence from range
* Subset a fasta by IDs using a regex 
* Subset a fasta by a GFF file
* Get the sequence ids
* Get the sequence full titles
* Count the number of sequences
* Index a fasta file
* Full path of fasta file

### gff

* filter GFF by gene feature type 
* filter GFF by selected feature types
* filter GFF by selected feature types
* Get the list of a specific attribute in GFF (9th column)
* GFF to BED

