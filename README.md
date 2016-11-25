# **Welcome to SQANTI: Structural and Quality Annotation of Novel Transcript Isoforms** #

 
###**What is SQANTI for?**###


SQANTI is a pipeline for the in-depth characterization of isoforms obtained by full-length transcript sequencing, which are commonly returned in a fasta file format without any extra information about gene/transcript annotation or attribute description. 

Although thought to be used for characterization of isoforms generated by long-read sequencing, SQANTI can be used for any set of transcript isoforms in fasta file format. Besides it can be applied to any organism.

SQANTI pipeline steps:

1. First, as long-read sequencing usually has a high rate of errors along sequences, SQANTI performs a **reference-based correction of sequences**.

2. Secondly, **generates genes models** and **computes a ORF prediction** for each isoform, obtaining information about the coding potential of each defined isoform. 

3. Finally it carries out a **deep characterization of isoforms at both transcript and junction level** and **generates a report** with several plots describing in detail the mayor attributes that catalog your set of sequenced-isoforms.

![Diapositiva1.png](https://bitbucket.org/repo/kpnA5g/images/69442998-Diapositiva1.png)


### Require software ###

* Python
* Perl
* Gmap aligner (version....)
* R environment


### Running ###





### What input files do I need? ###

SQANTI is a program written in python. These are its arguments:


```
#!bash
usage: squanti.py [-h] -g GTF -r REF [-o OUTPUT] [-d DIR] [-c COVERAGE]
                  [-f FASTA] [-s SITES] [-n]

Perform structural classificacion of sequenced full-length transcripts

optional arguments:
  -h, --help            show this help message and exit
  -g GTF, --gtf GTF     Input GTF file
  -r REF, --ref REF     Reference GTF file
  -o OUTPUT, --output OUTPUT
                        Prefix for output files
  -d DIR, --dir DIR     Directory for output files. Default: Directory where
                        the script was run
  -c COVERAGE, --coverage COVERAGE
                        Junction coverage files (comma-separated list of
                        SJ.out.tab files generated by STAR)
  -f FASTA, --fasta FASTA
                        Reference genome fasta file
  -s SITES, --sites SITES
                        Set of splice sites to be considered as canonical
                        (comma-separated list of splice sites). Default:
                        GTAG,GCAG,ATAC")
  -n, --name            Use gene_name tag from GTF to define genes. Default:
                        gene_id

```



 reference-based corrected transcriptome, a transcript-level annotation file containing several expression, structural and quality features, and a set of different summary descriptive plots for the entire dataset 

the predicted ORF sequences for PacBio sequences and two annotation files. The first one at transcript-level annotation and containing …orf predicted informantion, gene characterization, etc, and the second one at junction-level.

* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact